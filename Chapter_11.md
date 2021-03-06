# 第十一章 蜗杆传动

![托森限滑差速器主要工作原理即为蜗杆自锁与传动](https://oss.muzing.top/image/domm_Torsen_V3.1.jpg)

在交错轴间传递运动和动力的一种传动机构

## 11-1 蜗杆传动的类型

### 圆柱蜗杆传动

[GB/T 10089-2018 圆柱蜗杆、蜗轮精度](https://muzing-bucket0.oss-cn-huhehaote.aliyuncs.com/documents/GBT-10089-2018.pdf)

端面 —— 垂直于蜗杆轴线平面

轴面 —— 包含轴线的平面

#### 阿基米德蜗杆（ZA）

端面齿廓：阿基米德螺旋线

轴向齿廓：直线

齿形角：$$\alpha_0 = 20^\circ$$

#### 法向直廓蜗杆（ZN）

端面齿廓：延伸渐开线

法面齿廓：直线

#### 渐开线蜗杆（ZI）

端面齿廓：渐开线

相当于一个少齿数（齿数等于蜗杆头数）、大螺旋角的渐开线斜齿圆柱齿轮

#### 锥面包络圆柱蜗杆（ZK）

非线性螺旋齿面蜗杆

#### 圆弧圆柱蜗杆（ZC）

**特点**：

- 效率高，一般可达 90% 以上
- 承载能力高
- 体积小
- 质量小
- 结构紧凑

### 环面蜗杆传动

蜗杆体在轴向的外形是以凹圆弧为母线所形成的旋转曲面

### 锥蜗杆传动

特点：

- 同时接触的点数较多，重合度大
- 传动比范围大（10 ~ 360）
- 承载能力和效率较高
- 侧隙便于控制和调整
- 能作离合器使用
- 可节约有色金属
- 制造安装简便，工艺性好
- 不对称性，因而正、反转时受力不同，承载能力和效率不同

### 蜗杆传动类型选择的原则

1. 重载、高速、要求效率高、精度高的重要传动，可选用**圆弧圆柱蜗杆**（ZC 蜗杆）传动或**包络环面蜗杆**传动
2. 传动效率高、蜗杆不磨削的大功率传动，可选用**环面蜗杆**传动
3. 速度高、精密、蜗杆头数较多、加工工艺简单，可选用**渐开线圆柱蜗杆**（ZI 蜗杆）传动、**锥面包络蜗杆**（ZK 蜗杆）传动或**法向直廓蜗杆**（ZN 蜗杆）传动
4. 载荷较小、速度较低、精度要求不高或不太重要的传动，要求蜗杆加工简单时，可选用**阿基米德螺圆柱蜗杆**（ZA 蜗杆）传动
5. 要求自锁的低速、轻载的传动，可选用**单头阿基米德圆柱蜗杆**（ZA 蜗杆）传动

## 11-2 普通圆柱蜗杆传动的基本参数及几何尺寸计算

在中间平面上，普通圆柱蜗杆传动相当于齿条与齿轮的啮合传动。故在设计蜗杆传动时，取中间平面上的参数和尺寸为基准，并沿用齿轮传动的计算关系

### 普通圆柱蜗杆传动的基本参数及其选择

#### 模数 $$m$$ 和压力角 $$\alpha$$

蜗杆和蜗轮啮合时，在中间平面上，蜗杆的轴面模数、压力角应与蜗轮的端面模数、压力角相等，即：

$$
m_{a1} = m_{t2} = m
$$

$$
\alpha_{a1} = \alpha_{t2}
$$

ZA 蜗杆**轴向压力角 $$\alpha_a$$** 为标准值（20°）

ZN、ZI、ZK 蜗杆**法向压力角 $$\alpha_n$$** 为标准值（20°）

$$
\tan \alpha_a = \frac{\tan \alpha_n}{\cos \gamma}
$$

#### 蜗杆的分度圆直径 $$d_1$$

**蜗杆的直径系数**：

$$
q = \frac{d_1}{m}
$$

$$d_1$$ 与 $$q$$ 有标准值，以限制蜗轮滚刀的数目与便于标准化

常用的标准模数 $$m$$ 和蜗杆分度圆直径 $$d_1$$ ：查表

#### 蜗杆头数 $$z_1$$

蜗杆头数**少**：传动比可以较大，效率低

蜗杆头数**多**：效率高，加工困难

常取 1、2、4、6

#### 导程角 $$\gamma$$

$$
\tan \gamma = \frac{p_z}{\pi d_1} = \frac{z_1 p_a}{\pi d_1} = \frac{z_1 m}{d_1} = \frac{z_1}{q}
$$

| 字母符号 | 含义                        |
| -------- | --------------------------- |
| $$p_z$$  | 蜗杆导程，$$p_z = z_1 p_a$$ |
| $$p_a$$  | 蜗杆轴向齿距                |

#### 传动比 $$i$$ 与齿数比 $$u$$

$$
i = \frac{n_1}{n_2}
$$

$$
u = \frac{z_2}{z_1}
$$

当蜗杆为主动时，$$i = u$$

#### 蜗轮齿数 $$z_2$$

#### 蜗杆传动的标准中心距 $$a$$

$$
a = \frac{1}{2}(d_1 + d_2) = \frac{1}{2} (d_1 + z_2 m)
$$

### 蜗杆传动的几何尺寸计算

## 11-3 普通圆柱蜗杆传动承载能力计算

### 蜗杆传动的失效形式、设计准则及常用材料

### 蜗杆传动的受力分析

### 蜗杆传动强度计算

设计式：

$$
m^2 d_1 \geq \frac{1.53 K T_2}{z_2 [\sigma_F]} Y_{Fa2} Y_\beta
$$

### 蜗杆的刚度计算

最大挠度 $$y$$：

$$
y = \frac{\sqrt{F_{t1}^2 + F_{r1}^2}}{48 EI} {L^{\prime}}^3 \leq [y]
$$

| 字母符号       | 含义                                                         | 单位              |
| -------------- | ------------------------------------------------------------ | ----------------- |
| $$F_{t1}$$     | 蜗杆所受的圆周力                                             | N                 |
| $$F_{r1}$$     | 蜗杆所受的径向力                                             | N                 |
| $$E$$          | 蜗杆材料的弹性模量                                           | MPa               |
| $$I$$          | 蜗杆危险截面的惯性矩                                         | $$\mathrm{mm^4}$$ |
| $$L^{\prime}$$ | 蜗杆两端支承间的跨距，初步计算可选取 $$L^{\prime} \approx 0.9 d_2$$ | mm                |
| $$[y]$$        | 许用最大挠度，$$[y] = \frac{d_1}{1000}$$                     | mm                |

### 普通圆柱蜗杆传动的精度等级及其选择

[GB/T 10089-2018 圆柱蜗杆、蜗轮精度](https://muzing-bucket0.oss-cn-huhehaote.aliyuncs.com/documents/GBT-10089-2018.pdf)中规定了12个精度等级（1级最高），三个公差组

6 级精度：中等精度机床的分度机构、发动机调节系统及机械师读数装置的精密传动。允许的蜗轮圆周速度 $$v_2$$ > 5 m/s

7 级精度：运输和一般工业中的中等速度（$$v_2$$ < 7.5 m/s）的动力传动

8 级精度：每昼夜只有短时工作的次要的低速（$$v_2 \leq$$ 3 m/s）传动

## 11-4 圆弧圆柱蜗杆传动设计计算

### 概述

ZC蜗杆传动比普通圆柱蜗杆传动的承载能力大，传动效率高，使用寿命长，有逐渐代替后者的趋势

#### 传动特点

可以实现交错轴之间的传动，蜗杆能安装在蜗轮的上、下方或侧面

1. 传动比范围大，可实现 1：100 的大传动比传动
2. 蜗杆与蜗轮的齿廓呈凹凸啮合，接触线与相对滑动速度方向间的夹角大，有利于液体动力润滑油膜的形成，抗胶合能力强，承载能力大
3. 当蜗杆主动时，啮合效率可达 95% 以上，比普通圆柱蜗杆传动的啮合效率提高 10% ~ 20%
4. 中心距的偏差对蜗杆传动的承载能力影响较大（对中心距偏差较敏感）

#### 主要参数及其选择

**（1）齿形角 $$\alpha_0$$**

依据啮合分析，推荐选取齿形角 $$\alpha_0 = 23^{\circ} \pm 2^{\circ}$$

**（2）齿廓圆弧半径 $$\rho$$**

$$
\rho = (0.72 \pm 0.1)h_a^* (\frac{1}{\sin \alpha_0})^{2.2}
$$

实际应用时，推荐按下表（$$m$$ 为模数）

| $$z_1$$ | $$\rho$$ |
| ------- | -------- |
| 1、2    | $$5m$$   |
| 3       | $$5.3m$$ |
| 4       | $$5.5m$$ |

#### 圆弧圆柱蜗杆的参数及几何尺寸计算

TODO

### 圆弧圆柱蜗杆传动强度计算

## 11-5 普通圆柱蜗杆传动的效率、润滑及热平衡计算

### 蜗杆传动的效率

- 啮合摩擦损耗 $$\eta_1$$
- 轴承摩擦损耗 $$\eta_2$$
- 溅油损耗 $$\eta_3$$

当蜗杆主动时：

$$
\eta_1 = \frac{\tan \gamma}{\tan (\gamma + \varphi_v)}
$$

轴承摩擦与溅油摩擦功率损耗不大，一般取 $$\eta_2 \eta_3 = 0.95 \sim 0.96$$

在设计之初，为近似求出蜗轮轴上的转矩 $$T_2$$，$$\eta$$ 值可如下估取：

| 蜗杆头数 $$z_1$$ | 总效率 $$\eta$$ |
| ---------------- | --------------- |
| 1                | 0.7             |
| 2                | 0.8             |
| 4                | 0.9             |
| 6                | 0.95            |

### 蜗杆传动的润滑

### 蜗杆传动的热平衡计算

**热平衡计算原因**：蜗杆传动效率低发热量大，在闭式传动中若热量不能及时散逸，油温将不断升高导致润滑油稀释，进而增大摩擦损失，甚至发生胶合

**计算条件**：单位时间内的发热量等于同时间内的散热量

## 11-6 圆柱蜗杆和蜗轮的结构设计
