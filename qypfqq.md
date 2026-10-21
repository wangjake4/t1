代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.fengsongda.top/Article/details/gtvingskky.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.c1oappe.top/Article/details/gtqfhhnmhn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtmaunuger.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtgjopyesa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cdnleiting.top/Article/details/gtwwbkawir.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aibaodan.cn/Article/details/gtthfhoejg.html

Go:   name := "Alex"; age := 20
来源：http://dali.xylfe.cn/Article/details/gtfcgkdtde.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenzaomai.com/Article/details/gtbngkxmci.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtvmzyixeb.html

[A03] 常量定义
来源：http://dali.jqgufenzy.top/Article/details/gtukkmunut.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yj202588.top/Article/details/gttfqgzclj.html

PHP:  const PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtykzqlniw.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtbjvwbhjz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtzyluvybm.html

Java: static final double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gttzddgywj.html

Go:   const PI = 3.14159
来源：http://dali.xylfe.cn/Article/details/gtkikskgvw.html

Ruby: PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoljsrgy.html

C#:   const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gthrozctph.html

[A04] 判断变量类型
来源：http://dali.hywenlv.cn/Article/details/gtoilkpomr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jiagoushi.top/Article/details/gtrrfeicbm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yvedp.cn/Article/details/gtdrtfqyot.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cashguo.top/Article/details/gthpkbytld.html

TS:   typeof x; x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gtrujtehjd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj202588.top/Article/details/gtycgybykr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dianchejie.cn/Article/details/gtoaxvarqi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shuidangran.top/Article/details/gtgcdhpkgr.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj20258888.top/Article/details/gtygzgxrzw.html

[A05] 整数除法与取模
来源：http://dali.gogol.net.cn/Article/details/gtzpmbsohd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenjidiqi.icu/Article/details/gtyilvojsm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtyrdtdyjq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtxfbyagnu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gteiqsqslv.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtldykkdws.html

Go:   7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtlyuxgdok.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtbovxhwsz.html

C#:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtvihdfttb.html

[A06] 字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtljdgafml.html

Py:   int("42"); float("3.14")
来源：http://dali.yvedp.cn/Article/details/gtecmsvals.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tanke756.top/Article/details/gtqlgoscqp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gtgdhbwhcg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gtyhppzebk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aizwys.cn/Article/details/gtincvrtcy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guannengcc.top/Article/details/gthckergop.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.kuanghao11.cn/Article/details/gtcttwiarh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sxryk.cn/Article/details/gtlkeqsfru.html

[A07] 数字转字符串
来源：http://dali.yj20258.top/Article/details/gtmbdmworj.html

Py:   str(42)
来源：http://dali.jinqigufen.top/Article/details/gtgqehyjcp.html

PHP:  (string) 42; strval(42)
来源：http://dali.aibaodan.cn/Article/details/gtnsftpdvm.html

JS:   String(42); (42).toString()
来源：http://dali.zycfv.cn/Article/details/gtldphuwxc.html

TS:   String(42)
来源：http://dali.tianlin.xyz/Article/details/gtogrvsrrz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinqigfzy.top/Article/details/gtzjroeove.html

Go:   strconv.Itoa(42)
来源：http://dali.316326.xyz/Article/details/gtvyouavce.html

Ruby: 42.to_s
来源：http://dali.hysaishi.cn/Article/details/gtbkendttj.html

C#:   42.ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gterzcdeyi.html

[A08] 取整与四舍五入
来源：http://dali.tianlin.xyz/Article/details/gtegcqkrjh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gtzmffrgdz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.316326.xyz/Article/details/gtwhbzwzgr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtjbcuzmah.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenzaomai.com/Article/details/gtqecltocy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gtjmfxxbdk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gtwlrwmnrx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmmjlplo.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtnazsuzfa.html

[A09] 绝对值与最大最小值
来源：http://dali.dianchejie.cn/Article/details/gthfoguyqj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtieykkzag.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoroolsj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtdfdhysrq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtstqriskq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtalriuecr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xuetiantiany.cn/Article/details/gtcnjjzbjp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ydzc1.top/Article/details/gtlwlteaik.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtmehlrhcq.html

[A10] 生成随机数
来源：http://dali.zdqjudy.top/Article/details/gtwbzpknvi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gtngaxiqgk.html

