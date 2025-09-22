아래 내용을 README.md에 그대로 붙여 넣으면 된다.

Sudoku Game

가로·세로·3×3 박스에 1–9를 중복 없이 채우는 논리 퍼즐.

규칙

각 행에는 1–9가 중복되면 안 된다.

각 열에는 1–9가 중복되면 안 된다.

각 3×3 박스에는 1–9가 중복되면 안 된다.

주요 함수

initialize_board()
빈 9×9 보드 생성. 0은 빈 칸을 의미.

print_board(board)
현재 보드를 구분선과 함께 출력.

solve_sudoku(board)
백트래킹으로 퍼즐을 제자리에서 해결. 성공 시 True.

generate_sudoku(difficulty=\"medium\", seed=None)
완성 보드에서 칸을 제거해 유일 해답 퍼즐 생성. 난이도: easy|medium|hard|expert.

play_sudoku(difficulty=\"medium\", seed=None)
간단한 CLI 게임. 완성하거나 잘못된 입력 시 종료.
