# Elastic Load balancing

Elastic Load Balancing(ELB) 은  수신되는 애플리케이션 트래픽을 여러 EC2 인스턴스에 자동으로 배포합니다. 따라서 애플리케이션의 내결함성을 크게 높이고, 애플리케이션 트래픽을 배포하는데 필요한 로드 밸런싱 용량을 원활하게 제공할 수 있습니다.

Elastic Load Balancing 은 고가용성, 자동 조정 및 강력한 보안이 모두 적용된 두 가지 유형의 로드 밸런서를 제공합니다. 여기에는 애플리케이션 또는 네트워크 수준 정보에 따라 트래픽을 라우팅하는 Classic Load Balancer 와 요청 콘텐츠를 포함하는 고급 애플리케이션 수준 정보에 따라 트래픽을 라우팅하는 Application Load Balancer 가 포함됩니다. Classic Load Balancer 는 고급 라우팅 기능, 마이크로서비스 및 컨테이너 기반 아키텍처가 필요한 애플리케이션에 적합합니다. Application Load Balancer 를 사용하면 트래픽을 여러 서비스에 라우팅하거나 동일한 EC2 인스턴스에 있는 여러 포트에 걸쳐 로드를 밸런싱할 수 있습니다.
