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
<img width="684" height="640" alt="image" src="https://github.com/user-attachments/assets/0c34a06c-446e-49b3-a1e5-d349ce2288d6" />

<img width="697" height="694" alt="image" src="https://github.com/user-attachments/assets/af7030b2-0ea8-42de-b06e-841a40829884" />

<img width="778" height="624" alt="image" src="https://github.com/user-attachments/assets/b1f959c8-ae73-4041-bf76-9c5d92f4f0a8" />


