# bun-sanityio-blog-studio-demo

bun-sanityio-blog-studio-demo is a simple Sanity io studio with schemas using bun package manager.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Support and Contact](#support-and-contact)
- [Author](#author)
## Installation

Before make sure you have Sanity io client installed:
```
sanity --version
```
If you don't have it run:
```
npm install -g @sanity/cli
```

You need to download bun, that is currently today available for macOS and Linux (Octomber 2, 2023):
```
curl -fsSL https://bun.sh/install | bash
```

Now run bun-sanityio-blog-studio-demo on your local machine, follow these steps:

1. Clone the repository:

    ```bash
   git clone https://github.com/zukoheiwa/bun-sanityio-blog-studio-demo.git
    ```
2. Navigate to the project directory:

    ```bash
    cd bun-sanityio-blog-studio-demo
    ```
So far now you have a basic understanding of a demo project studio schema look, but you have to create your own one to start using the database right.

Create your own studio database with Sanity io by running this:
```
sanity init
```
- Continue creating a Sanity Studio v3 project? (Y/n) ```Y```
- You might need to create account or login to a sanity account with your prefrence.
- After that you can choose to create a studio schema project Your project name: (My Sanity Project) 
- Use the default dataset configuration? (Y/n) ```Y```
- Project output path: /home/zukoheiwa/Workspace/Sanity Io/my-sanity-project "Just click Enter"
- Now you have 3 demo studio schemas by Sanity io 1. Movie project (schema + sample data), 2. E-commerce (Shopify), 3. Blog (Schema), or You can choose Clean project with no prefined schemas, for this project you will choose the 3rd one 3. Blog (Schema).
- Do you want to use TypeScript? (Y/n) ```n```
- Package manager to use for installing dependencies? "Choose manual"

Your Sanity io studio schema is ready to run and taken care,

1. Navigate to the project:
```
cd my-sanity-project
```

2. Install dependencies:
```
bun install
```

3. Start the development:
```
bun run dev
```


# Usage
Usage
Once the app is running, open your web browser and access bun-sanityio-blog-studio-demo at http://localhost:3333. Here's how you can use it:

- Open your prefered browser and open this http://localhost:3333
- You can see the simple Blog Schema Demo

# Features
- 0/500k API CDN Requests.
- 0/100k API Requests.
- 0B/5GB Assets.
- 0B/10GB Bandwidth.
- 0/2 Datasets.
- 0/10k Documents.
- 0/3 Non-admin members.

# Contributing
We welcome contributions from the community! To contribute to bun-sanityio-blog-studio-demo, please follow these guidelines:
1. Fork the repository and create a new branch for your feature or bug fix.
2. Make your changes, ensuring to maintain coding standards.
3. Submit a pull request, describing your changes in detail.

# License
bun-sanityio-blog-studio-demo is open-source software licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

# Support and Contact
If you have questions, encounter issues, or want to get involved in the development, please contact me via:
- 📫 via Email **zukoheiwabusiness@gmail.com**
- 📄 via Issues https://github.com/zukoheiwa/bun-sanityio-blog-studio-demo/issues 

## Author
&#8226; ZukoHeiwa

<div>
<a href="https://www.youtube.com/channel/UCt3X0lR50_2yqdj9o3LUpKA" target="blank">
  <img src="https://img.shields.io/badge/@ZukoHeiwa-blue?style=for-the-badge&logo=twitter" alt="twitter" />
</a>
<br>
<a href="https://twitter.com/ZukoHeiwa" target="blank">
  <img src="https://img.shields.io/badge/@ZukoHeiwa-red?style=for-the-badge&logo=youtube" alt="youtube" />
</a>
<br>
<a href="https://github.com/ZukoHeiwa" target="blank">
  <img src="https://img.shields.io/badge/@ZukoHeiwa-black?style=for-the-badge&logo=github" alt="github" />
</a>
</div>
<br>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=zukoheiwa&show_icons=true&locale=en&layout=compact" alt="zukoheiwa" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=zukoheiwa&show_icons=true&locale=en" alt="zukoheiwa" /></p>
