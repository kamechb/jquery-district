# jquery.district 地区选择

### Example:

#### HTML snippet:
  <div id="district">
    <select id="province"></select>
    <select id="city"></select>
    <select id="district"></select>
  </div>

#### Usage:
  jQuery.District("#district", {
    url: '/district/',
    onChange: function(data){
      console.log(this);  // `this` is changed element 
      console.log(data);  // `data` is a district code like '330000'
    }
  })

