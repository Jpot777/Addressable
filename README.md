# Addressable
Unity 어드레서블 에셋 시스템 메모리 최적화 공부:)

고품질 게임은 메모리 내외부로 에셋을 효율적으로 스트리밍하는 기능을 필수로 갖추고 있어야 합니다.
메모리는 항상 과도하게 사용되지 않도록 관리해야 하며 특히 프로젝트를 새로운 플랫폼에 이식할 때라면 더 신중하게 관리해야 합니다. Addressable을 사용하면 불필요한 에셋의 로드를 방지하는 약한 참조를 도입하여 런타임 메모리를 개선할 수 있습니다. 약한 참조는 참조된 에셋이 메모리 내부 및 외부에 로드되는 시점을 제어할 수 있음을 의미하며, Addressable 시스템 역시 필요한 모든 종속성을 찾아서 로드하게 됩니다.
