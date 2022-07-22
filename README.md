# Anya Bot

Anya is a virtual healthcare assistant who can help you manage your appointments and map you to a suitable doctor who can satisfy your needs without any hassle.

Demo Video - 

It is a multi-lingual bot
Languages supported
1) English
2) German


----Login CREDENTIALS----

1) DOB - 2002-06-09, Last four digit of Aadhaar No. - 0906, Pincode - 500081
2) DOB - 2002-01-30, Last four digit of Aadhaar No. - 3001, Pincode - 500015
3) DOB - 2002-10-04, Last four digit of Aadhaar No. - 0410, Pincode - 501301
4) DOB - 2002-06-12, Last four digit of Aadhaar No. - 1206, Pincode - 500024


----Tech Stack----

Framework and Programming Languages used:

1) HTML
2) CSS(Bootstrap)
3) Javascript
4) JSON

----Database----

 	*MockAPI
Global Endpoints Used (method for all API are GET, POST, PUT and DELETE):

Base url-1: https://62d1aefadccad0cf176c3954.mockapi.io/anya

1) https://62d1aefadccad0cf176c3954.mockapi.io/anya/patient
2) https://62d1aefadccad0cf176c3954.mockapi.io/anya/appointment

Base url-2: https://62d6e0d649c87ff2af2f271f.mockapi.io/anya

1) https://62d6e0d649c87ff2af2f271f.mockapi.io/anya/provider
2) https://62d6e0d649c87ff2af2f271f.mockapi.io/anya/provider/..id/provider_slots

Base url-3: https://trackapi.nutritionix.com/v2/natural/nutrients

Base url-4: https://trackapi.nutritionix.com/v2/natural/exercise

----Channels deployed----

	*Website link https://anyabot.drcstudio.co.in/


----Languages supported----
1) English
2) German

The ChatBot usecases are:
1) Book an Appointment
2) Reschedule Appointments
3) View upcoming Appointments
4) Cancel Appointments
5) Viciniy (Show nearby Doctors)
6) Caloric Goal Set
7) Feedback (Like & Dislike button)

Book an Appointment

1) The VA checks the user's crendentials - DOB - Aadhaar number -  Pincode. 
2) If the crendentials match with the database, the VA returns a list of specializtions like General Physician, Cardiology, Pediatrician, Ortho and Dentist.
3) User clicks which catogory he/she want.
4) The VA ask which date and time should be schedule.
 
Reschedule Appointments

1) The VA check the user crendentials like DOB, Last four digit Aadhaar and Pincode.
2) If crendentials were matches with database the VA gives list of doctors if user clicks the VA ask which date and time should be reschedule

View upcoming Appointments

1) The VA check the user crendentials like DOB, Last four digit Aadhaar and Pincode.
2) If crendentials were matches with database the VA returns list of appointment that are scheduled.

Cancel Appointments

1) The VA check the user crendentials like DOB, Last four digit Aadhaar and Pincode.
2) If crendentials were matches with database the VA returns list of doctors user scheduled.
3) User clicks appointment would be cancel.

Vicinity

1) If user ask show nearby doctors.
2) Then VA ask Pincode for searching doctors.
3) After that user gives the pincode the VA returns nearby doctors 

Caloric Goal Set

1) If user give set caloric goal the VA ask 
	*What should you eat in morning?
	*What should you eat in afternoon?
	*What should you eat in night?
2) User give what food he/she ated 
3) VA returns the how many calories he/she need to take and returns takecare message.  
 
Default

1) If user ask help then bot returns list of task 
 
Feedback

1) Bot returns like and dislike button



----User Utterence for Book an Appointment----

I would like to see a doctor for my child.
I would like to book an appointment on 27/07/2022 at 9:00
I would like to see a doctor tomorrow
I would like to consult a physician on 24/10/2022

----User Utterence for Reschedule Appointments----

Can you reschedule my appointment to 25/07/2022
Is it possible to reschedule my appointment?
I wanna reschedule my appointment
I'd like to reschedule my appointment

----User Utterence for View upcoming Appointments----

I'd like to view my consultations.
View upcoming consultations
List out my current appointments
Which doctor will I be seeing for my next appointment?

----User Utterence for Cancel Appointments----

Let me call off my appt
Anya, please unbook my appointment
Anya, please help me to cancel the appointment
It is profoundly far-fetched that I will go for my appointment

----User Utterence for Vicinity----

Doctors around my residence
Doctor near my sector
Are there any doctors available near me?
Is there any cardiologist in my locale?
Are there any doctors in my precinct ?

----User Utterence for Caloric Goal Set----

Should I eat more than my current diet?
How much should I eat ?
How many calories did I burn today?
Is my diet working?
Am I taking the right amount of food?

----User Utterence for Feedback----

Bye bye
Nothing else
No Thanks

Knowledge Graph

It is only supported in English and German due to the Knowledge graph limit in publishing

1) HealthFAQ

	User: How much salt should I be eating? 
	VA: The recommended dose of sodium for a healthy diet is less than 4000 mg.


2) Baby

	User: What does my baby’s poop color say about his health? 
	VA: *Black*
		......................................

3) Nutrition

	User: How can I eat a more nutritious diet?
	VA: We admit it: We could all do better when selecting what to eat. It’s far too easy to fall for a “fad diet” only to find yourself back to square one.Let our experts help you.Our primary care doctors have extensive training in nutrition and helping you make healthy choices. Just ask one of them to help you create an eating plan. We’ll also provide follow-up appointments to be sure you have the assistance you need to stay the course.

4) General Physician

	User: How does my family history affect my health?
	IVA: We’re glad you asked that!If you have a close [family member]...........

5) Ortho

	User: What is Orthopaedics?
	VA: Orthopedics is a medical specialty focusing on the diagnosis, correction, prevention and treatment of patients with disorders of the bones, joints, muscles, ligaments, tendons and nerves. These parts of the body make up the musculoskeletal system.

6) Cardio

	User: Do I need a referral from my physician to be seen by a cardiac specialist?
	VA: Usually, cardiac surgery patients are referred by a general or family physician.

7) Dentist

	User: Are sweets and ice really bad for my teeth?
	VA: Yes, sweets and foods with acid, like candy and soda, could stick to teeth and lead to cavities.


Sentiment management

1) If the user becomes angry, the bot will return an apology message.
