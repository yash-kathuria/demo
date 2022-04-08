# demo
this is repository is representation of clowning
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        class person{
            constructor(name,age){
                this.name=name;
                this.age=age;
            }
            printName(){
                console.log("my name is "+this.name);
            }
            printAge(){
                console.log("my age is "+this.age);
            }
        }
        class car extends person{
            constructor(name,age,color){
                super(name,age);
                this.color=color;
            }
            printColor(){
                console.log(this.name+" has a car of "+this.color+" color");
            }
        }
        var name=window.prompt("Enter the name of the person");
        var age=window.prompt("Enter the age of the person");
        var color=window.prompt("Enter the color of car's that person have");
        let person1=new car(name,no,color);
        person1.printName();
        person1.printAge();
        person1.printColor();
    </script>
    
</body>
</html>
