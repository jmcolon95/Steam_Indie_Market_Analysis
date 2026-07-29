**Sketch for Creating my Database**

Games (Done)  
\---------  
game\_id(PK)  
Title  
Publisher\_ID  
Release\_date  
Base\_Price  
Steam\_deck  
Early\_acess  
Steam\_app\_ID

Developers\_Table (Done)  
\------------------------  
Developer\_ID (PK)  
Developer\_name

Publishers\_Table (Done)  
\-----------------------  
Publisher\_ID(PK)  
Publisher\_name

Reviews\_Table (Done)  
\--------------------  
Review\_ID (PK)  
Game\_ID (FK)  
Review\_score\_Desc  
Total\_reviews  
Positive\_reviews  
Negative\_reviews  
Last\_update

Tags\_table (Done)  
\--------------  
Tag\_ID (PK)  
Tag\_name

Gametags\_Table (Done)  
\----------------------  
Game\_ID(FK)  
Tag\_ID(FK)

Game\_Developers\_Table (Done)  
\----------------------------------  
Game\_ID(FK)  
Developer\_ID(FK)

Genres\_Table (Done)  
\------------------  
Genres\_ID (PK)  
Genre\_Name

Game\_Genres\_Table (Done)  
\----------------------------  
Game\_ID (PK)(FK)  
Genre(PK)(FK)
