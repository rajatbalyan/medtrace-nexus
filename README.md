# Medtrace Nexus

Medtrace Nexus is an innovative, blockchain-based solution designed to revolutionize the pharmaceutical supply chain by ensuring transparency, traceability, and security from raw material sourcing to the final consumer. The system integrates multiple platforms for hospitals, manufacturers, and suppliers, creating a unified network for demand-driven production, real-time inventory management, and provenance tracking.

## Features

- **Demand-Driven Manufacturing**: A platform where hospitals and stores can input their monthly drug requirements, enabling manufacturers to produce precise quantities of medicines.
- **Unified Supply Chain Management**: A common platform connecting suppliers, manufacturers, wholesalers, and retailers for streamlined purchasing, selling, and inventory management.
- **Provenance Tracking**: End-to-end tracking of raw materials, production, and distribution through blockchain, ensuring the authenticity and quality of medicines.
- **Public Record Platform**: A read-only public platform providing access to batch numbers, manufacturers, quality reports, and other vital information, enhancing transparency for consumers.

## Tech Stack

- **Frontend**: Next.js with TypeScript and Tailwind CSS for building responsive and interactive user interfaces.
- **Backend**: Node.js for server-side logic, integrated with smart contracts for blockchain functionality.
- **Blockchain**: Hyperledger Fabric for secure and scalable provenance tracking.
- **Database**: PostgreSQL for storing non-blockchain data.
- **Security**: Integration of smart contracts for automated and tamper-proof transactions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rajatbalyan/medtrace-nexus.git

2. Navigate to the project directory:
    ```bash
    cd medtrace-nexus

3. Install dependencies:
    ```bash
    npm install

4. Run the development server:
    ```bash
    npm run dev

5. Open http://localhost:3000 in your browser to see the app in action.

## Usage
1. Register as a user (Hospital, Store, Manufacturer, etc.).
2. Input your drug requirements for the upcoming month (for Hospitals/Stores).
3. Manage raw materials, production, and inventory (for Manufacturers).
4. Track and verify drug provenance via the blockchain (for all stakeholders).
5. Access public records for medicine details (for Consumers).