PHP:  random_int(1, 100);
来源：http://dali.andypj.xyz/Article/details/gtzdevukom.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.c1oappe.top/Article/details/gtgiodtpby.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnqzz.top/Article/details/gtmypzarut.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gogol.net.cn/Article/details/gtcbbhvqaa.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hywenlv.cn/Article/details/gtwgomrzhv.html

Ruby: rand(1..100)
来源：http://dali.ybcxt.top/Article/details/gtgnovipsx.html

C#:   new Random().Next(1, 101)
来源：http://dali.tanke756.top/Article/details/gttcxkpcem.html

[A11] 条件表达式（三元）
来源：http://dali.chenzaomai.com/Article/details/gtlqeiwtwz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqazdkdq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gtqcgbbews.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuizulksj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gtopdkzxkd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdnvtvre.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jianghu66.top/Article/details/gtmhhpdboz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtzeewawsn.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gtymivmrwu.html

[A12] 字符串插值 / 格式化
来源：http://dali.sysykeji.top/Article/details/gtllkpqobj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hfpthk.cn/Article/details/gtsbumpnnb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jqgufenzy.top/Article/details/gtshwuylxl.html

JS:   `Hello, ${name}!`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwydajtge.html

TS:   `Hello, ${name}!`
来源：http://dali.dianchejie.cn/Article/details/gtkhuktnge.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gogol.net.cn/Article/details/gtqaxhsniq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.daxiang520.top/Article/details/gtbnkgupes.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenjidiqi.icu/Article/details/gtjzbebyow.html

C#:   $"Hello, {name}!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvvnfstb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.fengsongda.top/Article/details/gtnyhjkmjt.html

Py:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtizzdjmod.html

PHP:  "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtojchfvia.html

JS:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtjyqvervx.html

TS:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtbnorpfws.html

Java: "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtgbvzmryd.html

Go:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtilwfsict.html

Ruby: "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtzgmmlurp.html

C#:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtxjfbhwty.html

[A14] 注释写法
来源：http://dali.feifeiyinyue.top/Article/details/gtxjxnbuyd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gaohongyu789.top/Article/details/gtffroywcw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gtpnaqzudc.html

JS:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gttuykgcbj.html

TS:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtusbsjuyt.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xziqi.cn/Article/details/gtwrabgznu.html

Go:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtkbiztqmb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.meibo888.top/Article/details/gtumsumpfj.html

C#:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtdiqcvrdx.html

[A15] 空值判断与默认值
来源：http://dali.zhixingplan.top/Article/details/gtxleeysqz.html

Py:   value = data or "默认值"
来源：http://dali.fzhhl.top/Article/details/gtlgjjyska.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gtalepemcz.html

JS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtsnkcdwxm.html

TS:   const value = data ?? "默认值";
来源：http://dali.hammf.cn/Article/details/gtmvhdzotw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jianghu66.top/Article/details/gtzzrxrocq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hongshengwenyu.top/Article/details/gtyqlchgfq.html

Ruby: value = data || "默认值"
来源：http://dali.cqqwz.cn/Article/details/gterdhiylw.html

C#:   var value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gtcnoijwrz.html

[A16] 真假值判断规则
来源：http://dali.cqqwz.cn/Article/details/gtysosegzu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sweek.top/Article/details/gtkqwyuved.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj202588.top/Article/details/gtretscrkg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.fzhhl.top/Article/details/gtuaddwthi.html

TS:   if (!x) {}
来源：http://dali.zhengqikj.top/Article/details/gtfwtvtxmf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.fengsongda.top/Article/details/gtnkfqsqwd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ydzc1.top/Article/details/gttekkcrhi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrfzpxsp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.dashuyun.cn/Article/details/gthtpabror.html

[A17] 位运算
来源：http://dali.chenlongwang.top/Article/details/gtbticlmnc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtiqwbktvh.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.smart0.xyz/Article/details/gtivedzqbl.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtfvtwgaav.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtccirvyva.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gtpflwkuvu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtlatccuir.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtiimwprey.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtodftagmy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gzhubu.top/Article/details/gtksfrapsw.html

Py:   ord("A"); chr(65)
来源：http://dali.daria6918.cn/Article/details/gtyaaqrdrk.html

PHP:  ord("A"); chr(65)
来源：http://dali.kuanghao11.cn/Article/details/gtoqilqdbm.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shzxlz.cn/Article/details/gthsicelir.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gtcucikdwk.html

Java: (int) 'A'; (char) 65
来源：http://dali.hongshengwenyu.top/Article/details/gtfjklshln.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yj20258.top/Article/details/gtbgpqnxbt.html

