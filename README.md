### Hello World! I am Felipe.

- 🔭 I’m currently working with back-end.
- 🌱 I’m studying Python, HTML and CSS.
- 💻 Also, I know a bit of Lua, C and C++  =)
- 💬 Any doubts feel free to ask.
- 📫 E-mail: Soon...

![Ren's GitHub stats](https://github-readme-stats.vercel.app/api?username=rendeviluke&show_icons=true&theme=rose_pine)<br>
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=rendeviluke&layout=compact&theme=rose_pine)

<div style="display: inline_block"><br>
  <img align="center" alt="Ren-Py" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img align="center" alt="Ren-Py" src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white">
  <img align="center" alt="Ren-Py" src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white">  
- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ rendeviluke }}

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
