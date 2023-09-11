1. 01_nav
bootstrap에 있는 toggle 예제와 비슷하여서 처음엔 쉽게 구현할 수 있었다. 하지만 list 안에 들어가 있는 Home, Community, Login이 기본 왼쪽 정렬로 구현되어 있는데 그것을 오른쪽으로 이동시키기가 많이 어려웠다. 이는 list의 부모 flexbox의 정렬을 row-reverse로 설정하면서 해결할 수 있었다

2. 02.home
sticky-top을 적용할 때 그 안에 modal 코드까지 넣어버려서 modal이 제대로 적용되지 않았던 문제가 있었다.
sticky-top을 적용한 block 밖으로 옮겨서 해결했다.

3. 03_community
section 부분이 viewport에 따라 형태가 완전히 바뀌기 때문에 이를 구현하는 것이 어려웠다.