<br>

# 🗂️ 힙(HEAP)
> - <code>**우선순위 큐**</code>를 위해 만들어진 자료구조로 <code>**완전 이진트리**</code>의 일종
> - 여러 값 중 최대/최소 값을 빠르게 찾아내도록 만들어진 반정렬 상태
> - 보통 최대/최소 값을 찾으려면 <code>O(n)</code>의 시간이 걸리지만 힙 사용시 <code>O(log<sub>n</sub>)</code>만큼 소요
> - 힙 트리는 중복된 값을 허용!
>
> <br>
>
> ## 우선순위 큐란?
> - 들어간 순서에 상관없이 높은 우선순위를 가진 원소를 낮은 우선순위를 가진 원소보다 먼저 처리
>
> <br>
>
> ## 완전 이진트리란?
> - 각 노드가 최대 2개의 자식 노드를 갖는 트리형태
> - 마지막 레벨을 제외한 모든 노드가 완전히 채워짐
> - 최하단 좌측 노드부터 차례로 삽입
>
> <br>
>
> ## 힙의 종류
> > ### 최대 힙
> > - 부모 노드의 키 값이 자식 노드의 키 값보다 크거나 같은 완전 이진 트리
> >
> > ### 최소 힙
> > - 부모 노드의 키 값이 자식 노드의 키 값보다 작거나 같은 완전 이진 트리
>
> <br>
>
> ## 힙 구현(파이썬) 
>
> ### 리스트를 사용하여 구현
>> #### 각 노드의 인덱스
>>   - 편의 상 0번 인덱스는 <code>None</code>으로 비워두고 구현 <code>(루트 노드 인덱스 : 1)</code>
>>   - 각 노드의 왼쪽 자식 노드 인덱스 : <code>(부모 노드) * 2</code>
>>   - 각 노드의 오른쪽 자식 노드 인덱스 : <code>(부모 노드) * 2 + 1</code>
>>
>> #### 삽입 및 삭제 연산
>>   - 노드 삽입 연산 시 리스트 끝에 <code>append()</code> 후 <code>업 힙</code>으로 정렬
>>   - 노드 삭제 연산 시 리스트 시작 값을 리스트 끝 값으로 치환 및 <code>pop()</code> 후 <code>다운 힙</code>으로 정렬
>
> <br>
>
> ## 🪄 참고 자료
> [힙 (최소 힙, 최대 힙)](https://velog.io/@jsbryan/%ED%9E%99-%EC%B5%9C%EC%86%8C-%ED%9E%99-%EC%B5%9C%EB%8C%80-%ED%9E%99)





<br>


