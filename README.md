# capstone-project
Wasm 스마트 컨트랙트 보호를 위한 TEE 기술 적용 프로젝트
프로젝트 개요

Hyperledger Fabric v2.2의 체인코드를 OP-TEE를 활용하여 신뢰 실행 환경(TEE)에서 실행하는 것을 목표로 합니다. 이를 통해 체인코드의 보안성을 향상시키고, WebAssembly(Wasm) 기반 스마트 컨트랙트의 안전한 실행 환경을 구축합니다.

주요 목표
	•	Hyperledger Fabric v2.2의 체인코드 실행 방식 이해 및 OP-TEE와의 통합
	•	WaTZ 프로젝트 분석 및 활용
	•	Fabric OP-TEE Chaincode (FOC) 아키텍처 및 API 연구
	•	Wasm 기반 스마트 컨트랙트의 보안성 및 성능 평가

사용 기술 및 도구
	•	Hyperledger Fabric v2.2
	•	WebAssembly(Wasm)
	•	OP-TEE: ARM TrustZone을 활용한 오픈 소스 TEE
	•	WaTZ: TrustZone을 활용한 신뢰할 수 있는 Wasm 런타임 환경
	•	Fabric OP-TEE Chaincode (FOC): Hyperledger Fabric 체인코드를 OP-TEE에서 실행하기 위한 아키텍처 및 API
