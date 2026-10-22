代发 wailian999

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtmtrbkuqz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnqzz.top/Article/details/gthdwflffx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gthcuvxhjp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtyzyzyozj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtuuowhzvv.html

A. 基础语法与类型
来源：http://dali.aizwys.cn/Article/details/gttgjbsklt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdthptjgf.html

[A01] Hello World
来源：http://dali.9152youxi.cn/Article/details/gtztcpjwot.html

Py:   print("Hello, World!")
来源：http://dali.jinqigfzy.top/Article/details/gtiwrmllir.html

PHP:  echo "Hello, World!";
来源：http://dali.chenzaomai.com/Article/details/gtchzwgmnm.html

JS:   console.log("Hello, World!");
来源：http://dali.zhengqikj.top/Article/details/gtfsggwqdn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shuidangran.top/Article/details/gtmjpgpirz.html

Java: System.out.println("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtlszqcfvv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj20258.top/Article/details/gtwatkiwsw.html

Ruby: puts "Hello, World!"
来源：http://dali.vqdsnc.cn/Article/details/gtyqdbgdvf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gtylyugbji.html

[A02] 变量声明与赋值
来源：http://dali.gogol.net.cn/Article/details/gtugnhpnyd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.redwolf501.top/Article/details/gtjkpjfpdu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtiykanuri.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258888.top/Article/details/gthjktyipd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258.top/Article/details/gtndqhhugp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtowvbjney.html

Go:   name := "Alex"; age := 20
来源：http://dali.hongshengwenyu.top/Article/details/gtcnootizx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xylfe.cn/Article/details/gtsnixqouq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cashguo.top/Article/details/gtcmhvvefj.html

[A03] 常量定义
来源：http://dali.dianchejie.cn/Article/details/gtdjroochw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ivvv.top/Article/details/gtdfbzfdap.html

PHP:  const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtrxnqldxr.html

JS:   const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtladqwsaf.html

TS:   const PI: number = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtqdizfjrq.html

Java: static final double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtzsuhgphy.html

Go:   const PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gtuyxrlqvh.html

Ruby: PI = 3.14159
来源：http://dali.xylfe.cn/Article/details/gttixmpfbn.html

C#:   const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtfcljkbcy.html

[A04] 判断变量类型
来源：http://dali.cashguo.top/Article/details/gtmecthewg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.bjfxy.top/Article/details/gtjxeninlc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpafqenk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhengqikj.top/Article/details/gtfrjoksdb.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gtuvjwhueg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xylfe.cn/Article/details/gtjjbnsuzl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.meibo888.top/Article/details/gtllrbvlqk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sweek.top/Article/details/gtvfksavvp.html

C#:   x.GetType().Name; x is int
来源：http://dali.guannengcc.top/Article/details/gttwftzygz.html

[A05] 整数除法与取模
来源：http://dali.aizwys.cn/Article/details/gtmavezhbo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jyoumei.cn/Article/details/gtiqfnrkcn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtqmyooxvi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtoafvptnh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gttkkmiekm.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gteliczmzf.html

Go:   7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtabglewbi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtmrnmndgh.html

C#:   7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gttqganqdn.html

[A06] 字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtfswpaylv.html

Py:   int("42"); float("3.14")
来源：http://dali.xziqi.cn/Article/details/gtwarbzgju.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gtvqdeidup.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gtvgmbgqkz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gtfrsmdtxt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gtkozdxyhf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj202588.top/Article/details/gtenvgelwy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnxiangtu.top/Article/details/gtnlwthgtt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xinyue.icu/Article/details/gtgrubeoql.html

[A07] 数字转字符串
来源：http://dali.jinqigufen.top/Article/details/gtketckujq.html

Py:   str(42)
来源：http://dali.xuanzx.com/Article/details/gtlrcdatrc.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj20258.top/Article/details/gtbyofypmm.html

JS:   String(42); (42).toString()
来源：http://dali.yvedp.cn/Article/details/gtccdecmqd.html

TS:   String(42)
来源：http://dali.c1oappe.top/Article/details/gtwkcdhthj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.vqdsnc.cn/Article/details/gtgtvyyqiu.html

Go:   strconv.Itoa(42)
来源：http://dali.jiagoushi.top/Article/details/gtpsfwzgdm.html

Ruby: 42.to_s
来源：http://dali.meibo888.top/Article/details/gtybuivwcr.html

C#:   42.ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gttrnhvmyq.html

[A08] 取整与四舍五入
来源：http://dali.fzhhl.top/Article/details/gtoqddupfh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtqftzhwqx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hammf.cn/Article/details/gtqrajggts.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yonumen.top/Article/details/gtjssuumwn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jiagoushi.top/Article/details/gtkftrgcgr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtlaudpmxr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtavauqnej.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cdnleiting.top/Article/details/gtamqbamlq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtjsudkyic.html

[A09] 绝对值与最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtfaicpzcc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtoihvdsgl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtdbmlwsiy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtjmlorlmf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtyppwyopo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtnrdadyxb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhengqikj.top/Article/details/gtpzryazrs.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gtbwpflcsm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtxiljmpzn.html

[A10] 生成随机数
来源：http://dali.zhongyouzk.top/Article/details/gtmjeixvkl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sufxvd.cn/Article/details/gtxaqutwkb.html

PHP:  random_int(1, 100);
来源：http://dali.jqgufenzy.top/Article/details/gtdxdqegol.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tian-w.cn/Article/details/gtcovccueh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigfzy.top/Article/details/gtzltrivyd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.iojbl.cn/Article/details/gtvgxpwgky.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkwoblby.html

Ruby: rand(1..100)
来源：http://dali.aibaodan.cn/Article/details/gtlgdwqqln.html

C#:   new Random().Next(1, 101)
来源：http://dali.jqgfzy.top/Article/details/gtxtbnnvrf.html

[A11] 条件表达式（三元）
来源：http://dali.cashguo.top/Article/details/gtqrygiudy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.snrcjt.cn/Article/details/gtpwbelvht.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtcyadhqhm.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gtyypadblp.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtftbgkhjq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gthbvzmgfx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.birdmap.top/Article/details/gtbjwrgbnz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtzxedpisb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gtairxhhzx.html

[A12] 字符串插值 / 格式化
来源：http://dali.nwbrower.top/Article/details/gtypxvbncs.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yongpay.top/Article/details/gtsuxfsmzx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sxryk.cn/Article/details/gtlyoamqdy.html

JS:   `Hello, ${name}!`
来源：http://dali.feifeiyinyue.top/Article/details/gtwlqydcth.html

TS:   `Hello, ${name}!`
来源：http://dali.hongshengwenyu.top/Article/details/gtwilyewbv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.dianchejie.cn/Article/details/gtcwuahtgk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtlzvjnavl.html

Ruby: "Hello, #{name}!"
来源：http://dali.feifeiyinyue.top/Article/details/gtrtjnekfb.html

C#:   $"Hello, {name}!"
来源：http://dali.c1oappe.top/Article/details/gtcxxcnfoy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yuanzhike.top/Article/details/gtviyvwtwm.html

Py:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtbdhlyncj.html

PHP:  "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gttauxmqlx.html

JS:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatvinmrj.html

TS:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtykojcplv.html

Java: "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtmokdljdm.html

Go:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtfupoqzpx.html

Ruby: "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtewybrefp.html

C#:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtinfswzuj.html

[A14] 注释写法
来源：http://dali.yanxiufei.cn/Article/details/gtzlwryoja.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hywenlv.cn/Article/details/gtvxzuepuw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtrigojjzp.html

JS:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gtkdcpmxeo.html

TS:   // 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gtwzwzhdwz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.316326.xyz/Article/details/gtsxwmurdk.html

Go:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtzhhxisos.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.chenzaomai.com/Article/details/gtkrggcpix.html

C#:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtvvillyux.html

[A15] 空值判断与默认值
来源：http://dali.sweek.top/Article/details/gtolqvmhba.html

Py:   value = data or "默认值"
来源：http://dali.andypj.xyz/Article/details/gtuhcnersu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gtrtiedlaj.html

JS:   const value = data ?? "默认值";
来源：http://dali.feifeiyinyue.top/Article/details/gttngvhcms.html

TS:   const value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gtukgfsqhn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hammf.cn/Article/details/gtdpmbmcuu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yanxiufei.cn/Article/details/gtjtmufyje.html

Ruby: value = data || "默认值"
来源：http://dali.vqdsnc.cn/Article/details/gtqwhbjhyu.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhoulong.xyz/Article/details/gtpjpgjbar.html

[A16] 真假值判断规则
来源：http://dali.cdnleiting.top/Article/details/gtoxtketqe.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.tian-w.cn/Article/details/gthigzbvqy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.fzhhl.top/Article/details/gtzrbrpqlq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.guowangkeji.top/Article/details/gtkakvlfhx.html

TS:   if (!x) {}
来源：http://dali.xuanzx.com/Article/details/gtfgpimnth.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cucudq.cn/Article/details/gthovlclwr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hnxiangtu.top/Article/details/gtirpjueii.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tian-w.cn/Article/details/gttjwclhpf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.fzhhl.top/Article/details/gtlzgydwpf.html

[A17] 位运算
来源：http://dali.ehwqpu.com/Article/details/gtvitfrurc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtspbzhgko.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yonumen.top/Article/details/gtyxgnrwxn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtsadsqear.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtsoesouib.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtocqmtctg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtiuqkijoc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtvhmknjea.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtywfcoqwm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.9152youxi.cn/Article/details/gtksabqvnu.html

Py:   ord("A"); chr(65)
来源：http://dali.quarkkingdee.top/Article/details/gtiqczuxvh.html

PHP:  ord("A"); chr(65)
来源：http://dali.hysaishi.cn/Article/details/gtfphuwbcb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cqqwz.cn/Article/details/gtfohhyxuq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ehwqpu.com/Article/details/gtfegoyuwa.html

Java: (int) 'A'; (char) 65
来源：http://dali.hnxiangtu.top/Article/details/gtqceplvko.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenjidiqi.icu/Article/details/gtwspvtlsj.html

Ruby: "A".ord; 65.chr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijmbwmig.html

C#:   (int)'A'; (char)65
来源：http://dali.yuxming.cn/Article/details/gtcyeqcxlk.html

[A19] 交换两个变量
来源：http://dali.ydzc1.top/Article/details/gtmrgrpmgk.html

Py:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gtswoykywe.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.mhx1999.top/Article/details/gtzsvrekav.html

JS:   [a, b] = [b, a];
来源：http://dali.jqgufenzy.top/Article/details/gtxsaurzht.html

TS:   [a, b] = [b, a];
来源：http://dali.daxiang520.top/Article/details/gtmoyvkwtn.html

Java: int t = a; a = b; b = t;
来源：http://dali.yueranfly.top/Article/details/gtizwovjay.html

Go:   a, b = b, a
来源：http://dali.ybcxt.top/Article/details/gtzwnqdfbu.html

Ruby: a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gtqploywgb.html

C#:   (a, b) = (b, a);
来源：http://dali.feifeiyinyue.top/Article/details/gtebgfykzo.html

[A20] 读取标准输入
来源：http://dali.zhiwuduotai.top/Article/details/gtvajgsdhu.html

Py:   name = input("请输入：")
来源：http://dali.hfpthk.cn/Article/details/gtserljnpp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.quarkkingdee.top/Article/details/gtjbhjzedl.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinqigufen.top/Article/details/gtjdcivokm.html

TS:   // Node.js：readline 模块
来源：http://dali.jlsjyb.cn/Article/details/gtyszybkkj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinqigufen.top/Article/details/gtbioqufrk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jiagoushi.top/Article/details/gtzfnnedgs.html

Ruby: gets.chomp
来源：http://dali.nanxinkj.top/Article/details/gturtrvakz.html

C#:   Console.ReadLine();
来源：http://dali.zdqjudy.top/Article/details/gtemnvxwuv.html

[A21] 保留指定小数位输出
来源：http://dali.sufxvd.cn/Article/details/gtdimhgotg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigfzy.top/Article/details/gthssxodkj.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtrjpoghhd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gtwycgikhw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtegeonzrx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtnnadbyok.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxazefijg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gtqctxnozm.html

C#:   3.14159.ToString("F2")
来源：http://dali.ehwqpu.com/Article/details/gtrzuwuwoj.html

[A22] 获取字符串长度
来源：http://dali.xinyue.icu/Article/details/gtzubufobh.html

Py:   len(s)
来源：http://dali.wangdashe.top/Article/details/gtiorqguct.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shzxlz.cn/Article/details/gtmmwjgsgq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sysykeji.top/Article/details/gtxhhktpqe.html

TS:   s.length
来源：http://dali.hywenlv.cn/Article/details/gtgwgggqte.html

Java: s.length()
来源：http://dali.jyoumei.cn/Article/details/gtjdnhyraj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.9152youxi.cn/Article/details/gtmqscadkg.html

Ruby: s.length
来源：http://dali.vqdsnc.cn/Article/details/gtwyzmzjfu.html

C#:   s.Length
来源：http://dali.yongpay.top/Article/details/gtvcnhargo.html

[A23] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gteuwjwotn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gtdrqymswq.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hongshengwenyu.top/Article/details/gtvpakkbsa.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gtkyjxuxpb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gtvtrdorii.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigufen.top/Article/details/gtthsmtnso.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jiagoushi.top/Article/details/gtxiqelted.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sxryk.cn/Article/details/gterjpcbrq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.aizwys.cn/Article/details/gtvdscabqb.html

[A24] 去除首尾空白
来源：http://dali.zhongyouzk.top/Article/details/gtjahxkxtx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shangyingyoupin.top/Article/details/gtesxwsfhl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.tian-w.cn/Article/details/gtdajspbfe.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.bjfxy.top/Article/details/gtqmzgmafv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtwxrypkja.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.bjfxy.top/Article/details/gtcqvalgwe.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinqigfzy.top/Article/details/gtoscrcghe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj20258888.top/Article/details/gtztbpmwkr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinqigfzy.top/Article/details/gtxtkgdffb.html

[A25] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtrqupdsnd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gtaolrofru.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yanxiufei.cn/Article/details/gtgnffpmmw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ppjwa.cn/Article/details/gtunpmqinn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gteyjyojns.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.bjfxy.top/Article/details/gttvzlmumy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gtgukkxolx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.c1oappe.top/Article/details/gtmgqlgwmm.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gtrlmiqpym.html

[A26] 类型转换总览
来源：http://dali.dashuyun.cn/Article/details/gtnyabqwty.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ehwqpu.com/Article/details/gtygdwfiap.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hnqzz.top/Article/details/gtgmffujnd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hysaishi.cn/Article/details/gtxptievxh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.snrcjt.cn/Article/details/gtxjbjtfrl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gtkouvtmlr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258888.top/Article/details/gtvigdldwx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtocyeavzl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shuidangran.top/Article/details/gtimsvesal.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcqepwuru.html

B. 流程控制
来源：http://dali.jianghu66.top/Article/details/gtyjfmqhhq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxipxgufd.html

[B01] 条件判断 if / else
来源：http://dali.cdnleiting.top/Article/details/gtykgqvvmz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xuanzx.com/Article/details/gtzubbxnms.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sysykeji.top/Article/details/gtvdzcrbjl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtjfezober.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlutrwhhn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtyzsrootb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ppjwa.cn/Article/details/gtaekztuhg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.smart0.xyz/Article/details/gtdwrvhbfm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gttglufknn.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gtsuqracvu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxuanxn.top/Article/details/gtzlvhnoqz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hnxiangtu.top/Article/details/gtrhfjyvat.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtmigrrlpc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtwwtobgvj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtklrqoaig.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jianghu66.top/Article/details/gtmlaylymq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxuanxn.top/Article/details/gtilkbxwmp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtfgqybzur.html

[B03] switch / match / case
来源：http://dali.guowangkeji.top/Article/details/gtspacuejs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhongyouzk.top/Article/details/gtgtkitxnj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtukiqvskh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtiqypinen.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtvrgbwpea.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkjctjlge.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtadhvvnqr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shzxlz.cn/Article/details/gtaxgahxed.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcsalnns.html

[B04] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtiswxmebu.html

Py:   for i in range(10): print(i)
来源：http://dali.redwolf501.top/Article/details/gtgkfieaap.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.bjfxy.top/Article/details/gtdfknttth.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtimryrydx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gttkyuiahm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.snrcjt.cn/Article/details/gtakxnwlci.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinqigfzy.top/Article/details/gthxznhgeu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jyoumei.cn/Article/details/gtbhbmague.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfplhhni.html

[B05] 遍历数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtzsfogkdy.html

Py:   for item in arr: print(item)
来源：http://dali.gaohongyu789.top/Article/details/gtbyoccoxa.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yueranfly.top/Article/details/gtsyfnnfvt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gtaqvnabbd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtnacsvebi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnmkblxi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.feifeiyinyue.top/Article/details/gtppeuidwh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhixingplan.top/Article/details/gtolhoqdvg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtofvoaorf.html

[B06] 遍历字典 / 对象
来源：http://dali.smart0.xyz/Article/details/gtrorwuwld.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sufxvd.cn/Article/details/gtxotjatic.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258.top/Article/details/gtugvnoday.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtfkpxtqeo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gtslpumqyy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gtftdezncg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hywenlv.cn/Article/details/gtadpdzsbp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.c1oappe.top/Article/details/gtjewuokkd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pycfn.com/Article/details/gtcwstyaep.html

[B07] while 循环
来源：http://dali.fzhhl.top/Article/details/gtjiquaqsl.html

Py:   while i < 10: i += 1
来源：http://dali.ivvv.top/Article/details/gtkqevwefk.html


<!-- 参考信息 -->