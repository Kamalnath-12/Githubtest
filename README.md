# Githubtest

<!DOCTYPE html>
<html lang="en">
    <title>new program</title>
    <head>
        <title>new program</title>
    </head>
    <body>
      <p>
        this is link:
        <span id="link"></span>
      </p>
      
    

    <script>
        var url=prompt("enter url");
        if(url.substring(0,4)=="http")
        {

        }
        else{
            url="http" + url;
        }
        var node=document.getElementsByName("link");
         node.innerText=<a href =  "url"> url </a>

    </script>
    </body>
    
    
</html>