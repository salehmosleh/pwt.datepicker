pwt.datepicker
==============
created by reza babakhani (@babakhani). i just customize it and add some features.

Jalali calendar datepicker, which depends on https://github.com/babakhani/PersianDate

[Documents](http://babakhani.github.io/PersianWebToolkit/datepicker)

example : 
```
$("#inputtext").persianDatepicker({
  altField: "##inputtext" , // show resualt of datetime selected into "altField"
  into : '#parentelement', // add htmls of datetime picker inside "into"
  timePicker: {
    enabled: true, // show it
    showMeridian:false // hide AM/PM in time picker
  } ,  
  persianDigit:false, // convert numbers to persian
  altFormat: "YYYY-MM-DD HH:mm:ss" // format of resualt
});
```

persian, datepicker, date, khayam, jalali, jquery, plugin, javascript, js, persian web toolkit, pwt,
bootstrap timepicker, bootstrap datetimepicker

