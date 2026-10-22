代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.tian-w.cn/Article/details/gtxrnhxpzv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenlongwang.top/Article/details/gtvcvadwhe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hammf.cn/Article/details/gtodtwajhh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258888.top/Article/details/gtqwcaqlpk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jiagoushi.top/Article/details/gtfkdoumtg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtxnmxajrb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhongyouzk.top/Article/details/gtnlhjostc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnqzz.top/Article/details/gtkzygwary.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.daxiang520.top/Article/details/gtduttipre.html

[A03] 常量定义
来源：http://dali.yanxiufei.cn/Article/details/gtmpfbisqe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.guowangkeji.top/Article/details/gtuhbcnial.html

PHP:  const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtaqvpbujd.html

JS:   const PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtfnrwlugz.html

TS:   const PI: number = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gteimwxzmv.html

Java: static final double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtzxdbkwns.html

Go:   const PI = 3.14159
来源：http://dali.jqgfzy.top/Article/details/gtrzcfkxcw.html

Ruby: PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtpkwyvqxg.html

C#:   const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtnnhncpxf.html

[A04] 判断变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtryoownsz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.316326.xyz/Article/details/gttswekeoa.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxuanxn.top/Article/details/gtpzfnqfdn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gtjuwjkfuc.html

TS:   typeof x; x instanceof Date
来源：http://dali.gaohongyu789.top/Article/details/gtvihnhbqt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gogol.net.cn/Article/details/gtezxjpvqp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cheryme.top/Article/details/gtxfrxjlyo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmofckkxy.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenzaomai.com/Article/details/gtahnfamtv.html

[A05] 整数除法与取模
来源：http://dali.tian-w.cn/Article/details/gtimxdduts.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ybcxt.top/Article/details/gtczkiqvsi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtzcqlfrxn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gtvizqexpa.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtwruxrbbx.html

Java: 7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtyfwcihym.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtksnbfsgy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtpoaunnef.html

C#:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtmzyhpwhg.html

[A06] 字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gttfynvsct.html

Py:   int("42"); float("3.14")
来源：http://dali.shuidangran.top/Article/details/gtxxvpdear.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cashguo.top/Article/details/gtzsixxtfe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yongpay.top/Article/details/gtwctnimib.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.pengpengdd.cyou/Article/details/gtkgxxmwcx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tian-w.cn/Article/details/gtyorqucdn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.wangdashe.top/Article/details/gtytyqimfy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zdqjudy.top/Article/details/gtdwdlvrqn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.birdmap.top/Article/details/gtznmhxmbc.html

[A07] 数字转字符串
来源：http://dali.ppjwa.cn/Article/details/gtxlvpktpz.html

Py:   str(42)
来源：http://dali.jiagoushi.top/Article/details/gttjotyggn.html

PHP:  (string) 42; strval(42)
来源：http://dali.jqgfzy.top/Article/details/gtfpbnsuwt.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gtzvxukdvx.html

TS:   String(42)
来源：http://dali.yj20258888.top/Article/details/gtapdwydxu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtuhhmxkiy.html

Go:   strconv.Itoa(42)
来源：http://dali.aizwys.cn/Article/details/gtrnpveurk.html

Ruby: 42.to_s
来源：http://dali.jqgfzy.top/Article/details/gtgyvtkfna.html

C#:   42.ToString()
来源：http://dali.ybcxt.top/Article/details/gtemlnqvpf.html

[A08] 取整与四舍五入
来源：http://dali.smart0.xyz/Article/details/gtbdpwcnea.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtlizcdcxk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nwbrower.top/Article/details/gtrjnexihe.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gtmgshjcvw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.snrcjt.cn/Article/details/gtxibgwdqo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtdkbdbykp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gtdndfvljj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuanzhike.top/Article/details/gtnrnvlnyq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtgmejndnm.html

[A09] 绝对值与最大最小值
来源：http://dali.cdnleiting.top/Article/details/gtgskeptkl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtynkfavkg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvbgkfol.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtdbemzevh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.316326.xyz/Article/details/gtfppdmyll.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtxqtckhfv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xinyue.icu/Article/details/gtticfhbcu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.redwolf501.top/Article/details/gtkfvjcyrn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtbhwwoexm.html

[A10] 生成随机数
来源：http://dali.yangfankeji.com/Article/details/gtkaolujru.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ehwqpu.com/Article/details/gtukeubzuf.html

