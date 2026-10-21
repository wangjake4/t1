代发 wailian999

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daria6918.cn/Article/details/gtxcgkxmlp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pycfn.com/Article/details/gttrrqbgif.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gthfokrvow.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtrpmpeaeb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtemdwlbas.html

A. 基础语法与类型
来源：http://dali.pycfn.com/Article/details/gtgvpjynff.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqkmlbfp.html

[A01] Hello World
来源：http://dali.haohaochexian.top/Article/details/gtfjlpkzln.html

Py:   print("Hello, World!")
来源：http://dali.ydzc1.top/Article/details/gtsyyvzibh.html

PHP:  echo "Hello, World!";
来源：http://dali.wangdashe.top/Article/details/gthhmkdiuo.html

JS:   console.log("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gthzdghkaa.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nwbrower.top/Article/details/gtmlagscaw.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gtcssxlkyo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hammf.cn/Article/details/gtxylirffz.html

Ruby: puts "Hello, World!"
来源：http://dali.hysaishi.cn/Article/details/gtrdhopjor.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gtemidlplq.html

[A02] 变量声明与赋值
来源：http://dali.zhengqikj.top/Article/details/gtmxxswdrm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.redwolf501.top/Article/details/gtuotgdrwp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.andypj.xyz/Article/details/gtotnweozt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuanzhike.top/Article/details/gtmlrslkqm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gthzhhywqw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gtupwaompn.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxuanxn.top/Article/details/gtetjwhcox.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jlsjyb.cn/Article/details/gttcezkqkc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtfprgouzm.html

[A03] 常量定义
来源：http://dali.chenzaomai.com/Article/details/gtncdpaetk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgfzy.top/Article/details/gthwllbpxg.html

PHP:  const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtxyskvatm.html

JS:   const PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtvuznoekt.html

TS:   const PI: number = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtlcpqekma.html

Java: static final double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtkdhwuius.html

Go:   const PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gtvywcitek.html

Ruby: PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gtbmuszkof.html

C#:   const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtyvsjywko.html

[A04] 判断变量类型
来源：http://dali.guowangkeji.top/Article/details/gtjkhelbnn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenlongwang.top/Article/details/gtxpybpztm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cashguo.top/Article/details/gtskdljsby.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtnboqshtt.html

TS:   typeof x; x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gtnmdgkkfi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shzxlz.cn/Article/details/gtrhjbmugc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gaohongyu789.top/Article/details/gttpozninq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.birdmap.top/Article/details/gtqgmphkob.html

C#:   x.GetType().Name; x is int
来源：http://dali.ybcxt.top/Article/details/gtyqzpunur.html

[A05] 整数除法与取模
来源：http://dali.yonumen.top/Article/details/gtgecaiuyy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgfzy.top/Article/details/gtcitloetd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtiodxckok.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzekcxtq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtpjxviway.html

Java: 7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtnwejosxg.html

Go:   7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gttsrtcafo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtkmvhhkck.html

C#:   7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtnslczjtf.html

[A06] 字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtqavawkyu.html

Py:   int("42"); float("3.14")
来源：http://dali.sweek.top/Article/details/gtalgzpafx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.316326.xyz/Article/details/gtfcwtzbmr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.guowangkeji.top/Article/details/gtfgcewhoe.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.wangdashe.top/Article/details/gtyknrkiwb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.guannengcc.top/Article/details/gttsnkcfjs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sufxvd.cn/Article/details/gtonzdrbvj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daria6918.cn/Article/details/gtfdydhlrq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgjxurul.html

[A07] 数字转字符串
来源：http://dali.cheryme.top/Article/details/gtnbhqekat.html

Py:   str(42)
来源：http://dali.mhx1999.top/Article/details/gtmwicrnhz.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjdihpeh.html

JS:   String(42); (42).toString()
来源：http://dali.zhongyouzk.top/Article/details/gtpkgxeoih.html

TS:   String(42)
来源：http://dali.aibaodan.cn/Article/details/gtnyulnyhg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhiwuduotai.top/Article/details/gttvgdcebj.html

Go:   strconv.Itoa(42)
来源：http://dali.chenzaomai.com/Article/details/gtjjhryfln.html

Ruby: 42.to_s
来源：http://dali.yj20258.top/Article/details/gtdefsmshx.html

C#:   42.ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtuyfxmekg.html

[A08] 取整与四舍五入
来源：http://dali.meibo888.top/Article/details/gtndcypbdn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gtkgkocdpr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shzxlz.cn/Article/details/gtpolgicly.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtcloilsvc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.andypj.xyz/Article/details/gttiayxitl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtruebraip.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gtyhmhpomp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.aibaodan.cn/Article/details/gtbtqzkirn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.birdmap.top/Article/details/gthynjcdak.html

[A09] 绝对值与最大最小值
来源：http://dali.hywenlv.cn/Article/details/gtpenemuwr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hammf.cn/Article/details/gtkeaowbgg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtiidhbeib.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtrikudtnm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.c1oappe.top/Article/details/gthfjjklpt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtckqcztuz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jiagoushi.top/Article/details/gtjshtlifn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnxiangtu.top/Article/details/gtqsskqddm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtcnubwcgg.html

[A10] 生成随机数
来源：http://dali.9152youxi.cn/Article/details/gtukzzeyed.html

Py:   import random; random.randint(1, 100)
来源：http://dali.daria6918.cn/Article/details/gttroqnzof.html

PHP:  random_int(1, 100);
来源：http://dali.mhx1999.top/Article/details/gtsfnkcqea.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gtxgacnghi.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.haohaochexian.top/Article/details/gtqchsuiov.html

Java: new Random().nextInt(100) + 1
来源：http://dali.andypj.xyz/Article/details/gtpumvcsue.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ydzc1.top/Article/details/gtfmgkemnk.html

Ruby: rand(1..100)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvojeluje.html

C#:   new Random().Next(1, 101)
来源：http://dali.yonumen.top/Article/details/gtyedjviru.html

[A11] 条件表达式（三元）
来源：http://dali.iojbl.cn/Article/details/gtmgecignr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.aibaodan.cn/Article/details/gtkyoqbyxv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gtzmqmmiva.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtawbgjjkw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtafdghpmv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtkgofumea.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ppjwa.cn/Article/details/gtpizqesmh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtiwahivlc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtqknqllfa.html

[A12] 字符串插值 / 格式化
来源：http://dali.ivvv.top/Article/details/gtfcnshhnp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhtlchpw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhiwuduotai.top/Article/details/gtlzjivprs.html

JS:   `Hello, ${name}!`
来源：http://dali.shangyingyoupin.top/Article/details/gtezkswxdr.html

TS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgixaprgv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.aibaodan.cn/Article/details/gtwzzbtkcw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cheryme.top/Article/details/gtgeekdbgw.html

Ruby: "Hello, #{name}!"
来源：http://dali.feifeiyinyue.top/Article/details/gtmtmpvvhy.html

C#:   $"Hello, {name}!"
来源：http://dali.jqgufenzy.top/Article/details/gtxljuwbct.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.snrcjt.cn/Article/details/gtwcqlmber.html

Py:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtyaagxfpv.html

PHP:  "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gteiuvappr.html

JS:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtkafowxef.html

TS:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtvnvnwqng.html

Java: "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtehqbpmaq.html

Go:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gttcfizubo.html

Ruby: "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbygvvrn.html

C#:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtakrsouir.html

[A14] 注释写法
来源：http://dali.nanxinkj.top/Article/details/gtksezprbg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yangfankeji.com/Article/details/gtlkoilvox.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gtpagqwqyf.html

JS:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtnuywzhfy.html

TS:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gtqpadjztf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.daria6918.cn/Article/details/gtzglmvqtn.html

Go:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gtfytupknr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yonumen.top/Article/details/gtiwgkkonj.html

C#:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gtqnvdvdtu.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gtflqruzrx.html

Py:   value = data or "默认值"
来源：http://dali.pycfn.com/Article/details/gtmvijcqno.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtohhdkdnw.html

JS:   const value = data ?? "默认值";
来源：http://dali.quarkkingdee.top/Article/details/gttpietjdg.html

TS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gtffmvurjv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yongpay.top/Article/details/gtsdodnqgt.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hysaishi.cn/Article/details/gtmtkojivl.html

Ruby: value = data || "默认值"
来源：http://dali.cucudq.cn/Article/details/gtowkbmaxm.html

C#:   var value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gtfbvhjmfu.html

[A16] 真假值判断规则
来源：http://dali.andypj.xyz/Article/details/gtjrqucmbv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.smart0.xyz/Article/details/gtxfjugkxt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhiwuduotai.top/Article/details/gtarcedmxu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.dianchejie.cn/Article/details/gtbukjarkg.html

TS:   if (!x) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsmdlfwuj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.gzhubu.top/Article/details/gtffsutuqn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ybcxt.top/Article/details/gtmdbthkkr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.chenlongwang.top/Article/details/gtkbzggplb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtfnmwtjnp.html

[A17] 位运算
来源：http://dali.hongshengwenyu.top/Article/details/gtffjxvinb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gtvkxcurnj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.iojbl.cn/Article/details/gtfemjxsrz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtyzqbmfit.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtclapwzcr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtxeffxumu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtdqztlrpw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gttwldllur.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtmygpesmv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.guowangkeji.top/Article/details/gtqhunfnak.html

Py:   ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gthgoggafa.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gtmmsjsdgu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gogol.net.cn/Article/details/gtwzgtwwnt.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigfzy.top/Article/details/gtzcuxruba.html

Java: (int) 'A'; (char) 65
来源：http://dali.yonumen.top/Article/details/gtopmbgttm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cucudq.cn/Article/details/gtwxcztagh.html

Ruby: "A".ord; 65.chr
来源：http://dali.jqgfzy.top/Article/details/gtyxbdvugr.html

C#:   (int)'A'; (char)65
来源：http://dali.feifeiyinyue.top/Article/details/gtmdpyrdjj.html

[A19] 交换两个变量
来源：http://dali.zhijiandao.cn/Article/details/gtyyntgyfa.html

Py:   a, b = b, a
来源：http://dali.aibaodan.cn/Article/details/gtixrcsmpy.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.wangdashe.top/Article/details/gtegzlrqfa.html

JS:   [a, b] = [b, a];
来源：http://dali.ehwqpu.com/Article/details/gtmumjitko.html

TS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsktczrrw.html

Java: int t = a; a = b; b = t;
来源：http://dali.xuanzx.com/Article/details/gtsqpmvgcu.html

Go:   a, b = b, a
来源：http://dali.zhengqikj.top/Article/details/gttpfcudyh.html

Ruby: a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gtmdjqqliy.html

C#:   (a, b) = (b, a);
来源：http://dali.xuetiantiany.cn/Article/details/gtdnbqdjcl.html

[A20] 读取标准输入
来源：http://dali.sweek.top/Article/details/gtjuqhgbqn.html

Py:   name = input("请输入：")
来源：http://dali.jqgufenzy.top/Article/details/gtiswnjidt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbavxlnu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pycfn.com/Article/details/gtnuyzuttc.html

TS:   // Node.js：readline 模块
来源：http://dali.hnxiangtu.top/Article/details/gtubebkqsb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jqgufenzy.top/Article/details/gtzdovbyek.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zycfv.cn/Article/details/gtwsvwbtvt.html

Ruby: gets.chomp
来源：http://dali.316326.xyz/Article/details/gtpudixvin.html

C#:   Console.ReadLine();
来源：http://dali.redwolf501.top/Article/details/gtsoimzqjx.html

[A21] 保留指定小数位输出
来源：http://dali.iojbl.cn/Article/details/gtmthhjflx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.aibaodan.cn/Article/details/gtaxjnglbs.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gtwsubgmwv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gtsmcrlbor.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtyyiwrspk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gtlzguctzd.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtyyhedrzc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtpkckfuin.html

C#:   3.14159.ToString("F2")
来源：http://dali.gotoacloud.top/Article/details/gtipkcngzq.html

[A22] 获取字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtycfwbdnd.html

Py:   len(s)
来源：http://dali.gogol.net.cn/Article/details/gtnyfsjfal.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yj20258888.top/Article/details/gtixxcggnd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.mhx1999.top/Article/details/gtjxrxgdqa.html

TS:   s.length
来源：http://dali.cdnleiting.top/Article/details/gtkmwxznog.html

Java: s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtlcbijyci.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hywenlv.cn/Article/details/gtrpajiahu.html

Ruby: s.length
来源：http://dali.jyoumei.cn/Article/details/gtdgjgmcxg.html

C#:   s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbuyodjca.html

[A23] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtdkpkncht.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jiagoushi.top/Article/details/gtbwefyhwt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.daxiang520.top/Article/details/gtvzsnrhbt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtruefkjty.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gtujakuftd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gtxlacjjuj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daria6918.cn/Article/details/gtuamvfttb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtsenfbuus.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.andypj.xyz/Article/details/gtjbqnimgg.html

[A24] 去除首尾空白
来源：http://dali.havefunace.top/Article/details/gtskmjosgw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.nanxinkj.top/Article/details/gtsbzzqnbj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.tanke756.top/Article/details/gtykvbirtq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gtegbhkurp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gtgpgpfibf.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sweek.top/Article/details/gtzdqknbcr.html

Go:   strings.TrimSpace(s)
来源：http://dali.sufxvd.cn/Article/details/gtlfchrriq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj20258.top/Article/details/gtohsuzrbt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.birdmap.top/Article/details/gtctwlslyp.html

[A25] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtauspstey.html

Py:   s1 == s2; s1 != s2
来源：http://dali.haohaochexian.top/Article/details/gtcdqdgprn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guannengcc.top/Article/details/gtpjmbaouh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtujvmtsvp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gtaibjgqco.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hysaishi.cn/Article/details/gtdjpacmrn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj20258888.top/Article/details/gtucpcuzji.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenzaomai.com/Article/details/gtipgsnwgf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxdxpjrp.html

[A26] 类型转换总览
来源：http://dali.andypj.xyz/Article/details/gtftapddxs.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxcbayag.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zdqjudy.top/Article/details/gtebglbzia.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcwsviug.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guowangkeji.top/Article/details/gtnhaedhez.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gtzbhejgfk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ydzc1.top/Article/details/gtinfuhexq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.c1oappe.top/Article/details/gtsgfoxchv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhiwuduotai.top/Article/details/gtjyoxomlz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgnwjylzq.html

B. 流程控制
来源：http://dali.ydzc1.top/Article/details/gtcaqrlvvr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpiplweqs.html

[B01] 条件判断 if / else
来源：http://dali.vqdsnc.cn/Article/details/gtofateusu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yvedp.cn/Article/details/gtobjbbxax.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gzhubu.top/Article/details/gtiuekmqxp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtwwhttdym.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtdrmvtmdr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtzefwbvuo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yvedp.cn/Article/details/gtygljtqxy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.snrcjt.cn/Article/details/gtfdkgbavt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtuxuisope.html

[B02] 多分支 else if / elif
来源：http://dali.yj202588.top/Article/details/gtsshuugvq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gogol.net.cn/Article/details/gttwdmtmkj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnyjttumn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtwagghdfq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtkpkhieyv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtqquqfnkw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jlsjyb.cn/Article/details/gttwpjzxqd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugbqvmga.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtecbmeaty.html

[B03] switch / match / case
来源：http://dali.chenlongwang.top/Article/details/gtbrlbjzvi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yangfankeji.com/Article/details/gtsaypvscj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtldidjzgs.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtbpjohhrb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtdzbfcpie.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtedcnqeyh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gtwnhfwruf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fengsongda.top/Article/details/gtgmbufscl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gogol.net.cn/Article/details/gtelavpfvl.html

[B04] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtbowazoli.html

Py:   for i in range(10): print(i)
来源：http://dali.dianchejie.cn/Article/details/gtdtbikqlm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmasdpdhe.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gtiicrygjh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gtabxpyeio.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fengsongda.top/Article/details/gtvlkzbzxw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.meibo888.top/Article/details/gtnzzgdcqa.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jqgufenzy.top/Article/details/gtfoojmpej.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtuezivzje.html

[B05] 遍历数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtidnzitdy.html

Py:   for item in arr: print(item)
来源：http://dali.pengpengdd.cyou/Article/details/gthwuddnpc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jiagoushi.top/Article/details/gtquqfuama.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gtxwqkuyqh.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtrnronkpf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yongpay.top/Article/details/gtqosdkadz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dianchejie.cn/Article/details/gtcgdwhcvg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yonumen.top/Article/details/gtmkuixmqw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fzhhl.top/Article/details/gtbhbymokr.html

[B06] 遍历字典 / 对象
来源：http://dali.hnxiangtu.top/Article/details/gtisdzwvqi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gtfvjsqpvx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dashuyun.cn/Article/details/gtuncdexcy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gtmqeqnakn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtntjoaj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sysykeji.top/Article/details/gtklqvdjuz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ivvv.top/Article/details/gtkgbdrris.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.redwolf501.top/Article/details/gtwvwvdtel.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtwuvccdbo.html

[B07] while 循环
来源：http://dali.xylfe.cn/Article/details/gtowyqilqx.html

Py:   while i < 10: i += 1
来源：http://dali.xziqi.cn/Article/details/gtizbaqfip.html


<!-- 参考信息 -->