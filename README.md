# PatronesAWS

##  Sitio estático en S3 
- Desde consola ingresamos al servicio s3
![Capture1](https://user-images.githubusercontent.com/43153078/76692688-f8abfc80-6627-11ea-9c9e-e49a5b3a3e67.PNG)
- Creamos un nuevo bucket e ingresamos los datos requeridos 
![Capture2](https://user-images.githubusercontent.com/43153078/76692689-fb0e5680-6627-11ea-9f25-51989f2d27f2.PNG)
![Capture3](https://user-images.githubusercontent.com/43153078/76692691-fe094700-6627-11ea-869b-653f9591961a.PNG)
![Capture4](https://user-images.githubusercontent.com/43153078/76692692-ff3a7400-6627-11ea-9aad-7fe59ff2496b.PNG)
![Capture5](https://user-images.githubusercontent.com/43153078/76692694-006ba100-6628-11ea-945a-9c1ab8a5649e.PNG)
![Capture6](https://user-images.githubusercontent.com/43153078/76692695-02cdfb00-6628-11ea-97ba-100d4dfb7c8d.PNG)
- Creamos nuestro bucket 
![Capture7](https://user-images.githubusercontent.com/43153078/76692696-03ff2800-6628-11ea-99dd-22d49eecdb81.PNG)

- Entramos a la sección de "overview"

![Capture8](https://user-images.githubusercontent.com/43153078/76692697-0497be80-6628-11ea-87be-71746b7bde5b.PNG)
- Revisamos las propiedas con las que cuenta nuestro bucket
![Capture9](https://user-images.githubusercontent.com/43153078/76692698-05c8eb80-6628-11ea-916a-b6a23c3d992d.PNG)
![Capture10](https://user-images.githubusercontent.com/43153078/76692699-06618200-6628-11ea-8da7-57dd91e1e2d4.PNG)
- Elegimos la función de upload para cargar nuestra página
![Capture11](https://user-images.githubusercontent.com/43153078/76692700-0792af00-6628-11ea-8ebb-35ea1fbf517a.PNG)
-Creamos un html sencillo 
![Capture12](https://user-images.githubusercontent.com/43153078/76692701-082b4580-6628-11ea-8bc4-ef6ad5eacb68.PNG)
-Subimos nuestro html al sitio estático 
![Capture13](https://user-images.githubusercontent.com/43153078/76692702-095c7280-6628-11ea-96be-22e2394173dc.PNG)
![Capture14](https://user-images.githubusercontent.com/43153078/76692704-0a8d9f80-6628-11ea-96ad-6af4b189153f.PNG)
![Capture15](https://user-images.githubusercontent.com/43153078/76692705-0bbecc80-6628-11ea-810a-dc83bc433f61.PNG)
![Capture16](https://user-images.githubusercontent.com/43153078/76692706-0ceff980-6628-11ea-937d-34cf23fab498.PNG)

- En cuanto es creado, apareceran las caracteristicas del archivo que fue subido
![Capture17](https://user-images.githubusercontent.com/43153078/76692707-0d889000-6628-11ea-8039-d8870ef40929.PNG)
- Se habilitan los permisos para que la página sea pública 
![Capture18](https://user-images.githubusercontent.com/43153078/76692708-0e212680-6628-11ea-92ed-f587367c3bc7.PNG)
![Capture19](https://user-images.githubusercontent.com/43153078/76692709-0f525380-6628-11ea-9c4c-387e210a84bd.PNG)

- Se prueba que el sitio web sea funcional 
![Capture20](https://user-images.githubusercontent.com/43153078/76692710-0feaea00-6628-11ea-9ca7-3ad65ceb5e41.PNG)



##  Formulario dinámico EC2
  - Se entrar a la consola de aws 
    ![Capture1](https://user-images.githubusercontent.com/43153078/76690912-fb502700-6612-11ea-840f-35db8c964ed7.PNG)
  -  Se crea una maquina virtual 
   ![Capture](https://user-images.githubusercontent.com/43153078/76690910-fab79080-6612-11ea-8652-40db9d65f1d4.PNG) 
  -  Se selecciona las instancia que se va a utilizar 
      ![Capture3](https://user-images.githubusercontent.com/43153078/76690914-fc815400-6612-11ea-88ca-99b1903c438b.PNG)
  - Despues de verificar que cumple con las caracteristicas requeridas lo lanzamos 
      ![Capture4](https://user-images.githubusercontent.com/43153078/76690916-fdb28100-6612-11ea-8336-06ebe8f588dd.PNG)
   - Se debe crear una llave de acceso a nuestra maquina virtual 
        ![Capture5](https://user-images.githubusercontent.com/43153078/76690917-fe4b1780-6612-11ea-912b-91aef8c93971.PNG)
   
   - Se descargan las llaves para poder lanzar nuestra maquina
   
   ![Capture6](https://user-images.githubusercontent.com/43153078/76690920-00ad7180-6613-11ea-8aa4-9d7f7563c31a.PNG)
   
   - Se crea satisfactoriamente
   
   ![Capture7](https://user-images.githubusercontent.com/43153078/76690921-02773500-6613-11ea-86f4-a1d2e095a581.PNG)

- Le damos permiso a las llaves para poder ejecutarlo 
![Capture8](https://user-images.githubusercontent.com/43153078/76690922-030fcb80-6613-11ea-97bd-d58b55f0aa1d.PNG)
- Mediante el comando ssh accedemos a nuestra maquina virtual mediante las llaves 

![Capture9](https://user-images.githubusercontent.com/43153078/76690924-03a86200-6613-11ea-8b3e-c5e191d95a5a.PNG)

- Instalamos Java, Git, maven para desplegar nuestro servicio en AWS
![Capture10](https://user-images.githubusercontent.com/43153078/76690925-0440f880-6613-11ea-816d-1f15212b8e2c.PNG)

- probamos nuestro servicio web 
![Capture11](https://user-images.githubusercontent.com/43153078/76690926-04d98f00-6613-11ea-8417-c78ee2bcff0a.PNG)
