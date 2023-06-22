
abstract class Animal{
    abstract hacersonido():void;


}


class Perro extends Animal{
    hacersonido(){
        console.log("Guau")
    }
}
class Gato extends Animal{
    hacersonido(){
        console.log("Miau")
    }
}

