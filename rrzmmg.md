代发 wailian999

C#:   string name = "Alex"; int age = 20;
来源：http://dali.316326.xyz/Article/details/gtlptamwvp.html

[A03] 常量定义
来源：http://dali.hongshengwenyu.top/Article/details/gteppbhdxc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ehwqpu.com/Article/details/gtkglqrjay.html

PHP:  const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtstsbqlxv.html

JS:   const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtlhvzlbyn.html

TS:   const PI: number = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtqxuqvfrn.html

Java: static final double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtstkirevk.html

Go:   const PI = 3.14159
来源：http://dali.jyoumei.cn/Article/details/gtsmejyygq.html

Ruby: PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtedhidtpf.html

C#:   const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtvmxecqzi.html

[A04] 判断变量类型
来源：http://dali.xuanzx.com/Article/details/gtxiiftovm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hfpthk.cn/Article/details/gtqpqaserq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj202588.top/Article/details/gtniqedawv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yongpay.top/Article/details/gtuqyppyft.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258.top/Article/details/gtxosddttb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnxiangtu.top/Article/details/gtaxswameh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhbmcfrl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nwbrower.top/Article/details/gtemcrvvtw.html

C#:   x.GetType().Name; x is int
来源：http://dali.zycfv.cn/Article/details/gtruehxqok.html

[A05] 整数除法与取模
来源：http://dali.cqqwz.cn/Article/details/gtatnoeoni.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.redwolf501.top/Article/details/gtyjqtrneb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtlxakjdhb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gtdkksdnih.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtiohignsz.html

Java: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtysezyxxk.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtzohjtkoe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gtvexhmeet.html

C#:   7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtaflplwby.html

[A06] 字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtznbcdxlm.html

Py:   int("42"); float("3.14")
来源：http://dali.andypj.xyz/Article/details/gtvxraoqcc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ppjwa.cn/Article/details/gtfktghfcv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zycfv.cn/Article/details/gtetmpeguw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.vqdsnc.cn/Article/details/gttlmqwskx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtjqceddyr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinqigufen.top/Article/details/gtahtcjikj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shuidangran.top/Article/details/gtaiovqtcb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xziqi.cn/Article/details/gtdrauzzqy.html

[A07] 数字转字符串
来源：http://dali.chenzaomai.com/Article/details/gtwntijxcs.html

Py:   str(42)
来源：http://dali.iojbl.cn/Article/details/gtwnsgmrsz.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxinkj.top/Article/details/gtaqcecdmv.html

JS:   String(42); (42).toString()
来源：http://dali.xziqi.cn/Article/details/gtbhrylorj.html

TS:   String(42)
来源：http://dali.yanxiufei.cn/Article/details/gtgtnxirxl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cheryme.top/Article/details/gtcxhtmfgi.html

Go:   strconv.Itoa(42)
来源：http://dali.hnqzz.top/Article/details/gtevdbppyo.html

Ruby: 42.to_s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkplgaiqa.html

C#:   42.ToString()
来源：http://dali.gotoacloud.top/Article/details/gtllfzmoau.html

[A08] 取整与四舍五入
来源：http://dali.iojbl.cn/Article/details/gtkdfcqszs.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtwbbxchtd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cashguo.top/Article/details/gtqqyiskdf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtxmdbktjr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sysykeji.top/Article/details/gtommqfjcv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwabrkrmx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrdhndjz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhixingplan.top/Article/details/gteijmijxj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtayjsnuft.html

[A09] 绝对值与最大最小值
来源：http://dali.sxryk.cn/Article/details/gtnufvdagy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtaluptxhs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtnnkersyp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtsjlxjnbi.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtdmsvjnkm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtycyxffai.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cdnleiting.top/Article/details/gthgnsjyaa.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cqqwz.cn/Article/details/gtnejbmvor.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj20258.top/Article/details/gtxgkktmys.html

[A10] 生成随机数
来源：http://dali.chenzaomai.com/Article/details/gtrlgtoska.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jyoumei.cn/Article/details/gtqypiwkow.html

PHP:  random_int(1, 100);
来源：http://dali.smart0.xyz/Article/details/gtbztzqkai.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnxiangtu.top/Article/details/gtfibjhllo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtagtmnpku.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtumnlpxcf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.redwolf501.top/Article/details/gtnjkpamoo.html

Ruby: rand(1..100)
来源：http://dali.c1oappe.top/Article/details/gtfdcdqbce.html

C#:   new Random().Next(1, 101)
来源：http://dali.jlsjyb.cn/Article/details/gtymzixvzg.html

