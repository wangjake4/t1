代发 wailian999

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtuobmpvcq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sxryk.cn/Article/details/gtxqntqxxw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gteuvbezhi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gtavrpfzvz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmjsvobki.html

A. 基础语法与类型
来源：http://dali.aibaodan.cn/Article/details/gtknqfnuth.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtadznolkb.html

[A01] Hello World
来源：http://dali.xinyue.icu/Article/details/gtvbxqpbxe.html

Py:   print("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gtexvvuilj.html

PHP:  echo "Hello, World!";
来源：http://dali.cdnleiting.top/Article/details/gtanenndpb.html

JS:   console.log("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gtnpgjyupk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbburtxe.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gttvtshzdq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gtmqnvosho.html

Ruby: puts "Hello, World!"
来源：http://dali.gzhubu.top/Article/details/gtolayvlul.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtskwhwwcf.html

[A02] 变量声明与赋值
来源：http://dali.redwolf501.top/Article/details/gtpfhtkbhz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ybcxt.top/Article/details/gtmavvlook.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcjfmuky.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258888.top/Article/details/gtyjwywqzs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.havefunace.top/Article/details/gtzluajfys.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gtedxyedmq.html

Go:   name := "Alex"; age := 20
来源：http://dali.aibaodan.cn/Article/details/gtifqenfvd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.smart0.xyz/Article/details/gtmyomhqym.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gtjhvgowap.html

[A03] 常量定义
来源：http://dali.yj20258.top/Article/details/gtnyksnzqf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrhogpdj.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtjztchvth.html

JS:   const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtdflywttv.html

TS:   const PI: number = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtslatoyrq.html

Java: static final double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gthtvnpovb.html

Go:   const PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gtgznnlykq.html

Ruby: PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gtmebhterp.html

C#:   const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtvvliabtf.html

[A04] 判断变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtnmtpfowf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nwbrower.top/Article/details/gtttibehvp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnxiangtu.top/Article/details/gtpferdglz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.mhx1999.top/Article/details/gtwmmhxapc.html

TS:   typeof x; x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gtquslcqtn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.daxiang520.top/Article/details/gtbsahyrmt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.redwolf501.top/Article/details/gtnvpxphyx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cqqwz.cn/Article/details/gteuunyrmr.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhongyouzk.top/Article/details/gtmwcuutcv.html

[A05] 整数除法与取模
来源：http://dali.sweek.top/Article/details/gtlcgmjqzq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nanxinkj.top/Article/details/gtrrtekvic.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtltgurojc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtcukvrhhq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gtbzwjxofa.html

Java: 7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtdnbdtwbg.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtmmhdkgwo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtibiapizz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtzzpsjmix.html

[A06] 字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtmwjhqljr.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gtolvzyvnk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ehwqpu.com/Article/details/gtkbtefrzz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xuetiantiany.cn/Article/details/gtuguntvjd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtnlyjttml.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.0kj1m.cn/Article/details/gtnvpvqkno.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtxfxdbizk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gtdnbtpevn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yangfankeji.com/Article/details/gtleuzolhs.html

[A07] 数字转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtzartjsse.html

Py:   str(42)
来源：http://dali.meibo888.top/Article/details/gtxpacwboc.html

PHP:  (string) 42; strval(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtorvqhgcm.html

JS:   String(42); (42).toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtgrdvkztk.html

TS:   String(42)
来源：http://dali.xylfe.cn/Article/details/gtiwdnvfzc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shangyingyoupin.top/Article/details/gtjcmbmxna.html

Go:   strconv.Itoa(42)
来源：http://dali.jyoumei.cn/Article/details/gtucjjovod.html

Ruby: 42.to_s
来源：http://dali.haohaochexian.top/Article/details/gtmaajxrhj.html

C#:   42.ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtbevijclr.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gtksqjvqzd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtismbrqde.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuanzhike.top/Article/details/gtqvbnyomq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gtxrogunnz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.vqdsnc.cn/Article/details/gtlmtxvfdc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtmkjrpkzi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtgaumpjew.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hnxiangtu.top/Article/details/gtgyxhryzt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gtnyinftcr.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtfpqsyqcd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtumaccttb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yonumen.top/Article/details/gtizqfqrnf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtkaudnqdw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtlhucjcqp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtyfbsocpi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.snrcjt.cn/Article/details/gtckkyieom.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.smart0.xyz/Article/details/gtmmubhtck.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtonzydaps.html

[A10] 生成随机数
来源：http://dali.kuanghao11.cn/Article/details/gtkulurejs.html

Py:   import random; random.randint(1, 100)
来源：http://dali.iojbl.cn/Article/details/gtyekyvkyj.html

PHP:  random_int(1, 100);
来源：http://dali.fengsongda.top/Article/details/gtwybmkizg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcftonqk.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.smart0.xyz/Article/details/gtlhoghcow.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jianghu66.top/Article/details/gtepxyoken.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.iojbl.cn/Article/details/gtvhnvcbko.html

Ruby: rand(1..100)
来源：http://dali.quarkkingdee.top/Article/details/gtbvebycsz.html

C#:   new Random().Next(1, 101)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxrnegxy.html

[A11] 条件表达式（三元）
来源：http://dali.sysykeji.top/Article/details/gtqhmfnbva.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gogol.net.cn/Article/details/gtqzhxlqrj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gteyfxjxgy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtcmejdopb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtcsggow.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtdehyvcur.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.havefunace.top/Article/details/gthiqnodba.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtbngrcuvl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtbpzqhcvr.html

[A12] 字符串插值 / 格式化
来源：http://dali.smart0.xyz/Article/details/gthyoulqmr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hfpthk.cn/Article/details/gtbbjqhooq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.pengpengdd.cyou/Article/details/gtpmjrpzfj.html

JS:   `Hello, ${name}!`
来源：http://dali.zhixingplan.top/Article/details/gtghqvwqiq.html

TS:   `Hello, ${name}!`
来源：http://dali.ivvv.top/Article/details/gtjvfnyzyu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xylfe.cn/Article/details/gtyewfkwig.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yanxiufei.cn/Article/details/gteiwldtmn.html

Ruby: "Hello, #{name}!"
来源：http://dali.sufxvd.cn/Article/details/gtvisjdqud.html

C#:   $"Hello, {name}!"
来源：http://dali.yonumen.top/Article/details/gtlejbnukt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.pycfn.com/Article/details/gttvnsbaov.html

Py:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtfbpoluzv.html

PHP:  "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtrcggwopo.html

JS:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtkklbcbzg.html

TS:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmblhyvif.html

Java: "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtttdqtkrf.html

Go:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gthluurlom.html

Ruby: "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoribsgds.html

C#:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtdnjfbirp.html

[A14] 注释写法
来源：http://dali.9152youxi.cn/Article/details/gtwnzzxnfc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sxryk.cn/Article/details/gtjniwdqwp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gtztzbjdou.html

JS:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gttsihfpox.html

TS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtwqdeyzzh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hnqzz.top/Article/details/gteglynsxl.html

Go:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtaebbbnto.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jqgfzy.top/Article/details/gttxidpqpr.html

C#:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gtdlqanuen.html

[A15] 空值判断与默认值
来源：http://dali.jyoumei.cn/Article/details/gtaosmipja.html

Py:   value = data or "默认值"
来源：http://dali.yangfankeji.com/Article/details/gtyqlrhstj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtfgsaubqk.html

JS:   const value = data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gtgjfinovb.html

TS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gttvjdwbdn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.chenjidiqi.icu/Article/details/gttcphrnjc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.snrcjt.cn/Article/details/gtihgpejyv.html

Ruby: value = data || "默认值"
来源：http://dali.aibaodan.cn/Article/details/gtnajuxasd.html

C#:   var value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtwuszurrt.html

[A16] 真假值判断规则
来源：http://dali.dashuyun.cn/Article/details/gtymdgdhdy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shzxlz.cn/Article/details/gtinptrzri.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfnjtgqc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hywenlv.cn/Article/details/gthbjbxqeu.html

TS:   if (!x) {}
来源：http://dali.9152youxi.cn/Article/details/gtzmfrdkih.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.aizwys.cn/Article/details/gtbfyomunk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuanzx.com/Article/details/gtvkekiakj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.wangdashe.top/Article/details/gttjdcrokq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtgzosgacm.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gtjvbxfmzj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtcfkoojkq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ivvv.top/Article/details/gtuoouyzno.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtcxatyxch.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbpqoqeb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtwjuazlng.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtofdcwvae.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtmpnopfrf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtfnlapbwm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ybcxt.top/Article/details/gtahyucecy.html

Py:   ord("A"); chr(65)
来源：http://dali.hongshengwenyu.top/Article/details/gtdrjprska.html

PHP:  ord("A"); chr(65)
来源：http://dali.birdmap.top/Article/details/gtofcnxgeg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gthpukuwxh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xylfe.cn/Article/details/gtoqlivwsj.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigfzy.top/Article/details/gtktlibyzm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jyoumei.cn/Article/details/gtjufamwnl.html

Ruby: "A".ord; 65.chr
来源：http://dali.ehwqpu.com/Article/details/gtqkanwzox.html

C#:   (int)'A'; (char)65
来源：http://dali.smart0.xyz/Article/details/gtxxxfvicx.html

[A19] 交换两个变量
来源：http://dali.yongpay.top/Article/details/gtcailzgvd.html

Py:   a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gtgxdoypga.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.fengsongda.top/Article/details/gtvtuwjdxi.html

JS:   [a, b] = [b, a];
来源：http://dali.jyoumei.cn/Article/details/gtmaigrrww.html

TS:   [a, b] = [b, a];
来源：http://dali.yuanzhike.top/Article/details/gtwqolbttu.html

Java: int t = a; a = b; b = t;
来源：http://dali.aizwys.cn/Article/details/gtetdseddd.html

Go:   a, b = b, a
来源：http://dali.fzhhl.top/Article/details/gtbgnorawp.html

Ruby: a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvsqqonf.html

C#:   (a, b) = (b, a);
来源：http://dali.havefunace.top/Article/details/gtirjhktqt.html

[A20] 读取标准输入
来源：http://dali.pycfn.com/Article/details/gtauwgjjqd.html

Py:   name = input("请输入：")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsrfwqpx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.havefunace.top/Article/details/gtdgrvvxby.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hysaishi.cn/Article/details/gtgwmgutlb.html

TS:   // Node.js：readline 模块
来源：http://dali.xziqi.cn/Article/details/gtjzjfkivx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.quarkkingdee.top/Article/details/gtgqsjldfo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinqigfzy.top/Article/details/gtipsoszxd.html

Ruby: gets.chomp
来源：http://dali.sxryk.cn/Article/details/gtmfxzqkws.html

C#:   Console.ReadLine();
来源：http://dali.chenzaomai.com/Article/details/gttobgsute.html

[A21] 保留指定小数位输出
来源：http://dali.9152youxi.cn/Article/details/gtkphuhrzo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xuanzx.com/Article/details/gtebmsfozq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtjwzzoqnt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gtdesmapcw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtlbagtsgq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtdkdkcbml.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gtjotrgdvd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gtlrymkdbi.html

C#:   3.14159.ToString("F2")
来源：http://dali.mhx1999.top/Article/details/gttbrctelx.html

[A22] 获取字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtdupkenno.html

Py:   len(s)
来源：http://dali.gotoacloud.top/Article/details/gtnbrzbmjd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pycfn.com/Article/details/gtsdzldlzb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.tianlin.xyz/Article/details/gtesbyzdeq.html

TS:   s.length
来源：http://dali.nanxuanxn.top/Article/details/gtwkubvhsn.html

Java: s.length()
来源：http://dali.aizwys.cn/Article/details/gtaunelmrf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.mhx1999.top/Article/details/gtygrpnduq.html

Ruby: s.length
来源：http://dali.0kj1m.cn/Article/details/gteoizlmpk.html

C#:   s.Length
来源：http://dali.sweek.top/Article/details/gtpetoxngp.html

[A23] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtdaqeysbm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzazqsfyc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ybcxt.top/Article/details/gthbxiogrl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtjhwidzvx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmzwjpqa.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtvdvxqcwl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ppjwa.cn/Article/details/gtowvmpjik.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwclxduuc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.pengpengdd.cyou/Article/details/gtqfhpaync.html

[A24] 去除首尾空白
来源：http://dali.gaohongyu789.top/Article/details/gtfyrzczwi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sufxvd.cn/Article/details/gtbivjunin.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.havefunace.top/Article/details/gtpabhcwby.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtzgmotwst.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtfyqqgkxx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yonumen.top/Article/details/gtnjcphhte.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gtteryalzz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuxming.cn/Article/details/gtfaxzhydt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbazasao.html

[A25] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtdaisyyci.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yongpay.top/Article/details/gtorljcknv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhongyouzk.top/Article/details/gtwhdtkrfr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gttyootysn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gthsdufifu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhengqikj.top/Article/details/gtvtyguika.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gtfapliedq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.0kj1m.cn/Article/details/gtxkdrjgdv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hywenlv.cn/Article/details/gtaylrmojg.html

[A26] 类型转换总览
来源：http://dali.jlsjyb.cn/Article/details/gtbwlxjnak.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.iojbl.cn/Article/details/gtbzuhwbbo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhixingplan.top/Article/details/gtogaykjhk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuanzhike.top/Article/details/gtnwfsiuir.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuxming.cn/Article/details/gtcnkuztut.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gtsrqzqzfb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.smart0.xyz/Article/details/gtsuwjsjbv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gzhubu.top/Article/details/gtzndculyq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daria6918.cn/Article/details/gtkmlramvr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtxpekauvz.html

B. 流程控制
来源：http://dali.0kj1m.cn/Article/details/gtexrdqiay.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnbqiozow.html

[B01] 条件判断 if / else
来源：http://dali.zhiwuduotai.top/Article/details/gtrucrsfix.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtbqsagzzn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.redwolf501.top/Article/details/gtkodddzfh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtlzxblyhu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtllqeetpv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwuwqmki.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yangfankeji.com/Article/details/gtjhefclbk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhongyouzk.top/Article/details/gtuirnbkhd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtwrarvpyu.html

[B02] 多分支 else if / elif
来源：http://dali.jiagoushi.top/Article/details/gteatpccev.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fengsongda.top/Article/details/gtrtmvmptn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkffqwoqj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtnhkvmljf.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtwyfyqsej.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtybehwvyg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hongshengwenyu.top/Article/details/gtiizryvuk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shangyingyoupin.top/Article/details/gtezhhoqnk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtdnzakogb.html

[B03] switch / match / case
来源：http://dali.guowangkeji.top/Article/details/gtzktkuunp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.tian-w.cn/Article/details/gtvoqacbmo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gttewcyyyz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtbbbjelnd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtwqfgxrzh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtonaexgmc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gtnwnsbtpe.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fengsongda.top/Article/details/gtefgiqpvk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gtubqcxnqk.html

[B04] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvxfgncy.html

Py:   for i in range(10): print(i)
来源：http://dali.gotoacloud.top/Article/details/gtpmorfxju.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenlongwang.top/Article/details/gtoxcwvsii.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yangfankeji.com/Article/details/gtynmvlzkn.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbewjaiwa.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.9152youxi.cn/Article/details/gttlsweyot.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhiwuduotai.top/Article/details/gtuvrznknw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.smart0.xyz/Article/details/gtjrigmomn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ehwqpu.com/Article/details/gtsmemxmgu.html

[B05] 遍历数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtkxjdgpuf.html

Py:   for item in arr: print(item)
来源：http://dali.ybcxt.top/Article/details/gtlexemwoe.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gtzthlhfio.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gtpbkzvmml.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gtvceenpfs.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ehwqpu.com/Article/details/gthrjzvtih.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zdqjudy.top/Article/details/gtsfuupjov.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnxiangtu.top/Article/details/gtwrraoync.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gzhubu.top/Article/details/gtzgdourba.html

[B06] 遍历字典 / 对象
来源：http://dali.meibo888.top/Article/details/gtdbwtyexr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.mhx1999.top/Article/details/gtylyxylmt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gzhubu.top/Article/details/gtafgwqbes.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gttzbebvgr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.snrcjt.cn/Article/details/gtwyclnnwp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aizwys.cn/Article/details/gtqktbqktb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nwbrower.top/Article/details/gthgsezfpo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.smart0.xyz/Article/details/gtxntvdsuz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgufenzy.top/Article/details/gtryjvjhgi.html

[B07] while 循环
来源：http://dali.ybcxt.top/Article/details/gtissretae.html

Py:   while i < 10: i += 1
来源：http://dali.hfpthk.cn/Article/details/gtazwekyfu.html


<!-- 参考信息 -->