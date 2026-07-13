# titanic-ml-llm-pipeline

1. Chosen Track: Model Prediction Explanation Pipeline (Track C).

2. A structured JSON explanation containing prediction label, confidence level, top reason, second reason and next step was generated for model predictions.

3. Temperature 0 was selected to ensure deterministic and reproducible responses suitable for structured output tasks.

4. Temperature 0.7 was tested and produced more varied outputs because it samples from a wider probability distribution.

5. JSON schema validation was performed using jsonschema.validate() to ensure all required fields were present.

6. A PII guardrail using regular expressions blocked email addresses and phone numbers before LLM calls were allowed.

7. The API key was intended to be stored in an environment variable rather than hardcoded into source code.
