代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.zhoulong.xyz/Article/details/gtmksifeob.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jyoumei.cn/Article/details/gtjxknytyn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplxkqzdd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtfvlnaqac.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fengsongda.top/Article/details/gtfvrznhvj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sxryk.cn/Article/details/gtjqrxkprs.html

Go:   name := "Alex"; age := 20
来源：http://dali.jianghu66.top/Article/details/gtxgsmgqvj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdtxvuma.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gtorvslvqn.html

[A03] 常量定义
来源：http://dali.pycfn.com/Article/details/gtqvelpxnv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgufenzy.top/Article/details/gtutpagdzh.html

PHP:  const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtkhaspmey.html

JS:   const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtuawgbewy.html

TS:   const PI: number = 3.14159;
来源：http://dali.tanke756.top/Article/details/gthtqphnpn.html

Java: static final double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtyfyhvaqn.html

Go:   const PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gtspavisji.html

Ruby: PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfbimaex.html

C#:   const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtsumkwrnm.html

[A04] 判断变量类型
来源：http://dali.guannengcc.top/Article/details/gtylfcwnml.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.mhx1999.top/Article/details/gtmusbhrkj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuanzx.com/Article/details/gtqzdzcped.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gtpefqwdyf.html

TS:   typeof x; x instanceof Date
来源：http://dali.sxryk.cn/Article/details/gtfjjhsbvo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hfpthk.cn/Article/details/gtreyydhng.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.meibo888.top/Article/details/gtjxbbehqy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenzaomai.com/Article/details/gtouuooefk.html

C#:   x.GetType().Name; x is int
来源：http://dali.hysaishi.cn/Article/details/gtdymjjrkx.html

[A05] 整数除法与取模
来源：http://dali.daria6918.cn/Article/details/gtytoifhec.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pengpengdd.cyou/Article/details/gtaipwmity.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtfbmxinok.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtreshkvjk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtcjjdojds.html

Java: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtmwcwoevc.html

Go:   7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gtmrxmrfix.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtqkudsekn.html

C#:   7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gtnovtrcxi.html

[A06] 字符串转数字
来源：http://dali.yonumen.top/Article/details/gtmnzfcdat.html

Py:   int("42"); float("3.14")
来源：http://dali.cheryme.top/Article/details/gtsirlgdgo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yangfankeji.com/Article/details/gtrenkisyp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gtvysvfqvm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.feifeiyinyue.top/Article/details/gtvixsvsai.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gtkylwvbjl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cucudq.cn/Article/details/gtykyxczdr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daria6918.cn/Article/details/gtlkbmezlo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gtuywhvotu.html

[A07] 数字转字符串
来源：http://dali.meibo888.top/Article/details/gtwupgvuka.html

Py:   str(42)
来源：http://dali.cashguo.top/Article/details/gthgxyuuat.html

PHP:  (string) 42; strval(42)
来源：http://dali.yonumen.top/Article/details/gtcxqyiojx.html

JS:   String(42); (42).toString()
来源：http://dali.guannengcc.top/Article/details/gtgajlyytd.html

TS:   String(42)
来源：http://dali.jqgufenzy.top/Article/details/gtcdmmghzq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gtsddzxhpo.html

Go:   strconv.Itoa(42)
来源：http://dali.yj20258888.top/Article/details/gtsxpvtsey.html

Ruby: 42.to_s
来源：http://dali.pycfn.com/Article/details/gtaecblsvg.html

C#:   42.ToString()
来源：http://dali.shuidangran.top/Article/details/gtqvxsgauj.html

[A08] 取整与四舍五入
来源：http://dali.shzxlz.cn/Article/details/gtwjffcpyu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtuyeffkhl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jqgfzy.top/Article/details/gtkkclrhst.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtafyxlyat.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hnqzz.top/Article/details/gteqzbchpu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtdsjqtnrs.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gttpbftgxj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shangyingyoupin.top/Article/details/gtyqrwigxg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwlsytcf.html

[A09] 绝对值与最大最小值
来源：http://dali.fengsongda.top/Article/details/gtllxstzsw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtvxskhnxd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtankqyfdt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtkxceavsc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtdihycktb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtkuxqdsdm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhiwuduotai.top/Article/details/gtufqqdazk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnxiangtu.top/Article/details/gtcofpwggh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtzjsfwdee.html

[A10] 生成随机数
来源：http://dali.yonumen.top/Article/details/gtofutfqsp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yuxming.cn/Article/details/gtgfelwtfx.html

