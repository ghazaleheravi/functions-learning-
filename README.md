# functions-learning-
<!DOCTYPE html>
<html lang="en-us">
    <head>
        <meta charset="utf-8">
        <title>function skill 1</title>
    </head>
    
    <body>
        <style>
            p {
              font-size: 30px;
              color:blue;  

            }
        </style>

        <h2>Random name is: </h2>

        <script>
            let names = ['Chris','Li Kang','Anne','Francesca','Mustafa','Tina','Bert','Jada'];
            let para = document.createElement('p');
            document.body.appendChild(para);

            function chooseName(){
                let length = names.length-1;
                let randomIdx = Math.floor((Math.random()*(length+1)));
                return names[randomIdx];
             }
            para.textContent = chooseName();

        </script>
    </body>
</html>
