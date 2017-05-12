

# Hotel Room Details Component


### Component Use

``` html

<t-hotel-rooms
    	token-response = "{{tokenResponse}}"
		roomsData-url = "e.g BASEURL/api/content/…" 
		signedinUserDetails-url = "e.g BASEURL/api/content/…"
		resources = {{resources}} 
		lang = "en">
</t-hotel-rooms>


```
Hotel wise and Room wise details: API should return  Room Name, Facilities, Adult and child count, special notes (shown in green), Single / All occupant’s details and relate input fields needed.

### Input Option to Component

```javascript

			var Hotels = {
				Hotel 1{
					Room1{
						Room Name : '',
						Facility : '',
						Adult Count : '',
						Child Count : '',
						Notes{
							Note1 : '',
							Note2 : '',
						}
						Single{
							Include heading : '',
							Fields{
								Title, FirstName, LastName, EmailID,
							}
						}
						Multiple{
							First Adult Fields {
							}
							Other Guest Fields{
							}
						}
					}	
					Room2{
					}
				}					
				Hotel 2{
					Room1{
					}
					Room2{
					}
				}

			}

		
```

# Validations 
- performed when the control loose the focus, to be confirmed.

# Questions
- How to work with signed in user?

# Output
-  Hotel wise Room wise guest details
