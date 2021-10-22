# docker-odoo
This is a plain Docker Template for any Odoo or PostgresSQL Version

# Using
1. Navigate to Odoo folder in this Repo
2. Setup Docker:
   1. `sudo apt install docker docker-compose -y`
   2. `sudo usermod -a -G docker $USER`
      - This add your User to Usergroup "docker"
   3. `sudo systemctl start docker`
   4. `sudo systemctl enable docker`
3. Call `make`
4. Open URL [http://localhost:8069](http://localhost:8069)


> # Note
> This Odoo docker is setup in "Proxy-Mode".
> Please Provide a Proxy-Server (like HaProxy or Nginx) for production serve.
