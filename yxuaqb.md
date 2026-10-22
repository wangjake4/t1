代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.yanxiufei.cn/Article/details/gt2ugjymiml.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shuidangran.top/Article/details/gt2iphrxais.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.redwolf501.top/Article/details/gt2bhngkujb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cdnleiting.top/Article/details/gt2ehxeosir.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gt2qxxvmsfv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gt2dqrylbfn.html

Go:   name := "Alex"; age := 20
来源：http://dali.sysykeji.top/Article/details/gt2qwoarldg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.kuanghao11.cn/Article/details/gt2tqodraiy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2splftxil.html

[A03] 常量定义
来源：http://dali.zhongyouzk.top/Article/details/gt2aacgofpa.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daria6918.cn/Article/details/gt2wwyufcwe.html

PHP:  const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2rdljzqrn.html

JS:   const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2feyywjbu.html

TS:   const PI: number = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2jzyvlauz.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uegrmlos.html

Go:   const PI = 3.14159
来源：http://dali.yongpay.top/Article/details/gt2kauhzkck.html

Ruby: PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gt2qnqyacpk.html

C#:   const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjjnwvub.html

[A04] 判断变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucrpyyvt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gotoacloud.top/Article/details/gt2ckuzrsbq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuanzhike.top/Article/details/gt2dctcmxah.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.mhx1999.top/Article/details/gt2yvecnpqb.html

TS:   typeof x; x instanceof Date
来源：http://dali.xuanzx.com/Article/details/gt2prshgmlq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ybcxt.top/Article/details/gt2yxiudpiy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhongyouzk.top/Article/details/gt2rmzvjbbw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdfunmyw.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenzaomai.com/Article/details/gt2mqxhzzop.html

[A05] 整数除法与取模
来源：http://dali.cdnleiting.top/Article/details/gt2cldmhave.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.aizwys.cn/Article/details/gt2ngslijcq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2lwctuzcs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2hexkhoop.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2ooxhguxw.html

Java: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2xszophjk.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoyzavj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkyitcis.html

C#:   7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2rdulftlf.html

[A06] 字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2rquuqxgz.html

Py:   int("42"); float("3.14")
来源：http://dali.yj202588.top/Article/details/gt2andravrc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinqigfzy.top/Article/details/gt2ayfappnf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daxiang520.top/Article/details/gt2kwpkdsgm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckhnjzcd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.daria6918.cn/Article/details/gt2icmasbmb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jianghu66.top/Article/details/gt2gdcmaxaf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2harihpha.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xylfe.cn/Article/details/gt2trzbprvg.html

[A07] 数字转字符串
来源：http://dali.yj202588.top/Article/details/gt2zcftocxa.html

Py:   str(42)
来源：http://dali.yueranfly.top/Article/details/gt2seshevng.html

PHP:  (string) 42; strval(42)
来源：http://dali.shzxlz.cn/Article/details/gt2ijwuydkf.html

JS:   String(42); (42).toString()
来源：http://dali.yj20258.top/Article/details/gt2tluywisi.html

TS:   String(42)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdxbdwin.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.redwolf501.top/Article/details/gt2fmoqpxmu.html

Go:   strconv.Itoa(42)
来源：http://dali.smart0.xyz/Article/details/gt2ebabuwxe.html

Ruby: 42.to_s
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtvgvofv.html

C#:   42.ToString()
来源：http://dali.yj202588.top/Article/details/gt2gfrgdjpq.html

[A08] 取整与四舍五入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2truqmtva.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gt2icvzgvhr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.dashuyun.cn/Article/details/gt2rwmjfgrl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gt2briokgik.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ppjwa.cn/Article/details/gt2nccuhzru.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gt2fepnfzqm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gt2wkqfydyi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhengqikj.top/Article/details/gt2vywbwhbu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gt2bxfqapae.html

[A09] 绝对值与最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfffrizv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2dpoowqvo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2arotasez.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2egdfcrpz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2kfuwzeam.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2gkqffrwj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yuanzhike.top/Article/details/gt2tuhcmgsr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.0kj1m.cn/Article/details/gt2qcfztfim.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xinyue.icu/Article/details/gt2aocskkan.html

[A10] 生成随机数
来源：http://dali.jlsjyb.cn/Article/details/gt2qogfplfa.html

Py:   import random; random.randint(1, 100)
来源：http://dali.316326.xyz/Article/details/gt2lvlnbeul.html

