<h2 align="center">Hey, nice to meet you! I'm Vitor Nere</h2>
<p align="center"><em><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> Software Engineer at <a href="https://usezapay.com.br/">Zapay Pagamentos</a> <b>&</b> Technology Consultant at <a href="https://capacitampe.com.br/">CapacitaMPE</a> <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"></em></p>

<p align="center">
<a href="https://www.linkedin.com/in/vitor-nere/"><img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://www.instagram.com/nere.swe/"><img src="https://img.shields.io/badge/<nere.swe>%20-%23E4405F.svg?&style=for-the-badge&logo=Instagram&logoColor=white"/></a>
</p>

### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> A little more about me...
<img align="right" src="https://media.giphy.com/media/TdNBNvKYuOGxWuUeDm/giphy.gif">

```python
#!/usr/bin/python3
# -*- coding: utf-8 -*-

class SoftwareEngineer:
    def __init__(self, data, indent=0):
        self.data = data
        self.indent = indent
    
    def __print(self, value, indent):
        return '\t' * indent + str(value) + '\n'

    def __beatiful_print(self, data, indent):
        to_str = ''
        for key, value in data.items():
            to_str += self.__print(key, indent)
            if isinstance(value, dict):
                to_str += self.__beatiful_print(value, indent+1)
            elif isinstance(value, list):
                to_str += self.__print(', '.join(value), indent+1)
            elif isinstance(value, tuple):
                to_str += self.__print(f'{value[0]}\xc2\xb0 N, {value[1]}\xc2\xb0 W', indent+1)
            else:
                to_str += self.__print(value, indent+1)
        return to_str

    def __str__(self):
        return self.__beatiful_print(self.data, self.indent)

if __name__ == '__main__':
    data = dict(
        name='Vitor Nere',
        role='Software Engineer',
        location=(-15.6697181, -47.8526106),
        code=['Python', 'Javascript', 'Typescript', 'Java', 'Kotlin'],
        technologies=dict(
            backEnd=['Django', 'Flask', 'FastAPI',
                     'Spring Boot Framework', 'Express', 'Nest.js'],
            frontEnd=['React', 'Next.js', 'Angular'],
            mobileApp=['React Native', 'Ionic'],
            desktopApp=['Electron', 'PWA'],
            devOps=['AWS', 'Docker', 'Serverless', 'Hasura'],
            databases=['PostgresSQL', 'DynamoDB'],
            misc=['Firebase', 'Unit Tests', 'GraphQL', 'Redux']
        )
    )
    vitor_nere = SoftwareEngineer(data)
    print(vitor_nere)
```
<img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="60"> <em><b>I love connecting with different people</b> so if you want to say <b>hi, I'll be happy to meet you more!</b> 😊</em>

---
# &#x1f4c8; GitHub Stats

[![Profile Stats](https://github-readme-stats.vercel.app/api?username=vitornere&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)

## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=vitornere&theme=tokyonight&column=7)](https://github.com/ryo-ma/github-profile-trophy)

### 🧑‍💻  This week, I spent my time on:

[![vitornere's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=vitornere&line_height=27&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=0e1116)](https://github.com/anuraghazra/github-readme-stats)

<!--
**vitornere/vitornere** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
