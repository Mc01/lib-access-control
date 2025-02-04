# Lib Access Control

## Installation
```
npm i git+https://github.com/Mc01/lib-access-control.git
```

## Usage

Import and use directly in your Diamond Proxy:
```
// create admin user
LibAccessControl.createAdmin(msg.sender);

// grant specific role
LibAccessControl.grantRole(role, msg.sender);
```
