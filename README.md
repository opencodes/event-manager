# event-manager
- Event
ID, Name, Desc, Location, Budget
- Expense
ID, EventID, ActivityID, ExpensePurpose, ExpenseType, PaymentType, Amount, SpentBy
- Guests
ID, Name, Contact, Address
- Activity
ID, ActivityName, ActivityDesc, DateTime, Status, ExpectedNoOfGuests, ActivityBudget
- Attendance
ID, EventID, GuestID, ActivityID, Status


## Flow
- Create Event
- Add Activity
- Add Guests
- Plan Budget
- Expense
- Attendence
- Summary