PHP:  random_int(1, 100);
来源：http://dali.wangdashe.top/Article/details/gt2vnrqcmcd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenlongwang.top/Article/details/gt2nvunkzzq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2jowvcubh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.fengsongda.top/Article/details/gt2xyielmie.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkohgagf.html

Ruby: rand(1..100)
来源：http://dali.pycfn.com/Article/details/gt2xsjmwlca.html

C#:   new Random().Next(1, 101)
来源：http://dali.birdmap.top/Article/details/gt2oixahzmx.html

[A11] 条件表达式（三元）
来源：http://dali.zhixingplan.top/Article/details/gt2cvfqlula.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2lucdnxwz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gt2wuocfevz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gt2yvsdpkip.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gt2bvknfrpk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gt2ecnchijh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shzxlz.cn/Article/details/gt2znnfvpmr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gt2wnzckdir.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2kfqbdvlz.html

[A12] 字符串插值 / 格式化
来源：http://dali.ydzc1.top/Article/details/gt2sqiyxtev.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.guannengcc.top/Article/details/gt2zxblllrx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jlsjyb.cn/Article/details/gt2bbrfwmbf.html

JS:   `Hello, ${name}!`
来源：http://dali.zhixingplan.top/Article/details/gt2bfmgsjml.html

TS:   `Hello, ${name}!`
来源：http://dali.zhengqikj.top/Article/details/gt2jaatuvdg.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yonumen.top/Article/details/gt2tqyjxxdk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.0kj1m.cn/Article/details/gt2vegifsrk.html

Ruby: "Hello, #{name}!"
来源：http://dali.quarkkingdee.top/Article/details/gt2xrrauxpi.html

C#:   $"Hello, {name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbiedeth.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.meibo888.top/Article/details/gt2blsurvyy.html

Py:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gt2trlfxaop.html

PHP:  "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gt2lqatzhiw.html

JS:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2ptbcsltx.html

TS:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2lmotwpgg.html

Java: "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2myejcslu.html

Go:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqdrjxlg.html

Ruby: "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2fikxaryb.html

C#:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2gdhpjmgs.html

[A14] 注释写法
来源：http://dali.pycfn.com/Article/details/gt2bcfaotki.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jlsjyb.cn/Article/details/gt2wedaczqb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gt2mscewhkt.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gt2loiayvxt.html

TS:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gt2amgafghq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.meibo888.top/Article/details/gt2vfzjuuqk.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gt2bksapvdj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.redwolf501.top/Article/details/gt2pobugjuf.html

C#:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnkauetk.html

[A15] 空值判断与默认值
来源：http://dali.sweek.top/Article/details/gt2xejuiwlc.html

Py:   value = data or "默认值"
来源：http://dali.jiagoushi.top/Article/details/gt2sdjgdwyy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aggvlrbu.html

JS:   const value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gt2azcpewan.html

TS:   const value = data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gt2oetidtus.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258888.top/Article/details/gt2jxslkkqe.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvsjvfym.html

Ruby: value = data || "默认值"
来源：http://dali.jianghu66.top/Article/details/gt2mrctsnpd.html

C#:   var value = data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gt2hpdckjpl.html

[A16] 真假值判断规则
来源：http://dali.quarkkingdee.top/Article/details/gt2amtrygrk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.mhx1999.top/Article/details/gt2swifaots.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhoulong.xyz/Article/details/gt2rxdankvg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hongshengwenyu.top/Article/details/gt2xinyrqdn.html

TS:   if (!x) {}
来源：http://dali.xuanzx.com/Article/details/gt2eciloofx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2pdnjcxiu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cucudq.cn/Article/details/gt2tpfmipcg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jqgfzy.top/Article/details/gt2gdfwfryp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wyekxucz.html

[A17] 位运算
来源：http://dali.fengsongda.top/Article/details/gt2iqejpsoh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gt2eeaxjpcc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ivvv.top/Article/details/gt2kjyyitzi.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyuwlxfx.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2mcfjuuri.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2kkscqlod.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2jtzcpdbp.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugmjafxv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2dnfuwref.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hnxiangtu.top/Article/details/gt2ohcqzxle.html

Py:   ord("A"); chr(65)
来源：http://dali.ivvv.top/Article/details/gt2sqvguvwf.html

