- 👋 Hi, I’m @aghrib
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on .../// ==UserScript==
// @name         c BLS individuel mohamed
// @namespace    http://tampermonkey.net/smith.hun
// @version      1.0
// @description  try to take over the world!
// @author       smith.hunt
// @require      https://cameroon.blsspainvisa.com/french/js/jquery-1.11.0.min.js
// @include      https://*.blsspainvisa.com/*/appointment.php
// @include      https://*.blsspainvisa.com/appointment.php
// @grant        none
// ==/UserScript==

var submit = document.getElementsByClassName('btn secondry-btn')[0];
if (submit != null) { submit.click();}

(function() {'use strict'; var reCapTimer = setInterval(data, 1000);})();
function data() {if(document.getElementById("recaptcha") === null) { document.getElementsByName('mission_selected')[0].id = 'recaptcha'; document.getElementsByName('mission_selected')[0].name = 'g-recaptcha-response'; document.getElementById('phone').id = "phone1";}
var R = document.getElementById('g-recaptcha-response').value; var handle = setInterval(function (){ document.getElementById('g-recaptcha-response').value; }, 1000); if (R != null) {document.getElementById("recaptcha").value = R; }}

var Name = ["1 ouzina", "2 ammari", "3 nafiaa", "4 morjane", "5 hajji", "6 el behri", "7 OUAHID", "8 el azzouzi ",];
var data1 = function () {
var firstName = "ouzina"; var lastName = "fatima zahra";
var birth = "1991-03-24"; var passNumber = "nm8214785";
var issueDate = "2021-09-01"; var expiryDate = "2026-09-01"; var issuePlace = "casa";
document.getElementById('first_name').value = firstName;document.getElementById('last_name').value = lastName;document.getElementById('passport_no').value = passNumber;$('#dateOfBirth').val(birth);$('#pptIssueDate').val(issueDate);$('#pptExpiryDate').val(expiryDate);document.getElementById('pptIssuePalace').value = issuePlace;document.getElementById('VisaTypeId').selectedIndex = 1;var indexMax = document.getElementById('app_time').length - 1;var ei = Math.floor((Math.random() * indexMax) + 0);document.getElementById('app_time').selectedIndex = ei;$('#terms').prop('checked', true);}


var data2 = function () {
var firstName ="ammari" ; var lastName = "najat";
var birth = "1972-09-02"; var passNumber = "ru9473979";
var issueDate = "2021-08-02"; var expiryDate = "2026-08-02"; var issuePlace = "mohammedia";
document.getElementById('first_name').value = firstName;document.getElementById('last_name').value = lastName;document.getElementById('passport_no').value = passNumber;$('#dateOfBirth').val(birth);$('#pptIssueDate').val(issueDate);$('#pptExpiryDate').val(expiryDate);document.getElementById('pptIssuePalace').value = issuePlace;document.getElementById('VisaTypeId').selectedIndex = 1;var indexMax = document.getElementById('app_time').length - 1;var ei = Math.floor((Math.random() * indexMax) + 0);document.getElementById('app_time').selectedIndex = ei;$('#terms').prop('checked', true);}

var data3= function () {
var firstName = "nafiaa"; var lastName = "amal-elkhir";
var birth = "1983-04-20"; var passNumber = "nt0589461";
var issueDate = "2019-10-03"; var expiryDate = "2024-10-03"; var issuePlace = "beni mellal";
document.getElementById('first_name').value = firstName;document.getElementById('last_name').value = lastName;document.getElementById('passport_no').value = passNumber;$('#dateOfBirth').val(birth);$('#pptIssueDate').val(issueDate);$('#pptExpiryDate').val(expiryDate);document.getElementById('pptIssuePalace').value = issuePlace;document.getElementById('VisaTypeId').selectedIndex = 1;var indexMax = document.getElementById('app_time').length - 1;var ei = Math.floor((Math.random() * indexMax) + 0);document.getElementById('app_time').selectedIndex = ei;$('#terms').prop('checked', true);}

var data4 = function () {
var firstName = "morjane"; var lastName = "ayoub";
var birth = "1989-07-18"; var passNumber = "pa5605273";
var issueDate = "2019-10-15"; var expiryDate = "2024-10-15"; var issuePlace = "berrechid";
document.getElementById('first_name').value = firstName;document.getElementById('last_name').value = lastName;document.getElementById('passport_no').value = passNumber;$('#dateOfBirth').val(birth);$('#pptIssueDate').val(issueDate);$('#pptExpiryDate').val(expiryDate);document.getElementById('pptIssuePalace').value = issuePlace;document.getElementById('VisaTypeId').selectedIndex = 1;var indexMax = document.getElementById('app_time').length - 1;var ei = Math.floor((Math.random() * indexMax) + 0);document.getElementById('app_time').selectedIndex = ei;$('#terms').prop('checked', true);}

