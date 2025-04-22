<h2>🖥️ 3-1. 시스템 프로그래밍 구현 과제</h2>

<h3>프로젝트 구조</h3>
Assem1 : no UI version(프로젝트 1b) : assembler 개발

Assem2 : UI version(프로젝트 2) : simulator 개발

<h2>⛏️ Assem2</h2>
Assem1에서 구현한 어셈블러의 Simulator 개발

<h3>구현 내용</h3>

1. object program code(output_objectcode_ex.txt) -> 가상 메모리에 load
   
2. instuction file -> 명령어 파일(inst_table.txt)을 InstrcuctionTable을 생성하는데 사용
   
3. load된 가상 메모리 -> 가상메모리와 레지스터를 사용해 instruction을 simulate

➡️ GUI에서 선택한 file(proj_2.txt) -> copy를 수행해 새로운 file(new_file.txt)를 생성

<h3>Java Class별 역할 설명</h3>

![image](https://github.com/user-attachments/assets/968a2731-72bd-4ec1-86bb-981c89a3d1a6)

<h3>실행 결과</h3>

- 초기화면 / 종료 화면 

![image](https://github.com/user-attachments/assets/cfc06f4b-4ae2-4b2b-83b4-3d42642d2741)

![image](https://github.com/user-attachments/assets/6c6be7e3-c5b8-47e0-8218-176b407825e4)

- 1 step 클릭 후 화면(하나의 line을 excute)

![image](https://github.com/user-attachments/assets/96caea08-9df4-49b7-9df0-38c5a2633b78)

- All step 클릭 후 화면(모든 line을 excute)

![image](https://github.com/user-attachments/assets/40e7f09b-cf15-4bb9-85c3-160aca1149a4)

- 기존의 proj_2.txt와 새롭게 생성된 new_file.txt(copy가 잘 수행되었는지 확인하는 목적)

![image](https://github.com/user-attachments/assets/b7d5bbba-b23a-48bd-b523-5a9fad4e3a56)
![image](https://github.com/user-attachments/assets/8cd045c2-8069-44b2-bb5b-bfc7dbbe49f4)

<h3>✨ 느낀 점</h3>

가장 좋았던 점은 하드웨어의 동작 원리를 직접 구현해볼 수 있었다는 것이다. 

머리 속으로 생각하는 것과 수업을 들으면서 상상하는 것을 직접 코드로 구현하고 시각적으로 확인해 볼 수 있었다.

난관이 많았지만 그만큼 좋은 경험이었다고 생각한다.

<h3>제출 보고서</h3>

[[219]프로젝트2_송하림_20221848.pdf]

(https://github.com/user-attachments/files/19847684/219.2_._20221848.pdf)
