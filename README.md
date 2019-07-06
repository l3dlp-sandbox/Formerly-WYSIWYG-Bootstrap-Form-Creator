# Formerly: A WISYWIG Bootstrap Form Creator
This tool allows easy, detailed creation and customization of Bootstrap Forms.

Table of Contents:
------------------
- Features
- Specs
- File Structure
- Contribute
- Support

Features
--------
Formerly is meant to be useful to both the novice developer/employee needing to quickly make a form, or the developer that would like to be able to make more specific choices with their forms, like changing attributes and aria-controls. Formerly can/allows users to:
- Create forms within seconds using the left toolbar
- Offers almost every form input type available to Bootstrap 4:
  - Text input fields
  - Checkboxes
  - Radio Buttons
  - Select Fields
  - Multiple Select Fields
  - Text Areas
- Drag and drop created form elements
- Edit the background color and text size/weight of form elements
- Generate usable HTML of created forms
- Save and delete created forms

Technologies
------------

Formerly's frontend was created with **HTML**, **CSS**, **JavaScript**, **jQuery**, and of course, **Bootstrap 4**.
Its backend was created with **Ruby On Rails**. Gems used include:
 - Better Errors - I strongly prefer this gem to the default errors GUI that comes with Rails.
 - Devise - For users and user authentication.

Contribute
----------

If you would like to contribute to this project, feel free to read through the **File Structure** section to get an idea of where everything is, and take a look at the "Issues" tab. I plan on building a suite of similar apps assiting in the ease of use and customization of bootstrap in the future, so be sure to follow this account for updates if this is something that interests you.

File Structure
--------------

**Bootstrap 4** and **jQuery** have been imported via CDN.
  - **bootstrap-form-creatorJS/**
    - **js/** 
      - **addInputs.js** -> All logic for adding and deleting each kind of input.
      - **formChanges.js** -> Logic for populating "Copy Your HTML" modal and changing form background color.
    - **css/**
      - **style.css** -> All custom styles not included with Bootstrap 4.
    - **index.html** -> All markup for the app.
    
 For a more in-depth explanation of Formerly's file structure, take a peek at the wiki.

Support
-------

If you are having any issues with the app, please let me know!
I can be contacted at kaylathomas.dev@gmail.com

License
-------

The project is licensed under the BSD license.