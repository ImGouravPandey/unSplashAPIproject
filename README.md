IMPORTANT: this project requires python , pip , and pipenv installed. Don't forget to run Pipenv shell before running Backend. 
Also if hosting on cloud, this Frontend only works on Nodejs version 16.x.x

## Initial configuration

- Create account at the https://unsplash.com
- At the https://unsplash.com/oauth/applications create new **demo** application with title **"Images Gallery"**.
  Demo applications are limited to 50 requests per hour
- In the newly created application find section **"Keys"** and copy **Access Key**
- In the **api** folder create file **.env.local** and add there following line:

```
UNSPLASH_KEY=<Paste copied Access Key here>
```

**EXAMPLE** with fake code(don't try to use it in your app):

```
UNSPLASH_KEY=2MJvApIkV13hfg2LmQlneILfHoJ2ttlzSdPKefGOyKM
```

- Save modified **.env.local** file


