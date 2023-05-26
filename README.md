# Ex04 Places Around Me
## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>My City</title>
    </head>
    <body>
    <h1 align="center">
        <font color="red"><b>ARIYALUR</b></font>
    </h1>
    <h3 align="center">
        <font color="black"><b>NIROSHA(22009078)</b></font>
    </h3>
    <centre>
    <img id="Image-Maps-Com-image-maps-2023-05-10-172105" src="/static/images/mapp.png" border="0" width="1693" height="728" 
         orgWidth="1693" orgHeight="728" usemap="#image-maps-2023-05-10-172105" alt="" />
<map name="image-maps-2023-05-10-172105" id="ImageMapsCom-image-maps-2023-05-10-172105">
<area  alt="" title="Ariyalur Bus Stand" href="busstand.html" shape="rect" coords="703,650,890,722" style="outline:none;
                    " target="_self"/>
<area  alt="" title="Government Hospital" href="hospital.html" shape="rect" coords="735,262,870,385" 
              style="outline:none;" target="_self"/>
<area  alt="" title="Collector Office" href="coloff.html" shape="rect" coords="1106,268,1302,329" 
              style="outline:none;" target="_self"/>
<area  alt="" title="Ariyalur Vallalar Orphanage" href="orphan.html" shape="rect" coords="741,44,937,105" 
              style="outline:none;" target="_self"/>
<area  alt="" title="Ariyalur Cement Works" href="cement.html" shape="rect" coords="904,385,1077,486" 
              style="outline:none;" target="_self"/>
<area shape="rect" coords="1691,726,1693,728" alt="Image Map" style="outline:none;" title="Image Map" 
             href="https://www.image-maps.com/"/>
</map>
        </centre>
    </body>
</html>


busstand.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>BUS STAND</title>
    </head>
    <body bgcolor="#ADDFFF">
        <h1 align="center">
            <font color="red"><b>ARIYALUR/b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>ARIYALUR BUS STAND</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                Irked by the delay in commencing the construction of the new bus stand in Ariyalur at a cost of Rs 7.8 crore, residents have urged the authorities to begin the work at the earliest. 
                The delay in construction has been attributed to the delay in setting up a temporary bus stand even after the foundation stone was laid over a month ago.
                The Ariyalur bus stand was established in 1975 in the town on a land parcel of three acres.
                Additional buildings cropped up in 1988 and 1995 respectively in the bus stand from which buses ply to various other districts, including Chennai, Tiruchy, Perambalur, Cuddalore, Thanjavur, Chidambaram, Salem and Virudhachalam. 
                However, the officials concerned decided to give the 42-year-old bus stand a facelift by replacing the dilapidated buildings with new construction out of public interest.

                

            </font>
        </p>
    </body>
</html>


orphan.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Orphange</title>
    </head>
    <body bgcolor="#C3FDB8">
        <h1 align="center">
            <font color="red"><b>ARIYALUR</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b> VALLALAR ORPHANAGE</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                I
            Be good. It is as simple as this. A good society comprises of individuals who are compassionate and peaceful and each person is as important as the other regardless of whether he is disabled, a destitute or an orphan. T
            That's humanity defined.Vellore is more known in the country as a medical hub.
            Patients come to CMC hospital for specialized treatment and cure. 
            It is natural for people to learn to be more patient and understanding. 
            Even the government has a considerable number of organizations giving medical aid, education, child care, community development,vocational training etc. and empowering children, women and disabled people to lead a normal life
            There are some children who are not lucky enough to have the umbrella of love and care of their parents. However, in Vellore, there are some Non-Government Organizations which have taken up the responsibility of looking after such children of God. 
            These NGOs use grants from various sources for the education and well being of these children.
            </font>
        </p>
    </body>
</html>


