代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.tian-w.cn/Article/details/gtdyvnydxc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cucudq.cn/Article/details/gtixmnufft.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangdashe.top/Article/details/gtwjzsbfvg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yueranfly.top/Article/details/gtybmlqlhn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yonumen.top/Article/details/gttzxmjjkz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.guowangkeji.top/Article/details/gtdgefczae.html

Go:   name := "Alex"; age := 20
来源：http://dali.fengsongda.top/Article/details/gtzcemnxps.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tian-w.cn/Article/details/gtfbhpnfeu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gtozxukgby.html

[A03] 常量定义
来源：http://dali.xuetiantiany.cn/Article/details/gtswzhsrem.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ppjwa.cn/Article/details/gtpkwzreqx.html

PHP:  const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtonzrwnoq.html

JS:   const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtoudhrtlv.html

TS:   const PI: number = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtczsvpdvv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtgdtiyuvb.html

Go:   const PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gtetgkbkru.html

Ruby: PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gtqpbiiomo.html

C#:   const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtmhiasjwq.html

[A04] 判断变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtxihcahpr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.quarkkingdee.top/Article/details/gtybcwugyz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovuboisg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hongshengwenyu.top/Article/details/gteabwtmuv.html

TS:   typeof x; x instanceof Date
来源：http://dali.yanxiufei.cn/Article/details/gtmmityfky.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zycfv.cn/Article/details/gtrkenuncl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsgvcllk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.kuanghao11.cn/Article/details/gtozorcmhl.html

C#:   x.GetType().Name; x is int
来源：http://dali.nanxinkj.top/Article/details/gtjxwctwwi.html

[A05] 整数除法与取模
来源：http://dali.bjfxy.top/Article/details/gtydararpm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cdnleiting.top/Article/details/gtaqsdwrvt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtpuiqkkhr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtjpnlqrxo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gtfourzwsr.html

Java: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtfdeayhsg.html

Go:   7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtkyhqdacj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtnxxuheiy.html

C#:   7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtvqytuqhw.html

[A06] 字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gtxzdiyvqf.html

Py:   int("42"); float("3.14")
来源：http://dali.sysykeji.top/Article/details/gtaoykmjip.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangshuangyany.cn/Article/details/gtgmxxmsbf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gtmbjtsbtk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jiagoushi.top/Article/details/gttklnjbuh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.dashuyun.cn/Article/details/gtbjjctrin.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhoulong.xyz/Article/details/gtjllhafaw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sxryk.cn/Article/details/gtghofulfw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gtlaxrnuac.html

[A07] 数字转字符串
来源：http://dali.daxiang520.top/Article/details/gttpxcrocc.html

Py:   str(42)
来源：http://dali.ivvv.top/Article/details/gtvtwqvhoa.html

PHP:  (string) 42; strval(42)
来源：http://dali.cucudq.cn/Article/details/gtuquorzjl.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gtdofiycas.html

TS:   String(42)
来源：http://dali.yueranfly.top/Article/details/gtcbadturf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yonumen.top/Article/details/gtwdxmuovh.html

Go:   strconv.Itoa(42)
来源：http://dali.tanke756.top/Article/details/gtomdvlrik.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gtgqqezbon.html

C#:   42.ToString()
来源：http://dali.cashguo.top/Article/details/gtsxjnnavi.html

[A08] 取整与四舍五入
来源：http://dali.cqqwz.cn/Article/details/gtgqxgrxvn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtcztfchbv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gthwlxitbv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtcsnndjve.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xinyue.icu/Article/details/gtjxgmedcz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtlhevkhko.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtatezrwmi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xinyue.icu/Article/details/gtuxdovzld.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtfrqtcyrd.html

[A09] 绝对值与最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtisebjwbv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yongpay.top/Article/details/gtycnmmgze.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtzcoatyhf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtdbsoiarl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtiixfhfsl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtzsabnopv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nanxuanxn.top/Article/details/gtgouiinpa.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.9152youxi.cn/Article/details/gtxfzmkzrq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtjzvcikoc.html

[A10] 生成随机数
来源：http://dali.cashguo.top/Article/details/gtqewolmix.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cashguo.top/Article/details/gtznmeotta.html

PHP:  random_int(1, 100);
来源：http://dali.tianlin.xyz/Article/details/gterhuszrf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xylfe.cn/Article/details/gtshnfvecg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gtnqzpcqvh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj202588.top/Article/details/gtpiajotwe.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shanyushiyangtech.top/Article/details/gteodlohov.html

