# project work directory
mkdir -p /home/projects/flask_app

# change directory to flask_app folder
cd /home/projects/flask_app

# ما اینجا دو تا حالت داریم میتونیم به اختیار از هرکدوم استفاده کنیم
# setup virtualenv
# راه اول استفاده از محیط مجازی پیش فرض پایتون
python -m venv .venv

# راه دوم نصب پکیج virtualenv و استفاده از آن
pip install virtualenv
virtualenv .venv

# اکتیو کردن محیط مجازی
windows: .\.venv\Scripts\activate
mac/Gnulinux: source ./.venv/bin/activate

#  نکته بعد از فعال شدن محیط مجازی یک پیام (activate) 
# در ترمنیال خود میبینید
# برای غیرفعال کردن از کامند &quot deactivate &quot استفاده کنید


# نصب پیکیج flask
pip install flask

# گرفتن خروجی فایل txt
pip freeze > requirement.txt
