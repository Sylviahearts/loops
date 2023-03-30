# loops
Q. What is the Event loop ?
ans-  The event loop is a mechanism that allows JavaScript to handle events and perform long-running tasks without blocking the main thread. It works by continuously monitoring the event queue and executing any pending callbacks when an event is triggered. The event loop is responsible for executing code in response to user input, network requests, and other events.


Q. Explain the 6 phases of the event loop
ans-  1.  Script Loading: This phase begins when the HTML page is loaded and all the scripts are loaded and parsed.
2.  Callback Queue: This phase consists of a queue of functions that are waiting to be executed. These functions are added to the queue by event handlers, timers, and Ajax requests.
3.  Event Loop: The event loop is the core of the event-driven architecture. It is responsible for checking if there are any functions in the callback queue that need to be executed. If there are, it will execute them one at a time in a FIFO (First In First Out) order.
4.  Polling: During this phase, the event loop will check for any new events that have occurred since the last iteration of the loop and add them to the callback queue if necessary.
5.  Checking: During this phase, the event loop will check for any timers or intervals that have expired and add their associated callbacks to the callback queue if necessary.
6.  Idle: When there is nothing left in either the callback queue or polling queue, then the event loop enters an idle state until something new comes up that needs to be processed by it.


Q. List some best practices in server-side code development
ans-  1. Use secure coding techniques to prevent security vulnerabilities.
2. Use proper error handling techniques to gracefully handle errors.
3. Follow a coding standard such as PSR-2 or another popular standard.
4. Test your code thoroughly before deployment, and use automated tests where possible.
5. Utilize a version control system like Git to track changes and collaborate with other developers.
6. Use an automated build process, such as Grunt or Gulp, to ensure consistent builds across environments.
7. Separate logic from presentation in your code and use templating languages where possible to keep code clean and maintainable over time.
8. Use dependency management tools like Composer or NPM to manage third-party libraries and packages your application needs to function properly.
9. Utilize a server-side caching solution like Redis or Memcached to improve performance of database queries and other expensive operations in your application codebase


Q.What is NPM5: How do you initialize a package in npm
ans-  NPM5 is the fifth major version of the Node.js package manager,
 To initialize a package in npm, you can use the command "npm init". This will create a package.json file in your current working directory. The package.json file contains information about the project, including its name, version, dependencies, and other configuration data.
 
 
 
Q. How do you run a script in the package.json ?
ans-  To run a script in the package.json, you can use the npm command line tool. For example, if you have a script called "start" defined in your package.json file, you could execute it with the following command:
npm run start
