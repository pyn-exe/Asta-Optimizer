# Asta-Optimizer
A performance Magisk module that auto-detects and tunes CPU, memory, and I/O on boot.

Module Features
•Automatic performance script, based on dumpsys
•Reduces Jitter and Latency
• Sets/verifies CPU governor to schedutil
• Syncs CPU frequency policy min/max with hardware limits
• Memory tuning — swappiness, cache pressure
• Sets mq-deadline I/O scheduler on compatible devices
• Safely skips unsupported values — no crashes
