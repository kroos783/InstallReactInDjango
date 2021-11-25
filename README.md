# Install React In Django :

#### Requirements :
- 📙 VsCode Download: https://code.visualstudio.com/download
- 📘 Python Download: https://www.python.org/
- 📘📕 Node.js & NPM: https://www.npmjs.com/get-npm
- 📘🔗 Fix Pip (Windows): https://www.youtube.com/watch?v=AdUZA...
- 📘🔗 Fix Pip (Mac): https://www.youtube.com/watch?v=E-WhA...

## 1. Django :

#### 1.1 Install Django : 
```
pip install django
pip install django djangorestframework
```

#### 1.2 Create django project :
```
django-admin startproject NameOfProject
```

***ne pas oublier d'entrer dans le dossier du project :***
```
cd .\NameOfProject\
```

#### 1.3 Create django API :
```
django-admin startapp NameOfApi
```

***ne pas oublier de parametrer les settings et les urls du project :***
```
Dossier project => settings.py => INSTALLED_APPS => 'NameOfAPI'
Dossier project => urls.py => urlpatterns => path("", include("network.urls")),
```

## 2. Create new API Front-end :

#### 2.1 Create new API Front-end :
```
django-admin startapp frontend
```

#### 2.2 Create new folders :
- frontend/templates
- frontend/templates/frontend
- frontend/static
- frontend/static/
- frontend/static/css
- frontend/static/frontend
- frontend/static/images
- frontend/src
- frontend/src/components

## 3. React.js :

***Essayer la commande npm et entrer dans le dossier frontend :***
```
npm
cd .\frontend\
```

#### 3.1 init react : 
```
npm init -y 
```

#### 3.2 install webpack react : 
```
npm i webpack webpack-cli --save-dev
```

#### 3.3 install babel react : 
```
npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
```

#### 3.4 install react-dom : 
```
npm i react react-dom --save-dev
```

#### 3.5 install material ui react : 
```
npm install @material-ui/core
```

#### 3.6 install plugin babel react : 
```
npm install @babel/plugin-proposal-class-properties
```

#### 3.7 install react router : 
```
npm install react-router-dom
```

#### 3.8 install material ui icons : 
```
npm install @material-ui/icons
```

