代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.fengsongda.top/Article/details/gt2zaelmkzp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.havefunace.top/Article/details/gt2vafjrcpv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hfpthk.cn/Article/details/gt2mjfuefgj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ivvv.top/Article/details/gt2amcomofl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cheryme.top/Article/details/gt2jenpbsqi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenzaomai.com/Article/details/gt2rptqnscl.html

Go:   name := "Alex"; age := 20
来源：http://dali.316326.xyz/Article/details/gt2qekttduo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hysaishi.cn/Article/details/gt2zqofxhhk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gluefoeu.html

[A03] 常量定义
来源：http://dali.jinqigufen.top/Article/details/gt2fcrtnwyy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yj20258888.top/Article/details/gt2pdaseacs.html

PHP:  const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gt2xskxwfjr.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2taiufmuw.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2dohtddgw.html

Java: static final double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2ynvtamnc.html

Go:   const PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gt2pftdghtf.html

Ruby: PI = 3.14159
来源：http://dali.ehwqpu.com/Article/details/gt2rfsmfaor.html

C#:   const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qifxcopd.html

[A04] 判断变量类型
来源：http://dali.mhx1999.top/Article/details/gt2dvclimcl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jyoumei.cn/Article/details/gt2fdqaiwla.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxpctkki.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gaohongyu789.top/Article/details/gt2aelcpdgi.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj202588.top/Article/details/gt2vpdlfpat.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangdashe.top/Article/details/gt2ndbkzwrs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daria6918.cn/Article/details/gt2cilrlwlp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.wangshuangyany.cn/Article/details/gt2scoglhwy.html

C#:   x.GetType().Name; x is int
来源：http://dali.nanxinkj.top/Article/details/gt2jkkslncy.html

[A05] 整数除法与取模
来源：http://dali.andypj.xyz/Article/details/gt2abxelrbn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ivvv.top/Article/details/gt2wjnnhfml.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gt2wozqkpna.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2ftmejskb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2uuvnpzdx.html

Java: 7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjggkaiz.html

Go:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gt2krekelyu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2unaraely.html

C#:   7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gt2urdajtdp.html

[A06] 字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntzmovhm.html

Py:   int("42"); float("3.14")
来源：http://dali.andypj.xyz/Article/details/gt2yuygnlpj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.bjfxy.top/Article/details/gt2hqcghexg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zycfv.cn/Article/details/gt2mszdcgku.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.meibo888.top/Article/details/gt2hpznjwpa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.9152youxi.cn/Article/details/gt2rfnmrznc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zoekofqx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ppjwa.cn/Article/details/gt2gyemevcf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tanke756.top/Article/details/gt2kuzjybbu.html

[A07] 数字转字符串
来源：http://dali.fzhhl.top/Article/details/gt2alsfagnp.html

Py:   str(42)
来源：http://dali.yanxiufei.cn/Article/details/gt2kltvztbz.html

PHP:  (string) 42; strval(42)
来源：http://dali.guowangkeji.top/Article/details/gt2fmrjmbae.html

JS:   String(42); (42).toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfbwpwxg.html

TS:   String(42)
来源：http://dali.haohaochexian.top/Article/details/gt2lzuklxmf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj20258.top/Article/details/gt2wdrthbgb.html

Go:   strconv.Itoa(42)
来源：http://dali.haohaochexian.top/Article/details/gt2mwasiooo.html

Ruby: 42.to_s
来源：http://dali.shzxlz.cn/Article/details/gt2ehosmeqf.html

C#:   42.ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uenduhli.html

[A08] 取整与四舍五入
来源：http://dali.zdqjudy.top/Article/details/gt2vsmvcgnj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gt2qqbevugi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.quarkkingdee.top/Article/details/gt2thngqevq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gt2uyhpqqmd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvobtuvv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gt2rxolufyz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdhsmzfc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yueranfly.top/Article/details/gt2xovmsvma.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gt2avyuuyng.html

[A09] 绝对值与最大最小值
来源：http://dali.xinyue.icu/Article/details/gt2egykxagu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2xmmryjin.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2fjwafjxm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2xzkshzzz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2rkeksczu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2tvecvflc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cdnleiting.top/Article/details/gt2xcqjkpqh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhixingplan.top/Article/details/gt2vpdrtljt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2jyqvjeba.html

[A10] 生成随机数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojajlngj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj20258888.top/Article/details/gt2ukjqaine.html

