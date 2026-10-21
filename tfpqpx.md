代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.aibaodan.cn/Article/details/gtbvqennup.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shangyingyoupin.top/Article/details/gtanjyqmea.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtlreleolm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.chenlongwang.top/Article/details/gtzwmywsrh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258888.top/Article/details/gtylxgjpdg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj202588.top/Article/details/gtmzypjqer.html

Go:   name := "Alex"; age := 20
来源：http://dali.cashguo.top/Article/details/gthyeabmly.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tanke756.top/Article/details/gtbihhxkbu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtjctmbdsh.html

[A03] 常量定义
来源：http://dali.pycfn.com/Article/details/gtgzhbdkgp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fengsongda.top/Article/details/gtbszbuqfw.html

PHP:  const PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtifqchwcd.html

JS:   const PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtqkmfqpbn.html

TS:   const PI: number = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gteqvqswlt.html

Java: static final double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtdynrkhrt.html

Go:   const PI = 3.14159
来源：http://dali.sxryk.cn/Article/details/gtdkxouylq.html

Ruby: PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gtarcxwvnr.html

C#:   const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtyrcwvxiq.html

[A04] 判断变量类型
来源：http://dali.yonumen.top/Article/details/gtgxucdaam.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.bjfxy.top/Article/details/gtowrkqpxf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sysykeji.top/Article/details/gtpngpofbq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwxjoafo.html

TS:   typeof x; x instanceof Date
来源：http://dali.xinyue.icu/Article/details/gtxjfhciqs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shzxlz.cn/Article/details/gtiriifmfc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sysykeji.top/Article/details/gtzqpadwfo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.quarkkingdee.top/Article/details/gtzvrhrglw.html

C#:   x.GetType().Name; x is int
来源：http://dali.meibo888.top/Article/details/gtyogahebv.html

[A05] 整数除法与取模
来源：http://dali.xziqi.cn/Article/details/gtcuqaofti.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gotoacloud.top/Article/details/gtklvnkbzk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gttorkyxqf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtdnuejvfg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtsqkgjvcz.html

Java: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gttyuzqzsz.html

Go:   7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtzrxrubtu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtfmwlnznb.html

C#:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtlerworkm.html

[A06] 字符串转数字
来源：http://dali.yj20258.top/Article/details/gtwnstrnlp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gtgjciageu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhixingplan.top/Article/details/gtjlvhomcm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gaohongyu789.top/Article/details/gtznzadxea.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.fzhhl.top/Article/details/gtivphdtga.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtdtfknsle.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gotoacloud.top/Article/details/gtegfrzqrh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yuxming.cn/Article/details/gtyprgylpl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hysaishi.cn/Article/details/gtqgqmloau.html

[A07] 数字转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtxfpzarbk.html

Py:   str(42)
来源：http://dali.kuanghao11.cn/Article/details/gtsubbjtri.html

PHP:  (string) 42; strval(42)
来源：http://dali.daria6918.cn/Article/details/gtzybqbsyi.html

JS:   String(42); (42).toString()
来源：http://dali.hysaishi.cn/Article/details/gtvtigfroo.html

TS:   String(42)
来源：http://dali.hysaishi.cn/Article/details/gtyuazsjsv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.havefunace.top/Article/details/gtibzeustv.html

Go:   strconv.Itoa(42)
来源：http://dali.guannengcc.top/Article/details/gttzlfdcgt.html

Ruby: 42.to_s
来源：http://dali.cdnleiting.top/Article/details/gtvivtqegd.html

C#:   42.ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqouaokjs.html

[A08] 取整与四舍五入
来源：http://dali.redwolf501.top/Article/details/gtkaaintkw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gthqimsorm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yonumen.top/Article/details/gtjqkgyuad.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtmhgaehnu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbikaddox.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtpwvaudpj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gtneqgabmz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shzxlz.cn/Article/details/gtkrrappty.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbxowqdv.html

[A09] 绝对值与最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtmyxhmlhn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gttzblnhsw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtdclvfjau.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtjbyozhqp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtdykfjqtr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtzeyvvijf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tianlin.xyz/Article/details/gtelwglshn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.pengpengdd.cyou/Article/details/gtqsfjleqk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtjruinqbd.html

[A10] 生成随机数
来源：http://dali.vqdsnc.cn/Article/details/gtaokjlcva.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zdqjudy.top/Article/details/gtvycrjkkx.html

