# sar

> 다양한 Linux 하위 시스템의 성능을 모니터링합니다.
> 더 많은 정보: <https://manned.org/sar>.

- 물리적 장치에 발행된 I/O 및 전송 속도를 1초 간격으로 보고 (종료하려면 `<Ctrl c>` 입력):

`sar -b {{1}}`

- 네트워크 장치 통계를 2초 간격으로 총 10회 보고:

`sar -n DEV {{2}} {{10}}`

- CPU 사용률을 2초 간격으로 보고:

`sar -u ALL {{2}}`

- 메모리 사용 통계를 1초 간격으로 총 20회 보고:

`sar -r ALL {{1}} {{20}}`

- 실행 대기열 길이와 평균 부하를 1초 간격으로 보고:

`sar -q {{1}}`

- 페이징 통계를 5초 간격으로 보고:

`sar -B {{5}}`
