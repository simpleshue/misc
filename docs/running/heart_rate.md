---
title: Heart Rate
parent: Running
---

1. TOC
{:toc}

Heart rate is probably the most accessible statistics for most runners.

## Max and Resting Heart Rate

Before using it to guide your workout, first, we need to understand the basics, max and resting (min) heart rates.

### Mysterious max heart rate formulas

There are many formulas to predict one's max heart rate. To name a few

* Haskell & Fox(1971): `200 - age`
* Tanaka, Monahan, & Seals (2001): `208 − (0.7 × age)`

These are all general predication based on a large number of samples. However, everyone is special. You might be surpised to see your HR to spike to 200 during an interval training. Some recent research suggests that human's max heart rate is close to 300!

To have a better estimate of your max HR. Professionally, it can be measured by increasing exercise intensity gradually until your heart has reached its max output (certain changes in heart function are detected on the ECG monitor).

A practical meassurement can be taken using 1-mile test:

1. Warmup 1-2 miles
1. Run one mile on a track at tempo pace. Run an all-out effort in the last 400 meters.
1. Sprint the last 100 meters as fast as possible.

Or, a more gradual test

1. Warm up by jogging for 10-15 minutes.
1. Run 1 mile at 10k or Lactate threshold pace.
1. Without stopping, increase your pace by 2 seconds every 200 meters until one can't keep increasing the pace.

The highest heart rate during the test can be used as the max heart rate.

### Resting heart rate

{: .note }
Resting heart rate is a much less known term, but I found it very important for runners.

Resting heart rate is an indicator for one's general health. While being in the general range, relatively lower heart rate is considered to be a better physical condition (e.g., see the heart rate reserve below).

Resting heart rate can be measured easily. The easiest way is to measure it right after wake-up, while you are still laying flat.

With such as morning indicator, it gives you a general sense of one's overall physical condition, and one may want to adjust the training plan accordingly if the reading is higher as normal. For runners, it can give some indication on how well is the recovery to avoid over-training.

Personally, I would reduce or even avoid hard workout when the morning resting heart rate is abnormally high. (See [Patterns](#patterns) below for more discussion on how various factors can effect resting heart rate).

### Heart rate reserve

Heart rate reverse describes the room one can push during exercise. So, don't be sad when one find a high Max Heart Rate. It means you have higher capacity!

```text
HR reserve = HR max − HR rest
```

### Heart Rate Variability(HRV)

HRV is a recent popular statistics, *supported* by modern sport watches. It is the *fluctuation* in the time intervals between adjacent heartbeats.

HRV is not ONE metric. It can be defined/measured by different durations (e.g., 24 hours, 5 minutes, or even shorter), or different frequency. All these can mean very different things when people are talking about "HRV".

HRV is correlated with stress, general health (e.g., inflammation), which is similar to resting heart rate. However, HRV is much harder to measure.

But, there is a catch. HRV measurement is very specific to the hardware and vendor.

* Different HR sensor can have different accuracy in terms of the measuring frequency. All sensors use some sort of approximations (e.g., comparing HRV from Apple Watch and Garmin may not make any sense).
* Some vendor often collect HRV from its own users and form a comparison of one's HRV to all others. So the HRV number is a relative comparison with others. Such commparison can also shift as the user base change overtime.

Never the less, HRV is still a good measurement if you know what you are looking at. To me, it is probably only useful to compare one's own HRV history over a relatively short time horizon.

## Zones

| Zone     |      % of Max HR      |  Notes |
|----------|:---------------------:|------:|
| 5 - Anaerobic |  90-100% | Can only sustain for < 1 minute. Faster than 5k. |
| 4 - Lactate threshold |   80-90%   |   Can sustain for < 1 hour. 10k/Intervals/Fartleks. |
| 3 - Tempo | 70-80% |  Challenging to hold a conversation. Tempo/Half marathon/Full marathon.  |
| 2 - Aerobic | 60-70% |    Conversational pace. Easy run pace. |
| 1 - Easy | 50-60% |    Very easy |

By far, the best chart I have found is from `Fluid Athletics`:
  ![zone_chart]({{ site.baseurl }}/assets/images/running/zone_chart.jpeg)

### "Zone 2" training

There is a lot of popularity nowadays on training in Zone 2. Addmittedly, it is a safer training zone, which does not put a lot of preassure on your body. It is also proven to bring a lot of benefit to VO2Max, lowering rest HR, incrase mitochondria.

However, all above benefits are also achievable through exercising in other zones, though with different efficiency and other benefits (e.g. speed). The main benefit in my opinion is to prevent/reduce injury. With lowe training stress, the body is more likely to recovery quickly, which is the key to continuous and compounded improvement.

However, we should also not underestimate the need for other zones. I would argue that proper training in other higher zones is also very important when one is pursuing better performance. You will get what you train for, especially during races. Different muscle groups will be recruited at different paces, so definite mix in a good amount of other zones if you goal is better race performance.

### New runners

For new runners, often it is  hard to keep HR low enough in the desired zone while maintaining some meaningful pace. You probably need to relax the heart rate restriction, and allow your body to adapt to running over (see [Progressive Overloading](../training_plan_design/#progressive-overloading) and [Training Cycles](../training_plan_design/#cycles) about adaptation).

## Patterns

### Things That Increases Resting HR

* Heat
* Humidity
* Dehydration
* Hard/long workout
* Sickness
* Tireness
* Stress
* Alcohol

### Things That Decreases Resting HR

* Easy/Zone-2 run - faster pace (e.g., lactate threshold) running won't necessarily reduce HR.
* Good rest

## Heart Rate vs Lactate Level

Lactate threshold training is a hot topic among running community, where blood lactate level is used as an indicator.

Lactate is a byproduct of anaerobic activity, while it also serves as a fuel when enough oxygen is available. In the meantime, it can reduce muscle functionalities by lower the blood's PH level. In the extreme case, it reduce the body's ability to move CO2 from muscle into blood, which significantly impacts performance. This is also one reason that one should have proper warmup to avoid early cumulation of lactate.

Many people plot a pace:lactate-level plot and try to find the turning point in the plot, and determine the pace zone where one can train to efficiently improve one tolerance to lactate.

So far so good, except it is much harder to get an accurate rating. One can invest to buy some device to sample the blood lactate level a few time in a workout, but it is far less frequent than heart rate.

Personally, I would rather choose [Progressive Interval Test](../testing/#progressive-interval-test), which is much easier to carry out and eary to observe how effectively you are moving the curve (i.e., improving your running efficiency).

And to find your one's Lactate Threshold speed, you could get an estimate using the [30-min Test](../testing/#30-min-test).

{. note}
When I draw speed:HR plot, I got a pretty straight line, which makes it impossible to find the “inflection” point like when using lactate level.
