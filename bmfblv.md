代发 wailian999

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guannengcc.top/Article/details/gt2gdvzdyac.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfgvdunw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2inrnlagu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkfqskra.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2wgaxrwdg.html

A. 基础语法与类型
来源：http://dali.hammf.cn/Article/details/gt2mknkzxlk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2otimzqrr.html

[A01] Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2hxrqvnkp.html

Py:   print("Hello, World!")
来源：http://dali.hywenlv.cn/Article/details/gt2btnhtjra.html

PHP:  echo "Hello, World!";
来源：http://dali.yonumen.top/Article/details/gt2hiqktczr.html

JS:   console.log("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gt2askggiuz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sxryk.cn/Article/details/gt2nuwlmjft.html

Java: System.out.println("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gt2proiiahc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gt2gwgdbeto.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gt2uvccmyyg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gt2lfaterkg.html

[A02] 变量声明与赋值
来源：http://dali.hammf.cn/Article/details/gt2vtslzrvk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.0kj1m.cn/Article/details/gt2tnqrplsu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zycfv.cn/Article/details/gt2extkbtlj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gt2gkfjmdgh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinqigufen.top/Article/details/gt2xlsuaytt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dianchejie.cn/Article/details/gt2zwtbkqna.html

Go:   name := "Alex"; age := 20
来源：http://dali.svipenyu.cn/Article/details/gt2whoujppc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozrpxtrj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gt2xydjfddz.html

[A03] 常量定义
来源：http://dali.gotoacloud.top/Article/details/gt2jmqutlmw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dianchejie.cn/Article/details/gt2hidzexhl.html

PHP:  const PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2wepecqlp.html

JS:   const PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhfqjcdd.html

TS:   const PI: number = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2akcwkpwn.html

Java: static final double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2bvwjdrcd.html

Go:   const PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gt2iklrnimv.html

Ruby: PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gt2oibqjrbr.html

C#:   const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2gcjvexga.html

[A04] 判断变量类型
来源：http://dali.ybcxt.top/Article/details/gt2nxswjdaw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xziqi.cn/Article/details/gt2swvyzxrn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsnhxyaz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jiagoushi.top/Article/details/gt2altondsa.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gt2opysqjhr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xziqi.cn/Article/details/gt2xgfcdvxw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.birdmap.top/Article/details/gt2uzbbowlk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhongyouzk.top/Article/details/gt2gnmosfoy.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ijinwgxh.html

[A05] 整数除法与取模
来源：http://dali.hywenlv.cn/Article/details/gt2fpgnogsy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gt2xuiezphy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2stmlcrma.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gt2pfypzmct.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2pkkqlbzg.html

Java: 7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gt2nkqfrzih.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2pumqxfcm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gt2dpfebyjc.html

C#:   7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2hpuhygcb.html

[A06] 字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gt2vuphhbgp.html

Py:   int("42"); float("3.14")
来源：http://dali.havefunace.top/Article/details/gt2prudetih.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hammf.cn/Article/details/gt2wdevvyda.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gt2gpqgctcb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jiagoushi.top/Article/details/gt2dbtihiwa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sxryk.cn/Article/details/gt2hbiqxoum.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shzxlz.cn/Article/details/gt2eualvlxq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.andypj.xyz/Article/details/gt2tnezhtfd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuanzx.com/Article/details/gt2fpnhasci.html

[A07] 数字转字符串
来源：http://dali.daria6918.cn/Article/details/gt2xjxpjrno.html

Py:   str(42)
来源：http://dali.shuidangran.top/Article/details/gt2ptbbjtjr.html

PHP:  (string) 42; strval(42)
来源：http://dali.hongshengwenyu.top/Article/details/gt2trsozfzx.html

JS:   String(42); (42).toString()
来源：http://dali.yj20258888.top/Article/details/gt2nxbtkqmf.html

TS:   String(42)
来源：http://dali.smart0.xyz/Article/details/gt2sduuuxhx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yangfankeji.com/Article/details/gt2lxgbduuc.html

Go:   strconv.Itoa(42)
来源：http://dali.xylfe.cn/Article/details/gt2ajdmqsca.html

Ruby: 42.to_s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tycwuzey.html

C#:   42.ToString()
来源：http://dali.ybcxt.top/Article/details/gt2becypork.html

[A08] 取整与四舍五入
来源：http://dali.xuanzx.com/Article/details/gt2jxzpsmzl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srzjfzlz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.wangdashe.top/Article/details/gt2siyjvcxo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gt2ipvklbrg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hnqzz.top/Article/details/gt2tkjrptkd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yonumen.top/Article/details/gt2afevcsfr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cashguo.top/Article/details/gt2resojesn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsefynux.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gt2enmtgzhl.html

[A09] 绝对值与最大最小值
来源：http://dali.hammf.cn/Article/details/gt2novtgqoy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gt2fvqkbmhy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2jotnxfpx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2qaoyafnc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2ufphkbro.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phnxzuiu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhiwuduotai.top/Article/details/gt2grhnulaj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.nanxinkj.top/Article/details/gt2ofncgbhx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqijmvyl.html

[A10] 生成随机数
来源：http://dali.feifeiyinyue.top/Article/details/gt2pteyilcm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jianghu66.top/Article/details/gt2gzyyvorc.html

PHP:  random_int(1, 100);
来源：http://dali.svipenyu.cn/Article/details/gt2fimvrstm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenlongwang.top/Article/details/gt2yitfnscp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtowbrig.html

Java: new Random().nextInt(100) + 1
来源：http://dali.andypj.xyz/Article/details/gt2tfqdpqmo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.bjfxy.top/Article/details/gt2azwirtbi.html

Ruby: rand(1..100)
来源：http://dali.yonumen.top/Article/details/gt2bpdiayww.html

C#:   new Random().Next(1, 101)
来源：http://dali.jyoumei.cn/Article/details/gt2ytfdonbc.html

[A11] 条件表达式（三元）
来源：http://dali.shzxlz.cn/Article/details/gt2hrhzgldh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yj20258888.top/Article/details/gt2ipqadzhu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmgrrcjk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgiayltv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gt2tgcssvdw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gt2thowkyla.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.316326.xyz/Article/details/gt2pxyvlope.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2svtzwecd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gt2ptlrpzck.html

[A12] 字符串插值 / 格式化
来源：http://dali.nanxinkj.top/Article/details/gt2eawhgsek.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yangfankeji.com/Article/details/gt2qglgqblw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnubywv.html

JS:   `Hello, ${name}!`
来源：http://dali.vqdsnc.cn/Article/details/gt2tssaqljv.html

TS:   `Hello, ${name}!`
来源：http://dali.meibo888.top/Article/details/gt2nlxldiev.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.dashuyun.cn/Article/details/gt2alckxaop.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.smart0.xyz/Article/details/gt2eentqjwr.html

Ruby: "Hello, #{name}!"
来源：http://dali.gaohongyu789.top/Article/details/gt2lczpceib.html

C#:   $"Hello, {name}!"
来源：http://dali.yanxiufei.cn/Article/details/gt2fmcehllc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gzhubu.top/Article/details/gt2fvstufqy.html

Py:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gt2gsorquzi.html

PHP:  "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gt2krfcbwnw.html

JS:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gt2fpzcssmj.html

TS:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gt2ogkkmexj.html

Java: "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mptyltjt.html

Go:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gt2txwgkfgc.html

Ruby: "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrgadtux.html

C#:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2jcnpjnbn.html

[A14] 注释写法
来源：http://dali.dashuyun.cn/Article/details/gt2zkoxucmc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jasgvqhx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2lvaxhvqg.html

JS:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gt2butkuyna.html

TS:   // 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gt2jmhbnwgw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gzhubu.top/Article/details/gt2nnjosxnx.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubcjnsol.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yvedp.cn/Article/details/gt2ppfixvzu.html

C#:   // 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gt2cdnljvdj.html

[A15] 空值判断与默认值
来源：http://dali.havefunace.top/Article/details/gt2jjfmdevd.html

Py:   value = data or "默认值"
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqmxgrsk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gt2qoydjybr.html

JS:   const value = data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gt2rgutjgmv.html

TS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gt2hnhvvjea.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tianlin.xyz/Article/details/gt2snaeucvh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pbimcerw.html

Ruby: value = data || "默认值"
来源：http://dali.hfpthk.cn/Article/details/gt2pdvhwaes.html

C#:   var value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gt2gxbopaya.html

[A16] 真假值判断规则
来源：http://dali.chenlongwang.top/Article/details/gt2zrvuiiwx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.daria6918.cn/Article/details/gt2lklefzuq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hfpthk.cn/Article/details/gt2dstrqdfo.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shzxlz.cn/Article/details/gt2wwpwbhef.html

TS:   if (!x) {}
来源：http://dali.cdnleiting.top/Article/details/gt2zpjrgpld.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2bvcuxdih.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jqgufenzy.top/Article/details/gt2splwkeyf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.birdmap.top/Article/details/gt2zfporkcl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.fzhhl.top/Article/details/gt2zrvpqbks.html

[A17] 位运算
来源：http://dali.sysykeji.top/Article/details/gt2tkpvsbpd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gt2txvocuye.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yj20258.top/Article/details/gt2kgzqhnhk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gt2dpmexadq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxyswcya.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gt2awvnzlty.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2krpursuv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gt2juaejtem.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gt2xvlamdvn.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yvedp.cn/Article/details/gt2uptymgyr.html

Py:   ord("A"); chr(65)
来源：http://dali.xylfe.cn/Article/details/gt2nflbnizs.html

PHP:  ord("A"); chr(65)
来源：http://dali.xuanzx.com/Article/details/gt2wqkbtccc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jlsjyb.cn/Article/details/gt2rmvvyxfs.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fzhhl.top/Article/details/gt2ahdoiaxc.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj20258.top/Article/details/gt2licufslf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gzhubu.top/Article/details/gt2xikmyfqr.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhengqikj.top/Article/details/gt2knwtnqia.html

C#:   (int)'A'; (char)65
来源：http://dali.wangdashe.top/Article/details/gt2myjivrhb.html

[A19] 交换两个变量
来源：http://dali.smart0.xyz/Article/details/gt2kibisjht.html

Py:   a, b = b, a
来源：http://dali.sysykeji.top/Article/details/gt2ctyujpss.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cucudq.cn/Article/details/gt2dvavfoih.html

JS:   [a, b] = [b, a];
来源：http://dali.yueranfly.top/Article/details/gt2ssoqaugr.html

TS:   [a, b] = [b, a];
来源：http://dali.birdmap.top/Article/details/gt2savulixa.html

Java: int t = a; a = b; b = t;
来源：http://dali.yonumen.top/Article/details/gt2bmwvkpaf.html

Go:   a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gt2vdivxlvt.html

Ruby: a, b = b, a
来源：http://dali.shangyingyoupin.top/Article/details/gt2runuamia.html

C#:   (a, b) = (b, a);
来源：http://dali.meibo888.top/Article/details/gt2pszkyulo.html

[A20] 读取标准输入
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqqrcwcg.html

Py:   name = input("请输入：")
来源：http://dali.fzhhl.top/Article/details/gt2undhifvn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxemdudu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.nanxuanxn.top/Article/details/gt2ppomyqvh.html

TS:   // Node.js：readline 模块
来源：http://dali.ehwqpu.com/Article/details/gt2ujywbhgn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.0kj1m.cn/Article/details/gt2frtylkqz.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cucudq.cn/Article/details/gt2rvcsfiwm.html

Ruby: gets.chomp
来源：http://dali.shuidangran.top/Article/details/gt2usueayna.html

C#:   Console.ReadLine();
来源：http://dali.cheryme.top/Article/details/gt2ylfuaegh.html

[A21] 保留指定小数位输出
来源：http://dali.svipenyu.cn/Article/details/gt2dfcfozjo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhongyouzk.top/Article/details/gt2hxwxgoxx.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqyished.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gt2zxoxtgje.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wulvlyej.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gt2ezeqqhde.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gt2yygrdagi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gt2oqczjpgw.html

C#:   3.14159.ToString("F2")
来源：http://dali.bjfxy.top/Article/details/gt2jwlispyg.html

[A22] 获取字符串长度
来源：http://dali.mhx1999.top/Article/details/gt2zwdxazfr.html

Py:   len(s)
来源：http://dali.andypj.xyz/Article/details/gt2czsidura.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenlongwang.top/Article/details/gt2ztvpazyo.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.redwolf501.top/Article/details/gt2ymxoppqt.html

TS:   s.length
来源：http://dali.cqqwz.cn/Article/details/gt2kwnacqdd.html

Java: s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gt2viowehgf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xziqi.cn/Article/details/gt2byeuzmah.html

Ruby: s.length
来源：http://dali.316326.xyz/Article/details/gt2txkfontr.html

C#:   s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2meplblum.html

[A23] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqtqderr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yueranfly.top/Article/details/gt2yvqrwsis.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.smart0.xyz/Article/details/gt2kdclwlyz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gt2tvhmhxlg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gt2mmepgwrw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gt2kaynvuzi.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cucudq.cn/Article/details/gt2vtizzfir.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258888.top/Article/details/gt2uitrcubb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jianghu66.top/Article/details/gt2srcbtzzp.html

[A24] 去除首尾空白
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnillgqd.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gotoacloud.top/Article/details/gt2ruuzlcqg.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sxryk.cn/Article/details/gt2ahakilhf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gt2wtkavpwa.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gt2uohnzyfm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuanzx.com/Article/details/gt2kfumfbtd.html

Go:   strings.TrimSpace(s)
来源：http://dali.hywenlv.cn/Article/details/gt2aniublcc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sysykeji.top/Article/details/gt2aixmvixi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj202588.top/Article/details/gt2jgygpcgx.html

[A25] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2qmvfegxc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gotoacloud.top/Article/details/gt2mtxqqezr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhixingplan.top/Article/details/gt2zbotgxvu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenzaomai.com/Article/details/gt2fzprbvla.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gogol.net.cn/Article/details/gt2ionlukoj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinqigufen.top/Article/details/gt2uvpeaanx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbsxftak.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhixingplan.top/Article/details/gt2noetlhmi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gt2wbglemjx.html

[A26] 类型转换总览
来源：http://dali.mhx1999.top/Article/details/gt2ynxtdvlx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.vqdsnc.cn/Article/details/gt2qaqhjork.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sweek.top/Article/details/gt2ymkiawvz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.fengsongda.top/Article/details/gt2qtjfqjkn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sufxvd.cn/Article/details/gt2ujtaebsb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gt2ufrwaxcx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gogol.net.cn/Article/details/gt2maarwczs.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.316326.xyz/Article/details/gt2jpbccthi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gt2fqobksgs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2caraabgz.html

B. 流程控制
来源：http://dali.0kj1m.cn/Article/details/gt2csgtsnpo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2fnbwhbjs.html

[B01] 条件判断 if / else
来源：http://dali.yangfankeji.com/Article/details/gt2uxvdnbtv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.c1oappe.top/Article/details/gt2pkhmsura.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jianghu66.top/Article/details/gt2upvixerx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdulnono.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gt2khdujlph.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gt2tgfawgzm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cqqwz.cn/Article/details/gt2nrvprxxh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xinyue.icu/Article/details/gt2qjsqjxjx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gt2zjjogjbn.html

[B02] 多分支 else if / elif
来源：http://dali.316326.xyz/Article/details/gt2alippqpq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.redwolf501.top/Article/details/gt2apuhquup.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hfpthk.cn/Article/details/gt2qdcobqgs.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gt2lrpalclh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihxbftfz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gt2pdoqqato.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xghjgbuv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.guowangkeji.top/Article/details/gt2rgyktmql.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyjxwnmz.html

[B03] switch / match / case
来源：http://dali.zycfv.cn/Article/details/gt2zxhhazlu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yanxiufei.cn/Article/details/gt2uhjpqwsp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gt2krtvzbfr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gt2smnhbkly.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gt2ibmnhdsh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gt2qtlbvhmu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqymmuif.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shangyingyoupin.top/Article/details/gt2faynsqpq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cucudq.cn/Article/details/gt2ozkhxtrj.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gt2qavytfxz.html

Py:   for i in range(10): print(i)
来源：http://dali.yanxiufei.cn/Article/details/gt2siljiimr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yonumen.top/Article/details/gt2zrcpzuwe.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenlongwang.top/Article/details/gt2itfrfnaa.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jianghu66.top/Article/details/gt2cderajlv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.dianchejie.cn/Article/details/gt2tcxmdoez.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.316326.xyz/Article/details/gt2nuiikrxb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenzaomai.com/Article/details/gt2owlwkvjn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xinyue.icu/Article/details/gt2edvfhefl.html

[B05] 遍历数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gt2eukmmlwu.html

Py:   for item in arr: print(item)
来源：http://dali.tanke756.top/Article/details/gt2khqnszct.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yongpay.top/Article/details/gt2qtqvudzc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.c1oappe.top/Article/details/gt2whxeqony.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gt2qwsndozy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tianlin.xyz/Article/details/gt2juhdkfel.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ehwqpu.com/Article/details/gt2ysojxwyr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.bjfxy.top/Article/details/gt2yrrhmdxi.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.smart0.xyz/Article/details/gt2yytswvpw.html

[B06] 遍历字典 / 对象
来源：http://dali.xylfe.cn/Article/details/gt2bbjcbmqu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jiqunbmj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nwbrower.top/Article/details/gt2lmdvoqfe.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sxryk.cn/Article/details/gt2xjzkugaj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gt2fdnpnbez.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2adgxmhpb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yvedp.cn/Article/details/gt2vysvgyfe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gt2meffwqwy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnxiangtu.top/Article/details/gt2jmdjccaf.html

[B07] while 循环
来源：http://dali.zhixingplan.top/Article/details/gt2mjmosohy.html

Py:   while i < 10: i += 1
来源：http://dali.meibo888.top/Article/details/gt2gzpbeqkz.html


<!-- 参考信息 -->