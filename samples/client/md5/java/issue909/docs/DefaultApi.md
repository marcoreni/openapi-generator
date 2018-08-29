# DefaultApi

All URIs are relative to *http://md5.jsontest.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getmd5**](DefaultApi.md#getmd5) | **GET** / | Print md5


<a name="getmd5"></a>
# **getmd5**
> Md5 getmd5(text)

Print md5

md5

### Example
```java
// Import classes:
//import org.openapitools.client.ApiException;
//import org.openapitools.client.api.DefaultApi;


DefaultApi apiInstance = new DefaultApi();
String text = "text_example"; // String | text
try {
    Md5 result = apiInstance.getmd5(text);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling DefaultApi#getmd5");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **text** | **String**| text |

### Return type

[**Md5**](Md5.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

