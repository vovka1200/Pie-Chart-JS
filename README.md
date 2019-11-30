# Pie Chart JS

Pie chart JS is a javascript written custom HTMLElement for creating easy pie charts in HTML

## Installation

Download the pie-chart-js.js file and then include it in your script using the following tag

```html
<script src="pie-chart-js.js">
</script>
```

## Usage

Pie chart JS is simple to use. Follow the example given in the chart-spending.html or the usage shown below.
The name, value and colour attributes are required by pchart-element for the HTMLElement to work properly. 

```html
<pie-chart id="pieChart" style="display:block;height:100%;width:100%;position:relative;">
    <pchart-element name="Rent" value="11000" colour="#00A676">
    <pchart-element name="Insurance" value="2100" colour="#373F51">
    <pchart-element name="Electricity" value="1100" colour="#008DD5">
    <pchart-element name="Gas" value="1250" colour="#DFBBB1">
    <pchart-element name="Internet" value="500" colour="#F56476">
    <pchart-element name="Phone" value="2000" colour="#E43F6F">
</pie-chart>
```
![alt text](https://github.com/lilave232/Pie-Chart-JS/raw/master/Screen%20Shot%202019-11-30%20at%208.07.13%20AM.png)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