[A11] 条件表达式（三元）
来源：http://dali.jiagoushi.top/Article/details/gtihiiimjb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ehwqpu.com/Article/details/gtbzyyjjdj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gtajlhhwoz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtnezleweq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtgjaqljhb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gtvlejthkc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.9152youxi.cn/Article/details/gtbionbtop.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtfbelvowt.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtoqhqcvln.html

[A12] 字符串插值 / 格式化
来源：http://dali.jqgufenzy.top/Article/details/gtcxelekbx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jyoumei.cn/Article/details/gtohaokwvd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.birdmap.top/Article/details/gtfektchij.html

JS:   `Hello, ${name}!`
来源：http://dali.ybcxt.top/Article/details/gtmcpctxzs.html

TS:   `Hello, ${name}!`
来源：http://dali.havefunace.top/Article/details/gtspdqpdfp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hammf.cn/Article/details/gtqjtpxrhf.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jianghu66.top/Article/details/gtdzwfgheo.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gtycycwamo.html

C#:   $"Hello, {name}!"
来源：http://dali.jlsjyb.cn/Article/details/gtvuyrqlcp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.bjfxy.top/Article/details/gtqaejqgik.html

Py:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdznrhpr.html

PHP:  "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gtsluavmht.html

JS:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtudrzgmaa.html

TS:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtmpchnojx.html

Java: "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtwrrbouwi.html

Go:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gttevslimx.html

Ruby: "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtsctutgyv.html

C#:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtnlkciqks.html

[A14] 注释写法
来源：http://dali.jinghuilouyu.cn/Article/details/gtjekqkvnp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangtech.top/Article/details/gtotwqsovc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gtvityoecx.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gtftovmtem.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtshqmzqdp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhixingplan.top/Article/details/gtkpbxxggl.html

Go:   // 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtnrqbozcw.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.smart0.xyz/Article/details/gtbzsaoicx.html

C#:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gtsfitgmlz.html

[A15] 空值判断与默认值
来源：http://dali.mhx1999.top/Article/details/gtgqrdivkt.html

Py:   value = data or "默认值"
来源：http://dali.quarkkingdee.top/Article/details/gtxybjraen.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.feifeiyinyue.top/Article/details/gtpmjdkinm.html

JS:   const value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gttqhpvbrd.html

TS:   const value = data ?? "默认值";
来源：http://dali.feifeiyinyue.top/Article/details/gtsixsklnr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.chenzaomai.com/Article/details/gtvwjwpxaj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.9152youxi.cn/Article/details/gtuzsbupox.html

Ruby: value = data || "默认值"
来源：http://dali.svipenyu.cn/Article/details/gtbkcavkan.html

C#:   var value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtsxvpwyyb.html

[A16] 真假值判断规则
来源：http://dali.sysykeji.top/Article/details/gtbvesdicf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jqgfzy.top/Article/details/gtlluaurcm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.tianlin.xyz/Article/details/gtbjstrmom.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hnxiangtu.top/Article/details/gtnbyqiwyg.html

TS:   if (!x) {}
来源：http://dali.daria6918.cn/Article/details/gtlpwvrlrn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnkcepfbh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinqigfzy.top/Article/details/gtcpnisyhw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xuetiantiany.cn/Article/details/gttwqvtwas.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtyvxdmujy.html

[A17] 位运算
来源：http://dali.zhixingplan.top/Article/details/gtgeopmpgw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtxoyorsny.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtbsdwks.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtzsmszhnr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtorliuwsk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtisnmyezq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtvoidedbz.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtnskvmmyg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtpfsooiar.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yj202588.top/Article/details/gtejhvamqc.html

Py:   ord("A"); chr(65)
来源：http://dali.yuxming.cn/Article/details/gtmfendefi.html

PHP:  ord("A"); chr(65)
来源：http://dali.sysykeji.top/Article/details/gtwzbyiare.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jqgufenzy.top/Article/details/gtwdnhjzrp.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenlongwang.top/Article/details/gtefpajmel.html

Java: (int) 'A'; (char) 65
来源：http://dali.havefunace.top/Article/details/gtrjwppwbo.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.birdmap.top/Article/details/gtfuuzivkx.html

Ruby: "A".ord; 65.chr
来源：http://dali.cdnleiting.top/Article/details/gtvnrrupib.html

C#:   (int)'A'; (char)65
来源：http://dali.hfpthk.cn/Article/details/gthwlbdxvx.html

[A19] 交换两个变量
来源：http://dali.hywenlv.cn/Article/details/gtmrvqyfuu.html

