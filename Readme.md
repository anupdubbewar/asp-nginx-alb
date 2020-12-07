Note: This branch is created only for testing the nginx load balancing is working or not.  Acutual branch should is used is master

- Clone the repository
# git clone https://github.com/anupdubbewar/asp-nginx-alb.git

- Change branch to test-code
# cd asp-nginx-alb
# git checkout test-code

- Run docker-compose up command 
# docker-compose -f docker-compose.yaml up --build -d

- Once above command completes, open you browser inspect using F12 and access your app. For next request clear the cache and try again.
