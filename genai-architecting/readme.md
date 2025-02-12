## GenAI Architecting

This is a collection of notes and resources for GenAI Architecting.

### Requirements

#### Technical Aspects

1. **Requirements**
   - System must handle authentication and authorization through AUTH GATEWAY
   - Frontend application runs on port 8000 with multiple user interfaces (Dashboard, Practice, Study Activities, Settings, etc)
   - Backend services run on port 5000 with dedicated services for Authentication, Content Management, Profile Settings, and Study Activities
   - Integration with RAG (Retrieval Augmented Generation) system for enhanced LLM interactions

2. **Data Strategy**
   - SQL Database integration for persistent storage
   - Content management system for educational materials
   - User profile and progress tracking
   - Study analytics and performance metrics

3. **Model Selection and Development**
   - LLM integration for language learning assistance
   - Query processing and embedding capabilities
   - Custom model chaining for specific language learning tasks

4. **Governance and Security**
   - Authentication services for user access control
   - Secure API communication between frontend and backend
   - Data privacy considerations for user information
   - Monitoring and logging of system usage

5. **Scalability and Future-Proofing**
   - Modular design allowing for new feature integration
   - Separate frontend and backend concerns
   - Containerization ready architecture

#### Business Aspects

1. **Use Cases**
   - Language learning and practice
   - Progress tracking and analytics
   - Personalized study scheduling
   - Achievement and badge system
   - Interactive writing and pronunciation exercises

2. **Complexity**
   - Multi-layered architecture with distinct service boundaries
   - Integration of AI/ML components with traditional web services
   - User experience management across multiple features
   - Real-time interaction handling

3. **Lock-in Considerations**
   - Database technology selection
   - LLM provider dependencies
   - Infrastructure requirements
   - API design and compatibility

4. **Integration Complexity**
   - LLM workflow integration with existing services
   - Real-time processing requirements
   - Data flow between components
   - Performance optimization needs


