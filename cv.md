# Nikita Yaruchenko

## Contact Info  

+ **Telephone: +79272066836**

+ **Email: nikitacpmi@gmail.com**

## Summary

I chose this school to plunge into the world of frontend and explore a new industry in IT. These courses will help me to acquire the
necessary knowledge that I can apply in my future work.

----------------

## Skills

+ Basic of **HTML5**, **CSS3**
+ Basic of **Git**
+ Programming language: **Java, C++, Python, C#**
+ Frameworks: **Google Web Toolkit** (Basic)

----------------

## Code Examples

This is example of string validator on Java:

```java
package com.laboratory.validators;

import javax.faces.component.UIComponent;
import javax.faces.context.FacesContext;
import javax.faces.validator.FacesValidator;
import javax.faces.validator.Validator;
import javax.faces.validator.ValidatorException;

@FacesValidator(value = "validators.StrValidator")
public class StrValidator extends ValidatorBaseFuncs implements Validator<String> {

    @Override
    public void validate(FacesContext facesContext, UIComponent uiComponent, String s) throws ValidatorException {
        if (s == null) {
            throwError(uiComponent, "Отсутствует строка!");
            return;
        }

        if (s.isEmpty()) {
            throwError(uiComponent, "Строка пустая!");
            return;
        }

        setSuccess(uiComponent);
    }
}
```

----------------

## Education

At the moment I am a 4th year student of Samara State University in the direction of "Applied Mathematics and Informatics". Purposefully I did not pass any courses, and studied interesting information on programming independently on the Internet.

----------------

## English

I began to study English in depth in the 3rd year of study at the Institute, up to this point my English was bad. According to the results of determining the level of English I have the result A2. To improve my English I look for interesting information in English, try to watch movies without translation and constantly read in this language.
