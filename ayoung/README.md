

# 1. ASP.NET 소개

####  C# 이란?

> 마이크로소프트사에서 만든 개체 지향 프로그래밍 언어 

<p></p>

#### APS.NET 이란?

> 프로그래밍 언어를 사용해 웹 응용 프로그램을 작성하는 기술. HTML 페이지가 클라이언트 브라우저에서 정적으로 보여준다면 ASP와 ASP.NET은 서버에서 동적으로 HTML 페이지를 만들어 웹 브라우저에 원하는 용도로 출력해준다.

<p></p>

ASP.NET으로 웹 응용프로그램을 제작할때는 C#, Visual Basic 등을 사용할 수 있으나, C#을 기반언어로 사용할 생각이다.

### ASP.NET의 특징

1. 웹 표준 및 웹 접근성이 뛰어난 응용 프로그램을 제작할 수 있다.
2. 개발 시간을 줄여 생산성 향상
3. 뛰어난 시각적 디자인 기능 제공
4. 개체 지향 프로그래밍 기법 지원
5. 데이터 베이스를 손쉽게 프로그래밍 할 수 있다
6. 배우기 쉽고 구조적으로 프로그래밍을 할 수 있다.


# 2. Enviornment

 MAC / VSCODE

# 3. Setting

1. .net core sdk 다운로드

    https://dotnet.microsoft.com/download

2. vscode 확장도구에서 C# 다운 (제일 위에있는것)

3. workspace 만든 뒤 폴더안에서 아래 명령어 

    ```
    dotnet new console  //C# 컴파일에 필요한 파일 셋팅
    ```
    혹시 Program.cs에 빨간줄이 뜬다면 (필요한 default class들이 import되지 않았기때문)
    ```
    dotnet restore
    ```
4. 실행명령어
    ```
    dotnet run
    ```

# 4. Hello World

간단히 이름 입력받고 출력해보기
```
    Console.WriteLine("\nWhat is your name? ");
    var name = Console.ReadLine();
    var date = DateTime.Now;
    Console.WriteLine($"\nHello, {name}, on {date:d} at {date:t}!");
    Console.Write("\nPress any key to exit...");
    Console.ReadKey(true);
```

실행결과는 다음과 같다.

![ex_screenshot](./img/1.png)