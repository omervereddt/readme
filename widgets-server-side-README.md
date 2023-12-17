
# readme

## This readme file will guide you through the steps in order to create a new widget type on server-side

### (1) widgetTypes constants
```ruby
  src/constants.js
  ```
(1.1) create new const of the widget type

### (2) Helpers
```ruby
src/services/widget-type-services/helpers.js
```
(2.1) In some cases, you will need to make use of those helpers, please make sure you understand all of them.

### (3) Widget Service
```ruby
 src/services/widget-type-services/
  ```
(3.1) create `my-widget-name-service` folder and inside it:

(3.2) create `index.js` file - look of other services for reference. update the execute function in order to fit necessary requests.

(3.2) take as a reference other execute function of widgets in order to understand the flow
