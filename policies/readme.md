# Policies Directory

This directory contains the policies that define how your organization operates and makes decisions. Unlike the formal agreements that establish relationships between members, policies provide the practical frameworks that guide day-to-day activities and governance processes.

## Understanding the Policy Domain Approach

We've designed this governance system around a foundational principle of subsidiarity - the idea that decisions should be made at the most local level possible by those who will be most affected. This is reflected in how policies are organized into separate domains, each with its own delegated authority.

The folder structure you see here isn't just organizational - it represents actual governance boundaries. Each subfolder represents a distinct policy domain with its own decision-making authority as defined in your organization's agreements. This approach balances autonomy with coordination, allowing specialized teams to govern their areas effectively while maintaining transparency across the organization.

For example, while the Metagovernance domain might establish how proposals are processed within the community governance system, the Operations domain has its own authority to determine how work is coordinated among contributors. These domains don't form a hierarchy - they represent different spheres of authority that work in parallel.

## Working with Policies

When adding or modifying policies, place them in the appropriate domain folder based on:

- Who has authority over the policy area
- Which aspect of the organization it governs
- Which circle or team will maintain it

Each policy document should include:

```
---
description: A brief description of what this policy governs
---

# Policy Title

Introduction that explains the purpose and scope...

## Policy Sections

Content organized in a logical flow...
```

The most effective policies aren't overly prescriptive - they focus on establishing clear boundaries while allowing flexibility in implementation. As you develop policies, focus on documenting your actual practices rather than aspirational ideals. Start with minimal viable governance and allow your policy documentation to evolve alongside your organization.

## Extending the Policy Structure

Your organization will likely need additional policy domains beyond those included in this template. The ideal policy structure should reflect your specific governance needs rather than following a prescribed pattern. When extending the structure:

Consider your organization's unique activities and governance requirements. Different types of organizations may need very different policy domains - a research collective might need domains for intellectual property and publishing standards, while a mutual aid community might prioritize resource distribution and member support policies.

Look for natural divisions of authority in your governance model. New policy domains should generally align with distinct areas of delegated decision-making within your organization. Creating a new domain isn't just an organizational choice - it should reflect actual governance boundaries.

When adding a new policy domain:

1. Create a new directory with both index.md and readme.md files
2. Update the main policies/index.md file to reference the new domain
3. Establish clear boundaries between the new domain and existing ones
4. Define the governance processes specific to that domain

The policy structure should evolve alongside your organization. As new activities emerge or governance needs change, be prepared to refactor your policy domains to maintain clarity and effectiveness.

## Maintaining Policy Documentation

Policies should be living documents that evolve with your organization. Regular review cycles help ensure they remain relevant and effective. When updating policies:

1. Reference the governance process defined for the specific domain
2. Use pull requests to propose and review changes
3. Maintain version history in the policy documents
4. Communicate changes to affected stakeholders

Remember that while all policies are documented in this central repository for transparency, each domain operates according to its own governance processes. The documentation structure reflects organizational boundaries but doesn't override the autonomy of each domain.