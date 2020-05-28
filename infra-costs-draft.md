For daily loads:

- Blockchain Nodes: $300/month (n1-standard-4 instance with 500GB SSD disk, adjust depending on requirements). Double of that if High Availability is needed.
- GKE cluster master: $70/month.
- Cloud Composer: $380/month.
- BigQuery Storage: $10/month (assuming 500GB of blockchain data stored in BigQuery).
- BigQuery ETL: 0.15/month (assuming 1GB of data processed per day).
- GCS Storage: $13/month (assuming 500GB of blockchain data stored in BigQuery).
- Others: $20/month (network data transfer, GCS API calls)

For real-time ingestion:

- Streamer nodes: $30/month (n1-standard-1 instance with 10GB SSD disk)
- GKE cluster master: $70/month.
- Dataflow: $65/month.
- Pub/Sub: $35/month (assuming 1GB/day, 4 days volume snapshot backlog).
- BigQuery Streaming: $2/month (assuming 1GB/day).
Should be adjusted for specific requirements on amount of data and blockchain size
