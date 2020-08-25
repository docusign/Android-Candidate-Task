# Organization Viewer App

Requirements
1. Users should be able to browse a list of Non-profit Organizations
2. Unit and functional tests should be written where appropriate
3. Code should be well architected and modular
4. Check the API Spec for necessary endpoint information
5. Feel free to use open source libraries (Retrofit, ButterKnife,
Rx, etc.) as you see fit.

API URL: https://projects.propublica.org/nonprofits/api/v2/search.json

Sample Response:
```
{
	"total_results": 1977430,
	"organizations": [{
		"ein": 464744976,
		"strein": "46-4744976",
		"name": "0 DEBT EDUCATION INC",
		"sub_name": "0 DEBT EDUCATION INC",
		"city": "SANTA ROSA",
		"state": "CA",
		"ntee_code": "P51",
		"raw_ntee_code": "P51",
		"subseccd": 3,
		"has_subseccd": true,
		"have_filings": true,
		"have_extracts": true,
		"have_pdfs": true,
		"score": 1.0
	}, {
		"ein": 272620044,
		"strein": "27-2620044",
		"name": "0 TOLERANCE INC",
		"sub_name": "0 TOLERANCE INC",
		"city": "SUWANEE",
		"state": "GA",
		"ntee_code": "B99",
		"raw_ntee_code": "B99",
		"subseccd": 3,
		"has_subseccd": true,
		"have_filings": null,
		"have_extracts": null,
		"have_pdfs": null,
		"score": 1.0
	}],
	"num_pages": 100,
	"cur_page": 0,
	"page_offset": 0,
	"per_page": 100,
	"search_query": null,
	"selected_state": null,
	"selected_ntee": null,
	"selected_code": null,
	"data_source": "ProPublica Nonprofit Explorer API: https://projects.propublica.org/nonprofits/api/\nIRS Exempt Organizations Business Master File Extract (EO BMF): https://www.irs.gov/charities-non-profits/exempt-organizations-business-master-file-extract-eo-bmf\nIRS Annual Extract of Tax-Exempt Organization Financial Data: https://www.irs.gov/uac/soi-tax-stats-annual-extract-of-tax-exempt-organization-financial-data",
	"api_version": 2
}
```
