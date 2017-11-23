# CO510  Modelling Assessment:<br> UML Portfolio 2 (Class Diagrams)

## Creating a project and a UML model:

1. Work on the same Papyrus Project that you have created for the UML use case diagram.
2. Inside that same Papyrus Project, create a new Papyrus Model. The Diagram Language should be UML. 
3. Next.  Make sure that Parent Folder is [yourlogin]_TaxiCumulus. 
4. Under File name enter the name of your model name [yourlogin]_ClassDiagram. 
5. Next.  Under Root model element name enter [yourlogin]_ClassDiagram. 
6. Select Class Diagram. 
7. Finish.

## Problem Description

Consider a new app (TaxiCumulus) to be developed for the Sky Taxi Company,
with headquarters at Canterbury, that would allow its premium customers to
manage their own bookings regarding trips to and from London airports. 

With this app, the taxi company expects their premium customers to
be able to manage their own bookings instead of contacting the company.

- The customers access the app for browsing the services and the tariffs
provided by the taxi company, while premium customers access services by
using third party authentication service, such as, Facebook or Google. 

- Once authenticated, premium customers should be able to browse the diary
of the Sky Taxi Company to check for availability.

- They should be able to make bookings, amend bookings, and cancel bookings. 

- For each transaction a confirmation is sent to the customer.

- Every booking needs to be paid before a confirmation is sent.

- Amendments and cancellations require a fee to be paid.

- Payment via credit/debit card or bank transfer.

- During periods of low demand the taxi company offers discounts to its
customers for new bookings.

- the taxi company also provides is the ability for customers to share
trips to and from airports to reduce costs.

- This involves customers interacting between themselves through a forum in
order to negotiate times for their trips, the taxi company doesn't involve
itself in any negotiation.

## Consider the following

- Each premium customer needs to provide one address, but can include up
to 5 alternative addresses, and whether he/she is part of an organisation.

- The premium customer is allowed 5 bookings at most. 

- The information related to a booking should include:
  + the information related to a premium customer making the booking, 
  + a pickup and destination addresses, 
  + the date and time of the booking, 
  + the fee, 
  + and a reference number.

- the premium customer can authenticate either using
  + [X] Facebook or 
  + [X] Google, 

- the payments can be done either via:
  + [X] credit/debit card or 
  + [X] bank transfer.

- The database keeps a record of:
  + [X] premium customers, 
  + [X] bookings and 
  + organisations, 

**NOTE**<br>
You do not need to represent the operations on the attributes of the database.

- Banks are identified by:
  + name, 
  + sort code 
  + account number, 

- Credit cards are identified by:
  + card number, 
  + expire date, 
  + name and address of the owner

------------------------------------------------------------

## Assignment

### Use Case Diagram

+ In your UML use case diagram, the system should be clear
identified, together with the use cases associated with that system,
any actor that should interact with the system, and the relationships
between these.

+ For each of the use cases identified in the UML use case diagram,
description of the use cases should also be specified according to the
template provided.

### Class Diagram

+ In your UML class diagram, classes should be clear identified, together with the associations between them.

+ For each class, make sure to include:
  - key attributes 
  - operations, 
  - for each association identify:
    * main roles 
	* multiplicity

### Sequence Diagram

1. A UML sequence diagram representing a premium customer making a booking. 

- You may well assume that the premium customer has been authenticated.

- As part of this scenario consider that the premium customer browses the
diary before making the booking.

- If payment is successful premium customer should receive a confirmation.

2. A UML sequence diagram representing the premium customer cancelling
a booking.

3. A UML sequence diagram describing the use case that captures the sequence
of actions related to cancelling a booking (or similar use case in your
diagram that captures this service).

- Check whether the UML sequence diagram of the design (UML class diagram)
conforms with the UML sequence diagram of the requirements (UML use case
diagram).

- Made the required changes to the design sequence diagram to make sure it
conforms to sequence diagram of the requirements.

- This UML sequence diagram of the requirements should be included in the
Papyrus Model of the UML use case diagram ([yourlogin]_UseCaseDiagram).

- The reason for creating a new Papyrus Model for the UML sequence diagram
is that you may have to change the original UML class diagram in order to
accommodate the behaviours mentioned above.

-----------------------------------------------------------------------

## Submission

You should submit via Moodle your solution consisting of one file: an
archive file (.zip) of the whole Papyrus Project ([yourlogin]_TaxiCumulus),
which is generated by Papyrus.

The Papyrus project to be submitted should be opened and selected before
you to use the Export facility of Papyrus to generate the archive file of
the project (General/Archive File (.zip file)).  Save the generated file
elsewhere in your computer, not in the Papyrus workspace. Before uploading
the file into Moodle, check whether it works properly (for example, import
the file into another open project in Papyrus) to make sure that the contents
are not corrupted.

You may want to modify your UML in order to improve them in light of new
insights or feedback received.

**NOTE:**<br>
As a submission, for your Papyrus UML diagrams nothing else will be
accepted except for an archive (.zip) file of your Papyrus Project. 