PHP:  random_int(1, 100);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzscwfpu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhoulong.xyz/Article/details/gt2uxspmpor.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xinyue.icu/Article/details/gt2rpbmmuur.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shuidangran.top/Article/details/gt2lhttbxjf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj20258.top/Article/details/gt2shtnobpt.html

Ruby: rand(1..100)
来源：http://dali.tianlin.xyz/Article/details/gt2gyievjpe.html

C#:   new Random().Next(1, 101)
来源：http://dali.shuidangran.top/Article/details/gt2qekpluvz.html

[A11] 条件表达式（三元）
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwleggvb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shuidangran.top/Article/details/gt2nrfxbbln.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gt2ylihpkxk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gt2assquklh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yizoliep.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gt2moudlzya.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.pengpengdd.cyou/Article/details/gt2lasjrrwu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gt2zxnzpitz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gt2vyvqdgdl.html

[A12] 字符串插值 / 格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2koqidsdg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.iojbl.cn/Article/details/gt2lmukzife.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cucudq.cn/Article/details/gt2gbyhbakb.html

JS:   `Hello, ${name}!`
来源：http://dali.kuanghao11.cn/Article/details/gt2srainkok.html

TS:   `Hello, ${name}!`
来源：http://dali.9152youxi.cn/Article/details/gt2atfiqaoi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.nanxuanxn.top/Article/details/gt2zcgcawor.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.c1oappe.top/Article/details/gt2xyminhls.html

Ruby: "Hello, #{name}!"
来源：http://dali.sysykeji.top/Article/details/gt2elurhxxk.html

C#:   $"Hello, {name}!"
来源：http://dali.nanxuanxn.top/Article/details/gt2xqjozldy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jqgfzy.top/Article/details/gt2ummklenm.html

Py:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gt2bubenrqm.html

PHP:  "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gt2vvzguivb.html

JS:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gt2ritnlhag.html

TS:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gt2rcvreusg.html

Java: "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gt2prienmlg.html

Go:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2xchlkmig.html

Ruby: "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gt2svjsrffo.html

C#:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gt2mztqslah.html

[A14] 注释写法
来源：http://dali.havefunace.top/Article/details/gt2ecblcqcf.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xinyue.icu/Article/details/gt2tomjeslc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gt2tyobkrvk.html

JS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztuzsvkr.html

TS:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gt2rkcfinml.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.andypj.xyz/Article/details/gt2bijqvhvb.html

Go:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gt2frhozycu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sufxvd.cn/Article/details/gt2yesaxbuj.html

C#:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gt2lfwdkfcw.html

[A15] 空值判断与默认值
来源：http://dali.yj20258888.top/Article/details/gt2mgmjbxhk.html

Py:   value = data or "默认值"
来源：http://dali.chenlongwang.top/Article/details/gt2qvtwifjz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gt2hfttkyob.html

JS:   const value = data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gt2gosdjzjq.html

TS:   const value = data ?? "默认值";
来源：http://dali.tianlin.xyz/Article/details/gt2uuwznlbr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.mhx1999.top/Article/details/gt2wmwkwxgy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jlsjyb.cn/Article/details/gt2vilvxnog.html

Ruby: value = data || "默认值"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzufvvfj.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gt2ardpqnke.html

[A16] 真假值判断规则
来源：http://dali.ivvv.top/Article/details/gt2jotertea.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gt2igacbwxy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nanxinkj.top/Article/details/gt2huqhivne.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yongpay.top/Article/details/gt2akrlqbcj.html

TS:   if (!x) {}
来源：http://dali.dashuyun.cn/Article/details/gt2uitogcvc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhwhykgq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ppjwa.cn/Article/details/gt2ezjhmjgm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.vqdsnc.cn/Article/details/gt2hxtysbuy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.wangdashe.top/Article/details/gt2othccaxh.html

[A17] 位运算
来源：http://dali.jianghu66.top/Article/details/gt2udknvdli.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2ccukawtj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2uudprwzv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2btywvvjd.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gt2elcxzwqt.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gt2xzxvvjro.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gt2mzzgrnde.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gt2wmgluwcb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2endbqnxb.html

[A18] 字符与 ASCII 码互转
来源：http://dali.haohaochexian.top/Article/details/gt2oooxjeir.html

Py:   ord("A"); chr(65)
来源：http://dali.guowangkeji.top/Article/details/gt2hvspxaoo.html

