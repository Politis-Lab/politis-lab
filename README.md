## Element locations

### Homepage
Most settings and items controlled in config.toml  
  
#### Main  
Logo - under [params] in config.toml:```static/images/logo.png```  
Banner - under [params] in config.toml: ```static/images/banner/bilayer.png```  
Introduction text - under [params.about] in ```config.toml```  
Introduction image - ```static/images/buttons/lacY.png```  
Twitter - under [params.footer], link to twitter handle politis_lab  
  
#### Research Themes  
Configurations in ```data/feature.yml```  
Images in ```static/images/buttons/*.png```  
  
#### Featured Publications  
Configuration files found in ```content/portfolio/```  
Each featured publication contained in individual markdown files  
Images are stored in ```static/images/blog/```  
  
### People  
Configurations in ```data/team.yml```  
List each member as new list item  
Images are stored in ```static/images/team/```  

#### Previous members  
Configurations in ```data/client.yml```  
Create new png images (245x311; opaque bg) for each former member  
AI file included as ```static/images/team/previous_members.ai```  
  
### Publications  
Publication list in ```data/publications.yml```  
Sort publications by date and month manually, list as list items  
  
### Location  
Configurations in ```data/contact.yml```  
Address and email widgets found as *officeAddress1* and *mail1* in yaml file  
Google map widget configured in ```themes/timer-hugo/layouts/location/list.html``` - embed as iframe on line 53  
  
### Vacancies
Each vacancy contained in individual markdown files in ```content/vacancies/```  