PHP:  ord("A"); chr(65)
来源：http://dali.yongpay.top/Article/details/gt2hmqdiade.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.316326.xyz/Article/details/gt2dopfwxuv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnqzz.top/Article/details/gt2pjopzcfy.html

Java: (int) 'A'; (char) 65
来源：http://dali.vqdsnc.cn/Article/details/gt2biuobavc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.meibo888.top/Article/details/gt2cwjfmzte.html

Ruby: "A".ord; 65.chr
来源：http://dali.gaohongyu789.top/Article/details/gt2upauivwn.html

C#:   (int)'A'; (char)65
来源：http://dali.gotoacloud.top/Article/details/gt2hlvokzxc.html

[A19] 交换两个变量
来源：http://dali.zycfv.cn/Article/details/gt2fjgumcbg.html

Py:   a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gt2srviyvko.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guannengcc.top/Article/details/gt2rznhfpzc.html

JS:   [a, b] = [b, a];
来源：http://dali.ehwqpu.com/Article/details/gt2kljonxkc.html

TS:   [a, b] = [b, a];
来源：http://dali.jyoumei.cn/Article/details/gt2avguahfk.html

Java: int t = a; a = b; b = t;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mppgmflw.html

Go:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2trtxuacs.html

Ruby: a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gt2dqnmivlf.html

C#:   (a, b) = (b, a);
来源：http://dali.svipenyu.cn/Article/details/gt2mwfawkqh.html

[A20] 读取标准输入
来源：http://dali.chenlongwang.top/Article/details/gt2uzmizzul.html

Py:   name = input("请输入：")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezgwzarb.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfxrxhhd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jknwyada.html

TS:   // Node.js：readline 模块
来源：http://dali.hnqzz.top/Article/details/gt2qogufgwm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tian-w.cn/Article/details/gt2dutaauot.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.andypj.xyz/Article/details/gt2afuaodku.html

Ruby: gets.chomp
来源：http://dali.hnqzz.top/Article/details/gt2baeupnzu.html

C#:   Console.ReadLine();
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzezoyno.html

[A21] 保留指定小数位输出
来源：http://dali.316326.xyz/Article/details/gt2kowvhsdy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cashguo.top/Article/details/gt2ofxwprsw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gt2lgwqetmj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gt2qtumlhgl.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gt2bizykkjh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gt2nzrgsnoz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gt2qivixlbr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gt2eqpedfhv.html

C#:   3.14159.ToString("F2")
来源：http://dali.ppjwa.cn/Article/details/gt2cxnpkqda.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dggfpghx.html

Py:   len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnzcfwxj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xziqi.cn/Article/details/gt2kahvrsvf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.birdmap.top/Article/details/gt2dcjcfxfh.html

TS:   s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2koidiosm.html

Java: s.length()
来源：http://dali.jiagoushi.top/Article/details/gt2kmczbwuy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.c1oappe.top/Article/details/gt2qdwztbmo.html

Ruby: s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfpmmuux.html

C#:   s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzpxysrc.html

[A23] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gt2ubhfiyus.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yuanzhike.top/Article/details/gt2ryinhlcx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cashguo.top/Article/details/gt2cwqvefgm.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gt2fhkveohk.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xinyue.icu/Article/details/gt2rzimmayx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhendiub.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2thdpiqfg.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gt2yfabuiza.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yonumen.top/Article/details/gt2noholxsj.html

[A24] 去除首尾空白
来源：http://dali.birdmap.top/Article/details/gt2ymtaayod.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkygtzqz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jlsjyb.cn/Article/details/gt2jhqjhleo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hammf.cn/Article/details/gt2gkvusdgd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.meibo888.top/Article/details/gt2ensseorg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jqgfzy.top/Article/details/gt2bttwzuvc.html

Go:   strings.TrimSpace(s)
来源：http://dali.dianchejie.cn/Article/details/gt2mavbaemd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxlauhng.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yonumen.top/Article/details/gt2rfqfvrcv.html

[A25] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2vphfnksa.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okmegidr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sysykeji.top/Article/details/gt2bctgjawj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.andypj.xyz/Article/details/gt2louvuphw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sysykeji.top/Article/details/gt2qnijyiup.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jlsjyb.cn/Article/details/gt2kmkahbqf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gaohongyu789.top/Article/details/gt2tmdkweav.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinqigufen.top/Article/details/gt2mvclkrjq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2lcjpsser.html

