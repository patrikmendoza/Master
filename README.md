# Master
// Sub clase Doctor
class Doctor extends Persona {
    private String especialidad;
    
    // Constructor
    public Doctor(String nombre, int edad, String direccion, String especialidad) {
        super(nombre, edad, direccion);
        this.especialidad = especialidad;
    }
    
    // Método getter y setter
    public String getEspecialidad() {
        return especialidad;
    }
    
    public void setEspecialidad(String especialidad) {
        this.especialidad = especialidad;
    }
    
    // Método para mostrar la información personal del doctor
    @Override
    public void mostrarInformacion() {
        super.mostrarInformacion();
        System.out.println("Especialidad: " + especialidad);
    }
}
