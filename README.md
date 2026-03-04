# Terminal-Run
## find the latest Node.js & npm versions and set them up using the terminal
| Task                          | Command                     |
| ----------------------------- | --------------------------- |
| Check Node.js version         | `node -v`                   |
| Check npm version             | `npm -v`                    |
| Install latest LTS (via nvm)  | `nvm install --lts`         |
| Install latest Node (current) | `nvm install node`          |
| Update npm                    | `npm install -g npm@latest` |

## Yarn
| Task                | Command                      |
| ------------------- | ---------------------------- |
| Check version       | `yarn -v`                    |
| Install via npm     | `npm install -g yarn`        |
| Update Yarn         | `npm install -g yarn@latest` |

## eslint-config-react-app
### 📦 eslint-config-react-app কী? কেন React সেটআপে ব্যবহার করা হয়?

eslint-config-react-app হলো একটি ready-made ESLint configuration package, যা মূলত
Create React App ব্যবহার করলে স্বয়ংক্রিয়ভাবে যুক্ত হয়।
🧠 আগে বুঝি — ESLint কী?
🔍 ESLint কী?

ESLint হলো একটি টুল যা:

কোডের ভুল (error) খুঁজে বের করে

খারাপ practice ধরিয়ে দেয়

কোড স্টাইল ঠিক রাখে

unused variable ধরতে পারে

সম্ভাব্য bug আগেই জানায়

🎯 তাহলে eslint-config-react-app কী করে?

React প্রজেক্টে অনেক নিয়ম (rules) দরকার হয়, যেমন:

JSX syntax ঠিক আছে কিনা

React Hooks সঠিকভাবে ব্যবহার হয়েছে কিনা

import/export সঠিক কিনা

unused variable আছে কিনা

এই সব rules একসাথে pre-configured অবস্থায় দেয় 👉 eslint-config-react-app

মানে আপনাকে আলাদা করে config লিখতে হয় না।

📌 এটি কী কী অন্তর্ভুক্ত করে?

এটার ভিতরে থাকে:

eslint

eslint-plugin-react

eslint-plugin-react-hooks

eslint-plugin-jsx-a11y

babel-eslint বা related parser

সবকিছু একসাথে configure করা থাকে React এর জন্য।
