# url-shortener program

## Foreword
This is sample program which consist of two features:
* `Open account and provide userId and password[in encrypted].`
* `Register url and return shortened url.`
* `Update redirect counter to find out number of redirect count.`
* `API Documentation is available using springfox-swagger and accessible using ::` *http://localhost:8080/swagger-ui.html*
    
    ### ``Internal Features``
    * ` Endponit is exposed to view all opened account information`
    * ` Endpoint is exposed to view registered url information`
* `i18n support enabled.`
## Future Improvement
* Need work on url shorting string to ensure always produce unique random string.


## Demo Setup
1. Checkout project from https://github.com/sauravsingh29/url-shortener.git
2. Run application as spring boot from ide or maven command *mvn spring-boot:run*
3. Access H2 in-memory console using http://localhost:8080/h2-console. [Get jdbc info from application.properties]

