# python-chatbot

## **1. Create Python virtual environment**
```
python -m venv venv
```

## **2. Activate environment**
* ### Powershell
    ```
    .\venv\Scripts\Activate.ps1
    ```

* ### CMD
    ```
    .\venv\Scripts\activate.bat
    ```

* ### Linux
    ```
    source ./venv/bin/activate
    ```

## **3. Install required modules**
```
pip install -r requirements.txt
```

## **4. Train the model**
```
python train_bot.py
```

## **5. Testing**
```
python chatgui.py
```