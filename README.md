Fixes & Improvements

✅ Fixed Raycasting Issues

    Ensures raycasting detects the correct clickable parent object.

✅ Improved Dragging Logic

    Uses delta movement (deltaX, deltaY) to adjust model position properly.

✅ Avoids Confusion with pointerId

    Instead of tracking pointerId, we just check draggingModel.

✅ Cleaner Code & Better Scaling

    Adjusts movement speed using a 0.001 scaling factor.
