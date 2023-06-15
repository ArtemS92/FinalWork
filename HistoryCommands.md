## Task 1
cat > home_animals    
cat > pack_animals    
cat home_animals pack_animals > animals    
cat animals    
mv animals mans_friends    

## Task 2
mkdir Finalwork 
mv mans_friends Finalwork  

## Task 3-4
sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb    
sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb    
sudo apt-get update    
sudo apt-get install mysql-server    
sudo dpkg -r mysql-apt-config  
