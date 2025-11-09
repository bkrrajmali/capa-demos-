# capa-demos-


 kubectl port-forward svc/highway-animation-service -n highway-animation 8082:3000 --address=0.0.0.0 &


argocd app create app-2 \
  --repo https://github.com/bkrrajmali/capa-demos-.git \
  --path ./capa-demos \
  --dest-namespace app-2 \
  --dest-server https://kubernetes.default.svc


   argocd app list
<img width="1671" height="118" alt="image" src="https://github.com/user-attachments/assets/a6f6b6d8-89ac-40f0-b839-093958235321" />



kubectl create ns app-2

argocd app sync app-2
