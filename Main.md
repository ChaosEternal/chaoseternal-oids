The oids of chaoseternal.

# Introduction #

This project co-ordinates the usage of oid in all chaoseternal's projects/products.

# Details #

The enterprise number i have is 9609 , with IANA prefix , the oid base of chaoseternal is

1.3.6.1.4.1.9609

For the next level,
  * SNMP: 0
  * LDAP: 1
    * my ldap-based simple network management tools: 100
      * objectClasses: 3
      * attributeTypes: 2

Another Enterprise Number is 33323

1.3.5.1.4.1.33323

# History #

Before, I store these information in dns system using TXT type record,
```
oids.chaoseternal.net.  	"1.3.6.1.4.1."	default  	
100.1.9609 	"simple network managements"	default 	
3.100.1.9609 	"objectClasses"	default 	
2.100.1.9609 	"attributeTypes"	default 	
9609 	"enterprise number for impaster co ltd"	default 	
0.9609 	"snmp entities"	default 	
1.9609 	"ldap entities"	default

```
## comments ##
Add your content here.  Format your content with:
  * Text in **bold** or _italic_
  * Headings, paragraphs, and lists
  * Automatic links to other wiki pages