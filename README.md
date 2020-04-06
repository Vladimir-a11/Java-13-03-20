package homw_work;

public class Parallepiped1 {
    public double lengh;
    public double width;
    public double height;

    public Parallepiped1 (double a, double b, double c){
       this.height = a; // высота
         this.lengh = b; // длинна
         this.width = c; // ширинв

    }

    public double getSquare() {

        return 2 * (lengh*width + width*lengh + height*lengh);
    }

    public double getPerimetr() {

        return  4*(lengh + width + height);
    }

    public double getVolume() {
        return lengh * width * height;

    }


}