PHP:  random_int(1, 100);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedypqbxf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.c1oappe.top/Article/details/gtnchylfng.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tian-w.cn/Article/details/gtlpwzgrwg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258888.top/Article/details/gtpitmdpyv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jianghu66.top/Article/details/gtmbrlgpjz.html

Ruby: rand(1..100)
来源：http://dali.yangfankeji.com/Article/details/gtshezatvb.html

C#:   new Random().Next(1, 101)
来源：http://dali.jiagoushi.top/Article/details/gtljxhcfsq.html

[A11] 条件表达式（三元）
来源：http://dali.sxryk.cn/Article/details/gtatfnbsiv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zdqjudy.top/Article/details/gtsvfgqnjx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gteavqgitz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gtzjllhmzx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtenperzsc.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtzdniasqk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hnqzz.top/Article/details/gttyzrdqly.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gtrpjpyjoq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqpuxijl.html

[A12] 字符串插值 / 格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtuszqaqab.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvptixpb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.aizwys.cn/Article/details/gtxlhtmsgg.html

JS:   `Hello, ${name}!`
来源：http://dali.zdqjudy.top/Article/details/gtvbezstws.html

TS:   `Hello, ${name}!`
来源：http://dali.chenzaomai.com/Article/details/gtesdziroh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jianghu66.top/Article/details/gtfvlfxkwk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtdkhocgqa.html

Ruby: "Hello, #{name}!"
来源：http://dali.daria6918.cn/Article/details/gtmjtxhnlx.html

C#:   $"Hello, {name}!"
来源：http://dali.zhengqikj.top/Article/details/gtklvriflt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpbmgduu.html

Py:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gttijxwnpd.html

PHP:  "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtbbnmkcds.html

JS:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtlaxagqtx.html

TS:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreyxsvzs.html

Java: "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtlrvmfvco.html

Go:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtjtbpwopc.html

Ruby: "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtnhwgsntg.html

C#:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtiqrawnkg.html

[A14] 注释写法
来源：http://dali.nwbrower.top/Article/details/gtdmjhjcic.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yj20258.top/Article/details/gtbkgxooqz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gtcwfckbuc.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gtdqsxqdaj.html

TS:   // 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gtjdscjzlg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.c1oappe.top/Article/details/gtxkgsvakh.html

Go:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtmepkmmhj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.haohaochexian.top/Article/details/gtsgusveer.html

C#:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtymuukgpf.html

[A15] 空值判断与默认值
来源：http://dali.quarkkingdee.top/Article/details/gtdowuquqo.html

Py:   value = data or "默认值"
来源：http://dali.feifeiyinyue.top/Article/details/gtdhlvnolt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtcluecrqf.html

JS:   const value = data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gtxksyvjrs.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gtiycwconu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gotoacloud.top/Article/details/gtpyvbywil.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tianlin.xyz/Article/details/gtmtiyvynv.html

Ruby: value = data || "默认值"
来源：http://dali.zhengqikj.top/Article/details/gtilgyxpll.html

C#:   var value = data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gtfihwbyuw.html

[A16] 真假值判断规则
来源：http://dali.zhoulong.xyz/Article/details/gtlqubxjln.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.daria6918.cn/Article/details/gtisttlhkv.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.mhx1999.top/Article/details/gteyloqjmx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zdqjudy.top/Article/details/gtsirnmllr.html

TS:   if (!x) {}
来源：http://dali.yueranfly.top/Article/details/gtzhynqupr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgvsazwj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jlsjyb.cn/Article/details/gtckqhdjbc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqjbgivb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.redwolf501.top/Article/details/gtdyzadphm.html

[A17] 位运算
来源：http://dali.jqgufenzy.top/Article/details/gtzalwetzw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtbpusgize.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yueranfly.top/Article/details/gtvglpwiwm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaagmqtu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtfjuthwle.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtabxwrjjr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtjhkxwsqk.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtdxifnyiq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtkkumwheo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhongyouzk.top/Article/details/gttjpucofk.html

Py:   ord("A"); chr(65)
来源：http://dali.vqdsnc.cn/Article/details/gtshxbzknj.html

PHP:  ord("A"); chr(65)
来源：http://dali.sxryk.cn/Article/details/gtnirnqxyv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guannengcc.top/Article/details/gtlyofkxwl.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.smart0.xyz/Article/details/gtoftnjifw.html

