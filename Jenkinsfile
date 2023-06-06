pipeline
{
 agent any   
    stages
    {
        stage("Creacion de fichero")
        {
            
            steps
            {
                
                script
                {
                    def cadena = "Prueba integración Git y Jenkins"
                    writeFile(file: "salida.txt", text: cadena)
                }
            }
            
        }
    }
}
