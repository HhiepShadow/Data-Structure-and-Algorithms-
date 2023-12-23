# Data-Structure-and-Algorithms-
<h1>Data Structure and Algorithms Using Java, Python and C++</h1>

<h2>I. [Java, C++] Data Structure</h2>
<h2>II. [Java, C++, Python] Algorithms and Applications</h2>

# Lesson 1: HelloWorld with Typescript

## I. Installation:
1. Cài đặt NodeJS phiên bản mới nhất (20.10.0)
2. Cài đặt Typescript: npm i -g typescript

====================================================================================================================

## II. Tạo project và file .ts:
1. Tạo 1 file main.ts
2. Biên dịch file .ts:
    ```bash
    tsc main.ts
    ``` 

    ```cmd (powershell)
    tsc.cmd main.ts
    ```

====================================================================================================================

## III. Watch flag:
- Để tránh việc mỗi khi phải biên dịch lại file .ts khi ta thay đổi mã trong nó, ta có thể gắn thêm cờ --watch (hoặc -w) khi biên dịch file

    ```bash
    tsc main.ts -w
    ```

    ```cmd (powershell)
    tsc.cmd main.ts -w
    ```

====================================================================================================================

## IV. File tsconfig.json:
- Là tệp dùng để cấu hình TypeScript
- Giúp thiết lập các tùy chọn biên dịch và cấu hình cho 1 dự án TypeScript
- Bao gồm:
    + "compilerOptions"
