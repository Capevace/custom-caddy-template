![](resources/screenshot-1.png)

# custom-caddy-template
> My personal customized Caddy v2 template

## How to use
Add the following to your Caddyfile security section:

```
{
	...

	security {
		authentication portal myPortal {
			ui {
        			...
				
        
        			template generic "/home/services/volumes/caddy/custom-template/templates/generic.template"
				template portal "/home/services/volumes/caddy/custom-template/templates/portal.template"
				template login "/home/services/volumes/caddy/custom-template/templates/login.template"
				template sandbox "/home/services/volumes/caddy/custom-template/templates/sandbox.template"
				custom css path "custom-template/css/output.css"
				
				
				...
			}
      		}
	}
}
      
...
```

## Screenshot
![](resources/screenshot-2.png)
![](resources/screenshot-3.png)
