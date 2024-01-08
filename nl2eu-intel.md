# install winget install microsoft.azd (Install-Module -Name Az -Scope CurrentUser -Repository PSGallery -Forceazd)
azd auth login

cd .\Git\Azure-Search-Demo\

azd init -t azure-search-openai-demo

# set up env variables
azd env set AZURE_RESOURCE_GROUP nl2eu-fdi-app

azd env set AZURE_LOCATION westeu

  
  npm config set strict-ssl=false
  
  #azd up
  
  ''''npm install --loglevel=error --prefer-offline --no-audit --progress=false @esbuild/win32-x64@0.18.11''''

azd up

