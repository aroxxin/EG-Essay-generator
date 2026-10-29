# EG-Essay-generator
This is a simple essay generator, created to help you practice this form of expression.

An advanced, web-based generator for non-standard essay and dissertation prompts, aligned with the core curriculum for primary schools.

This project was developed within the educational sector to assist in creating materials for lessons, tests, and the eighth-grade final examination, moving away from clichéd and boring question templates.

---

## What is this program for?

* **Generates non-standard topics:** Instead of generic, "fill-in-the-blank" style questions, this application is designed to derive prompts based on the moral themes and plot elements of required reading.
* **Supports essay writing:** It provides ready-made theses, primary arguments, and supporting evidence from the literary texts, making it easier to structure an essay outline.
* **Allows for custom configuration (`options.conf`):** It includes a built-in configuration editor, enabling you to adjust settings, define search keywords, and tailor the tool to your specific needs.
* **Includes a resource library:** It features a catalog of required reading for grades 6, 7, and 8, complete with relevant literary references.

---

## How does it work?

1. **Configuration selection:** Through the `options.conf` file, you can choose settings for a specific grade level (e.g., by using the "Load Grade 6" option) or provide your own custom configuration.
2. **Search simulation:** The program scans the configuration file for keywords and their associated thematic extensions. 3. **Generating arguments:** Upon selecting the "Generate topic and arguments" option, the system identifies a problem, formulates a thesis, and lists arguments to assist in drafting the introduction, body, and conclusion.

---

## How to use the application?

### Running locally:
1. Download or clone the repository to your computer.
2. Open the `index.html` file in a web browser (Chrome, Firefox, Edge, or Safari). The application requires no additional software, servers, or databases!

### Publishing online (Free hosting):
You can deploy this page in just one minute using free hosting services like **Netlify** or **GitHub Pages**:
* **GitHub Pages:** Go to the *Settings* tab of your repository -> *Pages* -> under the *Build and deployment* section, select "Deploy from a branch" (choose the `main` branch and the `/root` folder), then save. You will immediately receive a free URL for your site!
* **Netlify Drop:** Visit [drop.netlify.com](https://drop.netlify.com/) and drag-and-drop your `index.html` file there.

---

## Configuration file (`options.conf`)
An example structure that can be used with the application:

```ini
[szukaj]
Chłopcy z Placu Broni | motyw zdrady, honor i odwaga
Hobbit, czyli tam i z powrotem | przemiana bohatera, domator w świecie przygody

[lekturki_klasa_6]
Chłopcy z Placu Broni | Ferenc Molnár | 6
Katarynka | Bolesław Prus | 6