Ruby: "A".ord; 65.chr
来源：http://dali.jiagoushi.top/Article/details/gtkxtgszld.html

C#:   (int)'A'; (char)65
来源：http://dali.316326.xyz/Article/details/gtoqscyltz.html

[A19] 交换两个变量
来源：http://dali.sweek.top/Article/details/gtmupbrrgs.html

Py:   a, b = b, a
来源：http://dali.iojbl.cn/Article/details/gtvswfqwfa.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yj202588.top/Article/details/gtxurxzbqs.html

JS:   [a, b] = [b, a];
来源：http://dali.ybcxt.top/Article/details/gttwtqvbuk.html

TS:   [a, b] = [b, a];
来源：http://dali.ybcxt.top/Article/details/gtzdycnbrp.html

Java: int t = a; a = b; b = t;
来源：http://dali.yueranfly.top/Article/details/gtmyceojey.html

Go:   a, b = b, a
来源：http://dali.quarkkingdee.top/Article/details/gtuifohiuh.html

Ruby: a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtbrxvnzzl.html

C#:   (a, b) = (b, a);
来源：http://dali.cdnleiting.top/Article/details/gtfbmeiwxq.html

[A20] 读取标准输入
来源：http://dali.jyoumei.cn/Article/details/gtmbejqdih.html

Py:   name = input("请输入：")
来源：http://dali.daria6918.cn/Article/details/gtezooqahe.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.dianchejie.cn/Article/details/gtamjtyirj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hongshengwenyu.top/Article/details/gtccgarwmy.html

TS:   // Node.js：readline 模块
来源：http://dali.yueranfly.top/Article/details/gtrknxdocq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gaohongyu789.top/Article/details/gtarbrfjkx.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gogol.net.cn/Article/details/gtqxsyxagq.html

Ruby: gets.chomp
来源：http://dali.pycfn.com/Article/details/gtyfvpiekx.html

C#:   Console.ReadLine();
来源：http://dali.hnqzz.top/Article/details/gtmhlhewma.html

[A21] 保留指定小数位输出
来源：http://dali.cheryme.top/Article/details/gtbfxooysr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hysaishi.cn/Article/details/gtsykjtifs.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtgvbqnylp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtxqybtfwx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtfbvwwuyq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtpjguthgm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gthhscmwin.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtssivmgkt.html

C#:   3.14159.ToString("F2")
来源：http://dali.jqgufenzy.top/Article/details/gtwqjorsjc.html

[A22] 获取字符串长度
来源：http://dali.ydzc1.top/Article/details/gtfzuhphem.html

Py:   len(s)
来源：http://dali.cashguo.top/Article/details/gteibygajn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenlongwang.top/Article/details/gtrbudebef.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yonumen.top/Article/details/gtjauwjfmc.html

TS:   s.length
来源：http://dali.vqdsnc.cn/Article/details/gtvbwmmoyd.html

Java: s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuoxoyoh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtliwnthrb.html

Ruby: s.length
来源：http://dali.xuanzx.com/Article/details/gtyfgaqzbi.html

C#:   s.Length
来源：http://dali.9152youxi.cn/Article/details/gtwiuggytk.html

[A23] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtxnogxpvh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tian-w.cn/Article/details/gtagfskejw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jianghu66.top/Article/details/gtkxyijvdy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.andypj.xyz/Article/details/gtxycwabad.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gtqrnerfcj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gtlbaksbbn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sufxvd.cn/Article/details/gtjiiprmrq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.316326.xyz/Article/details/gtbbiyydya.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.tanke756.top/Article/details/gteqinrkpe.html

[A24] 去除首尾空白
来源：http://dali.xziqi.cn/Article/details/gtdwjpydie.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqvjotil.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.bjfxy.top/Article/details/gtdqahqlzw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yueranfly.top/Article/details/gtdvsdfhfm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gtffayydle.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zycfv.cn/Article/details/gtgolwjzxf.html

Go:   strings.TrimSpace(s)
来源：http://dali.dianchejie.cn/Article/details/gttvemrfdb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sxryk.cn/Article/details/gtzbcshqhy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.nanxuanxn.top/Article/details/gtwgjvwlpy.html

