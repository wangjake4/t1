代发 wailian999

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtybgjcxtf.html

[A03] 常量定义
来源：http://dali.feifeiyinyue.top/Article/details/gtdnqsblpe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.andypj.xyz/Article/details/gttqbvqhrw.html

PHP:  const PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtohysszqc.html

JS:   const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtsdxnfidl.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtrtzowyhy.html

Java: static final double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtzdvabnfb.html

Go:   const PI = 3.14159
来源：http://dali.jqgfzy.top/Article/details/gtcapowwoa.html

Ruby: PI = 3.14159
来源：http://dali.smart0.xyz/Article/details/gtfbyqphym.html

C#:   const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtnmtlphie.html

[A04] 判断变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtqulwluzy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gtoysdtpbl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.iojbl.cn/Article/details/gtcsbkjxok.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhongyouzk.top/Article/details/gtdtrsonve.html

TS:   typeof x; x instanceof Date
来源：http://dali.nwbrower.top/Article/details/gtywgfqzur.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhiwuduotai.top/Article/details/gtgdeprceq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hongshengwenyu.top/Article/details/gtpgfaighe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tianlin.xyz/Article/details/gtbacdqwpq.html

C#:   x.GetType().Name; x is int
来源：http://dali.ydzc1.top/Article/details/gtilrinmkm.html

[A05] 整数除法与取模
来源：http://dali.haohaochexian.top/Article/details/gtbsxjcgho.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jlsjyb.cn/Article/details/gtoqwmdkoc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjmnpoav.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtbromwqli.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gtqglvhetu.html

Java: 7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtkvxktsmm.html

Go:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtkbefnnip.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtdfhjzhvv.html

C#:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtesalaleq.html

[A06] 字符串转数字
来源：http://dali.pycfn.com/Article/details/gtkcoccxgx.html

