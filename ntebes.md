代发 wailian999

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtmajhgbcl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fengsongda.top/Article/details/gtgzsypuwk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtaqtogfuf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtxkqpztef.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqkznyvsc.html

A. 基础语法与类型
来源：http://dali.zhongyouzk.top/Article/details/gtjigptsvj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgtfnacyd.html

[A01] Hello World
来源：http://dali.fengsongda.top/Article/details/gtanndiulg.html

Py:   print("Hello, World!")
来源：http://dali.guowangkeji.top/Article/details/gtzhigiyak.html

PHP:  echo "Hello, World!";
来源：http://dali.hnxiangtu.top/Article/details/gtvnpzknpf.html

JS:   console.log("Hello, World!");
来源：http://dali.yonumen.top/Article/details/gtonbcppuv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sufxvd.cn/Article/details/gtxkaqtnuf.html

Java: System.out.println("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtahdahtly.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pengpengdd.cyou/Article/details/gtylagcscm.html

Ruby: puts "Hello, World!"
来源：http://dali.daxiang520.top/Article/details/gtqhlrloft.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtehqldphz.html

[A02] 变量声明与赋值
来源：http://dali.nanxuanxn.top/Article/details/gtpaghvmnj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nwbrower.top/Article/details/gtlhfgdfxq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yonumen.top/Article/details/gtoiswsvgz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yueranfly.top/Article/details/gtqmwmubdh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jiagoushi.top/Article/details/gtkeiewvjp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtnosoarse.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuxming.cn/Article/details/gtjobjagwa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.guowangkeji.top/Article/details/gtsykeyxju.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtivllpvvd.html

[A03] 常量定义
来源：http://dali.kuanghao11.cn/Article/details/gtoznsbnbo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yangfankeji.com/Article/details/gtotpdbdgb.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtttvhmeaj.html

JS:   const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtukvfrjis.html

TS:   const PI: number = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtdwmlikvy.html

Java: static final double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtjznvlekc.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtimalmzwe.html

Ruby: PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gthbvcoejg.html

C#:   const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtmuvsqwzi.html

[A04] 判断变量类型
来源：http://dali.chenlongwang.top/Article/details/gtwytcbxpb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fengsongda.top/Article/details/gtvmulcvuq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtfetxugmy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gtcrzkcnpu.html

TS:   typeof x; x instanceof Date
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcqiaxvr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gogol.net.cn/Article/details/gtlxdmovwg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hysaishi.cn/Article/details/gthyazjerj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cqqwz.cn/Article/details/gtdmjnzsog.html

C#:   x.GetType().Name; x is int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvptuwony.html

[A05] 整数除法与取模
来源：http://dali.gogol.net.cn/Article/details/gtdubjmuyg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yvedp.cn/Article/details/gtkvdwdqhv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtztpyrpzx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtoypeccgm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtbujwgwoz.html

Java: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtzpzcmben.html

Go:   7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtpydtcsms.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtojmwvjev.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtsodugjpg.html

[A06] 字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtujvxxbuj.html

Py:   int("42"); float("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtjrawbtgu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jyoumei.cn/Article/details/gtejkrbnpu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.mhx1999.top/Article/details/gtzceqsfbr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gtgpfyofae.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtjioqmrwg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.316326.xyz/Article/details/gtbwqlahwn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhixingplan.top/Article/details/gtocsdcudc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yvedp.cn/Article/details/gtcagotdhz.html

[A07] 数字转字符串
来源：http://dali.xinyue.icu/Article/details/gtikhxkzmv.html

Py:   str(42)
来源：http://dali.cashguo.top/Article/details/gthxektkla.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozgcdtsq.html

JS:   String(42); (42).toString()
来源：http://dali.dianchejie.cn/Article/details/gtrfjdqvhq.html

TS:   String(42)
来源：http://dali.jinqigufen.top/Article/details/gtvcnjemoe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dashuyun.cn/Article/details/gtgmsakaee.html

Go:   strconv.Itoa(42)
来源：http://dali.yj20258888.top/Article/details/gthpapsxzr.html

Ruby: 42.to_s
来源：http://dali.xinyue.icu/Article/details/gtvkmxjcqa.html

C#:   42.ToString()
来源：http://dali.jinqigufen.top/Article/details/gtiqzqelum.html

[A08] 取整与四舍五入
来源：http://dali.birdmap.top/Article/details/gtjynjyool.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gttcqdkknz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cashguo.top/Article/details/gtszojzmyy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtqscpfitk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.aibaodan.cn/Article/details/gtpctggniw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtjsddgtxt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gttgdmuznv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwltwpntd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtxwdodrjl.html

[A09] 绝对值与最大最小值
来源：http://dali.hnqzz.top/Article/details/gtrvdkqfdw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlvgecwd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtkqgvgtnm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtjdeiphas.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtiinmgqsb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtohaqqluy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.daria6918.cn/Article/details/gtnfwpemjr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zycfv.cn/Article/details/gtiuvpycjj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtnvdwnzzf.html

[A10] 生成随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxxzqnkx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.0kj1m.cn/Article/details/gtphhhwibn.html

PHP:  random_int(1, 100);
来源：http://dali.nwbrower.top/Article/details/gtkjqhbhgs.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xylfe.cn/Article/details/gtkaxfvqae.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dashuyun.cn/Article/details/gtwxkkbnju.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jianghu66.top/Article/details/gthdvyqbmm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhixingplan.top/Article/details/gtwesdbtzp.html

Ruby: rand(1..100)
来源：http://dali.hammf.cn/Article/details/gtlbmefijj.html

C#:   new Random().Next(1, 101)
来源：http://dali.smart0.xyz/Article/details/gtobbqvejk.html

[A11] 条件表达式（三元）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxjszhus.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.chenzaomai.com/Article/details/gtzsyoevzk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtmhtbrnlb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gtxbvfpkgt.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtgcslpzvb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtibtmipcc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xylfe.cn/Article/details/gtdfohwrhc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtzkgtffhg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtqiwkkdod.html

[A12] 字符串插值 / 格式化
来源：http://dali.ydzc1.top/Article/details/gtajfqhpcm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.snrcjt.cn/Article/details/gteqcggcqo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.smart0.xyz/Article/details/gtaitmwiff.html

JS:   `Hello, ${name}!`
来源：http://dali.zhixingplan.top/Article/details/gttppqnydw.html

TS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gtvmfnwjmq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gtvhirhaue.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nanxinkj.top/Article/details/gtqnfxzjhp.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhoulong.xyz/Article/details/gtnhinqojo.html

C#:   $"Hello, {name}!"
来源：http://dali.gzhubu.top/Article/details/gtagfgeyjv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.0kj1m.cn/Article/details/gtmgxtkdjc.html

Py:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtrcfttgmu.html

PHP:  "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtdbpnaghm.html

JS:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gtsvgjukih.html

TS:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfemnbiru.html

Java: "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtlsbtwfbu.html

Go:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtmuvnnbyi.html

Ruby: "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtvrewxluj.html

C#:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtqdqnoujs.html

[A14] 注释写法
来源：http://dali.jinghuilouyu.cn/Article/details/gtfphzhmis.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cdnleiting.top/Article/details/gtxyblihbj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtjobezaou.html

JS:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gtzfhadmuc.html

TS:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtzfpikfmk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yongpay.top/Article/details/gtvuaivlru.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtmmptyyjx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnynhqsr.html

C#:   // 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gtfmordxjt.html

[A15] 空值判断与默认值
来源：http://dali.c1oappe.top/Article/details/gtqsfsansw.html

Py:   value = data or "默认值"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshsfsout.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gtjhclreni.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gtazrbcdrq.html

TS:   const value = data ?? "默认值";
来源：http://dali.sxryk.cn/Article/details/gthqyvwemk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pengpengdd.cyou/Article/details/gtzwnzviaf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shangyingyoupin.top/Article/details/gtgjddactt.html

Ruby: value = data || "默认值"
来源：http://dali.gzhubu.top/Article/details/gtxrttdygh.html

C#:   var value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gtwloaoghm.html

[A16] 真假值判断规则
来源：http://dali.hongshengwenyu.top/Article/details/gtezamixvx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ydzc1.top/Article/details/gtutzkeymt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ppjwa.cn/Article/details/gtxasdkxoq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gogol.net.cn/Article/details/gtdfwlzrsr.html

TS:   if (!x) {}
来源：http://dali.yj202588.top/Article/details/gtwewrdhxv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbsfhbnmx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yvedp.cn/Article/details/gtnskguolo.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.guowangkeji.top/Article/details/gtkrubcipm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.redwolf501.top/Article/details/gtbihxcfbo.html

[A17] 位运算
来源：http://dali.nanxuanxn.top/Article/details/gtighwzecf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtrfdnwqxa.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.meibo888.top/Article/details/gtbudwvxvk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtgwkliqoc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtjnttlxbo.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtruodhitf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtfhrjlhdl.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtgnfnseec.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtqgqfbtpt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhoulong.xyz/Article/details/gtowbozvoz.html

Py:   ord("A"); chr(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtvhyjirph.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gtebsnnusc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hfpthk.cn/Article/details/gthrltajmj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbvwezuv.html

Java: (int) 'A'; (char) 65
来源：http://dali.hfpthk.cn/Article/details/gtjpzpltnc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.vqdsnc.cn/Article/details/gtgqbsedbc.html

Ruby: "A".ord; 65.chr
来源：http://dali.wangshuangyany.cn/Article/details/gtnjnuzlkn.html

C#:   (int)'A'; (char)65
来源：http://dali.pengpengdd.cyou/Article/details/gtxthdznyi.html

[A19] 交换两个变量
来源：http://dali.zhoulong.xyz/Article/details/gtxwygodcb.html

Py:   a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gtbscdsdnz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.vqdsnc.cn/Article/details/gtvqndzfdv.html

JS:   [a, b] = [b, a];
来源：http://dali.yongpay.top/Article/details/gtmiehwolj.html

TS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpjojabl.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhongyouzk.top/Article/details/gtkyhvbsdk.html

Go:   a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gtdzosqylg.html

Ruby: a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gtxoxiuaem.html

C#:   (a, b) = (b, a);
来源：http://dali.ivvv.top/Article/details/gtigmwvizr.html

[A20] 读取标准输入
来源：http://dali.yj20258888.top/Article/details/gtvobjqdno.html

Py:   name = input("请输入：")
来源：http://dali.daria6918.cn/Article/details/gtmrftczrn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.feifeiyinyue.top/Article/details/gtrncjxkht.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangtech.top/Article/details/gthedpcusj.html

TS:   // Node.js：readline 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeumistg.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfhnjbsh.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ybcxt.top/Article/details/gtgmvulpum.html

Ruby: gets.chomp
来源：http://dali.tian-w.cn/Article/details/gtbtqcitve.html

C#:   Console.ReadLine();
来源：http://dali.ydzc1.top/Article/details/gtbriohrdh.html

[A21] 保留指定小数位输出
来源：http://dali.guannengcc.top/Article/details/gtxxijwgaz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tian-w.cn/Article/details/gtybxhavuo.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtmmyssluk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtpytrxvtj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtovawvjdi.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtivrxnlnb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtnqwhxqyw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gtofiatill.html

C#:   3.14159.ToString("F2")
来源：http://dali.redwolf501.top/Article/details/gtvpmvbvbz.html

[A22] 获取字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtdukewaqh.html

Py:   len(s)
来源：http://dali.yangfankeji.com/Article/details/gtmejwzgzg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.c1oappe.top/Article/details/gtftnydmmd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhoulong.xyz/Article/details/gtdadsiozt.html

TS:   s.length
来源：http://dali.daria6918.cn/Article/details/gtlmokwqim.html

Java: s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtbnwebwnw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jyoumei.cn/Article/details/gtceqhjbtj.html

Ruby: s.length
来源：http://dali.jlsjyb.cn/Article/details/gtaqouflbg.html

C#:   s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtlpqjcgpa.html

[A23] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtzlwsbczj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gzhubu.top/Article/details/gtiftqpyph.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aibaodan.cn/Article/details/gtvqmedpzp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gtbbzkkrzr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gtpmkwewyt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xinyue.icu/Article/details/gtepibzjew.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.meibo888.top/Article/details/gtarsvpgil.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtaewifbkr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.9152youxi.cn/Article/details/gtjrbwgghh.html

[A24] 去除首尾空白
来源：http://dali.ybcxt.top/Article/details/gteprodrms.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yongpay.top/Article/details/gtjpivnfiv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cheryme.top/Article/details/gtwplbxhjj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xziqi.cn/Article/details/gtprejdpwl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhengqikj.top/Article/details/gtyjjhewgo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gogol.net.cn/Article/details/gtslrwidhg.html

Go:   strings.TrimSpace(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxjpjots.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yonumen.top/Article/details/gtgloddvtb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmjuszoo.html

[A25] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtkyqsbihg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.wangshuangyany.cn/Article/details/gtdhtorcml.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zdqjudy.top/Article/details/gtrwjlcbcc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gttstbrkvl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gtjaaxekvo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvreivok.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ydzc1.top/Article/details/gtukujysoz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cucudq.cn/Article/details/gtabengmiz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gtxommhnbs.html

[A26] 类型转换总览
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibnteztx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pycfn.com/Article/details/gtucoroilx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.9152youxi.cn/Article/details/gtvrupfswy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.9152youxi.cn/Article/details/gtxrysylqp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhiwuduotai.top/Article/details/gtjkznytiz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gtvyailzot.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shzxlz.cn/Article/details/gtyarvsdeo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yuxming.cn/Article/details/gthupwdxej.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gtgujmbpom.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojrjlsxu.html

B. 流程控制
来源：http://dali.fzhhl.top/Article/details/gthwmhshuu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvcwwabjv.html

[B01] 条件判断 if / else
来源：http://dali.ivvv.top/Article/details/gtzboecrko.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnxiangtu.top/Article/details/gtsvfpdwjg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.9152youxi.cn/Article/details/gtinaymwrv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gtokwxotge.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gtgrxlibza.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtnlowmjmp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.vqdsnc.cn/Article/details/gtvxdvbnxh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigfzy.top/Article/details/gtcschpzrz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gtxrbutgwy.html

[B02] 多分支 else if / elif
来源：http://dali.0kj1m.cn/Article/details/gtwyslnjra.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gogol.net.cn/Article/details/gtxvdwfaln.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shuidangran.top/Article/details/gtqnxqketk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gthbmephqj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtijqhlplj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gtyxweylsd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shzxlz.cn/Article/details/gtfleebktw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.bjfxy.top/Article/details/gtbzznszvv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtohuzmuaq.html

[B03] switch / match / case
来源：http://dali.ehwqpu.com/Article/details/gtbjofccsz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhixingplan.top/Article/details/gtzumldysa.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtxdsbeyzg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtzpdebbue.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtdrgzcnve.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtjnuctudl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ivvv.top/Article/details/gtswqxkmtz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhongyouzk.top/Article/details/gtrzwmaasp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtrncplrmh.html

[B04] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtroxnlpdm.html

Py:   for i in range(10): print(i)
来源：http://dali.zycfv.cn/Article/details/gtxrzblphh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sufxvd.cn/Article/details/gtehfmgrzy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gzhubu.top/Article/details/gtmdjsfmzy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yangfankeji.com/Article/details/gtpbiyvook.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.daxiang520.top/Article/details/gthcufwpas.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.meibo888.top/Article/details/gtrecxyjxh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hysaishi.cn/Article/details/gtubnpylwh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtlxnasyjf.html

[B05] 遍历数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtqqdkgyav.html

Py:   for item in arr: print(item)
来源：http://dali.dashuyun.cn/Article/details/gthbccihyx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.aizwys.cn/Article/details/gtvewprtdn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sweek.top/Article/details/gtkjxuftcq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtwcxhonrw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tian-w.cn/Article/details/gtzgbodlax.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shangyingyoupin.top/Article/details/gtrrqwdmoc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gtxxzjudzl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gthbbyxzqo.html

[B06] 遍历字典 / 对象
来源：http://dali.9152youxi.cn/Article/details/gtimbapstl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.haohaochexian.top/Article/details/gtemoxqxwa.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.9152youxi.cn/Article/details/gtcswolsgu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gtgrfpofrc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gtcaeocvpp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.bjfxy.top/Article/details/gtzjsnhtmg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zdqjudy.top/Article/details/gtujapigoh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258.top/Article/details/gteymnrvhn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.redwolf501.top/Article/details/gtxboqrhcg.html

[B07] while 循环
来源：http://dali.yuxming.cn/Article/details/gtzdycgdjn.html

Py:   while i < 10: i += 1
来源：http://dali.jqgfzy.top/Article/details/gtthzugpoi.html


<!-- 参考信息 -->