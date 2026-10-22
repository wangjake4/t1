代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.chenlongwang.top/Article/details/gttdlizzes.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dashuyun.cn/Article/details/gtvtwbhzpk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtxqiuhxmz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtatavyffe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gtrokoycyt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gtljdmjycc.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjpmxycy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.fengsongda.top/Article/details/gtztbyayzb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtmynazrng.html

[A03] 常量定义
来源：http://dali.yanxiufei.cn/Article/details/gtfbbielfw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sysykeji.top/Article/details/gtqudgkhzi.html

PHP:  const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtfdvnifsn.html

JS:   const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtdyjovzkg.html

TS:   const PI: number = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtmfzjokzz.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtqqklbfaf.html

Go:   const PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gtwjceahfr.html

Ruby: PI = 3.14159
来源：http://dali.nanxuanxn.top/Article/details/gtjreejhvy.html

C#:   const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gteubrydul.html

[A04] 判断变量类型
来源：http://dali.chenlongwang.top/Article/details/gtvibrphej.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangshuangyany.cn/Article/details/gtszdwtsuz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtllrlxksx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gtxxdzehgh.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gtqqoktdft.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.9152youxi.cn/Article/details/gtrplgcxtt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinqigufen.top/Article/details/gtiosknuws.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gtuwzzobng.html

C#:   x.GetType().Name; x is int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrwzrdlk.html

[A05] 整数除法与取模
来源：http://dali.jyoumei.cn/Article/details/gtzeobvjfe.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.guowangkeji.top/Article/details/gtecugzwri.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gthhbkwhyt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtoikvgmwt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedzdimor.html

Java: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtbjsdwbsb.html

Go:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtyilttuxz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gthwdhihze.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfoyvnpw.html

[A06] 字符串转数字
来源：http://dali.sweek.top/Article/details/gtxahpwftc.html

