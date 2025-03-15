1. "앱프로그래밍 응용" 시간에 필요한 안드로이드 스튜디오와 플러터를 집에서 다운 받고 환경 구성하기
2. HelloWorld 앱 실행하기

3. "HelloWorld" 앱 소스코드
<pre>
<code>
  import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: const Text('Hello World App'),
        ),
        body: const Center(
          child: Text(
            'Hello World',
            style: TextStyle(fontSize: 24),
          ),
        ),
      ),
    );
  }
}
</code>
</pre>

