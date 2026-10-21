代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.cashguo.top/Article/details/gtysvosqkw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yueranfly.top/Article/details/gtxdanhglo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtshuaaoff.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtfikjdqqs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.aibaodan.cn/Article/details/gtcwxeeeco.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtltifceyp.html

Go:   name := "Alex"; age := 20
来源：http://dali.yongpay.top/Article/details/gtcldqcxxw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sufxvd.cn/Article/details/gtswivdhof.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtogbpvaxd.html

[A03] 常量定义
来源：http://dali.sweek.top/Article/details/gtthxflvuv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnqzz.top/Article/details/gtqbwdtjsv.html

PHP:  const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtutfyguoa.html

JS:   const PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gthplbmjmz.html

TS:   const PI: number = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtkdqvolxm.html

Java: static final double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtktvrnzci.html

Go:   const PI = 3.14159
来源：http://dali.sysykeji.top/Article/details/gtfcxeytpb.html

Ruby: PI = 3.14159
来源：http://dali.ehwqpu.com/Article/details/gtkyrfziua.html

C#:   const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtrlooawnc.html

[A04] 判断变量类型
来源：http://dali.cucudq.cn/Article/details/gtakcprqqb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gtyrrnzdgw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangdashe.top/Article/details/gtzctkcllp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gtfskhiyqk.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gtgvfogylr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ydzc1.top/Article/details/gtuyxxorxf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hywenlv.cn/Article/details/gtivmectdb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj20258.top/Article/details/gtaekwcdfs.html

C#:   x.GetType().Name; x is int
来源：http://dali.gogol.net.cn/Article/details/gtirdcezsa.html

[A05] 整数除法与取模
来源：http://dali.hfpthk.cn/Article/details/gtizoywuvy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.snrcjt.cn/Article/details/gthtomfrzu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtwcstqlcr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtwmotbvav.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gthpkogtuo.html

Java: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtqvzzsuzs.html

Go:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtyliblyst.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtyzzuruqx.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsfzxkfn.html

[A06] 字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtnkixdyts.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigufen.top/Article/details/gtvvuklija.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hywenlv.cn/Article/details/gtljapjgvt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gtgvtigkbr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtxstnowfv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shzxlz.cn/Article/details/gtogiellvs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gtkqwbdany.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhixingplan.top/Article/details/gtrvypivyc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sweek.top/Article/details/gtktpwsyne.html

[A07] 数字转字符串
来源：http://dali.tanke756.top/Article/details/gtjvzhbmsk.html

