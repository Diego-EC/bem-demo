# bem-demo
- This is a simple demo of how to use BEM convention for styling.
- BEM stands for Block, Element, and Modifier. It's a CSS naming convention for writing cleaner and more readable CSS classes. BEM also aims to write independent CSS blocks in order to reuse them later in your project.
- Tutorial: https://youtu.be/YaAkV--25fg
- Convention detailed rules :http://getbem.com/naming/

&nbsp;
## Naming
### Block
- Encapsulates a standalone entity that is meaningful on its own.
- ie: Header, Nav, Form, Footer, Container
### Element
- Parts of a block and have no standalone meaning. Any element is semantically tied to its block.
- **block__elemnet**
- ie: form__input, nav__link
### Modifier
- Flags on blocks or elements. Use them to change appearance, behavior or state.
- **block__elemnet--modifier** / **block--modifier**
- ie: nav__link--disabled

&nbsp;
## Notes
- If I have a child inside an element, I can name it as an element.
![alt text](https://github.com/Diego-EC/bem-demo/blob/master/readme-img/bem1.PNG?raw=true)
- A tag can have more than one class of a block (mix in BEM).
![alt text](https://github.com/Diego-EC/bem-demo/blob/master/readme-img/bem2.PNG?raw=true)
- Global modifiers cannot be used.  
![alt text](https://github.com/Diego-EC/bem-demo/blob/master/readme-img/bem3.PNG?raw=true)
- In the CSS file the modifiers always go after the element to modify, because of the cascade, otherwise it does not work.  
![alt text](https://github.com/Diego-EC/bem-demo/blob/master/readme-img/bem4.PNG?raw=true)
