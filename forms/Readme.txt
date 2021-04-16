Fully working PHP/AJAX contact form script is available in the pro version of the template.
You can buy it from: https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/



https://docs.google.com/forms/d/e/1FAIpQLSdhuDMKZxl6lNnCFHctXtU6s2n_CZwqCVjFg1r4TvcvAsLOwQ/viewform?usp=pp_url
&entry.1533605505=garbageName
&entry.683228370=garbageEmail
&entry.1794083874=garbageSubject
&entry.1565749702=garbageMessage


<form name="gform" id="gform" enctype="text/plain"
  action="https://docs.google.com/forms/d/e/1FAIpQLSdhuDMKZxl6lNnCFHctXtU6s2n_CZwqCVjFg1r4TvcvAsLOwQ/formResponse?"
  target="hidden_iframe" onsubmit="submitted=true;">
  Your Name:<br>
  <input type="text" name="entry.1533605505" id="entry.1533605505"><br>

  Your Email:<br>
  <input type="text" name="entry.683228370" id="entry.683228370">

  Subject:<br>
  <input type="text" name="entry.1794083874" id="entry.1794083874">

  Message:<br>
  <input type="text" name="entry.1565749702" id="entry.1565749702">

  <input type="submit" value="Submit">
</form>

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>







<form>
  <div class="row">
    <div class="form-group col-md-6">
      <label for="name">Your Name</label>
      <input type="text" name="name" class="form-control" id="name" required>
    </div>
    <div class="form-group col-md-6">
      <label for="name">Your Email</label>
      <input type="email" class="form-control" name="email" id="email" required>
    </div>
  </div>
  <div class="form-group">
    <label for="name">Subject</label>
    <input type="text" class="form-control" name="subject" id="subject" required>
  </div>
  <div class="form-group">
    <label for="name">Message</label>
    <textarea class="form-control" name="message" rows="10" required></textarea>
  </div>
  <div class="text-center"><button type="submit">Send Message</button></div>



  <form name="gform" id="gform" enctype="text/plain"
    action="https://docs.google.com/forms/d/e/1FAIpQLSdhuDMKZxl6lNnCFHctXtU6s2n_CZwqCVjFg1r4TvcvAsLOwQ/formResponse?"
    target="hidden_iframe" onsubmit="submitted=true;">
    <div class="row">
      <div class="form-group col-md-6">
        Your Name:<br>
        <input type="text" name="entry.1533605505" id="entry.1533605505" class="form-control" required><br>
      </div>
      <div class="form-group col-md-6">
        Your Email:<br>
        <input type="text" name="entry.683228370" id="entry.683228370" class="form-control" required><br>
      </div>
    </div>
    <div class="form-group">
      Subject:<br>
      <input type="text" name="entry.1794083874" id="entry.1794083874" class="form-control" required><br>
    </div>
    <div class="form-group">
      Message:<br>
      <input type="text" name="entry.1565749702" id="entry.1565749702" class="form-control" required><br>
      <!-- <textarea class="form-control" name="message" rows="10" required></textarea> -->
    </div>
    <br>
    <input type="submit" value="Submit">
  </form>

  <iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>


  