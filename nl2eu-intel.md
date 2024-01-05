# install winget install microsoft.azd
# Run azd auth login
# Run azd init -t azure-search-openai-demo

# set up env variables
azd env set AZURE_RESOURCE_GROUP nl2eu-intelligence-app
azd env set AZURE_LOCATION westeu

 azd env set OPENAI_HOST openai
 azd env set OPENAI_ORGANIZATION {Your OpenAI organization}
 azd env set OPENAI_API_KEY {Your OpenAI API key}


azd up