from pathlib import Path

readme_content = """# 🌐 BNK 3rd Project — Web Prototype Links

## 🤖 Chatbot Pages
| Version | Link | Description |
|----------|------|-------------|
| v3 | [bnk_chatbot_ver3.html](https://yingbbang.github.io/bnk-3rd-project-test/bnk_chatbot_ver3.html) | 기존 챗봇 인터페이스 |
| v4 | [bnk_chatbot_ver4.html](https://yingbbang.github.io/bnk-3rd-project-test/bnk_chatbot_ver4.html) | 개선된 UI/UX 및 기능 업데이트 버전 |

---

## 💳 Card Page
| Page | Link | Description |
|-------|------|-------------|
| BNK Card | [bnk_card.html](https://yingbbang.github.io/bnk-3rd-project-test/bnk_card.html) | BNK 카드 상품 소개 및 UI 시안 |

---

## 🛠️ Admin Pages (금융상품 관리자 화면 Mockup)
| Version | Link | Description |
|----------|------|-------------|
| v1 | [bnk_financial_product_admin_html_css_mockup_v1.html](https://yingbbang.github.io/bnk-3rd-project-test/bnk_financial_product_admin_html_css_mockup_v1.html) | 기본 UI 레이아웃 구성 |
| v2 | [bnk_financial_product_admin_html_css_mockup_v2.html](https://yingbbang.github.io/bnk-3rd-project-test/bnk_financial_product_admin_html_css_mockup_v2.html) | 테이블·버튼 스타일 개선 |
| v3 | [bnk_financial_product_admin_html_css_mockup_v3.html](https://yingbbang.github.io/bnk-3rd-project-test/bnk_financial_product_admin_html_css_mockup_v3.html) | 완성도 높은 관리자 페이지 UI |

---

## 📁 Summary
> - **Chatbot Pages**: 예금·적금 추천형 대화 UI  
> - **Card Page**: 금융상품 시각화 카드  
> - **Admin Pages**: 내부 운영자용 금융상품 관리 화면(Mockup)
"""

path = Path("/mnt/data/BNK_3rd_Project_Links.md")
path.write_text(readme_content, encoding="utf-8")
path
