# CS2613: De,Aritra Library Experience Exploration Activity 2


# Question and Answers (included below)

## Table of Contents
- [Introduction](#introduction)
- [Questions related to Library Experience](#questions)

## Introduction
This document provides my overall experience with React library and answers the provided qusetions.

## Questions

### General Questions
<details>
<summary>Which package/library did you select?</summary>
<p>

- I used the React library for Javascript. 

</p>

</details>

<details>
<summary>What is the package/library?</summary>
<p>

- React is a free and open-source front-end JavaScript library for building user interfaces based on components
- React can be used as a base in the development of single-page or mobile applications, as it's optimal for fetching rapidly changing data that needs to be recorded in the user interface.
</p>
</details>

<details>
<summary>What purpose does it serve?</summary>
<p>
  
- React served the purpose of helping me develop the calculator user-friendly interface and observe dynamic upadtes on every test run.
- I liked the fact that React allows developers to create interactive user interfaces using a declarative approach. This means that I described the UI state, and React had taken care of updating the components when the data changed, leading to more predictable and easier to understand code. This makes the user experience smoother and more responsive.
- I had utilized the React's useReducer hook for state management, which is particularly useful for complex state logic that involves multiple sub-values or when the next state depends on the previous one. The useReducer hook was the alternative option for useState usage.

</p>
</details>

<details>
<summary>How do you use it?</summary>
<p>
- First things first, I initialized my react environment and checked dry runs.
- In accord to my source code, I used it primarily for the functional implementation of my calculator.
- After that I created the calculator grid and checked whether it is being displayed as per my design specifications.
  In this process, I also updated the styles.css file to reflect my preferred colour tone for the calculator.
- After creating the main application design, I added functionality to the buttons. 
- My function handled events and specially created the new function reducer to create the use-reducer hook.
- References for use-reducer hook:
    [https://www.w3schools.com/react/react_usereducer.asp]
    [https://react.dev/reference/react/useReducer]
- I sequenced the operands and placed them internally in the grid to reflect changes.
- I felt React supported my testing needs and allowed me to effeciently catch errors. I liked the fact that the errors were very transparent and clearly mentioned on the screen.
- I was also able to make personal adjustments to the blocks.

</p>
</details>

<details>
<summary>What are the functionalities of the package/library?</summary>
<p>
- React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.
- React handles everything that happens on the server side. It has a significant impact on front-end development, with thousands of sites already operating on it. This enables ReactJS developers to create versatile web apps with dynamic data that can work without reloading the page.
- React has mainly two components i.e. Function components and Class components:

  1. Functional Components
  When dealing with React, functional components are some of the most popular components you'll come across. These are nothing more than      JavaScript functions. By writing a JavaScript function, we can create a functional component for React. Data may or may not be passed as    parameters to these functions. The return value in functional Components is the JSX code to render to the DOM tree.

  2. Class Functions
  The class components are more difficult to understand than the functional components. Your program's functional components are oblivious    of each other, whereas the class components can collaborate. To create class-based components in React, we can use JavaScript ES6       
  classes. Information can be sent from one class component to another. The following React example shows a valid class-based component:

You can read more here: [https://www.microverse.org/blog/introduction-to-reactjs-a-guide-for-beginners]

- While handling internal data, I used props, but there are two types of data in React: props and state.
  The key difference is that the state is private and can be changed from within the component itself. Props are external, and not 
  controlled by the component itself. It’s passed down from components higher up the hierarchy, who also control the data.

A component can change its internal state directly. It can not change its props directly.
   - References for some good code in Tkinter:
    [https://realpython.com/tic-tac-toe-python/]
   - This reference is very helpful.
     [https://www.tutorialsteacher.com/python/create-gui-using-tkinter-python]
   
- This image below illustrates the main advantages and disadvanatges of React.
Reference: [https://www.simplilearn.com/tutorials/reactjs-tutorial]
<img width="676" alt="Screenshot 2024-02-26 at 5 54 20 AM" src="https://github.com/CS2613-WI24-FR01B/exploration-activity-2-aritrade001/assets/114476308/1137e6e3-1452-47a6-aa08-afd348de0891">

- Main Real Life Uses of React are:
  Facebook: As the company that created React, Facebook uses it extensively for news feeds and comments.

  Instagram: Provides smooth, dynamic user experience for its photo-sharing platform.

  Airbnb: To build and manage its user interface, enhancing the user experience for renting and booking accommodations.

  Netflix: Uses for fast, interactive user interfaces. I definitely wouldn't like my movie to start buffering during the climax scene. 

  WhatsApp Web: Provides responsive location sharing tools.

  Many other applications in the world use it competitively to enjoy advantages like lightweight architecture, effeicient testing process,    component based modelling etc.

</p>
</details>

<details>
<summary>When was it created?</summary>
<p>
  
- React was created by Jordan Walke, a software engineer at Facebook. It was first deployed on Facebook's news feed in 2011 and later on Instagram in 2012. React was open-sourced at JSConf US in May 2013. 

</p>
</details>

<details>
<summary>Why did you select this package/library?</summary>
<p>
- I selected this because it helped me as a beginner to explore the library and it is easy to test and functionally learn how to deploy the functional specification of my calculator. 
- React's rich ecosystem, including a wide range of development tools and reusable components, can speed up the development process. 
- I utilised the component based architecture, and the calculator needs a declarative UI to handle multiple user input change requests.
- The standard library is also under javascript, so it does not make me worry about external installs.
</p>
</details>

<details>
<summary>How did learning the package/library influence your learning of the language?</summary>
<p>
- It was compatible with javascript and helped me practice the core function concepts specially.
- It helped me research how to use the use-reducer hook.
- After every change, I ran the module to check my progress and this also helped me catch errors and debug the code accordingly.
- This project really gave me a sense how React can be used to handle large scale system requests.
  
</p>
</details>

<details>
<summary>How was your overall experience with the package/library?</summary>
<p>
- My overall experience with the package/libary was outstanding because I enjoyed the rich features of this library.
- I would definitely developers to make interesting projects using this library.
- I plan to use this library in my future possibly to create a day-to-day planner for watering my plants. I felt that there is great range 
  of manual customization possible in the library and the code can also be encrypted using secure packages. Supports containerization 
  priciples and I would once again boast about it's declarative UI capabilities and event handling performance metric.
</p>
</details>





## Asking Questions
If you have a question that's not listed, please:
- Check the existing [issues](#) to see if it has already been asked.
- If not, create a new issue and provide as much detail as possible to help others understand your question.

## Answering Questions
If you can answer a community question:
- Provide clear, concise, and helpful responses.
- Reference relevant parts of the documentation or code.
- Include examples or links to more information if possible.

## Contributing
Your contributions to improving this Q&A are welcome! Make sure to follow our contribution guidelines. This project was a result of extensive research over the internet and youtube. One could face issues if he/she wants to trace back to the historical data, and therefore needs to keep data registers handy to note down results of interest.
