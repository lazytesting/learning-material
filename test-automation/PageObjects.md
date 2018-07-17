Page Objects
============

1. What are page objects?
-------------------------

-   Splitting up Selenium logic with test logic.

-   A class which provides API to the tests

-   Actions (click, fill, login,etc.)

-   Get (element exist, get text, etc.)

-   Optional: Assertions

-   Optional: way to access the page

2. Why are Page Objects useful?
-------------------------------

-   Allow your test to focus on logic, not about implementation details

-   Single place for selectors and other implementation details

-   Decouple test runner from webdriver implementation

-   Change to test runner does not impact page objects

-   Change to different Webdriver (or other) framework to drive browse does not
    affect tests

3. Further readings
-------------------

-   http://www.seleniumhq.org/docs/06\_test\_design\_considerations.jsp\#page-object-design-pattern

-   http://martinfowler.com/bliki/PageObject.html
