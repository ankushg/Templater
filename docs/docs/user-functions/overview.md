---
title: Overview
slug: /user-functions
---

You can define your own functions in Templater.

There are two types of user functions you can use:

- [Script User Functions](user-functions/script-user-functions)
- [System Command User Functions](user-functions/system-user-functions)

## Invoking User Functions

You can call a user function using the usual function calling syntax: `tp.user.<user_function_name>()`, where `<user_function_name>` is the correct user function name. 

For example, if you defined a system command user function named `echo`, a complete command invocation would look like this:

```javascript
<% tp.user.echo() %>
```