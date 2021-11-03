### Hi there 👋🏽

<!--
**marcelleemendess/marcelleemendess** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


- uses: Platane/snk@master
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.marcelleemendess}}

    # path of the generated gif file
    # If left empty, the gif file will not be generated
    gif_out_path: dist/github-snake.gif

    # path of the generated svg file
    # If left empty, the svg file will not be generated
    svg_out_path: dist/https://platane.github.io/snk/


