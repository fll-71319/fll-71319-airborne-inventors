# Robot Game Programs

## Programming Platform: PyBricks

We use PyBricks for programming our SPIKE Prime robot.
- **Block Coding**: Visual programming for beginners
- **Python**: Text-based programming for advanced control

## Mission Programs

### Completed Missions
- [ ] M01: Surface Brushing (20 points)
- [ ] M14: Forum Delivery (5 points each)

### In Development
- [ ] M02: Map Reveal (10 points each)
- [ ] M03: Mineshaft Explorer (30-40 points)

## Code Organization

```
robot-game/
├── missions/        # Individual mission programs
├── lib/            # Shared functions and utilities
├── attachments/    # Attachment designs and notes
└── test/           # Test programs and calibration
```

## Naming Convention
- Mission programs: `m01_surface_brushing.py`
- Test programs: `test_gyro_turn.py`
- Libraries: `robot_utils.py`

## Robot Configuration
- **Left Motor:** Port A
- **Right Motor:** Port B
- **Attachment Motor:** Port C
- **Color Sensor:** Port D
- **Distance Sensor:** Port E
- **Gyro:** Built-in

## Tips
1. Always test programs multiple times
2. Document what each program does
3. Save working versions before making changes
4. Use consistent starting positions