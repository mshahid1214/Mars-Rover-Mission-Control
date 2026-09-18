# Mission ‘Analyze the Engineering Note’
## Functional Requirements 
### FR-01 Send movement commands to the rover.
The system shall allow authenticated Mission Control operators to send movement commands to the rover.
### FR-02 Receive and execute valid commands.
The rover shall receive and execute valid commands sent by Mission Control.
### FR-03 Receive and execute valid commands.
The rover shall report its current position to Mission Control.
### FR-04 Report rover position.
The rover shall report its battery level, temperature, and communication status.
### FR-05 Report battery, temperature, and communication status.
The system shall authenticate Mission Control operators before allowing them to issue commands.
### FR-06 Authenticate Mission Control operators.
The system shall reject invalid or unauthorized commands.
## Non-Functional Requirements
### NFR1 – Performance	
Command processing should normally complete within 5 seconds after a command is received by the rover.
### NFR2 – Security
Only authenticated Mission Control operators shall be permitted to issue commands.
### NFR3 – Reliability	
The system shall continue operating despite temporary communication interruptions.
### NFR4 – Scalability	
The system should support communication with multiple rovers simultaneously.

