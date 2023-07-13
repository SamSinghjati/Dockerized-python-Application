1. Create an direcoty by name app.
2. Run docker-compose up -d and wait until terminal is back.
3. Verify the pythonapp & mysql container are runing by "docker ps"
4. Open browser and paste ip:5000 (for python application) and ip:5000/countries ( for mysql database).

docker exe -it <container-id> mysql -u root -p 