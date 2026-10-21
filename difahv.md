代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.jinqigfzy.top/Article/details/gtehkjtztq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.pengpengdd.cyou/Article/details/gtjfnzuezw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xinyue.icu/Article/details/gtrisralmg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.fzhhl.top/Article/details/gtfgidnswg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gogol.net.cn/Article/details/gttswzsukt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tanke756.top/Article/details/gtgudyjjqm.html

Go:   name := "Alex"; age := 20
来源：http://dali.tanke756.top/Article/details/gtmahrldpf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxinkj.top/Article/details/gtixxlrvlq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtakxvrxmj.html

[A03] 常量定义
来源：http://dali.sxryk.cn/Article/details/gteadsyjsr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gtxuvbbdhw.html

PHP:  const PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtasmgyryb.html

JS:   const PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirhbnuug.html

TS:   const PI: number = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtnkhaurxi.html

Java: static final double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtgkyydvda.html

Go:   const PI = 3.14159
来源：http://dali.tanke756.top/Article/details/gttnzncpdx.html

Ruby: PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gtigvgalks.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtlwbivgob.html

[A04] 判断变量类型
来源：http://dali.zhengqikj.top/Article/details/gtugnimeue.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxlxmxji.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangdashe.top/Article/details/gthalydhpl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gtjajmnxnd.html

TS:   typeof x; x instanceof Date
来源：http://dali.cheryme.top/Article/details/gtzikazlmm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yangfankeji.com/Article/details/gtqzilrlef.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gotoacloud.top/Article/details/gtphkhsvrg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugkcjrgw.html

C#:   x.GetType().Name; x is int
来源：http://dali.bjfxy.top/Article/details/gtrzpcyvjl.html

[A05] 整数除法与取模
来源：http://dali.ydzc1.top/Article/details/gtokfztsxf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yanxiufei.cn/Article/details/gthzziovsy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtzrcdmzjs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtymggrlet.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtglpdpuiu.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtrzsunqis.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtcbblhbar.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtxuvmdizh.html

C#:   7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtxixgncvd.html

[A06] 字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtsrjpvxih.html

Py:   int("42"); float("3.14")
来源：http://dali.nwbrower.top/Article/details/gtnedlchjg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tanke756.top/Article/details/gtkjyufabh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangdashe.top/Article/details/gtxuewfdbq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cheryme.top/Article/details/gtzcmgqfex.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hammf.cn/Article/details/gtevdshkzg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtfefpdynu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yanxiufei.cn/Article/details/gtekxhegky.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gtdwemcias.html

[A07] 数字转字符串
来源：http://dali.aizwys.cn/Article/details/gtasgjpdxq.html

Py:   str(42)
来源：http://dali.aizwys.cn/Article/details/gtluyycsod.html

PHP:  (string) 42; strval(42)
来源：http://dali.cucudq.cn/Article/details/gtyjniacxm.html

JS:   String(42); (42).toString()
来源：http://dali.wangdashe.top/Article/details/gtfgvghnbp.html

TS:   String(42)
来源：http://dali.cdnleiting.top/Article/details/gtnylqbcem.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yongpay.top/Article/details/gtuhdwzmei.html

