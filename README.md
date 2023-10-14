## Get Started

1. Create a new directory named `.streamlit`:

```
mkdir .streamlit
```

2. Navigate to the newly created `.streamlit` directory:

```
cd .streamlit
```

3. Create a new file named `secrets.toml`:

```
touch secrets.toml
```

4. Open the `secrets.toml` file and add the following line, replacing `<Your API Key>` with your actual OpenAI API key:

```
OPENAI_API_KEY='<Your API Key>'
```

## Installation

- Install the required dependencies by running the following commands:

```
pip install streamlit
pip install openai
```

## Running

- To run the application, use the following command:

```
streamlit run main.py
```
