# 스도쿠 게임

## 📌 프로젝트 소개

이 프로젝트는 파이썬으로 구현된 스도쿠 게임입니다. 사용자가 스도쿠 퍼즐을 플레이하고, 자동으로 해결하며, 새로운 퍼즐을 생성하는 기능을 제공합니다.

## 📝 규칙

스도쿠는 가로, 세로, 그리고 3x3의 작은 정사각형 안에서 1부터 9까지의 숫자를 중복되지 않게 채워 넣는 논리 퍼즐입니다. 채워 넣을 숫자는 주어진 힌트와 숫자의 법칙에 따라 채워져야 합니다.

* **각 행에는 1부터 9까지의 숫자가 중복되지 않게 채워져야 합니다.**
* **각 열에는 1부터 9까지의 숫자가 중복되지 않게 채워져야 합니다.**
* **3x3의 작은 정사각형 안에는 1부터 9까지의 숫자가 중복되지 않게 채워져야 합니다.**

## 🧩 주요 기능 및 함수 설명

이 프로젝트는 다음과 같은 파이썬 함수들로 구성되어 있습니다.

* `initialize_board`: 빈 스도쿠 보드를 생성합니다.
* `print_board`: 현재 스도쿠 보드를 출력합니다.
* `solve_sudoku`: 주어진 스도쿠 퍼즐을 해결합니다.
* `generate_sudoku`: 빈 칸이 채워지지 않은 완성된 스도쿠 퍼즐을 생성합니다.
* `play_sudoku`: 사용자에게 스도쿠 게임을 플레이할 기회를 제공합니다. 게임은 사용자가 잘못된 이동을 하거나 스도쿠를 완성할 때까지 진행됩니다.

## 🚀 시작하는 방법 (How to Run)

1.  이 Repository를 클론합니다.
    ```bash
    git clone [https://github.com/YourUsername/Sudoku_Project.git](https://github.com/YourUsername/Sudoku_Project.git)
    cd Sudoku_Project
    ```
    *(주의: `YourUsername`을 본인의 GitHub 사용자 이름으로 변경하세요.)*

2.  (필요한 경우) 필요한 라이브러리를 설치합니다.
    ```bash
    # 예시: pip install -r requirements.txt (프로젝트에 requirements.txt가 있다면)
    ```

3.  `play_sudoku.py` 파일을 실행하여 게임을 시작합니다.
    ```bash
    python play_sudoku.py
    ```

## 🤝 기여하기 (Contributing)

이 프로젝트에 기여하고 싶다면 언제든지 환영합니다! Fork하여 자유롭게 기능을 추가하거나 버그를 수정해 주세요.
