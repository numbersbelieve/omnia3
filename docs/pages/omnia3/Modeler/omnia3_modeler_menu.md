---
title: Application Menu
keywords: omnia3
summary: "Modeling Application Menu"
sidebar: omnia3_sidebar
permalink: omnia3_modeler_menu.html
folder: omnia3
---


## 1. Introduction

Each model has an Application Menu definition that will be available in the Application, exposing the options to the user.
The menu can be customized or you can leave to the Platform the responsibility of generating a proposal at Build time.

In case of a customized Application Menu, a new menu entry will be automatically added to the menu root when a new Entity or Dashboard is created.

It's only possible to have one menu in the Application.



## 2. How to customize a Menu?

*Before you start, make sure that you have at least one successful build of your model. The customization is based on the menu proposed at build time.* 

 
By accessing **_Menu_** in the sidebar, you will have access to the Menu modeling screen.


A Menu is a hierarchical structure defined by nested menu entries.
Each Menu Entry is defined by:
* **Name**: the entry name (should be unique in a menu);
* **Label**: the element caption;
* **Row**: the layout row in which the element will be placed;
* **Column**: the layout column in which the element will be placed;
* **Size**: the element size on a scale of 1 (the smaller size) to 12 (the bigger size);
* **This entry is a**: the menu entry type. The type defines which action should happen when the user clicks;
* **Icon**: You can consult the available icons at [Font Awesome version 4.7.0](https://fontawesome.com/v4.7.0/);
* **Callout color when hovering**: color to display when hovering the menu entry;
* **Is the element hidden?**: the visibility of the element (hidden or visible);

