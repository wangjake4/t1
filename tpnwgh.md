代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.andypj.xyz/Article/details/gtprzxpfpj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nwbrower.top/Article/details/gtxqzfpsfy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtqvsrlxbj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhixingplan.top/Article/details/gteurwqhuj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xinyue.icu/Article/details/gtewbusdqz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gtfuscyexh.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gtxenbwybu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cashguo.top/Article/details/gtbrigoyke.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gtqfxdmczr.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gtdnwvemnq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hywenlv.cn/Article/details/gtfmpfpurr.html

PHP:  const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtzcoqpsst.html

JS:   const PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtehbpajsd.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtnsqgykhh.html

Java: static final double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtaccpnnqz.html

Go:   const PI = 3.14159
来源：http://dali.fzhhl.top/Article/details/gtyyiqdfjn.html

Ruby: PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gthandfywr.html

C#:   const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtdepjjuct.html

[A04] 判断变量类型
来源：http://dali.xylfe.cn/Article/details/gttyxdgnnv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.birdmap.top/Article/details/gtepcbtjix.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbgoiyor.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gtvyltqjhu.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gtdnnohdba.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.svipenyu.cn/Article/details/gtxivakqvg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yvedp.cn/Article/details/gtidggbzua.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jianghu66.top/Article/details/gtglstnegp.html

C#:   x.GetType().Name; x is int
来源：http://dali.jqgfzy.top/Article/details/gtndbpyglv.html

[A05] 整数除法与取模
来源：http://dali.redwolf501.top/Article/details/gtdouluupc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.iojbl.cn/Article/details/gtcnwvmrfy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtckxylgmm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gtjwdzrheq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtutwxbxev.html

Java: 7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtsnfzhjab.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtijxzjtxx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtkluzcgkr.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeymuahp.html

[A06] 字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtrohhbllk.html

Py:   int("42"); float("3.14")
来源：http://dali.hywenlv.cn/Article/details/gtovhmjgyk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cheryme.top/Article/details/gtmltnrbze.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxjxfqfb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gtiygtsxcz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.smart0.xyz/Article/details/gtbmftcnvz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhengqikj.top/Article/details/gtsswqrgxa.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.iojbl.cn/Article/details/gtcgnwyids.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tian-w.cn/Article/details/gtnodlvore.html

[A07] 数字转字符串
来源：http://dali.c1oappe.top/Article/details/gtpylsehjm.html

Py:   str(42)
来源：http://dali.yangfankeji.com/Article/details/gtpohrohrf.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguqybvoz.html

JS:   String(42); (42).toString()
来源：http://dali.sxryk.cn/Article/details/gtmlyevpzy.html

TS:   String(42)
来源：http://dali.birdmap.top/Article/details/gtosepyrsy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shangyingyoupin.top/Article/details/gtglzaubka.html

Go:   strconv.Itoa(42)
来源：http://dali.zhixingplan.top/Article/details/gthlophwry.html

Ruby: 42.to_s
来源：http://dali.hnqzz.top/Article/details/gtyedcddhv.html

C#:   42.ToString()
来源：http://dali.xuanzx.com/Article/details/gtdsqykonv.html

[A08] 取整与四舍五入
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrmrknul.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbelsprlc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.fzhhl.top/Article/details/gtdtkwpgmx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtnslskngr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jqgfzy.top/Article/details/gtxjdhdyag.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtybvoxjog.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtntzavovx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcklckfak.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gtnsvubcpr.html

[A09] 绝对值与最大最小值
来源：http://dali.ybcxt.top/Article/details/gtsjmtxnrh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gthrnbtbla.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtilagevgc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtdvaagjkc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtdsmwaxkz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtnpxyypcz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.aizwys.cn/Article/details/gtrjwccceg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.chenlongwang.top/Article/details/gtshvnknos.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtpuyfxfqm.html

[A10] 生成随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtcxfizsew.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jinqigfzy.top/Article/details/gtnsbymwyy.html

PHP:  random_int(1, 100);
来源：http://dali.yvedp.cn/Article/details/gtgjdjrzox.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nwbrower.top/Article/details/gtxuezhnnn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.kuanghao11.cn/Article/details/gtdlnroggd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.aibaodan.cn/Article/details/gtxzsdaqnw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yongpay.top/Article/details/gtjcvfmkgw.html

