# I2Cdev-MPU6050-2020-02-25
This is a copy for [XOD](https://xod.io/) patches of **[Jeff Rowberg's MPU6050 I2Cdev Library - 2020-02-25](https://www.i2cdevlib.com/)**

How to use in a **XOD patch**:

````
#pragma XOD error_raise enable

#pragma XOD require "https://github.com/as000fm/I2Cdev-2020-02-25"
#pragma XOD require "https://github.com/as000fm/I2Cdev-MPU6050-2020-02-25"

{{#global}}
#include <I2Cdev.h>
#include <MPU6050.h>

// The following header files already include the MPU6050.h file
//#include <MPU6050_6Axis_MotionApps_V6_12.h>
//#include <MPU6050_6Axis_MotionApps20.h>
//#include <MPU6050_9Axis_MotionApps41.h>
{{/global}}

struct State {
};

{{ GENERATED_CODE }}

void evaluate(Context ctx) {
    //auto inValue = getValue<input_IN>(ctx);
    //emitValue<output_OUT>(ctx, inValue);
}
````
