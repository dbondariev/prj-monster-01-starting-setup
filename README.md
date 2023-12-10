# Vue Basics

This is a basic Vue.js project that demonstrates some of the fundamental concepts of Vue.js.

## You can view the demo of this project here : [Demo](https://dbondariev.github.io/prj-monster-01-starting-setup/)

## Installation

To install the project, follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/vue-basics.git`
2. Navigate into the directory: `cd vue-basics`
3. Install the dependencies: `npm install`

## Usage

To run the project, use the following command: `npm run serve`

## Features

This project includes:

- Data Properties: The data function returns an object that contains the initial state of the application. This includes the health of the player and the monster, the current round, the winner, and an array of log messages.

- Computed Properties: These are functions that return a value based on the application's state. In this case, monsterBarStyles and playerBarStyles return an object that sets the width of the health bars based on the health of the monster and the player, respectively. mayUseSpecialAttack returns a boolean indicating whether the player can use a special attack.

- Watchers: These are functions that are called when a data property changes. In this case, playerHealth and monsterHealth watchers check if the player or the monster has lost all their health and sets the winner accordingly.

- Methods: These are functions that can be called from the Vue.js template. They include startGame, attackMonster, attackPlayer, specialAttackMonster, healPlayer, surrender, and addLogMessage.

- Mounting the Vue.js Application: The app.mount("#game") line of code mounts the Vue application to an HTML element with the id of game.

- The core Vue.js concepts used in this application are:

- Reactive Data: Vue.js automatically tracks the properties an application depends on and re-renders the application when those properties change.

- Computed Properties: These are used to calculate a value based on the application's state. They are cached and only re-computed when their dependencies change.

- Watchers: These are used to perform side effects when a data property changes.

- Methods: These are used to handle events in the Vue.js template.

- Vue Instance: The Vue application is created as an instance of the Vue class.

- Mounting: This is the process of inserting the Vue application into the DOM.

- Directives: Although not explicitly shown in the provided code, Vue.js uses directives (special attributes) in the template to apply special reactive behavior to the DOM. Examples include v-if, v-for, v-bind, and v-on.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

