## Next, let's add some state to our TicketControl component. Remember that our component can have one of two possible states:

TicketList is showing and NewTicketForm is hidden;
NewTicketForm is showing and TicketList is hidden.

  constructor(props) {
    super(props);
    this.state = {
      formVisibleOnPage: false
    };
  }