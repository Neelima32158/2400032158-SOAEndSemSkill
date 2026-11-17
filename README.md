# Customer Microservice – GET endpoint

This is a minimal Spring Boot project for the endpoint:

`GET http://localhost:8080/ms1/add?a=5&b=10`

Expected response body:

`15`

## Open in Spring Tool Suite (STS)

1. Extract this ZIP file.
2. In STS, choose **File → Import → Maven → Existing Maven Projects**.
3. Browse to the extracted `customer-microservice` folder.
4. Select the project and click **Finish**.
5. Wait for Maven dependencies to download.
6. Open `CustomerMicroserviceApplication.java`.
7. Right-click the file and choose **Run As → Spring Boot App**.
8. Test the URL in a browser or Postman:
   `http://localhost:8080/ms1/add?a=5&b=10`

## Important

`src/main/resources/contracts/customer.yml` is a simple YAML contract description.
It documents the expected request and response; it is not, by itself, an executable
Spring Cloud Contract test or generated stub.
