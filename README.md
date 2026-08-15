# Web Designing Workshop

A collection of **Web Designing** practicals for coursework, lab work, and practice. This repository contains the code for the experiments completed so far, along with reference/solution files.

## Repository Structure

```text
WebDesigning/
│
├── Ex.1(Home page)/
│   ├── index.html
│   ├── LOGIN.html
│   ├── REGISTRATION.html
│   ├── CATALOUGUE.html
│   ├── CART.html
│   ├── CSE.html
│   ├── AIML.html
│   ├── DS.html
│   └── IOT.html
│
├── Ex.2(Login page)2/
│   ├── index.html
│   ├── LOGIN.html
│   ├── REGISTRATION.html
│   ├── CATALOUGUE.html
│   ├── CART.html
│   ├── CSE.html
│   ├── AIML.html
│   ├── DS.html
│   └── IOT.html
│
├── Ex.3(Cataulouge page)/
│   └── CATALOUGUE.html
│
├── Ex.4(Cart page)/
│   └── CART.html
│
├── wd1.solp.df
├── wd2.Sol.pdf
└── README.md
```

## Experiments Completed

### Experiment 1 — Home Page

Contains a basic homepage for **Raj Kumar Goel Institute of Technology (RKGIT)** with navigation for Login, Registration, Catalogue, Cart, and department pages such as CSE, AIML, DS, and IOT.

### Experiment 2 — Login Page

Contains a simple HTML login page using a table layout with username, password, Login, and Reset controls.

### Experiment 3 — Catalogue Page

Contains a simple book catalogue using an HTML table with:

- Book cover placeholder
- Book name
- Author
- Publisher
- Price
- Add to Cart button

Books currently included include **XML Bible, AI, Java 2, and HTML in 24 Hours**.

### Experiment 4 — Cart Page

Contains a simple cart table showing:

- Book name
- Author
- Price
- Quantity
- Total
- Total amount
- Place Order button
- Reset button

---

# How to Use the Code in VS Code

This section is for classmates who want to use these practical codes in **Visual Studio Code (VS Code)**.

## 1. Create a Folder

Create one main folder anywhere on your computer. For example:

```text
WebDesigning
```

Open this folder in VS Code.

## 2. Create a Folder for the Experiment

For the first experiment, create a separate folder inside your main folder:

```text
WebDesigning/
└── Ex.1(Home page)/
```

Create the HTML files required for that experiment inside it.

For example:

```text
Ex.1(Home page)/
├── index.html
├── LOGIN.html
├── REGISTRATION.html
├── CATALOUGUE.html
└── CART.html
```

## 3. Copy the Code

Open the required file in VS Code and copy the corresponding code from this repository into that file.

For example:

```text
LOGIN.html  →  Copy the Login Page code into LOGIN.html
CATALOUGUE.html  →  Copy the Catalogue code into CATALOUGUE.html
CART.html  →  Copy the Cart code into CART.html
```

Save the file using **Ctrl + S**.

## 4. Check the File Names

Keep the file names exactly as they are used in the HTML links.

For example:

```html
<a href="LOGIN.html">LOGIN</a>
```

Here, `LOGIN.html` must exist in the correct location.

---

# How to Handle the Next Experiment

Before creating a new file for the next experiment, **check whether the required file already exists from the previous experiment**.

There are two simple options:

### Option 1 — Copy the Previous File

If the previous file is needed for the next experiment, copy it into the new experiment folder and then modify the copied code.

Example:

```text
Ex.1(Home page)/
└── LOGIN.html

Ex.2(Login page)/
└── LOGIN.html
```

This keeps the previous experiment unchanged.

### Option 2 — Change the Existing Code

If you are continuing with the same project and do not need to keep a separate copy, open the existing file and **change or replace its code according to the new experiment**.

For example, if the next experiment is related to `LOGIN.html`, open the existing `LOGIN.html` and update its code instead of unnecessarily creating another login file.

### Recommended Method

For practical submissions, it is better to keep each experiment in its own folder:

```text
WebDesigning/
│
├── Ex.1(Home page)/
├── Ex.2(Login page)2/
├── Ex.3(Cataulouge page)/
├── Ex.4(Cart page)/
├── Ex.5(...)/
└── Ex.6(...)/
```

This keeps every experiment separate and prevents new changes from overwriting your previous practical work.

---

# How to Run the HTML Code

After copying the code into VS Code:

1. Save the file using **Ctrl + S**.
2. Open the `.html` file in your browser.
3. If the experiment contains multiple HTML files, keep all related files in the correct folder.
4. Test all navigation links.

### Using Live Server (Optional)

If you have the **Live Server** extension installed in VS Code:

1. Open the HTML file.
2. Right-click inside the file.
3. Select **Open with Live Server**.
4. The webpage will open in your browser.

Live Server is optional. These basic HTML files can also be opened directly in a browser.

---

# Important Tips for Classmates

- Create a separate folder for each experiment.
- Copy the code into the **specific HTML file related to that experiment**.
- Before creating a new file, check whether the required file already exists.
- If the file exists, either **copy it into the new experiment folder** or **modify its code** according to the new experiment.
- Do not delete previous experiment files if you need them for submission.
- Keep file names exactly the same as those used in `href` links.
- Save your work regularly.
- Test every link after changing files or folders.

---

# Technologies Used

- **HTML5**
- HTML Tables
- HTML Forms
- Hyperlinks
- Iframes / navigation concepts
- Basic HTML attributes

The current exercises intentionally use simple HTML so that the basic concepts are easy to understand and reproduce during practical work.

## Reference Files

The repository also contains reference/solution files:

- `wd1.solp.df`
- `wd2.Sol.pdf`

## Author

**Vipin Prajapati**

B.Tech CSE (AI & ML) Student

---

This repository is maintained for **Web Designing coursework, practical assignments, and HTML practice**.
