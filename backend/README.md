#Instalações

	yarn -v
	npm install --global yarn
	npx create-react-app frontend --template typescript

	git init
	
	git add .
	
	git commit -m "Project created"
	
	git remote add origin <seu endereço>
	
	git push -u origin main

#Bootstrap

	yarn add bootstrap
	(index.tsx) import 'bootstrap/dist/css/bootstrap.css';

#Apex Charts

	yarn add apexcharts
	yarn add react-apexcharts

#Instalar React Router DOM

	yarn add react-router-dom
	yarn add @types/react-router-dom -D

#Instalar Axios
	
	yarn add axios

#Instalar date-fns ao projeto
	
	yarn add date-fns

#Ações no Heroku

	heroku -v
	heroku login
	heroku git:remote -a <nome-do-app>
	git remote -v
	git subtree push --prefix backend heroku main

#Link Netlify - https://60971b862b29e300074ba49b--diegoadricandido-dsvendas.netlify.app/