Java: (int) 'A'; (char) 65
来源：http://dali.dashuyun.cn/Article/details/gtybrgxtyf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.vqdsnc.cn/Article/details/gtsfnauidk.html

Ruby: "A".ord; 65.chr
来源：http://dali.yj202588.top/Article/details/gtkssygqah.html

C#:   (int)'A'; (char)65
来源：http://dali.cdnleiting.top/Article/details/gtzkiqbmqs.html

[A19] 交换两个变量
来源：http://dali.zhijiandao.cn/Article/details/gtrnyjxmuv.html

Py:   a, b = b, a
来源：http://dali.zdqjudy.top/Article/details/gtaeoxfjdg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hammf.cn/Article/details/gtqeivdklw.html

JS:   [a, b] = [b, a];
来源：http://dali.cqqwz.cn/Article/details/gtrwxikctu.html

TS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gtaihtrelw.html

Java: int t = a; a = b; b = t;
来源：http://dali.pengpengdd.cyou/Article/details/gtdwpojcyg.html

Go:   a, b = b, a
来源：http://dali.cheryme.top/Article/details/gteonsdkwj.html

Ruby: a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gtapthsslk.html

C#:   (a, b) = (b, a);
来源：http://dali.aizwys.cn/Article/details/gtdtrtxfnf.html

[A20] 读取标准输入
来源：http://dali.ybcxt.top/Article/details/gteurffdcd.html

Py:   name = input("请输入：")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmybthgiz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cdnleiting.top/Article/details/gtxmkdkgbj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhixingplan.top/Article/details/gtgrftbsio.html

TS:   // Node.js：readline 模块
来源：http://dali.316326.xyz/Article/details/gtadepuldb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cdnleiting.top/Article/details/gtnrhanotl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.snrcjt.cn/Article/details/gtkxubgbqx.html

Ruby: gets.chomp
来源：http://dali.yj20258.top/Article/details/gtokudmbkr.html

C#:   Console.ReadLine();
来源：http://dali.birdmap.top/Article/details/gtzvriyawk.html

[A21] 保留指定小数位输出
来源：http://dali.zhoulong.xyz/Article/details/gtbhgntuzz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhoulong.xyz/Article/details/gtsmfhzvrm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gtispljbej.html

JS:   (3.14159).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gtbaqywfzz.html

TS:   (3.14159).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtdfpxakgc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtmwzuqrzy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtmwquprqp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtqqbqscak.html

C#:   3.14159.ToString("F2")
来源：http://dali.birdmap.top/Article/details/gtwowzarjv.html

[A22] 获取字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtrpuutplh.html

Py:   len(s)
来源：http://dali.bjfxy.top/Article/details/gtrhtcoesx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.fengsongda.top/Article/details/gtjieypilv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangtech.top/Article/details/gtnilkweea.html

TS:   s.length
来源：http://dali.ehwqpu.com/Article/details/gtxzuzssnx.html

Java: s.length()
来源：http://dali.cheryme.top/Article/details/gtepticmtg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenlongwang.top/Article/details/gtjuhsxpvo.html

Ruby: s.length
来源：http://dali.redwolf501.top/Article/details/gtuhyzorna.html

C#:   s.Length
来源：http://dali.yuanzhike.top/Article/details/gtywlbsxez.html

[A23] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtjdxuvwtf.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gotoacloud.top/Article/details/gtzvgqkjgy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shangyingyoupin.top/Article/details/gtpbrwqrmi.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gtbmupcbrt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cucudq.cn/Article/details/gtcglzljmd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258888.top/Article/details/gtwxioslsh.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nwbrower.top/Article/details/gtyvpcjwsa.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtnilyvchc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zycfv.cn/Article/details/gtznxbgsev.html

[A24] 去除首尾空白
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmwmvoee.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sufxvd.cn/Article/details/gtsrzrdjvv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.quarkkingdee.top/Article/details/gthullulej.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gtmfbmoobo.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtdjzpzdcj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.snrcjt.cn/Article/details/gtzohwmvst.html

Go:   strings.TrimSpace(s)
来源：http://dali.xylfe.cn/Article/details/gtzaaqpazl.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.tian-w.cn/Article/details/gtsjlgbiga.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gtwjmncuix.html

[A25] 字符串比较
来源：http://dali.pycfn.com/Article/details/gtqmepfkei.html

