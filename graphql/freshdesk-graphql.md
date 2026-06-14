# Freshdesk GraphQL

## Description

Freshdesk is a customer support and helpdesk platform developed by Freshworks. It provides a REST API (v2) as its primary programmatic interface, available at `https://yourdomain.freshdesk.com/api/v2`.

## GraphQL Availability

Freshdesk does **not** offer a native public GraphQL endpoint. All official API access is provided through the versioned REST API. There is no announced GraphQL layer, federation endpoint, or third-party GraphQL wrapper in Freshdesk's public developer documentation or GitHub organization (https://github.com/freshdesk).

## Conceptual GraphQL Schema

The schema in `freshdesk-schema.graphql` is a **conceptual data model** derived from the Freshdesk REST API surface. It is not backed by a live endpoint. It is provided for:

- Catalog enrichment and API surface documentation
- Tooling that ingests GraphQL SDL (schema linting, code generation, mock servers)
- Mapping Freshdesk REST resources to a type-safe graph model

## REST API Reference

- Docs: https://developers.freshdesk.com/api/
- Base URL: `https://yourdomain.freshdesk.com/api/v2`
- Authentication: API key (HTTP Basic, key as username, any string as password)

## Core Types Modeled

Ticket, Contact, Company, Agent, Group, Role, Product, Category, Folder, Article, Note, ConversationEntry, TimeEntry, Forum, Topic, Post, EmailConfig, BusinessHour, SLAPolicy, EscalationMatrix, Automation, CannedResponse, TicketField, ContactField, SolutionCategory, SolutionFolder, SatisfactionRating, Export, AuditLog, App, Widget, Analytics
