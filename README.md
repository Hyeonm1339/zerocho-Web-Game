17버전 리액트 코드 - ReactDOM.render(....)
18버전 리액트 코드 - ReactDOM.creatRoot(...).render(...)

JSX문법상 for,if사용이 힘드므로 삼항연사자를 사용, 배열 map을 사용하여 반복문
setState는 비동기방식이므로 기존함수를 변경시에는 애로우함수를 추가하여 기존상태를 복사,유지 후 리턴하여 사용하는것이 좋다
ex) this.setState((prevState) => {
return {
result: prevState.value + '정답 입니다.',
first: Math.ceil(Math.random() _ 9),
second: Math.ceil(Math.random() _ 9),
value: '',
}
})