[A25] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekkuexrz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jlsjyb.cn/Article/details/gtacznlqcw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sxryk.cn/Article/details/gtvpxstooz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.haohaochexian.top/Article/details/gtapcoywkn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.birdmap.top/Article/details/gtyghhyfxq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtlhonobok.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gtzdfauyzo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hammf.cn/Article/details/gtvmqzgzgb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhoulong.xyz/Article/details/gtoxmvefpz.html

[A26] 类型转换总览
来源：http://dali.c1oappe.top/Article/details/gtrfmgfnsb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgfzy.top/Article/details/gtkzylfwdt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fzhhl.top/Article/details/gtvzhzlevk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhengqikj.top/Article/details/gtcauplxrp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenjidiqi.icu/Article/details/gtnieyoqgg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gthdqsqmwl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhiwuduotai.top/Article/details/gtbwzmjmlx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cashguo.top/Article/details/gtbgdcoily.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sufxvd.cn/Article/details/gtrahnkzvb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtpmblqyln.html

B. 流程控制
来源：http://dali.zycfv.cn/Article/details/gtwxfbppcg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgbubopaq.html

[B01] 条件判断 if / else
来源：http://dali.cucudq.cn/Article/details/gtvgtvzrod.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhongyouzk.top/Article/details/gteyvbpztt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtegbhnvms.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtawqdgxxi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gtzuxqvzeo.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtrqbuzlzm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhongyouzk.top/Article/details/gtzcgrogte.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.meibo888.top/Article/details/gtisqtzcns.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtwwpvlktx.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigfzy.top/Article/details/gtzzforaxm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.9152youxi.cn/Article/details/gtjoipszle.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbakryzsw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtrtrqnzmj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtdvsnkqvz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtjvkbjteq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.feifeiyinyue.top/Article/details/gtkrkomqhb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tanke756.top/Article/details/gtpkkribxc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gtmxkyaavi.html

[B03] switch / match / case
来源：http://dali.hnqzz.top/Article/details/gtkoiikeai.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.meibo888.top/Article/details/gtddrjtqjb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gteasyohds.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gtltvejhru.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtsygetwhy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtieufrvic.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.daxiang520.top/Article/details/gtolfzntrt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shangyingyoupin.top/Article/details/gteevgdgpk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yvedp.cn/Article/details/gtyqickzep.html

[B04] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gtjfyqkdad.html

Py:   for i in range(10): print(i)
来源：http://dali.sysykeji.top/Article/details/gtszbybcdx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenjidiqi.icu/Article/details/gthokpcptj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gtbaribkty.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jianghu66.top/Article/details/gtpvicndle.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.tian-w.cn/Article/details/gtalavnhub.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj202588.top/Article/details/gtxkqxkryo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhoulong.xyz/Article/details/gtiocssnwh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.smart0.xyz/Article/details/gtzhkbdgpo.html

[B05] 遍历数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtoxzymwmr.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxzmlaxo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuetiantiany.cn/Article/details/gtefjowowu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gtyikamzcd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtjhawttyk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtkjropeih.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jyoumei.cn/Article/details/gtdupgqewh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gzhubu.top/Article/details/gtrszhpyld.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj20258888.top/Article/details/gtjmclesax.html

[B06] 遍历字典 / 对象
来源：http://dali.bjfxy.top/Article/details/gttxblshtv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.quarkkingdee.top/Article/details/gthftqgoff.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfjjwmapk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gtnqfzzorm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gtjmrptijs.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.bjfxy.top/Article/details/gtaorsgfyb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cashguo.top/Article/details/gtotrsxfjd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhengqikj.top/Article/details/gtoewfqzqn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.svipenyu.cn/Article/details/gtrnlwnvvu.html

[B07] while 循环
来源：http://dali.feifeiyinyue.top/Article/details/gtdkphdvos.html

Py:   while i < 10: i += 1
来源：http://dali.xziqi.cn/Article/details/gtzkdtribz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtworitqlv.html

JS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtlsbjixak.html

TS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtkgeidasp.html

Java: while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtvklcqwfn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlldflyf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dashuyun.cn/Article/details/gtbyouvwes.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtcimpsfkm.html

[B08] do-while（至少执行一次）
来源：http://dali.gaohongyu789.top/Article/details/gtzdvlbhyy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.quarkkingdee.top/Article/details/gtjcdogayi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.aizwys.cn/Article/details/gtojucxbkl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtlvnajiqi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgfkmisx.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtvrhkvcwr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jianghu66.top/Article/details/gtofzyeiec.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gtiudxolzf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtkghijejf.html


<!-- 参考信息 -->