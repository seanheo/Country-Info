README
Country-Info app

Description
After app starts, it fetches the country info from the given endpoint and show each country's name, region, code and capital on the screen.

Features
1. Used ViewModel to retain data when activity restarts due to rotation or other config changes. On those cases, 
activity gets retained data first, then it fetches updated data from backend
2. Handle different fetch status like Loading, Errors and Success. On Error, it shows messages using Toast
3. Applied 5sec timeout to limit fetching time. When timeout happens, it shows a corresponding error message
4. Used CardView for better UI

Used libraries
1. RxJava for reactive programming
2. Retrofit for networking with backend
3. Gson for parsing json and creating POJO
