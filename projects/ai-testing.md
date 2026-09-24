## 🤖 AI & LLM Testing

Hands-on experience in testing AI-powered systems, LLM-based services,
NLU/NLP components and RAG-based systems.

### AI / LLM Testing Experience

- LLM-based systems and AI-powered services
- NLU / NLP testing
- Entity recognition and intent prediction
- RAG-based systems
- Non-deterministic output validation
- AI-generated test data
- LLM-as-a-judge evaluation
- Prompt engineering
- API and integration testing
- Kafka-based integrations

### AI Evaluation & Test Automation

- Practical experience with **DeepEval** and **PromptFoo** for evaluating
  LLM-based applications
- Designing evaluation scenarios for AI-generated responses
- Automated validation of model responses against expected behavior
- Testing response quality, relevance and correctness
- Using local LLMs to generate test datasets and test scenarios
- Using a separate local LLM as an evaluator for automated quality assessment
- Working with non-deterministic outputs where traditional exact-match
  assertions are not sufficient

### Entity Recognition Testing

Tested AI endpoints responsible for entity recognition and prediction.

For example, for a `predict_entities` endpoint:

- Prepared test requests and datasets for entity recognition scenarios
- Used one local LLM to generate diverse test inputs and test data
- Sent generated requests to the system under test
- Compared predicted entities with expected entities
- Evaluated recognition accuracy and identified incorrect or missing entities
- Automated the validation process to support repeatable testing

This approach allowed testing the quality of AI predictions rather than
only validating HTTP status codes or response schemas.

### Local LLM Performance Testing

Performed load testing of locally hosted LLM services using **Locust**.

The testing focused on determining:

- Maximum sustainable request throughput
- Response time under increasing load
- Model behavior under concurrent requests
- Resource limitations and system bottlenecks
- The number of requests the model infrastructure could process
- Stability of the service under sustained load

Load testing was performed against locally hosted models and AI service
endpoints to identify practical performance limits before integrating them
into larger systems.

### AI-assisted Test Engineering

- AI-assisted generation of test data
- Using LLMs to generate edge-case scenarios
- Using local models for automated evaluation
- Combining deterministic assertions with semantic evaluation
- Designing testing approaches for systems where a single "correct"
  response may not exist