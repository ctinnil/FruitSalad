## Welcome to FruitSalad

FruitSalad represents our POC for a full **reactive WiFi honeypot**. Try it out, express your opinion and experience to improve the framework and minimize the attack surface for a better, safer, quicker, and opener Internet.

![fruitsalad 001](https://user-images.githubusercontent.com/69745175/121582920-4c2e1580-ca38-11eb-911b-c905587ddcb5.png)

<p align="center">
  <a href="https://doi.org/10.5281/zenodo.4915653"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.4915653.svg" alt="DOI"></a>
  <a href="https://twitter.com/intent/tweet?text=FruitSalad+-+a+reactive+WiFi+honeypot&amp;url=https%3A%2F%2Fgithub.com%2Fctinnil%FruitSalad.git&amp;via=ctinnil">
      <img src="https://img.shields.io/twitter/url?url=https%3A%2F%2Fgithub.com%2Fctinnil%FruitSalad.git" alt="Tweet">
  </a>
</p>

The project's purpose is to showcase the advantages of a Reactive WiFi honeypot system to deter potential attackers that engage in deauthentication probing to gather EAPOL handshakes and gain unauthorized access to victim wireless networks.
We focused on WPA since today's wireless landscape lack Open and WEP secured networks, even for embedded devices and IoT systems.
The Jupyter notebooks follow the ML well-established lifecycle:
-	Mission definition
-	Dataset preparation
-	Data exploitation  
-	Model construction 
-	and Deployment 

### Some helpful remarks to get you started 

* You may encounter difficulties in viewing the .ipynb files. This issue is well known in the Github community ( [#reference](https://github.com/jupyter/notebook/issues/3035) ). To be sure, here is a workaround. All you need to do is visit [nbviewer](https://nbviewer.jupyter.org/) and pass the desired notebook link to inspect it quickly and effortlessly. 

* As you have probably noticed by now, I used [Google Colab]( https://colab.research.google.com/) to conduct my POC. To get your own training data and monitor for future attacks, you need to connect the Colab notebook to a locally hosted Jupyter Server. I have used Kali Linux as my based system due to its built-in variety of tools. Find below full specs and integration workflow.

1. Run the following commands:
```zsh
python3 -m pip install jupyterlab jupyter_http_over_ws
jupyter serverextension enable --py jupyter_http_over_ws
jupyter notebook  --NotebookApp.allow_origin='https://colab.research.google.com'   --port=8888   --NotebookApp.port_retries=0
```
2. Now go to Colab, click the "Connect" button, select "Connect to local runtime", and enter the URL yelled by the last command from the previous batch.

### Buy Me a Coffee

<just a placeholder>
  https://www.buymeacoffee.com/

### Repository Citation

  <just a placeholder>
    https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/archiving-a-github-repository/referencing-and-citing-content
    https://github.com/AASJournals/Tutorials/blob/master/Repositories/CitingRepositories.md
