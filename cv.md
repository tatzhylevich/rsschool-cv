### My CV

Tatsiana Zhylevich
========================

## My contacts: 

* **E-mail:** <tatzhilevich@gmail.com>
* **Phone:** +375336505640
* **GitHub:** <https://github.com/tatzhylevich>

## About me:

I have been working as a chemical engineer for 9 years. I always open to something new and ready to work on myself. And I love to travel even more, I have already visited 17 countries


## Skills

* Git
* HTML
* CSS/SASS
* JavaScript
* React
* Redux
* VS Code
* Adobe Photoshop, Figma


## Code example

        buttonArrowRight.addEventListener('click', function(event) {
          if (buttonArrowRight.className === 'arrow-right'){
            //    ограничение по количеству задач в процессе
                if(taskInProgress.children.length < 5){
                    taskInProgress.append(task);
                    buttonArrowRight.classList.remove('arrow-right');
                    buttonArrowRight.classList.add('arrow-right-in-progress');
                }else{
                    modal[2].style.display = 'block';
                    overlay.style.display = 'block';
                }  
                } else if(buttonArrowRight.className ===            'arrow-right-in-progress'){
                    taskDone.append(task);
                    buttonArrowRight.classList.remove('arrow-right-in-progress');
                    buttonArrowRight.classList.add('arrow-left');
                }else {
                    taskListTodo.append(task);
                     buttonArrowRight.classList.remove('arrow-left');
                    buttonArrowRight.classList.add('arrow-right');
                }
        })


## Courses

* JavaScript Manual on [LearnJavascript](https://learn.javascript.ru/)
* course Frontend developer TeachMeSkills 


## Languages

* Russian (native)
* Belarussian (native)
* English (intermediate)
* Ukrainian (intermediate)
* German (Basic)
* Polish (Basic)