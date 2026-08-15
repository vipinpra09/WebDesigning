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
│   ├── RGISTRATION.html
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

# How to Use This Repository

This section is mainly for classmates who want to use the practical code in **VS Code**.

## 1. Install VS Code

Download and install **Visual Studio Code (VS Code)** if it is not already installed.

## 2. Download or Clone the Repository

You can either download the repository as a ZIP file from GitHub or clone it using Git.

### Option A — Download ZIP

1. Open the repository on GitHub.
2. Click **Code**.
3. Select **Download ZIP**.
4. Extract the ZIP file.
5. Open the extracted `WebDesigning` folder in VS Code.

### Option B — Clone using Git

Open the VS Code terminal and run:

```bash
git clone https://github.com/vipinpra09/WebDesigning.git
```

Then open the `WebDesigning` folder in VS Code.

---

# How to Add the Code for an Experiment

**Important:** You do not need to create a new project for every small practical if the required files already exist.

## For the First Experiment

If you are starting from the beginning:

1. Create a folder on your computer, for example:

```text
WebDesigning
```

2. Open this folder in VS Code.
3. Create the required HTML files inside the folder.
4. Copy the code for the experiment into the corresponding files.
5. Save the files.
6. Open `index.html` in a browser to test the webpage.

For example:

```text
WebDesigning/
└── Ex.1(Home page)/
    ├── index.html
    ├── LOGIN.html
    ├── REGISTRATION.html
    ├── CATALOUGUE.html
    └── CART.html
```

## For the Next Experiments

Before creating new files, **check whether the files from the previous experiment already exist**.

If a required file already exists, you can simply:

- Copy the previous file into the new experiment folder, **or**
- Change/replace the code inside the existing file according to the new experiment.

### Example

Suppose you completed the Login Page and already have:

```text
LOGIN.html
```

For the next experiment, if the task requires changes to the login page, you do **not** need to create another random file.

Open the existing `LOGIN.html` and replace/update its code according to the new experiment.

Similarly, if the next experiment requires `CATALOUGUE.html` and that file already exists, either copy that file into the new experiment folder or modify its code as required.

### Recommended Method

Keep each experiment in its own folder so that your previous work remains safe:

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

This makes it easier to submit individual experiments and prevents newer code from accidentally overwriting your previous practical work.

---

# How to Run the HTML Code

After copying or writing the code:

1. Save the file using **Ctrl + S**.
2. Open the `.html` file in your browser.
3. For a multi-page experiment, make sure all linked HTML files are inside the correct folder.
4. Check that the file names used in `href` match the actual file names.

For example:

```html
<a href="LOGIN.html">LOGIN</a>
```

means that `LOGIN.html` should be in the same folder as the current HTML file unless another path is specified.

## Using Live Server (Optional)

If you have the **Live Server** extension installed in VS Code:

1. Open the HTML file.
2. Right-click inside the file.
3. Select **Open with Live Server**.
4. The webpage will open in your browser.

Live Server is optional. Basic HTML files in this repository can also be opened directly in a browser.

---

# Important Tips for Classmates

- Keep the **file names exactly the same** as used in the HTML `href` links.
- Do not delete previous experiment files if you may need them for submission.
- Before starting a new experiment, check whether the required HTML file already exists.
- If it exists, **copy it for the new experiment or modify its code** according to the new question.
- Save your work regularly.
- Test every link after changing file names or folder locations.
- Keep each experiment in a separate folder for easy organization and submission.

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