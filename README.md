rsschool-cv
# Aleksandr Volkov
## Junior Frontend Developer
### Contact information:
Phone: +7 926 560 06 70

E-mail: volsash@mail.ru

Telegram: @volsashgeo

Briefly About Myself:

Having started my career as a layout designer in a local newspaper with minimum skills, I became profficient in printing design.
My keen interest in printing technologies led me to working as a Prepress and DTP Engineer in the largest printing house in my city,
where I continued self-learning, examining the process of creating wine and food labels, magazines and other printed goods.

Three years ago I’ve become passionate about retouching. I’ve mastered different retouching techniques,
learned to work with graphic tablet, become an advanced Photoshop user and found my first job as a retoucher.

Remote work as a retoucher gives me extra free time, which I spend learning Frontend Development.
I’m interested in Web Development because this occupation provides endless possibilities for professional growth,
besides there’s a huge amount of free high quality resources for self-education and a large community of developers.

I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.

Skills and Proficiency:
HTML5, CSS3
JavaScript Basics
Git, GitHub
VS Code


Code example:

Check to see if a string has the same amount of 'x's and 'o's. The method must return a boolean and be case insensitive. The string can contain any char.

Examples input/output:

XO("ooxx") => true

XO("xooxx") => false

XO("ooxXm") => true

XO("zpzpzpp") => true // when no 'x' and 'o' is present should return true

XO("zzoo") => false



       function XO(str) {
            let arr = [];
            for (j = 0; j < str.length; j++) {
                arr.push(str[j]);
            }
            let countX = 0;
            for (i = 0; i < arr.length; i++) {
                if (arr[i] == 'x' || arr[i] == 'X') {
                    countX += 1;
                };

            }
            let countO = 0;
            for (i = 0; i < arr.length; i++) {
                if (arr[i] == 'o' || arr[i] == 'O') {
                    countO += 1;
                };

            }
            if (countX==countO || (countX==0 && countO==0)) {
                return true
            }else {
                return false
            }
    }
Courses:
HTML and CSS Tutorials on the w3schools (completed)
W3Schools Score
JavaScript Manual on learnjavascript.ru (in progress)
RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

Languages:

English - Intermediate/Upper-intermediate 

Russian - Native



