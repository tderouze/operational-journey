---
{"dg-publish":true,"permalink":"/aveva-pi-system/aveva-pi-system-for-batches/","tags":["AssetFramework","EventFrames","PISystem"]}
---

The AVEVA PI System is an infrastructure designed to drive business impacts across an enterprise, particularly in the batch process industry. It uses technologies such as new sensor technology and remote and mobile data access.

## Key Features of the AVEVA PI System for Batches:

- **Asset Framework:** This provides a hierarchical model of plant equipment, process data, and metadata.
- **Asset Analytics:** This feature offers operational analytics and batch operation capabilities.
- **Event Frames:** This creates a plant operation model for batches that is referenced to the asset model.
- **Notifications and Alerting:** These features help monitor and respond to events.

The system supports the ISA S88 standard, which provides a framework for managing batch processes. It structures data around process areas, units, equipment modules, and control modules.

## Automatic Event Generation

The AVEVA PI system includes a PI Event Frames Generator (PI EF Gen) that automates the generation of events from PI Tag triggers (historian). Key functions of the PI EF Gen include:

- Generating events.
- Handling multiple event types.
- Standardizing using event frame templates and populating event attributes.
- Generating complex event hierarchies like batches.
- Recovering history and backfilling events.
- High availability and failover.
- Flexible deployment.
- Easy migration from PI Batch Generator.

Event Frames are created based on configured analyses, which include an Event Frame Template, naming pattern, and attributes. The system allows testing and previewing of Event Frame generation.

## Interfaces for BES/MES Systems

The AVEVA PI System interfaces for Batch Execution Systems (BES) and Manufacturing Execution Systems (MES) enable:

- Automatic generation of batch events.
- Processing data in a batch context.
- Automatic configuration.
- Population of batch attributes.
- MES System integration.
- Attribute and tag templates.
- Recipe templates.
- Batch merging across systems.
- History recovery.
- Resilience to failure.

## Migration from PI Batch to Event Frames

Migrating from the traditional PI Batch system to Event Frames offers several advantages, including the elimination of constraints of the legacy PI Batch system. Event Frames can handle multiple events simultaneously per AF element. Additionally, event data is stored in the AF database. Key benefits of Event Frame adoption include:

- **Data Integration:** Simultaneously store data against a unit, including batch, downtime, and excursion data, with an integrated event view.
- **Enhanced Features:** Supports concurrent events on a unit, is industry agnostic, and provides tighter integration.
- **Ease of Use:** Increased flexibility with Event Frame templates and increased accessibility via new data access technologies.
- **Future Proof:** Utilizes modern PI System Technology with continuous updates and added functionality.

Batch interfaces can be configured to match batch events with the Event Frame hierarchy, while PI Analytics can manage simple Event Frames.


## Migration to Event Frames:

### Planning

Migration to Event Frames requires careful planning and preparation, including:

- Preparing batch data sources and consumers.
- Analyzing batch data before migration.
- Testing migration and cutover from current sources.
- Migrating batch data to event frames.
- Verifying event frame data.

Migration approaches include migrating the PI Batch database to Event Frames, switching over to Event Frames, and a "mixed" approach that combines both.

## Best Practices

Here are some best practices for migration:

- Perform migration in a test environment before production.
- Take recent full backups of both PI AF and PI Data Archive.
- Upgrade PI System and all OSIsoft applications to the latest versions.
- Plan migrations during plant downtime.
- Schedule time between test migration and production migration for continued testing.
- Test, utilize, and experiment with Event Frames as soon as possible.

## Conclusion

The AVEVA PI System offers a robust solution for the batch process industry, improving efficiency, quality, and process management. Migrating to Event Frames is a key step to realizing its full benefits. By adopting best migration practices, companies can optimize operations and enhance overall performance.

This is a summary of the key points from the provided sources. If you need more details on any specific aspect, let me know.