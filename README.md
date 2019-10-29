# what framework did you pick and why?
Angular. Angular is a part of the JavaScript ecosystem and one of the most popular software development instruments today. 
## why?
1. Detailed documentation. Angular boasts detailed documentation where developers can find all necessary information without asking their colleagues. As a result, developers can quickly come up with technical solutions and resolve emerging issues. 
2. Support by Google. A lot of developers consider Google support another benefit of Angular, making the platform trustworthy. At ng-conf 2017, the developers of Angular confirmed that Google will support Angular on a long-term basis.
3. reat ecosystem of third-party components. The popularity of Angular has resulted in the appearance of thousands of additional tools and components that can be used in Angular apps. As a result, you can get additional functionality and productivity improvements.
4. Component-based architecture. In the second version, Angular shifted from an MVC to a component-based architecture. According to this architecture, an app is divided into independent logical and functional components. These components can easily be replaced and decoupled as well as reused in other parts of an app. In addition, component independence makes it easy to test a web app and ensure that every component works seamlessly.

# what about that framework appealed to you, for this project?
1. This project is a calculator application and this is a small web application. Angular is proper to small application. Also, angular is easy to develop. In addition, Angular is written using TypeScript language, which is basically a superset for JavaScript. It fully compiles to JavaScript, but helps spot and eliminate common mistakes when actually typing the code. While small JavaScript projects don’t require such an enhancement, the enterprise-scale applications challenge developers to make their code cleaner and verify its quality more often.Putting the TypeScript-first policy of Angular into the benefits section is an arguable point for many engineers. TypeScript-related complaints appear every now and then among the development community. AngularJS is a structural framework for dynamic web apps. It lets you use HTML as your template language and lets you extend HTML’s syntax to express your application’s components clearly and succinctly. Angular’s data binding and dependency injection eliminate much of the code you would otherwise have to write.
2. I think the biggest appeal to me for Angular over the others is the tooling. Tooling in Typescript and VSCode have been standardizing really nicely around Angular. Easy to learn
Perfect for Single Page Applications, Code less, get more functionality, Provided re-usability with the help of components. It is very friendly for beniggers.

# What alternative frameworks did you condider?
React. 
1. ReactJS is an open-source JavaScript library which is used for building user interfaces specifically for single page applications. It’s used for handling view layer for web and mobile apps. React also allows us to create reusable UI components. React allows developers to create large web applications which can change data, without reloading the page. The main purpose of React is to be fast, scalable, and simple. It works only on user interfaces in application. This corresponds to view in the MVC template. It can be used with a combination of other JavaScript libraries or frameworks, such as Angular JS in MVC.In React, instead of using regular JavaScript for templating, it uses JSX. JSX is simple JavaScript which allows HTML quoting and uses these HTML tag syntax to render subcomponents. HTML syntax is processed into JavaScript calls of React Framework. We can also write in pure old JavaScript.
2. virtual document object model
React creates an in-memory data structure cache which computes the changes made and then updates the browser. This allows a special feature which enableprogrammer to code as if whole page is render on each change where as react library only render components which actually change.

# what resources did read/watch/listen to?
[https://angular.io/start](https://angular.io/start)
[https://www.edureka.co/blog/angular-tutorial/](https://www.edureka.co/blog/angular-tutorial/)
[https://www.youtube.com/watch?v=KhzGSHNhnbI](https://www.youtube.com/watch?v=KhzGSHNhnbI)
[https://www.javatpoint.com/angular-8](https://www.javatpoint.com/angular-8)
[https://medium.com/@cyrilletuzi/angular-is-easy-99797928e705](https://medium.com/@cyrilletuzi/angular-is-easy-99797928e705)
[https://www.c-sharpcorner.com/UploadFile/6ade65/what-are-the-advantages-of-using-angularjs-over-jquery/](https://www.c-sharpcorner.com/UploadFile/6ade65/what-are-the-advantages-of-using-angularjs-over-jquery/)
[https://reactjs.org/docs/getting-started.html](https://reactjs.org/docs/getting-started.html)
[https://reactjs.org/tutorial/tutorial.html][https://reactjs.org/tutorial/tutorial.html]
[https://reactjs.org/docs/hello-world.html](https://reactjs.org/docs/hello-world.html)
[https://www.npmjs.com/package/react-youtube](https://www.npmjs.com/package/react-youtube)

## Describe your project. What does it do? What components or features of the framework did you explore for this project?
It is a simply calculator application. In the web page designed, there are number buttons and operator buttons. The color is different between number buttons and operator buttons. The application contains a component named cal to encapsulate the calculator view and logic. There are three part in the cal component, cal.component.css for css styles, cal.component.html for the component's template or the vies and component.ts. The selector in cal.component.ts allows me to give the component a tag name that can be used to reference the component from other templates just like standard HTML tags. The templateUrl in cal.conponent.ts points to the HTML template that renders the view of the component. The styleUrls allow me to associate one or more multiple stylesheets to my component. In addition, I use data binding in the template to make communication between the component and its view. Event binding: data flows from the dom to the component. When a dom event, such as a click,  is triggered, the bound method from the component is called.
