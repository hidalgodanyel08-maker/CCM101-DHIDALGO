# Client Recommendations

## Client A – Startup Company

**Requirement:** A startup launching a mobile app with limited budget but expecting rapid growth.

**Recommended Platform:** **AWS**

**Explanation:** AWS offers the AWS Activate program with free credits for startups, a robust free tier, and the broadest service catalog to support rapid scaling. Services like EC2 Auto Scaling, RDS, and S3 allow the startup to start small and grow without re-architecting. AWS's pay-as-you-go model and extensive documentation also make it cost-effective for early-stage companies. [citation:13]

**Recommended Services:**
1. **Amazon EC2** - Virtual servers that can scale with demand
2. **Amazon RDS** - Managed database for the mobile app backend
3. **Amazon S3** - Object storage for user-generated content and static assets
4. **AWS Amplify** - For mobile app development and hosting

---

## Client B – University

**Requirement:** University already uses Windows Server, Microsoft 365, and Active Directory; wants to migrate to the cloud.

**Recommended Platform:** **Microsoft Azure**

**Explanation:** Azure is the natural choice for organizations already invested in the Microsoft ecosystem. Azure integrates natively with Active Directory (now Entra ID) for single sign-on, supports Windows Server workloads with Azure Hybrid Benefit (reduces costs), and provides unified billing with Microsoft 365. Azure Arc also enables hybrid management. [citation:5][citation:9][citation:13]

**Recommended Services:**
1. **Azure Virtual Machines** - Host Windows Server workloads
2. **Azure Active Directory (Entra ID)** - Identity management integration
3. **Azure SQL Database** - Managed database services
4. **Azure Files** - File storage accessible via SMB

---

## Client C – AI Research Company

**Requirement:** Research company developing AI/ML applications requiring high-performance computing.

**Recommended Platform:** **Google Cloud Platform**

**Explanation:** GCP offers best-in-class AI/ML capabilities with Vertex AI for end-to-end ML workflows and unique TPU (Tensor Processing Unit) accelerators that deliver superior price-performance for custom model training. BigQuery enables large-scale data analysis, and GKE supports containerized ML workloads. The platform is built on Google's experience with search and YouTube scale. [citation:1][citation:9][citation:13]

**Recommended Services:**
1. **Vertex AI** - End-to-end ML platform
2. **Compute Engine with TPUs** - High-performance compute with Tensor Processing Units
3. **BigQuery** - Data analytics for large ML datasets
4. **Cloud Storage** - Object storage for training data

---

## Client D – Global E-Commerce Company

**Requirement:** Multinational online shopping company requiring highly available, auto-scaling infrastructure.

**Recommended Platform:** **AWS**

**Explanation:** AWS offers the most mature and battle-tested infrastructure for global web applications. With 34 regions and 108 availability zones, AWS provides the global reach and high availability required by multinational e-commerce. AWS Auto Scaling, Elastic Load Balancing, and CloudFront CDN ensure traffic is handled efficiently during peak seasons. [citation:1][citation:13]

**Recommended Services:**
1. **Amazon EC2 Auto Scaling** - Automatically adjusts capacity
2. **Elastic Load Balancing (ELB)** - Distributes traffic across instances
3. **Amazon CloudFront** - Global content delivery network
4. **Amazon RDS with Multi-AZ** - Highly available database with automatic failover
