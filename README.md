# 🎨 카카오톡 AI 그림 생성 챗봇 (ChatGPT + DALL·E2)

## 프로젝트 개요
본 프로젝트는 ChatGPT와 DALL·E2를 활용하여  
사용자가 카카오톡에서 텍스트를 입력하면 AI가 이미지를 생성해주는 챗봇 시스템입니다.

- 목적: 누구나 쉽게 AI 이미지 생성을 사용할 수 있는 서비스 구현
- 플랫폼: 카카오톡 챗봇
- 기능: 자연어 기반 이미지 생성

---

## 주요 기능

- 텍스트 입력 → AI 이미지 생성
- ChatGPT를 활용한 프롬프트 처리
- DALL·E를 통한 이미지 생성
- 카카오톡 채팅 기반 인터페이스

---

## 🛠️ 시스템 구조
- 사용자 (카카오톡)
↓
- Kakao i Open Builder (Webhook)
↓
- AWS Lambda (서버)
↓
- ChatGPT (프롬프트 생성)
↓
- DALL·E2 (이미지 생성)
↓
- 카카오톡으로 결과 이미지 반환

---

## 동작 과정
1. 사용자가 카카오톡에서 이미지 생성 요청
2. AWS Lambda로 요청 전달
3. 사용자 입력을 ChatGPT로 전달하여 프롬프트 생성
4. 생성된 프롬프트를 DALL·E API에 전달
5. 이미지 생성 후 URL을 카카오톡으로 반환

---

## 결과 예시

<img width="1756" height="1039" alt="Kakao_chatbot" src="https://github.com/user-attachments/assets/e40a51b8-c47b-4223-8705-bfeebd499ffa" />

---
