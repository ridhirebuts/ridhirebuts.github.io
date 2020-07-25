---
layout: page
title: About
permalink: /about/
---

We live in a world where most Indian news outlets are dedicated to the "left" and the "right" – making the news increasingly polarised. We live in a world where misinformation spreads far faster than the truth –- making it increasingly difficult to know what is real and what is not. 

I am Ridhi. Kashmiri and a freelance journalist studying Cultural Studies and linguistic heritage of Kashmir.


### Contact me

[@ridhi.rebuts](https://www.instagram.com/ridhi.rebuts/)
<script>
  var $form = $('form#test-form'),
    url = 'https://script.google.com/macros/s/AKfycbx2grdWQDw40IiqmaCAN55Lj2ezYsL5dKCIrw9wR04fKCoSyYC_/exec'

$('#submit-form').on('click', function(e) {
  e.preventDefault();
  var jqxhr = $.ajax({
    url: url,
    method: "GET",
    dataType: "json",
    data: $form.serializeObject()
  }).success(
    // do something
  );
})
  </script>
<form id="test-form">
  
  <div>
    <label>Field 1</label>
    <input type="text" name="email" placeholder="Field 1"/>
  </div>

  <div>
    <label>Field 2</label>
    <input type="text" name="name" placeholder="Field 2"/>
  </div>
  

  <div>
    <button type="submit"id="submit-form">Submit</button>
  </div>


</form>
