# Actor movies and their news
Obtain actor known movies and latest news off NYTimes by simply entering actor name.

## Value
Easy way to get actor known movies and their latest news.

## Prerequisites
- Python 3.11 or higher
- pip (Python package manager)

## Setup
1. Clone this repository or download the source code. `git clone https://github.com/wg2261/actor_data_feature.git`
2. Navigate to the project directory:
   ```
   cd path/to/actor_data_feature
   ```
3. Create a virtual environemnt if you'd like
    ```
    python -m venv .venv 

    # On Windows:
    .venv\Scripts\activate

    # On macOS and Linux:
    source .venv/bin/activate

    ```
4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
5. Create a `.env` file in the project root directory with your NYTimes and TMDB connection string:
   ```
   NYTIMES_API_KEY=your_key_here
   TMDB_API_KEY=your_key_here
   ```
   Replace `your_key_here` with your respective connection string

## Usage
To run the application:
```
python main.py
```

Follow the on-screen prompts to interact
Enter actor name

## Data used
1. TMDB - Information on actors and movies
2. NYTimes - Latest news
