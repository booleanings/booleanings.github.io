---
layout: post
title: Learning Elm - Forms
tags: elm coding
category: coding 🗝
---
# Learning Elm - Forms
## Model
```
type alias Model =
  { name : String,
  password : String,
  passwordConfirm : String }

init : Model
init =
  Model "" "" ""
```

![]({{site.url}}/{{site.baseurl}}/assets/2018-11-30-LearningElm-Forms/6FB95D49-3850-4E43-8A2A-AD40BD6786E5.png)

* Creating a `Model` type with three properties: `name`, `password`, `passwordConfirm`.
* The `init` function sets all three to `""`.

## View
![]({{site.url}}/{{site.baseurl}}/assets/2018-11-30-LearningElm-Forms/EE173D6C-D0D2-49D4-8F48-971A6EEDE7AE.png)

Dec 3, 2018 at 5:26 PM
* I don't really understand anything.
*  `view` is a function that takes in a Model, a Html Msg.
	* basically creating a list of three of the viewInputs with properties (type_, placeholder, value, and the toMsg function)
* `viewInput` is a function that takes in three strings (`t p v`, and a function that takes in a String and returns a msg (`toMsg`).
* `viewValidation` is a function that takes in a Model and returns Html msg (lowercase Msg) this time.
	* basically if the password is the same as passwordConfirm then return a green div that says Ok, else return a red one with an error message.

## Update
![]({{site.url}}/{{site.baseurl}}/assets/2018-11-30-LearningElm-Forms/580DF7E8-FF40-474F-9D92-469392531363.png)

* update takes in a type of Msg and Model and returns a Model.
	* uses a case switch statement. if it receives a type name, it will update the name, if it receives a `Password` or `PasswordConfirm`, it will update those respectively.

## Questions for the Day ⁉️
* Why is `PasswordConfirm` set to the model's password variable still?
* What is the




 #coding/elm
