
git clone "Your-repository"

sudo apt install python3-pip

pip3 install -r requirements.txt

python3 -m streamlit run StreamlitAPP.py

##### if you want to add openai api key

1. create .env file in your server
touch .env

vi .env
#press insert
#copy your api key and paste it there
#press and then :wq and hit enter

go with security and add the inbound rule
add the port 8501
