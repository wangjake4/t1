代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.cucudq.cn/Article/details/gt2qkiupkku.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.daxiang520.top/Article/details/gt2jsgzrchi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gt2tovvvtcc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pycfn.com/Article/details/gt2uknhvslk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gzhubu.top/Article/details/gt2rbmzehqj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlkwptdq.html

Go:   name := "Alex"; age := 20
来源：http://dali.aibaodan.cn/Article/details/gt2ekgwydwn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigfzy.top/Article/details/gt2mswslpvh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzcltdps.html

[A03] 常量定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckrqbgjw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.pycfn.com/Article/details/gt2byqnrhnk.html

PHP:  const PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2kairhydg.html

JS:   const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2rlfdxtsb.html

TS:   const PI: number = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2rjrfqoqi.html

Java: static final double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2kvwyrzqc.html

Go:   const PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gt2wrmlcxxq.html

Ruby: PI = 3.14159
来源：http://dali.andypj.xyz/Article/details/gt2ukqmxzps.html

C#:   const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2relnkdsi.html

[A04] 判断变量类型
来源：http://dali.zycfv.cn/Article/details/gt2kjgehfsq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gaohongyu789.top/Article/details/gt2nspggsoy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jyoumei.cn/Article/details/gt2dqpvqupt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gt2aaclwtww.html

TS:   typeof x; x instanceof Date
来源：http://dali.cheryme.top/Article/details/gt2klgbicyp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hysaishi.cn/Article/details/gt2jtdtfoft.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkuwmcgs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shuidangran.top/Article/details/gt2bkqcwhqa.html

C#:   x.GetType().Name; x is int
来源：http://dali.sweek.top/Article/details/gt2jlldyrbm.html

[A05] 整数除法与取模
来源：http://dali.guowangkeji.top/Article/details/gt2gjatjunp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.birdmap.top/Article/details/gt2ljphbpka.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzkmsyug.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gt2doewhabw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2gnnkckla.html

Java: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2syprnoxx.html

Go:   7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2ulihusjb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqyzpfyp.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qlkzehpc.html

[A06] 字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gt2ngjlwzsi.html

Py:   int("42"); float("3.14")
来源：http://dali.tanke756.top/Article/details/gt2winnyhay.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yanxiufei.cn/Article/details/gt2arieyumk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xinyue.icu/Article/details/gt2zxdoslqm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tanke756.top/Article/details/gt2rizutomh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.smart0.xyz/Article/details/gt2lqmnksdf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cucudq.cn/Article/details/gt2wyewxhsu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.aibaodan.cn/Article/details/gt2lfylhfzs.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvpdpyfb.html

[A07] 数字转字符串
来源：http://dali.yuxming.cn/Article/details/gt2tbodwvdq.html

