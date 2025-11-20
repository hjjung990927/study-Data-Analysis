# Data-Analysis
<a name="readme-top"></a> 

### Data Analysis
- 원시(원본 그대로) 데이터를 분석하여 인사이트(가시성 증가 및 깊은 이해)로 변환하는 작업이다.
- 문제를 해결하기 위해 데이터를 사용해서 흐름 및 방향을 찾는 기술이다.
- 데이터 분석을 통해 비지니스 프로세스를 구성하고, 의사 결정을 개선하며, 비지니스 성장을 증진할 수 있다.

<img width="1430" height="570" alt="architecture" src="https://github.com/user-attachments/assets/f0f131c9-afa8-4c2c-917d-fe4a4c743b52" />
** <sub>ETL은 Extract(추출), Transform(변환), Load(적재)를 의미한다. 여기 저기 흩어진 데이터를 하나로 모으기 위한 결합 과정이다.</sub>

### 기초 통계 (Basic statistics)
📌 통계는 아직 발생하지 않은 일을 예측하기 위해 사용한다.
- 통계학을 공부하는 데 있어 필요한 기본 개념이고,  
  수량적인 비교를 기초로 많은 사실을 관찰하고 처리하는 방법을 연구하는 학문이다.
- 불균형 데이터를 대상으로 규칙성과 불규칙성을 발견한 뒤 실생활에 적용할 수 있다.  

<img width="1690" height="999" alt="statistics01" src="https://github.com/user-attachments/assets/6fd4b300-d5da-4ab3-a16f-524d9f1084ec" />

#### 변량 (Variable)
- 자료의 수치를 변량이라고 하며, 이는 데이터의 값을 의미한다.

#### 계급 (Class)
- 변량을 일정 간격으로 나눈 구간을 의미한다.
- 변량의 최소값과 최대값을 잘 고려해서 계급을 정해야한다.
- 예를 들어, 계급이 (150, 160]일 경우, 151 ~ 160이 계급에 속한다. 즉 소괄호는 구간 미포함, 대괄호는 구간 포함이다.

#### 도수 (Frequency)
- 각 계급에 속하는 변량의 개수를 의미한다.

#### 상대 도수 (Relative frequency)
- 각 계급에 속하는 변량의 비율을 의미한다.

#### 도수분포표(Frequency table)
- 주어진 자료를 계급별로 나눈 뒤 각 계급에 속하는 도수 및 상대 도수를 조사한 표이다.
- 구간별 분포를 한 번에 알아보기 좋지만 계급별 각 변량의 정확한 값이 생략되어 있다.

#### 히스토그램 (Histogram)
- 도수분포표를 시각화한 그래프이다.

#### 산술 평균 (Mean)
- 변량의 합을 변량의 수로 나눈 값을 의미한다.

<img width="171" height="63" alt="mean" src="https://github.com/user-attachments/assets/30719583-0732-4aeb-aa9d-30a2631b9ea7" />

#### 편차 (Deviation)
- 변량에서 평균을 뺀 값이다.
- 각 변량의 편차를 구한 뒤 모두 합하면 0이 되기 때문에 편차의 평균은 구할 수 없다.

#### 분산 (Variance)
- 변량이 평균으로부터 떨어져있는 정도를 보기 위한 통계량이다.
- 편차에 제곱하여 그 합을 구한 뒤 산술 평균을 낸다.

<img width="305" height="64" alt="variance" src="https://github.com/user-attachments/assets/315dcb20-3246-4451-a3d0-0b50807701e7" />

#### 표준편차 (Standard deviation)
- 분산의 제곱근이며, 관측된 변량의 흩어진 정도를 하나의 수치로 나타내는 통계량이다.
- 표준편차가 작을 수록 평균 값에서 변량들의 거리가 가깝다고 판단한다.

<img width="205" height="40" alt="standard_deviation" src="https://github.com/user-attachments/assets/108c2b5e-815b-43d5-9726-a80484cc18a7" />

#### 확률변수 (Random variable)
- 머신러닝, 딥러닝 등 확률을 다루는 분야에 있어서 필수적인 개념이다.
- 확률(probability)이 있다는 뜻은 사건(event)이 있다는 뜻이며,  
  시행(trial)을 해야 시행의 결과인 사건(event)이 나타난다.
