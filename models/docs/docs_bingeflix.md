# Bingeflix Docs
This file contains doumentation for Bingeflix data sources.

## Users
This section contains documentation from the Bingeflix Users table.

{% docs bingeflix_column_user_id %}
The unique identifier of the Bingeflix user. A user is created when user sucessfully signs up with email.
{% enddocs %}

{% docs bingeflix_column_created_at %}
The timestamp of when a user hits sign up with valid email. 
{% enddocs %}
        
{% docs bingeflix_column_phone_number %}
The phone number of user. 
{% enddocs %}


{% docs bingeflix_column_deleted_at %}
When the user's account was deleted. The value is NULL if the account has not been deleted.
{% enddocs %}

{% docs bingeflix_column_username %}
The username for login to Bingeflix.
{% enddocs %}

{% docs bingeflix_column_name %}
The name of the user.
{% enddocs %}

{% docs bingeflix_column_sex %}
The user's sex at birth.
{% enddocs %}

{% docs bingeflix_column_email %}
The user's email address.
{% enddocs %}

{% docs bingeflix_column_birthdate %}
The user's birthdate.
{% enddocs %}

{% docs bingeflix_column_region %}
Where the user resides (i.e. the state or province).
{% enddocs %}

{% docs bingeflix_column_country %}
Where the user resides.
{% enddocs %}