# install winget install microsoft.azd (Install-Module -Name Az -Scope CurrentUser -Repository PSGallery -Forceazd) 

'C:\Users\MamonovF\AppData\Local\Programs\Python\Python312\Scripts\pip3.exe install --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host files.pythonhosted.org install -r .\requirements-dev.txt

azd auth login

cd .\Git\Azure-Search-Demo\

azd init -t azure-search-openai-demo

'you may run in afterwards via azd build & azd up? 
cp C:\Users\MamonovF\Git\AzureSearchDemo\azure-search-openai-demo C:\Users\MamonovF\Git\Azure-Search-Demo

# set up env variables
azd env set AZURE_RESOURCE_GROUP nl2eu-fdi-app

azd env set AZURE_LOCATION westeu

 #install dependencies (FW limitations in AVD) 
npm config set strict-ssl=false  

npm install --loglevel=error --prefer-offline --no-audit --progress=false @esbuild/win32-x64@0.18.11

azd up

Starting gunicorn 20.1.0 Listening at: http://0.0.0.0:8000 (67) Using worker: sync Booting worker with pid: 70 Exception in worker process