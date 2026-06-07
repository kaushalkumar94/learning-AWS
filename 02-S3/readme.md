# Lesson 2 - Amazon S3 & Storage Classes

## Date
June 7, 2026

## What I Learned
- What Amazon S3 is and its core use cases
- How S3 is structured (Buckets → Objects)
- The different S3 Storage Classes and when to use each

## Key Concepts

### Amazon S3 (Simple Storage Service)
- Object storage service — stores files as objects inside buckets
- Each object has a Key (filename), Value (data), and Metadata
- Buckets are globally unique and region-specific

### S3 Storage Classes

| Storage Class | Use Case | Retrieval |
|---|---|---|
| S3 Standard | Frequently accessed data | Instant |
| S3 Intelligent-Tiering | Unknown access patterns | Instant |
| S3 Standard-IA | Infrequently accessed | Instant |
| S3 One Zone-IA | Non-critical, infrequent | Instant |
| S3 Glacier Instant | Archive, occasional access | Instant |
| S3 Glacier Flexible | Archive, rare access | Minutes–Hours |
| S3 Glacier Deep Archive | Long-term archive | Up to 12 hrs |

## Key Terms
- **Bucket** – Container for storing objects in S3
- **Object** – Any file stored in S3 (image, video, CSV, etc.)
- **Durability** – S3 offers 99.999999999% (11 9's) durability
- **Lifecycle Policy** – Automatically move objects between storage classes

## Questions / Doubts
- When exactly does Intelligent-Tiering make financial sense vs Standard?

## Next Steps
- Hands-on: Create an S3 bucket and upload a file
- Learn about S3 bucket policies and permissions