- 시행(trial)을 해서 어떤 사건(event)이 나타났는지에 따라 값이 정해지는 변수이다.
- 알파벳 대문자로 표현하며, X, Y, Z 또는 X<sub>1</sub>, X<sub>2</sub>, X<sub>3</sub>과 같이 표현한다.
- 확률변수는 집합이며, 원소를 확률변수값(Value of random variable)이라고 표현한다.  
  확률변수에서 사용한 알파벳의 소문자를 사용한다.
- Y = { y<sub>1</sub>, y<sub>2</sub>, y<sub>3</sub> }, 이 때 Y는 확률변수이고 원소인 y<sub>1</sub> ~ y<sub>3</sub>은 확률변수값이다.

![random_variable](https://github.com/user-attachments/assets/9a2a2edd-0ead-4519-9629-dd89ded286ef)

#### 범주형 확률변수 (Categorical random variable)
- 범주형 확률변수값은 수치가 아닌 기호나 언어, 숫자등으로 표현하고, 기호나 언어는 순서를 가질 수도 있다.
- 유한집합으로 표현한다. 유한집합은 원소의 수가 유한한 집합을 의미한다.
- {앞면, 뒷면}, {동의, 비동의}, {선택, 미선택}, {봄, 여름, 가을, 겨울}

#### 이산형 확률변수 (Discrete random variable)
- 이산형 확률변수값은 수치로 표현하고 셀 수 있는 값이다. 이를 더 넓은 범위로,  
  양적 확률변수 또는 수치형 확률변수라고도 부른다.
- 유한집합 또는 셀 수 있는 무한집합으로 표현한다. 무한집합은 원소의 수가 무한한 집합을 의미한다.
- {0, 1, 2, 3}, {10, 20, 30}, {1, 2, 3, ...}, {100, 1000, 10000}

#### 연속형 확률변수 (Continuous random variable)
- 연속형 확률변수는 구간을 나타내는 수치로 표현한다. 이를 더 넓은 범위로,  
  양적 확률변수 또는 수치형 확률변수라고도 부른다.
- 셀 수 없는 무한집합으로 표현한다.
- 128.56 < X < 268.56

#### 확률분포 (Probability distribution)
- 사건에 대한 확률변수에서 정의된 모든 확률값의 분포이며, 서로 다른 모든 결과의 출현 확률을 제공한다.
  
> <strong>1) 동전 던지기 (시행)</strong>  
> <strong>2) { 0, 1 } (확률변수와 확률변수값)</strong>  
> <strong>3) 완벽한 형태의 동전일 경우 확률 분포</strong>  
>
> <img width="259" height="186" alt="probability_distribution01" src="https://github.com/user-attachments/assets/6fe4583b-4050-40e1-b86f-4ed329339088" />


  
> <strong>1) 1 ~ 12까지 새겨진 주사위 던지기 (시행)</strong>  
> <strong>2) { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12 } (확률변수와 확률변수값)</strong>  
> <strong>3) 완벽한 형태의 주사위일 경우 확률 분포</strong>  
>
> <img width="474" height="190" alt="probability_distribution02" src="https://github.com/user-attachments/assets/e3b2d3cd-379c-4b9c-9c68-f866bd20b36f" />

#### 확률분포표 (Probability distribution table)
- 확률변수의 모든 값(원소)에 대해 확률을 표로 표시한 것이다.
- 범주형 또는 이산형 확률변수의 확률분포를 표현하기에 적합한 방식이다.

#### 확률분포함수 (Probability distribution function)
- 확률변수의 분포를 나타내는 함수로서, 확률변수의 확률변수값이 나올 확률을 나타내는 함수이다.
- 확률질량함수, 확률밀도함수 등의 함수가 있다.

#### 확률질량 함수 (Probability mass function, pmf)
- 확률변수 X의 분포를 나타내는 함수로서, x<sub>i</sub>가 나올 확률이다.
- 확률변수의 값을 매개변수로 전달받고, 해당 값이 나타날 확률을 구해서 리턴하는 함수이다.
- 범주형 확률변수와 이산형 확률변수에서 사용된다.
- 확률변수에서 각 값에 대한 확률을 나타내는 것이 마치 각 값이 "질량"을 가지고 있는 것처럼 보이기 때문에 확률질량 함수로 불린다.

