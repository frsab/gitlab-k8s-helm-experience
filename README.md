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


