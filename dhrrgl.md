代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.daria6918.cn/Article/details/gtxkbkscra.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj202588.top/Article/details/gturmmubbf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj202588.top/Article/details/gtwluhljec.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtoafsrqqx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.c1oappe.top/Article/details/gtiecsqeku.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtrpguuekn.html

Go:   name := "Alex"; age := 20
来源：http://dali.yanxiufei.cn/Article/details/gtkolgssbf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxinkj.top/Article/details/gtdknjgakm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtibcwanzs.html

[A03] 常量定义
来源：http://dali.yj20258888.top/Article/details/gtvtlekvsf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofxjyfvp.html

PHP:  const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtsfowgmug.html

JS:   const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gttpmgpsde.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtmxhcovlm.html

Java: static final double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtsapbnnci.html

Go:   const PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtkbpazwfv.html

Ruby: PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gtjvueylar.html

C#:   const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtpayxfaal.html

[A04] 判断变量类型
来源：http://dali.dianchejie.cn/Article/details/gtpihrsbdf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cqqwz.cn/Article/details/gthbzlqggh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daria6918.cn/Article/details/gthqzqzvnn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjshmait.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gtlsbofvjs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangdashe.top/Article/details/gtxduupmix.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daria6918.cn/Article/details/gtmxgdatld.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xylfe.cn/Article/details/gtfcedbqmf.html

C#:   x.GetType().Name; x is int
来源：http://dali.aizwys.cn/Article/details/gtgrtodydq.html

[A05] 整数除法与取模
来源：http://dali.vqdsnc.cn/Article/details/gtkyrqfixn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zdqjudy.top/Article/details/gthwfvdioc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gthbxgtgty.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqlyrabr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gteghezkaa.html

Java: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtpwpavvaq.html

Go:   7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtvmdvspfk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtovqyzvrd.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtnaeindva.html

[A06] 字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtfwofqiej.html

