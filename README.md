<div align="center">
	<h1> Thailand Holidays </h1>
  
 [![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/logicspark/thailand-holidays/blob/main/LICENSE)

 <p align=center> 
	 Makes it easy to access holiday information for Thailand and create you own holiday. You can download a JSON file or make API requests to retrieve holiday data. Developed by <a href="https://www.logicspark.com">Logic Spark</a> team.
</p>

<a id="readme-top"></a>

</div>

<div align="center">
  <a href="#open_book-overview">Overview</a> - 
  <a href="#rocket-getting-started">Getting Started</a> - 
  <a href="#card_file_box-sample-data">Sample Data</a> -
  <a href="#speech_balloon-feedback">Feedback</a> -
  <a href="#books-license">License</a>
</div>

## :open_book: Overview

Provides a wide range of holidays, including public holidays and government holidays, as well as the flexibility to create your own personalized holidays. We have created a user-friendly interface website that you can review holiday data and craft your own calendar.


## :rocket: Getting Started

In the subsequent subsections, we will display the data structure of Thailand holiday. The sample data will be in JSON format. Let's get started!

## :card_file_box: Sample Data

Here is an example of holiday data in JSON format

### Holidays.json

```json
{
  "name": "วันขึ้นปีใหม่",
  "date": "2023-01-01",
  "holidayTypes": [
    "Public",
    "Government"
  ],
  "note": "String"
}
```

#### JSON Key Description

| Key            | Type     | Description                    |
| :------------- | :------- | :----------------------------- |
| `name` | `string` | Holiday Name |
| `date` | `string` | Holiday Date |
| `holidayTypes` | `array` | Holiday Types (Public and Government) |
| `note` | `string` | Holiday Description |


## :speech_balloon: Feedback

If there is missing/incorrect data or any suggestion, please reach out to us [here](https://github.com/logicspark/thailand-holidays/issues/new).

## :books: License

Distributed under the MIT License. See [LICENSE](https://github.com/logicspark/thailand-holidays/blob/main/LICENSE) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
