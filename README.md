<h3 align="center">Shinyproxy Generative AI meadow</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
  [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)]() 

</div>

---

<p align="center"> Configured shinyproxy for multiple showcase application.
    <br> 
</p>

```
git clone https://github.com/LilianDK/shinyproxy_generative_ai_meadow.git
```

```
docker compose -f docker-compose-shinyproxy.yml up
```
Enter in browser: localhost:8080
![grafik](https://github.com/LilianDK/shinyproxy_generative_ai_meadow/assets/13328959/0280c552-f1b6-4f2a-a5b0-bb6b6eb10c20)

users:
    - name: admin
      password: admin
      groups: admin
    - name: user
      password: password
      groups: user

![grafik](https://github.com/LilianDK/shinyproxy_generative_ai_meadow/assets/13328959/61b3bc8a-a80e-450e-9803-6431aa6884b4)
