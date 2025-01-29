The Person class could have fields:

id (Integer) - user ID
firstName (String) - user’s first name
lastName (String) - user’s last name
email (String) - user’s email/username
password (String) - user’s password

The Person class should also have getters for all fields.
The Person class should have setters for all fields except id, which should be auto-generated.

The Person class in the application will be to connect the user/person to the events they are attending.
Person would have a many-to-many relationship with Event, as many people can attend multiple/many events.
Updates could be made to the Person class to create guest lists for the events that are being attended. This would add additional functionality and uses to the application.
