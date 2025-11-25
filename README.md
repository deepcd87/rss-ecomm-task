# 🛍️ eCommerce Application  
### Final Team Project (RS School JS/Frontend course)

This repository contains final project for the [RS School JS/Frontend course](https://rs.school/courses/javascript) — a full-featured **eCommerce Single Page Application** built from scratch using **React + TypeScript** and powered by **CommerceTools API**.

The application replicates a real online shopping experience: browsing products, viewing details, managing a shopping basket, and interacting through a responsive user-friendly interface.

This project was created through **full-scale team collaboration**, with shared planning, common architecture, and coordinated implementation across multiple sprints.

---

## 🌐 Project Overview

The eCommerce Application is a fully interactive SPA featuring:

🔐 User authentication (login & registration)

🏠 Main page with navigation to all major sections

📋 Catalog with sorting, filtering, and product categories

🔎 Detailed product pages

👤 User profile with editable personal data & addresses

🛒 Basket with quantity management and real-time updates

🙋‍♂️🙋‍♀️ About Us page

📱 Fully responsive layout (from 390px and up)

⚛️ Built using React + TypeScript

🔗 Powered by CommerceTools API

🧭 SPA routing with dynamic URLs

🧼 Clean, modular, scalable code

🧪 Unit test coverage (Jest)

---

## 🤝 Teamwork & Mentor Review

This project was developed in a team of three, following real industry practices:

🧩 Distributed tasks via a shared task board

🔀 Worked through pull requests with approvals

💬 Conducted active code reviews

🛠️ Collaborated on architecture and technical decisions

📚 Followed consistent coding standards (ESLint, Prettier, Husky)

Throughout the sprint, the project was continuously **reviewed by an experienced mentor**, who evaluated the code quality, teamwork, structure, and testing approach.
This mentor feedback played a key role in improving architecture, code readability, and project workflow — mimicking a professional development environment.

---

## 🧰 Tech Stack

- **React**  
- **TypeScript**
- **CommerceTools** API client
- Webpack
- React Router — SPA navigation  
- Jest — testing  
- ESLint & Prettier — code style  
- Husky — pre-commit hooks
  
---

## 🏁 Sprint Structure
<details>
<summary><strong>Sprint 1 — Setup & CommerceTools Integration</strong></summary><br>
  
- Repository setup  
- Task board organization  
- React + TypeScript project initialization  
- ESLint, Prettier, Husky, Jest configuration  
- CommerceTools client setup  
- Initial SPA architecture  
</details>

<details>
<summary><strong>Sprint 2 — Login, Registration & Main Pages</strong></summary><br>
  
- Login & Registration forms  
- Input validation  
- Token-based authentication  
- Basic global state for auth  
- Navigation and routing  
- Redirects and access rules  

</details>

<details>
<summary><strong>Sprint 3 — Catalog, Product Details & User Profile</strong></summary><br>
  
- Fetching products from CommerceTools  
- Catalog listing, filtering, sorting  
- Product card UI  
- Product Details page  
- User Profile with editable info and addresses  

</details>

<details>
<summary><strong>Sprint 4 — Basket, Enhancements & About Us</strong></summary><br>
  
- Basket page (quantity control, totals, removal)  
- Improved Product Details page  
- Catalog improvements (performance, UX)  
- About Us page  
- General UI polish and optimizations  

</details>

---

## 🛠️ Summary

This final project allowed us to:

- build a complete SPA from scratch  
- collaborate as a real development team  
- integrate a large-scale eCommerce platform  
- create a responsive, user-friendly interface  
- split work across sprints with clear responsibilities

---

## 🚀 Project Setup & Running

> ⚠️ **Important:**  
> This application **will not work** without valid **CommerceTools API credentials**.  
> You must obtain them from the CommerceTools Merchant Center and place them in a `.env` file before running the project.

#### 1. **Clone the repository**
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```
#### 2. **Add CommerceTools credentials to the `.env` file**
```bash
REACT_APP_BASE_URL=
REACT_APP_OAUTH_URL=
REACT_APP_PROJECT_KEY=

REACT_APP_ADMIN_CLIENT_ID=
REACT_APP_ADMIN_CLIENT_SECRET=

REACT_APP_SPA_CLIENT_ID=
REACT_APP_SPA_CLIENT_SECRET=
```

#### 3. **Install dependencies**
```bash
npm install
```
#### 4. **Run project**
```bash
npm start
```

#### 📜 Available Scripts

The following NPM scripts are available for development and maintenance:

| Command             | Description                                              |
|---------------------|----------------------------------------------------------|
| `npm start`         | Start dev server with Hot Module Replacement (HMR)       |
| `npm run dev`       | Build the project in development mode                    |
| `npm run prod`      | Build the project in production mode                     |
| `npm run lint`      | Run ESLint on `.ts` and `.tsx` files                     |
| `npm run prettier`  | Format source files using Prettier                       |
| `npm test`          | Run unit tests using Jest                                |

