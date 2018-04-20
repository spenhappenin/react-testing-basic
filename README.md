# ReduxSimpleStarter

Interested in learning [Redux](https://www.udemy.com/react-redux/)?

### Getting Started

There are two methods for getting started with this repo.

#### Familiar with Git?
Checkout this repo, install dependencies, then start the gulp process with the following:

```
> git clone https://github.com/StephenGrider/ReduxSimpleStarter.git
> cd ReduxSimpleStarter
> npm install
> npm start
```

#### Not Familiar with Git?
Click [here](https://github.com/StephenGrider/ReactStarter/releases) then download the .zip file.  Extract the contents of the zip file, then open your terminal, change to the project directory, and:

```
> npm install
> npm start
```

NOTES: 

- "describe" is used to convey to other developers that certain number of tests are related in some fashion.
- "it" blocks try to make an assertion about a very particular fact about the test subject.
- "expect" is used to make a single assertion about a target.

<!-- Use 'it' to test a single attribute of a target -->
it('shows the correct text', () => {

  <!-- // crate an instance of App -->
  const component = renderComponent(App);

  <!-- Use 'expect' to make an 'assertion' about a target -->
  expect(component).to.contain('React simple starter');

});
