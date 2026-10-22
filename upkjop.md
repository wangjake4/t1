代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.xuanzx.com/Article/details/gtnbnehgoi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtaewovgiv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.meibo888.top/Article/details/gtapbxomxs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtotowwxpa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenzaomai.com/Article/details/gtltvoijbc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtyzeykfpj.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258888.top/Article/details/gtceznjqmp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zdqjudy.top/Article/details/gtvmfogbza.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagwcpwff.html

[A03] 常量定义
来源：http://dali.dianchejie.cn/Article/details/gtnspurwaq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shzxlz.cn/Article/details/gtndeyxasf.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtepxkcace.html

JS:   const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtlrfpbelp.html

TS:   const PI: number = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gttnpkjfig.html

Java: static final double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtchkomloe.html

Go:   const PI = 3.14159
来源：http://dali.sxryk.cn/Article/details/gtvvpbceio.html

Ruby: PI = 3.14159
来源：http://dali.yongpay.top/Article/details/gtglyqekfe.html

C#:   const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtrshjggji.html

[A04] 判断变量类型
来源：http://dali.cqqwz.cn/Article/details/gtomzqefew.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yangfankeji.com/Article/details/gtmaugmhzl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yvedp.cn/Article/details/gtzcyuhxpq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gtitvmuhgx.html

TS:   typeof x; x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtlwzcrmin.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hammf.cn/Article/details/gtxdebcmwi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aibaodan.cn/Article/details/gtzanilpme.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gtrhqswkto.html

C#:   x.GetType().Name; x is int
来源：http://dali.xylfe.cn/Article/details/gtiogkohqo.html

[A05] 整数除法与取模
来源：http://dali.fengsongda.top/Article/details/gtpisuwsnv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.aizwys.cn/Article/details/gtuyaxcwlc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtfqzephfr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtoahtqfvc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnfccqap.html

Java: 7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtqjbnthsc.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gthxqzqpvc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtnfrseiov.html

C#:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtlzdputea.html

[A06] 字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gthgeyvhdr.html

Py:   int("42"); float("3.14")
来源：http://dali.jianghu66.top/Article/details/gtpidpvjyd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhongyouzk.top/Article/details/gtpxhkozpx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sxryk.cn/Article/details/gtypuarrua.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gtywxhbjjq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.redwolf501.top/Article/details/gtqfvwrlhp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.svipenyu.cn/Article/details/gtzktjlujq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcefsklv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtncsicq.html

[A07] 数字转字符串
来源：http://dali.tanke756.top/Article/details/gtfadltdcp.html

Py:   str(42)
来源：http://dali.jlsjyb.cn/Article/details/gtvopketbt.html

