# Create oData Services

1 - Access T-code SEGW

a.

![](SNAG0029.png)

b.

![](SNAG0028.png)

2 - After you create will generate this two entity types

a.

![](SNAG0027.png)

3 - In this case we gonna import from DDIC -> EKKO and EKPO 

a.

![](SNAG0026.png)

b.

![](SNAG0025.png)

c. Select the fields which you want to use

![](SNAG0024.png)

d. Select the keys

![](SNAG0023.png)

e. Do the same for EKPO

![](SNAG0022.png)

f.

![](SNAG0021.png)

g.

![](SNAG0020.png)

3 - Generate

a.

![](SNAG0019.png)

4 - after generating your odata service two new classes will be available

a. ABAP code should always be in DPC class.

![](SNAG0018.png)

5 - Register your service in the gateway. (If your system is not embedded, this part will be different)

a.

![](SNAG0017.png)

b.

![](SNAG0016.png)

6 - Maitain to check status/infos

a.

![](SNAG0015.png)

b.

![](SNAG0014.png)

c.Congrats! Your service is available.

![](SNAG0013.png)

d. Try using json format for better viewing

![](SNAG0012.png)

e. Check your metadata (Pay attention to this, very important to check the details of oData Service)

![](SNAG0011.png)

f. Copy this link and paste in your browser

![](SNAG0010.png)

g.

![](SNAG0009.png)

h.

![](SNAG0008.png)

7 - Lets try get some data from your service

a.

![](SNAG0007.png)

8 - Implement your service class

a.

![](SNAG0006.png)

b. Select the method and click in the redefinition button

![](SNAG0005.png)

c. Example code used in this tutorial:

SELECT * UP TO 10 ROWS FROM ekko INTO CORRESPONDING FIELDS OF TABLE et_entityset.

![](SNAG0004.png)

Save and Active the code.

9 - Now check the folder redefinition:

a.

![](SNAG0003.png)

10 - Test again in the gateway POHeaderSet

a.

![](SNAG0002.png)

11 - Nice! Check in the browser and gateway with json format.

a.

![](SNAG0001.png)

b.

![](SNAG0000.png)


