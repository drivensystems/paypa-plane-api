# A guide to Paypa Plane's Public APIs

This repository contains:

1. Explanations around Paypa Plane's Public APIs
1. An overview of Paypa Plane's data objects/models behind the APIs
1. Sample Postman collections to help get started with Paypa Plane's Public APIs

## Paypa Plane's Public APIs

The APIs provide a way to interact with Paypa Plane's systems by viewing and modifying the following items:

1. Event subscriptions

   The webhooks of external systems that will receive notifications about certain events.

1. Payment requests

   The central item that holds information about a customer's agreement and payment arrangement.

1. Customers

   The end users engaged with a payment request.

## Data Objects/Models

There are two key data objects/models to consider when interacting with Paypa Plane's systems:

1. Customers

   The customer object holds details about a person - the one agreeing to a payment request from a merchant. This includes:

   * Names
   * Addresses
   * Phone numbers

1. Payment requests

   The payment request object holds details about the payment arangement, agreement details and terms, payment methods and other related details. This includes:

   * Payment schedule and terms (i.e. amount, duration, frequency, etc)
   * Chosen payment method (i.e. VISA, Mastercard, bank transfer, etc)

## Postman Collections

To assist in getting started with Paypa Plane's Public APIs, a [Postman](https://www.getpostman.com/) collection of is available to demonstrate how the various API calls are made and the required payloads needed as a minimum to execute the calls.