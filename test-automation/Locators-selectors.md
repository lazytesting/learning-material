# Locators / Selectors#



## 1. What is a locator?##

- a way to find an element in the DOM 	

- Document Object Model: structured representation of the document

  ​

## 2. WebDriver locators ##

- CSS Selector
- ~~Link text selector~~
- ~~Partial link text selector~~
- ~~Xpath Selector~~



## 3. CSS Selectors ##

- Id  `#bla23`
- Type  `button`
- Class  `.teaser`
- Attribute  `[name='test']`
- Relations
  - Descendant  `#thing button` (child or child of child)
  - Child  `#thing > button` (direct child)



## 4. Best practices

- It should be unique (today and tomorrow)
- It should be low maintenance



## 5. Tip

- In browser console use `document.querySelectorAll("body")`
- In Visual Studio use Immediate Window to debug them in a flow



## 6. Further readings##

- DOM : https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model
- CSS selectors: https://developer.mozilla.org/en/docs/Web/Guide/CSS/Getting_started/Selectors















