# react-text-rotator-component
Simple text rotator component for react

## How to install?
Simple copy/download the TextRotator.jsx to the components folder in your React project.

## How to use?
- In your parent component, import your new TextRotator component, defininf the path depending to the location from Parent component.
- Now, add the component to your code, as example:
  ```jsx
  <TextRotator
      animationClass="css-class-with-for-animations"
      words={['Array of words', 'to rotate', 'in your page']}
      parentClass="css-class-for-wrapper-element"
  />
  ```
- Note if you are using react-18next, you can also supply a list of words from yopur current language contents, ex:
  ```jsx
  words={i18n.t('your.key.with.rotate_phrases', { lng: i18n.language, returnObjects: true })}
  ```

## Other configurations
- You can also set the delay between changing word, just change de ```speed: 5000``` in createTextRotator function inside the component.