Go:   strconv.Itoa(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtxospxfpz.html

Ruby: 42.to_s
来源：http://dali.svipenyu.cn/Article/details/gttkxqogrw.html

C#:   42.ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxttsgwz.html

[A08] 取整与四舍五入
来源：http://dali.jiagoushi.top/Article/details/gteandawyf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtqamejdxt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigvswpoa.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gtjpdczhoi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.feifeiyinyue.top/Article/details/gtttjfarot.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtjcknjbbb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gtwtquzitp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.0kj1m.cn/Article/details/gtybfbegju.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtrjypuolo.html

[A09] 绝对值与最大最小值
来源：http://dali.tanke756.top/Article/details/gtiuwknssb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtjtjtfvop.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptnjzkrv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtygnynich.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtbfaqtprp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtlbdluwtp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ybcxt.top/Article/details/gtrthmhljk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.nanxuanxn.top/Article/details/gtjvngwvue.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtwdenjbcw.html

[A10] 生成随机数
来源：http://dali.jqgufenzy.top/Article/details/gtbjfcidpd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhiwuduotai.top/Article/details/gtneewottm.html

PHP:  random_int(1, 100);
来源：http://dali.havefunace.top/Article/details/gtnztxibsk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cdnleiting.top/Article/details/gtzohtlgcd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aibaodan.cn/Article/details/gtudozsevi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.feifeiyinyue.top/Article/details/gtbhftqskf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.svipenyu.cn/Article/details/gtnmbjkdtt.html

Ruby: rand(1..100)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrtorjyq.html

C#:   new Random().Next(1, 101)
来源：http://dali.xinyue.icu/Article/details/gtikwpyntb.html

[A11] 条件表达式（三元）
来源：http://dali.gotoacloud.top/Article/details/gtrebdqqsr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtotsuwd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtdjvrtdtr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtcxzuwsuc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtkewijjwe.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtzlyrkpvc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yangfankeji.com/Article/details/gtxsqzzxwx.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtpauxqjzg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtjqkwdqxo.html

[A12] 字符串插值 / 格式化
来源：http://dali.zdqjudy.top/Article/details/gtbznhokqn.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cashguo.top/Article/details/gtijeuukio.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jlsjyb.cn/Article/details/gttgliykbw.html

JS:   `Hello, ${name}!`
来源：http://dali.ybcxt.top/Article/details/gtjtivkuou.html

TS:   `Hello, ${name}!`
来源：http://dali.hnxiangtu.top/Article/details/gtuzfqtoic.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cdnleiting.top/Article/details/gtbzmrbqcn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.haohaochexian.top/Article/details/gtnhomvhmb.html

Ruby: "Hello, #{name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gtanbicxdj.html

C#:   $"Hello, {name}!"
来源：http://dali.yueranfly.top/Article/details/gtjqhqazot.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hysaishi.cn/Article/details/gtiqatgqzx.html

Py:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsbdkgzm.html

PHP:  "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtvubdkpvq.html

JS:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtlsxmzlkp.html

TS:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtjzczonab.html

Java: "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtuqcrlece.html

Go:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflxynlko.html

Ruby: "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtzhxzwjih.html

C#:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtmqqaxlyj.html

[A14] 注释写法
来源：http://dali.sysykeji.top/Article/details/gtdjltbqqa.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sxryk.cn/Article/details/gtrrtkehyx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gtybuulmex.html

JS:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gtekjuezjg.html

TS:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtsuxqxjyo.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhengqikj.top/Article/details/gtpwuhbsro.html

Go:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtzhsrktfg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zdqjudy.top/Article/details/gtdhiptutq.html

C#:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtsjbmqjoa.html

[A15] 空值判断与默认值
来源：http://dali.shzxlz.cn/Article/details/gtcjrjpfqj.html

Py:   value = data or "默认值"
来源：http://dali.jqgfzy.top/Article/details/gtqeefqwku.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtqolauttf.html

JS:   const value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtmvtnxevs.html

TS:   const value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtmcwrahvo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.smart0.xyz/Article/details/gtquwgvaxz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.aizwys.cn/Article/details/gtvcguagiz.html

Ruby: value = data || "默认值"
来源：http://dali.jinqigufen.top/Article/details/gtaqtymgra.html

C#:   var value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gtgwollcrr.html

[A16] 真假值判断规则
来源：http://dali.kuanghao11.cn/Article/details/gthbvxkctm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yanxiufei.cn/Article/details/gthsmxrsiz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj20258.top/Article/details/gtoeqgiogf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gaohongyu789.top/Article/details/gtojluixmj.html

TS:   if (!x) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqwbawmju.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shuidangran.top/Article/details/gtktqwfion.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.pycfn.com/Article/details/gtfwvmroiy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.svipenyu.cn/Article/details/gtmhmyjkwk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tian-w.cn/Article/details/gtphhwivys.html

[A17] 位运算
来源：http://dali.zhiwuduotai.top/Article/details/gtneztrxkp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtyafvxpwg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zycfv.cn/Article/details/gtjzmtbvec.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtnxixkotv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtgoiqpxlw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtoufktird.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtsnffhriy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtjcqdzvqi.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtllipzbra.html

[A18] 字符与 ASCII 码互转
来源：http://dali.feifeiyinyue.top/Article/details/gtpjjrwvbc.html

Py:   ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gtfuwcyueb.html

PHP:  ord("A"); chr(65)
来源：http://dali.ydzc1.top/Article/details/gttnjvrgnp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigufen.top/Article/details/gttwviuwzn.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnqzz.top/Article/details/gtesbdqukf.html

Java: (int) 'A'; (char) 65
来源：http://dali.tianlin.xyz/Article/details/gtpnmdpjou.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jqgfzy.top/Article/details/gtamfhutce.html

Ruby: "A".ord; 65.chr
来源：http://dali.pengpengdd.cyou/Article/details/gtqpnzrmxn.html

C#:   (int)'A'; (char)65
来源：http://dali.daria6918.cn/Article/details/gtnxzihjls.html

[A19] 交换两个变量
来源：http://dali.nwbrower.top/Article/details/gtzhijidye.html

Py:   a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gtpjptfkat.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhijiandao.cn/Article/details/gtwbabzmqf.html

JS:   [a, b] = [b, a];
来源：http://dali.daria6918.cn/Article/details/gtmmssrhob.html

TS:   [a, b] = [b, a];
来源：http://dali.redwolf501.top/Article/details/gtaajkoahc.html

Java: int t = a; a = b; b = t;
来源：http://dali.fzhhl.top/Article/details/gtqzuoltzc.html

Go:   a, b = b, a
来源：http://dali.ehwqpu.com/Article/details/gtslzywuhs.html

Ruby: a, b = b, a
来源：http://dali.havefunace.top/Article/details/gtmyhdlvex.html

C#:   (a, b) = (b, a);
来源：http://dali.kuanghao11.cn/Article/details/gtlxpjgbex.html

[A20] 读取标准输入
来源：http://dali.hnxiangtu.top/Article/details/gtybnstqhl.html

Py:   name = input("请输入：")
来源：http://dali.shanyushiyangtech.top/Article/details/gthjskiquq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sufxvd.cn/Article/details/gtcmermrdt.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.birdmap.top/Article/details/gtnqgkanbn.html

TS:   // Node.js：readline 模块
来源：http://dali.gaohongyu789.top/Article/details/gtuefgtels.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhengqikj.top/Article/details/gtnqboyuqg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenzaomai.com/Article/details/gtwmfbeuba.html

Ruby: gets.chomp
来源：http://dali.chenlongwang.top/Article/details/gtoxryarmo.html

C#:   Console.ReadLine();
来源：http://dali.yvedp.cn/Article/details/gturigrepi.html

[A21] 保留指定小数位输出
来源：http://dali.yonumen.top/Article/details/gtckpwmurg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xuetiantiany.cn/Article/details/gtddhiazrk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gthnepbmkm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtzlyzpqxs.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtfwvaruwl.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtvdswtwdo.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbamiuch.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gtqyrmvnps.html

C#:   3.14159.ToString("F2")
来源：http://dali.gogol.net.cn/Article/details/gtezgjtvuh.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgyfcsxo.html

Py:   len(s)
来源：http://dali.hysaishi.cn/Article/details/gtvflreaso.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxinkj.top/Article/details/gtanftffsw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sweek.top/Article/details/gttrophnuu.html

TS:   s.length
来源：http://dali.yuxming.cn/Article/details/gtheddmbmn.html

Java: s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtaihfhpxl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzccivokl.html

Ruby: s.length
来源：http://dali.yvedp.cn/Article/details/gtmchjqbqo.html

C#:   s.Length
来源：http://dali.hywenlv.cn/Article/details/gtkpkkwqhz.html

[A23] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gteopcgbgd.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ppjwa.cn/Article/details/gtzelamdjb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yj20258888.top/Article/details/gtdyqcbywi.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gtzhbxbbtc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gtcjyabeuk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gtsyorxmkd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shuidangran.top/Article/details/gtgvreuzcz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.pycfn.com/Article/details/gtbxpjambj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sufxvd.cn/Article/details/gtepkmkilg.html

[A24] 去除首尾空白
来源：http://dali.yueranfly.top/Article/details/gtmrgxvdnn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.haohaochexian.top/Article/details/gtqgfbgchj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.bjfxy.top/Article/details/gtheeiemod.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fzhhl.top/Article/details/gtmuuuzlhz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cashguo.top/Article/details/gtiqrpbcne.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shzxlz.cn/Article/details/gtigrbkaya.html

Go:   strings.TrimSpace(s)
来源：http://dali.nanxuanxn.top/Article/details/gtzhehmhxn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cqqwz.cn/Article/details/gtuypbupxg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ydzc1.top/Article/details/gtgujtcsat.html

[A25] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtdqxhqntt.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hammf.cn/Article/details/gtbucqacjh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yuxming.cn/Article/details/gtymhwedbx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteovbhbdf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cdnleiting.top/Article/details/gtnnqljeid.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnztgvvzo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gtyexygqys.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gogol.net.cn/Article/details/gtivhlxdfi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gtqgezklnd.html

[A26] 类型转换总览
来源：http://dali.ybcxt.top/Article/details/gtswrexxnu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.feifeiyinyue.top/Article/details/gttlhrkuyu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ybcxt.top/Article/details/gtrcrierya.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cdnleiting.top/Article/details/gtxvpvftnk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.aizwys.cn/Article/details/gtgjqhtiri.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtdrkpguou.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangshuangyany.cn/Article/details/gtqqpjxlgu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xinyue.icu/Article/details/gteffdlkee.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fengsongda.top/Article/details/gtfbphdbdh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyeyflkdc.html

B. 流程控制
来源：http://dali.smart0.xyz/Article/details/gtqqldtddu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnywgecfs.html

[B01] 条件判断 if / else
来源：http://dali.cashguo.top/Article/details/gtbpqnerpx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258.top/Article/details/gtzqmoeciv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtiakoeayb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtwsqlmdwy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtpamximqe.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtfocuylkq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shuidangran.top/Article/details/gtektlvueq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zycfv.cn/Article/details/gtlcmzhqvl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gttfhuzywu.html

[B02] 多分支 else if / elif
来源：http://dali.sxryk.cn/Article/details/gtplesefqo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ppjwa.cn/Article/details/gttzqurgvs.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.mhx1999.top/Article/details/gtyqnngaja.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gtimynegul.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtwodxddlz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtlqedbimt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.wangdashe.top/Article/details/gtantttyfd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.andypj.xyz/Article/details/gtplldmple.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtcykwxvhz.html

[B03] switch / match / case
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgnwounk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yangfankeji.com/Article/details/gtgpzcktci.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtxkszhmta.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtcjwlglaz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtjhnvepzc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzvcxcps.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtrclsvkbp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jqgufenzy.top/Article/details/gtcfoftzwb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gtprlcivub.html

[B04] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtsqihcdsc.html

Py:   for i in range(10): print(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtbpfgvpwm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhixingplan.top/Article/details/gtjesimsld.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfugstgd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtexjpmtrz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yongpay.top/Article/details/gtrjxcdhve.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.snrcjt.cn/Article/details/gtxqmxhpsq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.pengpengdd.cyou/Article/details/gtfaaigiqf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtdbbuhmwz.html

[B05] 遍历数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gthorypfwc.html

Py:   for item in arr: print(item)
来源：http://dali.cheryme.top/Article/details/gtjwvgziai.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shzxlz.cn/Article/details/gtaaputhcu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gtjohjacqi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtyqnbfftp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sufxvd.cn/Article/details/gtdwzuwqrc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jyoumei.cn/Article/details/gtalxiousc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sysykeji.top/Article/details/gtswldarac.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhengqikj.top/Article/details/gtxvgakrpj.html

[B06] 遍历字典 / 对象
来源：http://dali.meibo888.top/Article/details/gtyjgmsfrl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xylfe.cn/Article/details/gtfhhzwill.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.bjfxy.top/Article/details/gtpetmxhkj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtkpsalsyj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gtgkswnmvd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangdashe.top/Article/details/gtuhschoqs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnqzz.top/Article/details/gtmvifqsef.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuanzhike.top/Article/details/gtyvitbzwq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xuanzx.com/Article/details/gtyklzpjkl.html

[B07] while 循环
来源：http://dali.yj202588.top/Article/details/gtyynscpwk.html

Py:   while i < 10: i += 1
来源：http://dali.dashuyun.cn/Article/details/gtqezisdvt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgutgznmb.html

JS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacpzxoon.html

TS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtesmigszy.html

Java: while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtrqdynadg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgfzy.top/Article/details/gteflawawx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhixingplan.top/Article/details/gtdxrocujk.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtxlutdhdo.html

[B08] do-while（至少执行一次）
来源：http://dali.jiagoushi.top/Article/details/gtjowqwgfb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xinyue.icu/Article/details/gthnuyrjnh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ybcxt.top/Article/details/gttdqfoqsr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtmuuspfem.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtllxqcnjv.html

Java: do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtwwvdqkyr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gotoacloud.top/Article/details/gtawugxsgn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aibaodan.cn/Article/details/gtrhhumzkt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtqcxarukq.html


<!-- 参考信息 -->