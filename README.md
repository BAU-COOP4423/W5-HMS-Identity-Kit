# (W5) HMS Identity Kit
5th week content of COOP4423 course

![Latest Version](https://img.shields.io/badge/latestVersion-1.0-yellow) ![Java](https://img.shields.io/badge/language-java-blue) ![Minimum SDK Version](https://img.shields.io/badge/minSDK-21-orange)

## Used Technologies
Documentation can be found at this <a href="https://developer.huawei.com/consumer/en/hms/huawei-identitykit/" target="_blank">HMS Identity Kit</a>

The demo implements the Identity Kit API to obtain the user address interface, and assembles and returns the selected address information to the interface.

## Obtaining a User Address
- Instantiate the request object by using the new UserAddressRequest method. Then, call the getUserAdddress API. The code location is in the getUserAddress method in the MainActivity.java file.

- Display the address selection page by calling the startActivityResult method of Status. The code location is in the startActivityForResult method in the MainActivity.java file.

- After the user selects an address, call the parseIntent method of UserAddress in onActivityResult of the page and obtain the address from the returned result. The code location is in the onActivityResult method in the MainActivity.java file.



## Clone the Repository

### With SSH
```
git clone git@github.com:BAU-COOP4423/W5-HMS-Identity-Kit.git
```

### With HTTPS
```
git clone https://github.com/BAU-COOP4423/W5-HMS-Identity-Kit.git
```

## Utilized resources
- <a href="https://developer.huawei.com/consumer/en/codelab/HMSIdentityKit/index.html#0">HMS Identity Kit Codelab Steps</a>

#### Note:
> Do not hesitate to open an <a href="https://github.com/BAU-COOP4423/W3-MVVM-Retrofit/issues" target="_blank">issue</a> for your questions.