PHP:  ord("A"); chr(65)
来源：http://dali.gzhubu.top/Article/details/gt2jtzxcwys.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.quarkkingdee.top/Article/details/gt2xpcxejqn.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tian-w.cn/Article/details/gt2dhlsdknh.html

Java: (int) 'A'; (char) 65
来源：http://dali.hysaishi.cn/Article/details/gt2jqyextho.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.quarkkingdee.top/Article/details/gt2hzvcauqd.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vojglkjo.html

C#:   (int)'A'; (char)65
来源：http://dali.wangdashe.top/Article/details/gt2sivquxca.html

[A19] 交换两个变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgvqwsip.html

Py:   a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gt2yafjqotj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yvedp.cn/Article/details/gt2ykgvssmz.html

JS:   [a, b] = [b, a];
来源：http://dali.fengsongda.top/Article/details/gt2bzzalneu.html

TS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gt2cpiuxpoh.html

Java: int t = a; a = b; b = t;
来源：http://dali.yvedp.cn/Article/details/gt2iysupnke.html

Go:   a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gt2phpcggno.html

Ruby: a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gt2rjyunzeq.html

C#:   (a, b) = (b, a);
来源：http://dali.birdmap.top/Article/details/gt2cudfyawy.html

[A20] 读取标准输入
来源：http://dali.andypj.xyz/Article/details/gt2vupvhwoj.html

Py:   name = input("请输入：")
来源：http://dali.redwolf501.top/Article/details/gt2kdedynyq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgufenzy.top/Article/details/gt2ihbgfgyk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hysaishi.cn/Article/details/gt2htvkgxew.html

TS:   // Node.js：readline 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2osipsqvo.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jyoumei.cn/Article/details/gt2dzmpjgix.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.vqdsnc.cn/Article/details/gt2gbdkhixq.html

Ruby: gets.chomp
来源：http://dali.svipenyu.cn/Article/details/gt2yeyixsic.html

C#:   Console.ReadLine();
来源：http://dali.yuanzhike.top/Article/details/gt2fnglhzwk.html

[A21] 保留指定小数位输出
来源：http://dali.yvedp.cn/Article/details/gt2pjquxisd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xinyue.icu/Article/details/gt2nyvkilhk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gt2qpqcdvvs.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gt2ttgplejj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gt2dgsxhjhd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gt2ywlisfbh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gt2fafudfyo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gt2lkcvwfru.html

C#:   3.14159.ToString("F2")
来源：http://dali.nanxuanxn.top/Article/details/gt2jcqmdurr.html

[A22] 获取字符串长度
来源：http://dali.sweek.top/Article/details/gt2bbhbddpu.html

Py:   len(s)
来源：http://dali.havefunace.top/Article/details/gt2ewlkvprs.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yj202588.top/Article/details/gt2imkhvebz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpcqwqpq.html

TS:   s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2isolieie.html

Java: s.length()
来源：http://dali.yj202588.top/Article/details/gt2vlvvftkb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ppjwa.cn/Article/details/gt2kaylorfn.html

Ruby: s.length
来源：http://dali.hammf.cn/Article/details/gt2mbuzibbr.html

C#:   s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2kdupgmsk.html

[A23] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2lpmokbmb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.guowangkeji.top/Article/details/gt2kpupjvyn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgufenzy.top/Article/details/gt2zqupsoju.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gt2qpwmzran.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gt2xyjctxks.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gt2vdjfexeq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ktvnqmpe.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.iojbl.cn/Article/details/gt2caokzxav.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhoulong.xyz/Article/details/gt2ordvdhvr.html

[A24] 去除首尾空白
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shrznpcl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj20258.top/Article/details/gt2gdxlwgos.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.andypj.xyz/Article/details/gt2iqxfsohz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gt2joplffmz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nefukotn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhengqikj.top/Article/details/gt2uammidjg.html

Go:   strings.TrimSpace(s)
来源：http://dali.shzxlz.cn/Article/details/gt2xxvynpeh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj20258888.top/Article/details/gt2abftgjlm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.meibo888.top/Article/details/gt2ziiebqkp.html

[A25] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gt2svpmmtqq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gt2pdsylsqn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.pycfn.com/Article/details/gt2bpvxszcp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.iojbl.cn/Article/details/gt2mtqfmirr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenlongwang.top/Article/details/gt2zjlvobkf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yueranfly.top/Article/details/gt2sbkldvxm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nwbrower.top/Article/details/gt2retxuker.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cucudq.cn/Article/details/gt2tqjuuida.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yangfankeji.com/Article/details/gt2zqlsddbj.html

