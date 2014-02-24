Monthpicker
===========

View examples and some doc [live](http://lucianocosta.info/jquery.mtz.monthpicker/).

##Update: Add Clear button for clear the input.
###Clear options:
#### options.clear
Type: `Boolen`
Default value: `'false'`

A boolen value that is used to flag whether to display .
#### options.clearText
Type: `String`
Default value: `'clear'`

A string value that is used to display the text.
### Usage Examples

#### Default Options

$('input').monthpicker({
				pattern: 'yyyy-mm',
				selectedMonth:02,
				selectedYear: 2014,
				startYear: 2010,
				finalYear: 2014,
				monthNames: ['一月', '二月', '三月', '四月', '五月', '六月', '七月', '八月', '九月', '十月', '十一月', '十二月'],
				//['Jan', 'Fev', 'Mar', 'Abr', 'Mai', 'Jun', 'Jul', 'Ago', 'Set', 'Out', 'Nov', 'Dez'],
				clear: true,
				clearText: '清除'
			});
			.bind('monthpicker-click-clear',function(e){
				alert('click on clear button');
			});
```
