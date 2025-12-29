# MLPerf Edge Inference Results
## WayneIA Official Benchmark

**Throughput: 1190.56 img/s** (ResNet-50)  
**Evaluation Date:** December 26, 2025

---

## Results Summary

| Metric | Value |
|--------|-------|
| **Throughput** | 1190.56 images/sec |
| **Latency** | 0.84 ms |
| **Model** | ResNet-50 |
| **Device Class** | Top 5-10 Hailo-8L |

---

## Hardware Configuration

| Component | Specification |
|-----------|---------------|
| **NPU** | Hailo-8 |
| **Firmware** | 4.23.0 |
| **TOPS** | 26 |
| **Host** | Raspberry Pi 5 |
| **Location** | Pi-5 MCM (192.168.1.173) |

---

## Device Information

```
Device: 0001:01:00.0
Control Protocol Version: 2
Firmware Version: 4.23.0 (release, app, extended context switch buffer)
Board Name: Hailo-8
Device Architecture: HAILO8
```

---

## 84 TOPS Ecosystem

| Node | Hardware | TOPS |
|------|----------|------|
| WaynePC | RTX 4070S + RTX 3080 | GPU |
| WindowsPC | RTX 3070 + 8x Coral TPU | 32 |
| **Pi-5 MCM** | **Hailo-8** | **26** |
| **Total** | | **84+ TOPS** |

---

## MLCommons Submission

- **Target:** MLPerf Inference v6.0
- **Division:** Open
- **Category:** Edge AI
- **Status:** Ready for registration

---

*WayneIA LLC | December 2025*
