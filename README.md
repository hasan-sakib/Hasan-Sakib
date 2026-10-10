<div align="center">

<img src="assets/hero.svg" width="100%" alt="Md. Sakib Hasan — AI Engineer · Full Stack Developer"/>

<br/>

<a href="https://www.linkedin.com/in/md-sakib-hasan-356304272/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn"/></a>
<a href="mailto:sakibmunshi013@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email"/></a>
<a href="https://raw.githubusercontent.com/hasan-sakib/hasan-sakib/main/Md.%20Sakib%20Hasan.pdf"><img src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-FF6B35?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=0D1117" alt="Résumé"/></a>
<a href="https://github.com/hasan-sakib"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" alt="GitHub"/></a>

<img src="https://img.shields.io/badge/Dhaka%2C%20Bangladesh-26A69A?style=flat-square&logo=googlemaps&logoColor=white&labelColor=0D1117" alt="Location"/>
<img src="https://img.shields.io/badge/Remote-0077B6?style=flat-square&logo=protonvpn&logoColor=white&labelColor=0D1117" alt="Remote"/>
<img src="https://komarev.com/ghpvc/?username=hasan-sakib&label=Profile%20views&color=0077B6&style=flat-square&labelColor=0D1117" alt="Profile views"/>

</div>

<br/>

<img src="assets/h-about.svg" width="100%" alt="01 — About"/>

```python
from dataclasses import dataclass, field


@dataclass
class SakibHasan:
    name: str = "Md. Sakib Hasan"
    roles: tuple = ("AI Engineer", "Full Stack Developer")
    location: str = "Dhaka, Bangladesh"
    education: str = "M.Sc. AI & ML @ East West University"
    working_at: str = "Acciptra (Remote)"

    focus: list = field(default_factory=lambda: [
        "Computer Vision",            # detection · segmentation · classification
        "Self-Supervised Learning",   # strong representations, minimal labels
        "Model Engineering",          # architectures · transfer learning · training
        "Full Stack Delivery",        # APIs + UIs that serve ML in production
    ])

    philosophy: str = (
        "Research-grade models only matter once they ship. "
        "I work on the seam between the two."
    )

    def ship(self, model):
        return model.train().evaluate().serve(api="FastAPI").wrap(ui="React")
```

<br/>

<img src="assets/h-focus.svg" width="100%" alt="02 — Where I Go Deep"/>
<img src="assets/focus.svg" width="100%" alt="Focus areas: Computer Vision, Self-Supervised Learning, Model Engineering, Full-Stack Delivery"/>

<br/>

<img src="assets/h-journey.svg" width="100%" alt="03 — Journey"/>
<img src="assets/journey.svg" width="100%" alt="M.Sc. in AI & ML at East West University (May 2026 – present); Full-Stack Developer & AI Engineer at Acciptra (Feb 2026 – present)"/>

<br/>

<img src="assets/h-pipeline.svg" width="100%" alt="04 — How I Work"/>
<img src="assets/pipeline.svg" width="100%" alt="Workflow: Research, Model, Serve, Product, with a feedback loop back to Research"/>

<br/>

<img src="assets/h-stack.svg" width="100%" alt="05 — Tech Stack"/>