PHP:  random_int(1, 100);
来源：http://dali.ehwqpu.com/Article/details/gtjaqpxqie.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigfzy.top/Article/details/gtuwsvafhd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yongpay.top/Article/details/gtairqalsh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sweek.top/Article/details/gtrdhqprmy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj202588.top/Article/details/gtgqesmdvg.html

Ruby: rand(1..100)
来源：http://dali.jinqigfzy.top/Article/details/gtulqqsoqy.html

C#:   new Random().Next(1, 101)
来源：http://dali.ivvv.top/Article/details/gtrrugtymw.html

[A11] 条件表达式（三元）
来源：http://dali.yvedp.cn/Article/details/gtgihcppgh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cqqwz.cn/Article/details/gttmchtqrr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtmogkkbqr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gtumtqwrgb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtxyurdmie.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtkdvlryrb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.aizwys.cn/Article/details/gttqjjuahu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gtepsrzuwa.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gttwrlaitl.html

[A12] 字符串插值 / 格式化
来源：http://dali.yangfankeji.com/Article/details/gtysdcpdbc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hysaishi.cn/Article/details/gtthdelwhd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hfpthk.cn/Article/details/gtasjyhsot.html

JS:   `Hello, ${name}!`
来源：http://dali.hysaishi.cn/Article/details/gtwtiewcyu.html

TS:   `Hello, ${name}!`
来源：http://dali.zhoulong.xyz/Article/details/gtffwzmwag.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sweek.top/Article/details/gtsqqxlmig.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.dianchejie.cn/Article/details/gtelhcdjhb.html

Ruby: "Hello, #{name}!"
来源：http://dali.yuxming.cn/Article/details/gtkohzchbt.html

C#:   $"Hello, {name}!"
来源：http://dali.yueranfly.top/Article/details/gtclphoqir.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gtdbqjtmrx.html

Py:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtosssbgys.html

PHP:  "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtynqxaoxq.html

JS:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtrryxguyh.html

TS:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtibqriklg.html

Java: "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtyjsupuiz.html

Go:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtipshojjm.html

Ruby: "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtvcbaoucr.html

C#:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtvjukwumq.html

[A14] 注释写法
来源：http://dali.hywenlv.cn/Article/details/gtnonrvraj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sxryk.cn/Article/details/gtipfxwnjh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtunrowdck.html

JS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtwlhoelfa.html

TS:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gtuxjemobm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.quarkkingdee.top/Article/details/gtcfbippqx.html

Go:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtykgbgulg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jqgufenzy.top/Article/details/gtqsrgdurz.html

C#:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gtjdoipuzj.html

[A15] 空值判断与默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcadgpwek.html

Py:   value = data or "默认值"
来源：http://dali.quarkkingdee.top/Article/details/gtpjcnjqqr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gtwqlrlhhl.html

JS:   const value = data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gtjcasyrcw.html

TS:   const value = data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gtlpvinags.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.sufxvd.cn/Article/details/gtpowwugwi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shzxlz.cn/Article/details/gttiajcuop.html

Ruby: value = data || "默认值"
来源：http://dali.zhongyouzk.top/Article/details/gtdhjfnmrd.html

C#:   var value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtvgzzzfxh.html

[A16] 真假值判断规则
来源：http://dali.yanxiufei.cn/Article/details/gtiploxkie.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.9152youxi.cn/Article/details/gtlfmcklqn.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xinyue.icu/Article/details/gtwiuntdrf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yvedp.cn/Article/details/gtzjwtttwh.html

TS:   if (!x) {}
来源：http://dali.redwolf501.top/Article/details/gtaqjcjinq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ybcxt.top/Article/details/gtofhnzbpc.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yueranfly.top/Article/details/gteqrnxjxm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhiwuduotai.top/Article/details/gttzcwhoaj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hywenlv.cn/Article/details/gtqrlqrfwe.html

[A17] 位运算
来源：http://dali.zhiwuduotai.top/Article/details/gtusozsgyp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtwwnsxsxw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gtphrnorpx.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtwqcjnaoh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtszmikoil.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gteqbdstam.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtdthhawqm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gthkpsogsy.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdevpktgc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nanxinkj.top/Article/details/gtwixbdnif.html

Py:   ord("A"); chr(65)
来源：http://dali.sweek.top/Article/details/gtqhrcbnqg.html