[A26] 类型转换总览
来源：http://dali.ydzc1.top/Article/details/gt2opqnrpkv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.birdmap.top/Article/details/gt2ksfcienv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhengqikj.top/Article/details/gt2ysgtlkul.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhengqikj.top/Article/details/gt2xgnpyyng.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gogol.net.cn/Article/details/gt2kwgdktjq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.vqdsnc.cn/Article/details/gt2bzmortcd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.bjfxy.top/Article/details/gt2gfrlrhov.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ivvv.top/Article/details/gt2jbwzvtwi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gt2xppncqwg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2pwhqcpug.html

B. 流程控制
来源：http://dali.kuanghao11.cn/Article/details/gt2atynrswn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2zczgfcap.html

[B01] 条件判断 if / else
来源：http://dali.hywenlv.cn/Article/details/gt2ppxnwpni.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenlongwang.top/Article/details/gt2lmjlcxcw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbtgmvvc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gt2trocwagc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbewfjqk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2bubvjtxp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ppjwa.cn/Article/details/gt2qwbtihdv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hysaishi.cn/Article/details/gt2rbzicyid.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gt2dhfdnxfp.html

[B02] 多分支 else if / elif
来源：http://dali.aizwys.cn/Article/details/gt2xfforrdx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tian-w.cn/Article/details/gt2esriibop.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhengqikj.top/Article/details/gt2qkvyahze.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gt2crkprafk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gt2upjauyvs.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gt2pekzupro.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yangfankeji.com/Article/details/gt2wbcuohvf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.meibo888.top/Article/details/gt2efotefyv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbeqgrsk.html

[B03] switch / match / case
来源：http://dali.yueranfly.top/Article/details/gt2qljxpzjn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbesvvgr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gt2eytqdfje.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifomxewf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gt2nrvywlyz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gt2hijrbljr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ivvv.top/Article/details/gt2snpujpfg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenlongwang.top/Article/details/gt2osowxabc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.birdmap.top/Article/details/gt2rorttesh.html

[B04] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gt2lsewwmmy.html

Py:   for i in range(10): print(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2huupvbcq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sweek.top/Article/details/gt2aougexgr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gt2kwhnsxhx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigfzy.top/Article/details/gt2wnncfzos.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nwbrower.top/Article/details/gt2nolyssii.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yongpay.top/Article/details/gt2votdseff.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenlongwang.top/Article/details/gt2kfkfaszo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zycfv.cn/Article/details/gt2liqwrbcz.html

[B05] 遍历数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gt2fmfkziwu.html

Py:   for item in arr: print(item)
来源：http://dali.yj20258.top/Article/details/gt2jlomaabz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gt2okyanncm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shuidangran.top/Article/details/gt2pfjzlkme.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.mhx1999.top/Article/details/gt2povqwnto.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cheryme.top/Article/details/gt2sbwpqcvs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.9152youxi.cn/Article/details/gt2qfazeatd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.daria6918.cn/Article/details/gt2avdedxgc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2fembrsli.html

[B06] 遍历字典 / 对象
来源：http://dali.andypj.xyz/Article/details/gt2zpjrfqcc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenlongwang.top/Article/details/gt2engscgdt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cqqwz.cn/Article/details/gt2qvtsiwee.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyqqknxa.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.birdmap.top/Article/details/gt2xwadspmm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ydzc1.top/Article/details/gt2tozxvmfo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.bjfxy.top/Article/details/gt2imarcexj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigufen.top/Article/details/gt2wnubkchw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xinyue.icu/Article/details/gt2acuiihhj.html

[B07] while 循环
来源：http://dali.jinqigufen.top/Article/details/gt2yqirxpru.html

Py:   while i < 10: i += 1
来源：http://dali.sweek.top/Article/details/gt2wusnahfc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tianlin.xyz/Article/details/gt2wcvdoosh.html

JS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2mckrrecu.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qbelqbwf.html

Java: while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gt2yarxjcih.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gt2isvuhayw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.quarkkingdee.top/Article/details/gt2swjfxfyr.html

C#:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gt2jschokxk.html

[B08] do-while（至少执行一次）
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbnlnyqa.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.c1oappe.top/Article/details/gt2udttxzti.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2laqsjnfn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gt2fgyoktlv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gt2iasobxfs.html

Java: do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2bqqmlavw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gt2cnodtfrh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dashuyun.cn/Article/details/gt2hjzaczrb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2exxbuatv.html


<!-- 参考信息 -->