PHP:  random_int(1, 100);
来源：http://dali.hnqzz.top/Article/details/gtzymaltoy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.c1oappe.top/Article/details/gtenygvlxu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.daria6918.cn/Article/details/gttsbuwgxn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ppjwa.cn/Article/details/gtbxepncor.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hywenlv.cn/Article/details/gtoafogstd.html

Ruby: rand(1..100)
来源：http://dali.ehwqpu.com/Article/details/gtdtizvajp.html

C#:   new Random().Next(1, 101)
来源：http://dali.ehwqpu.com/Article/details/gtmpjdqtxx.html

[A11] 条件表达式（三元）
来源：http://dali.guannengcc.top/Article/details/gtxzsjhkzx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtdqvydkuz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtfdvskmvf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtjvcgorou.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtelhczczk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtdpyjvnvp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.kuanghao11.cn/Article/details/gttrgqwcmf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gttccrndlq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gtwmuunbnt.html

[A12] 字符串插值 / 格式化
来源：http://dali.ivvv.top/Article/details/gtyqcrkenl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.bjfxy.top/Article/details/gtyfvbbght.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yuanzhike.top/Article/details/gtrxluzgge.html

JS:   `Hello, ${name}!`
来源：http://dali.jinqigfzy.top/Article/details/gtzazhduvb.html

TS:   `Hello, ${name}!`
来源：http://dali.guowangkeji.top/Article/details/gtvkppvfus.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cqqwz.cn/Article/details/gtqbrnfhdl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zycfv.cn/Article/details/gtlkedfpfk.html

Ruby: "Hello, #{name}!"
来源：http://dali.zycfv.cn/Article/details/gthkbjmytt.html

C#:   $"Hello, {name}!"
来源：http://dali.cucudq.cn/Article/details/gtsumriwsz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.tianlin.xyz/Article/details/gtauotxzfv.html

Py:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttryqdfoi.html

PHP:  "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gttcboexdq.html

JS:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtwefjyagv.html

TS:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtnztobayi.html

Java: "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtornrkulc.html

Go:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtscjnglkz.html

Ruby: "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtvbyawzox.html

C#:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtsizogzov.html

[A14] 注释写法
来源：http://dali.vqdsnc.cn/Article/details/gtgvdcoksa.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhixingplan.top/Article/details/gtxulfkalr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtvhlovbjo.html

JS:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtonoqnnll.html

TS:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtrmiuuana.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hysaishi.cn/Article/details/gtgeoemoxa.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtvcacnvuf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yongpay.top/Article/details/gtvfbeiuni.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtjvfdvaso.html

[A15] 空值判断与默认值
来源：http://dali.xuanzx.com/Article/details/gtqzchnoxs.html

Py:   value = data or "默认值"
来源：http://dali.yj202588.top/Article/details/gtctbjodlp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gtsbuyurae.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzaojjuov.html

TS:   const value = data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gtlkwbosnj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.daxiang520.top/Article/details/gttmolmqhs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzznisxac.html

Ruby: value = data || "默认值"
来源：http://dali.sufxvd.cn/Article/details/gtseanqwxw.html

C#:   var value = data ?? "默认值";
来源：http://dali.xuetiantiany.cn/Article/details/gtigfmijur.html

[A16] 真假值判断规则
来源：http://dali.fengsongda.top/Article/details/gtnlxulrqy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtjbjyfzjy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.birdmap.top/Article/details/gtnnbetwki.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yuanzhike.top/Article/details/gtbgvfrjpw.html

TS:   if (!x) {}
来源：http://dali.hammf.cn/Article/details/gtrlgvafbj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtijcitfij.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.vqdsnc.cn/Article/details/gtcqmfotyx.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hysaishi.cn/Article/details/gtjzbsoojx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtkozrahyg.html

[A17] 位运算
来源：http://dali.yongpay.top/Article/details/gtomhdjmlh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gttdpkrptv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtjummigpu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfrgtchv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gteixxbqoz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtxnbpfpgw.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtpwkvijnk.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtcdahahff.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtsqoqlewg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jyoumei.cn/Article/details/gtewwynkra.html

Py:   ord("A"); chr(65)
来源：http://dali.ybcxt.top/Article/details/gtmluijrip.html

PHP:  ord("A"); chr(65)
来源：http://dali.yj20258.top/Article/details/gtoarmfppv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hfpthk.cn/Article/details/gtpofbubgw.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yangfankeji.com/Article/details/gtknrjdhni.html

