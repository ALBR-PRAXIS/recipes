Xamarin Recipes
===============

Recipes for completing simple tasks with Xamarin products.

Contents
---------

What is a recipe and how does it differ from other types of documentation? 
--------------------------------------------------------------------------
 
At Xamarin we are passionate about empowering developers to make beautiful cross-platform apps and having great education is one way in which we do that. We also realize that everyone learns in a different way–some prefer classes and videos, some prefer to get hands on with samples, and some prefer to read. That's where recipes come in. We have two types of guides available at Xamarin, conceptual guides and recipes. As you can see from the linked examples conceptual guides are long-form articles that cover various topics in depth, they explain the _why_ as well as the _how_. In contrast, recipes tend to be much shorter. **They usually only explain the _how_, through a mixture of step-by-step points, screenshots, and code blocks.**

Code of Conduct
---------------

This project uses the [Microsoft Open Source Code of Conduct](https://github.com/xamarin/recipes/blob/master/code-of-conduct.md).

For more information see the Code of Conduct FAQ or contact opencode@microsoft.com with any additional questions or comments.

License
-------

The MIT License applies to all recipes in this repository.

Contributing
============

Thank you for taking the time to contribute, we appreciate your help in helping the Xamarin community to learn and grow! All content submitted **must** be your own work.

The information below will guide you through the organisation of this repository and will advise of the structure needed for naming folders, and how your recipe directory should be organised.

Please also visit the articles in the [Contibutor guide](https://github.com/xamarin/recipes/tree/open-recipes/contributor-guide), which will give detailed and practical help with the following:

* [Content Layout](https://github.com/xamarin/recipes/blob/open-recipes/contributor-guide/content-layout.md)
* [Style Guide](https://github.com/xamarin/recipes/contributor-guide/style-guide.md)
* [Markdown and metadata](https://github.com/xamarin/recipes/contributor-guide/markdown-and-metadata.md)
* [Templates](https://github.com/xamarin/recipes/contributor-guide/recipe-templates)

Repository Structure
---------------------

All recipes are contained within with `\recipes` directory. The structure follows the organization of recipes on https://developer.xamarin.com/recipes/, splitting content into Platform, General topic, and then providing the recipe. For example, the recipe at this location: (https://github.com/xamarin/recipes/recipes/ios/content_controls/map_view/add_an_overlay_to_a_map)[https://github.com/xamarin/recipes/recipes/ios/content_controls/map_view/add_an_overlay_to_a_map], will be displayed in the navigation as follows:

![Structure](/Images/structure.png)

The repository structure will look like the following: 

```
\recipes 
    \xamarin-forms
        \maps 
            \recipe-name-here 
                README.md 
                \Images 
                \source 
```

Folder naming standards 
-----------------------

The folder name will be used as the URL slug and therefore it is important to use the suggestions below. This ensure it will be SEO optimized and relevant for other users: 

* Try to keep the folder name between 1-3 words.  
* If more than one word, use hyphens (-), rather than underscores(_) 
* Use only lowercase letters, numbers, and hyphens 
* Make sure it is relevant to the recipe.

Recipe Contents 
----------------

Each recipe that is submitted should include the following: 

* A markdown file named **README.md** containing recipe instructions.
* Recipe sample code. This should be placed inside a folder named **source**.
* Images. These should be placed inside a folder named **Images**.









