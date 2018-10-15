# Angular Patient CRUD application with Aidbox


## Clone repository

``` bash
 $ git clone https://github.com/HealthSamurai/aidbox-angular-sample.git
 $ cd aidbox-angular-sample

```

##  Configure Base URL

### Aidbox.Dev

If you use Aidbox.Dev as a backend, you need specify `AIDBOX_URL` http://localhost:8888

``` typescript
export const environment = {
  AIDBOX_URL : "http://localhost:8888"
}
```

### Aidbox.Coud

When you want run this sample application with Aidbox.Cloud you need
specify `AIDBOX_URL` as https://<YOUR_BOX_NAME>.aidbox.app.

``` typescript
export const environment = {
  AIDBOX_URL : "https://<YOUR_BOX_NAME>.aidbox.app"
}
```

## Installation and start

``` bash
 $ npm install
 $ npm install -g @angular/cli 
 $ ng serve

```

Open in browser [http://localhost:4200](http://localhost:4200)

![asset/img/screen.png](asset/img/screen.png)