<table>
<tr>
<td width="150" valign="top"><b>🤖 AI / ML</b></td>
<td>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,keras,opencv&perline=8&theme=dark" alt="PyTorch, TensorFlow, Keras, OpenCV"/><br/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white&labelColor=0D1117" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black&labelColor=0D1117" alt="Hugging Face Transformers"/>
<img src="https://img.shields.io/badge/YOLO-111F68?style=flat-square&labelColor=0D1117" alt="YOLO"/>
<img src="https://img.shields.io/badge/LLMs-412991?style=flat-square&logo=openai&logoColor=white&labelColor=0D1117" alt="LLMs"/>
</td>
</tr>
<tr>
<td valign="top"><b>📊 Data</b></td>
<td>
<img src="https://skillicons.dev/icons?i=numpy,pandas,matplotlib&perline=8&theme=dark" alt="NumPy, pandas, Matplotlib"/><br/>
<img src="https://img.shields.io/badge/Seaborn-0C55AA?style=flat-square&logo=python&logoColor=white&labelColor=0D1117" alt="Seaborn"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white&labelColor=0D1117" alt="Jupyter"/>
<img src="https://img.shields.io/badge/Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white&labelColor=0D1117" alt="Google Colab"/>
</td>
</tr>
<tr>
<td valign="top"><b>💬 Languages</b></td>
<td><img src="https://skillicons.dev/icons?i=py,ts,js,java,c,mysql&perline=8&theme=dark" alt="Python, TypeScript, JavaScript, Java, C, SQL"/></td>
</tr>
<tr>
<td valign="top"><b>🔌 Backend</b></td>
<td>
<img src="https://skillicons.dev/icons?i=fastapi,django,flask,nodejs,express,graphql&perline=8&theme=dark" alt="FastAPI, Django, Flask, Node.js, Express, GraphQL"/>
<img src="https://img.shields.io/badge/REST-FF6B6B?style=flat-square&logo=json&logoColor=white&labelColor=0D1117" alt="REST"/>
</td>
</tr>
<tr>
<td valign="top"><b>🎨 Frontend</b></td>
<td><img src="https://skillicons.dev/icons?i=react,tailwind,bootstrap,html,css&perline=8&theme=dark" alt="React, Tailwind, Bootstrap, HTML, CSS"/></td>
</tr>
<tr>
<td valign="top"><b>🗄️ Data Stores</b></td>
<td><img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb&perline=8&theme=dark" alt="PostgreSQL, MySQL, MongoDB"/></td>
</tr>
<tr>
<td valign="top"><b>☁️ Infra</b></td>
<td><img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions,git,linux&perline=8&theme=dark" alt="Docker, Kubernetes, GitHub Actions, Git, Linux"/></td>
</tr>
</table>

<br/>

<img src="assets/h-stats.svg" width="100%" alt="06 — GitHub Stats"/>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=hasan-sakib&show_icons=true&hide_border=true&bg_color=0D1117&title_color=00D8A7&icon_color=0077B6&text_color=C9D1D9&ring_color=00D8A7&include_all_commits=true" height="165" alt="GitHub stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hasan-sakib&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=00D8A7&text_color=C9D1D9" height="165" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=hasan-sakib&hide_border=true&background=0D1117&stroke=0D1117&ring=00D8A7&fire=FF6B35&currStreakLabel=00D8A7&sideLabels=C9D1D9&dates=8B949E" height="165" alt="Contribution streak"/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=hasan-sakib&theme=github_dark" height="150" alt="Profile details and contribution history"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=hasan-sakib&theme=github_dark&utcOffset=6" height="150" alt="Commits by hour of day"/>

</div>

<br/>

<img src="assets/h-snake.svg" width="100%" alt="07 — Contributions"/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hasan-sakib/hasan-sakib/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hasan-sakib/hasan-sakib/output/github-snake.svg"/>
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/hasan-sakib/hasan-sakib/output/github-snake-dark.svg" width="100%"/>
</picture>

</div>

<br/>

<img src="assets/h-currently.svg" width="100%" alt="08 — Currently"/>
<img src="assets/currently.svg" width="100%" alt="Building full-stack AI features at Acciptra; researching self-supervised learning; open to collaboration"/>

<br/>

<img src="assets/h-contact.svg" width="100%" alt="09 — Contact"/>
<a href="mailto:sakibmunshi013@gmail.com"><img src="assets/contact.svg" width="100%" alt="Let's build something — sakibmunshi013@gmail.com"/></a>

<div align="center">

<a href="mailto:sakibmunshi013@gmail.com"><img src="https://img.shields.io/badge/Email%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email"/></a>
<a href="https://www.linkedin.com/in/md-sakib-hasan-356304272/"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn"/></a>

<sub><i>Building intelligent systems, one model at a time.</i></sub>

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:00D8A7,50:0077B6,100:0D1117&height=110&section=footer" width="100%" alt=""/>

</div>
