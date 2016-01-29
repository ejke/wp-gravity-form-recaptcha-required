# wp-gravity-form-recaptcha-required
Gravity form in Workpress doesnt have recaptcha required. Bug fixed!

WIth adding this code into wp-content->themes->/theme in use/->heading.php, you can make sure that element, like recapcha, that does not have possibility to make it required in wp dashboard, will be required in the end. 

Need for this came since gravity form that had recapcha in it, did not sumbit data if recapcha wasn't filled in. Company who had the form on website, was therefore losing customers. 
