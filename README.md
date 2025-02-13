# Introduction
The `ops-website` project is a simple webpage hosted on Nginx.  

To release a new version of the website:  
- Modify the contents of the `ops-website/myapp/templates` folder  
- Increase the chart version  
- Push the code  
- Execute [Publish Helm Chart](https://github.com/BrutalHex/ops-website/actions/workflows/release.yaml) in GitHub  

For more details, refer to the [ops-infra](https://github.com/BrutalHex/ops-infra) repository.  

This project creates a basic Helm repository using GitHub Pages.  


# Future fixes
- fix the index.html look.
- setup a sophisticated helm chart repository.