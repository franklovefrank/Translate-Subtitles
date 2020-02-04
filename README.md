# Translate-Subtitles
translate subtitles from english 


heehaw!!


from your terminal:

pip install pyexecjs  
pip install srt

if you want chinese:

pip install jieba

clone util_trans.py, util_srt.py, utils.py into directory   

example compiler input: 
from utils import translate_and_compose  
input_file = "sample.srt"   
translate_and_compose(input_file, 'output.srt', 'en', 'de', space=True)   


