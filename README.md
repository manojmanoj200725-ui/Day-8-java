class Car
{
    String name;
    int year;

    void display()
    {
        System.out.println("Name = " + name);
        System.out.println("Year = " + year);
    }
}

public class MyCar
{
    public static void main(String[] args)
    {
        Car sc = new Car();
        sc.name = "TATA";
        sc.year = 2025;
        sc.display();
    }
}
