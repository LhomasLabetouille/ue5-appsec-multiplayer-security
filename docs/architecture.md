# Application Architecture

## Components
- UE5 Client (Player)
- UE5 Dedicated Server

## Communication
- Client communicates with server using UE5 networking (RPCs)
- Client sends gameplay-related data
- Server processes and stores authoritative state

## Trust Assumptions
Initial implementation assumes excessive trust in client-provided data.

This trust model will be analyzed and corrected later in the project.