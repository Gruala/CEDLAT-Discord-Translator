[![Deploy // Desarrollado](https://cedlat.org/)](https://github.com/Gruala/)

![logo](https://cedlat.org/wp-content/uploads/2019/06/cropped-LOGO-CEDLAT.png)

# 🤖 CEDLAT-Discord-Translator-Bot (Discord Translator Bot)
> 🤖 Discord translator, Bot built with discord.js & uses Command Handler from [discordjs.guide](https://discordjs.guide)
> 🤖 Universal translator using Google translator. Programmed in Javascrip.


## Requirements // Requisitos
1. Visual Studio Code: 1.52.1 **[Guide](https://code.visualstudio.com/Download)**
2. Node.js v12.0.0 or newer
3. Latest Current Version: 15.5.0 (includes npm 7.3.0) **[Guide](https://nodejs.org/en/download/current/)**
4. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**

## Not necessary, for other projects // No necesario, para otros proyectos
1. YouTube Data API v3 Key **[Guide](https://developers.google.com/youtube/v3/getting-started)**  
2. Soundcloud Client ID **[Guide](https://github.com/zackradisic/node-soundcloud-downloader#client-id)**
3. Discord **[Discord](https://discord.js.org/#/)**
4. Discord documentation **[Documentación](https://discord.js.org/#/docs/main/stable/general/welcome)**


## 🚀 Getting Started

```
git clone https://github.com/Gruala/CEDLAT-Discord-Translator-Bot.git
cd CEDLAT-Discord-Translator-Bot-main
npm install
```
After installation finishes you can use `node index.js` to start the bot.


## ⚙️ Command npm
npm install               `Install and update all library   // Instala y actualiza todas las librerias`
npm update								`Update libreries                 // Actualiza librerias`
npm install -g npm        `Install a new version of the npm // Instala una nueva versión del npm`


## ⚙️ File configuration: config_connection_Example1.json
Enter the directory: // Entra en el directorio: 
`./config_connection`

Edit the file: // Edita el fichero: 
`./config_connection/Config_Connection.js`

Select the file name that will have the JSON data where the configuration is: // Selecciona el nombre de fichero que tendrá los datos JSON donde esta la configuración:
`config = require("./config_connection_Example1.json");`

Modify the file where you have the data to start the bot, update the Token. Owner is for informational purposes only, only administrators would see it. Set your custom values.
⚠️ **Note: Never commit or share your TOKEN, OWNER or api keys publicly** ⚠️
Modifica el fichero donde tienes los datos para iniciar el bot, actualiza el Token. El OWNER es solo informativo, solo lo verían los administradores. Pon tus valores personalizados. 
⚠️ **Nota: Nunca confirme ni comparta públicamente su TOKEN, OWNER o claves api** ⚠️
`./config_connection/config_connection_Example1.json`
{
    "TOKEN": "NTY5GFDLGTOFDFTYTA4MjU2MjE1MDU5.XLOmcQ.wqwzsdfcdsfgyrsEb_CtpFfOuY",
    "OWNER": ["456456456256215059"],
    "PLAYSTATUS": "Ayuda: :t ayuda",
    "PREFIX": ":t"
}


## ⚙️ File configuration: config_translate.json
Enter the directory: // Entra en el directorio: 
`./translate`

Edit the file and set your parameters. The maximum text to be translated is 2000 letters, it places a number less than 1920:
Edita el fichero y pon tus parámetros. El texto máximo a traducir son de 2000 letras, coloca un número inferior a 1920:
`./config_connection/config_translate.json`
{
 "TRANSLATOR_Enabled": true,
 "TSCHANNELS_Enabled": true,
 "SEPARATE_LANGUAGE": ",",
 "MAX_TRANSLATE": 1920,
 "MAX_TEXT_ICON": 200
}


## ⚙️ File commands: config_command.json
Enter the directory: // Entra en el directorio: 
`./commands_function`

Allows users and moderators to use commands. Turns on blacklisting.
Permite que los usuarios y  moderadores usen los comandos. Activa el uso de la lista negra.
`./commands_function/config_command.json`
{
 "COMMAND_USER_Enabled": true,
 "COMMAND_MODERATOR_Enabled": true,
 "COMMAND_BLACK_Enabled": true,
 "STRING_TEXT_NO_CLEAR": "{"
}


## ⚙️ File commands: config_command.json
Enter the directory: // Entra en el directorio: 
`./languages`

Select the file with the translation. Only Spanish and English work for now.
Selecciona el fichero con la traducción. Solo funciona por ahora el Español y el ingles.
`./languages/Config_Language.js`
  //config = require("./Language_Chinese.json");
  //config = require("./Language_Czech.json");
  //config = require("./Language_English.json");
  //config = require("./Language_French.json");
  //config = require("./Language_German.json");
  //config = require("./Language_Hungarian.json");
  //config = require("./Language_Italian.json");
  //config = require("./Language_Russian.json");
  config = require("./Language_Spanish.json");
  //config = require("./Language_Ukrainian.json");


## ⚙️ Commands: 
List of commands: // Lista de comandos: 
`:t help` o `:t ayuda`
Supported languages // Idiomas soportados
`:t languages`
Ejemplos para usar el traductor // Examples to use the translator
`:t translation` o `:t traduccion`

Spanish Commands:
:t act_black_list
:t act_moderadores
:t act_usuarios
:t act_traducion
:t act_ts_channels
:t añade_black
:t añade_moderador
:t Borrar
:t connexion
:t connexion_log
:t ayuda
:t invitar
:t languages
:t ping
:t estadisticas
:t traduccion
:t tiempo_activo
:t version


## ⚙️ Use TS Channel:  //  Usar TS Channel 
List of command


## 🤝 Contributing // Contribuyendo
1. [Fork the repository](https://github.com/Gruala/CEDLAT-Discord-Translator-Bot/fork)
2. Clone your fork: `git clone https://github.com/Gruala/CEDLAT-Discord-Translator-Bot.git`
3. Create your feature branch: `git checkout -b my-new-feature`
4. Commit your changes: `git commit -am 'Add some feature'`
5. Push to the branch: `git push origin my-new-feature`
6. Submit a pull request


## 📝 Credits
[Grualia](https://github.com/Gruala) For the queue system used in this application which was adapted from [Grualia/CEDLAT-Discord-Translator-Bot](https://github.com/Gruala)
