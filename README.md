<p align="center">
  <a href="https://dev.to/vumdao">
    <img alt="How to curl single file using access token in gitlab" src="https://dev-to-uploads.s3.amazonaws.com/i/qprr8isej3qbsup4v44p.png" width="1000" />
  </a>
</p>


## What’s In This Document 
- [Create access token](#-Create-access-token)
- [Get project ID to call API](#-Get-project-ID-to-call-API)
- [Get raw file from repository](#-Get-raw-file-from-repository)


### 🚀 **[Create access token](#-Create-access-token)**
- Go to `User Setttings` -> `Access Tokens`

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/4mve0fn40k5wnkp2e6cp.png)

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/oul9w4o5ebpobo948aw2.png)

### 🚀 **[Get project ID to call API](#-Get-project-ID-to-call-API)**
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/5g1ub7tnfdal48pz5noj.png)

### 🚀 **[Get raw file from repository](#-Get-raw-file-from-repository)**
Ref: https://docs.gitlab.com/ee/api/repository_files.html#get-raw-file-from-repository
- Format: `GET /projects/:id/repository/files/:file_path/raw`
- eg. `curl --header "PRIVATE-TOKEN: <your_access_token>" "https://gitlab.example.com/api/v4/projects/13083/repository/files/app%2Fmodels%2Fkey%2Erb/raw?ref=master"`

- To get file `scripts/run.sh` in project the url is
```
curl --header "PRIVATE-TOKEN: <your_access_token>" "https://gitlab.example.com/api/v4/projects/13083/repository/files/scripts%2Frun.sh/raw?ref=master"
```

### **Visit wwww.cloudopz.co to get more**

<h3 align="center">
  <a href="https://dev.to/vumdao">:stars: Blog</a>
  <span> · </span>
  <a href="https://vumdao.hashnode.dev/">Web</a>
  <span> · </span>
  <a href="https://www.linkedin.com/in/vu-dao-9280ab43/">Linkedin</a>
  <span> · </span>
  <a href="https://www.linkedin.com/groups/12488649/">Group</a>
  <span> · </span>
  <a href="https://www.facebook.com/CloudOpz-104917804863956">Page</a>
  <span> · </span>
  <a href="https://twitter.com/VuDao81124667">Twitter :stars:</a>
</h3>

