# supervisord-autostart
Auto start supervisord<br>

**First**<br>
sudo nano /etc/init.d/supervisord<br>

**then**<br>
Copy and paste auto-script content<br>

**and..**<br>
sudo chmod +x /etc/init.d/supervisord<br>
sudo update-rc.d supervisord defaults<br>
sudo /etc/init.d/supervisord start