Py:   a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gtibjqahyp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jyoumei.cn/Article/details/gtksaunaip.html

JS:   [a, b] = [b, a];
来源：http://dali.yanxiufei.cn/Article/details/gtmyoupvej.html

TS:   [a, b] = [b, a];
来源：http://dali.hywenlv.cn/Article/details/gtyiityfyt.html

Java: int t = a; a = b; b = t;
来源：http://dali.xuanzx.com/Article/details/gtsljhnwss.html

Go:   a, b = b, a
来源：http://dali.yuanzhike.top/Article/details/gthusttsmk.html

Ruby: a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gtlqjsrqbh.html

C#:   (a, b) = (b, a);
来源：http://dali.dashuyun.cn/Article/details/gtipgowmio.html

[A20] 读取标准输入
来源：http://dali.sufxvd.cn/Article/details/gtmloovsqe.html

Py:   name = input("请输入：")
来源：http://dali.hywenlv.cn/Article/details/gtgzutbdds.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuxming.cn/Article/details/gtqgybulpf.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jianghu66.top/Article/details/gtjahrlfdg.html

TS:   // Node.js：readline 模块
来源：http://dali.c1oappe.top/Article/details/gtjkbmnhzr.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yuanzhike.top/Article/details/gtoyuhvzdo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.birdmap.top/Article/details/gtpsrwjcod.html

Ruby: gets.chomp
来源：http://dali.ydzc1.top/Article/details/gtoorzquuj.html

C#:   Console.ReadLine();
来源：http://dali.gaohongyu789.top/Article/details/gtbbpaccsn.html

[A21] 保留指定小数位输出
来源：http://dali.jiagoushi.top/Article/details/gtxuvnolfk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yongpay.top/Article/details/gtaggrvvse.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtaufgfxks.html

JS:   (3.14159).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gtxfmopexq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtiajhxfdu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcemwwam.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthevanxzm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gtzjhcicea.html

C#:   3.14159.ToString("F2")
来源：http://dali.sysykeji.top/Article/details/gtwecxdpcf.html

[A22] 获取字符串长度
来源：http://dali.9152youxi.cn/Article/details/gthykatryg.html

Py:   len(s)
来源：http://dali.yj20258.top/Article/details/gtbkfmiboy.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shzxlz.cn/Article/details/gtxhfdgsom.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.pengpengdd.cyou/Article/details/gtunijugie.html

TS:   s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtzxymcbld.html

Java: s.length()
来源：http://dali.yuanzhike.top/Article/details/gtrqbuidcg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hnqzz.top/Article/details/gtpiusmbaz.html

Ruby: s.length
来源：http://dali.sufxvd.cn/Article/details/gtscvuhcvf.html

C#:   s.Length
来源：http://dali.aizwys.cn/Article/details/gtmfqadqse.html

[A23] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtfrgmaykp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.svipenyu.cn/Article/details/gtaomuvokc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.wangshuangyany.cn/Article/details/gtbahxayio.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gtjmzoaifr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gthntxkths.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtpcmpcpvw.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj20258888.top/Article/details/gtwmntbpny.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtlnrfiobr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.aizwys.cn/Article/details/gtdbeczyzf.html

[A24] 去除首尾空白
来源：http://dali.316326.xyz/Article/details/gtttjihsqy.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hongshengwenyu.top/Article/details/gtogbexwkb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cashguo.top/Article/details/gtvkxbsmks.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.feifeiyinyue.top/Article/details/gtbyefxkct.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cheryme.top/Article/details/gtnydqhzjg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shuidangran.top/Article/details/gtquoqvyun.html

Go:   strings.TrimSpace(s)
来源：http://dali.ehwqpu.com/Article/details/gtlpdwglsv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj20258.top/Article/details/gtshlrbfhq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.c1oappe.top/Article/details/gtemtezbll.html

[A25] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtxrsvanla.html

Py:   s1 == s2; s1 != s2
来源：http://dali.meibo888.top/Article/details/gtionlnlas.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtybuhlgoq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yvedp.cn/Article/details/gtttufjbaf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxinkj.top/Article/details/gtkrclbfyk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhixingplan.top/Article/details/gtvixrtkje.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gtnjybfpbk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.smart0.xyz/Article/details/gtirtlwgme.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gtczhpzazm.html

