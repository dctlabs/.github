# DroneCTL

**A software foundation for connected robots.**

DroneCTL brings together an embedded runtime, shared infrastructure and a typed
SDK to build applications for drones and other robotic systems. Its goal is to
let developers work with robots, missions and data through a coherent API,
while keeping hardware and transport details behind clear interfaces.

## From the robot to the application

The embedded runtime connects robot hardware to common services. Adapters keep
autopilot and equipment specifics separate from the shared foundation, leaving
room for navigation, perception and autonomous behavior.

The infrastructure coordinates access, live observations and mission data.
A mission provides a durable context for robot participation, recordings and
collected files; it is distinct from a physical flight or a browser session.
Administration tools provide a separate space for diagnostics and maintenance.

## Built for developers and operators

The TypeScript SDK is intended for browser applications, backend services and
headless programs, with optional React bindings. Applications use domain objects
and typed operations rather than handling wire protocols or device-specific
messages themselves.

Identity, permissions, control authority and the timing of observations are
part of the foundation. Shared contracts describe common capabilities;
explicit extensions represent what is specific to a robot or its equipment.

## Project status

DroneCTL is under active development. The current work focuses on the software
foundation and an integrated simulation environment. Autonomous navigation and
operational readiness remain separate development and validation stages.

Source repositories are currently private.

[Contact the team](mailto:contact@dronectl.dev)