> 확률질량 함수 f는 확률변수 X가 x를 변수값으로 가질 때의 확률이다.  
> <img width="157" height="33" alt="pmf01" src="https://github.com/user-attachments/assets/05e1b8bc-5a82-4816-9a31-416a942f4ba1" />
> <img width="113" height="53" alt="pmf02" src="https://github.com/user-attachments/assets/2cff693e-8187-4407-b1f2-4af491da085a" />
> <img width="122" height="25" alt="pmf03" src="https://github.com/user-attachments/assets/24a5952d-dc18-4e20-9fde-9723304f71c9" />

#### 무한대 (Infinity)
- 끝없이 커지는 상태를 의미하고 기호로 ∞를 사용한다.

#### 무한소 0 (Infinitesimal)
- 거의 없다는 의미이고, 0에 매우 근접하지만 0이 아닌 상태를 의미한다.

#### 미분 (Differential)
- 기울기는 독립변수가 종속변수에 미치는 영향력의 크기를 의미한다.
- 변경 전의 독립변수 x<sub>1</sub>이라는 점과 변경 후의 x<sub>2</sub>라는 점을 지나는 직선의 기울기가 바로 변화에 대한 속도이다.
- 즉, 직선의 기울기가 4로 구해졌다면,  
  종속변수가 독립변수의 변화에 4배 속도로 변화된 것이다.
- 이 때, 두 점 사이가 무한히 가까워지면,  
  결국 거의 한 점과 같은 점에 대한 접선의 기울기가 되고 이는 순간적인 변화량이다.
- 미분을 통해서 독립변수가 미세하게 변화할 때 순간적으로 종속변수가 얼마나 빠르게 변화하는 지를 알 수 있다.

#### 적분 (Integral)
- 선분 = 높이(길이), 면적 = 가로 X 높이
- 면적을 구할 때 여러 사각형으로 나눈 뒤 합하여도 전체 면적이 나온다.
- 가로가 무한소 0인 사각형 즉, 선분과 거의 비슷한 사각형을 쌓은 뒤, 각 면적을 모두 합하는 것이 적분이다.

#### 확률밀도 함수 (Probability density function, pdf)
- 확률변수 X의 분포를 나타내는 함수로서, 특정 구간에 속할 확률이고 이는 특정 구간을 적분한 값이다.
- 확률변수값의 범위(구간)를 매개변수로 전달받고, 범위의 넓이를 구해서 리턴하는 함수이다.
- 연속형 확률변수에서 사용된다.
- 전체에 대한 확률이 아닌 구간에 포함될 확률을 나타내기 때문에 구간에 따른 밀도를 구하는 것이고,  
  이를 통해 확률밀도 함수라 불린다.

- ※ CDF(cumulative distribution function): 이하 확률

> 확률밀도 함수 f는 특정 구간에 포함될 확률을 나타낸다.  
> <img width="243" height="56" alt="pdf01" src="https://github.com/user-attachments/assets/78e0547a-a5e6-4e1e-964f-88c6bd784fb6" />
> <img width="122" height="25" alt="pdf02" src="https://github.com/user-attachments/assets/5dfc58d2-fa62-4175-8778-52dbe71e06d7" />
> <img width="142" height="59" alt="pdf03" src="https://github.com/user-attachments/assets/f3e41a28-f01c-442d-80d6-0f3c1a5af087" />
> <img width="127" height="32" alt="pdf04" src="https://github.com/user-attachments/assets/3c73eb67-1385-4c8c-84a9-cfcde10ee2c9" />

#### 정규분포 (Normal distribution)
- 모든 독립적인 확률변수들의 평균은 어떠한 분포에 가까워지는데, 이 분포를 정규분포라고 한다.
- 즉, 비정규분포의 대부분은 극한상태에 있어서 정규분포에 가까워진다.

