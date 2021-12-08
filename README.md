# dictionaries
dict={'name':'jifri','designation':'student','qual':'btech','univ':'cmr'}
print(dict['name'])
print(dict['qual'])
dict={'name':'jifri','designation':'student','qual':'btech','univ':'cmr'}
dict['name']='jifri'
print(dict['name'])
dict['class']='cse7sem'
print(dict['class'])
dict={'name':'jifri','designation':'AsP','qual':'student','univ':'cmr'}
del dict['designation']
#print(dict['designation'])
dict.clear()
#print(dict['name'])
del dict
dict={'name':'jifri','designation':'student','qual':'btech','univ':'cmr','name':'jifri'}
print(dict['name'])  #here updated name is printed 
print(len(dict))
 
dict={'name':'jifri','designation':'student','qual':'btech','univ':'cmr','name':'jifri'}
print(dict.values())
print(dict.items())
print(dict.keys())
 
dict={'name':'jifri','designation':'student','qual':'btech','univ':'cmr','name':'jifri'}
print(dict['name'])
print(dict.get('edu','nothing'))
 
dict={'name':'jifri','designation':'student','qual':'btech','univ':'cmr','name':'jifri'}
dict2=dict.copy()
print(dict2['name'])
print(len(dict2))
 
#for merging 2 dictionaries use update
dict={'name':'jifri','designation':'student','qual':'btech','univ':'cmr','name':'jifri'}
dict2={'edu':'btech-mtech','students':'7sem'}
print(dict)
print(dict2)
dict.update(dict2)
print(dict)
