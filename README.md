# Cloud-Azure-Projects
Repository a Azureproject

Steps taken in this Project:
  Create a service principal in Entra ID, at my tenant with the least amount of priviledged and a limited scope to be in line with the principle of least-power
  Added the credidentials of this service pricipal in the secrets for Github Actons
  Added a ARM-template for a storage account
  Added and edited a YAML file for automatization. 
  

After sucessful creation the service principal will be deleted, so further pushes will result in a error, because the referenced AD SP is no longer in the tenant
