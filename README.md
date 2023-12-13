# readme

### This readme file will guide you through the steps in order to create a new widget type on client-side

#### (1) widget-type-services 
```ruby
  src/services/widget-type-services
  ```
(1.1) create new `name-of-widget-widget-type-service.js` file 

(1.2) see an example reference of `src/services/widget-type-services/my-direct-report-widget-type-service.js` 

(1.3) inside `index.js` file - import the new service and add it to the `SERVICES` const

(1.4) add `translations.json` file - add the displayed value as a translation

#### (2) Constants
```ruby
src/constants/widget-types.js
```
(2.1) add the new widget type to the file

#### (3) Components
```ruby
 src/components/widget/widget-components/
  ```
(3.1) create `my-widget-name` folder

(3.2) add `translations.json` file - there you will put the empty state title

(3.2) add `src/components/widget/widget-components/my-direct-report/new-widget-component.js` file

(3.3) add `src/components/widget/widget-components/my-direct-report/new-widget-component-styles.js` file

##### take one of the other widget components as a reference. they have all the same structure.
#### 1. adding new empty state image
```ruby
 src/components/widget/widget-components/my-team-widget/my-team-widget-component-styles.js
  ```
