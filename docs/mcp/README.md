# Master Control Program (MCP)

Many of the video games developed by Epic Games use an MCP (Master Control Program).

An MCP is a middleware system that acts as a centralized backend framework for managing core game services, not just for a single game but across multiple titles, especially those utilizing shared infrastructure. It serves as an orchestration platform, enabling communication, data flow, and connectivity between various services. This allows the frontend of a game to seamlessly retrieve or submit data through multiple endpoints, ensuring smooth functionality and interaction.

------

## Examples of Epic Games' MCP Usage

-  **Epic Online Services (EOS):** Epic Games leverages MCP to manage shared features across its games, such as Fortnite and Unreal Tournament, providing a unified backend solution.
-  **Gearbox Backend for Borderlands 3:** While not directly under Epic Games, Gearbox's games utilize an MCP-like backend system for features like cross-platform saves, matchmaking, and cooperative gameplay, integrating shared functionality effectively.

------

## What's Included in This Directory?

The MCP backend includes several endpoint functionalities, documented in the `profile` directory of this folder. Below are common features provided by Fortnite's MCP:

-  **Account Management:** Manages user authentication, account creation, and cross-platform linking.
-  **Leaderboards and Account Stats:** Tracks player statistics, achievements, and global leaderboards.
-  **Purchasing and Monetization:** Integrates with payment systems to handle in-game purchases and microtransactions.
-  **Cross-Game Communication:** Enables unified chat systems, friend lists, and other interconnectivity features across games in Epic's ecosystem.
-  **Event Management:** Handles live events, such as tournaments, seasonal updates, and time-limited challenges.

For more information on utilizing these features, refer to the [Operation Request](mcp/profile/operation_request.md) page.