cement.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>CEMENT</title>
    </head>
    <body bgcolor="#ADDFFF">
        <h1 align="center">
            <font color="red"><b>ARIYALUR</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>CEMENT WORKS</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
            The third cement plant of TANCEM commenced its operation in 2019.
            It is a most modern 1 million ton per annum plant of state-of-the-art technology and installed with advanced equipment such as pre calciner, crossbar cooler, VRM for raw grinding as well as coal grinding.
            It has a modern laboratory to ensure consistent quality of cement.
            It manufactures OPC 43 Grade & PPC under ARASU and VALIMAI brands.
            The Ariyalur Cement Works is primarily supplying cement to Government departments.
             It has a wide network of stockists for open market sales and is selling cement in the central and northern districts of Tamil Nadu and Northern districts of Kerala.   
            </font>
        </p>
    </body>
</html>


hospital.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>GOV HOSPITAL</title>
    </head>
    <body bgcolor="#ADDFFF">
        <h1 align="center">
            <font color="red"><b>ARIYALUR/b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>ARIYALUR GOVERMENT HOSPITAL</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                
                A hospital is a health care institution providing patient treatment with specialized health science and auxiliary healthcare staff and medical equipment.[
                The best-known type of hospital is the general hospital, which typically has an emergency department to treat urgent health problems ranging from fire and accident victims to a sudden illness. 
                district hospital typically is the major health care facility in its region, with many beds for intensive care and additional beds for patients
                who need long-term care. Specialized hospitals include trauma centers, rehabilitation hospitals, children's hospitals, seniors' (geriatric) hospitals, and hospitals for dealing with specific medical
                needs such as psychiatric treatment (see psychiatric hospital) and certain disease categories. Specialized hospitals can help reduce health care costs compared to general hospitals.
                Hospitals are classified as general, specialty, or government depending on the sources of income received. 

            </font>
        </p>
    </body>
</html>


coloff.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>GOV HOSPITAL</title>
    </head>
    <body bgcolor="#ADDFFF">
        <h1 align="center">
            <font color="red"><b>ARIYALUR/b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>ARIYALUR GOVERMENT HOSPITAL</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                
                A hospital is a health care institution providing patient treatment with specialized health science and auxiliary healthcare staff and medical equipment.[
                The best-known type of hospital is the general hospital, which typically has an emergency department to treat urgent health problems ranging from fire and accident victims to a sudden illness. 
                district hospital typically is the major health care facility in its region, with many beds for intensive care and additional beds for patients
                who need long-term care. Specialized hospitals include trauma centers, rehabilitation hospitals, children's hospitals, seniors' (geriatric) hospitals, and hospitals for dealing with specific medical
                needs such as psychiatric treatment (see psychiatric hospital) and certain disease categories. Specialized hospitals can help reduce health care costs compared to general hospitals.
                Hospitals are classified as general, specialty, or government depending on the sources of income received. 

            </font>
        </p>
    </body>
</html>
```

## CLIENT OUTPUT

<img width="959" alt="output1" src="https://github.com/Niroshassithanathan/NearMe/assets/121418437/5bc27dd3-0c31-4c7b-8caf-5ffb07fb88c5">


<img width="960" alt="output2" src="https://github.com/Niroshassithanathan/NearMe/assets/121418437/7abbff00-9491-4376-9529-63ee66bbf593">


<img width="960" alt="output6" src="https://github.com/Niroshassithanathan/NearMe/assets/121418437/a0b793eb-2e94-4d24-b58d-7a00baedc304">


<img width="960" alt="output3" src="https://github.com/Niroshassithanathan/NearMe/assets/121418437/d435041e-4617-4cf3-801d-67a0ed827fd9">


<img width="960" alt="output4" src="https://github.com/Niroshassithanathan/NearMe/assets/121418437/c93901e1-3dfa-4ec1-a696-cfb1a04fc980">


<img width="960" alt="output5" src="https://github.com/Niroshassithanathan/NearMe/assets/121418437/7c6faa02-1a61-4061-9316-b51badf980a5">


## SERVER OUTPUT

<img width="957" alt="output7server" src="https://github.com/Niroshassithanathan/NearMe/assets/121418437/b08f668d-fcdb-48dc-b1bb-dddec05ab517">


## HTML VALIDATOR

<img width="960" alt="output8html" src="https://github.com/Niroshassithanathan/NearMe/assets/121418437/fa7e6478-ebf6-4953-9b96-d25e6c6d75be">


## RESULT

The program for implementing image maps using HTML is executed successfully.
