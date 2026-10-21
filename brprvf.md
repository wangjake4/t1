代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.0kj1m.cn/Article/details/gtftxygpmx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ydzc1.top/Article/details/gtizamvwlq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtytagnmwk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtuxoqocil.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xylfe.cn/Article/details/gtbyqifkcl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gtumhxefjn.html

Go:   name := "Alex"; age := 20
来源：http://dali.jianghu66.top/Article/details/gtdfqmdbaj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shangyingyoupin.top/Article/details/gtwhvowvrn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gtrgycsbmu.html

[A03] 常量定义
来源：http://dali.cheryme.top/Article/details/gtrvclyooy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.andypj.xyz/Article/details/gtbyaasmrz.html

PHP:  const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtupypvyzc.html

JS:   const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtdybnuzju.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllghdvpt.html

Java: static final double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtiqsuijdo.html

Go:   const PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gtissshcbp.html

Ruby: PI = 3.14159
来源：http://dali.zycfv.cn/Article/details/gtqrskvsyh.html

C#:   const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqniulvz.html

[A04] 判断变量类型
来源：http://dali.tian-w.cn/Article/details/gtnfgbffbv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cashguo.top/Article/details/gtnlbnuwzk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gotoacloud.top/Article/details/gtgzfmycec.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gthyeibsny.html

TS:   typeof x; x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gtvybflbtd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ybcxt.top/Article/details/gtcgpbbgkx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuanzx.com/Article/details/gtickvtjwy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenzaomai.com/Article/details/gteujrmtor.html

C#:   x.GetType().Name; x is int
来源：http://dali.smart0.xyz/Article/details/gtkqlkzjqn.html

[A05] 整数除法与取模
来源：http://dali.vqdsnc.cn/Article/details/gtoqogbbon.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.c1oappe.top/Article/details/gtbnkvzueu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gthekayous.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtszwzdssi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlxguejg.html

Java: 7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtttqocrye.html

Go:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtqtinqfjl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtfrmjjwqm.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtdguwfmoa.html

[A06] 字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtipslemiq.html

