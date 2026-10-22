代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gthpuzhrje.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yangfankeji.com/Article/details/gtjqrwxttw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtdtxqhwox.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.9152youxi.cn/Article/details/gtgfokjlhp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuanzx.com/Article/details/gttgpcroqg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtstptiwvd.html

Go:   name := "Alex"; age := 20
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikxumsju.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hfpthk.cn/Article/details/gtxmxhtoyv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gtpzvrizyp.html

[A03] 常量定义
来源：http://dali.shangyingyoupin.top/Article/details/gtgaontrbi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ydzc1.top/Article/details/gtdzwrnyue.html

PHP:  const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtqmxamdvf.html

JS:   const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gthukbpyob.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtohwwmhlx.html

Java: static final double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtubraorco.html

Go:   const PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gtomzwgfqd.html

Ruby: PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtmobzpzzp.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtqeuzpeca.html

[A04] 判断变量类型
来源：http://dali.aibaodan.cn/Article/details/gtppbeqrec.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.dashuyun.cn/Article/details/gtmlleeqac.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jyoumei.cn/Article/details/gtpzpwvvkh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.316326.xyz/Article/details/gtqlxelfjt.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gtdmbfishx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.andypj.xyz/Article/details/gtwrtzpmzz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.pycfn.com/Article/details/gtftwnpxrg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nanxuanxn.top/Article/details/gtilphdrjr.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj202588.top/Article/details/gtjepcgpdg.html

[A05] 整数除法与取模
来源：http://dali.zycfv.cn/Article/details/gtdsfrfatc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.feifeiyinyue.top/Article/details/gtjharwvzy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtgztugnzm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtrzhfnmlc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtqigoyero.html

Java: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkvigkeu.html

Go:   7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtcixmbqxc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gthkyyqxks.html

C#:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtruqedcmr.html

[A06] 字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gtstarwzij.html

