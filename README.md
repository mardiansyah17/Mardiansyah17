<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=mardiansyah17&show_icons=true&theme=gotham" alt="mardi" />

  
# Hi there, I'm Muhammad Mardiansyah 👋

I'm a fullstack web developer with expertise in Tailwindcss, Bootstrap, Reactjs, Laravel, Nodejs, Expressjs, MySQL, and MongoDB. I'm passionate about creating robust and scalable web applications that solve real-world problems.

## Skills

- **Front-end**: Tailwindcss, Bootstrap, Reactjs
- **Back-end**: Laravel, Nodejs, Expressjs
- **Database**: MySQL, MongoDB
- **Other Tools**: Git, GitHub, Visual Studio Code, Heroku, Firebase

## Projects

Here are some of the projects that I've worked on:

- [Bloging system - BidarBlog](https://ti-bidar.com/): The bidarblog application is an application that allows users to read blogs without having to log in first. However, after logging in, users will be able to create blogs that must be approved by the admin before publishing.
- [Discussion forum - Forum](https://forum.ti-bidar.com/): Discussion forum applications are applications that allow users to discover and participate in a variety of different forums. Users can view the topics being discussed and provide answers and make comments. However, once logged in, users will be able to add, edit, and delete already published forums. This application also provides light mode and dark mode features that can be adjusted according to user preferences.


## Contact Me

- [Email](mailto:mardiansyahm002@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/muhammad-mardiansyah-b8b787231/)
- [Website](https://mardiancode.tech/)


Feel free to reach out to me if you have any questions or if you'd like to collaborate on a project. Thanks for stopping by!

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
