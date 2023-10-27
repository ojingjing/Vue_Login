# Vue_Login   
---
[ecole Notion정리](https://creative-respect-76a.notion.site/ecole-4Day-6e92e447fc454ffeaddfb4e5339b8fd9?pvs=4)      
[Vue사용방법 참고](https://mmsesang.tistory.com/entry/Visual-Studio-Code-VSCode-%EC%97%90%EC%84%9C-Vuejs-%ED%99%98%EA%B2%BD-%EC%84%B8%ED%8C%85%ED%95%98%EA%B8%B0)     
[Appwrite](https://appwrite.io/docs/quick-starts/vue)      
---
# Setting   
## 1.Vue설정   
<img width="616" alt="image" src="https://github.com/ojingjing/Vue_Login/assets/48702158/7acd030b-b808-4011-a7ff-4317e4b53b19">

```
  $npm install -g @vue/cli
```
```
  $vue create my-app
```
```
  $cd my-app
  $npm run serve
```
---  
## 2.Appwrite 사용하기  
```
 $npm init vue@latest my-app && cd my-app
```
```
 $npm install appwrite
```
```
 import { Client, Account} from 'appwrite';

export const client = new Client();

client
    .setEndpoint('https://cloud.appwrite.io/v1')
    .setProject('<YOUR_PROJECT_ID>'); // Replace with your project ID

export const account = new Account(client);
export { ID } from 'appwrite';

```
---   
## LoginCss    
1.초기의 모습     
<img width="660" alt="image" src="https://github.com/ojingjing/Vue_Login/assets/48702158/88869cc1-5ca3-4663-97af-c116d406c789">     
2.디자인 도안   
<img width="336" alt="image" src="https://github.com/ojingjing/Vue_Login/assets/48702158/582ed55d-1421-4420-a8c2-edc8d7732341">         
3.css입히는 과정     
<img width="336" alt="image" src="https://github.com/ojingjing/Vue_Login/assets/48702158/095d7d31-e96c-4e39-8c16-26956aebe6f7">         
4.Router적용모습   
<img width="632" alt="image" src="https://github.com/ojingjing/Vue_Login/assets/48702158/8a885232-8772-4a7b-89dc-cd63596ec763">    



---
## CloudPanel      
AWS,cloudFlare,cloudPanel        
https://cp.omin.kr/

<img width="1230" alt="image" src="https://github.com/ojingjing/Vue_Login/assets/48702158/a1914e95-4dbf-4b4d-9026-704e8548ab84">   
<img width="600" alt="image" src="https://github.com/ojingjing/Vue_Login/assets/48702158/c13f007d-b612-42d1-a02a-4d42a8d18d81">    
<img width="1258" alt="image" src="https://github.com/ojingjing/Vue_Login/assets/48702158/7c593178-41c2-429a-bde5-eadb3e25d359">     
<img width="1190" alt="image" src="https://github.com/ojingjing/Vue_Login/assets/48702158/e625b920-0bc1-43a1-8771-eb08f22863d0">     
<img width="876" alt="image" src="https://github.com/ojingjing/Vue_Login/assets/48702158/ce1e9169-f72b-40fb-b3a1-b0713f5528b2">    
<img width="865" alt="image" src="https://github.com/ojingjing/Vue_Login/assets/48702158/bf554c8e-d794-417d-b6cb-8c8e7d1238fe">     
환경설정 완료!!    
<img width="1459" alt="image" src="https://github.com/ojingjing/Vue_Login/assets/48702158/962c4dbc-5c78-4ade-b219-47bd29f81256">                 


