## Multiroom chat production ready. Node.js + Socket.IO + cloudControl

* 1. Install Node.js, npm and cctrl command line app
* 2. `git clone git@github.com:fern4lvarez/socketiochatrooms.git`
* 3. `[sudo] npm install`
* 4. To run locally: `node app.js`
* 5. Create app on cloudControl: `cctrlapp APP_NAME create nodejs`
* 6. Push and deploy:

```
$ cctrlapp APP_NAME/default push

$ cctrlapp APP_NAME/default deploy
```

* 7. Check it out on APP_NAME.cloudcontrolapp.com
