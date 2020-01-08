> ## Documentation GoBarber 

This documentation was created using API Blueprint and genreate HTML file with Aglio. .

#### API Blueprint
[Api Blueprint](https://apiblueprint.org) was used to describe the application. The syntax of the requests and responses need to be JSON, like following:

      # GET /message
      + Response 200 (text/plain)
		+ Body
		{
		 "message": "Hello World!"
		}

#### Aglio 
[Aglio](https://github.com/danielgtaylor/aglio) was used to generate the HTML file.


### Commands

To generate the HTML, use the following command:

       aglio -i index.apib -o index.html

<strong>You can use other templates, see aglio documentation.</strong>

index.html : Web file name.

index.apib : file with documentation.


