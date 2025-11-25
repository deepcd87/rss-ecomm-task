# 🛍️ eCommerce Application  
### Final Team Project (RS School JS/Frontend course)

This repository contains our final project for the [RS School JS/Frontend course](https://rs.school/courses/javascript) — a full-featured **eCommerce Single Page Application** built from scratch using **React + TypeScript** and powered by **CommerceTools API**.

The application replicates a real online shopping experience: browsing products, viewing details, managing a shopping basket, and interacting through a responsive user-friendly interface.

This project was created through **full-scale team collaboration**, with shared planning, common architecture, and coordinated implementation across multiple sprints.

---

## 👥 Team Collaboration

This project is the result of **coordinated work by a team of three developers**.  
Throughout the development process, we:

- planned architecture and features together  
- divided responsibilities across sprints  
- collaborated through Git, code reviews, and shared conventions  
- unified our development environment (ESLint, Prettier, Husky)  
- jointly integrated CommerceTools  
- implemented shared design, routing structure, and UI logic  

Each member submitted their individual contribution to the mentor,  
while the **team lead** submitted the final combined project for cross-check.

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

## 🗂️ Key Pages

### 🔐 Login  
User authentication with validation and token handling.

### 📝 Registration  
Account creation with input validation and redirect to login.

### 🏠 Main Page  
Entry page with navigation to core sections and optional promo content.

### 📋 Catalog Page  
Product catalog with cards, filters, sorting, and categories.

### 🔎 Product Details Page  
Full product info, images, description, price, and “add to cart” options.

### 👤 User Profile  
User personal data, addresses, and edit functionality.

### 🛒 Basket  
Product management (add/remove/change quantity), subtotal, and total.

### 🙋‍♂️🙋‍♀️ About Us  
Team introduction with roles, photos, short bios, GitHub links,  
and RS School logo.

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

