![A-1](https://github.com/user-attachments/assets/e9cbc545-199e-4a7a-88cb-57ca4b975155)

---------------------------------------------------------------------------------------------
  Go through this file to ensure scalabilty of thiis form.
  If your have further explanation, chat me up via whatsapp (+2348130954145)
_____________________________________________________________________________________________

To scale up the form to have more than three(3) sections, just do:
    1. Go to "stepwiseform.html" file 

    2. scroll down to <ul class="form-stepper form-stepper-horizontal">

    3. locate the last <li> ... </li> tag, which should beas shown below
         <li class="form-stepper-active text-center form-stepper-list" step="3">
             <a class="">
                <span class="form-stepper-circle">
                    <span>3</span>
                </span>
                <div class="label sm-none">Caption 3</div>
             </a>
         </li>

    4. Copy and paste it on the next line and modify it to the fourth caption heading

    5. Afterward, scroll down to the <form> tag
           <form action="#" method="POST" class="form" enctype="multipart/form-data">

    6. Locate the last section, which should be as shown below
	     <section id="step-3" class="form-step d-none">
                 <h5 class="font-normal">Caption 3</h5>
                    <!-- Step 3 input fields -->
                 <div class="control_container">
                    <div class="row">
                        <div class="col"></div>
                        <div class="col"></div>
                    </div>
                    <div class="row">
                        <div class="col"></div>
                        <div class="col"></div>
                    </div>
                 </div>
                 <div class="navigButton">
                    <button class="button prev-btn btn-navigate-form-step" type="button" step_number="2">Prev</button>
                    <button class="button submit-btn" type="submit" name="addStudentsubmit"><i class="fa fa-save"></i> &nbsp; Submit</button>
                 </div>
             </section>

    7. Copy and paste it on the next line and modify it to the Fourth section by doing the following:
	   a. change <section id="step-3" class="form-step d-none"> TO <section id="step-4" class="form-step d-none">
	   b. change 
                 <div class="navigButton">
                    <button class="button prev-btn btn-navigate-form-step" type="button" step_number="2">Prev</button>
                    <button class="button submit-btn" type="submit" name="addStudentsubmit">Submit</button>
                 </div>
	       TO
                 <div class="navigButton">
                    <button class="button prev-btn btn-navigate-form-step" type="button" step_number="3">Prev</button>
                    <button class="button submit-btn" type="submit">Submit</button>
                 </div>
   8. Lastly, Modify the third(3rd) section to make it the NON-last section by doing:
	   a. change 
 		 <div class="navigButton">
                    <button class="button prev-btn btn-navigate-form-step" type="button" step_number="2">Prev</button>
                    <button class="button submit-btn" type="submit"><i class="fa fa-save"></i> &nbsp; Submit</button>
                 </div>
	      TO
		 <div class="navigButton">
                    <button class="button prev-btn btn-navigate-form-step" type="button" step_number="2">Prev</button>
                    <button class="button next-btn btn-navigate-form-step" type="button" step_number="4">Next </button>
                 </div>

     NOTE
    --------------------------------------------------------------------------------------------------------------
       The last section must have 
	   i. First <button> whose step_number = previous section number
	  ii. Second <button> must be used to "SUBMIT"; it should not be 'NEXT'
  ________________________________________________________________________________________________________________

  


![B-1](https://github.com/user-attachments/assets/abce2f7f-78f7-481f-876c-02dbf4205e82)

![C-1](https://github.com/user-attachments/assets/9de22ead-515f-495b-97c6-ffb2a1d3cfd7)