PHP:  ord("A"); chr(65)
来源：http://dali.xuanzx.com/Article/details/gtyrfcqrhr.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yongpay.top/Article/details/gteoueehlf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tanke756.top/Article/details/gtqrtomaez.html

Java: (int) 'A'; (char) 65
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjgttkft.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxinkj.top/Article/details/gtwcbxcccb.html

Ruby: "A".ord; 65.chr
来源：http://dali.haohaochexian.top/Article/details/gtrqjromun.html

C#:   (int)'A'; (char)65
来源：http://dali.ivvv.top/Article/details/gtdtngeabe.html

[A19] 交换两个变量
来源：http://dali.cdnleiting.top/Article/details/gttpcxpgsi.html

Py:   a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gtxqeljqjl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jiagoushi.top/Article/details/gtqjjylgig.html

JS:   [a, b] = [b, a];
来源：http://dali.jiagoushi.top/Article/details/gtydcaifga.html

TS:   [a, b] = [b, a];
来源：http://dali.cheryme.top/Article/details/gtrnbgwzhs.html

Java: int t = a; a = b; b = t;
来源：http://dali.0kj1m.cn/Article/details/gtcmgauzhb.html

Go:   a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gtddwooqpm.html

Ruby: a, b = b, a
来源：http://dali.quarkkingdee.top/Article/details/gthdlnnkou.html

C#:   (a, b) = (b, a);
来源：http://dali.zhoulong.xyz/Article/details/gtebsahbir.html

[A20] 读取标准输入
来源：http://dali.yuanzhike.top/Article/details/gtsdacjkft.html

Py:   name = input("请输入：")
来源：http://dali.gogol.net.cn/Article/details/gtehlgqswp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhongyouzk.top/Article/details/gtxsquozyh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shangyingyoupin.top/Article/details/gtbfdavclg.html

TS:   // Node.js：readline 模块
来源：http://dali.sweek.top/Article/details/gttxwibtnr.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xziqi.cn/Article/details/gtvnxzbxuy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhongyouzk.top/Article/details/gtjkcajcuw.html

Ruby: gets.chomp
来源：http://dali.zhixingplan.top/Article/details/gtomfqxcoi.html

C#:   Console.ReadLine();
来源：http://dali.316326.xyz/Article/details/gtqfgyntgn.html

[A21] 保留指定小数位输出
来源：http://dali.nanxinkj.top/Article/details/gtrhaaudfc.html

Py:   f"{3.14159:.2f}"
来源：http://dali.wangshuangyany.cn/Article/details/gtpjyxhsfi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gtguvdyglt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtbfwgmmfb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gtgqnbdbie.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtxwceyeiq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtyzalhgod.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gtqsmcsgrk.html

C#:   3.14159.ToString("F2")
来源：http://dali.nwbrower.top/Article/details/gtzcuxjzmn.html

[A22] 获取字符串长度
来源：http://dali.nwbrower.top/Article/details/gtauqcottx.html

Py:   len(s)
来源：http://dali.yj20258888.top/Article/details/gtogomucik.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zdqjudy.top/Article/details/gttseuvzet.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgwxdvyx.html

TS:   s.length
来源：http://dali.ehwqpu.com/Article/details/gtleqfwetz.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gthmwstdsn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtzuwvcfag.html

Ruby: s.length
来源：http://dali.xuanzx.com/Article/details/gtgvlumdub.html

C#:   s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtbskblxml.html

[A23] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtcgsbfwyg.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtayuqkqbg.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.havefunace.top/Article/details/gtcacguley.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gtswlftfwb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gthugobstw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gtbjhwroxg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.tian-w.cn/Article/details/gtxzcuchxe.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtxckppwup.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenjidiqi.icu/Article/details/gthbkmpdij.html

[A24] 去除首尾空白
来源：http://dali.andypj.xyz/Article/details/gtxchxqslw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.tanke756.top/Article/details/gtvtteujhs.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yj20258888.top/Article/details/gtglgfhdpj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jianghu66.top/Article/details/gtcnzyeumi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfsvjiux.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.0kj1m.cn/Article/details/gthrlaxbbo.html

