<br />
<div align="center">
  <h2 align="center"> <img align="center" alt="PrivateBin" src="https://privatebin.info/theme/img/icon.svg"/> Private Bin</h2>
  <h4 align="center">This repository has files to configure your Private Bin using Docker.</h4>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#preliminarydetails">Preliminary Details</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>

## Preliminary Details:
- Files in the repo:
  - [To create Deployment](DeploymentWithService.yml)
  - [To create Pod](PodWithService.yml)
  - [Nginx Conf](nginx.conf)

## Usage
You can follow below steps to configure:
- Deploy as Deployment with Service:
  - ```$ kubectl create -f DeploymentWithService.yml```
- Deploy as Pod with Service:
  - ```$ kubectl create -f PodWithService.yml```
- Nginx Conf for Proxy pass to redirect using SSL:
  - ```$ kubectl create -f DeploymentWithService.yml```


<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

[![PrivateBin][PrivateBin.js]][PrivateBin-url] [![Kubernetes][Kubernetes.js]][Kubernetes-url] [![Nginx][Nginx.js]][Nginx-url]


[PrivateBin.js]: https://img.shields.io/badge/privatebin-FFD700?style=for-the-badge&logo=lock&logoColor=black
[PrivateBin-url]: https://privatebin.info/
[Kubernetes.js]: https://img.shields.io/badge/kubernetes-007BFF?style=for-the-badge&logo=kubernetes&logoColor=white
[Kubernetes-url]: https://kubernetes.io/
[Nginx.js]: https://img.shields.io/badge/nginx-28a745?style=for-the-badge&logo=nginx&logoColor=white
[Nginx-url]: https://www.nginx.com
[pbicon]: https://privatebin.info/theme/img/icon.svg
