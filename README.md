# Daily automation

### Setup Virtual environment
```
virtualenv env
source env/bin/activate (Only for manual run)
```

### Chrome driver setup
```
sudo apt-get install chromium-chromedriver
```
- Ensure that the Chromedriver is initialized like: 
`webdriver.Chrome(chrome_options=self.options)` i.e without providing the path to the driver.

### Setting env variable
```
nano ~/.bash_profile
export LINKEDIN_USERNAME=username
export LINKEDIN_PASSWORD=password
```
**Note:** Do not use quotes for the env variable values above.
- Save the above file
- `source ~/.bash_profile`

### Misc
Dev/shm update - https://www.cyberciti.biz/tips/what-is-devshm-and-its-practical-usage.html