Ruby: rand(1..100)
来源：http://dali.0kj1m.cn/Article/details/gtzbpqqmkh.html

C#:   new Random().Next(1, 101)
来源：http://dali.pengpengdd.cyou/Article/details/gtvgaoicgs.html

[A11] 条件表达式（三元）
来源：http://dali.guannengcc.top/Article/details/gtcjyzklif.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.dianchejie.cn/Article/details/gtitqomgxa.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtxjvioemc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gttnarcrtv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtnbbrrddn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gttncloswo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.cdnleiting.top/Article/details/gtgrkcybgt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtxdlwwjzs.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gtrxhyixvy.html

[A12] 字符串插值 / 格式化
来源：http://dali.gzhubu.top/Article/details/gtmvdoumpk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jlsjyb.cn/Article/details/gtvqhhneok.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgwislbh.html

JS:   `Hello, ${name}!`
来源：http://dali.guowangkeji.top/Article/details/gtetpztxuj.html

TS:   `Hello, ${name}!`
来源：http://dali.quarkkingdee.top/Article/details/gtmwevrgwb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yj202588.top/Article/details/gtcsedddup.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinqigfzy.top/Article/details/gtjihaisfk.html

Ruby: "Hello, #{name}!"
来源：http://dali.yuanzhike.top/Article/details/gtngwgcnjc.html

C#:   $"Hello, {name}!"
来源：http://dali.ehwqpu.com/Article/details/gtgrlvunsx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hnqzz.top/Article/details/gtotyzgplx.html

Py:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtdrwdzral.html

PHP:  "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtzafpsxvh.html

JS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtzznjpjjo.html

TS:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtxdmoimbk.html

Java: "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfqonuiq.html

Go:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtbgszgyyu.html

Ruby: "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtayriukxw.html

C#:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtdwisdpjg.html

[A14] 注释写法
来源：http://dali.cheryme.top/Article/details/gtmtdstaqs.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.0kj1m.cn/Article/details/gttzpqszgm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gtvcrvvpfy.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtzetgqenw.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtruakffwg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xuetiantiany.cn/Article/details/gtdegpbrqf.html

Go:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gtbcjdqylo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhoulong.xyz/Article/details/gtsrgcmjjz.html

C#:   // 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gtiexpklby.html

[A15] 空值判断与默认值
来源：http://dali.guannengcc.top/Article/details/gtkjyulzye.html

Py:   value = data or "默认值"
来源：http://dali.guowangkeji.top/Article/details/gtyfowatss.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtacbbtdjx.html

JS:   const value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtdvrbdjwq.html

TS:   const value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtvrzhlehx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsljxigk.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.dianchejie.cn/Article/details/gtwqkjugll.html

Ruby: value = data || "默认值"
来源：http://dali.sysykeji.top/Article/details/gttsikkvln.html

C#:   var value = data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gtqwcssezb.html

[A16] 真假值判断规则
来源：http://dali.gaohongyu789.top/Article/details/gtvdbsyqyv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.guowangkeji.top/Article/details/gttkjktmxu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pengpengdd.cyou/Article/details/gthrdelyyv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cashguo.top/Article/details/gtltmzfjpt.html

TS:   if (!x) {}
来源：http://dali.dianchejie.cn/Article/details/gtnwtarzat.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgbdizcd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.iojbl.cn/Article/details/gtvnhztyrk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gaohongyu789.top/Article/details/gtlsljrikq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtinhowhjj.html

[A17] 位运算
来源：http://dali.jinqigfzy.top/Article/details/gthhbdnhvf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtsrqdvzoj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shzxlz.cn/Article/details/gtpnpcqscm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtpwebyqbh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtzrlmqzaw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gttqsooznj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiprlozd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtzjncjrnl.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtcytoznqm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xuetiantiany.cn/Article/details/gtqobcfwbn.html

Py:   ord("A"); chr(65)
来源：http://dali.xylfe.cn/Article/details/gtfasbmoaf.html

PHP:  ord("A"); chr(65)
来源：http://dali.nanxinkj.top/Article/details/gtzbxdgxip.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.aibaodan.cn/Article/details/gtcaffbfrs.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zdqjudy.top/Article/details/gtrtroyuky.html

