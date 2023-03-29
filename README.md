Please make sure that you have Python, pip, and pipenv installed before running the Backend. Additionally, do not forget to run Pipenv shell before starting the Backend.

If you plan on hosting this project on the cloud, please note that the Frontend will only work with Node.js version 16.x.x.

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
UNSPLASH_KEY=<apikey>
```

- Save modified **.env.local** file


# spashproject
