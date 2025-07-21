# SANO 
Privacy-First Sexual Health Tracker (iOS)

**In Development | Target TestFlight Release: Q4 2025**  
*SwiftUI | CoreML | Figma | Local-First Architecture*

[SANO Figma Link](https://www.figma.com/proto/fZM2XvzGvfsb7pzMmOnbkl/SANO?node-id=3-6&t=l7xwgUC1M6LimApq-1)

## Mission
SANO helps LGBTQ+ and high-risk communities track STD/HIV exposure **anonymously** by:
-  **Color-coded encounter logging** (green/yellow/red risk levels)
-  **PrEP adherence tracking** with local reminders
-  **On-device ML** for personalized risk scores (no cloud storage)

##  Current Progress
-  **Figma prototype** validated by 50+ users
-  **SwiftUI architecture** in development:
  - CoreData for local storage
  - CoreML model training (target: 85% recall)
-  **Next steps**: 
  - Implement risk scoring algorithm
  - Beta testing via TestFlight (target: Q4 2025)
    
##  FAQ
- **Q:** Why no public code yet?
  - **A:** Ensuring HIPAA-compliant architecture before open-sourcing non-core components.

- **Q:** How can I contribute?
  - **A:** DM me for Figma access or SwiftUI code reviews!

## Technical Stack
```swift
import SwiftUI
import CoreML // For on-device risk model
import CoreData // For local storage

