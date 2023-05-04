# Dynamic modular website back-office with Strapi
## Work in progress

This project is a back-office for a dynamic modular website. It is built with Strapi, a headless CMS, and a [Rails application](https://github.com/JulesPR1/dynamic-modular-site-front) use the API provided to display the customized website content.

What is special about this back-office is that it offers the possibility to move front-end components easily. For example, if you want to move the "About us" section from the bottom of the page to the top, you just have to change the order of the components in the back-office. The [Rails application](https://github.com/JulesPR1/dynamic-modular-site-front) will then display the components in the right order.

## 📚 Versions

- yarn 1.22.19
- npm 8.5.0

## 🚀 How to launch the project

```
yarn develop
```

or

```
npm run develop
```

## 🛠️ Components list

- About us
- Blog
- Features
- Footer
- Instagram Posts
- Menu
- Meal of the day
- Reservations
- Reviews
- Slider
- Team
- Top bar

All components are displayed on the home page. You can change the order of the components in the back-office. You can also add or remove components from the home page.

If you want to add a new component in the back-office, you will have to create a matching ERB file in the [Rails application](https://github.com/JulesPR1/dynamic-modular-site-front).