
# readme

## This readme file will guide you through the steps in order to create a new widget type on client-side

### (1) widget-type-services 
```ruby
  src/services/widget-type-services
  ```
(1.1) create new `name-of-widget-widget-type-service.js` file 

(1.2) see an example reference of `src/services/widget-type-services/my-direct-report-widget-type-service.js` 

(1.3) inside `index.js` file - import the new service and add it to the `SERVICES` const

(1.4) add `translations.json` file - add the displayed value as a translation

### (2) Constants
```ruby
src/constants/widget-types.js
```
(2.1) add the new widget type to the file

### (3) Components
```ruby
 src/components/widget/widget-components
  ```
(3.1) create `my-widget-name` folder and inside it:

(3.2) create `translations.json` file - there you will put the empty state title text

(3.2) create `name-of-widget-widget-component.js` file

(3.3) create `name-of-widget-component-styles.js` file

#### take one of the other widget components as a reference. they have all the same structure.
### (4) Empty state image
```ruby
 public/images/widgets
  ```
(4.1) add the new png image of the empty state 

(4.2) in the `name-of-widget-widget-component.js` file,  add the new `imgSrc` prop in the `EmptyState` component

### (5) Icon.svg file
```ruby
src/icons
```

(4.1) add the new icon.svg file - make sure height is set to "100%"

(4.2) import the new icon as a component - see refernece of other widget-type component

### (6) adding the new widget button to the adding options  
```ruby
src/components/home-view/home-view-component.js
```
(6.1) add to the `possibleWidgetTypes` the new widget type

