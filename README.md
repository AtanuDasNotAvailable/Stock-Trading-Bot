## Steps to Run the Project

1. **Set up a virtual environment**  
   Create a new environment:  
   `conda create -n trader python=3.10`  

2. **Activate the environment**  
   Activate the newly created environment:  
   `conda activate trader`  

3. **Install dependencies**  
   Install the initial dependencies:  
   `pip install lumibot timedelta alpaca-trade-api==3.1.1`  

4. **Add machine learning libraries**  
   Install additional libraries:  
   `pip install torch torchvision torchaudio transformers`  

5. **Configure API keys**  
   Update the `API_KEY` and `API_SECRET` variables with your Alpaca account credentials.  

6. **Run the trading bot**  
   Execute the bot script:  
   `python tradingbot.py`  