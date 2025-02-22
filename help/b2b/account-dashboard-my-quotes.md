---
title: '[!UICONTROL My Quotes]'
description: Learn about the customer experience for quotes, which is available in their account dashboard.
exl-id: 137f0a99-8f24-4838-b54b-b0ef2c39a32a
---
# [!UICONTROL My Quotes]

If quotes are enabled, the _[!UICONTROL My Quotes]_ section of the account dashboard lists all quotes submitted by the customer. Depending on their permissions, only buyers who make purchases on behalf of a company can submit requests to negotiate the price of a purchase.

![My Quotes](./assets/account-dashboard-my-quotes.png)<!-- zoom -->

The buyer begins the process by [submitting a request](quote-request.md) for a quote from the shopping cart. Email is exchanged between the buyer and seller during the [negotiation process](quote-price-negotiation.md). For the buyer, the [!UICONTROL My Quotes] page is the focal point for all communication between buyer and seller during the negotiation process. A buyer who accepts the negotiated price offered by the seller can proceed directly to checkout from the quote. Additional discounts cannot be added to the negotiated quote.

## Show quotes

With the required [permissions for their role](account-company-roles-permissions.md), customers associated with a company account can see quotes requested by [subordinate users](account-company-structure.md). Company administrators can see all quotes for the company account.

1. Customer logs in to the storefront.

1. Clicks **[!UICONTROL My Quotes]**.

1. To see all the quotes that they have created, clicks the **[!UICONTROL Show My Quotes]** link (displayed only for the company administrator or account with subordinate users).

1. To see all the quotes of all company users, clicks **[!UICONTROL Show All Quotes]**.

## View a quote

1. Customer logs in to their account.

1. In the left panel, chooses **[!UICONTROL My Quotes]**.

1. Finds the quote in the list and clicks **[!UICONTROL View]** in the _[!UICONTROL Action]_ column.

## Print a quote

1. In the open quote to the right of the _[!UICONTROL Items Quoted]_ section, clicks **[!UICONTROL Print]**.

1. Verifies the **[!UICONTROL Destination]** as either a printer or PDF.

1. Clicks **[!UICONTROL Print]**.

## Cancel a quote request

1. In the open quote just above the Items Quoted section, clicks **[!UICONTROL Close quote]**.

   The request is canceled, and the quote status changes to `Closed`. The closed quote remains in your list of quotes, and remains listed in the _[!UICONTROL Quotes]_ grid from the Admin.

1. To remove the canceled quote from the list of quotes, clicks **[!UICONTROL Delete]**.

1. When prompted to confirm, clicks **[!UICONTROL OK]**.

   The closed quote is removed from their list of quotes. However, it remains listed on the _[!UICONTROL Quotes]_ grid in the Admin, with the `Closed` status.

## Column descriptions

|Column|Description|
|--- |--- |
|[!UICONTROL Quote Name]|The name assigned to the quote request by the buyer.|
|[!UICONTROL Created]|The date the quote request was first submitted.|
|[!UICONTROL Created By]|The first and last name of the buyer who submitted the quote request.|
|[!UICONTROL Status]|Indicates the status of the quote. The status of a quote can be changed only by action on the part of either the buyer or seller. <br/>**[!UICONTROL Submitted]** - The buyer’s request for a quote hasn’t yet been opened by the seller. While in this state, the buyer can still modify the request for a quote. Available actions: `View` / `Close` / `Edit Quantity` / `Delete SKU` / `Add Comments` / `Edit Shipping Address` <br/>**[!UICONTROL Pending]** - The seller has opened the request and is in the process of reviewing it and preparing a response. Available actions: `View` / `Close` <br/>**[!UICONTROL Updated]** - The seller has sent a response to the buyer, and the _[!UICONTROL Proceed to Checkout]_ button is enabled. While in this state, the buyer can continue to modify the quote. Available actions: `View` / `Send for Review` / `Proceed to Checkout` / `Delete Quote` / `Close` / `Edit Quantity` / `Delete SKU` / `Add comments` / `Edit Shipping Address` <br/>**[!UICONTROL Open]** - The buyer is still updating the quote, and the _[!UICONTROL Proceed to Checkout]_ button is disabled. Available actions: `View` / `Send for Review` / `Delete Quote` / `Edit quantity` / `Delete SKU` / `Add Comments` / `Edit Shipping Address` <br/>**[!UICONTROL Ordered]** - The buyer has submitted an order based on the negotiated quote. The quote is locked, and cannot be edited. Available action: View <br/>**[!UICONTROL Closed]** - The buyer has ended the negotiation and cancels the quote. The quote is locked, and cannot be edited by either buyer or seller. Available actions: `View` / `Delete` <br/>**[!UICONTROL Declined]** - The seller has declined the request for a quote, or to make a proposed change during the negotiation process. A quote can be declined at any stage of the workflow. Any custom pricing is removed from the quote. The buyer can continue editing the quote and resubmit it, or make the purchase with standard catalog prices. Available actions: `View` / `Send for Review` / `Delete Quote` / `Edit Quantity` / `Delete SKU` / `Add Comments` / `Edit Shipping Address` <br/>**[!UICONTROL Expired]** - The lifetime of the quote has expired. Any proposed prices are reset. The buyer can either complete the purchase based on standard catalog prices, or initiate another round of negotiations. Available actions: `View` / `Send for Review` / `Delete Quote` / `Edit Quantity` / `Delete SKU` / `Add Comments` / `Edit Shipping Address`|

{style="table-layout:auto"}