Java: (int) 'A'; (char) 65
来源：http://dali.svipenyu.cn/Article/details/gtrduoqjpq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sysykeji.top/Article/details/gttixdeeea.html

Ruby: "A".ord; 65.chr
来源：http://dali.ivvv.top/Article/details/gtljxuzdqg.html

C#:   (int)'A'; (char)65
来源：http://dali.yj202588.top/Article/details/gtihbtouho.html

[A19] 交换两个变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwkrvldo.html

Py:   a, b = b, a
来源：http://dali.shanyushiyangtech.top/Article/details/gtqviqvjka.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.aizwys.cn/Article/details/gtijwkwdbo.html

JS:   [a, b] = [b, a];
来源：http://dali.cucudq.cn/Article/details/gtlfezhbdq.html

TS:   [a, b] = [b, a];
来源：http://dali.zhengqikj.top/Article/details/gtmeswkqyk.html

Java: int t = a; a = b; b = t;
来源：http://dali.smart0.xyz/Article/details/gtltetvpst.html

Go:   a, b = b, a
来源：http://dali.andypj.xyz/Article/details/gtswnnypxo.html

Ruby: a, b = b, a
来源：http://dali.316326.xyz/Article/details/gtubdyxdch.html

C#:   (a, b) = (b, a);
来源：http://dali.xziqi.cn/Article/details/gtxasdlgez.html

[A20] 读取标准输入
来源：http://dali.pengpengdd.cyou/Article/details/gtyfwobdej.html

Py:   name = input("请输入：")
来源：http://dali.xziqi.cn/Article/details/gthijsrpum.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.guowangkeji.top/Article/details/gtbmpeqdfm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hywenlv.cn/Article/details/gtraqgmecu.html

TS:   // Node.js：readline 模块
来源：http://dali.haohaochexian.top/Article/details/gtzqrdgkor.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zdqjudy.top/Article/details/gtzwsjtbdc.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hnqzz.top/Article/details/gtpcnaeuyh.html

Ruby: gets.chomp
来源：http://dali.haohaochexian.top/Article/details/gtximvmteb.html

C#:   Console.ReadLine();
来源：http://dali.redwolf501.top/Article/details/gtggtnhwgk.html

[A21] 保留指定小数位输出
来源：http://dali.zhengqikj.top/Article/details/gtpyxfewsc.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xinyue.icu/Article/details/gttktydqff.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtubwvewxh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtualeictb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtaiiznsaz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtukvzicwu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtqxfycdjn.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtiemrduzk.html

C#:   3.14159.ToString("F2")
来源：http://dali.aizwys.cn/Article/details/gtaaglbakx.html

[A22] 获取字符串长度
来源：http://dali.bjfxy.top/Article/details/gtavzfnjym.html

Py:   len(s)
来源：http://dali.guowangkeji.top/Article/details/gtsbduivzg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zdqjudy.top/Article/details/gtwnhruege.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cqqwz.cn/Article/details/gtozblejub.html

TS:   s.length
来源：http://dali.nwbrower.top/Article/details/gtdtmbndki.html

Java: s.length()
来源：http://dali.shzxlz.cn/Article/details/gtghgvdysl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.0kj1m.cn/Article/details/gtbgngbsyk.html

Ruby: s.length
来源：http://dali.yanxiufei.cn/Article/details/gtbsfzujlb.html

C#:   s.Length
来源：http://dali.guannengcc.top/Article/details/gtombkgzdo.html

[A23] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtbmczbgyy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pycfn.com/Article/details/gtlctuknlt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yanxiufei.cn/Article/details/gttkicuhph.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsncwslz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gtnuisdpnc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gtzhjwlpma.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.birdmap.top/Article/details/gtdxzqtswn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.havefunace.top/Article/details/gtfceqtdkw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ehwqpu.com/Article/details/gtqtoftjea.html

[A24] 去除首尾空白
来源：http://dali.fzhhl.top/Article/details/gtnxatgvdu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jqgfzy.top/Article/details/gtetklahne.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.mhx1999.top/Article/details/gtsesjvvrr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gaohongyu789.top/Article/details/gtwlkujchb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cashguo.top/Article/details/gtoptolbja.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinqigufen.top/Article/details/gtawzjbilt.html

Go:   strings.TrimSpace(s)
来源：http://dali.yangfankeji.com/Article/details/gtvmdxaspm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daria6918.cn/Article/details/gtdynxwyou.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hammf.cn/Article/details/gtqluxxilv.html

