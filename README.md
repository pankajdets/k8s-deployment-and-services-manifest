# k8s-deployment-and-services-manifest
Commands

        cd k8s-deployment-and-services-manifest/
  275  ls
  276  kubectl apply -f persistance-volume.yml
  277  git pull
  278  ls
  279  kubectl apply -f persistance-volume.yml
  280  kubectl get persistance-volume.yml
  281  kubectl get persistance-volume
  282  kubectl get pv
  283  git pull
  284*
  285* kubectl apply -f persistance-volume-claim.
  286  kubectl get pv
  327  kubectl get pvc

  332  kubectl apply -f configmap.yml

  333  kubectl get configmap

  334  kubectl describe configmap usermgmt-dbcreation-script

  336  git pull

  337  kubectl apply -f mysqlsecret.yml

  338  kubectl get secret

  339  kubectl describe secret my-db-secret
  
  //////////MYSQL Deployment command//////////////////////////////////////////////////
  //////////////////myql-deployment.yml   file//////////////////////////////
  
 
  297  kubectl apply -f mysql-deployment.yml
  298  git pull
  299  kubectl apply -f mysql-deployment.yml
  300  kubectl get deploy
  301  kubectl describe deploy mysql
  302  kubectl get pod
  303  kubectl exec -it nameofthepod --bin-bash
  304  mysql -u root -p
  305  kubectlt get pod
  306  kubectl get pod
  307  kubectl exec -it mysql-deployment-5495c77f58-976mm /bin/bash
  308  kubectl delete deploy myapp-deployment
  309  history