Ruby: rand(1..100)
来源：http://dali.hammf.cn/Article/details/gtazylwlrq.html

C#:   new Random().Next(1, 101)
来源：http://dali.snrcjt.cn/Article/details/gtggtmbzwf.html

[A11] 条件表达式（三元）
来源：http://dali.xinyue.icu/Article/details/gtcfnwbrdq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xylfe.cn/Article/details/gtubolsdxt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtekewtwsu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtflueqhof.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtmulmvzps.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtncvbisny.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.wangshuangyany.cn/Article/details/gtawlwgwuq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gtwggkvwhp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnotpcrtx.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhongyouzk.top/Article/details/gtpqbzzhzq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jyoumei.cn/Article/details/gtevpmbozf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.tianlin.xyz/Article/details/gtapafjyow.html

JS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gtcgnygoro.html

TS:   `Hello, ${name}!`
来源：http://dali.yuxming.cn/Article/details/gtczohtlec.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.quarkkingdee.top/Article/details/gtdygkrwtm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yongpay.top/Article/details/gtngoyljgl.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtdajzelvt.html

C#:   $"Hello, {name}!"
来源：http://dali.svipenyu.cn/Article/details/gtgecrcgjv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhengqikj.top/Article/details/gtghcvlnmg.html

Py:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtlfzvshtl.html

PHP:  "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gttarbomxr.html

JS:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtqdgbhfkl.html

TS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtoberdegn.html

Java: "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtikthlmkd.html

Go:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtcubnsgkf.html

Ruby: "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoxpfxrb.html

C#:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtxnqciaeo.html

[A14] 注释写法
来源：http://dali.jyoumei.cn/Article/details/gtnmmgamnk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jiagoushi.top/Article/details/gtanujaoam.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtmcwnjemd.html

JS:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gtjadaieji.html

TS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gttncggysu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gzhubu.top/Article/details/gtsfvgxyrj.html

Go:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtmmfgatjn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.wangshuangyany.cn/Article/details/gtwxkdxihx.html

C#:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtcwujyaoa.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpekfacws.html

Py:   value = data or "默认值"
来源：http://dali.zycfv.cn/Article/details/gtnsmfgkbz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gteemzifnq.html

JS:   const value = data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gtkcjqtnmk.html

TS:   const value = data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gtzsxqamnm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.nwbrower.top/Article/details/gtyrbcwqvx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.wangshuangyany.cn/Article/details/gtxjkvlehe.html

Ruby: value = data || "默认值"
来源：http://dali.0kj1m.cn/Article/details/gtdvzqslwh.html

C#:   var value = data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gtcgkammya.html

[A16] 真假值判断规则
来源：http://dali.ybcxt.top/Article/details/gtekqrpihc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.smart0.xyz/Article/details/gtcfvsjwht.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnqzz.top/Article/details/gthfcagwls.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jianghu66.top/Article/details/gtdynucjwj.html

TS:   if (!x) {}
来源：http://dali.havefunace.top/Article/details/gtwinjnsta.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yongpay.top/Article/details/gtcccszeii.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenzaomai.com/Article/details/gtnxphmkdw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.aizwys.cn/Article/details/gtljuzipkn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jyoumei.cn/Article/details/gtlfkacynt.html

[A17] 位运算
来源：http://dali.316326.xyz/Article/details/gtbesafpcu.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtlwzqwnii.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.daria6918.cn/Article/details/gtuwhxxqwt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtvhkmpeqh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtqfkggmzf.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gtjmfzwvoy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtjrrcaiun.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtstjzuojl.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtapwadpvy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shzxlz.cn/Article/details/gtqyifbwtj.html

Py:   ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtlcophoxr.html

PHP:  ord("A"); chr(65)
来源：http://dali.birdmap.top/Article/details/gttezbdkpw.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cucudq.cn/Article/details/gtxmrpgdnu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shuidangran.top/Article/details/gtzmkjxbzw.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuetiantiany.cn/Article/details/gtgqmrnkqj.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yonumen.top/Article/details/gtbedxcuui.html

Ruby: "A".ord; 65.chr
来源：http://dali.ivvv.top/Article/details/gtqmjyiwgu.html

C#:   (int)'A'; (char)65
来源：http://dali.haohaochexian.top/Article/details/gtashgsyld.html