<img width="400px" alt="normal_distribution01" src="https://github.com/user-attachments/assets/5823cc07-a456-4363-979d-3659aee7ee1a" /> <img width="400px" alt="normal_distribution02" src="https://github.com/user-attachments/assets/5a71a81e-f72b-4e12-8199-240c09e760d5" />
- 평균 μ(mu)와 표준편차 σ(sigma)에 대해 아래의 확률밀도함수를 가지는 분포를 의미한다.

<div style="display: flex">
    <div>
      <img width="230px" alt="normal_distribution03" src="https://github.com/user-attachments/assets/708ad938-3667-4300-9cb5-fc2a67f7b38f" />
    </div>
    <div>
      <img width="700px" alt="normal_distribution04" src="https://github.com/user-attachments/assets/7070228d-498e-4f79-846b-b9c8a9de8ef3" />
    </div>
</div>

#### 표준 정규분포 (Standard normal distribution)
- 정규분포는 평균과 표준편차에 따라서 모양이 달라진다.

<img width="545" height="339" alt="standard_normal_distribution01" src="https://github.com/user-attachments/assets/80c2484e-3fb5-4bbf-9f62-32c5e0ff0a68" />

- 정규분포를 따르는 분포는 많지만 각 평균과 표준편차가 달라서 일반화할 수 없다.
- N(μ, σ) = N(0, 1)로 만든다면 모두 같은 특성을 가지는 동일한 확률분포로 바꿔서 일반화할 수 있다.
- 따라서 일반 정규분포를 표준 정규분포로 바꾼 뒤 표준 정규분포의 특정 구간의 넓이를 이용해서 원래 분포의 확률을 구할 수 있다.

<img width="501" height="376" alt="standard_normal_distribution02" src="https://github.com/user-attachments/assets/029d3fdf-15ff-41c8-873e-a6b3ca1647ad" />

#### 표준화 (Standardization)
- 다양한 형태의 정규분포를 표준 정규분포로 변환하는 방법이다.
- 표준 정규분포에 대한 값(넓이)를 이용해 원래 분포의 확률을 구할 수 있다.  

<img width="136" height="60" alt="standardization01" src="https://github.com/user-attachments/assets/2d8ad0cb-508b-4f2e-814d-2bf15bce6ccd" />

<img width="679" height="644" alt="standardization02" src="https://github.com/user-attachments/assets/1e02943c-e010-43fa-a883-185d06d2e7f9" />

#### 모집단과 모수 (Population and population parameter)
- 모집단이란, 정보를 얻고자 하는 대상의 전체 집합을 의미한다.
- 모수란, 모집단의 수치적 요약값을 의미한다. 평균 또는 표준편차와 같은 모집단의 통계값을 모수라고 한다.

#### 표본과 샘플링 (Sample and Sampling)
- 표본이란, 모집단의 부분집합으로서 표본의 통계량을 통해 모집단의 통계량을 추론할 수 있다.
- 모집단의 통계량을 구할 수 없는 상황 즉, 전수 조사가 불가능한 상황에서 임의의 표본을 추출하여 분석한다.
- 이렇게 표본(sample)을 추출하는 작업을 샘플링(sampling)이라고 한다.

### Numpy
- 머신러닝 애플리케이션에서 데이터 추출, 가공, 변환과 같은 데이터 처리 부분을 담당한다.
- 넘파이 기반의 사이킷런을 이해하기 위해서는 넘파이는 필수이다.
- 사이킷런은 직관적이고 간결하기 때문에 상대적으로 개발하기 쉽지만 넘파이는 양도 많고 배울 것도 많다.
- 넘파이 전체를 다 이해하고 공부하는 것은 머신러닝을 포기하게 만들기 때문에  
  기본 문법과 중요 API만 이해하는 것이 전략적으로 좋다.

#### ndarray
- N차원(n-dimension) 배열 객체이다.
- 파이썬 list를 array() 메소드에 전달하면 ndarray로 변환되고  
  넘파이의 다양하고 편리한 기능들을 사용할 수 있게 된다.
- 반드시 같은 자료형의 데이터만 담아야 한다.  

<img width="791" height="269" alt="numpy1" src="https://github.com/user-attachments/assets/6546bc70-2e05-4c32-a224-92a5c3bcb32f" />

