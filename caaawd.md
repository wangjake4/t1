代发 wailian999

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guowangkeji.top/Article/details/gt2xhpxgcyx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ydzc1.top/Article/details/gt2zjtabzzj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gt2wdovvjbm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gt2dsrmuaic.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2vukyrtdq.html

A. 基础语法与类型
来源：http://dali.dashuyun.cn/Article/details/gt2jjuhsbxn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2jwtuufeu.html

[A01] Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2vrtfkypt.html

Py:   print("Hello, World!")
来源：http://dali.dashuyun.cn/Article/details/gt2cwnxvigo.html

PHP:  echo "Hello, World!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpzenjad.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ajqcvpkr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zdqjudy.top/Article/details/gt2setbdewc.html

Java: System.out.println("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gt2hupsiaib.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sxryk.cn/Article/details/gt2lygssrrl.html

Ruby: puts "Hello, World!"
来源：http://dali.xinyue.icu/Article/details/gt2laoyllpz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjwhtoyf.html

[A02] 变量声明与赋值
来源：http://dali.sweek.top/Article/details/gt2xayuiobl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.meibo888.top/Article/details/gt2aladcqqf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cheryme.top/Article/details/gt2jtlzgnzd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gt2qiztmqxl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.aizwys.cn/Article/details/gt2vleotbyk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gt2hqmcfgke.html

Go:   name := "Alex"; age := 20
来源：http://dali.hammf.cn/Article/details/gt2pcartomf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkdibevt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gt2rduilhbl.html

[A03] 常量定义
来源：http://dali.hnqzz.top/Article/details/gt2qmyzbqnm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxinkj.top/Article/details/gt2ohahtdlg.html

PHP:  const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2eizqxftb.html

JS:   const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2nhhnodfn.html

TS:   const PI: number = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2tpznocjs.html

Java: static final double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2jqpgqsep.html

Go:   const PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gt2cwcyiwwt.html

Ruby: PI = 3.14159
来源：http://dali.jyoumei.cn/Article/details/gt2qjkqynwt.html

C#:   const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2gvqlmklw.html

[A04] 判断变量类型
来源：http://dali.andypj.xyz/Article/details/gt2jagctmcw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hfpthk.cn/Article/details/gt2ffbsofqg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenlongwang.top/Article/details/gt2gtmmfnjs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gt2rzpzbrck.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gt2tjyigibi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cheryme.top/Article/details/gt2evvnliwb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhixingplan.top/Article/details/gt2ljlidxum.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.pycfn.com/Article/details/gt2ngprakrt.html

C#:   x.GetType().Name; x is int
来源：http://dali.smart0.xyz/Article/details/gt2nidnqyxd.html

[A05] 整数除法与取模
来源：http://dali.yuxming.cn/Article/details/gt2pyhnrzwx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhengqikj.top/Article/details/gt2gkmbkjtg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2dasxzdrq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2jqinqjzx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gt2cqnjsknj.html

Java: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2vzmshcbk.html

Go:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gt2oghovhkl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlimemho.html

C#:   7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gt2lupqziwr.html

[A06] 字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2scjwxrot.html

Py:   int("42"); float("3.14")
来源：http://dali.ivvv.top/Article/details/gt2njuumkwe.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cdnleiting.top/Article/details/gt2ewxwqsmv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gt2ecarvdsg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gt2znmbjqnd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gt2auehojbm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pynlikad.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ivvv.top/Article/details/gt2olotofre.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jiagoushi.top/Article/details/gt2iumpnoye.html

[A07] 数字转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2zovnhzln.html

Py:   str(42)
来源：http://dali.cheryme.top/Article/details/gt2cyigrvyv.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukniztul.html

JS:   String(42); (42).toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbzcofnp.html

TS:   String(42)
来源：http://dali.gotoacloud.top/Article/details/gt2sdpamoie.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sxryk.cn/Article/details/gt2rhfxyctm.html

Go:   strconv.Itoa(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emtglgsu.html

Ruby: 42.to_s
来源：http://dali.gotoacloud.top/Article/details/gt2axdtrgoe.html

C#:   42.ToString()
来源：http://dali.sweek.top/Article/details/gt2vzfmgzgh.html

[A08] 取整与四舍五入
来源：http://dali.andypj.xyz/Article/details/gt2ltejkpdk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.haohaochexian.top/Article/details/gt2ebfnsyas.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.smart0.xyz/Article/details/gt2gizcnpim.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gt2kueawlth.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.fengsongda.top/Article/details/gt2ritvhsdi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gt2uytopssv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bztseprt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.kuanghao11.cn/Article/details/gt2oyslntyu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gt2kqvvvujc.html

[A09] 绝对值与最大最小值
来源：http://dali.xziqi.cn/Article/details/gt2oecewnba.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2fupicday.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2izogixfu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aplvmcbn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2ipqtrgvj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2ikoeweic.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.316326.xyz/Article/details/gt2wfbzmsil.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.dianchejie.cn/Article/details/gt2iolukdbg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2abjwpezt.html

[A10] 生成随机数
来源：http://dali.daxiang520.top/Article/details/gt2fkkcvudo.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yuxming.cn/Article/details/gt2fxwzrsld.html

PHP:  random_int(1, 100);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uopnwnqk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ybcxt.top/Article/details/gt2hvqxixia.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqqbniih.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guowangkeji.top/Article/details/gt2ucupdikt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cashguo.top/Article/details/gt2migfwusi.html

Ruby: rand(1..100)
来源：http://dali.redwolf501.top/Article/details/gt2zkzvnzbq.html

C#:   new Random().Next(1, 101)
来源：http://dali.jiagoushi.top/Article/details/gt2dnbvkoha.html

[A11] 条件表达式（三元）
来源：http://dali.iojbl.cn/Article/details/gt2behxwoff.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.birdmap.top/Article/details/gt2kwtbzbir.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gt2oigpipkk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gt2kckdnnjy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjcqreir.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gt2czhjzzkb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xinyue.icu/Article/details/gt2nokqguew.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gt2rebqnzrh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2ajljrhhx.html

[A12] 字符串插值 / 格式化
来源：http://dali.gotoacloud.top/Article/details/gt2tromoewp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.fengsongda.top/Article/details/gt2ulbznmud.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibjmlcgk.html

JS:   `Hello, ${name}!`
来源：http://dali.gaohongyu789.top/Article/details/gt2ldomlbpq.html

TS:   `Hello, ${name}!`
来源：http://dali.hywenlv.cn/Article/details/gt2tckovxrj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.ehwqpu.com/Article/details/gt2uwhhysbd.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.smart0.xyz/Article/details/gt2vlsuodgo.html

Ruby: "Hello, #{name}!"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcqcaqoa.html

C#:   $"Hello, {name}!"
来源：http://dali.ehwqpu.com/Article/details/gt2xbvxebkd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iglkpyml.html

Py:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gt2bihpiyyg.html

PHP:  "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gt2vjytamgm.html

JS:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gt2tgnnrrqd.html

TS:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gt2irghrcca.html

Java: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2daaezavl.html

Go:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2ooeeoozm.html

Ruby: "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2qbpedska.html

C#:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gt2irtmkxbs.html

[A14] 注释写法
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnpmucuy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gotoacloud.top/Article/details/gt2wilolkeu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gt2ffpirvhn.html

JS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcvldaoa.html

TS:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gt2yzglrpyq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nanxinkj.top/Article/details/gt2ubxykqan.html

Go:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gt2wnyopwzc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.vqdsnc.cn/Article/details/gt2owneyqlw.html

C#:   // 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gt2ckinaeug.html

[A15] 空值判断与默认值
来源：http://dali.birdmap.top/Article/details/gt2fvjcmstb.html

Py:   value = data or "默认值"
来源：http://dali.bjfxy.top/Article/details/gt2piomeghy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gt2zutrqlyf.html

JS:   const value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gt2xzpkrvks.html

TS:   const value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gt2fpkbpxqq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hfpthk.cn/Article/details/gt2xadgosxf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.dashuyun.cn/Article/details/gt2svijizzy.html

Ruby: value = data || "默认值"
来源：http://dali.hywenlv.cn/Article/details/gt2hkiayrap.html

C#:   var value = data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gt2btetiirn.html

[A16] 真假值判断规则
来源：http://dali.smart0.xyz/Article/details/gt2bzumamtt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgglfdyy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzpygqju.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yongpay.top/Article/details/gt2ukgoezat.html

TS:   if (!x) {}
来源：http://dali.ehwqpu.com/Article/details/gt2eomvoheq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hnqzz.top/Article/details/gt2pqyhljdj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ehwqpu.com/Article/details/gt2zhnbckzv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj20258888.top/Article/details/gt2kwjockqn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yj20258888.top/Article/details/gt2qwuamlpw.html

[A17] 位运算
来源：http://dali.gogol.net.cn/Article/details/gt2btusjyfh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2mrvdcqhb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2plfbmmjh.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gt2oaitowmv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2dcmgdkhl.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gt2qvibylhi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2bustshiw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gt2ayiddmzf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gt2qceerohi.html

[A18] 字符与 ASCII 码互转
来源：http://dali.chenzaomai.com/Article/details/gt2adwbyaqw.html

Py:   ord("A"); chr(65)
来源：http://dali.9152youxi.cn/Article/details/gt2sjbugpos.html

PHP:  ord("A"); chr(65)
来源：http://dali.xziqi.cn/Article/details/gt2paalxacv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daria6918.cn/Article/details/gt2bmywflpn.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qszuping.html

Java: (int) 'A'; (char) 65
来源：http://dali.yanxiufei.cn/Article/details/gt2lbevuzyx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daria6918.cn/Article/details/gt2nqwjxbph.html

Ruby: "A".ord; 65.chr
来源：http://dali.cheryme.top/Article/details/gt2mgidrdpi.html

C#:   (int)'A'; (char)65
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bovtefnb.html

[A19] 交换两个变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjnofqxp.html

Py:   a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gt2tumaxjui.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.tianlin.xyz/Article/details/gt2ajnawwdt.html

JS:   [a, b] = [b, a];
来源：http://dali.chenzaomai.com/Article/details/gt2mlfupmpm.html

TS:   [a, b] = [b, a];
来源：http://dali.yangfankeji.com/Article/details/gt2fothbhrd.html

Java: int t = a; a = b; b = t;
来源：http://dali.cqqwz.cn/Article/details/gt2ikwqteex.html

Go:   a, b = b, a
来源：http://dali.shangyingyoupin.top/Article/details/gt2exaqsgee.html

Ruby: a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gt2eglsgius.html

C#:   (a, b) = (b, a);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufsjplip.html

[A20] 读取标准输入
来源：http://dali.jlsjyb.cn/Article/details/gt2arqfxaxs.html

Py:   name = input("请输入：")
来源：http://dali.smart0.xyz/Article/details/gt2svexvuzk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.nanxuanxn.top/Article/details/gt2kxidaboj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yanxiufei.cn/Article/details/gt2fnitntwr.html

TS:   // Node.js：readline 模块
来源：http://dali.dashuyun.cn/Article/details/gt2psjrvbub.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.fengsongda.top/Article/details/gt2ortawqfk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gzhubu.top/Article/details/gt2gryvizan.html

Ruby: gets.chomp
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmoxuyoo.html

C#:   Console.ReadLine();
来源：http://dali.wangdashe.top/Article/details/gt2gnjpuvko.html

[A21] 保留指定小数位输出
来源：http://dali.xinyue.icu/Article/details/gt2zipfmoti.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tianlin.xyz/Article/details/gt2frujssdz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gt2drckvxux.html

JS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gt2qbhlypgw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gt2zrqwbxaa.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2yfsiptwz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gt2lowplfzm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jlsjyb.cn/Article/details/gt2gwelhgou.html

C#:   3.14159.ToString("F2")
来源：http://dali.jyoumei.cn/Article/details/gt2rokjbewb.html

[A22] 获取字符串长度
来源：http://dali.bjfxy.top/Article/details/gt2ysbsiwxt.html

Py:   len(s)
来源：http://dali.hnqzz.top/Article/details/gt2pmxgneya.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxuanxn.top/Article/details/gt2brzfgfoj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.wangshuangyany.cn/Article/details/gt2skyrejyb.html

TS:   s.length
来源：http://dali.sweek.top/Article/details/gt2mjsihftf.html

Java: s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2dfupmpnv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.mhx1999.top/Article/details/gt2gfzfzbfe.html

Ruby: s.length
来源：http://dali.hammf.cn/Article/details/gt2foywkjhw.html

C#:   s.Length
来源：http://dali.sweek.top/Article/details/gt2zyurqrkt.html

[A23] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gt2eegnupbi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihasqkuu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2odimadnu.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gt2dzylqyad.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxrhwspq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gt2wakisgiu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgnmprtb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gt2demoheoo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.guannengcc.top/Article/details/gt2dhfiihyv.html

[A24] 去除首尾空白
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqnvhqpt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj20258888.top/Article/details/gt2issygcdo.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhoulong.xyz/Article/details/gt2xkmdnnwz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gt2tlzlvbmm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.snrcjt.cn/Article/details/gt2ztnvjeaf.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pengpengdd.cyou/Article/details/gt2vsdpggfa.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinqigufen.top/Article/details/gt2krdwnfsw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnlcdcfg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj202588.top/Article/details/gt2pvshxrqs.html

[A25] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gt2owxyzfkr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuanzhike.top/Article/details/gt2ypkycccw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxixhfpy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ppjwa.cn/Article/details/gt2xckfuevo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzcgnobd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhoulong.xyz/Article/details/gt2qphobnjc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gt2roxmwmxe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.quarkkingdee.top/Article/details/gt2aqcvkhre.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gt2klplzyiu.html

[A26] 类型转换总览
来源：http://dali.andypj.xyz/Article/details/gt2ovtbxhum.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xylfe.cn/Article/details/gt2roeevodk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkdformp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.vqdsnc.cn/Article/details/gt2qjzfmpcy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.quarkkingdee.top/Article/details/gt2jcvxmgoh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.guowangkeji.top/Article/details/gt2odlkmnfm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zycfv.cn/Article/details/gt2ntdscvjy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xylfe.cn/Article/details/gt2mtfnmebn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cheryme.top/Article/details/gt2dqcfmzqd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2reumkrbo.html

B. 流程控制
来源：http://dali.nwbrower.top/Article/details/gt2ycfbuxzx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2orsmcmzt.html

[B01] 条件判断 if / else
来源：http://dali.9152youxi.cn/Article/details/gt2hzvvwcgr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.svipenyu.cn/Article/details/gt2tmpvtasz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sufxvd.cn/Article/details/gt2mouixouv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gt2fkkxrkpm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2sttxerxw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2nsgdhjkr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbngbxtf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guowangkeji.top/Article/details/gt2otoavupp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gt2hfpwakez.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gt2djhooitd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.0kj1m.cn/Article/details/gt2lpzhuiov.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zycfv.cn/Article/details/gt2plenmtpe.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gt2cixydyfs.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gt2uwwiiowv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gt2pdlysihi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shzxlz.cn/Article/details/gt2tkuipgbg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xuanzx.com/Article/details/gt2uceunhzf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gt2csopqomr.html

[B03] switch / match / case
来源：http://dali.smart0.xyz/Article/details/gt2ljabibit.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmfdxxsw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gt2yljueacz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tharjgmk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gt2epqzrmuy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2iosusajy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zngcknna.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cashguo.top/Article/details/gt2jhvyrhbj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.0kj1m.cn/Article/details/gt2pucboxzw.html

[B04] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gt2trwibcqf.html

Py:   for i in range(10): print(i)
来源：http://dali.hammf.cn/Article/details/gt2ykxbxakq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yueranfly.top/Article/details/gt2gbnxszhm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2frwrmezl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gt2lnynycan.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.daxiang520.top/Article/details/gt2ixrdkpje.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhongyouzk.top/Article/details/gt2sggmhifi.html

Ruby: 10.times { |i| puts i }
来源：http://dali.andypj.xyz/Article/details/gt2exalxdid.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yanxiufei.cn/Article/details/gt2jjnnfnvk.html

[B05] 遍历数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gt2nmrjwhsb.html

Py:   for item in arr: print(item)
来源：http://dali.yuanzhike.top/Article/details/gt2dspzwjye.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2odgayfbl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gt2kwpkfoxv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gt2cakofdpa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.vqdsnc.cn/Article/details/gt2fnflvvbb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrbjexmu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yueranfly.top/Article/details/gt2kcatsqdr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cqqwz.cn/Article/details/gt2cqvxhmmz.html

[B06] 遍历字典 / 对象
来源：http://dali.tian-w.cn/Article/details/gt2hjymhlak.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gt2nctssvcb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shzxlz.cn/Article/details/gt2oemtlfgm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gt2bkgddquq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gt2vqmfpext.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gogol.net.cn/Article/details/gt2brayfqbp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hysaishi.cn/Article/details/gt2iezocpcm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gogol.net.cn/Article/details/gt2eymhwmis.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnqzz.top/Article/details/gt2etbvyaed.html

[B07] while 循环
来源：http://dali.hammf.cn/Article/details/gt2nrlffjlr.html

Py:   while i < 10: i += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrbkbwgc.html


<!-- 参考信息 -->