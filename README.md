<div align="center">
  <h1 align="center">Austin M. Wallace</h1>

[![neovim][neovim-shield]][neovim-url]
[![lua][lua-shield]][lua-url]
[![python][python-shield]][python-url]
[![R][R-shield]][R-url]
[![javascript][javascript-shield]][javascript-url]
[![html][html-shield]][html-url]
[![c][c-shield]][c-url]
[![cpp][cpp-shield]][cpp-url]
[![go][go-shield]][go-url]
[![rust][rust-shield]][rust-url]
[![latex][latex-shield]][latex-url]
[![markdown][md-shield]][md-url]
[![bash][bash-shield]][bash-url]
[![jupyter][jupyter-shield]][jupyter-url]
[![yarn][yarn-shield]][yarn-url]
[![react][react-shield]][react-url]
[![redux][redux-shield]][redux-url]
[![rn][rn-shield]][rn-url]
[![expo][expo-shield]][expo-url]
[![node][node-shield]][node-url]
[![flask][flask-shield]][flask-url]
[![sql][sql-shield]][sql-url]
[![postgresql][postgresql-shield]][postgresql-url]
</div>

- 🔭 **Graduate Student Researcher** at Georgia Tech in the Sherrill Group
- 💻 **Neovim** ([nvim config](https://github.com/Awallace3/nvim_lazy))
- 🌱 Actively Learning more about: 
  - **PyTorch**
  - **C++**

# Research Interests
- Symmetry Adapted Perturbation Theory (SAPT) for understanding drug design
- Inexpensive dispersion methods for accurate noncovalent interaction energies ([d4_dimers](https://github.com/Awallace3/d4_dimers))
- Improved docking scoring functions
- Machine Learned Force Field (MLFF) development
- Highly distributed parallelization for high-throughput dataset generation
  ([hrcl_jobs](https://github.com/Awallace3/hierarchical_python_jobs))
- AI tools and agents ([OpenAI Computational Chemistry Assistant](https://chatgpt.com/g/g-67d6215e7d5c81918645f4feb022890a-quantum-chemistry-assistant))

# Tutorials
## QCArchive+Psi4+QCMLForge
- [QCArchive+Psi4+QCMLForge+Cybershuttle](https://github.com/Awallace3/psi4_interaction_energy_cybershuttle/tree/main) 
- Demonstrates how to setup a QCArchive/QCFractal database/server for
interfacing through python:
  - Executes computations on Cybershuttle HPC resources
  - Runs Psi4 SinglePoint energies and QCManyBody calculations as datasets
  - Visualize benchmarking results
  - Trains AP-Net2 related models (transfer learning and $\Delta$ learning) using
    computed datasets through QCMLForge.


# Websites
## vergil.chemistry.gatech.edu (Sherrill Group Website)
- [vergil.chemistry.gatech.edu](https://vergil.chemistry.gatech.edu/)
- Collaborated with [Caroline Glick](https://github.com/carolinesargent), [C.
  David Sherrill](https://github.com/CDSherrill), and Sherrill group to create
  website using `Flask`, `HTML/CSS`, and `SQL`
- Created users and blog functionality for members to update website news
- - Developed internal group paper/citation database synchronizing SQL/bibtex
- Deployed and maintain website

## DyesDB 
- [dyesdb.com](https://dyesdb.com/)
- Visualizes electronic excited state energies for thousands of Vis-NIR organic
  dyes for dye sensitized solar cells
  ([DOI:10.1039/D3DD00023K](https://doi.org/10.1039/D3DD00023K))
- Provides a browser interface for 0nset, a tool for computing the λ onset
  value for dyes
  ([DOI:10.1016/j.jqsrt.2021.107544](https://doi.org/10.1016/j.jqsrt.2021.107544))
- Wrote `React.js` frontend and `Flask` backend

## r410berry
- Collaborated with [mvee18](https://github.com/mvee18/mvee18) to create
  [r410berry.com](https://r410berry.com/) for the Computational Astrochemistry
  Research Group @ Ole Miss 
- Wrote the frontend in `React.js` 
- Deployed and maintained website on a Linode server

# Example Repositories
## Python
- [QCMLForge](https://github.com/awallace3/qcmlforge) is a package for
  training and inference of atomic and dimer machine learning models related to
  AP-Net models.
- [hrcl_jobs](https://github.com/awallace3/hrcl_jobs) provides functionality to distribute jobs on compute clusters
- Provides basic functionalities for interacting with SQL/PostgreSQL databases
- Example jobspecs for psi4, AutoDock Vina, AP-Net2, and OpenMM
## CPP
- [HF](https://github.com/awallace3/hf) is a simple SCF code written in CPP dependent on Psi4
## PyBind11 (Python+CPP)
- [d4_dimers](https://github.com/awallace3/d4_dimers) has python3 frontend for calling CPP submodule [dispersion](https://github.com/Awallace3/dispersion/tree/c7dcfb3995afadcb4afdc1ed7d4506a0951f269b) to accelerate -D4 damping function parameter fitting by over 400x.


<!-- # Containers 
- [dockerhub repositories](https://hub.docker.com/repositories/awallace43)
-->

<!-- <div align="center"> -->
<!-- <img height="137px" -->
<!-- src="https://github-readme-stats.vercel.app/api?username=Awallace3&include_all_commits=true&hide_title=true&hide_border=false&show_icons=true&include_all_commits=true&count_private=true&line_height=21&&theme=tokyonight&hide_rank=true" -->
<!-- /> -->
<!-- <div/> -->
<!--   <img height="137px" -->
<!-- src="https://github-readme-stats.vercel.app/api/top-langs/?username=Awallace3&hide_title=false&hide_border=false&layout=compact&langs_count=6&theme=tokyonight&count_private=true" -->
<!-- /> -->
<!---
<img height="137px"
src="https://github-readme-stats.vercel.app/api?username=Awallace3&include_all_commits=true&hide_title=true&hide_border=false&show_icons=true&include_all_commits=true&count_private=true&line_height=21&&theme=tokyonight"
/>
-->
<!--
![Metrics](https://metrics.lecoq.io/Awallace3?template=classic&repositories.forks=true&isocalendar=1&languages=1&habits=1&repositories=1&introduction=1&achievements=1&lines=1&stars=1&skyline=1&base=header%2C%20activity%2C%20community%2C%20repositories%2C%20metadata&base.indepth=false&base.hireable=false&base.skip=false&repositories.batch=100&repositories.forks=true&repositories.affiliations=owner&isocalendar=false&isocalendar.duration=full-year&languages=false&languages.limit=8&languages.threshold=0%25&languages.other=false&languages.colors=github&languages.sections=most-used&languages.indepth=false&languages.analysis.timeout=15&languages.analysis.timeout.repositories=7.5&languages.categories=markup%2C%20programming&languages.recent.categories=markup%2C%20programming&languages.recent.load=300&languages.recent.days=14&lines=false&lines.sections=base&lines.repositories.limit=4&lines.history.limit=1&stars=false&stars.limit=4&habits=false&habits.from=200&habits.days=14&habits.facts=true&habits.charts=false&habits.charts.type=classic&habits.trim=false&habits.languages.limit=8&habits.languages.threshold=0%25&repositories=false&repositories.featured=Awallace3%2Fqm_tools%2C%20Awallace3%2Fhierarchical_python_jobs&repositories.pinned=0&repositories.starred=0&repositories.random=0&repositories.order=featured%2C%20pinned%2C%20starred%2C%20random&achievements=false&achievements.threshold=A&achievements.secrets=true&achievements.display=detailed&achievements.limit=0&introduction=false&introduction.title=true&skyline=false&skyline.year=current-year&skyline.frames=60&skyline.quality=0.5&skyline.compatibility=false&skyline.settings=%7B%0A%20%20%22url%22%3A%20%22https%3A%2F%2Fskyline.github.com%2F%24%7Blogin%7D%2F%24%7Byear%7D%22%2C%0A%20%20%22ready%22%3A%20%22%5B...document.querySelectorAll('span')%5D.map(span%20%3D%3E%20span.innerText).includes('Share%20on%20Twitter')%22%2C%0A%20%20%22wait%22%3A%201%2C%0A%20%20%22hide%22%3A%20%22button%2C%20footer%2C%20a%22%0A%7D%0A&config.timezone=America%2FNew_York)
-->


<!---
<img height="137px"
src="https://github-readme-stats.vercel.app/api/top-langs/?username=Awallace3&hide_title=false&hide_border=false&layout=compact&langs_count=6&theme=tokyonight&count_private=true"
/>
<div/>
-->

## Contact Me

<p id="socialIcons" align="center">
    <a href="mailto:austinwallace196@gmail.com">
        <img alt="Gmail" src="https://img.shields.io/badge/austinwallace196@gmail.com-D14836?style=flat&logo=gmail&logoColor=white" /></a>
    <a href="https://linkedin.com/in/austin-wallace-42a5b3199" alt="LinkedIn">
        <img src="https://img.shields.io/badge/-Awallace3-blue?style=flat-square&logo=linkedin" /></a>
    <a href="https://instagram.com/austin_wallace1024" alt="Instagram">
        <img src="https://img.shields.io/badge/-austin_wallace1024-3F729B?style=flat-square&logo=instagram&logoColor=white" /></a>
    <a href="https://www.researchgate.net/profile/Austin-Wallace-7" alt="Instagram">
        <img src="https://img.shields.io/badge/Awallace3-00CCBB?style=flat-square&logo=ResearchGate&logoColor=white" /></a>
</p>


<!--
**Awallace3/Awallace3** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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


<!-- OS -->
[linux-shield]: https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black
[linux-url]: https://www.linux.org/
[debian-shield]: https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white
[debian-url]: https://www.debian.org/
[android-shield]: https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white
[android-url]: https://www.android.com/
[windows-shield]: https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white
[windows-url]: https://www.youtube.com/watch?v=zjedLeVGcfE&t=11s
<!-- programming languages -->
[java-shield]: https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white
[java-url]: https://www.java.com
[c-shield]: https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white
[c-url]: http://www.open-std.org/jtc1/sc22/wg14/
[cpp-shield]: https://img.shields.io/badge/c++-%2300599C.svg?style=flat-square&logo=c%2B%2B&logoColor=white
[cpp-url]: http://www.open-std.org/jtc1/sc22/wg14/
[bash-shield]: https://img.shields.io/badge/Bash_Script-353535?style=flat-square&logo=gnu-bash&logoColor=white
[bash-url]: https://www.gnu.org/software/bash/
[javascript-shield]: https://img.shields.io/badge/JavaScript-FFDD00?style=flat-square&logo=javascript&logoColor=black
[javascript-url]: https://www.javascript.com/
[python-shield]: https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54
[python-url]: https://www.python.org/
[go-shield]: https://img.shields.io/badge/Go-00ADD8.svg?style=flat-square&logo=go&logoColor=white
[go-url]: https://go.dev/
[rust-shield]: https://img.shields.io/badge/rust-%23000000.svg?style=flat-square&logo=rust&logoColor=white
[rust-url]: https://www.rust-lang.org/
[R-shield]: https://img.shields.io/badge/r-%23276DC3.svg?style=flat-square&logo=r&logoColor=white
[R-url]: https://www.r-project.org/
[lua-shield]: https://img.shields.io/badge/lua-%232C2D72.svg?style=flat-square&logo=lua&logoColor=white
[lua-url]: https://www.lua.org/
<!-- markdown languages -->
[html-shield]: https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white
[html-url]: https://www.html.it/
[latex-shield]: https://img.shields.io/badge/LaTeX-47A141?style=flat-square&logo=LaTeX&logoColor=white
[latex-url]: https://www.latex-project.org/
[css-shield]: https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white
[css-url]: https://www.w3schools.com/css/
[md-shield]: https://img.shields.io/badge/Markdown-575757.svg?style=flat-square&logo=markdown&logoColor=white
[md-url]: https://www.markdownguide.org/
[jupyter-shield]: https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat-square&logo=markdown&logoColor=white
[jupyter-url]: https://www.markdownguide.org/
<!-- Engine & IDE -->
[neovim-url]: https://neovim.io/
[neovim-shield]: https://img.shields.io/badge/NeoVim-%2357A143.svg?&style=flat-square&logo=neovim&logoColor=white
[vs-shield]: https://img.shields.io/badge/Visual_Studio-5C2D91?style=flat-square&logo=visual%20studio&logoColor=white
[vs-url]: https://visualstudio.microsoft.com/
[sublime-shield]: https://img.shields.io/badge/Sublime_Text-%23575757.svg?&style=flat-square&logo=sublime-text&logoColor=important
[sublime-url]: https://www.sublimetext.com/
<!-- Frameworks & Libraries -->
[flutter-shield]: https://img.shields.io/badge/Flutter-%2302569B.svg?style=flat-square&logo=Flutter&logoColor=white
[flutter-url]: https://flutter.dev/
[yarn-shield]: https://img.shields.io/badge/yarn-%232C8EBB.svg?style=flat-square&logo=yarn&logoColor=white
[yarn-url]: https://img.shields.io/badge/yarn-%232C8EBB.svg?style=flat-square&logo=yarn&logoColor=white

[react-shield]: https://img.shields.io/badge/react-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB
[react-url]: https://reactjs.org
[rn-shield]: https://img.shields.io/badge/react_native-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB
[rn-url]: https://www.reactnative.dev
[redux-shield]: https://img.shields.io/badge/redux-%23593d88.svg?style=flat-square&logo=redux&logoColor=white
[redux-url]: https://www.redux.js.org/
[node-shield]: https://img.shields.io/badge/node.js-6DA55F?style=flat-square&logo=next.js&logoColor=white 
[node-url]: https://www.nodejs.org

[flask-shield]: https://img.shields.io/badge/flask-%23000.svg?style=flat-sqaure&logo=flask&logoColor=white
[flask-url]: https://flask.palletsprojects.com
[expo-shield]: https://img.shields.io/badge/expo-1C1E24?style=flat-sqaure&logo=expo&logoColor=#D04A37 
[expo-url]: https://expo.dev
[sql-shield]: https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white
[sql-url]: https://learn.microsoft.com/en-us/sql/?view=sql-server-ver16
[postgresql-shield]: https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white
[postgresql-url]: https://www.postgresql.org/




<!-- Social Networks -->
[linkedin-shield]: https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/michele-righi/?locale=en_US
[researchgate-shield]: https://img.shields.io/badge/ResearchGate-00CCBB?style=flat-square&logo=ResearchGate&logoColor=white
[researchgate-url]: https://www.researchgate.net/profile/Austin-Wallace-7
<!-- Others -->
[raspberry-shield]: https://img.shields.io/badge/-RaspberryPi-C51A4A?style=flat-square&logo=Raspberry-Pi
[raspberry-url]: https://www.raspberrypi.org/

[coffee-shield]: https://img.shields.io/badge/Buy_Me_A_Coffee-F7DF1E?style=flat-square&logo=buy-me-a-coffee&logoColor=black
[coffee-url]: https://www.buymeacoffee.com/mikyll

<!-- https://paypal.me/mikyll98 -->
<!-- more badges: https://badgen.net/ and https://github.com/Ileriayo/markdown-badges#office -->

