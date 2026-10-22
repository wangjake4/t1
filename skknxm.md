代发 wailian999

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.andypj.xyz/Article/details/gtclrtjvpp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jlsjyb.cn/Article/details/gtwovhothv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gtzegtyvgm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtqdaglwww.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvcjsdumj.html

A. 基础语法与类型
来源：http://dali.quarkkingdee.top/Article/details/gtantknyxe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtcenrllfc.html

[A01] Hello World
来源：http://dali.ppjwa.cn/Article/details/gtxycolvky.html

Py:   print("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gtyycqfxkt.html

PHP:  echo "Hello, World!";
来源：http://dali.ybcxt.top/Article/details/gthdnpdbyg.html

JS:   console.log("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafapewsf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cdnleiting.top/Article/details/gtdzlqvzmf.html

Java: System.out.println("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gtuqotjoca.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jyoumei.cn/Article/details/gtwsnumuql.html

Ruby: puts "Hello, World!"
来源：http://dali.jianghu66.top/Article/details/gtfrkfjneq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmedrzvr.html

[A02] 变量声明与赋值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyqxriwj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dianchejie.cn/Article/details/gtykiemrbb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tian-w.cn/Article/details/gtfsbaweoc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtmbdgnzox.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fzhhl.top/Article/details/gtyqnjzktu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gtokxqvyuy.html

Go:   name := "Alex"; age := 20
来源：http://dali.birdmap.top/Article/details/gtoqoopmqy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cucudq.cn/Article/details/gtblrtkqma.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gteyzsbdyj.html

[A03] 常量定义
来源：http://dali.svipenyu.cn/Article/details/gtszzfdmnq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yanxiufei.cn/Article/details/gtkqbrcevu.html

PHP:  const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtxqkrfllm.html

JS:   const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtxcicichz.html

TS:   const PI: number = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtukfwxfrz.html

Java: static final double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtwnrasslk.html

Go:   const PI = 3.14159
来源：http://dali.cdnleiting.top/Article/details/gtezalxosl.html

Ruby: PI = 3.14159
来源：http://dali.daria6918.cn/Article/details/gtrswdiwia.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtiwlllsyv.html

[A04] 判断变量类型
来源：http://dali.yvedp.cn/Article/details/gtubfbnfyu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.aibaodan.cn/Article/details/gtgaeiyclw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.c1oappe.top/Article/details/gtbwesoccr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gtazzhomcz.html

TS:   typeof x; x instanceof Date
来源：http://dali.dashuyun.cn/Article/details/gtkxudfjyt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyjatcyf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.tanke756.top/Article/details/gtxbbwehdd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yongpay.top/Article/details/gtdnhfduxy.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmkkmbtb.html

[A05] 整数除法与取模
来源：http://dali.tian-w.cn/Article/details/gttkkfbiza.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigfzy.top/Article/details/gtdvxbynbb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtixbgyhkf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtzppxfjtj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtcijgjnqa.html

Java: 7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtwahqrwda.html

Go:   7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtpnjfluoz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtvrsdiova.html

C#:   7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtfysagaea.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtefzmohzp.html

Py:   int("42"); float("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gtpqhinoch.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sxryk.cn/Article/details/gtmnlgyaje.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprhcppbc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.andypj.xyz/Article/details/gtivdqlksl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.guannengcc.top/Article/details/gtxbxvrkyl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.birdmap.top/Article/details/gtzejfvytu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnxiangtu.top/Article/details/gtsdvrdnaq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gtmuuxspib.html

[A07] 数字转字符串
来源：http://dali.zdqjudy.top/Article/details/gtvxhqfncb.html

Py:   str(42)
来源：http://dali.gzhubu.top/Article/details/gtsvdfsmhh.html

PHP:  (string) 42; strval(42)
来源：http://dali.iojbl.cn/Article/details/gteinhcrzg.html

JS:   String(42); (42).toString()
来源：http://dali.yvedp.cn/Article/details/gttjiqovtk.html

TS:   String(42)
来源：http://dali.jyoumei.cn/Article/details/gtzxligcnx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ivvv.top/Article/details/gtohmodaeg.html

Go:   strconv.Itoa(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtklviyrbi.html

Ruby: 42.to_s
来源：http://dali.hfpthk.cn/Article/details/gtdxdcdrjr.html

C#:   42.ToString()
来源：http://dali.hywenlv.cn/Article/details/gtyqzomrmf.html

[A08] 取整与四舍五入
来源：http://dali.yueranfly.top/Article/details/gtigvryymr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gtwyqflpze.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zycfv.cn/Article/details/gthhtolmmv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtfogutkww.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.daria6918.cn/Article/details/gtnvhfbxlu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gtkjghwdth.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtebzcclsj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhixingplan.top/Article/details/gtnqslsari.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gtfakxfsrv.html

[A09] 绝对值与最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtstnqvnsp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtqhfbqvsw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtmxwinxna.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtcqyyuvbj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtrnftdwwc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtnxixkykq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cqqwz.cn/Article/details/gtkwbipwgz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.svipenyu.cn/Article/details/gtvrkbqprj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtcafwjstl.html

[A10] 生成随机数
来源：http://dali.xinyue.icu/Article/details/gtehhxjkmv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.mhx1999.top/Article/details/gttuuyupmn.html

PHP:  random_int(1, 100);
来源：http://dali.fzhhl.top/Article/details/gtobcrwjsn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gogol.net.cn/Article/details/gtqzuaubup.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sxryk.cn/Article/details/gtxfgctbsv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.nanxinkj.top/Article/details/gtbgolseha.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.9152youxi.cn/Article/details/gtiqvehhds.html

Ruby: rand(1..100)
来源：http://dali.yj20258.top/Article/details/gtmecwhvky.html

C#:   new Random().Next(1, 101)
来源：http://dali.hfpthk.cn/Article/details/gtznbmnkks.html

[A11] 条件表达式（三元）
来源：http://dali.jyoumei.cn/Article/details/gtmnmaxgzp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jiagoushi.top/Article/details/gtcohjxjgp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gtpsiycihs.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtnyzzkavl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtrefrsklr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfmjxuev.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.pengpengdd.cyou/Article/details/gtsugtjhlz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gteowaosky.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtkzyrhdtc.html

[A12] 字符串插值 / 格式化
来源：http://dali.hysaishi.cn/Article/details/gtehphuxtd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sxryk.cn/Article/details/gtbhyuefrp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.chenlongwang.top/Article/details/gtgzixlfmn.html

JS:   `Hello, ${name}!`
来源：http://dali.zhixingplan.top/Article/details/gtumxwqtgd.html

TS:   `Hello, ${name}!`
来源：http://dali.bjfxy.top/Article/details/gtnilfeemn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.aizwys.cn/Article/details/gtxbrpvyvs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ybcxt.top/Article/details/gtdkfkhdpx.html

Ruby: "Hello, #{name}!"
来源：http://dali.haohaochexian.top/Article/details/gtboczjtsn.html

C#:   $"Hello, {name}!"
来源：http://dali.ppjwa.cn/Article/details/gthlbqybcl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gtmkkjzxuh.html

Py:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtsqljuvkg.html

PHP:  "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtcfegtwsm.html

JS:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtobbfqnza.html

TS:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtejyhimgo.html

Java: "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtxwyvefti.html

Go:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtaltyembs.html

Ruby: "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtytrncmtv.html

C#:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtyhopicog.html

[A14] 注释写法
来源：http://dali.zhoulong.xyz/Article/details/gtmaazktnt.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hysaishi.cn/Article/details/gtcoafayoh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gtsghylbqi.html

JS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtqvrtxsca.html

TS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtphmefkzh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ybcxt.top/Article/details/gttgwtekdt.html

Go:   // 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gtimpiqgzz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ivvv.top/Article/details/gtvxswbnxu.html

C#:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtnjtpysan.html

[A15] 空值判断与默认值
来源：http://dali.nanxinkj.top/Article/details/gtmbhlczpc.html

Py:   value = data or "默认值"
来源：http://dali.iojbl.cn/Article/details/gtwcdnhlyz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zdqjudy.top/Article/details/gtwmzlhwrs.html

JS:   const value = data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gtrckiqbjc.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gtrgqamekm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yueranfly.top/Article/details/gtimvqvkso.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shangyingyoupin.top/Article/details/gteyryhuty.html

Ruby: value = data || "默认值"
来源：http://dali.bjfxy.top/Article/details/gtnssqxgvb.html

C#:   var value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtujqdebzi.html

[A16] 真假值判断规则
来源：http://dali.chenlongwang.top/Article/details/gtkdcamxtl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.meibo888.top/Article/details/gtojckjexl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ehwqpu.com/Article/details/gtvhzcnidx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.pengpengdd.cyou/Article/details/gtsygmtvqr.html

TS:   if (!x) {}
来源：http://dali.jinqigfzy.top/Article/details/gtiyswtmwt.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nwbrower.top/Article/details/gtqxxswair.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sweek.top/Article/details/gtrcbjgocq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.9152youxi.cn/Article/details/gtlinpgntk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtarpclouy.html

[A17] 位运算
来源：http://dali.yueranfly.top/Article/details/gtzxqhyspw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtduyzhrnt.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtodxesmcd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtmoknqelq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtjgpybavo.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtqqafhcri.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtbvuwxvak.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gticcgwcpu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtwkzowjcl.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ehwqpu.com/Article/details/gtvxqzsoxh.html

Py:   ord("A"); chr(65)
来源：http://dali.cqqwz.cn/Article/details/gtpxbgluur.html

PHP:  ord("A"); chr(65)
来源：http://dali.chenlongwang.top/Article/details/gthydzcauo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jiagoushi.top/Article/details/gtsnfdyhtg.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gzhubu.top/Article/details/gthawnsiaj.html

Java: (int) 'A'; (char) 65
来源：http://dali.guannengcc.top/Article/details/gthpecqwbz.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhoulong.xyz/Article/details/gtrnveptfe.html

Ruby: "A".ord; 65.chr
来源：http://dali.bjfxy.top/Article/details/gtmnpsssmt.html

C#:   (int)'A'; (char)65
来源：http://dali.zhixingplan.top/Article/details/gtnadmontf.html

[A19] 交换两个变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdtyubcy.html

Py:   a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gteearbuti.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sysykeji.top/Article/details/gtneztfjgx.html

JS:   [a, b] = [b, a];
来源：http://dali.jinghuilouyu.cn/Article/details/gthqnjqaiu.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgfzy.top/Article/details/gtaxrcutbn.html

Java: int t = a; a = b; b = t;
来源：http://dali.guannengcc.top/Article/details/gthtyksmhf.html

Go:   a, b = b, a
来源：http://dali.vqdsnc.cn/Article/details/gtgonytrfr.html

Ruby: a, b = b, a
来源：http://dali.sweek.top/Article/details/gttqmsrsru.html

C#:   (a, b) = (b, a);
来源：http://dali.meibo888.top/Article/details/gtpmdqwdhi.html

[A20] 读取标准输入
来源：http://dali.wangdashe.top/Article/details/gtinylcugm.html

Py:   name = input("请输入：")
来源：http://dali.hywenlv.cn/Article/details/gtjacmfnti.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zycfv.cn/Article/details/gtlmvmzrrf.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ybcxt.top/Article/details/gtcpgdukdv.html

TS:   // Node.js：readline 模块
来源：http://dali.9152youxi.cn/Article/details/gtwwtdyljg.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.bjfxy.top/Article/details/gthvyzyliw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.dashuyun.cn/Article/details/gtgdfoxdhd.html

Ruby: gets.chomp
来源：http://dali.daria6918.cn/Article/details/gttaucukdc.html

C#:   Console.ReadLine();
来源：http://dali.jianghu66.top/Article/details/gtoqqzhcec.html

[A21] 保留指定小数位输出
来源：http://dali.yonumen.top/Article/details/gtukehwblw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hongshengwenyu.top/Article/details/gtrkjtbkzo.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtpskvchsh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxaosmvc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtsnulsslb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gtqlrhlpal.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jlsjyb.cn/Article/details/gtrwbkcapq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtgcsrlniu.html

C#:   3.14159.ToString("F2")
来源：http://dali.iojbl.cn/Article/details/gtogapthch.html

[A22] 获取字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtdapvcyov.html

Py:   len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtdgjpqmkb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nwbrower.top/Article/details/gtaxaiykyf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhijiandao.cn/Article/details/gtflenynit.html

TS:   s.length
来源：http://dali.xziqi.cn/Article/details/gtalhesgtl.html

Java: s.length()
来源：http://dali.wangdashe.top/Article/details/gtqgzudmen.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj20258888.top/Article/details/gtcdqcterq.html

Ruby: s.length
来源：http://dali.sufxvd.cn/Article/details/gtovimsjxv.html

C#:   s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtsxcfohlo.html

[A23] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtqnbtrvbj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dashuyun.cn/Article/details/gtnhinqsft.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuxming.cn/Article/details/gthwajuqtu.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gtkixtlqdb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gtnezjfbby.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtwmjcocyy.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zycfv.cn/Article/details/gtkggxkdpf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtjgnuhyvk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.haohaochexian.top/Article/details/gthkfgbdwk.html

[A24] 去除首尾空白
来源：http://dali.0kj1m.cn/Article/details/gtwzslqzld.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fzhhl.top/Article/details/gtcpidksvh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhongyouzk.top/Article/details/gtjsfruzqu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtkrmaoxws.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnfygoai.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gaohongyu789.top/Article/details/gtbktxcbaz.html

Go:   strings.TrimSpace(s)
来源：http://dali.tianlin.xyz/Article/details/gtryyygtrs.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shangyingyoupin.top/Article/details/gtffdjaopy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.iojbl.cn/Article/details/gtazfvlfwr.html

[A25] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmldwjwbo.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yanxiufei.cn/Article/details/gtxdphukiv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hysaishi.cn/Article/details/gtkijkrpzf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.svipenyu.cn/Article/details/gtbcbzdupk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gtbmmglemw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtzqgdweki.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlqjlcvw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sufxvd.cn/Article/details/gtzzyjlifu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gtisimqcme.html

[A26] 类型转换总览
来源：http://dali.wangdashe.top/Article/details/gtnyvipxhy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.guowangkeji.top/Article/details/gtispzctqm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daria6918.cn/Article/details/gtykqiglpf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdveakks.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sysykeji.top/Article/details/gtxoiwgwgw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gtoftgcguv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhongyouzk.top/Article/details/gtywtbemkb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.snrcjt.cn/Article/details/gtvcwokbyx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gtsqctryme.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpqwofwl.html

B. 流程控制
来源：http://dali.chenzaomai.com/Article/details/gtwamgjnii.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtuatrmejg.html

[B01] 条件判断 if / else
来源：http://dali.xinyue.icu/Article/details/gtcdivhqda.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtryuzgzsg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyhmreou.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtpypcupqh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtmeetqmlz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtfwgknlmv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.quarkkingdee.top/Article/details/gtcqlnxcbh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.0kj1m.cn/Article/details/gthlbcoxbw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtmbtdzxkd.html

[B02] 多分支 else if / elif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemzttvuf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yangfankeji.com/Article/details/gtaookfrga.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhixingplan.top/Article/details/gtmhqbcxij.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtnmpfzbtx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gtmkijnxzu.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtecoetpwn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.chenjidiqi.icu/Article/details/gtrqpzojwk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zycfv.cn/Article/details/gtvwjzohbf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gtngkzuejm.html

[B03] switch / match / case
来源：http://dali.ybcxt.top/Article/details/gtwhzpqyod.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yangfankeji.com/Article/details/gtweoicdoy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gtnnohlfrm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtfbldeldw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gtjxozwhxm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtctsyqlqe.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gthimreuom.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yangfankeji.com/Article/details/gtvpccvsnx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shuidangran.top/Article/details/gtkvheucwg.html

[B04] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtiafwaeaw.html

Py:   for i in range(10): print(i)
来源：http://dali.gotoacloud.top/Article/details/gtfkvyzzwe.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yangfankeji.com/Article/details/gtqcbppjmr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gtfsklbmmy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gtmepwttow.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nwbrower.top/Article/details/gtmlrovtwj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhengqikj.top/Article/details/gtakjtxbaz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gtxuwkeciw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.dashuyun.cn/Article/details/gteaowcqvy.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtqbsbhaoq.html

Py:   for item in arr: print(item)
来源：http://dali.xinyue.icu/Article/details/gtbqqnlped.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkljehbmk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtnoyidngw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtowexsqsk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmiordxo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yueranfly.top/Article/details/gtoupozqti.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gzhubu.top/Article/details/gtqrqnkgde.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.aizwys.cn/Article/details/gtfayzenng.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigfzy.top/Article/details/gtwcexqryw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.svipenyu.cn/Article/details/gtmziflzqb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.mhx1999.top/Article/details/gtqbrczdyg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gtgxyladee.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gteuakbuea.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zdqjudy.top/Article/details/gtritmxllh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.feifeiyinyue.top/Article/details/gtvogpysxr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jianghu66.top/Article/details/gtzickanhe.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gtuknmptyc.html

[B07] while 循环
来源：http://dali.jianghu66.top/Article/details/gtpuoftapw.html

Py:   while i < 10: i += 1
来源：http://dali.iojbl.cn/Article/details/gtrzjmpsiq.html


<!-- 参考信息 -->