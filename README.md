 # <center> gitlab-k8s-helm-experience</center>
 ## <center> Ressources et explications</center>
 ### Pod de Débogage Kubernetes 
  [Fichier de configuration d'un pod de debug](createDebugPod.yaml)
 ### Configuration de 'values.yaml' de Helm 
 - [Fichier des configurations  par defaut (v0.72.0)](configHelm/values0.72.0.yaml)
 - [Fichier des configurations personnalisés](configHelm/values.yaml) :
    -  replicas: 5
    - gitlabUrl: http://192.168.1.76:9988/
    - runnerRegistrationToken: "L3cKXUo4U_iuV7pnEev8"
    - serviceAccount.name
    - runners.config (clone_url)
 ### Fichier des configurations ServiceAccount, Role et Rolebindings 
 - [configurations des ServiceAccount, Role et Rolebindings](ServiceAccountConfig/gitlab-runner-rbac.yaml) 
 - [configurations des ServiceAccount, Role et Rolebindings (version avec des commentaires)](ServiceAccountConfig/gitlab-runner-rbacCommented.yaml) 
 - [configuration de Role ](ServiceAccountConfig/gitlab-runner-role.yaml) 
 - [configuration de Rolebindings](ServiceAccountConfig/gitlab-runner-rolebinding.yaml) 
 - [configuration de ServiceAccount](ServiceAccountConfig/gitlab-runner-serviceaccount.yaml)



