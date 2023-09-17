# Plantilla de habilidades de Alexa para integrar ChatGPT de OpenAI
Utilice ChatGPT-4 en Alexa 😊

# Instrucciones
- Cree una cuenta y una clave de autenticación API en OpenAI: https://platform.openai.com/account/api-keys
     - Tendrás derecho a una prueba gratuita de 3 meses (o límite de $18).
     - Documentación: https://platform.openai.com/docs/api-reference/authentication

- Cree una habilidad alojada en Alexa (Python) en Alexa: https://developer.amazon.com/alexa/console/ask/create-new-skill
   - Nombra tu habilidad: elige un nombre de tu elección (Ej.: ChatGPT)
   - Elija una ubicación principal: español (ES)
   - En el tipo de experiencia, seleccione: Otro > Personalizado > Alojado en Alexa (Python)
   - Región de alojamiento: puede dejar la predeterminada (Este de EE. UU. (Norte de Virginia))
   - Plantillas: haga clic en Importar habilidad
   - Ingrese la dirección: https://github.com/alexandremendoncaalvaro/skill-alexa-chatgpt4.git

- Vaya a la pestaña "Código"
- Inserta tu clave en el código: lambda > lambda_function.py:
   ```pitón
   openai.api_key = "reemplazar-con-su-clave-api-openai"
   ```
- Guardar cambios

- Construir el modelo e implementar el código.

- ¡Sea feliz!

