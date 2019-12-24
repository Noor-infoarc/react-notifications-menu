# cb-react-notifications

> A React Component used to render notifications with default styles and also allows to customize entire notification component
> by providing necessary props and styles.

[![NPM](https://img.shields.io/npm/v/cb-react-notifications.svg)](https://www.npmjs.com/package/cb-react-notifications) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

|                                                       Default                                                       |                                                     Customized                                                     |
| :-----------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: |
| <img src="https://github.com/NaveenrajV/cb-react-notifications/blob/master/src/assets/default.gif" height="320px"/> | <img src="https://github.com/NaveenrajV/cb-react-notifications/blob/master/src/assets/okrjoy.gif" height="320px"/> |

## Getting Started

### Install

Install using npm or yarn

```bash
npm install --save cb-react-notifications
```

or

```bash
yarn add --save cb-react-notifications
```

### Adding to project

Just import the default Notifications component from the package and use the component in project.

```jsx
```

## Basic Usage

```jsx
import Notifications from "cb-react-notifications";

const Example = () => {
  return (
    <Notifications
      renderItem={CustomComponent}
      classNamePrefix="okrjoy"
      displaySeeAll={false}
    />
  );
};
```

To know more, visit [cb-react-notifications](/) docs