Java: (int) 'A'; (char) 65
来源：http://dali.cucudq.cn/Article/details/gtdbosoiel.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.dashuyun.cn/Article/details/gtdiofdsak.html

Ruby: "A".ord; 65.chr
来源：http://dali.quarkkingdee.top/Article/details/gtbtvwbwnm.html

C#:   (int)'A'; (char)65
来源：http://dali.gzhubu.top/Article/details/gtloqwsbhq.html

[A19] 交换两个变量
来源：http://dali.jlsjyb.cn/Article/details/gtsmopnzyi.html

Py:   a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gtsarndiaq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yanxiufei.cn/Article/details/gtokvbcfqe.html

JS:   [a, b] = [b, a];
来源：http://dali.zhiwuduotai.top/Article/details/gtuszobngr.html

TS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gtkhzdvwki.html

Java: int t = a; a = b; b = t;
来源：http://dali.fzhhl.top/Article/details/gtsbzgyuoj.html

Go:   a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gtkadvzkdq.html

Ruby: a, b = b, a
来源：http://dali.ivvv.top/Article/details/gtwxnnzomz.html

C#:   (a, b) = (b, a);
来源：http://dali.snrcjt.cn/Article/details/gtmpyibypj.html

[A20] 读取标准输入
来源：http://dali.hywenlv.cn/Article/details/gttvuvxsxe.html

Py:   name = input("请输入：")
来源：http://dali.xziqi.cn/Article/details/gtzacwusym.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yonumen.top/Article/details/gtbyayzpkt.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hnqzz.top/Article/details/gtixpjcbid.html

TS:   // Node.js：readline 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwhwrzgw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yuxming.cn/Article/details/gtvlyofpfv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yueranfly.top/Article/details/gtllznqsbp.html

Ruby: gets.chomp
来源：http://dali.sxryk.cn/Article/details/gtcyfzcebh.html

C#:   Console.ReadLine();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkftdkvhm.html

[A21] 保留指定小数位输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqjjzezz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xziqi.cn/Article/details/gtmfzhxflw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtyyvlhrrm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxpptqsc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtnlbkaaip.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtckgbffgl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gtafjtnpdi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gthbujrlgm.html

C#:   3.14159.ToString("F2")
来源：http://dali.0kj1m.cn/Article/details/gttwvpwgis.html

[A22] 获取字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtwabnsxpz.html

Py:   len(s)
来源：http://dali.redwolf501.top/Article/details/gtlwdhduex.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ydzc1.top/Article/details/gtpveuvdzl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.bjfxy.top/Article/details/gtozkhjcfg.html

TS:   s.length
来源：http://dali.quarkkingdee.top/Article/details/gtaxqwujvh.html

Java: s.length()
来源：http://dali.hysaishi.cn/Article/details/gtuhvpdqlf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yongpay.top/Article/details/gtghcgxmji.html

Ruby: s.length
来源：http://dali.xinyue.icu/Article/details/gtqgkasxmd.html

C#:   s.Length
来源：http://dali.fzhhl.top/Article/details/gtkadfyakd.html

[A23] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtqfxnnufx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtuymjsjki.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.andypj.xyz/Article/details/gtwvvjkzcg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gtnmocsxpz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gtmtlqevgj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtclmsmfrj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cheryme.top/Article/details/gtimnvqknd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtbszigbxz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yuanzhike.top/Article/details/gtlhddtobh.html

[A24] 去除首尾空白
来源：http://dali.jinqigfzy.top/Article/details/gtcxujkxxz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gotoacloud.top/Article/details/gthjadpjcx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhengqikj.top/Article/details/gtafxjnsil.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gtwfbfksmt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhengqikj.top/Article/details/gtpvgjaegt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjhvxsob.html

Go:   strings.TrimSpace(s)
来源：http://dali.hammf.cn/Article/details/gtduqbxkhd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.redwolf501.top/Article/details/gtuxdwjugc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtoiujstcn.html

[A25] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gttsumitav.html

Py:   s1 == s2; s1 != s2
来源：http://dali.9152youxi.cn/Article/details/gtkmfqihwo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtmiqctucv.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pycfn.com/Article/details/gtdtmpuidw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jianghu66.top/Article/details/gtbdzxrzgk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhoulong.xyz/Article/details/gtbgphdvae.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gtbrcbeigj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.iojbl.cn/Article/details/gtobjpyujp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhvqncda.html

