# Youtube-Data-API-Model

![image](https://user-images.githubusercontent.com/110320717/226411478-de793e4c-7b52-4139-9ca8-59d95ad7e653.png)

# Introduction

The YouTube Analytics API enables you to generate custom reports containing YouTube Analytics data. The API supports reports for channels and for content owners. Report fields are characterized as either dimensions or metrics:

* Dimensions are common criteria that are used to aggregate data, such as the date on which an action occurred or the country where the users were located.

  In a report, each row of data has a unique combination of dimension values. As such, the dimensions you choose for a report determine how YouTube calculates the values for the metrics in that report.
  

* Metrics are individual measurements related to user activity, ad performance, or estimated revenue. User activity metrics include things like video view counts and ratings (likes and dislikes).

The Analytics API provides filtering and sorting parameters, so the calling application does not need to natively support those functions. The API also allows you to retrieve data for YouTube Analytics groups, where a group is a custom collection of up to 500 videos, playlists, channels, or assets.
