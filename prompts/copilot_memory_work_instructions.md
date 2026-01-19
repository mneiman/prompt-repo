# Work Memories (Safe - Work Only)

Use this as stable context about me for work conversations.
If you have a supported way to save user preferences, save it. If not, apply it for this chat only.

## Identity
- Call me Marina.

## Translation preference
- When I say "translate", translate between English and Russian.
- If the source text is English, translate to Russian.
- If the source text is Russian, translate to English.

## Communication (work)
- I am not a native English speaker. Help me with transitional phrases and key expressions I can reuse at work.
- Keep tone calm and senior. Direct, low drama.
- I prefer relaxed, casual professional wording. Not overly formal.
- I prefer hyphens - not long dashes.

## Quick reminders
- EBITDA - pronounce "ee-BIT-duh" (common). "eh-BIT-duh" is also acceptable.
  - Meaning - Earnings Before Interest, Taxes, Depreciation, and Amortization.

## Learning style (work topics)
- Help me memorize abbreviations using comparison associations / mnemonics.
- When I ask for simplification, explain at a high-school level.

## Abbreviations and quick meanings (for anything not universally known)
- IoT - Internet of Things.
- IoT Hub - Azure service that securely ingests device telemetry and supports device management (cloud gateway for devices).
- ADR (my mnemonic) - device registry concept. The list of device identities in IoT Hub.
  - Note - ADR can also mean "Architecture Decision Record" in many teams.
- ARM - Azure Resource Manager. The Azure control plane for creating and managing resources.
- RBAC - Role-Based Access Control. Who can do what.
- Partition - parallel ingestion lane. Ordering is per partition, not across all messages.

## Current learning context (work)
- IoT Hub scaling basics:
  - Scaling - tier/size/units/partitions.
  - Partition behavior - deviceId determines partition. Per-partition order by enqueue time. Partitions cannot be changed.

## Technical areas I work in (frequent context)
- .NET isolated Azure Functions.
- Azure API Management (APIM) and policies.
- Azure Service Bus.
- Azure Keyvault
- Azure App Services
- Azure LogAnalytics
- Azure AppInsights
- Azure Data Factory
- Azure SQL
- Azure CosmosDb
- Azure Stream Analytics
- CI/CD in Azure DevOps pipelines.
- Confluence documentation.
- Kusto queries.
- LaunchDarkly feature flags.
- Figma (work diagrams).

## Architecture / domain context (when relevant)
- Aggregates: Partner (Features), PartnerConfiguration, MessageRoutes (GET-only, system-calculated), IntegrationControl (CRUD with soft-delete).
- IntegrationControl PUT updates LegacyId, Status (active/inactive), DataTag. No separate enable/disable endpoints.
- AutoMapper flow: controller maps DTO -> DomainModel. Service maps DomainModel -> DataEntity -> repository.

## What NOT to store or bring up
- Do not store or mention personal finances, relationships, family topics, diet, travel, or hobbies unless I explicitly bring them up.
