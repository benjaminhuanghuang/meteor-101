## Reference 
    - 用Meteor构建App程序
        - http://m.maiziedu.com/course/342/
        - https://github.com/kevingzhang/meteor101cam

## Install Meteor
```
    curl https://install.meteor.com/ | sh
```

## Create app
```
    meteor create ./my_app

    meteor create --bare to create an empty app.
    meteor create --full to create a scaffolded app.
```

## Create libraries
```
    meteor add coffeescript
    meteor add less

    meteor add mdg:camera
```

## Mobile simulator and sdk
```
    meteor add-platform ios 
    meteor add-platform android

    meteor install-sdk android

    meteor run ios
    meteor run android
```

## Hot code push

