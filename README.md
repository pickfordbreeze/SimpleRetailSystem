# Simple Retail System
C++ Inheritance, Polymorphism, and STL project. Completed 02/09/24

## Project Overview
This repo contains my impelmentation of a simplified online retail system, taking inspiration from an Amazon like platform. This project involves reading a database of products and users, handling searches, managing carts, and processing purchases. This project was created for a class assignment in spring 2024 on which I achieved a perfect score. 

### Features
- Product and User DB Management: Implements effient storage and retrival mechanisms for product characteristics (ex: name, price, attributes) and user info (ex: username, and credit amount).
- Interactive Search: Supports keyword-based product searchs with AND/OR logic, maps keywords to products without having to iterate over all entries.
- Shopping Cart Functionality: Lets users add products to cart, view their cart, and purchase items, making sure to check against stock availibility and user funds.
- Session Persistence: Allows saving the updated state of the db after transactions to reflect changes in quantities and user funds.

```
Skills demonstrated:
        Demonstrated ability in object-oriented design and programming in C++
        Advanced file I/O operations for db management
        Implemention of effient search algorithm
        Implementation of UI design for terminal based applications
        Effective memory management and debugging with Valgrind
        Proficient understanding and implementation of Makefiles for project complitation
```

#### File Organization
- amazon.cpp: Main application entry point, handles user interactions.
- datastore.h, user.h, product.h: Data models for users and products.
- db_parser.cpp, product_parser.cpp: Parsing utilities for loading database entries.
- util.cpp: Contains utility functions for string processing and set operations.
- mydatastore.cpp: Implements the core functionality of the retail system.
        