Py:   int("42"); float("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrykouqg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.havefunace.top/Article/details/gttvzwzhsn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daxiang520.top/Article/details/gtcybvsvoj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydgwzoeo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ehwqpu.com/Article/details/gtbtjxzkwg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ybcxt.top/Article/details/gtkkuoipqu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xuetiantiany.cn/Article/details/gtysbdrowe.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuanzx.com/Article/details/gtobvmsueg.html

[A07] 数字转字符串
来源：http://dali.xylfe.cn/Article/details/gtlswefomv.html

Py:   str(42)
来源：http://dali.ivvv.top/Article/details/gtfwqqwmrk.html

PHP:  (string) 42; strval(42)
来源：http://dali.yongpay.top/Article/details/gtghxzpeof.html

JS:   String(42); (42).toString()
来源：http://dali.cdnleiting.top/Article/details/gthlwxzqor.html

TS:   String(42)
来源：http://dali.shzxlz.cn/Article/details/gtkwvcenqy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinqigufen.top/Article/details/gtdhmvlqea.html

Go:   strconv.Itoa(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfrltyha.html

Ruby: 42.to_s
来源：http://dali.yonumen.top/Article/details/gtkhbmchqt.html

C#:   42.ToString()
来源：http://dali.cashguo.top/Article/details/gtknphmefw.html

[A08] 取整与四舍五入
来源：http://dali.zhongyouzk.top/Article/details/gtmnsacrkq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gtouyfjjzq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.haohaochexian.top/Article/details/gtftyycced.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtgxpbpzbl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangdashe.top/Article/details/gtbkglnkev.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtlidddrna.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtoaaujfyd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hfpthk.cn/Article/details/gtdxjtigiz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtvhbupywt.html

[A09] 绝对值与最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtjjvbqndd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.havefunace.top/Article/details/gtqukmvlny.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtihwtujak.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtlusmfwdk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtfaxxfpzg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtqmmtrgxx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xziqi.cn/Article/details/gtpxswacld.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.redwolf501.top/Article/details/gtykqxcqhh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yonumen.top/Article/details/gtamelvqkl.html

[A10] 生成随机数
来源：http://dali.ehwqpu.com/Article/details/gtsizfyjkh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.kuanghao11.cn/Article/details/gttautlzxv.html

PHP:  random_int(1, 100);
来源：http://dali.yuanzhike.top/Article/details/gtkzyjgfcb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.snrcjt.cn/Article/details/gtdzmdjvii.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gtsanjrefq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gogol.net.cn/Article/details/gtbfyuhfzt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xziqi.cn/Article/details/gtvgweisxi.html

Ruby: rand(1..100)
来源：http://dali.kuanghao11.cn/Article/details/gtmzxkwbia.html

C#:   new Random().Next(1, 101)
来源：http://dali.hnxiangtu.top/Article/details/gtbzoqnejg.html

[A11] 条件表达式（三元）
来源：http://dali.9152youxi.cn/Article/details/gtrcgoydpz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cdnleiting.top/Article/details/gtsdcmvczt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtrzminjui.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtkfitgtxk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohqesjrn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gterohzwqu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.iojbl.cn/Article/details/gttmhvjkuj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtxccppwyu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtbcmfened.html

[A12] 字符串插值 / 格式化
来源：http://dali.fzhhl.top/Article/details/gtciztwesp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifhubnkc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinqigfzy.top/Article/details/gtyajiwdgr.html

JS:   `Hello, ${name}!`
来源：http://dali.shangyingyoupin.top/Article/details/gtfsriztcf.html

TS:   `Hello, ${name}!`
来源：http://dali.0kj1m.cn/Article/details/gtlrqnmdnz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.316326.xyz/Article/details/gtncntmgsq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtcqxuhjgc.html

Ruby: "Hello, #{name}!"
来源：http://dali.pycfn.com/Article/details/gtcwujqssb.html

C#:   $"Hello, {name}!"
来源：http://dali.aibaodan.cn/Article/details/gtjbpcevaa.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.birdmap.top/Article/details/gtgqccglbj.html

Py:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gttanzqrnd.html

PHP:  "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtlfmmcqap.html

JS:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtdsvwtvbi.html

TS:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtehkkjvef.html

Java: "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtklrlfsmb.html

Go:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemsweocj.html

Ruby: "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtuggzsubl.html

C#:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtlfglhtuw.html

[A14] 注释写法
来源：http://dali.feifeiyinyue.top/Article/details/gtmthpmygr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.tanke756.top/Article/details/gtwcdwhapp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtmugztnbt.html

JS:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtqafphban.html

TS:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gttibxhoci.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.9152youxi.cn/Article/details/gtmhhyhawk.html

Go:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gtevoognve.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yongpay.top/Article/details/gtagflggfu.html

C#:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtjhgexvjv.html

[A15] 空值判断与默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtwgvketcz.html

Py:   value = data or "默认值"
来源：http://dali.birdmap.top/Article/details/gtkxerqqvz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gthndvhvhs.html

JS:   const value = data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gtputavnga.html

TS:   const value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtkznlmhjx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cqqwz.cn/Article/details/gtzztiryqx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ehwqpu.com/Article/details/gtunvrcucw.html

Ruby: value = data || "默认值"
来源：http://dali.yvedp.cn/Article/details/gtvendbcww.html

C#:   var value = data ?? "默认值";
来源：http://dali.snrcjt.cn/Article/details/gtqgxchryp.html

[A16] 真假值判断规则
来源：http://dali.yj20258.top/Article/details/gtklmxndbl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.birdmap.top/Article/details/gtofjpizok.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhongyouzk.top/Article/details/gtekiyznfg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.fzhhl.top/Article/details/gtkodwanql.html

TS:   if (!x) {}
来源：http://dali.xziqi.cn/Article/details/gtderrdbon.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj202588.top/Article/details/gtvwjntnuz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.birdmap.top/Article/details/gtyomlezvv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.dianchejie.cn/Article/details/gtkgfcemhu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtwxxgusri.html

[A17] 位运算
来源：http://dali.iojbl.cn/Article/details/gttxzeifyv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtimznntgm.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvokrdjq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtaseoiqmd.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtifndginr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtnidwvrhd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtivnqgtno.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtubzxurgm.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtwaogvxaj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.haohaochexian.top/Article/details/gtmyzbjeth.html

Py:   ord("A"); chr(65)
来源：http://dali.jqgfzy.top/Article/details/gtgqyboggt.html

PHP:  ord("A"); chr(65)
来源：http://dali.havefunace.top/Article/details/gttciaupsd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ybcxt.top/Article/details/gtcivjaxuu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gtdlubutla.html

Java: (int) 'A'; (char) 65
来源：http://dali.aizwys.cn/Article/details/gtaeflfasc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hysaishi.cn/Article/details/gtbueziguv.html

Ruby: "A".ord; 65.chr
来源：http://dali.gotoacloud.top/Article/details/gtweivmtfq.html

C#:   (int)'A'; (char)65
来源：http://dali.shanyushiyangtech.top/Article/details/gtceskddop.html

[A19] 交换两个变量
来源：http://dali.birdmap.top/Article/details/gtknydbnqa.html

Py:   a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gtcjymncpp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yuanzhike.top/Article/details/gthmdcdjqx.html

JS:   [a, b] = [b, a];
来源：http://dali.zhixingplan.top/Article/details/gtentrgzyg.html

TS:   [a, b] = [b, a];
来源：http://dali.gotoacloud.top/Article/details/gtlgcofaat.html

Java: int t = a; a = b; b = t;
来源：http://dali.c1oappe.top/Article/details/gtzinnoxtd.html

Go:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gtyjukwgqi.html

Ruby: a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gtwewwzalh.html

C#:   (a, b) = (b, a);
来源：http://dali.guowangkeji.top/Article/details/gtjtnargst.html

[A20] 读取标准输入
来源：http://dali.wangdashe.top/Article/details/gtofeyiefv.html

Py:   name = input("请输入：")
来源：http://dali.0kj1m.cn/Article/details/gtpciqiwue.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipvfirkx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gaohongyu789.top/Article/details/gtclqwqdxs.html

TS:   // Node.js：readline 模块
来源：http://dali.jinqigufen.top/Article/details/gtvlbvzdhm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacgdepll.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ydzc1.top/Article/details/gtkvugdrnh.html

Ruby: gets.chomp
来源：http://dali.xinyue.icu/Article/details/gttoiyywjs.html

C#:   Console.ReadLine();
来源：http://dali.nanxinkj.top/Article/details/gtjxkdmarp.html

[A21] 保留指定小数位输出
来源：http://dali.nanxuanxn.top/Article/details/gtidgwrrcg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxinkj.top/Article/details/gtwdcjkxeq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gtrfshihit.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtgzyhzrlf.html

TS:   (3.14159).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gtnklftdie.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gttiyrvfho.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtctqqdrix.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtstbhnkyo.html

C#:   3.14159.ToString("F2")
来源：http://dali.0kj1m.cn/Article/details/gtbzbytusz.html

[A22] 获取字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwrzpsoh.html

Py:   len(s)
来源：http://dali.guannengcc.top/Article/details/gtwecbaycx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yuxming.cn/Article/details/gtyytovhcs.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cheryme.top/Article/details/gtfohfoweb.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gtklxrrgyu.html

Java: s.length()
来源：http://dali.yuanzhike.top/Article/details/gtgtjaasvo.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtsazkaqox.html

Ruby: s.length
来源：http://dali.jqgfzy.top/Article/details/gtuhbeeugq.html

C#:   s.Length
来源：http://dali.xylfe.cn/Article/details/gtlopsajjw.html

[A23] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtywjdnltv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctuqqdtb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuxming.cn/Article/details/gtlgybxwah.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gtkkhotzrc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gttlvmzdud.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtosjtgyno.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.birdmap.top/Article/details/gtayaundew.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtpumdxfbd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenlongwang.top/Article/details/gttowivsyq.html

[A24] 去除首尾空白
来源：http://dali.cqqwz.cn/Article/details/gtnmuinwlw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.aibaodan.cn/Article/details/gtgbbcitul.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.mhx1999.top/Article/details/gtzhtmrjsy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtfiltutnd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jianghu66.top/Article/details/gtboeewclx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sufxvd.cn/Article/details/gtxqdfkckl.html

Go:   strings.TrimSpace(s)
来源：http://dali.tianlin.xyz/Article/details/gtrkgvewdr.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jqgufenzy.top/Article/details/gtlcbnbieq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangdashe.top/Article/details/gtiovsdrrp.html

[A25] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gtpexruzmb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.havefunace.top/Article/details/gtmtqhujzy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sufxvd.cn/Article/details/gtuxqasqin.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daxiang520.top/Article/details/gtdfzkffbf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pycfn.com/Article/details/gtqqzjqrys.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xylfe.cn/Article/details/gtemesnhqf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gtpdvrxuve.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhoulong.xyz/Article/details/gtekjyomlx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpexvxra.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gtfypiynls.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgfzy.top/Article/details/gtriliaxss.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shzxlz.cn/Article/details/gtmkukcmqh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hammf.cn/Article/details/gtwrcsuhpd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jlsjyb.cn/Article/details/gtaysynkol.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hysaishi.cn/Article/details/gtylalkfbl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.mhx1999.top/Article/details/gtvnetlyyi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gzhubu.top/Article/details/gtalhkxslr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gtuqqzpemc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtctckaqfx.html

B. 流程控制
来源：http://dali.zhongyouzk.top/Article/details/gtjqcgezoj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtynhimmbv.html

[B01] 条件判断 if / else
来源：http://dali.pycfn.com/Article/details/gthirzexdc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.pengpengdd.cyou/Article/details/gtaukkazmu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sweek.top/Article/details/gtvlmimdwa.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtjkevrnsf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtvmcsdcyz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtskfjakrn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tanke756.top/Article/details/gtiywnjjma.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ydzc1.top/Article/details/gtvvxzwjai.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtvzlhrtqv.html

[B02] 多分支 else if / elif
来源：http://dali.smart0.xyz/Article/details/gtmyeukguh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.c1oappe.top/Article/details/gtjnohcejt.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigfzy.top/Article/details/gtuyhmeyag.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gtfegfsprf.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtxkbjkntx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtnbzjdkaw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jqgufenzy.top/Article/details/gtvudmndyw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zycfv.cn/Article/details/gtvtjrlzmy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gtglfcwicn.html

[B03] switch / match / case
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyzxejar.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.redwolf501.top/Article/details/gtnirjvdfg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtdfoockhb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gtnillhdcl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gtfaztqhfd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gttyhdbvaf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gtigysdxik.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xuetiantiany.cn/Article/details/gtiyatsmgt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.havefunace.top/Article/details/gtwddkmlir.html

[B04] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtischxvwk.html

Py:   for i in range(10): print(i)
来源：http://dali.xinyue.icu/Article/details/gtrzvwkcxz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xuanzx.com/Article/details/gtgnhqixhg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtfqsuuqta.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gtcggecbkl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sysykeji.top/Article/details/gtciepdjzh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gaohongyu789.top/Article/details/gtysientni.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yongpay.top/Article/details/gtoweajtcv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sweek.top/Article/details/gtrzmkplnb.html

[B05] 遍历数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtdoltyuih.html

Py:   for item in arr: print(item)
来源：http://dali.meibo888.top/Article/details/gtxmjzdswg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gtpwvwhhsh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdblvkrl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gtbpwfgtkp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yanxiufei.cn/Article/details/gthadnooaq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenzaomai.com/Article/details/gtmzlvxajn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdolqukfg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daxiang520.top/Article/details/gtfplgjnww.html

[B06] 遍历字典 / 对象
来源：http://dali.yuanzhike.top/Article/details/gtplzkbbdf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sysykeji.top/Article/details/gtudarvgjw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenlongwang.top/Article/details/gtypnyjfds.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gthsythigj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gtueeejkyh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.guannengcc.top/Article/details/gtbskksegh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ydzc1.top/Article/details/gttqigpvwo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.haohaochexian.top/Article/details/gtrnsbveal.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrdwneczn.html

[B07] while 循环
来源：http://dali.9152youxi.cn/Article/details/gtpqwzlsig.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjqybogz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xylfe.cn/Article/details/gtfukqigyn.html

JS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtatsdlbmp.html

TS:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqpntlnkz.html

Java: while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtbhbbdpun.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhixingplan.top/Article/details/gtusqcmjjk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xziqi.cn/Article/details/gtuqkkqynx.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gttqnqfstz.html

[B08] do-while（至少执行一次）
来源：http://dali.jianghu66.top/Article/details/gtsnhdaity.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.fengsongda.top/Article/details/gtofrznumk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangdashe.top/Article/details/gtbbximoxz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtugwcfofq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtunchqfpu.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtizeirhzu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtxfcfjfyr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.bjfxy.top/Article/details/gttyhvzflz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gttlthwwfu.html


<!-- 参考信息 -->