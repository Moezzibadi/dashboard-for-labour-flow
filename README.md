# dashboard for labour flow in france work zones
 Intra-regional and inter-regional labor flows over the last 20 or so years
 
The app is too large to be run by Heroku (Slug size 1.1G (max is 500M)

Commands for Heroku by Voila:

Launch local : voila MyApp.ipynb<br />
heroku login<br />
heroku create<br />
heroku apps:rename dashboard-for-labour-flow --app ....<br />
Clone from Desktop git
heroku git:remote -a dashboard-for-labour-flow<br />
git push heroku main<br />
heroku open<br />
To destroy : heroku apps:destroy<br />
Debug : heroku logs -n 200<br />  
