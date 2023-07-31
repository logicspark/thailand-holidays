<div align="center">
	<h1> Thailand Holidays for 2023 </h1>
  
 [![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/logicspark/thailand-holidays/blob/main/LICENSE)

 <p align=center> 
	 Complete Thailand holidays for 2023 in Thai and English. Public data is available in JSON format. Gather and verified by <a href="https://www.logicspark.com">Logic Spark</a> team.
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

Provides a database of Thailand holidays including public holidays and government holidays. We have created a simple [website](https://mha.logicspark.com) to review the data. Have fun exploring :sunglasses:

_Note: At the moment, we provide Thailand holidays for 2023._

## :rocket: Getting Started

In the subsequent subsections, we will display the data structure of Thailand holidays. The sample data will be in JSON format. Let's get started!

## :card_file_box: Sample Data

Here is an example of holiday data in JSON format

### Holidays.json

```json
{
  "nameTh": "วันขึ้นปีใหม่",
  "nameEn": "New year day",
  "date": "2023-01-01",
  "holidayTypes": ["Public", "Government"],
  "note": "My holiday"
}
```

#### JSON Key Description

| Key            | Type     | Description                               |
| :------------- | :------- | :---------------------------------------- |
| `nameTh`       | `string` | Holiday name in Thai                      |
| `nameEn`       | `string` | Holiday name in English                   |
| `date`         | `string` | Holiday date                              |
| `holidayTypes` | `array`  | Holiday types (`public` and `government`) |
| `note`         | `string` | Holiday description                       |

## :speech_balloon: Feedback

If there is missing/incorrect data or any suggestion, please reach out to us [here](https://github.com/logicspark/thailand-holidays/issues/new).

## :books: License

Distributed under the MIT License. See [LICENSE](https://github.com/logicspark/thailand-holidays/blob/main/LICENSE) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
