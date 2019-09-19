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

This is exampe of string validator on Java:
'''java
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
'''