# K-Water 공모전 프로젝트
[![공모전 표지](물공모전.jpg)]

<div>
  <h2> <strong>프로젝트 표지</strong> </h2>
</div>

![수자원 프로젝트 표지](수자원_표지.png)

<br>

<div>
  <h2><strong>발표자료</strong></h2>
</div>

<ul>
  <li><a href="수자원프로젝트.pdf">수자원 프로젝트 자료</a></li>
</ul>


<br>

<div>
  <h2><strong>🛠 사용 기술 스택</strong></h2>
  <ul>
    <li><strong>언어</strong>: R, SQL</li>
    <li><strong>분석 도구</strong>: Random Forest</li>
    <li><strong>데이터베이스</strong>: Oracle</li>
    <li><strong>데이터 시각화 및 웹 구현</strong>: Rshiny</li>
  </ul>
</div>

<br>

<div>
  <h2><strong>프로젝트 개요</strong></h2>
  기상 및 수문 데이터를 활용하여 머신러닝 기반의 가뭄 예측 시스템을 개발하였습니다.<br>
  특히, R을 활용한 머신러닝 분석과 Oracle 데이터베이스를 활용한 데이터 관리로 성과를 도출했습니다.<br>
  그 결과, 2024년 K-water 대국민 물 빅데이터 공모전에서 장려상을 수상하였습니다.
</div>

<br>

<div>
  <h2><strong>프로젝트 내용</strong></h2>
  <ul>
    <li><strong>1.문제 상황 및 분석 목적</strong>
      <ul>
        <li>대한민국은 여름철 강수 집중 현상으로 인해 가뭄 위험성이 증가하고 있으며, 효율적인 물 자원 관리가 필수적입니다.</li>
        <li>가뭄 예측 모델 개발을 통해 저수량 관리 및 물 자원 활용 계획 수립에 기여하고자 했습니다.</li>
      </ul>
    </li>
    <li><strong>2.데이터 설명</strong>
      <ul>
        <li><strong>활용 데이터:</strong>
          <ul>
            <li>다목적 댐 및 용수댐 데이터 (댐 강우량, 방류량, 저수량 등)</li>
            <li>기상 데이터 (평균기온, 강수량, 일조시간 등)</li>
            <li>SPI6 지수 기반 데이터</li>
          </ul>
        </li>
        <li><strong>데이터 수집 출처:</strong>
          <ul>
            <li>K-water 데이터 포털</li>
            <li>기상청 자료</li>
          </ul>
        </li>
      </ul>
    </li>
    <li><strong>3.모델 개발</strong>
      <ul>
        <li><strong>변수 선택:</strong>
          <ul>
            <li>정보 획득량을 기준으로 예측 성능이 높은 5개의 독립변수를 선정.</li>
          </ul>
        </li>
        <li> <strong>머신러닝 모델:</strong>
          <ul>
            <li>랜덤 포레스트(Random Forest)를 사용하여 모델 개발.</li>
            <li><strong>평가지표 개선:</strong>
              <ul>
                <li>F1 스코어: 0.933</li>
                <li>AUC: 0.955</li>
                <li>정확도: 96.1%</li>
              </ul>
            </li>
          </ul>
        </li>
      </ul>
    </li>
    <li><strong>4.시스템 구현</strong>
      <ul>
        <li>예측 결과를 시각적으로 확인할 수 있는 웹 기반 대시보드 구축.</li>
        <li>사용자 입력을 통해 가뭄 확률을 계산하고 결과를 제공.</li>
      </ul>
    </li>
  </ul>
</div>

<br>

<div>
  <h2><strong>📜 기대 효과</strong></h2>
  <ul>
    <li>조기 경고 시스템을 통한 가뭄 피해 최소화.</li>
    <li>댐 운영 최적화 및 농업용수 조절로 효율적인 물 자원 관리.</li>
    <li>지속 가능한 물 관리 전략 수립에 기여.</li>
  </ul>
</div>

<br>

<div>
  <h2><strong>🏆 성과</strong></h2>
  <ul>
    <li>2024년 K-water 대국민 물 빅데이터 공모전 장려상 수상</li>
    <li>본 프로젝트는 높은 데이터 활용도와 예측 성능을 인정받아 수상하였습니다.</li>
  </ul>
</div>