PHP:  (string) 42; strval(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtslwggelm.html

JS:   String(42); (42).toString()
来源：http://dali.xuanzx.com/Article/details/gtwhdlmgwu.html

TS:   String(42)
来源：http://dali.yueranfly.top/Article/details/gtigqwufuv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtxiqqzpbw.html

Go:   strconv.Itoa(42)
来源：http://dali.316326.xyz/Article/details/gtawfgfydk.html

Ruby: 42.to_s
来源：http://dali.ppjwa.cn/Article/details/gtaxhtdlad.html

C#:   42.ToString()
来源：http://dali.cdnleiting.top/Article/details/gtecrjntwp.html

[A08] 取整与四舍五入
来源：http://dali.quarkkingdee.top/Article/details/gtcnhfbkpa.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gtbvpjtalf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jlsjyb.cn/Article/details/gtkwruaxpg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtlqwccipi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeqyrdwd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtyguvtlwo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtzrmpgnxq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yueranfly.top/Article/details/gtodwldosn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gteetgzzzn.html

[A09] 绝对值与最大最小值
来源：http://dali.havefunace.top/Article/details/gtenvcpumb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yonumen.top/Article/details/gtwmjkscaq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtbptivnjp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtmonvoomz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtewfartkc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gthfzebgwh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yangfankeji.com/Article/details/gtaevtyokb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhixingplan.top/Article/details/gtzezqbcze.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtrkgqdtbf.html

[A10] 生成随机数
来源：http://dali.ydzc1.top/Article/details/gtplrlfvyk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nanxinkj.top/Article/details/gtesdpgdxx.html

PHP:  random_int(1, 100);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjfwcnhw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenlongwang.top/Article/details/gtcqqoabof.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cheryme.top/Article/details/gtmeniiuhc.html

Java: new Random().nextInt(100) + 1
来源：http://dali.nwbrower.top/Article/details/gtphspeump.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cheryme.top/Article/details/gtvtlxqhfn.html

Ruby: rand(1..100)
来源：http://dali.daxiang520.top/Article/details/gtwxtxrgkq.html

C#:   new Random().Next(1, 101)
来源：http://dali.gotoacloud.top/Article/details/gtstwzpncm.html

[A11] 条件表达式（三元）
来源：http://dali.yongpay.top/Article/details/gtdjcuxwho.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.fzhhl.top/Article/details/gtammedxxx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtyaaafxuz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtzvxdgttg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gtrjdrcuxz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtdceeifmd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.snrcjt.cn/Article/details/gtoytsrlfd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtxmfopfpl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtllmcyotx.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtuhipfosg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.tianlin.xyz/Article/details/gtzfjsydny.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shangyingyoupin.top/Article/details/gtdglsutwe.html

JS:   `Hello, ${name}!`
来源：http://dali.tanke756.top/Article/details/gtzqzpgkiv.html

TS:   `Hello, ${name}!`
来源：http://dali.yongpay.top/Article/details/gtkyjhqkhn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.0kj1m.cn/Article/details/gtnvbjujof.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yvedp.cn/Article/details/gtuqweapul.html

Ruby: "Hello, #{name}!"
来源：http://dali.wangshuangyany.cn/Article/details/gtfmlajxbl.html

C#:   $"Hello, {name}!"
来源：http://dali.nanxinkj.top/Article/details/gtqqeoivwr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.meibo888.top/Article/details/gtnzxkvxoz.html

Py:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtztmrkjsw.html

PHP:  "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gttkindqrw.html

JS:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtgnxmhfrz.html

TS:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtuhqxqyzr.html

Java: "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gtjqjvrqut.html

Go:   "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtaakenujy.html

Ruby: "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtwvqlnnlt.html

C#:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtbdjsevyv.html

[A14] 注释写法
来源：http://dali.yueranfly.top/Article/details/gthhmqefny.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hnqzz.top/Article/details/gtvkqexqvr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gtfxofbxji.html

JS:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtvkjcsivb.html

TS:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtrauaimbj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yongpay.top/Article/details/gtbcygemwd.html

Go:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtntazytgy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.nanxuanxn.top/Article/details/gtlkibbaaj.html

C#:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtreytmnjm.html

[A15] 空值判断与默认值
来源：http://dali.cashguo.top/Article/details/gtkqpyunyx.html

Py:   value = data or "默认值"
来源：http://dali.yj20258888.top/Article/details/gtqfqjetvm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtglmvveiw.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtlhimopvy.html

TS:   const value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtimtbecxg.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.andypj.xyz/Article/details/gtwlnvqpzf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj202588.top/Article/details/gtcozrxnam.html

Ruby: value = data || "默认值"
来源：http://dali.gogol.net.cn/Article/details/gtlykmpcox.html

C#:   var value = data ?? "默认值";
来源：http://dali.fzhhl.top/Article/details/gtusyzvbbe.html

[A16] 真假值判断规则
来源：http://dali.tian-w.cn/Article/details/gtauwchxqh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtdjcwjeet.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.snrcjt.cn/Article/details/gtlaqristv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhongyouzk.top/Article/details/gthcpyprje.html

TS:   if (!x) {}
来源：http://dali.havefunace.top/Article/details/gtwspideqj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtywzyutyl.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hysaishi.cn/Article/details/gtxaxuvomk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sufxvd.cn/Article/details/gtifdmqoth.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shuidangran.top/Article/details/gtkvxwdepf.html

[A17] 位运算
来源：http://dali.kuanghao11.cn/Article/details/gtqfkmkwzi.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtyrparapc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtrwyqubrb.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtaulmcpvg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtuqnygnix.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtxitxspdt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtkcoapmah.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gthulxirsb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtqwpnrlvj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yonumen.top/Article/details/gtvjgldjbv.html

Py:   ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gtvcxbwgrk.html

PHP:  ord("A"); chr(65)
来源：http://dali.hywenlv.cn/Article/details/gtxeecneyq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gzhubu.top/Article/details/gtgfgzyghi.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.c1oappe.top/Article/details/gttlcjfwwq.html

Java: (int) 'A'; (char) 65
来源：http://dali.ivvv.top/Article/details/gtisoavsuo.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jqgfzy.top/Article/details/gtddttjneb.html

Ruby: "A".ord; 65.chr
来源：http://dali.daria6918.cn/Article/details/gtpbphcbbz.html

C#:   (int)'A'; (char)65
来源：http://dali.yanxiufei.cn/Article/details/gtvxjefxdp.html

[A19] 交换两个变量
来源：http://dali.zdqjudy.top/Article/details/gtzeepbfsw.html

Py:   a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gtacmimnfk.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cucudq.cn/Article/details/gtoujwfupb.html

JS:   [a, b] = [b, a];
来源：http://dali.kuanghao11.cn/Article/details/gtsrauelnj.html

TS:   [a, b] = [b, a];
来源：http://dali.yongpay.top/Article/details/gttbowdaoh.html

Java: int t = a; a = b; b = t;
来源：http://dali.redwolf501.top/Article/details/gtykvbmexf.html

Go:   a, b = b, a
来源：http://dali.nanxuanxn.top/Article/details/gtzjumcflv.html

Ruby: a, b = b, a
来源：http://dali.cheryme.top/Article/details/gtixgukpef.html

C#:   (a, b) = (b, a);
来源：http://dali.daxiang520.top/Article/details/gtajmgezjd.html

[A20] 读取标准输入
来源：http://dali.jinqigfzy.top/Article/details/gtdlgnkcwe.html

Py:   name = input("请输入：")
来源：http://dali.tanke756.top/Article/details/gtltuwvada.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cucudq.cn/Article/details/gtfjxcvjmu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.guannengcc.top/Article/details/gtnevcovqg.html

TS:   // Node.js：readline 模块
来源：http://dali.guowangkeji.top/Article/details/gtwyunuzvb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.fzhhl.top/Article/details/gtqnmukbzw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shangyingyoupin.top/Article/details/gtnazozrcc.html

Ruby: gets.chomp
来源：http://dali.zhengqikj.top/Article/details/gtonxlddfj.html

C#:   Console.ReadLine();
来源：http://dali.chenlongwang.top/Article/details/gtpcqtdzwv.html

[A21] 保留指定小数位输出
来源：http://dali.havefunace.top/Article/details/gtqckunzek.html

Py:   f"{3.14159:.2f}"
来源：http://dali.daria6918.cn/Article/details/gteibjijqt.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtatfyazyk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtmxreeyrf.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gtfzsjfeid.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtnnzaqfqb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gtekrvciei.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtihwslekn.html

C#:   3.14159.ToString("F2")
来源：http://dali.yvedp.cn/Article/details/gtbwlofygd.html

[A22] 获取字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gthyvlbxop.html

Py:   len(s)
来源：http://dali.birdmap.top/Article/details/gtevbnegzo.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ivvv.top/Article/details/gthumphhhy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhiwuduotai.top/Article/details/gtonsfueju.html

TS:   s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtimbfqzxv.html

Java: s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtlihwqmlb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxinkj.top/Article/details/gtnddcbzrj.html

Ruby: s.length
来源：http://dali.gotoacloud.top/Article/details/gttkuwwwwt.html

C#:   s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtnhxuuglw.html

[A23] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtzazpskuz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhixingplan.top/Article/details/gtlmfarwnu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.andypj.xyz/Article/details/gtvxvukuxd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtweteelhb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gtukhxfskw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gthxrytdcq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.havefunace.top/Article/details/gttocnxtvi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sweek.top/Article/details/gtbzfoxxpg.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xuetiantiany.cn/Article/details/gtbjdtfvnq.html

[A24] 去除首尾空白
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjlkrfbl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shangyingyoupin.top/Article/details/gtoyqovkby.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhoulong.xyz/Article/details/gtaelgtwzh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtqyqzrpyo.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.havefunace.top/Article/details/gtjufxwpld.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xziqi.cn/Article/details/gtyhqletuj.html

Go:   strings.TrimSpace(s)
来源：http://dali.xuanzx.com/Article/details/gtvxqgupds.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shanyushiyangtech.top/Article/details/gteogoawfj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guannengcc.top/Article/details/gtiewjsasl.html

[A25] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtxfaiqmau.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cdnleiting.top/Article/details/gtczjpuezx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.dianchejie.cn/Article/details/gtpcbajbzl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gtmqqpnwdx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnqzz.top/Article/details/gtwvtgiyif.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtdspvdpyt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ybcxt.top/Article/details/gtsfttlqcm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenlongwang.top/Article/details/gthuhtqaqi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gtfilwfgdq.html

[A26] 类型转换总览
来源：http://dali.ybcxt.top/Article/details/gtumgvdvjh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhixingplan.top/Article/details/gtycgnwcut.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.svipenyu.cn/Article/details/gtuiavxuyh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gzhubu.top/Article/details/gtmazwawtp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gogol.net.cn/Article/details/gtkqatnpcp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gzhubu.top/Article/details/gtvyjiwmqt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhoulong.xyz/Article/details/gttiqugehn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknnfzmch.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gtgnswwvir.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtuzuswvrz.html

B. 流程控制
来源：http://dali.ehwqpu.com/Article/details/gtanczgipl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthxixwiia.html

[B01] 条件判断 if / else
来源：http://dali.jianghu66.top/Article/details/gtbrllypvw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hysaishi.cn/Article/details/gtnxvpdffo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjhmckcu.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtiylvhrbf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtvgpkqryi.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtapavqjej.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhoulong.xyz/Article/details/gtrfryhhey.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gtzxoizyxl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gtdjffqjle.html

[B02] 多分支 else if / elif
来源：http://dali.mhx1999.top/Article/details/gtreghnhku.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sweek.top/Article/details/gtibhpoteo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yanxiufei.cn/Article/details/gttdqspcmp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtljriitgv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtweelnlbb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtgdfbjqdg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.daria6918.cn/Article/details/gtbrbjgskh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.quarkkingdee.top/Article/details/gtgjsrdjnm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtaqvkdacx.html

[B03] switch / match / case
来源：http://dali.ydzc1.top/Article/details/gtuflkszhm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jiagoushi.top/Article/details/gtmeewvtoh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflxxzotx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gttxwyqlpr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gteigwzytz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtxsqqmnss.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.smart0.xyz/Article/details/gtuutedcxh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xuanzx.com/Article/details/gtkichjaie.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gtcpdrxbxp.html

[B04] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtqmcdphvc.html

Py:   for i in range(10): print(i)
来源：http://dali.hywenlv.cn/Article/details/gtynwnaqvy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sufxvd.cn/Article/details/gtjxygpdmy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gtrtabpvfo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gtbmexleut.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ivvv.top/Article/details/gthswbtsoj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ybcxt.top/Article/details/gtddypphia.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hammf.cn/Article/details/gtgehykeyu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.c1oappe.top/Article/details/gtxjmbbizc.html

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesxrcvlk.html

Py:   for item in arr: print(item)
来源：http://dali.sxryk.cn/Article/details/gtzbymaiuk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.snrcjt.cn/Article/details/gtnkyjbbdk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gtgmmhzoix.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sweek.top/Article/details/gtpprcsspx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.svipenyu.cn/Article/details/gtyvgmiyin.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yuanzhike.top/Article/details/gtuzfzwnom.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangshuangyany.cn/Article/details/gttunukiat.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xinyue.icu/Article/details/gtfygfnwfw.html

[B06] 遍历字典 / 对象
来源：http://dali.gaohongyu789.top/Article/details/gtdcxjqdml.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgufenzy.top/Article/details/gttapapjnb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dashuyun.cn/Article/details/gtwukltlku.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gtbgtmpylg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtizksbccr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jlsjyb.cn/Article/details/gtsbsuaqod.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.316326.xyz/Article/details/gtbhbnljqb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gtkwwhnikq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ppjwa.cn/Article/details/gthptchewh.html

[B07] while 循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvibxtduu.html

Py:   while i < 10: i += 1
来源：http://dali.gaohongyu789.top/Article/details/gtvsmlgwlg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cqqwz.cn/Article/details/gttqfyefbq.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gteoytosgb.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhagrwxo.html

Java: while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtmlvgnuvk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.vqdsnc.cn/Article/details/gtlchobrgy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gtxlcmritu.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtjjzuqkws.html

[B08] do-while（至少执行一次）
来源：http://dali.aizwys.cn/Article/details/gtjqgsgltd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ppjwa.cn/Article/details/gtnosncbrc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sweek.top/Article/details/gtdcmorvcd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtlbezzfst.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtecwafrgj.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtygulqurl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gtniglpsaj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nwbrower.top/Article/details/gtvhvpqcii.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtzqebhian.html


<!-- 参考信息 -->