[A19] 交换两个变量
来源：http://dali.tianlin.xyz/Article/details/gtejntmbdh.html

Py:   a, b = b, a
来源：http://dali.yuxming.cn/Article/details/gtukxwzzdt.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sufxvd.cn/Article/details/gtedsiovfn.html

JS:   [a, b] = [b, a];
来源：http://dali.feifeiyinyue.top/Article/details/gtzevkxphs.html

TS:   [a, b] = [b, a];
来源：http://dali.snrcjt.cn/Article/details/gtatrbgbuj.html

Java: int t = a; a = b; b = t;
来源：http://dali.ydzc1.top/Article/details/gtqjbjwpzj.html

Go:   a, b = b, a
来源：http://dali.havefunace.top/Article/details/gtbsxogkmk.html

Ruby: a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gtiktabsuy.html

C#:   (a, b) = (b, a);
来源：http://dali.yuxming.cn/Article/details/gtzvmzovoh.html

[A20] 读取标准输入
来源：http://dali.yonumen.top/Article/details/gtaxohsobe.html

Py:   name = input("请输入：")
来源：http://dali.ehwqpu.com/Article/details/gtuovdftkc.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shuidangran.top/Article/details/gthzicdcyc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.quarkkingdee.top/Article/details/gtcwhhulpv.html

TS:   // Node.js：readline 模块
来源：http://dali.jianghu66.top/Article/details/gtnogzqnxd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.redwolf501.top/Article/details/gtyeybrjdf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jqgufenzy.top/Article/details/gtrrxdfnmp.html

Ruby: gets.chomp
来源：http://dali.hysaishi.cn/Article/details/gtxwcicegk.html

C#:   Console.ReadLine();
来源：http://dali.redwolf501.top/Article/details/gtigbwxywr.html

[A21] 保留指定小数位输出
来源：http://dali.yueranfly.top/Article/details/gtyeordmht.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigfzy.top/Article/details/gtafxohbjo.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtokonyasj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtcwgbptjp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtbenvsyla.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gtjkeoejap.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gtnposixny.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gthllgxjip.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhiwuduotai.top/Article/details/gtzvanjnqu.html

[A22] 获取字符串长度
来源：http://dali.gogol.net.cn/Article/details/gteoiqxhig.html

Py:   len(s)
来源：http://dali.dianchejie.cn/Article/details/gtehntyzwr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.feifeiyinyue.top/Article/details/gtfurvzyih.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xuetiantiany.cn/Article/details/gtidfcsccl.html

TS:   s.length
来源：http://dali.yvedp.cn/Article/details/gtabpejlgg.html

Java: s.length()
来源：http://dali.cdnleiting.top/Article/details/gtnujlgxbe.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.birdmap.top/Article/details/gtmyrkpcpr.html

Ruby: s.length
来源：http://dali.ehwqpu.com/Article/details/gtxcxhqipg.html

C#:   s.Length
来源：http://dali.guannengcc.top/Article/details/gtprjtmowg.html

[A23] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gthsqncnfb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hywenlv.cn/Article/details/gtxtittrgt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.daria6918.cn/Article/details/gtadpiqafz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gtjwuzeqbn.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gtkqnxfzdj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gterldedlq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj20258888.top/Article/details/gtimizpneh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtyamnjpyf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hnqzz.top/Article/details/gtaiutcgmt.html

[A24] 去除首尾空白
来源：http://dali.dianchejie.cn/Article/details/gtopcaaopu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xziqi.cn/Article/details/gtpbrbvugb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xziqi.cn/Article/details/gteickjudx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.dashuyun.cn/Article/details/gtlyfzhrzt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.quarkkingdee.top/Article/details/gtrtzthvfi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.fengsongda.top/Article/details/gtnhpnlwyo.html

Go:   strings.TrimSpace(s)
来源：http://dali.pycfn.com/Article/details/gtwmeuluau.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.316326.xyz/Article/details/gtagcxlbzi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.meibo888.top/Article/details/gttsuhctgq.html

[A25] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtuabmatys.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gotoacloud.top/Article/details/gtwiscjrna.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanmnrkuw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yongpay.top/Article/details/gtismqhwbs.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gthzzfqrzi.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shzxlz.cn/Article/details/gtzkmaklzf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gtujzycbqz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shuidangran.top/Article/details/gtxkovpuut.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gtykozrcgh.html

