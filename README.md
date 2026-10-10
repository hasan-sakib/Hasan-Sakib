<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0D1117,50:0077B6,100:00D8A7&height=230&section=header&text=Md.%20Sakib%20Hasan&fontSize=52&fontColor=FFFFFF&fontAlignY=38&desc=AI%20Engineer%20%C2%B7%20Full%20Stack%20Developer&descSize=18&descAlignY=60&animation=twinkling" width="100%" alt="Md. Sakib Hasan — AI Engineer · Full Stack Developer"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2800&pause=900&color=00D8A7&center=true&vCenter=true&width=700&height=40&lines=%24+whoami+%E2%86%92+AI+Engineer+%2B+Full+Stack+Dev;%24+focus+--areas+%22computer-vision%22+%22self-supervised-learning%22;%24+train+model+%26%26+ship+api+%26%26+build+ui;%24+echo+%22research+rigor+meets+software+engineering%22" alt="Terminal typing animation"/>

<br/><br/>

<a href="https://www.linkedin.com/in/md-sakib-hasan-356304272/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn"/></a>
<a href="mailto:sakibmunshi013@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email"/></a>
<a href="https://raw.githubusercontent.com/hasan-sakib/hasan-sakib/main/Md.%20Sakib%20Hasan.pdf"><img src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-FF6B35?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=0D1117" alt="Résumé"/></a>
<a href="https://github.com/hasan-sakib"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" alt="GitHub"/></a>

<br/>

<img src="https://img.shields.io/badge/Dhaka%2C%20Bangladesh-26A69A?style=flat-square&logo=googlemaps&logoColor=white&labelColor=0D1117" alt="Location"/>
<img src="https://img.shields.io/badge/Remote-0077B6?style=flat-square&logo=protonvpn&logoColor=white&labelColor=0D1117" alt="Remote"/>
<img src="https://img.shields.io/badge/Open%20to-Collaboration-00D8A7?style=flat-square&logo=handshake&logoColor=white&labelColor=0D1117" alt="Open to collaboration"/>
<img src="https://komarev.com/ghpvc/?username=hasan-sakib&label=Profile%20views&color=0077B6&style=flat-square&labelColor=0D1117" alt="Profile views"/>

</div>

<br/>

## `~/about.py`

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

## `$ git log --graph --oneline`

```text
* 2026-05  (HEAD) M.Sc., Artificial Intelligence & Machine Learning
|                  East West University, Dhaka
|                  └─ research: self-supervised representation learning
|
* 2026-02  Full-Stack Developer & AI Engineer
                   Acciptra (Remote)
                   └─ building full-stack AI features, from model to interface
```

<br/>

## `$ cat pipeline.mmd`

```mermaid
flowchart LR
    A["🔬 Research<br/><sub>frame the problem</sub>"] --> B["🧪 Model<br/><sub>train · evaluate</sub>"]
    B --> C["⚡ Serve<br/><sub>FastAPI · Docker</sub>"]
    C --> D["🖥️ Product<br/><sub>React · TypeScript</sub>"]
    D -. "feedback + new data" .-> A

    classDef n fill:#0D1117,stroke:#00D8A7,stroke-width:2px,color:#C9D1D9;
    class A,B,C,D n;
```

<br/>

## `$ ls ./stack`