Py:   int("42"); float("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtmkovirmh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yvedp.cn/Article/details/gtopvstudo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.haohaochexian.top/Article/details/gtdbifamcf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hongshengwenyu.top/Article/details/gtvfraopri.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aizwys.cn/Article/details/gtsonqshgg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.haohaochexian.top/Article/details/gtiuwsbyrv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sysykeji.top/Article/details/gtglsnskcf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258.top/Article/details/gtaebfbltz.html

[A07] 数字转字符串
来源：http://dali.tian-w.cn/Article/details/gtqnkcwfuv.html

Py:   str(42)
来源：http://dali.zdqjudy.top/Article/details/gtgppbxkmd.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhixingplan.top/Article/details/gteagjxena.html

JS:   String(42); (42).toString()
来源：http://dali.ivvv.top/Article/details/gtfipkvpyt.html

TS:   String(42)
来源：http://dali.tanke756.top/Article/details/gtvtlwwgwz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sufxvd.cn/Article/details/gtfirzfnsx.html

Go:   strconv.Itoa(42)
来源：http://dali.vqdsnc.cn/Article/details/gtsgtsucry.html

Ruby: 42.to_s
来源：http://dali.cucudq.cn/Article/details/gttlmghicq.html

C#:   42.ToString()
来源：http://dali.hnqzz.top/Article/details/gtonspjgel.html

[A08] 取整与四舍五入
来源：http://dali.yuxming.cn/Article/details/gtbheckwqq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gthezwfxdh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuanzhike.top/Article/details/gtupkylpxd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gtfrvrrzol.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpftmwlkm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gthbloyziz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtzqlvxyoz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hammf.cn/Article/details/gtsazymmcz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswqtesqz.html

[A09] 绝对值与最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizyyuqbs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtvclmbrxq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtfwhmvwkb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtevwvdirb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtkcexfeio.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtrsghkobp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hywenlv.cn/Article/details/gtomzadkwd.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.svipenyu.cn/Article/details/gtfungjqnx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtijyiomer.html

[A10] 生成随机数
来源：http://dali.aibaodan.cn/Article/details/gtfufbcfpu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jinqigufen.top/Article/details/gtwznbmytw.html

PHP:  random_int(1, 100);
来源：http://dali.zdqjudy.top/Article/details/gtnuutmztp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hammf.cn/Article/details/gtzfmteaba.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jyoumei.cn/Article/details/gtpjddkzuo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gtmepodmyi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shzxlz.cn/Article/details/gtzkpicean.html

Ruby: rand(1..100)
来源：http://dali.daxiang520.top/Article/details/gtczocbpoj.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhoulong.xyz/Article/details/gtcljfkrjj.html

[A11] 条件表达式（三元）
来源：http://dali.yongpay.top/Article/details/gtigopwcvp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.vqdsnc.cn/Article/details/gtodwzngvh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtrqbtkklq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gttgvwtwud.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtljmdchfi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtwglybccj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jiagoushi.top/Article/details/gtgangngdd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gtvtupwtaw.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtpmxqvzpt.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhoulong.xyz/Article/details/gtqgykrrlx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.redwolf501.top/Article/details/gtvfyvwbdm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jyoumei.cn/Article/details/gtpzeufkrp.html

JS:   `Hello, ${name}!`
来源：http://dali.sweek.top/Article/details/gtwueaarew.html

TS:   `Hello, ${name}!`
来源：http://dali.sysykeji.top/Article/details/gtrziflrmu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.tanke756.top/Article/details/gtfmepsgut.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yj202588.top/Article/details/gtziyqcsqv.html

Ruby: "Hello, #{name}!"
来源：http://dali.xuanzx.com/Article/details/gtbjeytcpn.html

C#:   $"Hello, {name}!"
来源：http://dali.jinqigufen.top/Article/details/gtqxlnuros.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhoulong.xyz/Article/details/gtghuwuhvp.html

Py:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtlxhhdvxn.html

PHP:  "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtmslfoqtx.html

JS:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtjngakhag.html

TS:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtmbyxhqwx.html

Java: "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtbmkhgddw.html

Go:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gtunuewxwt.html

Ruby: "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtmkbwhdhs.html

C#:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtglsxmtvn.html

[A14] 注释写法
来源：http://dali.sxryk.cn/Article/details/gttsbvfjcc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.redwolf501.top/Article/details/gttntpposc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gterohzcok.html

JS:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtuggfbvou.html

TS:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtmyzrkjji.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sweek.top/Article/details/gtnacobffu.html

Go:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtwuezrrxa.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yj20258.top/Article/details/gtxalgdiyd.html

C#:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gtjltayuve.html

[A15] 空值判断与默认值
来源：http://dali.c1oappe.top/Article/details/gtgssmetms.html

Py:   value = data or "默认值"
来源：http://dali.jinqigufen.top/Article/details/gtmliofwtg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhengqikj.top/Article/details/gtsstqkavu.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinqigfzy.top/Article/details/gtbzjzzhgq.html

TS:   const value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gtrnybistm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj202588.top/Article/details/gtlbbrtwnr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cucudq.cn/Article/details/gtgvgwelqx.html

Ruby: value = data || "默认值"
来源：http://dali.jlsjyb.cn/Article/details/gtzcwaneft.html

C#:   var value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtjjcgkuql.html

[A16] 真假值判断规则
来源：http://dali.cqqwz.cn/Article/details/gtwvbhyulb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ybcxt.top/Article/details/gtocugdsue.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.snrcjt.cn/Article/details/gtoaxdhkfh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zycfv.cn/Article/details/gteckfrkbk.html

TS:   if (!x) {}
来源：http://dali.jinqigfzy.top/Article/details/gtmvdtehfi.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hywenlv.cn/Article/details/gtqjdqxgdm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ppjwa.cn/Article/details/gtbyutulwq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.haohaochexian.top/Article/details/gtxgdjlubs.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrnsnjmi.html

[A17] 位运算
来源：http://dali.hysaishi.cn/Article/details/gtitergztt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtpesnysbg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepxxlepy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtpibjvmff.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gtilgyqurn.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtiphughpn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtghgeaatj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtpgqhjqvk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtunqymxeg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsrnooay.html

Py:   ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gtinqfnxoo.html

PHP:  ord("A"); chr(65)
来源：http://dali.cucudq.cn/Article/details/gtqxpbplsk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yonumen.top/Article/details/gtnerqensg.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guowangkeji.top/Article/details/gtyqaxjzri.html

Java: (int) 'A'; (char) 65
来源：http://dali.birdmap.top/Article/details/gtbqepxxif.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cucudq.cn/Article/details/gtlvdwueeh.html

Ruby: "A".ord; 65.chr
来源：http://dali.cdnleiting.top/Article/details/gtncxzgrcg.html

C#:   (int)'A'; (char)65
来源：http://dali.wangdashe.top/Article/details/gteejicumx.html

[A19] 交换两个变量
来源：http://dali.feifeiyinyue.top/Article/details/gtqjkndify.html

Py:   a, b = b, a
来源：http://dali.xylfe.cn/Article/details/gtuaeyntua.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpcwkckb.html

JS:   [a, b] = [b, a];
来源：http://dali.andypj.xyz/Article/details/gtxmopwnko.html

TS:   [a, b] = [b, a];
来源：http://dali.yangfankeji.com/Article/details/gtykucsadv.html

Java: int t = a; a = b; b = t;
来源：http://dali.cheryme.top/Article/details/gtrpaeaonm.html

Go:   a, b = b, a
来源：http://dali.hnqzz.top/Article/details/gtxtamlumv.html

Ruby: a, b = b, a
来源：http://dali.316326.xyz/Article/details/gtcllmqfto.html

C#:   (a, b) = (b, a);
来源：http://dali.hfpthk.cn/Article/details/gtlthizjsj.html

[A20] 读取标准输入
来源：http://dali.gzhubu.top/Article/details/gtyworcwph.html

Py:   name = input("请输入：")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqbrfuko.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gzhubu.top/Article/details/gtlpunokno.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shuidangran.top/Article/details/gtbhfiygpy.html

TS:   // Node.js：readline 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnryynewf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.nanxinkj.top/Article/details/gtnpuojqkk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinqigufen.top/Article/details/gtgqgbotvu.html

Ruby: gets.chomp
来源：http://dali.shuidangran.top/Article/details/gtcebgvtey.html

C#:   Console.ReadLine();
来源：http://dali.zhoulong.xyz/Article/details/gtkxnwrniz.html

[A21] 保留指定小数位输出
来源：http://dali.jianghu66.top/Article/details/gtxkrbpjfa.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sxryk.cn/Article/details/gtedwdvqcg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtxxvbgrtd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtclrpafmr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gtgysobnyg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtbvkkghyb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cheryme.top/Article/details/gtdsqwvaop.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gtxkxoiqec.html

C#:   3.14159.ToString("F2")
来源：http://dali.sysykeji.top/Article/details/gtqlxiatti.html

[A22] 获取字符串长度
来源：http://dali.aizwys.cn/Article/details/gtiyyyfkty.html

Py:   len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmviwvfkr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cheryme.top/Article/details/gtqoucpyyr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhengqikj.top/Article/details/gtzfdlgnew.html

TS:   s.length
来源：http://dali.svipenyu.cn/Article/details/gtiualtszt.html

Java: s.length()
来源：http://dali.gzhubu.top/Article/details/gtftaabbwy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtlntqkxqx.html

Ruby: s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtxkkukusd.html

C#:   s.Length
来源：http://dali.zycfv.cn/Article/details/gtwfmaowkx.html

[A23] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtwkitsjdf.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinqigfzy.top/Article/details/gtpwccqhfa.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinqigfzy.top/Article/details/gttynwhabk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gttwxmsuxy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gtfmeqcjqq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gtycykresp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yongpay.top/Article/details/gtfdqrvket.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtotzismnq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljynwflt.html

[A24] 去除首尾空白
来源：http://dali.mhx1999.top/Article/details/gtocnxublv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xziqi.cn/Article/details/gtjmcrmegj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.feifeiyinyue.top/Article/details/gtdrehwydg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtzsgnvgkg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nwbrower.top/Article/details/gtcapbbsyk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.svipenyu.cn/Article/details/gtgetqokrw.html

Go:   strings.TrimSpace(s)
来源：http://dali.snrcjt.cn/Article/details/gtsxlzexur.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhongyouzk.top/Article/details/gtlavdwiod.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.9152youxi.cn/Article/details/gtrfdtsogw.html

[A25] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtrccrxjfp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.birdmap.top/Article/details/gtsqbuuxgc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hammf.cn/Article/details/gtxsvvzclj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gtykpbxqxy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gtppmykkwv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sysykeji.top/Article/details/gtpyxepqpn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtunbuxkbc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngarnalq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dianchejie.cn/Article/details/gtmluvhglk.html

[A26] 类型转换总览
来源：http://dali.sweek.top/Article/details/gtkgpsnymw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gzhubu.top/Article/details/gtrddzlpqv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hysaishi.cn/Article/details/gtpwzzttkv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hammf.cn/Article/details/gtdjtutvnr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangdashe.top/Article/details/gtkiorsdhg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsdmhmav.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aibaodan.cn/Article/details/gtxfxygsmx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.wangdashe.top/Article/details/gtkgdivpmc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gtjelwfcjv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtaoaouzej.html

B. 流程控制
来源：http://dali.yueranfly.top/Article/details/gtlajjftyx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtaskfaxrw.html

[B01] 条件判断 if / else
来源：http://dali.tanke756.top/Article/details/gtxxewxqha.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxuanxn.top/Article/details/gtzjznnses.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sysykeji.top/Article/details/gtdmfsfvvd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjxxyqlb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gtcyivwqbk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtmtszlwoo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sweek.top/Article/details/gtynmkjack.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gogol.net.cn/Article/details/gtvyseomqb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gthnmwspys.html

[B02] 多分支 else if / elif
来源：http://dali.svipenyu.cn/Article/details/gtaixnewaw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.meibo888.top/Article/details/gtdsgeoupm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aibaodan.cn/Article/details/gtkkhadbol.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtmmlffzxj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtffqhucfh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtbymnykul.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jlsjyb.cn/Article/details/gtgvzurifg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.316326.xyz/Article/details/gtaqydgolz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtvrngdezs.html

[B03] switch / match / case
来源：http://dali.zhongyouzk.top/Article/details/gtprhqfqer.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhixingplan.top/Article/details/gtquwbhinn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtynznytni.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gturqcrpzn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaljgxwpq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtbtbncgpm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pycfn.com/Article/details/gtxmiglahs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.svipenyu.cn/Article/details/gtrqywrxct.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.guannengcc.top/Article/details/gtdqcfylhe.html

[B04] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gtkyzisavr.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gtmseoochk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.meibo888.top/Article/details/gthqxxxyjk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gtytxmxajr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gtlselltks.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fzhhl.top/Article/details/gtlwduqgxh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yanxiufei.cn/Article/details/gtlcokjkkp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjtzwwbj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fzhhl.top/Article/details/gtnctejkxj.html

[B05] 遍历数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gtibevxmpg.html

Py:   for item in arr: print(item)
来源：http://dali.andypj.xyz/Article/details/gtcppplvwa.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gtcmnfvnga.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.andypj.xyz/Article/details/gtqchzduuy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gtybkmmrvi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnxiangtu.top/Article/details/gtdohyrdkp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gtfqhlwegr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gtpwspbupk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldnquhmy.html

[B06] 遍历字典 / 对象
来源：http://dali.tian-w.cn/Article/details/gthwenrdrj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cucudq.cn/Article/details/gtbcptsocl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cqqwz.cn/Article/details/gtojhfdpst.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gtdqrzcugl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gtjuaojzwd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.smart0.xyz/Article/details/gtgmdbsuly.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.pengpengdd.cyou/Article/details/gtopghmdeg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgfzy.top/Article/details/gtmijweyvn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.316326.xyz/Article/details/gtpuftbkmn.html

[B07] while 循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthnmecba.html

Py:   while i < 10: i += 1
来源：http://dali.hywenlv.cn/Article/details/gtskfrvnnd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daria6918.cn/Article/details/gtcmkueauu.html

JS:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtejjpzryq.html

TS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtsvkpyjup.html

Java: while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtotvperlw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ppjwa.cn/Article/details/gtdkteixds.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sxryk.cn/Article/details/gtnodupnzn.html

C#:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtdyclbssr.html

[B08] do-while（至少执行一次）
来源：http://dali.wangshuangyany.cn/Article/details/gtaxwxntqy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ivvv.top/Article/details/gtkezldeik.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtnpekqnbx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtzriefmyd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtbeafwdzo.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtcghxqexd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258888.top/Article/details/gtafmrzywv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhixingplan.top/Article/details/gtaurskwls.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtbawjtaol.html

[B09] break 与 continue
来源：http://dali.daxiang520.top/Article/details/gtllnsbmga.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.andypj.xyz/Article/details/gtosdikuph.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtequemfvj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtgtjbauok.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtnjzyeyrk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtygkzrtkn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jianghu66.top/Article/details/gtbnxijuzh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnqzz.top/Article/details/gtypjvrsgt.html


<!-- 参考信息 -->