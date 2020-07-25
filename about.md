---
layout: page
title: About
permalink: /about/
---

We live in a world where most Indian news outlets are dedicated to the "left" and the "right" – making the news increasingly polarised. We live in a world where misinformation spreads far faster than the truth –- making it increasingly difficult to know what is real and what is not. 

I am Ridhi. Kashmiri and a freelance journalist studying Cultural Studies and linguistic heritage of Kashmir.


### Contact me

[@ridhi.rebuts](https://www.instagram.com/ridhi.rebuts/)
<form name="submit-to-google-sheet" >
      <div class="container">
   
<table id="wrapperax">
  <tr  id="clearfix">
    <td> <input type="email"  id="email" placeholder="Your Email Address" name="email" required></td>
   
  </tr>
  <tr >
    <td >  
        <div>
         
          <button  id="axbutton" type="submit">Subscribe</button>
        </div></td>
  
  </tr>
</table>
   
       
    
      </div>
  

  </form>
<style>
    
#wrapperax{
    width: 100%;
}
#email {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}
#email:focus {
  background-color: #ddd;
  outline: none;
}
#axbutton {
  background-color: #a1d9e2;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
      font-weight: bold;
}
#axbutton:hover {
  opacity:1;
}
/* Float cancel and signup buttons and add an equal width */
#axbutton {
  float: left;
 
}

/* Add padding to container elements */
 .container {
  padding: 16px;
}

/* Clear floats */
/*.clearfix::after {
  content: "";
  clear: both;
  display: table;
}
 */


  </style>

  
  <script src="https://wzrd.in/standalone/formdata-polyfill"></script>
<script src="https://wzrd.in/standalone/promise-polyfill@latest"></script>
<script src="https://wzrd.in/standalone/whatwg-fetch@latest"></script>
  <script>
    const scriptURL = 'https://script.google.com/macros/s/AKfycbx2grdWQDw40IiqmaCAN55Lj2ezYsL5dKCIrw9wR04fKCoSyYC_/exec'
    const form = document.forms['submit-to-google-sheet']
 
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response =>console.log('Success!', response),document.getElementById('email').value = "",
              document.getElementById('clearfix').style.visibility = "collapse",
             document.getElementById('axbutton').innerHTML = "Thank You! Successfully  Subscribed ",
                  document.getElementById('axbutton').disabled = true)
        .catch(error => console.error('Error!', error.message))
    })
  </script>