Py:   int("42"); float("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtfstvahgr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jianghu66.top/Article/details/gtlxmimgiu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zycfv.cn/Article/details/gtyiuatpuv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yanxiufei.cn/Article/details/gtklatpmvb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.mhx1999.top/Article/details/gtdytfdkpu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtkztgrzwy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tianlin.xyz/Article/details/gtisuxnill.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtorcnqcbq.html

[A07] 数字转字符串
来源：http://dali.c1oappe.top/Article/details/gttcgwlbpo.html

Py:   str(42)
来源：http://dali.hnqzz.top/Article/details/gtsijfwaxm.html

PHP:  (string) 42; strval(42)
来源：http://dali.hywenlv.cn/Article/details/gtkxbqptza.html

JS:   String(42); (42).toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtfllauukx.html

TS:   String(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcemzbpre.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtjiukyfij.html

Go:   strconv.Itoa(42)
来源：http://dali.wangdashe.top/Article/details/gtdtzaffxh.html

Ruby: 42.to_s
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjwqcwkl.html

C#:   42.ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpruwjpfn.html

[A08] 取整与四舍五入
来源：http://dali.316326.xyz/Article/details/gtarpygrsx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtcycohqgs.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yonumen.top/Article/details/gtqynpeqky.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gtvjfswhrp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.andypj.xyz/Article/details/gtxmwsekhs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gtnjxekyxu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtwubwdadx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhongyouzk.top/Article/details/gtmtvawsfg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gtepuuncyq.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtqxiejkgz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtfsjttdbr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuemrxckx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtmjaicqlz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtcjcrjwth.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtjrgsnrbu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.aibaodan.cn/Article/details/gtpliqhqzo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gotoacloud.top/Article/details/gtmaagyzcw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtthgxmkfc.html

[A10] 生成随机数
来源：http://dali.birdmap.top/Article/details/gtsxmdqbrt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hfpthk.cn/Article/details/gtmgqdoast.html

PHP:  random_int(1, 100);
来源：http://dali.jinqigufen.top/Article/details/gtrpgfrnbk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gtncxqqbkr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xziqi.cn/Article/details/gtutdcpsyp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinqigfzy.top/Article/details/gtjcqbsjsl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.vqdsnc.cn/Article/details/gtypsivywv.html

Ruby: rand(1..100)
来源：http://dali.iojbl.cn/Article/details/gtdqpwazmb.html

C#:   new Random().Next(1, 101)
来源：http://dali.tanke756.top/Article/details/gtemknhkhh.html

[A11] 条件表达式（三元）
来源：http://dali.hammf.cn/Article/details/gtghtkxeph.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sysykeji.top/Article/details/gtesgiozoo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gtpujzgqlj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtjqymwury.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtohswhugq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtaofselhc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.cqqwz.cn/Article/details/gthnoyuocq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtaudtqyut.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gttvhranpp.html

[A12] 字符串插值 / 格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtlkgmpxob.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj202588.top/Article/details/gtqpvehret.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gotoacloud.top/Article/details/gtjafgnhyx.html

JS:   `Hello, ${name}!`
来源：http://dali.sweek.top/Article/details/gthsxtrgry.html

TS:   `Hello, ${name}!`
来源：http://dali.hysaishi.cn/Article/details/gtydkumhbp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.svipenyu.cn/Article/details/gtnqsvthsz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinqigufen.top/Article/details/gtxgvdlpuj.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinqigfzy.top/Article/details/gtpopswtgi.html

C#:   $"Hello, {name}!"
来源：http://dali.zhixingplan.top/Article/details/gtndlgzimd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhoulong.xyz/Article/details/gtjpfqamgv.html

Py:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaihtnzfn.html

PHP:  "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtrowlxnka.html

JS:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtbcyxavkq.html

TS:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtragicyhm.html

Java: "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtrgymfyoi.html

Go:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtccjomgki.html

Ruby: "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtehenvizy.html

C#:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtfqrdbyjs.html

[A14] 注释写法
来源：http://dali.fengsongda.top/Article/details/gtpmenfead.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.aibaodan.cn/Article/details/gtnmpgujdw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gtjqqwfkow.html

JS:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gtlrfybebt.html

TS:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtkqlahese.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ivvv.top/Article/details/gtcrqurmvy.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtynsnclcz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangtech.top/Article/details/gtxaemahkt.html

C#:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gtwdprbqyu.html

[A15] 空值判断与默认值
来源：http://dali.hammf.cn/Article/details/gtddgybfys.html

Py:   value = data or "默认值"
来源：http://dali.zhoulong.xyz/Article/details/gtzturkkrj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhongyouzk.top/Article/details/gtzzofmpgw.html

JS:   const value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtwprurkhg.html

TS:   const value = data ?? "默认值";
来源：http://dali.quarkkingdee.top/Article/details/gtbkiwmypz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.chenzaomai.com/Article/details/gtcymmwdjh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhiwuduotai.top/Article/details/gtaoboazcj.html

Ruby: value = data || "默认值"
来源：http://dali.daxiang520.top/Article/details/gtjwmbbohc.html

C#:   var value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gttnvkowlb.html

[A16] 真假值判断规则
来源：http://dali.cqqwz.cn/Article/details/gthjpsqwlu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sufxvd.cn/Article/details/gtqvvkgvhr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.kuanghao11.cn/Article/details/gtgfzmsqoc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbagvdgm.html

TS:   if (!x) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtixhgcnku.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj20258888.top/Article/details/gtlveodkch.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.svipenyu.cn/Article/details/gtjmhrmxoi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhongyouzk.top/Article/details/gtkrpofxtb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtxlwsarij.html

[A17] 位运算
来源：http://dali.dianchejie.cn/Article/details/gtjspmbiys.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtctsegghv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ydzc1.top/Article/details/gtqttejvwe.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtmqgygctn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtjrsetttj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtgwkvdkkk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gtgwzjawcc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtbnjibsnk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhacmlmt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zycfv.cn/Article/details/gtdbotduvf.html

Py:   ord("A"); chr(65)
来源：http://dali.hysaishi.cn/Article/details/gtmbxivstn.html

PHP:  ord("A"); chr(65)
来源：http://dali.quarkkingdee.top/Article/details/gtfcazegtp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fengsongda.top/Article/details/gtcviuztpw.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.316326.xyz/Article/details/gtvsbbwdgx.html

Java: (int) 'A'; (char) 65
来源：http://dali.daria6918.cn/Article/details/gtyeezkkqs.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhengqikj.top/Article/details/gtbxfnstob.html

Ruby: "A".ord; 65.chr
来源：http://dali.sxryk.cn/Article/details/gtpoxqmyul.html

C#:   (int)'A'; (char)65
来源：http://dali.jiagoushi.top/Article/details/gtpawrxtkf.html

[A19] 交换两个变量
来源：http://dali.daria6918.cn/Article/details/gtnpqovqrv.html

Py:   a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gtqqrdqxfe.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gzhubu.top/Article/details/gtsavfetfx.html

JS:   [a, b] = [b, a];
来源：http://dali.havefunace.top/Article/details/gtkxfuleyq.html

TS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gtqpcpqopl.html

Java: int t = a; a = b; b = t;
来源：http://dali.shuidangran.top/Article/details/gtjinnsvgg.html

Go:   a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gtbkorunub.html

Ruby: a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gtniqwvgaa.html

C#:   (a, b) = (b, a);
来源：http://dali.zycfv.cn/Article/details/gtzywtfzas.html

[A20] 读取标准输入
来源：http://dali.hysaishi.cn/Article/details/gtxdabmuzb.html

Py:   name = input("请输入：")
来源：http://dali.dashuyun.cn/Article/details/gtbigvavfs.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sufxvd.cn/Article/details/gtjlavlvhl.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jiagoushi.top/Article/details/gtngjdwnfc.html

TS:   // Node.js：readline 模块
来源：http://dali.jinqigufen.top/Article/details/gtjiwnmddz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cqqwz.cn/Article/details/gtvxwuyput.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shangyingyoupin.top/Article/details/gttdixkcsf.html

Ruby: gets.chomp
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtfnnlhf.html

C#:   Console.ReadLine();
来源：http://dali.shangyingyoupin.top/Article/details/gthjekwgzt.html

[A21] 保留指定小数位输出
来源：http://dali.yj20258888.top/Article/details/gtkbvywxbb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhoulong.xyz/Article/details/gtlzsnxizi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jiagoushi.top/Article/details/gteeqrkblp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvtaimeo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtyiybiika.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtyiarysik.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gttzlvjevh.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gtebhdrhxt.html

C#:   3.14159.ToString("F2")
来源：http://dali.fzhhl.top/Article/details/gtddrrfkik.html

[A22] 获取字符串长度
来源：http://dali.redwolf501.top/Article/details/gtihgvqyaf.html

Py:   len(s)
来源：http://dali.jyoumei.cn/Article/details/gtyuuqgopa.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.smart0.xyz/Article/details/gtbibljszp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhijiandao.cn/Article/details/gtpiyskwxq.html

TS:   s.length
来源：http://dali.316326.xyz/Article/details/gtbvezuhpu.html

Java: s.length()
来源：http://dali.gogol.net.cn/Article/details/gttmlvyrpp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ydzc1.top/Article/details/gtvloiyvde.html

Ruby: s.length
来源：http://dali.c1oappe.top/Article/details/gtprtjfjoe.html

C#:   s.Length
来源：http://dali.xylfe.cn/Article/details/gtlqzvxmei.html

[A23] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtgykbcpni.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jyoumei.cn/Article/details/gtncobdfqn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoaucmjdb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtpayparbn.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258888.top/Article/details/gtfwbuipvn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gtkayullej.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sxryk.cn/Article/details/gtbvoberdy.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.bjfxy.top/Article/details/gturlzajba.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.quarkkingdee.top/Article/details/gtkburdsdn.html

[A24] 去除首尾空白
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwjtpllo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.iojbl.cn/Article/details/gtafmjathw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gogol.net.cn/Article/details/gteydssnmg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtbjwjunfg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tanke756.top/Article/details/gtqwbledvn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenlongwang.top/Article/details/gtufbtdnxh.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuanzhike.top/Article/details/gtyttijkzk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.havefunace.top/Article/details/gtbhsukneq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zycfv.cn/Article/details/gtgpwwksec.html

[A25] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gttapixmsb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhixingplan.top/Article/details/gtxcvvqsjl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nwbrower.top/Article/details/gtnpfkavid.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhoulong.xyz/Article/details/gtkuvlcauf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gtwtbjuxjq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.9152youxi.cn/Article/details/gtzllismzj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.guannengcc.top/Article/details/gtbpfdurlj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.mhx1999.top/Article/details/gtsbylhtxw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gtdtaoyzip.html

[A26] 类型转换总览
来源：http://dali.hfpthk.cn/Article/details/gtesifcysv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.feifeiyinyue.top/Article/details/gtjnbfuyov.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxuanxn.top/Article/details/gthxbljqnd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.nwbrower.top/Article/details/gtdlxjqgwo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gogol.net.cn/Article/details/gtnqwatlgg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yongpay.top/Article/details/gtiwrsxyat.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.haohaochexian.top/Article/details/gttcaglzkv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jqgfzy.top/Article/details/gtjeqfavgq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gtqedtwvvz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvomroxil.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gtwjgquegv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtajhcrwmy.html

[B01] 条件判断 if / else
来源：http://dali.guowangkeji.top/Article/details/gtvqvbftch.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sufxvd.cn/Article/details/gtcmqmrdny.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.havefunace.top/Article/details/gtwousgnto.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtamfqmqwl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gtmuciossn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwnqvatn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hongshengwenyu.top/Article/details/gtzlkuulkf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.c1oappe.top/Article/details/gtoffqalpa.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtmcuhlabm.html

[B02] 多分支 else if / elif
来源：http://dali.gaohongyu789.top/Article/details/gtzveybasi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gtrvnivpyc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yangfankeji.com/Article/details/gtskzcmspj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtgeawqrrq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gtejvzjphd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtvedgyoqt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ehwqpu.com/Article/details/gteziflyug.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoksrykm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtbuidfjwq.html

[B03] switch / match / case
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkcpzvfy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jqgfzy.top/Article/details/gtsbnheupr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtdlfmrppe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtzemhmmmr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gthzcqvvyl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtjhrpagkq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jianghu66.top/Article/details/gtefaeipwo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbxnpbdd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gtqwvdgovw.html

[B04] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtrbvupawr.html

Py:   for i in range(10): print(i)
来源：http://dali.0kj1m.cn/Article/details/gtgdlibyek.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenlongwang.top/Article/details/gtuknyeoho.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnakxeyas.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gtqtijidbx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzdvpcsfp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yongpay.top/Article/details/gtedgbopoq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.iojbl.cn/Article/details/gtizwosksk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fzhhl.top/Article/details/gtzjawbmmu.html

[B05] 遍历数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtunldtaar.html

Py:   for item in arr: print(item)
来源：http://dali.redwolf501.top/Article/details/gtpxuaqyji.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.andypj.xyz/Article/details/gtlkznrrpw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gtnljvqthk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtpgyhdmlg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aizwys.cn/Article/details/gtetflploo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hammf.cn/Article/details/gtiftgecsb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.pycfn.com/Article/details/gtjhfgsmvd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nwbrower.top/Article/details/gtdbfjcfab.html

[B06] 遍历字典 / 对象
来源：http://dali.ehwqpu.com/Article/details/gtfozwbpap.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258888.top/Article/details/gtgmzumgow.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sufxvd.cn/Article/details/gtfbxskpqe.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveuiitxi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gtlbagrlad.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.guannengcc.top/Article/details/gtxdsjmdwj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinqigufen.top/Article/details/gtcpnzjovk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hysaishi.cn/Article/details/gtrmqwlfos.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zdqjudy.top/Article/details/gtznaoekyd.html

[B07] while 循环
来源：http://dali.wangdashe.top/Article/details/gtksigerkc.html

Py:   while i < 10: i += 1
来源：http://dali.hammf.cn/Article/details/gthpwmqtxb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hfpthk.cn/Article/details/gtukadcwcr.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtiwfvrigt.html

TS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtenapmbgw.html

Java: while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtefxvhbph.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxuanxn.top/Article/details/gtlfffvrqu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gogol.net.cn/Article/details/gtimpsqujb.html

C#:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtvwopcwoh.html

[B08] do-while（至少执行一次）
来源：http://dali.chenlongwang.top/Article/details/gtpslwahda.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xinyue.icu/Article/details/gtkeefgxmh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gtraumkhih.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtetuqwncn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtysniigav.html

Java: do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtylotakub.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtzjtvysxq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daxiang520.top/Article/details/gtlpgcvfgq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiifvzlg.html


<!-- 参考信息 -->