[A26] 类型转换总览
来源：http://dali.hywenlv.cn/Article/details/gt2gdnvyymw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cheryme.top/Article/details/gt2uztdaibz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hysaishi.cn/Article/details/gt2sginndos.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.pycfn.com/Article/details/gt2nzagbebg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.iojbl.cn/Article/details/gt2cadrbqit.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gt2edtlcwxk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.kuanghao11.cn/Article/details/gt2bafexsuf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.daria6918.cn/Article/details/gt2qdvbdpev.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gt2tdyiwrsu.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2boltaojc.html

B. 流程控制
来源：http://dali.nanxinkj.top/Article/details/gt2izznaklt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2iwyuxrlf.html

[B01] 条件判断 if / else
来源：http://dali.fengsongda.top/Article/details/gt2fymmgxon.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejuzaurh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xziqi.cn/Article/details/gt2vkkcucfo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gt2qpeglqwd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gt2sqcabhpt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gt2tadhrcpf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yueranfly.top/Article/details/gt2remcekak.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fzhhl.top/Article/details/gt2vgrvrisb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gt2dbeilwgz.html

[B02] 多分支 else if / elif
来源：http://dali.feifeiyinyue.top/Article/details/gt2edwegnle.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gzhubu.top/Article/details/gt2modazmiw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yueranfly.top/Article/details/gt2pcswcyho.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gt2szuouxjx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gt2vhzgqjyk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gt2ymcwkpmo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xuanzx.com/Article/details/gt2hvzcqvij.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhoulong.xyz/Article/details/gt2movbnkxb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gt2bueojhwz.html

[B03] switch / match / case
来源：http://dali.zdqjudy.top/Article/details/gt2exeteyiy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ppjwa.cn/Article/details/gt2pwmixygo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gt2rzadmpnr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcheaawn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gt2tclihssa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gt2qchuvkip.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258.top/Article/details/gt2yirkatdu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmmfyzf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.svipenyu.cn/Article/details/gt2lxqtgcvb.html

[B04] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gt2hpcwnzrp.html

Py:   for i in range(10): print(i)
来源：http://dali.hnqzz.top/Article/details/gt2wnolejdh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cdnleiting.top/Article/details/gt2vgfbldrw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.haohaochexian.top/Article/details/gt2serpeshg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gt2evcemmxs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jqgfzy.top/Article/details/gt2ywqruamc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinqigufen.top/Article/details/gt2xpgrvify.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guowangkeji.top/Article/details/gt2zsxghpqb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yonumen.top/Article/details/gt2nfualtgo.html

[B05] 遍历数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gt2pwrfgetg.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigfzy.top/Article/details/gt2zdtzhsas.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gt2bgvaumue.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnxiangtu.top/Article/details/gt2fbdbinfq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gt2nahzkbph.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgufenzy.top/Article/details/gt2lsdondml.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.smart0.xyz/Article/details/gt2qnaedhzn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shuidangran.top/Article/details/gt2olwudjwb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sysykeji.top/Article/details/gt2tasrbqdh.html

[B06] 遍历字典 / 对象
来源：http://dali.zdqjudy.top/Article/details/gt2zmuwmznb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.c1oappe.top/Article/details/gt2tlgvrmhl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cqqwz.cn/Article/details/gt2wjreqcqv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2daexjqlh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gt2oznkzxox.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daxiang520.top/Article/details/gt2deqaaida.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iyrztibf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigfzy.top/Article/details/gt2loeudtyu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.aizwys.cn/Article/details/gt2pobqiiov.html

[B07] while 循环
来源：http://dali.yj20258888.top/Article/details/gt2bcztvgap.html

Py:   while i < 10: i += 1
来源：http://dali.yonumen.top/Article/details/gt2mkgrckcf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xyprhdmf.html

JS:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gt2suwassju.html

TS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gt2rnzmzfsr.html

Java: while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2petlvcvc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.iojbl.cn/Article/details/gt2suxfbnod.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hfpthk.cn/Article/details/gt2phrbkxhz.html

C#:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gt2mhjemuns.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gt2kikurzcs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.mhx1999.top/Article/details/gt2pkynmchd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2lykefndg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2iellqlzs.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2rhcsejje.html

Java: do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gt2woujyjjw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsghxswz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cashguo.top/Article/details/gt2tdrzqgrx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gt2qwrlkeak.html


<!-- 参考信息 -->