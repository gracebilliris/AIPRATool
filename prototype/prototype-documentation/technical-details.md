# Technical Details of AIQPRA Tool Prototype

This document provides an overview of the technical implementation of the AI and Quantum Privacy Risk Assessment (AIQPRA) Tool prototype.

## Prototype Platform

-   The prototype is developed using **Tally.so**, a no-code/low-code form builder platform.
-   Tally.so enables quick deployment and easy access through web forms, suitable for initial validation and user engagement.

## Architecture and Features

-   The prototype consists of a **static questionnaire** divided into key privacy risk domains.
-   Users manually select answers; scoring is computed within the form based on predefined logic.
-   The tool provides a summary risk score after submission to highlight areas of potential privacy concern.

## Limitations

-   **Automation:** The prototype does not support automated data collection or integration with external systems.
-   **Scalability:** Designed for small-scale assessments and early-stage validation only.
-   **Interactivity:** Limited dynamic or adaptive question flows; all users see the same fixed set of questions.
-   **Data Storage:** Responses are managed by Tally.so’s platform and are not directly controlled by the research team.

## Future Technical Directions

-   Transitioning to a **modular, agent-based system architecture** to enable:

    -   Automated data ingestion and real-time privacy risk monitoring
    -   AI-powered natural language understanding and explanation generation
    -   Integration with distributed ledger technologies for audit trails
    -   Implementation of quantum-resistant cryptographic methods

-   Development planned using cloud platforms (e.g., Google Cloud, Azure) and AI APIs (e.g., OpenAI, Google) for enhanced capabilities.

## Data Privacy and Security

-   Prototype data collection follows ethical guidelines; no sensitive or identifiable information is stored beyond the Tally platform.
-   Future versions will incorporate robust security and privacy-preserving mechanisms aligned with regulatory requirements.

For questions or technical support, please contact the project team at [13925894@student.uts.edu.au].
