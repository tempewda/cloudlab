## Create
az ad sp create-for-rbac \
  --name "github-auth-sp" \
  --role contributor \
  --scopes /subscriptions/<subscription id>

  