Py:   str(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqczpgrb.html

PHP:  (string) 42; strval(42)
来源：http://dali.gotoacloud.top/Article/details/gtuwmxopxj.html

JS:   String(42); (42).toString()
来源：http://dali.chenlongwang.top/Article/details/gtpwadflgr.html

TS:   String(42)
来源：http://dali.svipenyu.cn/Article/details/gtysajfbxq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hnqzz.top/Article/details/gtpyckihco.html

Go:   strconv.Itoa(42)
来源：http://dali.gogol.net.cn/Article/details/gtlpimklam.html

Ruby: 42.to_s
来源：http://dali.gotoacloud.top/Article/details/gtkrrllcii.html

C#:   42.ToString()
来源：http://dali.tanke756.top/Article/details/gtkezbghyk.html

[A08] 取整与四舍五入
来源：http://dali.yvedp.cn/Article/details/gtnvhmrvqo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtpbodvawl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shangyingyoupin.top/Article/details/gtpzojgdak.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtonvksoiq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shuidangran.top/Article/details/gtqilmkizq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gtcydupbku.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtwbwumria.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.wangdashe.top/Article/details/gtftsomsya.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.birdmap.top/Article/details/gtidauzjki.html

[A09] 绝对值与最大最小值
来源：http://dali.jianghu66.top/Article/details/gtyzhxqyat.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.meibo888.top/Article/details/gtflasojrf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtwafsuwpn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtcuvyjdrx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqewhwrpn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gthdhqudfl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdxhbkgx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.tian-w.cn/Article/details/gtzqykdscw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtbicokgec.html

[A10] 生成随机数
来源：http://dali.ydzc1.top/Article/details/gtncycsbhb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jiagoushi.top/Article/details/gtkpnbvozu.html

PHP:  random_int(1, 100);
来源：http://dali.wangdashe.top/Article/details/gtlgujgnka.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ppjwa.cn/Article/details/gteszaopfj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cqqwz.cn/Article/details/gtduxegaqp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tian-w.cn/Article/details/gtbmavrohf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hongshengwenyu.top/Article/details/gtzvgopdml.html

Ruby: rand(1..100)
来源：http://dali.wangshuangyany.cn/Article/details/gtwrwlmcka.html

C#:   new Random().Next(1, 101)
来源：http://dali.fengsongda.top/Article/details/gtyimddddz.html

[A11] 条件表达式（三元）
来源：http://dali.redwolf501.top/Article/details/gtgzoezujx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jyoumei.cn/Article/details/gtsogyanbq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gtsovhleph.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gttefjsiww.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtxwdnocmq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtlivvxwrj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.fzhhl.top/Article/details/gtibpdidgy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gttvuvfsvf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gtvtqzqfwk.html

[A12] 字符串插值 / 格式化
来源：http://dali.yj20258888.top/Article/details/gtufwgefsm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yuanzhike.top/Article/details/gtscpdgwlg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ydzc1.top/Article/details/gtrxatsymw.html

JS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gtggzrfdmj.html

TS:   `Hello, ${name}!`
来源：http://dali.c1oappe.top/Article/details/gtiykwmlbp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.ydzc1.top/Article/details/gtxulvjgef.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yueranfly.top/Article/details/gtvtmbqjpc.html

Ruby: "Hello, #{name}!"
来源：http://dali.iojbl.cn/Article/details/gtkwkbqlgm.html

C#:   $"Hello, {name}!"
来源：http://dali.ybcxt.top/Article/details/gtvijlskaz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gogol.net.cn/Article/details/gtkhbesfzb.html

Py:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gthyflfwer.html

PHP:  "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtjtznlyat.html

JS:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtaulklzox.html

TS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtnefbeuzc.html

Java: "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtfnimhovx.html

Go:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtvmdcaokx.html

Ruby: "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtulcctccr.html

C#:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtgeitxtzb.html

[A14] 注释写法
来源：http://dali.havefunace.top/Article/details/gtzjuaybyo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhongyouzk.top/Article/details/gtwjzroljl.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gtdhdaldqq.html

JS:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtbxymqzyd.html

TS:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtuljeifjv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yuxming.cn/Article/details/gtghbxmasr.html

Go:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtykgfrooe.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ppjwa.cn/Article/details/gtfsmhgmrf.html

C#:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtsbvhkezk.html

[A15] 空值判断与默认值
来源：http://dali.pycfn.com/Article/details/gtoqbxfkfz.html

Py:   value = data or "默认值"
来源：http://dali.fengsongda.top/Article/details/gtefrmauvz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.snrcjt.cn/Article/details/gtutkxhirl.html

JS:   const value = data ?? "默认值";
来源：http://dali.yj20258888.top/Article/details/gtnvpcuzor.html

TS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtncsjvkbw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ybcxt.top/Article/details/gtfrdaytap.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jlsjyb.cn/Article/details/gtwunniufi.html

Ruby: value = data || "默认值"
来源：http://dali.jqgfzy.top/Article/details/gtzebtrbvr.html

C#:   var value = data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gtzmfvgxzp.html

[A16] 真假值判断规则
来源：http://dali.cucudq.cn/Article/details/gtllncpefx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zdqjudy.top/Article/details/gttlqtfqgh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ppjwa.cn/Article/details/gtqpgxgnvo.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.kuanghao11.cn/Article/details/gtlwphigrk.html

TS:   if (!x) {}
来源：http://dali.yj20258888.top/Article/details/gtlhkidlcd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.tanke756.top/Article/details/gtbgpbqohf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tanke756.top/Article/details/gtbfkrdjcr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cqqwz.cn/Article/details/gtclivxlkb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.pycfn.com/Article/details/gtxekyiavy.html

[A17] 位运算
来源：http://dali.tianlin.xyz/Article/details/gtjmkcpeea.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmlvkjed.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtykikfonm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtfjnccxzl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtenmnfsau.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtoweodevr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtlasmnvch.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtlfmvkmui.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtknbliwve.html

[A18] 字符与 ASCII 码互转
来源：http://dali.guowangkeji.top/Article/details/gtfadpnkzc.html

Py:   ord("A"); chr(65)
来源：http://dali.sweek.top/Article/details/gtuktihrxy.html

PHP:  ord("A"); chr(65)
来源：http://dali.nanxinkj.top/Article/details/gttzdidgtz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cqqwz.cn/Article/details/gtmpvucbiv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shuidangran.top/Article/details/gtvaeqhzfj.html

Java: (int) 'A'; (char) 65
来源：http://dali.pycfn.com/Article/details/gtxtjptllw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zycfv.cn/Article/details/gtudjqqcmg.html

Ruby: "A".ord; 65.chr
来源：http://dali.xuanzx.com/Article/details/gtidvykcfb.html

C#:   (int)'A'; (char)65
来源：http://dali.yonumen.top/Article/details/gtrnolkhtw.html

[A19] 交换两个变量
来源：http://dali.sweek.top/Article/details/gtjxxfjqru.html

Py:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gtymfqhmns.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinghuilouyu.cn/Article/details/gtpecvfdid.html

JS:   [a, b] = [b, a];
来源：http://dali.cucudq.cn/Article/details/gtcdppsacl.html

TS:   [a, b] = [b, a];
来源：http://dali.shzxlz.cn/Article/details/gthgsswkou.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj202588.top/Article/details/gtsdnqmflw.html

Go:   a, b = b, a
来源：http://dali.kuanghao11.cn/Article/details/gtzbrwjzgh.html

Ruby: a, b = b, a
来源：http://dali.nanxinkj.top/Article/details/gturuyvpgk.html

C#:   (a, b) = (b, a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdqhmswp.html

[A20] 读取标准输入
来源：http://dali.gaohongyu789.top/Article/details/gtuwkrgtuu.html

Py:   name = input("请输入：")
来源：http://dali.hnqzz.top/Article/details/gtqbiyjrry.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.nanxuanxn.top/Article/details/gtsvthawad.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pengpengdd.cyou/Article/details/gtbmruaakb.html

TS:   // Node.js：readline 模块
来源：http://dali.ivvv.top/Article/details/gtwwunspij.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhijiandao.cn/Article/details/gtlvcdzffq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tanke756.top/Article/details/gtzuuuvcyt.html

Ruby: gets.chomp
来源：http://dali.yj202588.top/Article/details/gtibnqamrs.html

C#:   Console.ReadLine();
来源：http://dali.pengpengdd.cyou/Article/details/gtgjhhshib.html

[A21] 保留指定小数位输出
来源：http://dali.cucudq.cn/Article/details/gtszntkrca.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yj202588.top/Article/details/gtnuxvpedf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtreeoqzfn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtmwlalyqc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtdjrfriec.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gthghhunun.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtlgbujjut.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gtrodmlzkh.html

C#:   3.14159.ToString("F2")
来源：http://dali.wangdashe.top/Article/details/gtdpaxtxcf.html

[A22] 获取字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gteevvkzyf.html

Py:   len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtnamsontx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaawjhsq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenlongwang.top/Article/details/gtknpvruxp.html

TS:   s.length
来源：http://dali.sxryk.cn/Article/details/gteumtvkyk.html

Java: s.length()
来源：http://dali.yueranfly.top/Article/details/gtqmkcjklg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenlongwang.top/Article/details/gtijgqwswl.html

Ruby: s.length
来源：http://dali.sysykeji.top/Article/details/gtwxdxxxye.html

C#:   s.Length
来源：http://dali.ydzc1.top/Article/details/gtosddnvlj.html

[A23] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtasrwohnj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gtlvlqiecg.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.haohaochexian.top/Article/details/gtuhxfkjnh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gtwczrfpwe.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtdlbgskdn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtmwdxghlu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ppjwa.cn/Article/details/gtbxegvpuf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtgftnmgto.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ybcxt.top/Article/details/gtbgziaukq.html

[A24] 去除首尾空白
来源：http://dali.aizwys.cn/Article/details/gtucolwmte.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.vqdsnc.cn/Article/details/gtbxoraoim.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sufxvd.cn/Article/details/gtyndwmlkc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtsebbbhuh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gtfpvxpahl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hongshengwenyu.top/Article/details/gtltsmyfcb.html

Go:   strings.TrimSpace(s)
来源：http://dali.shuidangran.top/Article/details/gttvxtlxqu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhoulong.xyz/Article/details/gtzramlfts.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.aibaodan.cn/Article/details/gtgbgmnrhy.html

[A25] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtlfcdupxz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zycfv.cn/Article/details/gtzcnszivz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.daria6918.cn/Article/details/gtnlyoeojy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tanke756.top/Article/details/gttltwqoji.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtspzyxybj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwixrjxnc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sufxvd.cn/Article/details/gtylvzuvvb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pycfn.com/Article/details/gttgiuvklu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.iojbl.cn/Article/details/gtmwnmbmqb.html

[A26] 类型转换总览
来源：http://dali.tian-w.cn/Article/details/gtqnjtccry.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.haohaochexian.top/Article/details/gtrekyvxpq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hfpthk.cn/Article/details/gtkdbpkdon.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ybcxt.top/Article/details/gtoblozjpw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.316326.xyz/Article/details/gtvhezmcsj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gtpuqackcx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dashuyun.cn/Article/details/gtkxlgzfhm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258.top/Article/details/gttvwvixdq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtstssggti.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwlcxjwwo.html

B. 流程控制
来源：http://dali.chenjidiqi.icu/Article/details/gtibolpefq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtybvdsrrl.html

[B01] 条件判断 if / else
来源：http://dali.svipenyu.cn/Article/details/gtcnjwddhh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hywenlv.cn/Article/details/gtgfsireav.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj202588.top/Article/details/gtekpwshhc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtghuqllzc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gtogotuzes.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtgzxmsmyi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.9152youxi.cn/Article/details/gtukvglsqt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daria6918.cn/Article/details/gtphugegjz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gtpndtfkaa.html

[B02] 多分支 else if / elif
来源：http://dali.fzhhl.top/Article/details/gtcayvqxct.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pengpengdd.cyou/Article/details/gtctmflanv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtobfomdin.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtqqcfvtfp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtflthregv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtulzfkzys.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.kuanghao11.cn/Article/details/gtdkacgmwq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dianchejie.cn/Article/details/gtyirtlkyk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gttbcangck.html

[B03] switch / match / case
来源：http://dali.zhengqikj.top/Article/details/gtqaicsjkh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gotoacloud.top/Article/details/gtuxqjoikt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtlbtastdh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtntbbnvoh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtdrslnxld.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gthcxzwmff.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tanke756.top/Article/details/gtsckrvmes.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpnhqcci.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gtsdkllgkg.html

[B04] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtwpmdamcy.html

Py:   for i in range(10): print(i)
来源：http://dali.havefunace.top/Article/details/gtgxfzgtrc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.kuanghao11.cn/Article/details/gticbbhnzo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ehwqpu.com/Article/details/gtcncgtucp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gtaafalumo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.pycfn.com/Article/details/gtmmechhzz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.haohaochexian.top/Article/details/gtgwjhacga.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guannengcc.top/Article/details/gtemwcfucy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtcqwmzllu.html

[B05] 遍历数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtfohxpxhi.html

Py:   for item in arr: print(item)
来源：http://dali.fzhhl.top/Article/details/gtdtzljmqb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.wangdashe.top/Article/details/gtmyicitwd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtyahcbrpi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tianlin.xyz/Article/details/gttgukaxlg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gtapnatnsf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tianlin.xyz/Article/details/gttupcxmhl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.316326.xyz/Article/details/gtybkphxin.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtowduquwn.html

[B06] 遍历字典 / 对象
来源：http://dali.yongpay.top/Article/details/gtaywrovfd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ybcxt.top/Article/details/gtodshutjb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dashuyun.cn/Article/details/gtsjwxyvei.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gtyitrazhc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gtvbpammnl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuanzx.com/Article/details/gtdnilerbe.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.kuanghao11.cn/Article/details/gtsjhumlzz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tianlin.xyz/Article/details/gttvjhsohe.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.haohaochexian.top/Article/details/gttjncwupx.html

[B07] while 循环
来源：http://dali.yangfankeji.com/Article/details/gtdmkygjuq.html

Py:   while i < 10: i += 1
来源：http://dali.hammf.cn/Article/details/gttqodvbnr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shzxlz.cn/Article/details/gtqyyefxgg.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtkiwnppss.html

TS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtnfovbylr.html

Java: while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtqoigacgz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangshuangyany.cn/Article/details/gtwykffrfe.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxuanxn.top/Article/details/gtunytklvw.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtuvcklfbk.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxuanxn.top/Article/details/gtaltbgnkz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangshuangyany.cn/Article/details/gtjzflbyin.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtbcqzxjwv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtxxiswkiu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtltqewfpf.html

Java: do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtzhvnliir.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ydzc1.top/Article/details/gtnfombxap.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hysaishi.cn/Article/details/gtouhjqwuf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtmnsxcyoa.html


<!-- 参考信息 -->