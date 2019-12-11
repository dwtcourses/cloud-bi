# cloud-bi
Cloud Business Intelligence for marketing, sales, finance and operations

Google Analytics account 
-  

`ga-service-account.json`

How to create Google Service Account  
f.e. https://console.developers.google.com/apis/credentials?project=omega-portal-211213&authuser=1&organizationId=321028625189  
Create service account key  
New Service Account  
This will download JSON   

Add Service account GA user to Google Analytics  

`google-analytics-metrics-all.json`  

``{
    "view_id": "170687010"
  }
``

![GA VIEW_ID](./docs/img/ga_view_id.png)
![GA VIEW_ID](./docs/img/ga_view_id_2.png)

  
Facebook
-

Create Application  
https://developers.facebook.com/apps/  

Copy APP_ID and APP_SECRET 
![FB_app_1](./docs/img/fb_app_1.png)

Create `Never Expired - Extended Page Token`  
!!! Generating Never Expiring Facebook Page Access Token  
https://sujipthapa.co/blog/generating-never-expiring-facebook-page-access-token

Scope:  
- pages_show_list 
- manage_pages 

https://developers.facebook.com/tools/explorer  
https://developers.facebook.com/tools/debug/accesstoken/

![FB_TOKEN](./docs/img/fb_token_1.png)
![FB_TOKEN](./docs/img/fb_token_2.png)
![FB_TOKEN](./docs/img/fb_token_3.png)
![FB_TOKEN](./docs/img/fb_token_4.png)

