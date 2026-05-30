# DukaRes Architecture

## Core Architecture

DukaRes is built around a real inventory model.

```text
PROPERTY
    ↓
ROOM
    ↓
UNIT
    ↓
CALENDAR
```

## Definitions

### Property

A hotel, apartment building, villa, resort, guesthouse, or any accommodation business.

### Room

A room type.

Examples:

- Double Room
- Deluxe Room
- Suite
- Family Room

### Unit

A real physical room.

Examples:

- Room 101
- Room 102
- Room 103

### Calendar

Availability is managed at unit level.

Every booking is connected to real inventory.

## Design Principles

- Real Availability
- Real Inventory
- Scalability
- Multi-Property Support
- Multi-Tenant Support

## Important

This document describes the public architecture only.

Internal services, booking logic, algorithms, availability engine, and business logic are not included in this repository.
