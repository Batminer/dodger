# Traefik2 #

To run docker-compose up you have to adapt `.env` and do

> ```sudo chmod 600 -R ./letsencrypt```

as well as change your E-Mail in:

>  ```--certificatesresolvers.mytlschallenge.acme.email=YOUR_EMAIL```

(I wasn't able to resolve it with a `.env` file, please feel free to contribute)