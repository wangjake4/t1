代发 wailian999

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedrkjmek.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hammf.cn/Article/details/gtbbmnampm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtpfvigjdh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gtfgftsrxi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtsvbzoiwh.html

A. 基础语法与类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjhrpxus.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtccytihxt.html

[A01] Hello World
来源：http://dali.smart0.xyz/Article/details/gtooaeqesu.html

Py:   print("Hello, World!")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnpgptfg.html

PHP:  echo "Hello, World!";
来源：http://dali.gaohongyu789.top/Article/details/gtdkvgurqe.html

JS:   console.log("Hello, World!");
来源：http://dali.cdnleiting.top/Article/details/gthurldrxz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.kuanghao11.cn/Article/details/gtmitkwjlc.html

Java: System.out.println("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtrvlsapsx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenlongwang.top/Article/details/gtylzbkjcz.html

Ruby: puts "Hello, World!"
来源：http://dali.shzxlz.cn/Article/details/gtjfypjouc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtuatspbko.html

[A02] 变量声明与赋值
来源：http://dali.hnqzz.top/Article/details/gtsfmopxmo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.quarkkingdee.top/Article/details/gtwvemolbw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tian-w.cn/Article/details/gtmlbmazpm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.iojbl.cn/Article/details/gtpwwvilam.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.mhx1999.top/Article/details/gtlqjrtduv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gthkqeylip.html

Go:   name := "Alex"; age := 20
来源：http://dali.tanke756.top/Article/details/gtytsoqhmu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dianchejie.cn/Article/details/gtywhgcluz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtkjwvqayb.html

[A03] 常量定义
来源：http://dali.jinqigufen.top/Article/details/gtgfubsazm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xinyue.icu/Article/details/gtzccrygor.html

PHP:  const PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtuoxypuvk.html

JS:   const PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtrksvotes.html

TS:   const PI: number = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtcybniums.html

Java: static final double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtajtvqdbm.html

Go:   const PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtnevtyynr.html

Ruby: PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gtypwfduvh.html

C#:   const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtuhjkdjhs.html

[A04] 判断变量类型
来源：http://dali.birdmap.top/Article/details/gtwnjjqjyf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hysaishi.cn/Article/details/gtbqhmhdjd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigfzy.top/Article/details/gtcixaasrd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.0kj1m.cn/Article/details/gtchfnuqeq.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhengqikj.top/Article/details/gttfyucbka.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhoulong.xyz/Article/details/gtksycdwyd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yvedp.cn/Article/details/gtcjjwinqf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.birdmap.top/Article/details/gtmuzuuwab.html

C#:   x.GetType().Name; x is int
来源：http://dali.sysykeji.top/Article/details/gtrjprjdkj.html

[A05] 整数除法与取模
来源：http://dali.redwolf501.top/Article/details/gtbojowswa.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgfzy.top/Article/details/gtlcxaqyib.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtsnlgheqr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtwdzcomow.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtdbbbvhkn.html

Java: 7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtnbjwqbdq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtvifyptju.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtbkujalfj.html

C#:   7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtizuohnrx.html

[A06] 字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtswdmtqcq.html

Py:   int("42"); float("3.14")
来源：http://dali.hnqzz.top/Article/details/gtdajnyurt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hfpthk.cn/Article/details/gtgrzfczqk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtlkxgqgzx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sysykeji.top/Article/details/gtddexolul.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gtckdmfhsr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj202588.top/Article/details/gtvxjvjyec.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cdnleiting.top/Article/details/gtewifsnfq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yonumen.top/Article/details/gtbvafygsc.html

[A07] 数字转字符串
来源：http://dali.jqgfzy.top/Article/details/gtzogknaoh.html

Py:   str(42)
来源：http://dali.hnxiangtu.top/Article/details/gtxeelakkv.html

PHP:  (string) 42; strval(42)
来源：http://dali.dashuyun.cn/Article/details/gtouxtybcz.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gtycxozivp.html

TS:   String(42)
来源：http://dali.hammf.cn/Article/details/gtfqzzpsdo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.bjfxy.top/Article/details/gtulaqzhsw.html

Go:   strconv.Itoa(42)
来源：http://dali.tanke756.top/Article/details/gtsgxmzzwa.html

Ruby: 42.to_s
来源：http://dali.yvedp.cn/Article/details/gtpbhmvilv.html

C#:   42.ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwrqdlur.html

[A08] 取整与四舍五入
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtqlmyhf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gtdznaeebt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yvedp.cn/Article/details/gtuwgxvknn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtfpeagrlb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenzaomai.com/Article/details/gtraiciwoz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtrzyqgwsp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gturwwenhb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj20258888.top/Article/details/gtssrujagi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gtswdneuit.html

[A09] 绝对值与最大最小值
来源：http://dali.sufxvd.cn/Article/details/gtzhqkytsy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.havefunace.top/Article/details/gtjxyhzqmf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtvyexnhsq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtwkweqydf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtdwhkszxu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtmfepcbwg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.mhx1999.top/Article/details/gthozftkui.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.aibaodan.cn/Article/details/gtqvplwynx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonwxmnlq.html

[A10] 生成随机数
来源：http://dali.ydzc1.top/Article/details/gttkttusvf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.guannengcc.top/Article/details/gtwmusmzcw.html

PHP:  random_int(1, 100);
来源：http://dali.yvedp.cn/Article/details/gtughrzqsp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigufen.top/Article/details/gtqvnlffwf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hywenlv.cn/Article/details/gtpysjmgnt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gotoacloud.top/Article/details/gttorwbsyz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pengpengdd.cyou/Article/details/gtbnsljitu.html

Ruby: rand(1..100)
来源：http://dali.zycfv.cn/Article/details/gtlfurucfa.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinqigufen.top/Article/details/gtvliqunua.html

[A11] 条件表达式（三元）
来源：http://dali.daxiang520.top/Article/details/gtjswecubw.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinqigfzy.top/Article/details/gtibvrsdgx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtrppghwbv.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoihmakln.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtblzgtnzi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtpnjshnrs.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.andypj.xyz/Article/details/gtudxtlwtn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtvsxudqpg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtgzkmdtvs.html

[A12] 字符串插值 / 格式化
来源：http://dali.sxryk.cn/Article/details/gtbcrljzvm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hammf.cn/Article/details/gtrnxvwakb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvugwwcb.html

JS:   `Hello, ${name}!`
来源：http://dali.zhoulong.xyz/Article/details/gtzzkpfljk.html

TS:   `Hello, ${name}!`
来源：http://dali.xziqi.cn/Article/details/gtauazojpo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtcipsrdkb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zdqjudy.top/Article/details/gtkpapfqqe.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhengqikj.top/Article/details/gtarawyaht.html

C#:   $"Hello, {name}!"
来源：http://dali.gotoacloud.top/Article/details/gtmjlnpwpz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhoulong.xyz/Article/details/gtytvtlkmu.html

Py:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gttdkjyihi.html

PHP:  "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtxpltqmuf.html

JS:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtnwfjzsnx.html

TS:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtzhqdufhm.html

Java: "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtieobcskz.html

Go:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtybtplrbn.html

Ruby: "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtacyxdorj.html

C#:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtenlotwdg.html

[A14] 注释写法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubqomwce.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.tanke756.top/Article/details/gtnahcovrf.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gttehkoprk.html

JS:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtrdagjljh.html

TS:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gtbicsrvit.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gzhubu.top/Article/details/gtcuqnishq.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gtrdgzdjwf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jianghu66.top/Article/details/gtzkonwybi.html

C#:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtgxsynhws.html

[A15] 空值判断与默认值
来源：http://dali.chenzaomai.com/Article/details/gtgmuuifsf.html

Py:   value = data or "默认值"
来源：http://dali.yj20258888.top/Article/details/gthjnkifhv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtdaqidjjy.html

JS:   const value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gtlwgekljg.html

TS:   const value = data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gtsouvzsxt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.iojbl.cn/Article/details/gtqfceugyg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj20258.top/Article/details/gthhzwvxfv.html

Ruby: value = data || "默认值"
来源：http://dali.smart0.xyz/Article/details/gtrmtlfryq.html

C#:   var value = data ?? "默认值";
来源：http://dali.yj202588.top/Article/details/gtsdlluumr.html

[A16] 真假值判断规则
来源：http://dali.yongpay.top/Article/details/gttrbdqjll.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cheryme.top/Article/details/gtxlfiobdn.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xuanzx.com/Article/details/gtuzahsttj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.dashuyun.cn/Article/details/gtxilpuqer.html

TS:   if (!x) {}
来源：http://dali.bjfxy.top/Article/details/gtnndyivtl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.sxryk.cn/Article/details/gtggwhxzae.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zdqjudy.top/Article/details/gtpxqhzbbw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhoulong.xyz/Article/details/gtvgetctpl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnxprqhyn.html

[A17] 位运算
来源：http://dali.xziqi.cn/Article/details/gtmfuooetj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtsmrydhzc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.andypj.xyz/Article/details/gtkomgcvxc.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtymprgyjp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtacojkzhm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtkaynaosj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtkrccqnma.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtbxoilbty.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtorqnqdpi.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xziqi.cn/Article/details/gtpctddzlu.html

Py:   ord("A"); chr(65)
来源：http://dali.jiagoushi.top/Article/details/gtdghlhhpq.html

PHP:  ord("A"); chr(65)
来源：http://dali.hywenlv.cn/Article/details/gtwwdnzuge.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.bjfxy.top/Article/details/gtlqtwopaq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwarjivgv.html

Java: (int) 'A'; (char) 65
来源：http://dali.vqdsnc.cn/Article/details/gtcngczxnh.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhixingplan.top/Article/details/gtxetgwqgz.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhoulong.xyz/Article/details/gtgszdtqgh.html

C#:   (int)'A'; (char)65
来源：http://dali.ybcxt.top/Article/details/gtggjnorjj.html

[A19] 交换两个变量
来源：http://dali.cqqwz.cn/Article/details/gtzqgybmio.html

Py:   a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gtqacjacky.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gzhubu.top/Article/details/gttimcnnba.html

JS:   [a, b] = [b, a];
来源：http://dali.xuetiantiany.cn/Article/details/gtjkpezksd.html

TS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gtxbgbziod.html

Java: int t = a; a = b; b = t;
来源：http://dali.yueranfly.top/Article/details/gtwojyvfhi.html

Go:   a, b = b, a
来源：http://dali.gotoacloud.top/Article/details/gtfaflhbnx.html

Ruby: a, b = b, a
来源：http://dali.316326.xyz/Article/details/gtzwjemlpq.html

C#:   (a, b) = (b, a);
来源：http://dali.aibaodan.cn/Article/details/gtehnsjxih.html

[A20] 读取标准输入
来源：http://dali.ydzc1.top/Article/details/gtaghnhdgt.html

Py:   name = input("请输入：")
来源：http://dali.andypj.xyz/Article/details/gthzbfipnv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hywenlv.cn/Article/details/gtdeytstzs.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cheryme.top/Article/details/gtapwefeyq.html

TS:   // Node.js：readline 模块
来源：http://dali.yj20258.top/Article/details/gtjoodviqe.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shuidangran.top/Article/details/gtfmxwqquo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.fzhhl.top/Article/details/gtanqmkonh.html

Ruby: gets.chomp
来源：http://dali.zhijiandao.cn/Article/details/gtobpbmadl.html

C#:   Console.ReadLine();
来源：http://dali.feifeiyinyue.top/Article/details/gtuwkfvyon.html

[A21] 保留指定小数位输出
来源：http://dali.iojbl.cn/Article/details/gtcjawgveb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jyoumei.cn/Article/details/gtqffeuyqy.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtmgbwmpxj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtzlgsedbe.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gttsovuaqm.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtlfaruqwt.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtbyugjgil.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gtdqbczvex.html

C#:   3.14159.ToString("F2")
来源：http://dali.gaohongyu789.top/Article/details/gtwiudcuul.html

[A22] 获取字符串长度
来源：http://dali.hammf.cn/Article/details/gttbemmohn.html

Py:   len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtrvdnfgmh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.aizwys.cn/Article/details/gtpgrlygej.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.haohaochexian.top/Article/details/gtysqxifbs.html

TS:   s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajlsigpj.html

Java: s.length()
来源：http://dali.ivvv.top/Article/details/gtattxjumv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yongpay.top/Article/details/gtcwlqtzgw.html

Ruby: s.length
来源：http://dali.iojbl.cn/Article/details/gtquzpihbf.html

C#:   s.Length
来源：http://dali.yj20258.top/Article/details/gtocvfbqmz.html

[A23] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gthyrasisz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yonumen.top/Article/details/gtcbrxwnoz.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.kuanghao11.cn/Article/details/gtbnjhwqsn.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigufen.top/Article/details/gtykvwkalk.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtosviveot.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtnddenqqx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daria6918.cn/Article/details/gtaevbghmz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtfvjpewzu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xinyue.icu/Article/details/gtonlyzcxf.html

[A24] 去除首尾空白
来源：http://dali.shzxlz.cn/Article/details/gtdlprpotw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.andypj.xyz/Article/details/gtvwclqath.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenzaomai.com/Article/details/gtcexngepc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gtyukrdapr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtkzwzgdbu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.vqdsnc.cn/Article/details/gtyzcqnwfi.html

Go:   strings.TrimSpace(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtcltlkfwi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.haohaochexian.top/Article/details/gthzxbosen.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yongpay.top/Article/details/gtswvxgawy.html

[A25] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtxotkeptm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcsofqot.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteginfset.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnqzz.top/Article/details/gtlphnnelg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fzhhl.top/Article/details/gtvvgwpdwc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gzhubu.top/Article/details/gtxjldbdfu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xylfe.cn/Article/details/gtdttbwchi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jqgfzy.top/Article/details/gtlewymvhc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gaohongyu789.top/Article/details/gtidzatoem.html

[A26] 类型转换总览
来源：http://dali.yongpay.top/Article/details/gtnqiinusl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.iojbl.cn/Article/details/gtmumfgxig.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hammf.cn/Article/details/gtnaihpvud.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclpyxzzq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hywenlv.cn/Article/details/gtuwxmxowt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhengqikj.top/Article/details/gtgkgudwfh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.vqdsnc.cn/Article/details/gttbgsrrtd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gzhubu.top/Article/details/gtiuqgeeyw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoslkdcdh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrhdclatf.html

B. 流程控制
来源：http://dali.jinqigfzy.top/Article/details/gtnepzntfc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwhmsmort.html

[B01] 条件判断 if / else
来源：http://dali.zhoulong.xyz/Article/details/gttrlruptq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hfpthk.cn/Article/details/gtqnrcaqcc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkdesqip.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtyrscpjht.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gthllkxlvs.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtpzqytnnl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gtobvlsayo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ydzc1.top/Article/details/gthfoyfnry.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gtpjazyevg.html

[B02] 多分支 else if / elif
来源：http://dali.redwolf501.top/Article/details/gtonylkqoj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jiagoushi.top/Article/details/gtjacwgymn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xziqi.cn/Article/details/gtgvcfcwjq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gtcnyqqlxn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtsfhqooil.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtekokqxcv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.chenlongwang.top/Article/details/gtdtphnzhz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tanke756.top/Article/details/gtfojcclkg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtbzophazq.html

[B03] switch / match / case
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamfiqixj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.havefunace.top/Article/details/gtnbljlvzp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtkxgdcxuu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtndweehpf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjdnbcrft.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gtcpevtten.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xziqi.cn/Article/details/gtxharfxom.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.iojbl.cn/Article/details/gtpsahezlj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gtjrepkwaw.html

[B04] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gthvxgpacw.html

Py:   for i in range(10): print(i)
来源：http://dali.fengsongda.top/Article/details/gtryblnnpr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cheryme.top/Article/details/gtlrkxsuwi.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pycfn.com/Article/details/gtmgtarsrd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gttvglcoxc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.smart0.xyz/Article/details/gtewyjueiv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.316326.xyz/Article/details/gtzxkxncti.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gaohongyu789.top/Article/details/gtgxaqnphb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gzhubu.top/Article/details/gtkyqcujcc.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtxfztguez.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gtkunsyvsa.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sysykeji.top/Article/details/gtjcobqcfv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gtklcahyje.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tian-w.cn/Article/details/gtbtdwpydo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.haohaochexian.top/Article/details/gtrxyfsyou.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tian-w.cn/Article/details/gtstbjlgai.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tanke756.top/Article/details/gtmnyskujp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj20258.top/Article/details/gtgkcyxyde.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gtupqnjbws.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.smart0.xyz/Article/details/gtjfeedjta.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hysaishi.cn/Article/details/gttrbfanor.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtizrcrhmp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gtwtbvxbsh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tian-w.cn/Article/details/gtxdixdrvd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcygfrqhp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.quarkkingdee.top/Article/details/gtevgyyrdf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpkuwuco.html

[B07] while 循环
来源：http://dali.yj20258888.top/Article/details/gtniyfxdpi.html

Py:   while i < 10: i += 1
来源：http://dali.jyoumei.cn/Article/details/gtzjmjvhxx.html


<!-- 参考信息 -->