package Padre;

public class Empleado {
    private string nombre;


    private double sueldo;

    public Empleado(string nombre, double sueldo) {
        this.nombre = nombre;
        this.sueldo = sueldo;
    }


    public string getNombre() {
        return nombre;
    }

    public void setNombre(string nombre) {
        if (nombre.equals ("homero")){
            this.nombre="No homeros"
        } else {
        this.nombre = nombre;
    }

    public double getSueldo() {
        return sueldo;
    }

    public void setSueldo(double sueldo) {
        this.sueldo = sueldo;
    }
}
