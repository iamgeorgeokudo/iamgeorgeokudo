![image](https://github.com/iamgeorgeokudo/iamgeorgeokudo/assets/57495814/2dc0aa87-600e-46ba-9257-6e23ae0555c8)
file:///home/iamomondiokudo/Downloads/Systems%20and%20technology%20programming%20company%20logo.png

### Hi there. Welcome to my github account 👋
![Profile views](https://gpvc.arturio.dev/[iamgeorgeokudo])

<!--
**iamgeorgeokudo/iamgeorgeokudo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

- 🌱 I’m currently learning Machine Learning with Tensor Flow.
- 😄 Pronouns: He/Him
- - ⚡ Fun fact: I watch aviation accidents investigation daily 😄
 


<!--START_SECTION:waka-->
name: Work Stats Readme

on:
  workflow_dispatch:
  schedule:
    # Runs every 2 hours
    - cron: "0 */2 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
<!--END_SECTION:waka-->
