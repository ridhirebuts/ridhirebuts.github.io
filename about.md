---
layout: page
title: About
permalink: /about/
---

We live in a world where most Indian news outlets are dedicated to the "left" and the "right" – making the news increasingly polarised. We live in a world where misinformation spreads far faster than the truth –- making it increasingly difficult to know what is real and what is not. 

I'm Ridhi, a Kashmiri freelance journalist studying the cultural studies and linguistic heritage of Kashmir. I attempt to draw attention to lesser known truths and dissect complex narratives. 


### Contact me

[@ridhirebuts](https://www.instagram.com/ridhirebuts/)

### Drop Me a Line, Let Me Know What You Think
<form name="submit-to-google-sheet" >
      <div class="containeroffeedback">
    
<table id="wrapperax">
  <tr  id="clearfix">
    <td> <input  class ="forminputax" type="text" placeholder="Name" name="name" ></td>
  </tr>
  <tr id="clearfixtwo"> 
    <td> <textarea  rows="5" class ="forminputax" type="text"  id="email" placeholder="Your Message" name="message" required></textarea>
    </td>
    </tr>
  <tr >
    <td >  
        <div>
         
          <button  id="axbutton" type="submit">Submit</button>
        </div></td>
  
  </tr>
</table>
      </div>
  

  </form>
<style>
    
#wrapperax{
    width: 100%;
}
.forminputax{
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
  resize: none;
  font-family: inherit;
}
.forminputax:focus {
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
 .containeroffeedback {
  padding-top: 16px;
}

/* Clear floats */
/*.clearfix::after {
  content: "";
  clear: both;
  display: table;
}
 */


  </style>

  
  
  <script>
    const scriptURL = 'https://script.google.com/macros/s/AKfycbzwKpDbgyX_PUQGfPxM3pUCXFlXuTXYdfOiL5j-_W2xR7U4arNG/exec'
    const form = document.forms['submit-to-google-sheet']
 
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response =>console.log('Success!', response),document.getElementById('email').value = "",
              document.getElementById('clearfix').style.visibility = "collapse",
             document.getElementById('axbutton').innerHTML = "Thank You! Successfully  Sent ",
                  document.getElementById('axbutton').disabled = true,
                         document.getElementById('clearfixtwo').style.visibility = "collapse")
        .catch(error => console.error('Error!', error.message))
    })
  </script>
