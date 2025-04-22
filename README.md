# EzModals

This project is a tool that allows you to create modals in your application easily using native CSS and JS with classes.

[![paaypalBadge](https://img.shields.io/badge/support-on_paypal-006be1?style=for-the-badge)](https://paypal.me/rdaphq)
[![discordBadge](https://img.shields.io/discord/922010556481826866?style=for-the-badge&color=5865F2)](https://rdaphq.com/discord)

## How to use

Start by cloning this repository and place it into your project folder.

After cloning, you can use the EzModals classes into your HTML or PHP files. These classes always start with "ez-", followed by the name of the modal you want to create. Below you can find all the classes available and their modals.

---

## Classes

| Class | Description | Style |
|-------|-------|-------|
| ```class="ez-warning"``` | Yellow modal for warnings and alerts. | Light/Dark
| ```class="ez-error"``` | Red modal for errors. | Light/Dark
| ```class="ez-success"``` | Yellow modal for warnings and alerts. | Light/Dark
| ```class="ez-info"``` | Blue modal for information, notes or recommendations. | Light/Dark

### Now, this is an example of how to use it in HTML.

```html sample.html
<div class="ez-warning">
    <p>This is a warning modal.</p>
</div>
```

To add light or dark style, use class ```ez-light``` or ```ez-dark```, for example:

```html sample.html
<div class="ez-warning ez-dark">
    This is a warning modal.
</div>
```
![a](https://i.imgur.com/8022084.png)