Py:   int("42"); float("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gtqrmkpyal.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sweek.top/Article/details/gtleylnafd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nwbrower.top/Article/details/gtplwwywwx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gtcbvkwfxj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yuxming.cn/Article/details/gtpyrvjqho.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.kuanghao11.cn/Article/details/gtlbencxct.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yvedp.cn/Article/details/gtsatiytgc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gtfuidquuk.html

[A07] 数字转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtyajtifcf.html

Py:   str(42)
来源：http://dali.meibo888.top/Article/details/gtedoetmhq.html

PHP:  (string) 42; strval(42)
来源：http://dali.meibo888.top/Article/details/gtzzfivawr.html

JS:   String(42); (42).toString()
来源：http://dali.cashguo.top/Article/details/gtfdmwlvcg.html

TS:   String(42)
来源：http://dali.dianchejie.cn/Article/details/gtmrbeatef.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gthrrraucf.html

Go:   strconv.Itoa(42)
来源：http://dali.jlsjyb.cn/Article/details/gtvjbssegx.html

Ruby: 42.to_s
来源：http://dali.chenlongwang.top/Article/details/gtjoabdqsg.html

C#:   42.ToString()
来源：http://dali.ehwqpu.com/Article/details/gtcasxyeqn.html

[A08] 取整与四舍五入
来源：http://dali.fengsongda.top/Article/details/gtncshvcfw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtyqtgfpqm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.birdmap.top/Article/details/gtghsmclvv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtqivsiwyw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xinyue.icu/Article/details/gtwzjcotyu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtgdmbbnhs.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gteelqbcvj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cashguo.top/Article/details/gtglvialhw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtinqrxjkz.html

[A09] 绝对值与最大最小值
来源：http://dali.yueranfly.top/Article/details/gtqbqwyktl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtsgqohyai.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtllsotqnf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtzirrtlvn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtjzgptanm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtieozifrc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.iojbl.cn/Article/details/gtudztznol.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruskrnsd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwklfvlz.html

[A10] 生成随机数
来源：http://dali.zhoulong.xyz/Article/details/gtxqrhxpiu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.pengpengdd.cyou/Article/details/gtschykmod.html

PHP:  random_int(1, 100);
来源：http://dali.wangdashe.top/Article/details/gtfjhliyjh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzxwlchq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jianghu66.top/Article/details/gtoreqyqqy.html

Java: new Random().nextInt(100) + 1
来源：http://dali.chenlongwang.top/Article/details/gtwytvjgcm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ehwqpu.com/Article/details/gtuxbjuzvf.html

Ruby: rand(1..100)
来源：http://dali.jianghu66.top/Article/details/gtiqmqnykm.html

C#:   new Random().Next(1, 101)
来源：http://dali.pengpengdd.cyou/Article/details/gtopsfjtca.html

[A11] 条件表达式（三元）
来源：http://dali.9152youxi.cn/Article/details/gtmasszmhc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ydzc1.top/Article/details/gtgtqczpux.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtvorqklgd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtqamiidoj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtioaxwpds.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtithbbhcw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shzxlz.cn/Article/details/gtuueebuus.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gtullqecfn.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtxefpkujo.html

[A12] 字符串插值 / 格式化
来源：http://dali.meibo888.top/Article/details/gtpzfgtuml.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.c1oappe.top/Article/details/gtexiktiou.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hysaishi.cn/Article/details/gtcdghddzg.html

JS:   `Hello, ${name}!`
来源：http://dali.shzxlz.cn/Article/details/gtuvbtbbly.html

TS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gtkhjxghkg.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jinqigfzy.top/Article/details/gtmahurnbd.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.c1oappe.top/Article/details/gthvnxmoqp.html

Ruby: "Hello, #{name}!"
来源：http://dali.vqdsnc.cn/Article/details/gtouonbbdl.html

C#:   $"Hello, {name}!"
来源：http://dali.sxryk.cn/Article/details/gtphimzepf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.iojbl.cn/Article/details/gtkfeprlqs.html

Py:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtkqvdlhjw.html

PHP:  "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtwildfhav.html

JS:   "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gtpsxmmlug.html

TS:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtdtmcfuek.html

Java: "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtbwuudnxg.html

Go:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtdhqmcjvs.html

Ruby: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtsohjnhza.html

C#:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gthitxovze.html

[A14] 注释写法
来源：http://dali.aibaodan.cn/Article/details/gtymqjrdwm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.chenjidiqi.icu/Article/details/gtnpjyzyqc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gtpscfjaez.html

JS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtxmgijguu.html

TS:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtindcnulh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.chenzaomai.com/Article/details/gttxrtliar.html

Go:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gtqfziakip.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.smart0.xyz/Article/details/gtpbwtsavy.html

C#:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtzywrwyvc.html

[A15] 空值判断与默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqphpchn.html

Py:   value = data or "默认值"
来源：http://dali.yj20258.top/Article/details/gtwqztewqp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtexlkbhhc.html

JS:   const value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gtfaundeti.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gtuitxfwks.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cashguo.top/Article/details/gtjxubmrxa.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.birdmap.top/Article/details/gtzmwrbacy.html

Ruby: value = data || "默认值"
来源：http://dali.ehwqpu.com/Article/details/gtwdltbeye.html

C#:   var value = data ?? "默认值";
来源：http://dali.andypj.xyz/Article/details/gtykulwich.html

[A16] 真假值判断规则
来源：http://dali.jinqigfzy.top/Article/details/gtcgllhfdq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.tianlin.xyz/Article/details/gtkknsxlng.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinqigfzy.top/Article/details/gtxuvgemov.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.9152youxi.cn/Article/details/gtgxtonrje.html

TS:   if (!x) {}
来源：http://dali.jiagoushi.top/Article/details/gtugffcnyh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj20258888.top/Article/details/gtbticjrpi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhixingplan.top/Article/details/gthmixvvfp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sysykeji.top/Article/details/gtlnevvcsy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthwbommvb.html

[A17] 位运算
来源：http://dali.hnqzz.top/Article/details/gtvpzrteln.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlcanqls.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtlylouliq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxzwpgtm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstvulnpt.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtbcfsvnmi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtjlsrjhms.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtmapggilb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtrigbewkf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sxryk.cn/Article/details/gtnfvgrylp.html

Py:   ord("A"); chr(65)
来源：http://dali.yj202588.top/Article/details/gtwodbxvjc.html

PHP:  ord("A"); chr(65)
来源：http://dali.ydzc1.top/Article/details/gtoekildah.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sweek.top/Article/details/gtnqwzxdlx.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fengsongda.top/Article/details/gtacjepqix.html

Java: (int) 'A'; (char) 65
来源：http://dali.tianlin.xyz/Article/details/gtqvttvnps.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.iojbl.cn/Article/details/gtkehrjjxt.html

Ruby: "A".ord; 65.chr
来源：http://dali.ybcxt.top/Article/details/gtyndsxqbu.html

C#:   (int)'A'; (char)65
来源：http://dali.gaohongyu789.top/Article/details/gtkixyhlvu.html

[A19] 交换两个变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcpbqrpb.html

Py:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gtivrzwuyt.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hammf.cn/Article/details/gtkqrjeqmk.html

JS:   [a, b] = [b, a];
来源：http://dali.yj202588.top/Article/details/gtgvwflfin.html

TS:   [a, b] = [b, a];
来源：http://dali.gogol.net.cn/Article/details/gtbvcznkad.html

Java: int t = a; a = b; b = t;
来源：http://dali.cucudq.cn/Article/details/gtasvqpjzk.html

Go:   a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteefeffee.html

Ruby: a, b = b, a
来源：http://dali.gaohongyu789.top/Article/details/gtyuyrtdjg.html

C#:   (a, b) = (b, a);
来源：http://dali.0kj1m.cn/Article/details/gtfqplpbuv.html

[A20] 读取标准输入
来源：http://dali.cucudq.cn/Article/details/gtucaeovgo.html

Py:   name = input("请输入：")
来源：http://dali.tian-w.cn/Article/details/gtgtpagfsz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.chenlongwang.top/Article/details/gtvdzuefiu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrqrcjxg.html

TS:   // Node.js：readline 模块
来源：http://dali.sweek.top/Article/details/gttnkxibsd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cheryme.top/Article/details/gtiffelizt.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhoulong.xyz/Article/details/gtfgesrltl.html

Ruby: gets.chomp
来源：http://dali.xylfe.cn/Article/details/gtukcxoiwe.html

C#:   Console.ReadLine();
来源：http://dali.jyoumei.cn/Article/details/gtkogwutdf.html

[A21] 保留指定小数位输出
来源：http://dali.jyoumei.cn/Article/details/gtpyagobfc.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ivvv.top/Article/details/gtcfdintdf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gtsdyjuncd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtkxwspzms.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtxzeyoavi.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gtmiffzndh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gtufsxelux.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtzywkonup.html

C#:   3.14159.ToString("F2")
来源：http://dali.cashguo.top/Article/details/gthveiisps.html

[A22] 获取字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtkcaganrk.html

Py:   len(s)
来源：http://dali.0kj1m.cn/Article/details/gtxkklilly.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.smart0.xyz/Article/details/gteomdxzqa.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.wangdashe.top/Article/details/gtdkcsqgps.html

TS:   s.length
来源：http://dali.jqgufenzy.top/Article/details/gtawiauefi.html

Java: s.length()
来源：http://dali.guannengcc.top/Article/details/gtgzqxuywv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukyihtab.html

Ruby: s.length
来源：http://dali.yj20258888.top/Article/details/gteleiqxtk.html

C#:   s.Length
来源：http://dali.mhx1999.top/Article/details/gtfweunpvb.html

[A23] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtshgcabcx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.nwbrower.top/Article/details/gtitftdzrb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jianghu66.top/Article/details/gtwsovxcmj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gtcckebesv.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gteoikprww.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gtmavgdxhl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhixingplan.top/Article/details/gtfojxnkfz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.bjfxy.top/Article/details/gteysylkqk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sufxvd.cn/Article/details/gtqkyzjyav.html

[A24] 去除首尾空白
来源：http://dali.hnxiangtu.top/Article/details/gtizqdpjga.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yonumen.top/Article/details/gtcnarlwyx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenlongwang.top/Article/details/gtrqovwvmp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtriuvmeyn.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gttbdmbjvc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuetiantiany.cn/Article/details/gtycwrcjim.html

Go:   strings.TrimSpace(s)
来源：http://dali.tianlin.xyz/Article/details/gtwobqpiya.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.fzhhl.top/Article/details/gtlpbzwuix.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258.top/Article/details/gtdapkanzs.html

[A25] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtcidymfny.html

Py:   s1 == s2; s1 != s2
来源：http://dali.wangshuangyany.cn/Article/details/gtwymrjagj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zdqjudy.top/Article/details/gtbmaplpke.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258888.top/Article/details/gtlrmztziy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.bjfxy.top/Article/details/gtarpmappl.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtoyuwbsdl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj20258888.top/Article/details/gtnmonivar.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj202588.top/Article/details/gtxzqxvhtg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.haohaochexian.top/Article/details/gtfgugmzjz.html

[A26] 类型转换总览
来源：http://dali.hywenlv.cn/Article/details/gtdhnvjflj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.tianlin.xyz/Article/details/gtzwhneulb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pycfn.com/Article/details/gtnamtximj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ivvv.top/Article/details/gtnnbqhvvm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tianlin.xyz/Article/details/gtnxdeotzx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cashguo.top/Article/details/gtjbudqxaz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dashuyun.cn/Article/details/gtbligdopk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtejqqvqxn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtztvjnzgv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkpixageb.html

B. 流程控制
来源：http://dali.hongshengwenyu.top/Article/details/gtmxegiiyr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtupxnojto.html

[B01] 条件判断 if / else
来源：http://dali.wangshuangyany.cn/Article/details/gtpebizrjb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwzityhs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jyoumei.cn/Article/details/gtamcxmpjf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtvrknnzaw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtecfkyzjt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtokncsusm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglwakyso.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigufen.top/Article/details/gtfcbptpbc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtidqiejyg.html

[B02] 多分支 else if / elif
来源：http://dali.jianghu66.top/Article/details/gtyxvbyqef.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gotoacloud.top/Article/details/gtmewfvudj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jianghu66.top/Article/details/gtezrbfvcc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtgebjcftr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gtlwrjxlgn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtiazsaaxu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj202588.top/Article/details/gtzirkuecw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hywenlv.cn/Article/details/gtpfuknxvt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtyifxqdoy.html

[B03] switch / match / case
来源：http://dali.meibo888.top/Article/details/gtwfdlxbtr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhengqikj.top/Article/details/gtechkftbz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtmaebmbsa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtpcdyqsbd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtmegzqipp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsguxsknv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.birdmap.top/Article/details/gtflgmamsh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hammf.cn/Article/details/gtpzxzkjlf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xinyue.icu/Article/details/gttjgnkjtw.html

[B04] for 计数循环
来源：http://dali.yj202588.top/Article/details/gthagrljqd.html

Py:   for i in range(10): print(i)
来源：http://dali.fengsongda.top/Article/details/gtlkibhgqn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aizwys.cn/Article/details/gtvaffpbsq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daxiang520.top/Article/details/gtfeaylbmj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtwmeooqnw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gthllrjezd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwsdmisb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.kuanghao11.cn/Article/details/gtrhdsherk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aibaodan.cn/Article/details/gtxwtrxarg.html

[B05] 遍历数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtlehybhrw.html

Py:   for item in arr: print(item)
来源：http://dali.fzhhl.top/Article/details/gtlvexfhyl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.redwolf501.top/Article/details/gteaierhfk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtahnjewlq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gtncichqmv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yongpay.top/Article/details/gtgslhmcct.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cucudq.cn/Article/details/gtpaslykem.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cucudq.cn/Article/details/gtufbxmajn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhengqikj.top/Article/details/gtixcwunsl.html

[B06] 遍历字典 / 对象
来源：http://dali.feifeiyinyue.top/Article/details/gtbrwqpwmi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.bjfxy.top/Article/details/gthdefqady.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.mhx1999.top/Article/details/gtqdinylhg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gtclfccxtp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gteqpylbdn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.vqdsnc.cn/Article/details/gtmqmfphpm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgufenzy.top/Article/details/gtchhwbmaw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hammf.cn/Article/details/gtdwqmonoq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtsxxsyjwy.html

[B07] while 循环
来源：http://dali.sysykeji.top/Article/details/gtzvtqktuh.html

Py:   while i < 10: i += 1
来源：http://dali.nanxinkj.top/Article/details/gtektrjrme.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtzdtixoix.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtwmmunzjw.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtibbnttqy.html

Java: while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtkpbndnye.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cqqwz.cn/Article/details/gtmufknhao.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ydzc1.top/Article/details/gtogrvjsiv.html

C#:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtomgoypjd.html

[B08] do-while（至少执行一次）
来源：http://dali.tanke756.top/Article/details/gtcahqaqkb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jqgufenzy.top/Article/details/gthwscurtw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtywfxvsvr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtzgcbfhtt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtgikpvenq.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtlyftvvic.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gtjzftlfls.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenlongwang.top/Article/details/gtgytedxqr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtuumhdvrr.html


<!-- 参考信息 -->