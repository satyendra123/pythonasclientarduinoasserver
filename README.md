# pythonasclientarduinoasserver
python exe works as a client and arduino as a server. match the data with the database and send command to arduino with ethernet shield

isme hum apna ek python ka script likhte hai jo ki client ki tarah kaam karega aur us ip aur port par connect karne ka try karega jo ki humne apne arduino me mentioned kiya hua hai. so basically yaha par humara arduino jo hai wo server ki tarah kaam karta hai aur humara python script jo hai wo client ki tarah kaam karta hai. so humara python ka script hai wo arduino se |HLT% ka command leta hai aur |OK% ka command revert back krta hai jab usko |HLT% ka command mil jata hai to. aur actually jo humara python ka script hai wo database ke sath connection banata hai aur database ke table se ENTRY aur EXIT table se data fetch karta hai. agar jaise hi ise 1 milta hai database ke table me ye arduino ko |OPENEN% ka command send kar deta hai aur humara arduino us command ko receive karega aur relay ko trigger kara dega