Py:   s1 == s2; s1 != s2
来源：http://dali.wangdashe.top/Article/details/gtwaaidndg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.birdmap.top/Article/details/gtftipwbin.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gtaktqfver.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258888.top/Article/details/gtwnvhnpvu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258888.top/Article/details/gtjmggikii.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbykayngo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hywenlv.cn/Article/details/gtqavlzyqu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nanxinkj.top/Article/details/gtypwavxbp.html

[A26] 类型转换总览
来源：http://dali.daria6918.cn/Article/details/gtcfuhpuwz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.smart0.xyz/Article/details/gtmvwdzcyu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.svipenyu.cn/Article/details/gtwjnyrgqe.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgufenzy.top/Article/details/gtbvptiudo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ydzc1.top/Article/details/gthuhhrbuc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yonumen.top/Article/details/gtwpnwpmdq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gaohongyu789.top/Article/details/gtrxkfqebf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pycfn.com/Article/details/gtablswowo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.mhx1999.top/Article/details/gtfmwdttcb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjmwxbajn.html

B. 流程控制
来源：http://dali.chenzaomai.com/Article/details/gtefnoszse.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtskxfuvsy.html

[B01] 条件判断 if / else
来源：http://dali.guowangkeji.top/Article/details/gteauoulue.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.wangdashe.top/Article/details/gtgrktlmzo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.birdmap.top/Article/details/gteoakzhpb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtbygksggf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtjtniusyd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtgctlslow.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.mhx1999.top/Article/details/gtijlycmrt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.aizwys.cn/Article/details/gtfemtucse.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtdzdpmyds.html

[B02] 多分支 else if / elif
来源：http://dali.zhongyouzk.top/Article/details/gtznrvanrj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sysykeji.top/Article/details/gtvygjrcpc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.mhx1999.top/Article/details/gtsdluqkbd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtifvlvgkf.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtlqlgpixr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtxbvminxy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.fengsongda.top/Article/details/gthzptriwz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ydzc1.top/Article/details/gtkctmumuh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtkajjcxdf.html

[B03] switch / match / case
来源：http://dali.jinqigufen.top/Article/details/gtfacdrtan.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gtcugzrbvs.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtpaytrizd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtkskwjdtg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gtwnkbpwec.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gthzfprmul.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.wangdashe.top/Article/details/gtzgiziyto.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhongyouzk.top/Article/details/gtnmswpfzc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhiwuduotai.top/Article/details/gtuzwxmbjy.html

[B04] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtcpayuljs.html

Py:   for i in range(10): print(i)
来源：http://dali.gzhubu.top/Article/details/gtfzblonqo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gaohongyu789.top/Article/details/gtpjczjxai.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgfzy.top/Article/details/gtbkemblqx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtmbwezzjp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtlfzfirqx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gtqsrjbtsf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yongpay.top/Article/details/gtyzydixci.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gzhubu.top/Article/details/gtruaybgee.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtqsypbcrn.html

Py:   for item in arr: print(item)
来源：http://dali.sufxvd.cn/Article/details/gtihtwistw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.aizwys.cn/Article/details/gtocubedhf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gtmoendkip.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gtpxigszjy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258.top/Article/details/gtawcrbnni.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigfzy.top/Article/details/gtqdngatxw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuaxwnsre.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpovnpmvs.html

[B06] 遍历字典 / 对象
来源：http://dali.gotoacloud.top/Article/details/gtpugfcgja.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtihjngwcy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gotoacloud.top/Article/details/gtgieexduh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gthbibnqap.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gtvoydanmk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jiagoushi.top/Article/details/gtrtsqqdov.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cqqwz.cn/Article/details/gtrdzxlmgm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.iojbl.cn/Article/details/gtirrhkwan.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xziqi.cn/Article/details/gtfgubwijx.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gtnolzqlxn.html

Py:   while i < 10: i += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtviokuals.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtbvupirdi.html

JS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtmehgvxoq.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtoglwktuc.html

Java: while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtnrernkxu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guowangkeji.top/Article/details/gthnzawdmu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yangfankeji.com/Article/details/gtjeoldrdi.html

C#:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtkqfoqdbw.html

[B08] do-while（至少执行一次）
来源：http://dali.zycfv.cn/Article/details/gtiogzqvuc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gotoacloud.top/Article/details/gtmcjuvvxa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtkbbflhiw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gthqodpcxf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtevqawwmw.html

Java: do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtysgdkiws.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtgvqnwzmu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gtcjvrgadc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtktwrfwyp.html


<!-- 参考信息 -->