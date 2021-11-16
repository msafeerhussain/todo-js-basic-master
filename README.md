Basic JavaScript ToDo App
======
Vanilla (**JavaScript**)-only

## Synopsis

Just a basic todo app that I wrote using vanilla **JavaScript** so there's not much to it.

## Code Example

```
var taskCompleted = function() {               // Mark a task as complete
  var listItem = this.parentNode;              // We assign it for readability
  completedTasksHolder.appendChild(listItem);  // Append the task list item to the #completed-tasks
  bindTaskEvents(listItem, taskIncomplete);    // We bind it to the opposite holder
};
```

## Motivation

Learning and enforcing good structural and practical **strategies** for JavaScript development.

### Directory Layout

```
.
├── /css/                # CSS folder
│   └── /style.css       # Basic CSS stylesheet
├── /js/                 # JavaScript folder
│   └── /app.js          # Main app source
├── .gitignore           # Version control omission file
│── index.html           # Main entry point
└── README.md            # This file
```

## Installation

Checkout this repo and open index.html:

```
	> git clone git@github.com:Bartekus/todo-js-basic.git
	> cd todo-js-basic
	> open index.html
```

## Usage

Use to add/edit/delete tasks without persistence (no backend).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

0.1.0 Finalized the example

## Tests

Basic non-automated manual browser test aka no test :P

## Contributors

Standing on the shoulders of all the giants before me.

## Contact

* E-mail: msafeerhussain13@gmail.com

