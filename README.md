<p align="center">
<img src="https://user-images.githubusercontent.com/5693916/30330868-8071b3da-97d6-11e7-8207-99243d19f1fe.png" data-canonical-src="https://user-images.githubusercontent.com/5693916/30330868-8071b3da-97d6-11e7-8207-99243d19f1fe.png" width="100" height="100" />
<img src="https://user-images.githubusercontent.com/5693916/30366646-10dc3b30-986c-11e7-871a-4f5c237b9a6f.png" data-canonical-src="https://user-images.githubusercontent.com/5693916/30366646-10dc3b30-986c-11e7-871a-4f5c237b9a6f.png" width="100" height="100" />
</p>

## Assignment

### Goal
The goal of this assignment is to have the candidate work with the same tools that are used in every-day Chama web development, so we can learn how one would perform while solving common development tasks that we have.

### Description
For this assignment, you are supposed to build a CRUD-complete **to-do list**, persisted on the user's machine.

### Stack
At Chama, our frontend stack consists of [React](https://facebook.github.io/react/docs/hello-world.html) + [Redux](http://redux.js.org/) :heart:

You are required to use that same stack in this assignment.

Complementary libraries are permited e.g. lodash, provided that we are able to check how you code using React and Redux.

To speed things up, you can use CRA to bootsrap your app. The architecture CRA generates can be used or discarted, either way you'll have to be able to explain your final solution.

### Firebase (optional)
Chama also uses [Firebase](https://firebase.google.com/) to give our dealers a real-time experience. You'll get extra points if you are able to proper host, authenticate and/or provide a real-time experience using Firebase.

**This is totally optional**, so we recommend that it is the last things you try to do - preferentially in a separated branch, which will be merged to your master if you manage to make it work.

If you're not experienced with this kind of stuff and want to give it a shot, you can create an account in their free-plan with your own Goolge account.

### Layouting the app
Don't invest too much on a beautiful visual because in real-life at Chama it would be handed out to you - as a front-ender here you would be able to suggest changes, of course.

But put energy on using good HTML and CSS, it can be vanilla or pre-processed.

### Must have
- [ ] Assign priority to a TO-DO and sort them by **highest to lowest priority**;
- [ ] Set a due time. Add real-time visual and auditive hints to the TO-DO item that indicate that the due time is near and has passed;
- [ ] Nice usability;
- [ ] Nice stylesheet and a nice layout out of it;
- [ ] Work on Chrome.

### Nice to have
- [ ] Sign-in/Sign-out functionality using [Firebase Auth](https://firebase.google.com/docs/auth/);
- [ ] Use **[Firebase Realtime Database](https://firebase.google.com/docs/database/)** linked to **Redux** to keep all the TO-DO's;
- [ ] Optimistic response when dealing with firebase;
- [ ] Host your working app on the *[Firebase Hosting environment](https://firebase.google.com/docs/hosting/)*;
- [ ] Unit tests;
- [ ] Aceptance tests;

## Instructions
Create a new repo into your favorite git platform (github, bitbucket, etc), copy this README into it. You're free to edit it, though it should preserve the must-have functionalities and stack.

**After you finished, you can share the repository URL with us (preference) or just send us a .zip containing the source code.**

When you're done, share your repositoy's and Firebase hosting's URL.

## Review

After you delivered the completed assignment to us, we will review it as soon as we can, generally within 3 days. **We pay special attention to:**

* Coding skills
   * Writing testable code	
   * Whether you use Redux, React, HTML and CSS properly
* Software Engineering Skills
   * Code organization (modularity, dependencies between modules, naming, etc)
* Overall Feeling
   * Software usability
   * Assignment completion
   * Overall code quality (edge cases, usage of tools, performance, best practices)
   
## Presentation

If we like what we see, we'll invite you to present your solution! We have a big screen for you to present on. Don't forget your laptop!

## Hints
* You don't need to spend time creating a dev/build environment, using [react-create-app](https://github.com/facebookincubator/create-react-app) (and other alike tools) is totally ok!
* Never done anything with Firebase? You can follow [this guide](https://firebase.google.com/docs/web/setup) and it should give you a nice starting point.
* If you wish to spend less time writing boilerplate code, go to http://todomvc.com/, on this website, you will find many sample implementations of the same TO-DO application, every time using a different framework. You can choose the [React](http://todomvc.com/examples/react/#/) implementation as a starting point. It's OK to use the same styling as the original application.
* Don't need to re-invent the wheel, for components like Datepickers and/or Timepicker you can use [Material-ui](https://github.com/callemall/material-ui) or any other of your choice, it has great integration with React environments.
* This is a test of your skills (mainly) with React, Redux and Firebase. Though we allow third-person libraries, keep in mind that we need to read some code of yours with those tools, so you should avoid not writing code which touches them.
* As a company, we believe that communication is the key to success. So if something is not clear to you, or if you have doubts on what you can use, reach the devs.
* Threat this project as if it would continue working on this after your assignment: maintainability, scalability, and readability are super important

## That's it!

Happy coding! :metal:

<img src="https://user-images.githubusercontent.com/5693916/30273942-84252588-96fb-11e7-9420-5516b92cb1f7.gif" data-canonical-src="https://user-images.githubusercontent.com/5693916/30273942-84252588-96fb-11e7-9420-5516b92cb1f7.gif" width="150" height="150" />
