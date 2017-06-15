This project serves as the public facing restful api for the tutoring forum app: at http://tutoring-forum.herokuapp.com/.

Heroku dynos only let you provide one port to the outside world. (https://github.com/facebookincubator/create-react-app/issues/639) Thus, the app has a second heroku app which serves as the public restful api for our primary app. 

Repo for tutoring forum app: https://github.com/AumitLeon/tutoring-forum