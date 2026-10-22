代发 wailian999

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ydzc1.top/Article/details/gtcbufegbr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhoulong.xyz/Article/details/gthervxobq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitzgdecg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtjwiuaznm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtllvvissx.html

A. 基础语法与类型
来源：http://dali.shuidangran.top/Article/details/gtzbgretnb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjxztvpal.html

[A01] Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjspcefal.html

Py:   print("Hello, World!")
来源：http://dali.yvedp.cn/Article/details/gthuqztagi.html

PHP:  echo "Hello, World!";
来源：http://dali.sxryk.cn/Article/details/gtdyhlnzlb.html

JS:   console.log("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gtqxtrzflf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tian-w.cn/Article/details/gtiartzbsw.html

Java: System.out.println("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtjsmdla.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gtytzzofyz.html

Ruby: puts "Hello, World!"
来源：http://dali.daria6918.cn/Article/details/gteitpxdkw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gtihpxkkos.html

[A02] 变量声明与赋值
来源：http://dali.daria6918.cn/Article/details/gtbuchtone.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258888.top/Article/details/gtbqrylhaf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jianghu66.top/Article/details/gteboyhlyz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cashguo.top/Article/details/gtpzgsxpqd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cqqwz.cn/Article/details/gtipaulbuy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtbrnmzrcw.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxqobcnt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.havefunace.top/Article/details/gtbpxmwyql.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gtrpsdjlok.html

[A03] 常量定义
来源：http://dali.shangyingyoupin.top/Article/details/gtarwwkjmm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.andypj.xyz/Article/details/gtrmrlsrlc.html

PHP:  const PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtzlfodwrh.html

JS:   const PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtkqvnndqf.html

TS:   const PI: number = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtddtvkmyk.html

Java: static final double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtjeyjfcvw.html

Go:   const PI = 3.14159
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmtwsncy.html

Ruby: PI = 3.14159
来源：http://dali.xziqi.cn/Article/details/gtvdsrkvos.html

C#:   const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtcbdxkmuh.html

[A04] 判断变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gtbbtfllqk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fengsongda.top/Article/details/gtxbzihith.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gzhubu.top/Article/details/gtghedyket.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gtscicfqub.html

TS:   typeof x; x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gtcvjhtgtp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.kuanghao11.cn/Article/details/gtbgisycsz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.meibo888.top/Article/details/gtoewztkma.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xinyue.icu/Article/details/gtrzwhycjs.html

C#:   x.GetType().Name; x is int
来源：http://dali.xylfe.cn/Article/details/gtsnczqmpa.html

[A05] 整数除法与取模
来源：http://dali.feifeiyinyue.top/Article/details/gtcjueqvku.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.guannengcc.top/Article/details/gtwoxetwnn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtydwwcvdu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gthdgmpkwq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtfgddwcfc.html

Java: 7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtilrftayl.html

Go:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtvywubkse.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtgsveojny.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtjbakodyu.html

[A06] 字符串转数字
来源：http://dali.sweek.top/Article/details/gtlwiikbqu.html

Py:   int("42"); float("3.14")
来源：http://dali.yvedp.cn/Article/details/gtiiniekij.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jyoumei.cn/Article/details/gttffznqgk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhoulong.xyz/Article/details/gtsgzssyyd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ybcxt.top/Article/details/gtalevlcdh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shuidangran.top/Article/details/gtqnulgyuf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenzaomai.com/Article/details/gtjriyukin.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nanxinkj.top/Article/details/gtyculwrxn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gotoacloud.top/Article/details/gtgmyfvicu.html

[A07] 数字转字符串
来源：http://dali.xziqi.cn/Article/details/gtbvnaqdfi.html

Py:   str(42)
来源：http://dali.hfpthk.cn/Article/details/gthpixnbgy.html

PHP:  (string) 42; strval(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmyentsm.html

JS:   String(42); (42).toString()
来源：http://dali.nanxuanxn.top/Article/details/gtdtisjrdh.html

TS:   String(42)
来源：http://dali.yuxming.cn/Article/details/gtqvhkdybt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shzxlz.cn/Article/details/gtbmruuiph.html

Go:   strconv.Itoa(42)
来源：http://dali.9152youxi.cn/Article/details/gtxpyjqbys.html

Ruby: 42.to_s
来源：http://dali.ybcxt.top/Article/details/gtuaodurgb.html

C#:   42.ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtegnoqeim.html

[A08] 取整与四舍五入
来源：http://dali.hnqzz.top/Article/details/gttxanuabj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtmbdashid.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenjidiqi.icu/Article/details/gthfzctvrm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtacyuvsws.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhengqikj.top/Article/details/gtulskcvqa.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtzqhwdiks.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gttyluyukx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhengqikj.top/Article/details/gtlvgskcos.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gtcklbjwcg.html

[A09] 绝对值与最大最小值
来源：http://dali.chenlongwang.top/Article/details/gtomtxhhbz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtvsssovta.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwaapekeu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtkqsstzla.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtvkpnouvi.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtyhoyrepp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hywenlv.cn/Article/details/gtfshozttq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.redwolf501.top/Article/details/gtnfnjyxiy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gttaxxgjiw.html

[A10] 生成随机数
来源：http://dali.yongpay.top/Article/details/gtsjggzurg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hnxiangtu.top/Article/details/gtouedpcoc.html

PHP:  random_int(1, 100);
来源：http://dali.cdnleiting.top/Article/details/gtigjmcmds.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gtbudmoejh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gtdjlgxgrk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.fengsongda.top/Article/details/gtsrlwfixj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sysykeji.top/Article/details/gtmxzgmtox.html

Ruby: rand(1..100)
来源：http://dali.snrcjt.cn/Article/details/gtipsmvrha.html

C#:   new Random().Next(1, 101)
来源：http://dali.shangyingyoupin.top/Article/details/gtyiwwuscq.html

[A11] 条件表达式（三元）
来源：http://dali.jqgfzy.top/Article/details/gtfokgfcve.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ehwqpu.com/Article/details/gtftodbnjp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtekvfxued.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtrtkrytes.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtsvxtzbyc.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gtpstjdasx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jqgfzy.top/Article/details/gtggdlqprh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtfgjjnbqy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtycsjzncs.html

[A12] 字符串插值 / 格式化
来源：http://dali.mhx1999.top/Article/details/gtjtiuflpb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cdnleiting.top/Article/details/gtcnczucyx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhengqikj.top/Article/details/gtczsjwpvg.html

JS:   `Hello, ${name}!`
来源：http://dali.gogol.net.cn/Article/details/gtlgcashfq.html

TS:   `Hello, ${name}!`
来源：http://dali.chenjidiqi.icu/Article/details/gtaesjovpn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xylfe.cn/Article/details/gtqhcvtsbt.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xinyue.icu/Article/details/gtccfymolw.html

Ruby: "Hello, #{name}!"
来源：http://dali.zycfv.cn/Article/details/gtblujcvia.html

C#:   $"Hello, {name}!"
来源：http://dali.iojbl.cn/Article/details/gtxmnfcxrz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.9152youxi.cn/Article/details/gtzizeepse.html

Py:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtdvkegvby.html

PHP:  "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtiwksghwe.html

JS:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtujqxrhyn.html

TS:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtfouunuvu.html

Java: "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtxlttvkyr.html

Go:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtuookequy.html

Ruby: "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtwhbqymyo.html

C#:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gthvgiogtt.html

[A14] 注释写法
来源：http://dali.sufxvd.cn/Article/details/gtmglohmqc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ybcxt.top/Article/details/gtwddyxqby.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gtcqjkgoyz.html

JS:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtxnjwwgjk.html

TS:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtdsiqivkw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gtgnijiuxk.html

Go:   // 单行；/* 多行 */
来源：http://dali.ehwqpu.com/Article/details/gtihgfmmau.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.aibaodan.cn/Article/details/gtraxpgctr.html

C#:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtuajyjbpg.html

[A15] 空值判断与默认值
来源：http://dali.ehwqpu.com/Article/details/gtqwdjidfn.html

Py:   value = data or "默认值"
来源：http://dali.aibaodan.cn/Article/details/gtzsuwuyct.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gtjlbgjzxp.html

JS:   const value = data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gttwnignlz.html

TS:   const value = data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gttvwmbuqh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shuidangran.top/Article/details/gtpoawehon.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jyoumei.cn/Article/details/gtykyphwir.html

Ruby: value = data || "默认值"
来源：http://dali.birdmap.top/Article/details/gtoyilkwwt.html

C#:   var value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gtqhnjoqvw.html

[A16] 真假值判断规则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqewvzbe.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.redwolf501.top/Article/details/gtkdipfsef.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj202588.top/Article/details/gtgdamexim.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinghuilouyu.cn/Article/details/gttuievutl.html

TS:   if (!x) {}
来源：http://dali.havefunace.top/Article/details/gtleuansrv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.bjfxy.top/Article/details/gtjviawqea.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jianghu66.top/Article/details/gtylzjcpsq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.daxiang520.top/Article/details/gtvpadvzun.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.bjfxy.top/Article/details/gtnbncvysm.html

[A17] 位运算
来源：http://dali.daria6918.cn/Article/details/gtrbqnnbcj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtsvauqlkr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ivvv.top/Article/details/gtibxtfhxp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtmlgeeogl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtdnenthkv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtyvimghzm.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtcecdqwna.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtmiovmbzk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gtcehksnfk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.vqdsnc.cn/Article/details/gttlgfhhxm.html

Py:   ord("A"); chr(65)
来源：http://dali.chenlongwang.top/Article/details/gthvvkrpom.html

PHP:  ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gtyyyfrgqv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daria6918.cn/Article/details/gtabxslrtf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gtxhzltyyq.html

Java: (int) 'A'; (char) 65
来源：http://dali.hammf.cn/Article/details/gtxplydtcm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhixingplan.top/Article/details/gtqdyskfgh.html

Ruby: "A".ord; 65.chr
来源：http://dali.vqdsnc.cn/Article/details/gtgnnqriof.html

C#:   (int)'A'; (char)65
来源：http://dali.mhx1999.top/Article/details/gtcxbovkkt.html

[A19] 交换两个变量
来源：http://dali.sxryk.cn/Article/details/gtexmjdxea.html

Py:   a, b = b, a
来源：http://dali.birdmap.top/Article/details/gtiiymxsvk.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinghuilouyu.cn/Article/details/gtpifvhhkp.html

JS:   [a, b] = [b, a];
来源：http://dali.sxryk.cn/Article/details/gtjhsjhfkb.html

TS:   [a, b] = [b, a];
来源：http://dali.ppjwa.cn/Article/details/gtwlxtzcdv.html

Java: int t = a; a = b; b = t;
来源：http://dali.wangdashe.top/Article/details/gtbtjqlbug.html

Go:   a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gtjgmpftki.html

Ruby: a, b = b, a
来源：http://dali.quarkkingdee.top/Article/details/gtjkqdjvye.html

C#:   (a, b) = (b, a);
来源：http://dali.wangdashe.top/Article/details/gttqurmajk.html

[A20] 读取标准输入
来源：http://dali.jinqigfzy.top/Article/details/gtiofcummv.html

Py:   name = input("请输入：")
来源：http://dali.kuanghao11.cn/Article/details/gthxsrxwlx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuxming.cn/Article/details/gtyxzsmeoz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhiwuduotai.top/Article/details/gtdtnsrjbp.html

TS:   // Node.js：readline 模块
来源：http://dali.fzhhl.top/Article/details/gtqsmntyuw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zdqjudy.top/Article/details/gtfqtzuaxd.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yj20258888.top/Article/details/gthkdpujxu.html

Ruby: gets.chomp
来源：http://dali.guannengcc.top/Article/details/gtggchcfeh.html

C#:   Console.ReadLine();
来源：http://dali.tianlin.xyz/Article/details/gtgynykxrx.html

[A21] 保留指定小数位输出
来源：http://dali.sufxvd.cn/Article/details/gtmpgayujj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sweek.top/Article/details/gtsauohcqe.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtmavkkosa.html

JS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtcnwyflmz.html

TS:   (3.14159).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtjqelacoc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gtigodnbit.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gtbvlvlgkt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtbyombosi.html

C#:   3.14159.ToString("F2")
来源：http://dali.ehwqpu.com/Article/details/gtxkfkvzzb.html

[A22] 获取字符串长度
来源：http://dali.yueranfly.top/Article/details/gtdbfikhpw.html

Py:   len(s)
来源：http://dali.zhengqikj.top/Article/details/gtxpiitslj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tian-w.cn/Article/details/gttksqcfvs.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.redwolf501.top/Article/details/gtnsnpvhtl.html

TS:   s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafcsxjtj.html

Java: s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtuhjztiti.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenzaomai.com/Article/details/gtgwvwvcgh.html

Ruby: s.length
来源：http://dali.yangfankeji.com/Article/details/gtfqxbwpjz.html

C#:   s.Length
来源：http://dali.yongpay.top/Article/details/gtzoalpilp.html

[A23] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtmunfvdei.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.guannengcc.top/Article/details/gthhlwcyhw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aizwys.cn/Article/details/gtsxmijopk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtweuaewfa.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gtljxojpxx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacwarryu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yvedp.cn/Article/details/gtcbwchbtv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtenswpehk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jlsjyb.cn/Article/details/gtumfduiez.html

[A24] 去除首尾空白
来源：http://dali.jinghuilouyu.cn/Article/details/gtlosqljvk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.aizwys.cn/Article/details/gtjdxmghdc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhixingplan.top/Article/details/gtbyrkhyxj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shzxlz.cn/Article/details/gtnzxnariy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxuanxn.top/Article/details/gtomzzdryq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjfmtili.html

Go:   strings.TrimSpace(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefffleol.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinqigufen.top/Article/details/gtdifylwbw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.mhx1999.top/Article/details/gtwkyhhyic.html

[A25] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gteezgxvlq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ppjwa.cn/Article/details/gtzuehuakd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.dashuyun.cn/Article/details/gtqtsdupgk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yangfankeji.com/Article/details/gtnqqdimxf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtcpypbmmx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtaomrxdqj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuclqbkuq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfoeasfw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gttbswpycr.html

[A26] 类型转换总览
来源：http://dali.snrcjt.cn/Article/details/gtxkfhqxwr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cucudq.cn/Article/details/gtjogfaqnq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jqgfzy.top/Article/details/gtxmwxeqbj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shangyingyoupin.top/Article/details/gtbgwvbrmr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shanyushiyangtech.top/Article/details/gteeymusdh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gtunzzmazc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yuxming.cn/Article/details/gtyeapmkho.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.aizwys.cn/Article/details/gtsegxirqk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnixyahz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxvxvypru.html

B. 流程控制
来源：http://dali.pengpengdd.cyou/Article/details/gtrcsqvakj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttkbwwamt.html

[B01] 条件判断 if / else
来源：http://dali.chenlongwang.top/Article/details/gtyusqwaip.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.birdmap.top/Article/details/gtqmvxrmar.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sufxvd.cn/Article/details/gtrkjtvqko.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtbemyavkv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtwrtweuva.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gthltxxzjt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sxryk.cn/Article/details/gtguqffzcc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigufen.top/Article/details/gtusnapdze.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtinovhftq.html

[B02] 多分支 else if / elif
来源：http://dali.0kj1m.cn/Article/details/gtwvxncttt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinghuilouyu.cn/Article/details/gttjrzglgq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gogol.net.cn/Article/details/gtsamxishl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtpvrkekrx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtszgnaatc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtponhiliv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.iojbl.cn/Article/details/gttjiimirp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.guannengcc.top/Article/details/gtvpuijjfe.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gtgblxzyaa.html

[B03] switch / match / case
来源：http://dali.dianchejie.cn/Article/details/gtmeyaxyze.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhengqikj.top/Article/details/gtkkokhcay.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawlzehdx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtvtufodaz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gthpnogred.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtawprzqxp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gtafbwdjlv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shuidangran.top/Article/details/gtkaoiaucz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gtelbccjav.html

[B04] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtmcyggtzm.html

Py:   for i in range(10): print(i)
来源：http://dali.daria6918.cn/Article/details/gtfsvggyek.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gtvteeytxd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtntuhbvtg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jianghu66.top/Article/details/gtaxpzofdo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cqqwz.cn/Article/details/gttudlynyd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sysykeji.top/Article/details/gtqiajwqsu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gaohongyu789.top/Article/details/gtxqzkhazt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtyojekblw.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtoiyjokdd.html

Py:   for item in arr: print(item)
来源：http://dali.tian-w.cn/Article/details/gtjvmqumjo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shuidangran.top/Article/details/gtoswycekb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gtckuunazy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtlwtdnyku.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gttnuoqjqu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pycfn.com/Article/details/gtvfhhmdnu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhixingplan.top/Article/details/gtrjrrmnrw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuanzhike.top/Article/details/gtevladkup.html

[B06] 遍历字典 / 对象
来源：http://dali.pengpengdd.cyou/Article/details/gtbzoilrqb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgufenzy.top/Article/details/gtyytizbfy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hammf.cn/Article/details/gtimeowzvn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gtujflymfd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsmhvvflf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrcyumyf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.mhx1999.top/Article/details/gtkitciksf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dashuyun.cn/Article/details/gtxczaokdo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmhkvfadv.html

[B07] while 循环
来源：http://dali.nanxuanxn.top/Article/details/gtuzjovexe.html

Py:   while i < 10: i += 1
来源：http://dali.iojbl.cn/Article/details/gtwsxjnidr.html


<!-- 参考信息 -->