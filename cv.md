# Vitali Khvisevich

##### Personal information:

**Phone:** +375 (44) 738-49-86  
**Email:** vitalykhvisevich@gmail.com  
**Linkedin:** linkedin.com/in/vitali-khvisevich-2478981ba  
**Github:** https://github.com/Vitaly-Khvisevich  

##### Profile:
  Responsible, honest, easy to learn, highly motivated Junior developer without bad habits. I have no professional experience and have worked as a system administrator for more than 10 years in various fields (production, construction, sales). I want to master a creative, highly paid and in-demand specialty, as well as get the rank of senior in  programming in 2 years.
  
 ##### Skills:
	* Python
	* Django
	* SQL
	* Github

##### Code example:
```
from collections import deque
graph={}
graph['you']=['alise', 'bob', 'claire']
graph['bob']=['anuj', 'peggy']
graph['alise']=['peggy']
graph['claire']=['thom','jonny']
graph['anuj']=[]
graph['peggy']=[]
graph['thom']=[]
graph['jonny']=[]

def person_is_seller(name):
    return name[-1]==''

def search(name):
    search_queue=deque()
    search_queue+=graph[name]
    searched=[]
    while search_queue:
        person=search_queue.popleft()
        if not person in searched:
            if person_is_seller(person):
                print (f'{person} is a mangoo seller!!!')
                return True
            else:
                search_queue+=graph[person]
                searched.append(person)
                print(person)
    print('seller is not found')
    return False
search('you')
```

##### Work experience:  
**EDUCATIONAL CENTER FOR PROGRAMMING AND HIGH TECH**  
**Project name:** Electronic library of science fiction and fantasy.  
The project is designed to store entertainment literature in the genre of fantasy and science fiction in one place, as well as distribute this information among interested people. The project was executed in Django using Html, css and Sqlite. The functions of registration, adding information, feedback, selection, and saving to the user's computer were enabled.

##### Education: 
**Educational Center for Programming and High Tech** (07.2020 - 10.2020)  
*Comprehensive course on Web application development in Python Python Developer*

**Belarusian State University of Informatics and Radioelectronics** (2008 - 2012)  
*Information technology and management in technical systems*

**English level:** A2
