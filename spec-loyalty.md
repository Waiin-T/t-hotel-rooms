
# Loyalty program Component


## Component Use

``` html

<t-loyalty ProgramData-url = ="e.g BASEURL/api/content/…"></t-loyalty>


```


## Input Option to Component

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

### Validations 
- performed when the control loose the focus, to be confirmed.

### Questions
- How to work with signed in user?

### Output
-  Hotel wise Guest list 
