## ArrayList
- 기본적으로 **`배열`** 을 사용
- 크기를 지정하지 않고 **동적**으로 값을 삽입 · 삭제 가능

### Array vs. ArrayList
|Array|ArrayList|
|---|---|
|생성 시 크기 지정 필수|생성 시 크기 미지정 (동적)|

### 조회
- 각 데이터의 `index`를 가지기 때문에 **random access** 가능

### 삽입·삭제
- 특정 데이터를 삭제하면 뒤에 위치한 데이터들을 앞으로 이동시켜주어야 함
- 삽입, 삭제가 많으면 ArrayList는 **비효율적**임

## LinkedList
- 각각의 노드가 데이터와 다음 노드를 가리키는 포인터를 가지고 한 줄로 연결되어 있는 방식

### 조회
- **sequential access**이므로 검색의 속도가 느림

### 삽입·삭제
가리키고 있는 **주소값**만 **변경**해주면 됨. → ArrayList에 비해 훨씬 효율적
  