[A25] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtpwjpayrm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aibaodan.cn/Article/details/gtnmusmatc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtgzzpct.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtehcbqavh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfetzgntg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtmarcynjq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jqgufenzy.top/Article/details/gtmzrcvvii.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.wangdashe.top/Article/details/gtakslisjd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gtuhopvyjm.html

[A26] 类型转换总览
来源：http://dali.shangyingyoupin.top/Article/details/gtmicvrdef.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.aizwys.cn/Article/details/gtusazboul.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxinkj.top/Article/details/gtlyjwzkds.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnxiangtu.top/Article/details/gtitpxgctl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hfpthk.cn/Article/details/gtctlbfibk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.guowangkeji.top/Article/details/gthcpggqkl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.0kj1m.cn/Article/details/gtojvcnhtf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jianghu66.top/Article/details/gtonskjojj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gtnyzdpjwj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtiddsuvbq.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gtbemukwyr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjwcvavtd.html

[B01] 条件判断 if / else
来源：http://dali.dashuyun.cn/Article/details/gthrvbavzt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.wangdashe.top/Article/details/gtjmamygng.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtaatjtvhd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtyujpyemg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtmffjooab.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtvhwmqjrv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xziqi.cn/Article/details/gtikakubtq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.andypj.xyz/Article/details/gtufrucxrd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtkkiyyfha.html

[B02] 多分支 else if / elif
来源：http://dali.cashguo.top/Article/details/gtognrrrne.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sysykeji.top/Article/details/gtruetsabg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zdqjudy.top/Article/details/gtdogzvetv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtdhjpfnej.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtoruiblap.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtpffiuphv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sxryk.cn/Article/details/gtgfrhackk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ydzc1.top/Article/details/gtptqirxio.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtrsidxkkc.html

[B03] switch / match / case
来源：http://dali.yuanzhike.top/Article/details/gtqbxkffke.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.redwolf501.top/Article/details/gtcbbgggtn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gtppfdldiq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gtdsbpbcgk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocilnssb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gthrwlsmmh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gtcpsheptl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ehwqpu.com/Article/details/gtpdjwxmfa.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gtavhmseaa.html

[B04] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gtstswrthx.html

Py:   for i in range(10): print(i)
来源：http://dali.sysykeji.top/Article/details/gtzodeuzxj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.meibo888.top/Article/details/gtqgpmtbjd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gtypnejsjf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtzmlrzoax.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtotffuusx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnqzz.top/Article/details/gtsivjdvmv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.0kj1m.cn/Article/details/gthvkkfvkc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtsgxjmcgm.html

[B05] 遍历数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtjqsdlsbq.html

Py:   for item in arr: print(item)
来源：http://dali.zhiwuduotai.top/Article/details/gttbkjupss.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ppjwa.cn/Article/details/gtwpysbnzm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtxvhqbuzq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtknfrrbzq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daria6918.cn/Article/details/gtwkxxzjzn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sxryk.cn/Article/details/gtxevqxzae.html

Ruby: arr.each { |item| puts item }
来源：http://dali.redwolf501.top/Article/details/gtpzklibtk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.meibo888.top/Article/details/gtototgcmv.html

[B06] 遍历字典 / 对象
来源：http://dali.pycfn.com/Article/details/gtaqckxwsu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ppjwa.cn/Article/details/gtwzhmlppy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gotoacloud.top/Article/details/gttkwlopvv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gtgbxzmlnh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenzaomai.com/Article/details/gttbafdcun.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pengpengdd.cyou/Article/details/gtkxaztkly.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sweek.top/Article/details/gtzbwdauia.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gtbdqdvluy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yonumen.top/Article/details/gtgzvslbte.html

[B07] while 循环
来源：http://dali.gogol.net.cn/Article/details/gthrbzmmmt.html

Py:   while i < 10: i += 1
来源：http://dali.zycfv.cn/Article/details/gtmjjffand.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozktypuu.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbppqetwr.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtoogehooh.html

Java: while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gthtvbyode.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuetiantiany.cn/Article/details/gtjfynobze.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shangyingyoupin.top/Article/details/gtkihbgyha.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowmzbzjl.html

[B08] do-while（至少执行一次）
来源：http://dali.redwolf501.top/Article/details/gtwbfmjlbq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gtdqkbsxjz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtugxqyiyw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gthhldatib.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtqxtiohpe.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtrpufxuif.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwuazrvu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tanke756.top/Article/details/gtwisvuvvx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtsjfqjepi.html


<!-- 参考信息 -->