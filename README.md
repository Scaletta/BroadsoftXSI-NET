# BroadsoftXSI-NET
C# wrapper for the Broadsoft XSI API

### Prerequisites

```
Visual Studio 2017
.NET Framework 4.5.2
```

## Status

Here you can check the status of implementations

### Profile-level

Change stuff on the userlevel.
Requires the users username and password.

```
Profile - 100%
This method allows the retrieval of profile information for a particular user.  It returns information about a user as stored in BroadWorks.  It also allows for retrieval of users’ feature access codes (FAC) and device registrations, as well as schedules, for the Holiday and Time Schedule services.

Profile/Fac - 0% 
This method retrieves all feature access codes configured for services, which are assigned for a particular user.  For each feature access code, the name and code are returned.  If an alternate code has been defined for a feature access code in BroadWorks, then that alternate code is also returned.

Profile/Schedule - 0%
This method returns schedules assigned to a user.  Holiday and Time schedules form the list of schedules a user can have.  This command returns the name and type of each user schedule.  Use commands described in the subsections to obtain only Holiday or Time schedules, as well as to obtain detailed schedule information.

Profile/Password/Portal - 0%
This method allows you to configure your BroadWorks web portal password. This password is used to log in to the BroadWorks web portal as well as any BroadWorks client applications; it is also the password used to authenticate a subscriber over the BroadWorks OCI-P, CAP, and Xtended Services Interfaces.

Profile/Registrations - 0%
This method retrieves the list of Session Initiation Protocol (SIP) registrations that belong to devices or device endpoints which belong to a user.

```

### Service-level

```
Call Forwarding Always - 100%
This service allows the setting and retrieval of the Call Forwarding Always configuration. Call Forwarding Always (CFA) enables a user to redirect all incoming calls to another phone number. If activated, a user must specify the forwarding number.

Services/CallForwardingBusy - 50%
This service allows the setting and retrieval of the Call Forwarding Busy configuration. Call Forwarding Busy (CFB) enables a user to redirect calls to another destination when an incoming call encounters a busy condition.  If activated, a user must specify the forwarding number.

Services/CallForwardingNoAnswer - 0%
This service allows the setting and retrieval of the Call Forwarding No Answer configuration. Call Forwarding No Answer (CFNA) enables a user to redirect calls to another destination when an incoming call is not answered within a specified number of rings. If activated, a user must specify the forwarding number and the number of rings before forwarding.

Services/CallForwardingNotReachable - 0%
This service allows for the setting and retrieval of the Call Forwarding Not Reachable service. Call Forwarding Not Reachable forwards calls to a different number when the user’s phone is not registered.

Services/CallForwardingSelective - 0%
This service allows the configuration and retrieval of some of the Call Forwarding Selective configurations.  It only allows the enabling and disabling of criteria related to the service.  Additional criteria may not currently be added.
Call Forwarding Selective (CFS) enables a user to define criteria that causes certain incoming calls to be redirected to another destination.  If an incoming call meets user-specified criteria, the call is redirected to the user-specified destination.  A criterion set is based on incoming calling line identity, time of day, and day of week.  Multiple criteria sets can be defined.

Services/CallNotify - 0%
This service allows for the configuration and retrieval of some of the Call Notify configurations.  It only allows for the enabling and disabling of criteria related to the service.  Additional criteria may not currently be added.
Call Notify (CN) enables a user to define criteria that cause certain incoming calls to trigger an e-mail notification.  If an incoming call meets user-specified criteria, an e-mail (or short message to a cell phone) is sent to the notify address, informing the user of the details of the incoming call attempt.  A criterion set is based on incoming calling line identity, time of day, and day of week.  Multiple criteria sets can be defined.

Services/CallPark - 0%
The Call Park feature allows users to park a call so that any member of a group can retrieve it with the Call Park Retrieve function.
A call can be parked against any user of a group, including the user who parks the call.  However, a user can only have one call parked at a time.
This service identifies which Call Park group the user belongs to, if any, and the list of users in the group.

```
More coming soon

### Serviceprovider-level

```
More coming soon
```

## Deployment

Compile using Visual Studio 2017

## Authors

* **G.T Nomikos** - *Everything* - [Scaletta](https://github.com/Scaletta)

## License

This project is licensed under the GNU 3.0 License - see the [LICENSE.md](LICENSE.md) file for details