Py:   int("42"); float("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gtthwscqcz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sysykeji.top/Article/details/gtxfuywxcd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltrllwtv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ybcxt.top/Article/details/gtqqzvdrrd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.andypj.xyz/Article/details/gtmbuaarog.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hfpthk.cn/Article/details/gtopvktoir.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cucudq.cn/Article/details/gtciosgmyl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtvtidjylj.html

[A07] 数字转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gttjoqnxpi.html

Py:   str(42)
来源：http://dali.ppjwa.cn/Article/details/gtgqitlgyw.html

PHP:  (string) 42; strval(42)
来源：http://dali.gaohongyu789.top/Article/details/gtpxspuwph.html

JS:   String(42); (42).toString()
来源：http://dali.daria6918.cn/Article/details/gtffqmcjyc.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gtnkbfwxsy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gotoacloud.top/Article/details/gtqriaovhl.html

Go:   strconv.Itoa(42)
来源：http://dali.yueranfly.top/Article/details/gtfkkznpya.html

Ruby: 42.to_s
来源：http://dali.zhoulong.xyz/Article/details/gtycwzvbpo.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gthyznsjzj.html

[A08] 取整与四舍五入
来源：http://dali.feifeiyinyue.top/Article/details/gtgxqutbza.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtqrkrptkx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jiagoushi.top/Article/details/gtqfteslah.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gtakzsbbsa.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guowangkeji.top/Article/details/gtwbnuhjhh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gthmnpeufr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gtuidramil.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xylfe.cn/Article/details/gtomjefxyc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gtjygsxits.html

[A09] 绝对值与最大最小值
来源：http://dali.guannengcc.top/Article/details/gtnyugdrye.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtwmpgxthl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtpfjbhwew.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtqvcrzaib.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtoewjdhlj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtafgyvanj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.fengsongda.top/Article/details/gtuoeysbmx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinqigufen.top/Article/details/gtkoafgmpd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtvzuwsgbh.html

[A10] 生成随机数
来源：http://dali.cqqwz.cn/Article/details/gtniagvolb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj20258.top/Article/details/gtlneqtihu.html

PHP:  random_int(1, 100);
来源：http://dali.aizwys.cn/Article/details/gtdgoxtruy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.snrcjt.cn/Article/details/gtuyshjupm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.kuanghao11.cn/Article/details/gtwoshxjnv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.feifeiyinyue.top/Article/details/gtbukmdqka.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbiyqoazf.html

Ruby: rand(1..100)
来源：http://dali.cashguo.top/Article/details/gtxxkbexbf.html

C#:   new Random().Next(1, 101)
来源：http://dali.aizwys.cn/Article/details/gtpceiyjut.html

[A11] 条件表达式（三元）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbxyfzgm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.c1oappe.top/Article/details/gtacirurar.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gtrdkshsrt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gtgywbyvss.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtxllyuwcr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczjttxkr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.havefunace.top/Article/details/gtgfkinyjl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtpbfycsui.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtqnicwrog.html

[A12] 字符串插值 / 格式化
来源：http://dali.hywenlv.cn/Article/details/gtqtnddrcl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.tianlin.xyz/Article/details/gtarqjmywn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhoulong.xyz/Article/details/gtyzlmglrb.html

JS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gtueziouct.html

TS:   `Hello, ${name}!`
来源：http://dali.chenzaomai.com/Article/details/gtunqpkcrr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shuidangran.top/Article/details/gtzsiujafk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xziqi.cn/Article/details/gtnfwscdmr.html

Ruby: "Hello, #{name}!"
来源：http://dali.mhx1999.top/Article/details/gtnrjolhuq.html

C#:   $"Hello, {name}!"
来源：http://dali.c1oappe.top/Article/details/gtpfbvsenu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.chenlongwang.top/Article/details/gtcdnxwekv.html

Py:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtlwngixlv.html

PHP:  "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtwtylsfcy.html

JS:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgfzihvr.html

TS:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtqrmelxlo.html

Java: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtjibzgetg.html

Go:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtkoilqzok.html

Ruby: "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtufudsyjf.html

C#:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtnifglthl.html

[A14] 注释写法
来源：http://dali.feifeiyinyue.top/Article/details/gtcgkbizvd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shzxlz.cn/Article/details/gtlztkksog.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gtslqegcwn.html

JS:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtonfiupsn.html

TS:   // 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gtirbhdsft.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nanxuanxn.top/Article/details/gtcugrllvu.html

Go:   // 单行；/* 多行 */
来源：http://dali.quarkkingdee.top/Article/details/gtnfvxzvxt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cheryme.top/Article/details/gtvoxfwthy.html

C#:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtzuihhtoe.html

[A15] 空值判断与默认值
来源：http://dali.gzhubu.top/Article/details/gtoypsrahk.html

Py:   value = data or "默认值"
来源：http://dali.jiagoushi.top/Article/details/gtdrnwvtmu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gtzxdtahvh.html

JS:   const value = data ?? "默认值";
来源：http://dali.yuanzhike.top/Article/details/gtigvqoauk.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gtbcucxijq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ydzc1.top/Article/details/gtuayltizy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hysaishi.cn/Article/details/gtuhkyapwl.html

Ruby: value = data || "默认值"
来源：http://dali.tian-w.cn/Article/details/gttvcfxeqz.html

C#:   var value = data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gtvurkwogm.html

[A16] 真假值判断规则
来源：http://dali.yuxming.cn/Article/details/gttnvhplyh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nanxinkj.top/Article/details/gtuonkpeib.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xinyue.icu/Article/details/gtvgotferx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.quarkkingdee.top/Article/details/gtftmuvcnj.html

TS:   if (!x) {}
来源：http://dali.yj202588.top/Article/details/gtmndqntlo.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jianghu66.top/Article/details/gtlwstakdq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yuanzhike.top/Article/details/gtwaxnptmw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.kuanghao11.cn/Article/details/gtdpyxmnrn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtciwocttf.html

[A17] 位运算
来源：http://dali.sxryk.cn/Article/details/gthdsppyho.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtweqxkkij.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtlufrroyr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtveaxrdha.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtstkusdtw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtqdpilzfu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtxyqthxay.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gthlxgpsdi.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtapektkqt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hnxiangtu.top/Article/details/gtnshzmqtg.html

Py:   ord("A"); chr(65)
来源：http://dali.havefunace.top/Article/details/gthfsxnmrg.html

PHP:  ord("A"); chr(65)
来源：http://dali.yonumen.top/Article/details/gtyuxtwkyh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daxiang520.top/Article/details/gtefjzjcxs.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.feifeiyinyue.top/Article/details/gtptvzsgjm.html

Java: (int) 'A'; (char) 65
来源：http://dali.yanxiufei.cn/Article/details/gtbrrlbslj.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ehwqpu.com/Article/details/gtrfvjrsun.html

Ruby: "A".ord; 65.chr
来源：http://dali.quarkkingdee.top/Article/details/gtffjlmuwc.html

C#:   (int)'A'; (char)65
来源：http://dali.xinyue.icu/Article/details/gtijwxrkea.html

[A19] 交换两个变量
来源：http://dali.jyoumei.cn/Article/details/gtzuchzjiw.html

Py:   a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaybxwwjn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gotoacloud.top/Article/details/gtrhdxpooa.html

JS:   [a, b] = [b, a];
来源：http://dali.aizwys.cn/Article/details/gtoxepgeos.html

TS:   [a, b] = [b, a];
来源：http://dali.jlsjyb.cn/Article/details/gtfqbplxtu.html

Java: int t = a; a = b; b = t;
来源：http://dali.birdmap.top/Article/details/gtcyqledzv.html

Go:   a, b = b, a
来源：http://dali.smart0.xyz/Article/details/gtagqbyioo.html

Ruby: a, b = b, a
来源：http://dali.yj20258.top/Article/details/gtzfpfzcgi.html

C#:   (a, b) = (b, a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnhnvrid.html

[A20] 读取标准输入
来源：http://dali.iojbl.cn/Article/details/gtdibosncy.html

Py:   name = input("请输入：")
来源：http://dali.yj202588.top/Article/details/gtkshdbhzr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuanzhike.top/Article/details/gtcofrhjuf.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.vqdsnc.cn/Article/details/gtnvhxxyjd.html

TS:   // Node.js：readline 模块
来源：http://dali.yvedp.cn/Article/details/gtshcszton.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhengqikj.top/Article/details/gtnubtwbbr.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aizwys.cn/Article/details/gtugmacrur.html

Ruby: gets.chomp
来源：http://dali.sxryk.cn/Article/details/gtefdiozte.html

C#:   Console.ReadLine();
来源：http://dali.daria6918.cn/Article/details/gtelneipna.html

[A21] 保留指定小数位输出
来源：http://dali.sysykeji.top/Article/details/gtjqprnznb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jyoumei.cn/Article/details/gtiyhuvjnd.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttferguxv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtsmyyxvbi.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtbhninuma.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtavvvcwmf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtkbxmonsp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtkbogqtqc.html

C#:   3.14159.ToString("F2")
来源：http://dali.andypj.xyz/Article/details/gtzwzorykp.html

[A22] 获取字符串长度
来源：http://dali.iojbl.cn/Article/details/gtwzcdkomz.html

Py:   len(s)
来源：http://dali.chenlongwang.top/Article/details/gtrvxqmcrl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.redwolf501.top/Article/details/gtspohsetl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sysykeji.top/Article/details/gtuvtctbmn.html

TS:   s.length
来源：http://dali.jqgufenzy.top/Article/details/gtwhybegev.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtanblfrtj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ybcxt.top/Article/details/gtjejhharn.html

Ruby: s.length
来源：http://dali.c1oappe.top/Article/details/gtoitiuzrw.html

C#:   s.Length
来源：http://dali.snrcjt.cn/Article/details/gtgwciazsx.html

[A23] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtwrjbhigr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yonumen.top/Article/details/gtslxxgfre.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.guowangkeji.top/Article/details/gtqpnubgeo.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gtcpufkifg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gtqafqsbcl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gtjpifsayr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xziqi.cn/Article/details/gtlihqppal.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtrreaebqb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhoulong.xyz/Article/details/gtjzgmujbe.html

[A24] 去除首尾空白
来源：http://dali.c1oappe.top/Article/details/gtsxhuhipf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xylfe.cn/Article/details/gtpimlcwme.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.iojbl.cn/Article/details/gtamfjwmiq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gtoivblsjl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxuanxn.top/Article/details/gtosnybsjn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.iojbl.cn/Article/details/gtsusiiyoi.html

Go:   strings.TrimSpace(s)
来源：http://dali.shuidangran.top/Article/details/gtrkbfohex.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.aibaodan.cn/Article/details/gtsderwlvv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtccgeiqxf.html

[A25] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtuvtxcyrj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fengsongda.top/Article/details/gtrtywsdbw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guannengcc.top/Article/details/gtnhfdfhqa.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gtlvxgpedv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgufenzy.top/Article/details/gtpwnkaprn.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shuidangran.top/Article/details/gttgncnwxc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ybcxt.top/Article/details/gtkuxlunco.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblpqkisp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gtwokvripr.html

[A26] 类型转换总览
来源：http://dali.sxryk.cn/Article/details/gtcybppzqn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.tanke756.top/Article/details/gtaqxlpflb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ivvv.top/Article/details/gtglriqlsb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aizwys.cn/Article/details/gthalirvzy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktsfoadg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gtkgwtousz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xinyue.icu/Article/details/gtzewiyolg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.iojbl.cn/Article/details/gtyygufras.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gtwozljiuy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhcynobx.html

B. 流程控制
来源：http://dali.jinqigfzy.top/Article/details/gtbhlzwqje.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtolkueikm.html

[B01] 条件判断 if / else
来源：http://dali.zhixingplan.top/Article/details/gthakmkvbr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yongpay.top/Article/details/gtrgatotto.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.fzhhl.top/Article/details/gttjcrlcxc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gttyzeubfj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtmintcmpx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtoqmkpvke.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhongyouzk.top/Article/details/gtycbflfbj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhengqikj.top/Article/details/gtyhdkosgb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtqfertpyd.html

[B02] 多分支 else if / elif
来源：http://dali.havefunace.top/Article/details/gtstgujdxv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.guowangkeji.top/Article/details/gtcfmzgbls.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhongyouzk.top/Article/details/gttrumfgbg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtttngzzua.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtfjrvdxdd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtyhxrfpig.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.vqdsnc.cn/Article/details/gtbyxcqyvm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yuxming.cn/Article/details/gtmzrbxnca.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtxjujhtdg.html

[B03] switch / match / case
来源：http://dali.ppjwa.cn/Article/details/gtyefldxxm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigfzy.top/Article/details/gtyckvntbi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtoomkzcgx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtkykkxizr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtsraoaxpm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtgkocuegp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gzhubu.top/Article/details/gtbhjbnjcj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sxryk.cn/Article/details/gtgxogjrie.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.birdmap.top/Article/details/gtgttbbbdi.html

[B04] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gttstzhkox.html

Py:   for i in range(10): print(i)
来源：http://dali.meibo888.top/Article/details/gtwalvkrlf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.svipenyu.cn/Article/details/gtksgwndnz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.andypj.xyz/Article/details/gtainqabhg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jyoumei.cn/Article/details/gttsspzbnc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aizwys.cn/Article/details/gtfzgtlvek.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258.top/Article/details/gttaplvgmn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gaohongyu789.top/Article/details/gtgxlaobpa.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cucudq.cn/Article/details/gtaybiwmgy.html

[B05] 遍历数组 / 列表
来源：http://dali.meibo888.top/Article/details/gteojgusrr.html

Py:   for item in arr: print(item)
来源：http://dali.haohaochexian.top/Article/details/gtmzkovyhr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.mhx1999.top/Article/details/gttukovqqx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtuesjzffk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gtewuynbqg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangdashe.top/Article/details/gtketmlfix.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shuidangran.top/Article/details/gtvhzbabnw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.haohaochexian.top/Article/details/gtxmmxdpgl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yueranfly.top/Article/details/gtsfoagczw.html

[B06] 遍历字典 / 对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcxlxugj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.mhx1999.top/Article/details/gtdkoghspm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.meibo888.top/Article/details/gtpscgqefi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gtvqjecade.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnxiangtu.top/Article/details/gtstrtuddb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jianghu66.top/Article/details/gtbvjoujuk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnxiangtu.top/Article/details/gtfmdpwvzd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cheryme.top/Article/details/gtppsegkjc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gogol.net.cn/Article/details/gtzxhebvuh.html

[B07] while 循环
来源：http://dali.xinyue.icu/Article/details/gtnmrxnlff.html

Py:   while i < 10: i += 1
来源：http://dali.zycfv.cn/Article/details/gtwuwdlqgm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtephozxus.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gthblrtweb.html

TS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtkzlkkrjt.html

Java: while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtspjndwuh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.feifeiyinyue.top/Article/details/gthohhojys.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgufenzy.top/Article/details/gtypecutkq.html

C#:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtdponxaaq.html

[B08] do-while（至少执行一次）
来源：http://dali.jiagoushi.top/Article/details/gtgpbpfsle.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.haohaochexian.top/Article/details/gtdeudbmxr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcybwcyk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtwafjmpsp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtxgssjlke.html

Java: do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtmcxodgzt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtnzgmoqva.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.svipenyu.cn/Article/details/gteualwzdg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtamqtwlkc.html


<!-- 参考信息 -->