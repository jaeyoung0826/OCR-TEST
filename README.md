# 참고사항

본 코드는 개발 중입니다. OCR 과 Tkinter 입문단계에서 제작해본 간단한 코드입니다.
잘못된 기재에 대해서는 언제든지 수정요구 부탁드립니다!!

# OCR-with-Tkinter

 한글이 포함된 이미지 파일에서 한글을 추출해내고자 하여 만든 프로그램 입니다.
 계속 파일명을 바꿔야 하는 불편함을 해소하기위해 tkinter 를 사용하여 파일을 업로드하는 방식을 택하였습니다.

# OCR -Tesseract

 OCR 기능을 사용하기 위해서 설치하였습니다. 
 Tesseract github :https://github.com/tesseract-ocr/tesseract
 참고자료 : https://joyhong.tistory.com/79

# Tkinter package download
 
 Tkinter는 Python 에서 GUI 프로그래밍을 하기위해 설치한 모듈입니다.
 해당 코드에서는 파일 업로드와 기본 설명에 쓰였습니다.
 
 
 # 오류시 확인 사항
 
  1. package 설치 확인
  2. 업로드된 파일이 너무 크거나 작을 경우 전처리를 해주어야 합니다.
  3. 확인용 사진을 닫아야 OCR 기능이 작동합니다. 
  
  
  # 개선사항
  
  1. 확인 이미지를 새로운 윈도우 창이 아닌 기존 Tkinter의 window(root) 에 띄울 수 있는 방법이 있는지.
  2. 실제 OCR 이 적용된 모습 (BOX의 좌표가 가리키는 곳) 을 같이 첨부 할 수 있어야 한다.
  3. 창을 일정시간 후에 자동적으로 닫게 한다.
  
  
  
 
  
