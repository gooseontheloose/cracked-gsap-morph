# cracked-gsap-morph
dont arrest me please. doesnt actually work, it only removes the buy gsap screen.

## GSAP Plugin Usage

This example demonstrates how character codes and plugin scripts can be used in combination with the GreenSock Animation Platform (GSAP) library to check the current website's domain and restrict certain functionality based on specific domains.

### Disclaimer

- This code is for educational purposes only and should not be used for unauthorized activities.
- Always support developers and respect their licenses and terms of use for any libraries or plugins.

### Allowed Site List

In the provided script, an allowed site list is defined by an array of character codes that spell out the domain name. For instance, `greensock.com` is represented as:

```javascript
[103, 114, 101, 101, 110, 115, 111, 99, 107, 46, 99, 111, 109]
```

## Extending Allowed Site List

You can extend this list by adding your own domain name character codes.

## Checking Allowed Sites

The script checks whether the current site's domain matches any of the allowed domains. You can add your domain to the list by converting it to an array of character codes. For example, if your site is `example.site`, you would convert it to:


```
currentSite = 'example.site';
t = [/* ... */, currentSite, /* ... */, /* ... */, /* ... */];
```


## Script Breakdown

- The script involves using character codes to represent domain names.
- The `p` function converts arrays of character codes to strings.
- The allowed site list is an array of character code arrays.
- The script checks if the current site's domain is in the allowed site list.
- If the current site is allowed, the script executes specific functionality.

## Using GSAP Plugins

The code also references GSAP plugins like `SplitText3.min.js` and `CustomEase3.min.js`. These plugins enhance animation capabilities. Make sure to include these plugins in your project if you plan to use them.

## Getting Started

1. Include the necessary GSAP libraries and plugins in your project.
2. Replace `example.site` with your actual domain name.
3. Customize the script to fit your desired functionality.

Remember to adhere to ethical coding practices and respect the terms of use for libraries and plugins.