var data5 = function () {
var firstName = "hajji"; var lastName = "el houcine";
var birth = "1992-12-19"; var passNumber = "fw8278192";
var issueDate = "2020-10-23"; var expiryDate = "2025-10-23"; var issuePlace = "tinghir";
document.getElementById('first_name').value = firstName;document.getElementById('last_name').value = lastName;document.getElementById('passport_no').value = passNumber;$('#dateOfBirth').val(birth);$('#pptIssueDate').val(issueDate);$('#pptExpiryDate').val(expiryDate);document.getElementById('pptIssuePalace').value = issuePlace;document.getElementById('VisaTypeId').selectedIndex = 1;var indexMax = document.getElementById('app_time').length - 1;var ei = Math.floor((Math.random() * indexMax) + 0);document.getElementById('app_time').selectedIndex = ei;$('#terms').prop('checked', true);}

var data6 = function () {
var firstName = "el behri"; var lastName = "soufyane";
var birth = "1998-12-06"; var passNumber = "ob2545680";
var issueDate = "2020-01-08"; var expiryDate = "2025-01-08"; var issuePlace = "tinghir";
document.getElementById('first_name').value = firstName;document.getElementById('last_name').value = lastName;document.getElementById('passport_no').value = passNumber;$('#dateOfBirth').val(birth);$('#pptIssueDate').val(issueDate);$('#pptExpiryDate').val(expiryDate);document.getElementById('pptIssuePalace').value = issuePlace;document.getElementById('VisaTypeId').selectedIndex = 1;var indexMax = document.getElementById('app_time').length - 1;var ei = Math.floor((Math.random() * indexMax) + 0);document.getElementById('app_time').selectedIndex = ei;$('#terms').prop('checked', true);}

var data7 = function () {
var firstName = "ouahid"; var lastName = "amine";
var birth = "1993-06-30"; var passNumber = "jv5031760";
var issueDate = "2019-11-15"; var expiryDate = "2024-11-15"; var issuePlace = "casablanca";
document.getElementById('first_name').value = firstName;document.getElementById('last_name').value = lastName;document.getElementById('passport_no').value = passNumber;$('#dateOfBirth').val(birth);$('#pptIssueDate').val(issueDate);$('#pptExpiryDate').val(expiryDate);document.getElementById('pptIssuePalace').value = issuePlace;document.getElementById('VisaTypeId').selectedIndex = 1;var indexMax = document.getElementById('app_time').length - 1;var ei = Math.floor((Math.random() * indexMax) + 0);document.getElementById('app_time').selectedIndex = ei;$('#terms').prop('checked', true);}

var data8 = function () {
var firstName = "el azzouzi"; var lastName = "rachid";
var birth = "1992-01-01"; var passNumber = "mr9419648";
var issueDate = "2021-05-21"; var expiryDate = "2026-05-21"; var issuePlace = "beni mellal";
document.getElementById('first_name').value = firstName;document.getElementById('last_name').value = lastName;document.getElementById('passport_no').value = passNumber;$('#dateOfBirth').val(birth);$('#pptIssueDate').val(issueDate);$('#pptExpiryDate').val(expiryDate);document.getElementById('pptIssuePalace').value = issuePlace;document.getElementById('VisaTypeId').selectedIndex = 1;var indexMax = document.getElementById('app_time').length - 1;var ei = Math.floor((Math.random() * indexMax) + 0);document.getElementById('app_time').selectedIndex = ei;$('#terms').prop('checked', true);}

var j = 1;
var i;
for (i = 0; i <= 7; i++){
var button = document.createElement('input');
button.value = 'data name' +j;
button.id = 'formulaire' +j;
//button.onclick = data2;
document.getElementsByTagName('tbody')[0].parentNode.insertBefore(button, document.getElementsByTagName('tbody')[0]);
document.getElementById('formulaire' +j).style="cursor: pointer; border:1,5px solid #000;float: center; font-size: 12px; padding: 6px; width: 80px; margin-bottom: 4px;"


//button.addEventListener('click', 'data' +j);
document.getElementById('formulaire' +j).value = Name[i];
j++;
}
document.getElementById('formulaire1').onclick = data1;
document.getElementById('formulaire2').onclick = data2;
document.getElementById('formulaire3').onclick = data3;
document.getElementById('formulaire4').onclick = data4;
document.getElementById('formulaire5').onclick = data5;
document.getElementById('formulaire6').onclick = data6;
document.getElementById('formulaire7').onclick = data7;
document.getElementById('formulaire8').onclick = data8;
document.getElementById('formulaire9').onclick = data9;




var appdateoff = function () {
var element = document.getElementById('reload').value;
if (element === 'ON') {document.getElementById('app_date').onchange="this.form.submit()"; document.getElementById('reload').value = "OFF"; document.getElementById('reload').style.background = "red"; document.getElementById('app_date').readOnly = false;}
else {document.getElementById('app_date').form.submit();showLoader();}
setInterval(function (){document.getElementById('app_date_hidden').value = document.getElementById('app_date').value ; }, 1000);}
var button2 = document.createElement('input');
button2.value = 'ON';
button2.id = 'reload';
document.getElementById('app_date').parentNode.insertBefore(button2, document.getElementById('app_date').nextsibling);
document.getElementById('reload').style="cursor: pointer;float: center; font-size: 12px; padding: 6px; width: 50px; text-align: center; background: green"
document.getElementById('reload').onclick = appdateoff;
- 📫 How to reach me ...

<!---
aghrib/aghrib is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