<table>
<tr>
<td width="150" valign="top"><b>🤖 AI / ML</b></td>
<td>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,keras,opencv&perline=8" alt="PyTorch, TensorFlow, Keras, OpenCV"/><br/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white&labelColor=0D1117" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black&labelColor=0D1117" alt="Hugging Face Transformers"/>
<img src="https://img.shields.io/badge/YOLO-111F68?style=flat-square&labelColor=0D1117" alt="YOLO"/>
<img src="https://img.shields.io/badge/LLMs-412991?style=flat-square&logo=openai&logoColor=white&labelColor=0D1117" alt="LLMs"/>
</td>
</tr>
<tr>
<td valign="top"><b>📊 Data</b></td>
<td>
<img src="https://skillicons.dev/icons?i=numpy,pandas,matplotlib&perline=8" alt="NumPy, pandas, Matplotlib"/><br/>
<img src="https://img.shields.io/badge/Seaborn-0C55AA?style=flat-square&logo=python&logoColor=white&labelColor=0D1117" alt="Seaborn"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white&labelColor=0D1117" alt="Jupyter"/>
<img src="https://img.shields.io/badge/Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white&labelColor=0D1117" alt="Google Colab"/>
</td>
</tr>
<tr>
<td valign="top"><b>💬 Languages</b></td>
<td><img src="https://skillicons.dev/icons?i=py,ts,js,java,c,mysql&perline=8" alt="Python, TypeScript, JavaScript, Java, C, SQL"/></td>
</tr>
<tr>
<td valign="top"><b>🔌 Backend</b></td>
<td>
<img src="https://skillicons.dev/icons?i=fastapi,django,flask,nodejs,express,graphql&perline=8" alt="FastAPI, Django, Flask, Node.js, Express, GraphQL"/>
<img src="https://img.shields.io/badge/REST-FF6B6B?style=flat-square&logo=json&logoColor=white&labelColor=0D1117" alt="REST"/>
</td>
</tr>
<tr>
<td valign="top"><b>🎨 Frontend</b></td>
<td><img src="https://skillicons.dev/icons?i=react,tailwind,bootstrap,html,css&perline=8" alt="React, Tailwind, Bootstrap, HTML, CSS"/></td>
</tr>
<tr>
<td valign="top"><b>🗄️ Data Stores</b></td>
<td><img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb&perline=8" alt="PostgreSQL, MySQL, MongoDB"/></td>
</tr>
<tr>
<td valign="top"><b>☁️ Infra</b></td>
<td><img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions,git,linux&perline=8" alt="Docker, Kubernetes, GitHub Actions, Git, Linux"/></td>
</tr>
</table>

<br/>

## `$ gh stats --me`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=hasan-sakib&show_icons=true&hide_border=true&bg_color=0D1117&title_color=00D8A7&icon_color=0077B6&text_color=C9D1D9&ring_color=00D8A7&include_all_commits=true" height="165" alt="GitHub stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hasan-sakib&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=00D8A7&text_color=C9D1D9" height="165" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=hasan-sakib&hide_border=true&background=0D1117&stroke=0D1117&ring=00D8A7&fire=FF6B35&currStreakLabel=00D8A7&sideLabels=C9D1D9&dates=8B949E" height="165" alt="Contribution streak"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=hasan-sakib&bg_color=0D1117&color=C9D1D9&title_color=00D8A7&line=00D8A7&point=FFFFFF&area=true&area_color=0077B6&hide_border=true&custom_title=Contribution%20Activity" width="98%" alt="Contribution graph"/>

</div>

<br/>

## `$ ./snake --eat contributions`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hasan-sakib/hasan-sakib/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hasan-sakib/hasan-sakib/output/github-snake.svg"/>
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/hasan-sakib/hasan-sakib/output/github-snake-dark.svg" width="100%"/>
</picture>

</div>

<br/>

## `$ cat currently.yml`

```yaml
building:    Full-stack AI features at Acciptra
researching: Self-supervised representation learning (M.Sc.)
studying:    AI & ML at East West University
open_to:
  - Computer vision collaborations
  - Applied ML projects
  - Full-stack builds
```

<br/>

<div align="center">

## `$ ping sakib`

```text
64 bytes from sakib: AI/ML projects · full-stack builds · research collaborations
```

<a href="mailto:sakibmunshi013@gmail.com"><img src="https://img.shields.io/badge/sakibmunshi013%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email"/></a>
<a href="https://www.linkedin.com/in/md-sakib-hasan-356304272/"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn"/></a>

<sub><i>Building intelligent systems, one model at a time.</i></sub>

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:00D8A7,50:0077B6,100:0D1117&height=110&section=footer" width="100%" alt=""/>

</div>
