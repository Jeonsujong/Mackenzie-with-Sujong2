### 전체적인 과정
아무 것도 없는 데에서 시작하여 그럴듯한 블로그를 만들어낸다. 그 동안 배운 개념을 다시 적용할 수 있었다.
### 새로 안 내용
devise gem을 통한 sign_up과 sign_in
### 오류 내용
오타로 시간 날리고, 쉼표 안 넣어서 시간 날리고 그래도 괜찮았다 참을 수 있었다 

'undefined method `post_comment_path' for #<#<Class:0x007f6b39a37db0>:0x007f6b39a351c8>
Did you mean?  post_comments_path
               post_comments_url'
               
근데 저 에러는 참을 수 없었다. 왜냐하면 너무 많은 시간을 뺏어갔기 때문이다.. 안 그래도 늦었는데..
그래도 결국에 스스로 찾아내서 너무 기쁘다. routes에 resources를 resource라고 써서 발생한 문제였다. 30분이나 버렸다. 찾아낸 내가 대견하다.