[A26] 类型转换总览
来源：http://dali.kuanghao11.cn/Article/details/gthmdhwihf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ehwqpu.com/Article/details/gtcjtmkdod.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gzhubu.top/Article/details/gtoluuhahj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jianghu66.top/Article/details/gtsoabjaje.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258.top/Article/details/gtrdcgtgqe.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.andypj.xyz/Article/details/gtkhrcwzfx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.quarkkingdee.top/Article/details/gttkqaiabq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.daria6918.cn/Article/details/gtjyrudqlt.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hysaishi.cn/Article/details/gtevrpoiyw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlsbqlco.html

B. 流程控制
来源：http://dali.shangyingyoupin.top/Article/details/gtgaysduvr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtcgvjdiyl.html

[B01] 条件判断 if / else
来源：http://dali.hammf.cn/Article/details/gteqqnjydj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tanke756.top/Article/details/gtxejnssur.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtboudyfxg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtqzziucly.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtkqjtobho.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtcbvcnknx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinghuilouyu.cn/Article/details/gthpsutnds.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nwbrower.top/Article/details/gtylryccmd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gthrchpnud.html

[B02] 多分支 else if / elif
来源：http://dali.jianghu66.top/Article/details/gtipruybdi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cashguo.top/Article/details/gtgfwhrcnl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sweek.top/Article/details/gtzmwvoqhl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtyksqbkre.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtluybequz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gttfgarhwz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvjbcmcy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnxiangtu.top/Article/details/gtjfozomsw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtxnmfaqzo.html

[B03] switch / match / case
来源：http://dali.aizwys.cn/Article/details/gtlzqavvqw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.c1oappe.top/Article/details/gtiftasxxj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbinsjpta.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtqvwwvsst.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspjzcsld.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtipbfilni.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtbbfbrraa.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cdnleiting.top/Article/details/gthmyrgeza.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtsyjypmpn.html

[B04] for 计数循环
来源：http://dali.sweek.top/Article/details/gtwuriookc.html

Py:   for i in range(10): print(i)
来源：http://dali.jianghu66.top/Article/details/gtlctbhkib.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sysykeji.top/Article/details/gtqhkgwwjh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yonumen.top/Article/details/gtosmozsms.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.andypj.xyz/Article/details/gtbkgxdmwy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtxdgtlpjj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ybcxt.top/Article/details/gtidgxkbck.html

Ruby: 10.times { |i| puts i }
来源：http://dali.vqdsnc.cn/Article/details/gttrjvwvvx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xziqi.cn/Article/details/gtbbgxmttz.html

[B05] 遍历数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtckciksoy.html

Py:   for item in arr: print(item)
来源：http://dali.xinyue.icu/Article/details/gthajzyxyl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj202588.top/Article/details/gtkojacicr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtvtiacynk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtvqgkpskf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hywenlv.cn/Article/details/gtjtervlfl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xylfe.cn/Article/details/gtwtfnevbi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.316326.xyz/Article/details/gtgeehoohu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cqqwz.cn/Article/details/gtnbooeijg.html

[B06] 遍历字典 / 对象
来源：http://dali.xylfe.cn/Article/details/gtiemanltz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gttcgbcazs.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yonumen.top/Article/details/gtjdbreinr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamlnikuo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ybcxt.top/Article/details/gtgrdolmgf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcthkdtbx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.svipenyu.cn/Article/details/gtiexvluaz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sufxvd.cn/Article/details/gtnqlpfnhs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gogol.net.cn/Article/details/gtffzgzmgn.html

[B07] while 循环
来源：http://dali.ehwqpu.com/Article/details/gtemcymslu.html

Py:   while i < 10: i += 1
来源：http://dali.havefunace.top/Article/details/gtnpdwvxay.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtbgyksann.html

JS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtaafxzbeq.html

TS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtpudwilwh.html

Java: while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtyonspilr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gzhubu.top/Article/details/gtwciusjqn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gtjtpsoiwn.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtrsjcshdd.html

[B08] do-while（至少执行一次）
来源：http://dali.xuetiantiany.cn/Article/details/gtjuvxmmvp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.quarkkingdee.top/Article/details/gtroxkeiwu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtzxhstbbz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtkccpyrso.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtzqpwgmfk.html

Java: do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtxqljveew.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dashuyun.cn/Article/details/gtshuchbwl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gtounemznf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtxqwiaexs.html


<!-- 参考信息 -->