# timestamps

Created By: Iván
Project: New Horizons
Product: VARO
Created: January 30, 2025 2:23 PM
Last Edited Time: January 30, 2025 2:43 PM
Last Edited By: Iván

ISO 8601 Format Capability: year, month, day, hour, minutes, seconds, and milliseconds.
Example: 2022-09-27 18:00:00.000 = September 27, 2022 at 6 p.m.

|	Location in UI	|	Date type	|	Location of date in files	|	Following ISO 8601?	|	Intended 8601?	|	User Need	|	Notes	|	Files	|
| --- | --- | --- | --- | --- | --- | --- | --- | 
|	Email Subject	|	report created date	|	EmailRepo - line 68	|	Yes	|	Yes	|	Date	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-151945.png?version=1&modificationDate=1738275617525&cacheVersion=1&api=v2&width=250, https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-151945.png?version=1&modificationDate=1738275617525&cacheVersion=1&api=v2&width=250	|
|	Email message	|	report created date	|	EmojiEmail - line 34	|	Yes	|	Yes	|	Date	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-151835.png?version=1&modificationDate=1738275617350&cacheVersion=1&api=v2&width=250	|
|	Email message	|	report created date	|	EmojiEmail - line 100	|	Yes	|	Yes	|	Date, Time	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-151845.png?version=1&modificationDate=1738275617178&cacheVersion=1&api=v2&width=250	|
|	Email page	|	data collected date	|	EmailFragment - line 164email_fragment.xml - 142	|	No	|	Yes	|	Date, Time	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-151807.png?version=1&modificationDate=1738275616984&cacheVersion=1&api=v2&width=250	|
|	Past report details page	|	email generated date	|	ReportDetailsFragment - line 121report_details.xml - line 149	|	No	|	Yes	|	Date, Time	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-152026.png?version=1&modificationDate=1738275616810&cacheVersion=1&api=v2&width=250	|
|	Past report details page	|	logger data capture date	|	ReportDetailsFragment - line 146report_details.xml - line 88	|	No	|	Yes	|	Date, Time	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-152019.png?version=1&modificationDate=1738275616652&cacheVersion=1&api=v2&width=250	|
|	Past report details page	|	report created date	|	ReportDetailsFragment - line 147report_details.xml - line 106	|	No	|	Yes	|	Date, Time	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-152504.png?version=1&modificationDate=1738275616454&cacheVersion=1&api=v2&width=250	|
|	Past reports entry	|	report created date	|	PastReportsAdapter - line 43past_report_item.xml - line 49	|	No	|	Yes	|	Date, Time	|	Not displayed	|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-152945.png?version=1&modificationDate=1738275616291&cacheVersion=1&api=v2&width=250	|
|	Chart information page	|	appliance date of production	|	VaroChartDialog - line 156	|	No	|	Yes	|	Date	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-153007.png?version=1&modificationDate=1738275616093&cacheVersion=1&api=v2&width=250	|
|	Chart information page	|	logger date of production	|	VaroChartDialog - line 165	|	No	|	Yes	|	Date	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-153008.png?version=1&modificationDate=1738275615937&cacheVersion=1&api=v2&width=250	|
|	Chart information page	|	compressor 1 date of production	|	VaroChartDialog - line 172	|	No	|	Yes	|	Date	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-153010.png?version=1&modificationDate=1738275615750&cacheVersion=1&api=v2&width=250	|
|	Chart information page	|	compressor 2 date of production	|	VaroChartDialog - line 178	|	Yes	|	Yes	|	Date	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-153011.png?version=1&modificationDate=1738275615587&cacheVersion=1&api=v2&width=250	|
|	Chart page header	|	date of first record from data	|	VaroChartDialog - line 107ChartData - line 85	|	No	|	Yes	|	Date, Time	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-153037.png?version=1&modificationDate=1738275615432&cacheVersion=1&api=v2&width=250	|
|	Chart page header	|	date of last record from data	|	VaroChartDialog - line 116ChartData - line 86	|	No	|	Yes	|	Date, Time	|		|	https://launchcg.atlassian.net/wiki/download/thumbnails/3335684097/image-20250129-153038.png?version=1&modificationDate=1738275615170&cacheVersion=1&api=v2&width=250	|