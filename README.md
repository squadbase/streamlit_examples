# Streamlit Examples for Squadbase

## Overview

`streamlit_examples` is a curated collection of AI‑powered Streamlit applications designed for **internal deployment on Squadbase**.
Each sub‑directory contains a self‑contained app that can be run locally or deployed to Squadbase with a single git push.

### Included Apps

| Directory                  | Summary                                                                                                                         | Key Tech                                     | Upstream Repository                   |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- | ------------------------------------- |
| `exploratory-copilot-app/` | Upload a CSV and receive an automated Exploratory Data Analysis (EDA) report powered by a Copilot‑style assistant.              | `streamlit`, `pandas‑profiling`, `langchain` | business‑science/ai-data‑science‑team |
| `pandas-data-analyst-app/` | An AI assistant that guides you through interactive data wrangling and analysis with Pandas.                                    | `streamlit`, `pandas`, `openai`              | business‑science/ai-data‑science‑team |
| `sql-database-agent-app/`  | Connect to a SQL database and ask questions in natural language; the agent translates requests into SQL and visualises results. | `streamlit`, `sqlalchemy`, `langchain`       | business‑science/ai-data‑science‑team |

## Deploying to Squadbase

1. Push your fork or branch to a Git repository connected to Squadbase.
2. In the Squadbase dashboard, **Add Application → Git** and select the corresponding directory as the build path.
3. Set any required environment variables in _Environment Variables_.

> **Tip:** Because each app lives in its own directory, you can deploy them as separate projects or combine them under a single multi‑page Streamlit app.

## Acknowledgements

The initial set of apps was forked from examples created by the Business‑Science team (see upstream links above). We appreciate their work for offering a solid foundation to showcase AI‑assisted data workflows with Streamlit.

As we add more sample applications from other sources, this section will be updated to credit each original author and project accordingly.
