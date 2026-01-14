# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Use of media queries for the mobile version. The change from desktop to mobile was basically the constraints on the height:
```html
<div id="card">
  card content
</div>
```
```css
#card {
    /* ... other properties ...*/
    width: 320px;
    height: 464px;
}
@media (max-width: 375px) {
    #card {
        height: auto;  /* remove fixed height */
    }
}
```
The use of CSS variables for colors.