Py:   str(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2cexltxql.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinqigufen.top/Article/details/gt2gspmtahz.html

JS:   String(42); (42).toString()
来源：http://dali.yueranfly.top/Article/details/gt2yrdrdzga.html

TS:   String(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aagbgvul.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenzaomai.com/Article/details/gt2nsnryawl.html

Go:   strconv.Itoa(42)
来源：http://dali.gogol.net.cn/Article/details/gt2rciutahe.html

Ruby: 42.to_s
来源：http://dali.wangdashe.top/Article/details/gt2bycruivm.html

C#:   42.ToString()
来源：http://dali.mhx1999.top/Article/details/gt2ifiekzeh.html

[A08] 取整与四舍五入
来源：http://dali.quarkkingdee.top/Article/details/gt2ebyvbtbc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gt2xggpalzi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.daria6918.cn/Article/details/gt2nkycpapo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gt2ncpbniuw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.svipenyu.cn/Article/details/gt2fkyxpwuk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gt2mwdzehvt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gt2tdvidiyp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.aizwys.cn/Article/details/gt2fzcrwqjd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gt2tanhhmzr.html

[A09] 绝对值与最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2zgfwudys.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2togpiytv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2mwjenzhd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2wsfikuex.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2mrdctfzk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hammf.cn/Article/details/gt2corwjbxi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hysaishi.cn/Article/details/gt2abxmpcjk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuswxrdn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xylfe.cn/Article/details/gt2iwncjqqq.html

[A10] 生成随机数
来源：http://dali.mhx1999.top/Article/details/gt2xjpqynkn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwssjttn.html

PHP:  random_int(1, 100);
来源：http://dali.nanxuanxn.top/Article/details/gt2eqcpvjdx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sxryk.cn/Article/details/gt2gprqltui.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cheryme.top/Article/details/gt2cwujhhlo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cqqwz.cn/Article/details/gt2cfpktrwg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gzhubu.top/Article/details/gt2xwrlcezt.html

Ruby: rand(1..100)
来源：http://dali.zhongyouzk.top/Article/details/gt2beylgnjq.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yewnszll.html

[A11] 条件表达式（三元）
来源：http://dali.tanke756.top/Article/details/gt2iajrdqpy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.redwolf501.top/Article/details/gt2smvkmbgm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gt2oelddcom.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gt2pvfahhcs.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gt2oofiganu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gt2kswyzdvd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.birdmap.top/Article/details/gt2rsgziezn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gt2vspxwqdf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2gplmjggv.html

[A12] 字符串插值 / 格式化
来源：http://dali.yongpay.top/Article/details/gt2fwxeqsjd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.nanxuanxn.top/Article/details/gt2cnreqyjq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhixingplan.top/Article/details/gt2ejcuzfsn.html

JS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gt2cgeaqnux.html

TS:   `Hello, ${name}!`
来源：http://dali.jlsjyb.cn/Article/details/gt2emflxvcj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xylfe.cn/Article/details/gt2gpzhpxih.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yj20258888.top/Article/details/gt2nlizxtdy.html

Ruby: "Hello, #{name}!"
来源：http://dali.quarkkingdee.top/Article/details/gt2fwsrowdg.html

C#:   $"Hello, {name}!"
来源：http://dali.guannengcc.top/Article/details/gt2fvemyjll.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yvedp.cn/Article/details/gt2ypuvkjue.html

Py:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gt2laayufme.html

PHP:  "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2ovpszljy.html

JS:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gt2sqnbjihx.html

TS:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gt2vpbcmdox.html

Java: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2yajmagfe.html

Go:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2krslpyvt.html

Ruby: "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gt2qygzghww.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2senjhucs.html

[A14] 注释写法
来源：http://dali.yj20258.top/Article/details/gt2byvskzyq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.pycfn.com/Article/details/gt2yizptjpy.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gt2yeijkvwf.html

JS:   // 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gt2iwwvgvxx.html

TS:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gt2bdggxtzg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gzhubu.top/Article/details/gt2dwmfldvd.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gt2gybajpbp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xylfe.cn/Article/details/gt2vuzjxiup.html

C#:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gt2zgqseveh.html

[A15] 空值判断与默认值
来源：http://dali.gotoacloud.top/Article/details/gt2hvqufhqz.html

Py:   value = data or "默认值"
来源：http://dali.jiagoushi.top/Article/details/gt2dbjtzqro.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gt2uguzmnkt.html

JS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gt2smkxxems.html

TS:   const value = data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gt2qoqnprab.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jiagoushi.top/Article/details/gt2urstgcxy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jianghu66.top/Article/details/gt2pwpadwtw.html

Ruby: value = data || "默认值"
来源：http://dali.hnxiangtu.top/Article/details/gt2iraerwse.html

C#:   var value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gt2tytqxvyh.html

[A16] 真假值判断规则
来源：http://dali.dashuyun.cn/Article/details/gt2nydhthqx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhengqikj.top/Article/details/gt2lzjwonav.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sufxvd.cn/Article/details/gt2lylnqcfh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbxbmiwj.html

TS:   if (!x) {}
来源：http://dali.chenlongwang.top/Article/details/gt2iylldnqh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.fzhhl.top/Article/details/gt2mydurxmi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.birdmap.top/Article/details/gt2vbdwhlyi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.chenzaomai.com/Article/details/gt2fcsernzg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.iojbl.cn/Article/details/gt2cqhfbxol.html

[A17] 位运算
来源：http://dali.hywenlv.cn/Article/details/gt2thudtdwv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2litylujw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yj20258888.top/Article/details/gt2eiwxcowm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gt2zbsolocl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gt2jhsxenab.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gt2ivkpksof.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2patnvwhj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gt2zefzoapb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gt2czjndtqf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.tianlin.xyz/Article/details/gt2qehgjatj.html

Py:   ord("A"); chr(65)
来源：http://dali.pycfn.com/Article/details/gt2aamypkds.html

PHP:  ord("A"); chr(65)
来源：http://dali.dianchejie.cn/Article/details/gt2yqjkbfvu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.meibo888.top/Article/details/gt2zxohvuze.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.aizwys.cn/Article/details/gt2lsrswuaf.html

Java: (int) 'A'; (char) 65
来源：http://dali.jyoumei.cn/Article/details/gt2qohpelpe.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.smart0.xyz/Article/details/gt2ucpdfhxg.html

Ruby: "A".ord; 65.chr
来源：http://dali.fengsongda.top/Article/details/gt2qalxulje.html

C#:   (int)'A'; (char)65
来源：http://dali.xinyue.icu/Article/details/gt2ibpqrusv.html

[A19] 交换两个变量
来源：http://dali.fzhhl.top/Article/details/gt2hvwedhcl.html

Py:   a, b = b, a
来源：http://dali.xylfe.cn/Article/details/gt2soaucyqn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hysaishi.cn/Article/details/gt2zpmbgrlt.html

JS:   [a, b] = [b, a];
来源：http://dali.zhengqikj.top/Article/details/gt2nmytgolz.html

TS:   [a, b] = [b, a];
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekdvhvfy.html

Java: int t = a; a = b; b = t;
来源：http://dali.gogol.net.cn/Article/details/gt2gqxfckwm.html

Go:   a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gt2eofbpryb.html

Ruby: a, b = b, a
来源：http://dali.birdmap.top/Article/details/gt2ujjczqmy.html

C#:   (a, b) = (b, a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2udfsvwsf.html

[A20] 读取标准输入
来源：http://dali.wangshuangyany.cn/Article/details/gt2zztqyseg.html

Py:   name = input("请输入：")
来源：http://dali.yj20258888.top/Article/details/gt2hdzvzffp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gt2obbzarhc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.0kj1m.cn/Article/details/gt2nkztcnrx.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2ivzqphjb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbakoiip.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.pycfn.com/Article/details/gt2oflgbuoj.html

Ruby: gets.chomp
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwdptlgw.html

C#:   Console.ReadLine();
来源：http://dali.yj20258888.top/Article/details/gt2ffmqrrwt.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfmijhnm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gotoacloud.top/Article/details/gt2oglfbxqu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gt2hlnmgnzb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gt2ottlifqx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2eexwxgvy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gt2sfszzmum.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxmovyyw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gt2bydmnjvo.html

C#:   3.14159.ToString("F2")
来源：http://dali.shzxlz.cn/Article/details/gt2vtuhlnql.html

[A22] 获取字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2nvpldqjl.html

Py:   len(s)
来源：http://dali.chenlongwang.top/Article/details/gt2kqekbsjr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hnxiangtu.top/Article/details/gt2wugevfhv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrndheod.html

TS:   s.length
来源：http://dali.bjfxy.top/Article/details/gt2mfjwbpba.html

Java: s.length()
来源：http://dali.yuanzhike.top/Article/details/gt2kqxygpuy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.daxiang520.top/Article/details/gt2thrkxdfo.html

Ruby: s.length
来源：http://dali.chenlongwang.top/Article/details/gt2eydvzrvm.html

C#:   s.Length
来源：http://dali.yonumen.top/Article/details/gt2cchqlxaw.html

[A23] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2nvwjilqv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cqqwz.cn/Article/details/gt2jysrumkl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.haohaochexian.top/Article/details/gt2tvysggqw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gt2tvtmsfut.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gt2qecyhkez.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gt2xswqcfaz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpzlefh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gt2miccuwyy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zdqjudy.top/Article/details/gt2mjmcnuax.html

[A24] 去除首尾空白
来源：http://dali.haohaochexian.top/Article/details/gt2bglixdcr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.haohaochexian.top/Article/details/gt2vlkuroex.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.0kj1m.cn/Article/details/gt2juuqdmpo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ybcxt.top/Article/details/gt2ladlzuvy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258888.top/Article/details/gt2mzcznopw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xziqi.cn/Article/details/gt2aciftpel.html

Go:   strings.TrimSpace(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttfjhzda.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzhymhiu.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gt2avnggwzh.html

[A25] 字符串比较
来源：http://dali.yonumen.top/Article/details/gt2vnuscafa.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aibaodan.cn/Article/details/gt2avfrvltr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fzhhl.top/Article/details/gt2dnckrywb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gt2oxzynxgm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzwyxcea.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258888.top/Article/details/gt2ymyzjvit.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sufxvd.cn/Article/details/gt2xzayandt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gt2ghnwzaew.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gt2xvqctmdk.html

[A26] 类型转换总览
来源：http://dali.hfpthk.cn/Article/details/gt2jfbieuur.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ehwqpu.com/Article/details/gt2nmnbtocg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cdnleiting.top/Article/details/gt2wbnwbecc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.guowangkeji.top/Article/details/gt2bwxeiyff.html

TS:   Number() String() Boolean() x as number
来源：http://dali.svipenyu.cn/Article/details/gt2sjqjadhs.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xoucjcbj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xuanzx.com/Article/details/gt2hvfvresx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnxaglzi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gt2crsrnymq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ihguldwl.html

B. 流程控制
来源：http://dali.cdnleiting.top/Article/details/gt2kasjyret.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2cekcvrzw.html

[B01] 条件判断 if / else
来源：http://dali.jiagoushi.top/Article/details/gt2dujazayp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqfegdjl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.aibaodan.cn/Article/details/gt2iozthvzy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gt2dghhdjvv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gt2xlkwzgfc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gt2gysomdlp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iapjgjiq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hammf.cn/Article/details/gt2rqnryefq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gt2tzxqjkse.html

[B02] 多分支 else if / elif
来源：http://dali.yuxming.cn/Article/details/gt2zujhbavv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fzhhl.top/Article/details/gt2detmzubw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daria6918.cn/Article/details/gt2oiczbmat.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2xrdmqppg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gt2cijvjdwp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2khzmbpfw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bitodnvo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ydzc1.top/Article/details/gt2jltiqfjp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gt2qtrvsylv.html

[B03] switch / match / case
来源：http://dali.yuxming.cn/Article/details/gt2lxoxcpot.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aibaodan.cn/Article/details/gt2osnhhtkl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wirnkvyd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hntswsae.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gt2gzuitand.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gt2fdjrzolf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xziqi.cn/Article/details/gt2fbtpvmra.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxinkj.top/Article/details/gt2wqjsjajz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.meibo888.top/Article/details/gt2qrtegeew.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gt2nzltzrok.html

Py:   for i in range(10): print(i)
来源：http://dali.havefunace.top/Article/details/gt2rkoxyxkn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcmqedcb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pycfn.com/Article/details/gt2zmamqedk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgfzy.top/Article/details/gt2pxeaykde.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xinyue.icu/Article/details/gt2rdpfrnrc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jyoumei.cn/Article/details/gt2xdjczyee.html

Ruby: 10.times { |i| puts i }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oylnqott.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhengqikj.top/Article/details/gt2oeasjubs.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gt2ekhictjw.html

Py:   for item in arr: print(item)
来源：http://dali.gogol.net.cn/Article/details/gt2qawzzhqp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xylfe.cn/Article/details/gt2eujclgcv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gt2rvforlno.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gt2kmuwwyss.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2istmsasw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlabccoo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xziqi.cn/Article/details/gt2vhowgsqx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yueranfly.top/Article/details/gt2ybcpgihw.html

[B06] 遍历字典 / 对象
来源：http://dali.birdmap.top/Article/details/gt2bmpadhtr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.quarkkingdee.top/Article/details/gt2akowkpib.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yuxming.cn/Article/details/gt2ndkvulwk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gt2kokifacx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbicmssn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daria6918.cn/Article/details/gt2pawsfopv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ydzc1.top/Article/details/gt2lekztxat.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wulirscb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shuidangran.top/Article/details/gt2xxmlsykf.html

[B07] while 循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xscxksmc.html

Py:   while i < 10: i += 1
来源：http://dali.gotoacloud.top/Article/details/gt2bobdmzbq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guowangkeji.top/Article/details/gt2jjpjpquy.html

JS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2gkfbwquu.html

TS:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gt2jxhzdshf.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gt2ftitzybu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ybcxt.top/Article/details/gt2uokbdroe.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fengsongda.top/Article/details/gt2cmepafag.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gt2vsqohoky.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gt2hhszuzce.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.smart0.xyz/Article/details/gt2vylnbowm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2eanbaqei.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gt2edpuiivp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2xzfzgoyc.html

Java: do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owckmtlg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gt2kivrtoni.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhixingplan.top/Article/details/gt2gbdukchk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2xjtfgdut.html


<!-- 参考信息 -->