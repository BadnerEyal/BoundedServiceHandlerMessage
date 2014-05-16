BoundedServiceHandlerMessage
============================

BoundedServiceHandlerMessage. 

The difference between BoundedServiceHandlerPost to BoundedServiceHandlerMessage 

BoundedServiceHandlerMessage 

We needs to make us Handler knows how to read the message number 
Sent to us by it to do something 

BoundedServiceHandlerPost 
We actually do operations through the tube 
Proper use in my opinion is to use the messages and post 
Possible that we do not know if anyone on the service 
Really wish we'd something in him that is why 
So that the code would be a generic and simple utility notifies the situation 
And those who read the service decides what to do by the message.

BoundedServiceHandlerMessage.

ההבדל בין BoundedServiceHandlerPost ל BoundedServiceHandlerMessage

BoundedServiceHandlerMessage
אנו צרכים להכין לנו הנדלר שיודע לקרוא את מספר ההודעה
שנשלח אלינו ולפי זה לעשות משהו

BoundedServiceHandlerPost 
אנו בעצם עושים פעולות דרך הצינור
השימוש הנכון לפי דעתי זה להשתמש בהודעות ולא בפוסט
כמה שאפשר כי אנו לא יודעים אם מי שמחובר לשירות
באמת רוצה שנפעיל אצלו משהו לכן
כדי שהקוד יהיה קוד גנרי והשירות פשוט יודיע מה המצב
ומי שקרא לשירות יחליט מה לעשות לפי ההודעה.