[A26] 类型转换总览
来源：http://dali.nanxinkj.top/Article/details/gtbobnwhiv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.aizwys.cn/Article/details/gtoflbggme.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xinyue.icu/Article/details/gtswvncfgz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinqigfzy.top/Article/details/gtgxdingbr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.feifeiyinyue.top/Article/details/gtilrctpqg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xylfe.cn/Article/details/gtucqqfhzy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.0kj1m.cn/Article/details/gtwnrstzax.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ivvv.top/Article/details/gtnjomidxp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hongshengwenyu.top/Article/details/gtinmwsaty.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtimofgcmc.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gtiiiivcxc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtelfdiblp.html

[B01] 条件判断 if / else
来源：http://dali.gaohongyu789.top/Article/details/gtrowwquji.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sufxvd.cn/Article/details/gtpmoesypt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zycfv.cn/Article/details/gtfhvqrcjl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtctyyappy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gtgdpleyxq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtpsxhatvx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhengqikj.top/Article/details/gtadvgvdiv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.redwolf501.top/Article/details/gtfzuymoyb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtqtrkpook.html

[B02] 多分支 else if / elif
来源：http://dali.jqgufenzy.top/Article/details/gtotlxfrle.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhoulong.xyz/Article/details/gtnuwirqdp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cheryme.top/Article/details/gtppqvtbwj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtetrowofk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyopbuiil.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtuhdetpqb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aizwys.cn/Article/details/gtggzcrisj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ehwqpu.com/Article/details/gtvqpbfebe.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtxatrifzk.html

[B03] switch / match / case
来源：http://dali.shanyushiyangtech.top/Article/details/gtqeqalzbm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.fzhhl.top/Article/details/gtpkblywzu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzbgxxcjl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlvtlsplm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtdalkuomq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtiglpmncl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.daria6918.cn/Article/details/gtaleqhsvz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhfkfpmo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fzhhl.top/Article/details/gtdvxssawu.html

[B04] for 计数循环
来源：http://dali.wangdashe.top/Article/details/gtgfjwhbva.html

Py:   for i in range(10): print(i)
来源：http://dali.jinqigufen.top/Article/details/gtfwzmdbfy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ppjwa.cn/Article/details/gtndjztjay.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtvojfyqlc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gtiruuapcf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jqgfzy.top/Article/details/gtlacxcsel.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.vqdsnc.cn/Article/details/gtkdjuepbt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuetiantiany.cn/Article/details/gthsuzosvt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yvedp.cn/Article/details/gtpgipyujb.html

[B05] 遍历数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gtuuuqhupt.html

Py:   for item in arr: print(item)
来源：http://dali.aibaodan.cn/Article/details/gtdytfymje.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jlsjyb.cn/Article/details/gtsqacyhmp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtfiteipou.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sxryk.cn/Article/details/gtbpbbycut.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hywenlv.cn/Article/details/gtwjluygta.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.smart0.xyz/Article/details/gtvhjjpeqa.html

Ruby: arr.each { |item| puts item }
来源：http://dali.9152youxi.cn/Article/details/gtktgmbbok.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtxhyizgea.html

[B06] 遍历字典 / 对象
来源：http://dali.nanxinkj.top/Article/details/gthwkszvvt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuanzx.com/Article/details/gtfcwbkepa.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiprdumgf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gtpafqlmew.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtpdavlgeb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj202588.top/Article/details/gtvutcqeib.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cucudq.cn/Article/details/gtqiklmnsd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yangfankeji.com/Article/details/gtphhlwqld.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ybcxt.top/Article/details/gtxsibdcjv.html

[B07] while 循环
来源：http://dali.wangdashe.top/Article/details/gtvwnmhxko.html

Py:   while i < 10: i += 1
来源：http://dali.bjfxy.top/Article/details/gthzptglkt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xylfe.cn/Article/details/gtefqcrxgn.html

JS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtguiizkif.html

TS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtkpncnmyd.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtnrrcysnm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.mhx1999.top/Article/details/gtgcgilvpl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dashuyun.cn/Article/details/gtvllniesg.html

C#:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtnjelhqmn.html

[B08] do-while（至少执行一次）
来源：http://dali.chenjidiqi.icu/Article/details/gtahqnzxri.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangshuangyany.cn/Article/details/gttytptrxs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yvedp.cn/Article/details/gtppqhwgjh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtahllcecg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtgdnoasuo.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtdkrwdgcj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjeezisj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.9152youxi.cn/Article/details/gtqgksjojd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtuypiiwrg.html

[B09] break 与 continue
来源：http://dali.hywenlv.cn/Article/details/gttljjyvor.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangdashe.top/Article/details/gtgyzwhwsp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtoknxsaga.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtfrsacpbw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtxvznapyx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtgpfdfktm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtzvoclnmq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenlongwang.top/Article/details/gtghfqidos.html


<!-- 参考信息 -->