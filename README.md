# PotholeCivilAuthorityAndroidApp
This is repository for Pothole Civil Authority Android app

This is one of the components of a complete Pothole App 



### Repo Links to other components : 

- [Pothole User Android App (Current)](https://github.com/TharunRajeev/socialcopapp)
- [Pothole User Server (Private)](https://github.com/TharunRajeev/socialcopserver)
- [Pothole Civil Authority Android App](https://github.com/TharunRajeev/SocialCop-CivilAuthoritiesApp)
- [Pothole Civil Authority Server (Private)](https://github.com/TharunRajeev/SocialCop-CivilAuthoritiesAppServer)


This app is the frontend interface for Admin / Civil Authorities .

This app communicates with the Node js / Express backend server , and talks to it via set of APIs 

### Prequistes 

An account must be created for the Civil authority in database manually , specifying contact details and area that civil authority operates in GeoJSON format (no interface exists for that)

## Features of this app
1) View and track status of Potholes registered or reported within you locality.
2) Filter Potholes based on current status  (Resolved , Assigned  , Rejected , etc)
3) Merge multiple into one pothole , i.e. One Pothole could be reported multiple times , so Admin/Authority can merge them into one, Also in new updates , Potholes within same vicinity are merged automatically in the backend
4) One to Many Communication between Authority and User , Authority can update the Pothole status , so that user can get notified and track the status of Potholes too , Merged Potholes will notify all the users the users realted to that Pothole.
5) HeatMaps , to show the location with most occuring potholes , so that Authority can get an idea of which location suffers from more potholes
6) The app have notifications features and email updates too.
7) There are more technological details and security factors too , I won't go into implementation detail over here.

## Technologies Used

Android (Java) , Retrofit , Glide , etc.


#### NOTE :
> Replace the BASE_URL in strings , with your server url.

## Screenshots
<img src="https://github.com/TharunRajeev/SocialCop-CivilAuthoritiesApp/blob/master/Screenshot3.png" width="30%" height="auto" alt="Screenshot of App"/>

> There are few fixes that are needed to be done , so before using it into production make sure of some fixes.
