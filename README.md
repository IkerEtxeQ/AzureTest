# Mi Proyecto en Azure con Deploy Automático

Este es un ejemplo mínimo de aplicación Flask que se despliega en **Azure Container Apps**
usando **GitHub Actions** y **Azure Container Registry (ACR)**.

## 🚀 Despliegue
1. Configura estos secretos en GitHub:
   - `AZURE_ACR_USERNAME`
   - `AZURE_ACR_PASSWORD`
   - `AZURE_ACR_LOGIN_SERVER`

2. Crea un tag con `deploy` y súbelo:
   ```bash
   git tag deploy-v1
   git push origin deploy-v1
   ```
Azure descargará la nueva imagen y tu app estará online.