#### astype()
- ndarray에 저장된 요소의 타입을 변환시킬 때 사용한다.
- 대용량 데이터 처리 시, 메모리 절약을 위해 사용한다.

#### axis
- 축의 방향성을 표현할 때, axis로 표현할 수 있다.  
  
<img width="1045" height="276" alt="numpy2" src="https://github.com/user-attachments/assets/71bb4dc2-0c42-4b37-8a7b-50191196e2cb" />

#### arange(), zeros(), ones()
- ndarray의 요소를 원하는 범위의 연속값, 0 또는 1로 초기화할 때 사용한다.

### reshape()
- ndarray의 기존 shape를 다른 shape로 변경한다.

#### Indexing
- 특정 위치의 데이터를 가져오는 것
- 위치 인덱싱(Location indexing)
- 슬라이싱(Slicing)
- 팬시 인덱싱(Fancy indexing)
- 불린 인덱싱(Boolean indexing)

#### Sorting
- 모두 오름차순 정렬이며, 내림차순은 오름차순 정렬 후 [::-1]을 붙여 사용한다.

### 벡터
- 데이터 과학에서 벡터란 숫자 자료를 나열한 것을 의미한다.
- 벡터는 공간에서 한 점을 나타낸다.
- feature 1개당 1차원이고, feature가 3개면 3차원이다.
- 이 때, 1차원 좌표평면에서는 열벡터를 표현할 수 있으며, 2차원 좌표평면에서는 2열 데이터를 표현할 수 있게 된다.

#### 내적 (Dot product)
- 두 벡터의 성분들의 곱의 합  

<img width="467" height="121" alt="dot_product" src="https://github.com/user-attachments/assets/8a94a5ca-0b6b-4005-9f6d-a94338ec9fba" />

#### 선형대수 (Linear Algebra)
- 선형 방정식을 풀기 위해 배우는 학문이다.
- 4x = 16일 경우, 좌항의 4를 우항으로 넘겨서 x라는 것을 구할 수 있고,  
  방정식 1개만으로 해를 구할 수 있다.
- y = 2x + 5일 경우, 미지수가 2개이기 때문에 방정식이 2개 필요하다.
- 이러한 연립 방정식을 표현할 때 쉽게 표현하기 위해서 선형대수를 배운다.

#### 과결정계(Overdetermined system)
- 미지수보다 방정식 더 많이 있는 연립방정식으로서 보통 해가 존재하지 않고, 만약 존재하더라도 유일하지 않다.
- 3차원 공간에 존재하는 2차원 평면 4개에서는 3차원 공간의 해를 구하기는 어렵다.  
  3차원 공간에 있는 평면들의 교점이 1개라는 조건을 만족하려면, 4번째 평면이 정확하게 이 교점을 지나야 하는데, 이는 결국 해를 찾는 것이 불가능에 가깝기 때문이다.
- 결국 차원을 넘어간 평면에 위치한 점들 중, 교점과 가장 가까운 거리의 점을 찾고, 투영을 통해 해당 차원으로 축소해야 해를 찾을 수 있으며, 이 때 해의 근사치를 구할 수 있다.   
  투영시, 원본 값에서 어느정도의 loss(손실)가 발생하지만 이를 감안하더라도 근사값을 구하기 위해 수행한다.

### 판다스 (Pandas)
- 데이터 처리 라이브러리 중 가장 인기있는 라이브러리이다.
- 2차원 데이터(테이블, 엑셀, CSV 등)를 효율적으로 가공 및 처리할 수 있다.

#### 판다스 구성 요소
- DataFrame: 행과 열로 구성된 2차원 Dataset을 의미한다.
- Series: 1개의 열로만 구성된 열벡터 Dataset을 의미한다.
- Index: DataFrame과 Series에서 중복없는 행 번호를 의미한다.

#### DataFrame()
- dict를 DataFrame으로 변환하고자 할 때 DataFrame 생성자에 전달한다.
- 컬럼명을 추가하거나 인덱스명을 변경하는 등 다양하게 설정할 수 있다.

#### read_csv()
- csv 파일을 DataFrame으로 읽어온다.

#### head()
- 전체 데이터 중 앞부분 일부를 가져온다.

