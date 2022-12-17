# Using the Tradelens Actionable Doc Flow API #

Tradelens is an actionable document flow API that aims to streamline the transportation process by automating the creation and management of documents. This tool is specifically designed for programmers, providing a range of functions and features to help them efficiently handle transportation documents. Whether you're a software developer working on logistics-related projects or simply looking for a more efficient way to handle documents, Tradelens is worth considering. Its focus on automating document flow makes it a valuable resource for anyone involved in transportation.


[Actionable Doc Flow API](https://www.worldindata.com/api/Tradelens-actionable-doc-flow-api)

Worldindata's data marketplace offers a wide range of third party APIs that are designed to make data more accessible and user-friendly. Whether you're a developer working on a new project or simply looking for a quick way to access information, Worldindata's APIs offer a convenient solution. With a focus on usability and simplicity, these APIs make it easy to access and work with data, helping you get the insights you need to make informed decisions.


## Industry, Sectors, and Consumers for the API ##

**Industry and Sectors**
- transportation
- automation
- logistics
- import
- export
- trade

**Client Types**
- transportation and logistics companies
- importers
- exporters
- international traders




## Objects, JSON output and Parameters of the API ##
The POST /api/v1/actionableFlows/search endpoint allows users to search for specific actionable flows within the consignment automation API.

**filter parameters**
- flowType
- tradeObjectIdentifiers
- includeInactive
- flowState
- tradeObjectIdentifiers
- includeActionAuditList
- limit
- from

```
{
  "flowType": "eBOLFlow",
  "flowState": "ISSUED",
  "tradeObjectIdentifiers": [
    {
      "consignment": {
        "billOfLadingNumber": "BOL8331939",
        "carrierBookingNumber": "CBN456789",
        "consignmentId": "CID8331939"
      },
      "shipment": {
        "references": [
          {
            "reference": "myReference",
            "type": "proformaInvoiceNumber"
          }
        ],
        "shipmentId": "sdkjf68-fdsjf0-jsddj-dskjk"
      },
      "transportEquipment": {
        "billOfLadingNumber": "BOL8331939",
        "carrierBookingNumber": "CBN456789",
        "equipmentNumber": "ACME1122334",
        "transportEquipmentId": "TEID8331939"
      }
    }
  ],
  "includeActionAuditList": false
}

```

**Objects**
- flowType
- flowState
- tradeObjectIdentifiers
- consignment
- billOfLadingNumber
- carrierBookingNumber
- consignmentId
- shipment
- references
- references
- type
- shipmentId
- transportEquipment
- billOfLadingNumber
- carrierBookingNumber
- equipmentNumber
- transportEquipmentId
- includeActionAuditList

## SDK of the API ##
The Tradelens transportation documents automation data is available through Software Development Kits in various programming languages, including JAVA, Python, PHP, Ruby, and JavaScript. These kits make it easy for developers to work with the data and integrate it into their own projects.

### Disclaimer of responsibility ###
Worldindata is a data marketplace that aims to make the vast amount of data available in the world more accessible and user-friendly. We do not own the data ourselves, but rather work to connect developers with data providers. Our team is made up of big fans of the actionable doc flow API and Tradelens, and we believe in the power of data to drive innovation and progress. However, we cannot be held responsible for the accuracy or reliability of the data, and users should always verify any information they find through our platform before using it for any purpose.


[Worldindata](https://www.worldindata.com)