[A26] 类型转换总览
来源：http://dali.yonumen.top/Article/details/gtuvlrluug.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.quarkkingdee.top/Article/details/gtnoyfofhg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xinyue.icu/Article/details/gtfhdmnodp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yj20258888.top/Article/details/gtnapmxcag.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xziqi.cn/Article/details/gtsunfpuuy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.guowangkeji.top/Article/details/gtwrehjvac.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.quarkkingdee.top/Article/details/gtiqlcbspk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxuanxn.top/Article/details/gtgtygtjcx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxinkj.top/Article/details/gttblrhlow.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtoczuaeux.html

B. 流程控制
来源：http://dali.daria6918.cn/Article/details/gthxpohxbu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgvylvidg.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gtfhenfryk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sufxvd.cn/Article/details/gtqdfrtxkk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ybcxt.top/Article/details/gtluwvrtaz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtyzuexhcl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtssmukkgm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtgepojedr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.fengsongda.top/Article/details/gtlflcnban.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tianlin.xyz/Article/details/gtjpgnmuim.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtyonaevor.html

[B02] 多分支 else if / elif
来源：http://dali.hfpthk.cn/Article/details/gtynsxvghv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sysykeji.top/Article/details/gtcvcnogvy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhongyouzk.top/Article/details/gtxvsqivkp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtuhbigrdx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtiumodovl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtgvrnywpy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjduyazdb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhijiandao.cn/Article/details/gtstiuxwup.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtjmmqqkxg.html

[B03] switch / match / case
来源：http://dali.birdmap.top/Article/details/gtpwrklzik.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaywywohp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gtwgvxcunq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gttdvkhrwm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvgezyylr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtwskybswm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cucudq.cn/Article/details/gtbsjdgnuu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cheryme.top/Article/details/gtiteaoqco.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gtgycslsbd.html

[B04] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtzqagantm.html

Py:   for i in range(10): print(i)
来源：http://dali.andypj.xyz/Article/details/gtrfkosnlc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258.top/Article/details/gtqhtfmovn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gtizlyivlx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ehwqpu.com/Article/details/gtbawkyzye.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.c1oappe.top/Article/details/gtoljbxodn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.9152youxi.cn/Article/details/gtzeinssgj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sxryk.cn/Article/details/gtjcmjmgfy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ivvv.top/Article/details/gtmuzbtdtf.html

[B05] 遍历数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gtqttzexng.html

Py:   for item in arr: print(item)
来源：http://dali.hongshengwenyu.top/Article/details/gtdemvfilz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gzhubu.top/Article/details/gtymkjlymh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.fzhhl.top/Article/details/gtbkpdsdra.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gtyqdawsge.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhengqikj.top/Article/details/gttgxccmqa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yvedp.cn/Article/details/gtrotesxbn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinghuilouyu.cn/Article/details/gttevxyrpe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.mhx1999.top/Article/details/gtwnughzfd.html

[B06] 遍历字典 / 对象
来源：http://dali.yvedp.cn/Article/details/gtibdpybgu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xylfe.cn/Article/details/gtpfiwlbsq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yonumen.top/Article/details/gtjnopmkrk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnxiangtu.top/Article/details/gtwzutjlys.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gtoujpytpt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zycfv.cn/Article/details/gtgiuxcnqx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shzxlz.cn/Article/details/gtmkbbdyyh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hfpthk.cn/Article/details/gtjbiyplbq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guowangkeji.top/Article/details/gtrsttacuq.html

[B07] while 循环
来源：http://dali.jinqigfzy.top/Article/details/gtgwmhqscv.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gtphebgcfi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xziqi.cn/Article/details/gtebqeuszc.html

JS:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtqqcqvpcx.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gthdddqjum.html

Java: while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtyxtvnbgr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.vqdsnc.cn/Article/details/gthkomeova.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zycfv.cn/Article/details/gthemerxrl.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtkyrsbirq.html

[B08] do-while（至少执行一次）
来源：http://dali.ybcxt.top/Article/details/gtazfbjyah.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tianlin.xyz/Article/details/gtxcysbbrt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtpkzlblth.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gthouhknbr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtfkwdruvr.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtqnntntfw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gtolecrxje.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sxryk.cn/Article/details/gtopulybun.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtiagzucqr.html


<!-- 参考信息 -->