#### tail()
- 전체 데이터 중 뒷부분 일부를 가져온다.

#### iloc[], loc[]
- 원하는 행 또는 열을 가져온다.
- iloc은 인덱스 번호로 가져오고, loc은 인덱스 값 또는 컬럼명으로 가져온다.

#### describe()
- 숫자형 데이터의 개수, 평균, 표준편차, 최소값, 사분위 분포도(중앙값: 50%), 최대값을 제공한다.
- 25번째 백분위수와 75번째 백분위수를 기준으로 정상치의 범위를 설정할 수 있다.

### Visualization (시각화)
#### https://matplotlib.org/stable/plot_types/index.html

<img width="919" height="228" alt="visual01" src="https://github.com/user-attachments/assets/86b20534-abfa-4a50-95b0-ef233ba64f9e" />
<img width="917" height="284" alt="visual02" src="https://github.com/user-attachments/assets/b9539fc1-baa2-45b8-b21b-37471b1b0148" />
<img width="921" height="249" alt="visual03" src="https://github.com/user-attachments/assets/aec03c78-57c4-428f-9d13-9451b4a0df75" />

##### 범주형(상품 카테고리: 생활용품, 전자제품, 의류, 학생 수준: High, Medium, Low, 측정년도: 2021, 2022, ...)
- 바이올린 차트
- 스캐터 플롯
- 막대 차트
- 누적 막대 차트
  
##### 수치형(학번: 1, 2,..., 구매 횟수: 157, 789, ..., 가격: 1280.15648, ..., 식물의 높이: 10.251, ...)
- 막대 차트(숫자가 적을 경우)
- 선 그래프(숫자가 많을 경우)
- 바이올린 차트
- 스캐터 플롯
- 히스토그램
- KDE

### RFM 분석  

사용자별로 얼마나 최근에, 얼마나 자주, 얼마나 많은 금액을 지출했는지에 따라 사용자들의 분포를 확인하거나  
사용자 그룹(또는 등급)을 나누어 분류하는 분석 기법이다. 구매 가능성이 높은 고객을 선정할 때 용이한 데이터 분석 방법이며,  
사용자들의 평소 구매 패턴을 기준으로 분류를 진행하기 때문에 각 사용자 그룹의 특성에 따라  
차별화된 마케팅 메세지를 전달할 수 있다.  

- Recency: 얼마나 최근에 구매했는가
- Frequency: 얼마나 자주 구매했는가
- Monetary: 얼마나 많은 금액을 지출했는가

### 🛒이커머스 플랫폼 A기업의 RFM 분석
📌이커머스: 온라인을 통해 상품이나 서비스를 사고파는 서비스 (쿠팡, 11번가, 네이버 등)

 
<table style="width: 50%; margin-left:10px;">
    <caption>고객 분석</caption>
    <tr>
        <th>사용자</th>
        <th>구매 횟수</th>
        <th>구매 금액</th>
        <th>최근 구매일</th>
    </tr>
    <tr>
        <th>정희준</th>
        <th>45</th>
        <th>1,980,000</th>
        <th>2개월 전</th>
    </tr>
    <tr>
        <th>홍길동</th>
        <th>2</th>
        <th>45,320</th>
        <th>1년 전</th>
    </tr>
</table>

👓"정희준" 고객을 VIP로 선정해서 연말 선물을 전달하면, 충성심있는 고객으로 유지할 수 있는 전략을 세울 수도 있고, <br><br> 🎫"홍길동" 고객에게 할인 쿠폰 등 자사의 플랫폼을 이용할 거리를 전달함으로써, 구매를 유도할 수 있는 전략을 세울 수도 있다.

RFM을 통해 사용자 특성별로 다른 정책을 적용하고 서비스를 더 잘 사용하도록 유도하는 전략을 세울 수 있다.

#### 정규화 (Nomalization)   
값의 범위를 0~1 사이로 변환시켜 모든 컬럼의 데이터가 평등해진다.
서로 다른 단위의 값은 비교 대상이 될 수 없다. 예를 들어, 80kg과 180cm는 비교할 수 없기 때문에 정규화를 사용해서 비교한다.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
