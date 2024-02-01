# MyTicketToken README

## Overview

**MyTicketToken** is a Solidity smart contract that adheres to the ERC-20 standard and utilizes the OpenZeppelin library. This contract functions as a tokenized ticket system, allowing the minting, burning, and transfer of tickets. The contract is exclusively owned by a designated entity referred to as the "ticketIssuer."

## Features

- **Ticket Minting**: The `mintTickets` function enables the ticketIssuer to create new tickets, each associated with a specified ticket price.

- **Ticket Burning**: Users have the ability to burn their tickets through the `burnTickets` function, thereby reducing the overall ticket supply.

- **Ticket Transfer**: The standard ERC-20 `transfer` function facilitates the transfer of tickets from one address to another.

## Usage

### Contract Deployment

1. Deploy the contract with the desired token name and symbol.

### Minting Tickets

2. The `mintTickets` function is reserved for the ticketIssuer to generate new tickets. This action can only be performed by the owner of the contract.

### Burning Tickets

3. Users can burn their tickets using the `burnTickets` function, specifying the ticket price they wish to burn.

### Transferring Tickets

4. Ticket transfers between addresses are achieved through the standard ERC-20 `transfer` function.

## Events

The contract emits events to enhance transparency:

- **TicketsMinted**: Triggered when new tickets are minted.
  
- **TicketsBurned**: Fired when tickets are burned.
  
- **TicketsTransferred**: Standard ERC-20 transfer event.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Deployment Example

1. Deploy the MyTicketToken contract.

2. Mint an initial supply of tickets, for instance, 100 tickets.

## Author 
Name:kantesh 

Gmail: Kanteshmh11@gmail.com
