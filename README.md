# LAYOUTGOOD
try use route to excute model on website
django 必須使用虛擬環境執行 
請用virtualenv建立環境才安裝所需套件套件
如：
virtualenv VENV
並啟動環境 source VENV/bin/activate
到 requirements.txt檔案那層
執行 pip3 install -r requirements.txt
啟動伺服器
python3 manage.py runserver

BeautyGAN模型請到BeautyGAN資料夾下載並放在BeautyGAN > model下
shape_predictor_68_face_landmarks.dat 請上網下載並放在BeautyGAN資料夾下
object_detection模型 請放在object_detection>checkpoint_test資料夾下
