Analyze this entire repository and identify where the application calculates, predicts, estimates, or retrieves stock values.

The term “stock value” may refer to:

* Current market price
* Fair value or intrinsic value
* Private-company share value
* Option or equity value
* Valuation based on financial data
* Machine-learning model prediction
* Price retrieved from an external API or database

Perform a read-only investigation. Do not modify any files.

Follow these steps:

1. Search the repository for relevant terms, including:

   * stock
   * share price
   * market price
   * fair value
   * intrinsic value
   * valuation
   * equity value
   * enterprise value
   * price prediction
   * model.predict
   * prediction
   * inference
   * scoring
   * estimate
   * quote
   * NAV
   * DCF
   * Black-Scholes
   * Monte Carlo
   * XGBoost
   * RandomForest
   * regression
   * ONNX
   * pickle
   * joblib
   * coefficients
   * feature engineering

2. Look for:

   * Classes or functions that calculate a stock value
   * ML model-loading code
   * Calls to `predict`, `predict_proba`, `transform`, or inference endpoints
   * Mathematical valuation formulas
   * SQL queries or stored procedures returning stock values
   * External APIs that provide market prices
   * Configuration files containing model names or model endpoints
   * Scheduled jobs, queues, or batch processes that update valuations
   * Controllers, services, repositories, notebooks, and utility classes related to valuation

3. Trace the complete execution flow:

   * What API, UI action, scheduled job, or event starts the process?
   * Which controller or handler receives the request?
   * Which service performs the calculation?
   * Which model or formula is used?
   * What input features are passed to the model?
   * Where are the model files or model endpoints configured?
   * Where is the calculated value stored?
   * How is the final value returned or displayed?

4. Determine whether the value is:

   * Calculated internally
   * Predicted by an ML model
   * Retrieved from an external service
   * Read directly from a database
   * Produced through a combination of these approaches

5. Inspect tests because they may reveal the expected valuation behavior.

6. Use GitHub, Sourcegraph, and other available repository-search tools or MCP integrations when useful.

Return the findings in this format:

## Most likely implementation

* File path:
* Class:
* Function or method:
* Relevant line range:
* Why this appears to determine the stock value:
* Confidence: High, Medium, or Low

## Execution flow

Show the flow in this format:

`Entry point → Controller/Handler → Service → Model/API/Formula → Database → Response`

## Candidate implementations

Create a table with:

| Priority | File | Class/Function | Role | Evidence | Confidence |
| -------- | ---- | -------------- | ---- | -------- | ---------- |

## Model details

For each discovered model, identify:

* Model type
* Model name
* Model file or endpoint
* Input features
* Output
* Model-loading location
* Prediction location
* Configuration location
* Training code, if present

## External dependencies

List any APIs, databases, queues, scheduled jobs, stored procedures, or external services involved.

## Unknowns

Clearly state anything that cannot be confirmed from the repository.

Include exact file paths, class names, method names, and short code excerpts as evidence. Do not make assumptions without repository evidence.
