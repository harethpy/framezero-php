# FrameZero: Frameless Framework-like PHP Library

[![PHP](https://img.shields.io/badge/php-%3E%3D7.2-8892BF.svg)](https://php.net/)

## Introduction
Without the restrictions and limitations frequently connected with conventional frameworks, FrameZero is a PHP library made to give developers the power and flexibility of a framework. With a wide selection of utility classes and components available, it enables highly adaptable and effective development, enabling developers to create reliable and scalable applications.

FrameZero will adapt to your code instead of you adapting to it

## Features
- **Modularity**: FrameZero has a modular architecture enables you to pick and choose which elements to use based on the requirements of your application. As a result, you are free to design the structure of your application without being constrained by a predetermined framework structure.

- **Performance**: FrameZero is designed to be highly optimized and performant, ensuring your applications run smoothly and efficiently even under heavy loads.

- **Frequently Updated**: FrameZero is actively maintained and updated on a regular basis to incorporate new features, improvements, and bug fixes as well as ensure compatibility with the most recent versions of PHP. Although it is open-source but any development hinders shall be noted here.
## Functions

- [ ] Encryption & Decryption 
- [ ] User Authentication
- [ ] Database Handling
- [ ] Database Easy Queries
- [ ] Error Handling
- [ ] Validations
- [ ] Logging & Debugging
- [ ] URL Handling


## Getting Started
Plug-and-Play, after installing the library properly. you can load it.

FrameZero offers tracing as well to see what is being executed in the code.  
**Note: Tracing and Debugging can lead to slower performance**
```php
include 'lib/framezero/main.php'

fz::load();
// <-- Your code -->

fz_request:set_debug(true); // allow debugging in fz_request class
fz_request:set_tracing(true); // allow tracing in fz_request class

if(fz_request::request('post', 'form_name')) // Handle request in POST Type, with form name
{
}
```

## Documentation

For detailed usage instructions and examples, please refer to the [FrameZero Documentation](https://your-documentation-link).
