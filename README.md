#Uber Style Platform
=============

Group-bounded, invite-only, carpooling platform

##Launch Docker images
<li>docker-compose -f local.yml build</li>  
<li>docker-compose -f local.yml up</li>

##Set a monitor over Django
<li>set COMPOSE_FILE=local.yml</li>
<li>docker rm -f uber-style-platform_django_1</li>
<li>docker-compose run --rm --service-ports django</li>   

##Launch enviroment
<li>python3 -m venv uber-mock-env</li>
<li>uber-mock-env\Scripts\activate</li>  
<li>pip3 install -r local.txt</li>