Go:   strings.TrimSpace(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtztuuylnv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.pycfn.com/Article/details/gturlnjqqf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xziqi.cn/Article/details/gtdtlhiltb.html

[A25] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtvizmabfa.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gaohongyu789.top/Article/details/gtyqzqxlqp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ybcxt.top/Article/details/gtkastiehf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gtuauuhqtj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daria6918.cn/Article/details/gtnrfgyfrs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xylfe.cn/Article/details/gtsnbmgrzg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gtrtqleplo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhijiandao.cn/Article/details/gtqnnjutti.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gtzlrojqae.html

[A26] 类型转换总览
来源：http://dali.zhoulong.xyz/Article/details/gtxevolfai.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hywenlv.cn/Article/details/gtbvnrmxwt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.meibo888.top/Article/details/gtblckoobl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuanzx.com/Article/details/gtgzpfgavg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jiagoushi.top/Article/details/gtbcxxsdkq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.guannengcc.top/Article/details/gtsvojcfsd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xziqi.cn/Article/details/gtzcfbnzzh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenjidiqi.icu/Article/details/gterossmmc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gtxjmprljm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttbzhklmx.html

B. 流程控制
来源：http://dali.mhx1999.top/Article/details/gtmnpncnkr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjplpuqri.html

[B01] 条件判断 if / else
来源：http://dali.pengpengdd.cyou/Article/details/gteqhankcd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnxiangtu.top/Article/details/gtbrhfokvf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sufxvd.cn/Article/details/gtbmkyqvxg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtolijakdi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtjdhjqnfd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gtwsbdgbcu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cqqwz.cn/Article/details/gtsrhscomf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daria6918.cn/Article/details/gtnixwqryz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gtcyorittt.html

[B02] 多分支 else if / elif
来源：http://dali.quarkkingdee.top/Article/details/gtfpojayyp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yonumen.top/Article/details/gtveaoyrtl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jianghu66.top/Article/details/gtyvoierag.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtxwyvzbwl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtvcditgrp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtwwsvaexg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.chenlongwang.top/Article/details/gtqaosedug.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinghuilouyu.cn/Article/details/gtiijnrdtq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtkvbtaywx.html

[B03] switch / match / case
来源：http://dali.sysykeji.top/Article/details/gtnyfdbsjn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gtoxdasyju.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtooimbgqq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gthpsaavuw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtgtusoqfr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gtnhssgmcd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.havefunace.top/Article/details/gtezwslhub.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ydzc1.top/Article/details/gttqmqbwlk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sweek.top/Article/details/gtrovrboyp.html

[B04] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gtprtircuz.html

Py:   for i in range(10): print(i)
来源：http://dali.jlsjyb.cn/Article/details/gtapsujwaz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guannengcc.top/Article/details/gtryysxmkg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gotoacloud.top/Article/details/gttrvvjgru.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cqqwz.cn/Article/details/gtbrykxrcx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqhzjubl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258.top/Article/details/gtqgmmvtbo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.316326.xyz/Article/details/gtcidggkam.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.0kj1m.cn/Article/details/gtlsbaomvl.html

[B05] 遍历数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtcsvxcxwk.html

Py:   for item in arr: print(item)
来源：http://dali.tianlin.xyz/Article/details/gtjdnnrqsr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sxryk.cn/Article/details/gtkimcgnna.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqoayjrbx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hfpthk.cn/Article/details/gtlxydexxx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.haohaochexian.top/Article/details/gtrpxnonut.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.iojbl.cn/Article/details/gtyduedngv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yueranfly.top/Article/details/gtvutifesf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfnjlasfn.html

[B06] 遍历字典 / 对象
来源：http://dali.c1oappe.top/Article/details/gtnpolmmty.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gtooqsjwfb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigfzy.top/Article/details/gtsaiszliv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gtizktomrk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gtvclpqjvu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gtyygnnwyr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daxiang520.top/Article/details/gtsjtkaqhl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.quarkkingdee.top/Article/details/gtmyvhjilm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.svipenyu.cn/Article/details/gtgbmczpoe.html

[B07] while 循环
来源：http://dali.zhongyouzk.top/Article/details/gtdnkirbve.html

Py:   while i < 10: i += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtiizdtlnx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtczdlgvcd.html

JS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtllxqgsfx.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtgscwmzkf.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtkpcqzteg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ppjwa.cn/Article/details/gtsonragrf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cqqwz.cn/Article/details/gtddcotape.html

C#:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtrqzsljvk.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gtolcitrxu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.guannengcc.top/Article/details/gttmtoeivu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gttolkizwd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gthvueqsin.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtzfxqrwqy.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtkfidwbgq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pycfn.com/Article/details/gtakhhqzme.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuxming.cn/Article/details/gtagpbadqu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtxvosfilb.html


<!-- 参考信息 -->