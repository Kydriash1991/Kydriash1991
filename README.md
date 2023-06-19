![Header](https://github.com/Kydriash1991/Kydriash1991/blob/main/assets/standard.gif)
### About me 🧑🏻‍💻
- I am a beginner QA engineer. I work hard on myself to become a worthy specialist. My goal is to build a successful career.:fire:
- I have read over 30 books by Stephen King.
- I have been jibbing on a snowboard for 18 years.
- Gathered a large collection of sneakers.
- I dream of visiting Japan


### Language and Tools
![Header](https://img.shields.io/badge/Postman-090909?style=for-the-badge&logo=postman&logoColor=f76935)
![Header](https://img.shields.io/badge/Swagger-090909?style=for-the-badge&logo=swagger&logoColor=7ede2b)
![Header](https://img.shields.io/badge/Github-090909?style=for-the-badge&logo=github&logoColor=8cc4d7)
![Header](https://img.shields.io/badge/MySQL-090909?style=for-the-badge&logo=mysql&logoColor=00618a)
![Header](https://img.shields.io/badge/DevTools-090909?style=for-the-badge&logo=googlechrome&logoColor=2674f2)
![Header](https://img.shields.io/badge/CharlesProxy-090909?style=for-the-badge&logo=charlesproxy&logoColor=8cc4d7)


### Testing Documentation

- [Checklists](https://miro.com/app/board/uXjVM-2ukgw=/?share_link_id=738546179073)

### Follow Me

- [Telegram](https://t.me/kydriashov)




  uses: Kydriash1991/Kydriash1991
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
