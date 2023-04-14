# sample-aks


az managedapp definition create --name "visionai-aks-sumanth" --location eastus --resource-group testaks --lock-level ReadOnly --display-name "visionai-aks-sumanth" --description "visionai aks" --authorizations "528eeba5-bbd0-4af4-b7ed-ab574b85a152:8e3af657-a8ff-443c-a75c-2fe8c4bcb635" --package-file-uri "https://raw.githubusercontent.com/sumanthvisionify/sample-aks/main/app.zip"