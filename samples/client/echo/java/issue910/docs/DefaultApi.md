# DefaultApi

All URIs are relative to *http://echo.jsontest.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getEcho**](DefaultApi.md#getEcho) | **GET** /test_string/test/test_date/{date} | Print echo


<a name="getEcho"></a>
# **getEcho**
> Echo getEcho(date)

Print echo

echo

### Example
```java
// Import classes:
//import org.openapitools.client.ApiException;
//import org.openapitools.client.api.DefaultApi;


DefaultApi apiInstance = new DefaultApi();
String date = "date_example"; // String | date
try {
    Echo result = apiInstance.getEcho(date);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling DefaultApi#getEcho");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **date** | **String**| date |

### Return type

[**Echo**](Echo.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

