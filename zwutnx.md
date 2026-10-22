代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.yj202588.top/Article/details/gt2jjuyerao.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yuanzhike.top/Article/details/gt2kvvcnfgi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gt2jxyugbke.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gt2iiwghkmw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgybaeip.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gt2ybklsljb.html

Go:   name := "Alex"; age := 20
来源：http://dali.cucudq.cn/Article/details/gt2cnplylyj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cashguo.top/Article/details/gt2huvlvksn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.guowangkeji.top/Article/details/gt2vdtkulud.html

[A03] 常量定义
来源：http://dali.dianchejie.cn/Article/details/gt2sfjfeqod.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xinyue.icu/Article/details/gt2dixyilrg.html

PHP:  const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2makyzznv.html

JS:   const PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2qyxrdiho.html

TS:   const PI: number = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcfpsrjv.html

Java: static final double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2odpuykqi.html

Go:   const PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gt2jsxmszjd.html

Ruby: PI = 3.14159
来源：http://dali.9152youxi.cn/Article/details/gt2tzlnxajf.html

C#:   const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2enoilcvu.html

[A04] 判断变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myqepuhp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yueranfly.top/Article/details/gt2uspazbhz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangdashe.top/Article/details/gt2zhjlntjy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gt2ukcklgip.html

TS:   typeof x; x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gt2bkfcitog.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjmrzjfw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhixingplan.top/Article/details/gt2vcgwopjn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgufenzy.top/Article/details/gt2dunpytxh.html

C#:   x.GetType().Name; x is int
来源：http://dali.cheryme.top/Article/details/gt2vtewurok.html

[A05] 整数除法与取模
来源：http://dali.hnqzz.top/Article/details/gt2tqkvrkdh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj20258.top/Article/details/gt2nhnzsiqh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gt2tgezwrka.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2xleosris.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gt2nptteejx.html

Java: 7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2cxwnovwc.html

Go:   7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gt2ioypjlxr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2jlnbiwae.html

C#:   7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gt2acjmarso.html

[A06] 字符串转数字
来源：http://dali.yongpay.top/Article/details/gt2cstxkpdm.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxinkj.top/Article/details/gt2cppozjuc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.mhx1999.top/Article/details/gt2xwwuemmy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gotoacloud.top/Article/details/gt2nnlwmaax.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gogol.net.cn/Article/details/gt2xhlizadd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cucudq.cn/Article/details/gt2ladndgmf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jyoumei.cn/Article/details/gt2nadfjksn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zdqjudy.top/Article/details/gt2lwwzdzbc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258.top/Article/details/gt2boomzwtf.html

[A07] 数字转字符串
来源：http://dali.aibaodan.cn/Article/details/gt2ycnmowjt.html

Py:   str(42)
来源：http://dali.tian-w.cn/Article/details/gt2diaiggyv.html

PHP:  (string) 42; strval(42)
来源：http://dali.yonumen.top/Article/details/gt2gmlokcji.html

JS:   String(42); (42).toString()
来源：http://dali.snrcjt.cn/Article/details/gt2jvswsusw.html

TS:   String(42)
来源：http://dali.birdmap.top/Article/details/gt2cmtawzhe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.daria6918.cn/Article/details/gt2tzuheocu.html

Go:   strconv.Itoa(42)
来源：http://dali.yanxiufei.cn/Article/details/gt2ixbtxysj.html

Ruby: 42.to_s
来源：http://dali.nwbrower.top/Article/details/gt2yymsqgsu.html

C#:   42.ToString()
来源：http://dali.yj202588.top/Article/details/gt2wcktdgxr.html

[A08] 取整与四舍五入
来源：http://dali.fzhhl.top/Article/details/gt2tzyqwber.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncdtskja.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tian-w.cn/Article/details/gt2bthztpzt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2urfmuvhz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.smart0.xyz/Article/details/gt2nareifkk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2huundmao.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gt2cfxyxkwf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.daria6918.cn/Article/details/gt2hgmmxrjv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gt2pwekcnlf.html

[A09] 绝对值与最大最小值
来源：http://dali.yj20258.top/Article/details/gt2vaioptlz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2mwhieark.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2celwtqpk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2xovwgivf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gt2gmlxmfum.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2zkpcbjft.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sysykeji.top/Article/details/gt2paivhohm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cashguo.top/Article/details/gt2ipeldmbd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2pmmkbpil.html

[A10] 生成随机数
来源：http://dali.sysykeji.top/Article/details/gt2oarwjbcw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.dianchejie.cn/Article/details/gt2vveqvuzp.html

PHP:  random_int(1, 100);
来源：http://dali.fzhhl.top/Article/details/gt2jxbnhlfx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwhtcezn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdlerhys.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zycfv.cn/Article/details/gt2vuabznfn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gotoacloud.top/Article/details/gt2vswapgzh.html

Ruby: rand(1..100)
来源：http://dali.zhoulong.xyz/Article/details/gt2deslxznb.html

C#:   new Random().Next(1, 101)
来源：http://dali.xinyue.icu/Article/details/gt2enjuzpry.html

[A11] 条件表达式（三元）
来源：http://dali.quarkkingdee.top/Article/details/gt2cncwusse.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yuxming.cn/Article/details/gt2swavqfoe.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2elaxhogu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sozlcvqa.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gt2ogspcglg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gt2rqrlxwkz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpqoqlpt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gt2laofmjtb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gt2mobsnkfu.html

[A12] 字符串插值 / 格式化
来源：http://dali.jiagoushi.top/Article/details/gt2rmcrsfin.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xuanzx.com/Article/details/gt2yzhsjlku.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.fzhhl.top/Article/details/gt2mapbsnjw.html

JS:   `Hello, ${name}!`
来源：http://dali.yj20258888.top/Article/details/gt2gvoicsop.html

TS:   `Hello, ${name}!`
来源：http://dali.xziqi.cn/Article/details/gt2rujrvrlb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.nanxuanxn.top/Article/details/gt2zjbcvqwl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tobddeqx.html

Ruby: "Hello, #{name}!"
来源：http://dali.nanxuanxn.top/Article/details/gt2myllrbwp.html

C#:   $"Hello, {name}!"
来源：http://dali.kuanghao11.cn/Article/details/gt2cobtilmo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xziqi.cn/Article/details/gt2wqozaglp.html

Py:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gt2htoiekcn.html

PHP:  "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2aghfetgi.html

JS:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2pufnkmjt.html

TS:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eukowsph.html

Java: "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2rvhllbsk.html

Go:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gt2awpybkyt.html

Ruby: "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2rtbhgvqt.html

C#:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2ivvrsuyt.html

[A14] 注释写法
来源：http://dali.316326.xyz/Article/details/gt2rinlfbaa.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.nanxuanxn.top/Article/details/gt2evelyrhs.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gt2ysqmisps.html

JS:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gt2bqllvipj.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gt2artoqxpx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yuxming.cn/Article/details/gt2mtfqehjc.html

Go:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gt2djzvlzin.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tanke756.top/Article/details/gt2anmytzuc.html

C#:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgboyqgf.html

[A15] 空值判断与默认值
来源：http://dali.havefunace.top/Article/details/gt2nzlwvbqq.html

Py:   value = data or "默认值"
来源：http://dali.aizwys.cn/Article/details/gt2xqdyvgyz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gt2ncfsownk.html

JS:   const value = data ?? "默认值";
来源：http://dali.quarkkingdee.top/Article/details/gt2izpfijbq.html

TS:   const value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gt2kbrhzwru.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tian-w.cn/Article/details/gt2tbffbzsz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guannengcc.top/Article/details/gt2shgpbcoa.html

Ruby: value = data || "默认值"
来源：http://dali.nwbrower.top/Article/details/gt2dxpbnhgm.html

C#:   var value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gt2abyawvyt.html

[A16] 真假值判断规则
来源：http://dali.redwolf501.top/Article/details/gt2byprdvap.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.vqdsnc.cn/Article/details/gt2aajofwbp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccsrjuse.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.birdmap.top/Article/details/gt2elkmyerg.html

TS:   if (!x) {}
来源：http://dali.shzxlz.cn/Article/details/gt2legzlogl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2hnjhztoo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tanke756.top/Article/details/gt2avjuasvo.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cheryme.top/Article/details/gt2fzkkoxft.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2vmhaanqn.html

[A17] 位运算
来源：http://dali.c1oappe.top/Article/details/gt2fywtucti.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gt2xcyncvyu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxlahmvn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2lhcuexmk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2cpdlrdwe.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2kagenxgb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2pnbwgpak.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2smroqawk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gt2sebnubme.html

[A18] 字符与 ASCII 码互转
来源：http://dali.c1oappe.top/Article/details/gt2mqzqpqmy.html

Py:   ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gt2tyswvggc.html

PHP:  ord("A"); chr(65)
来源：http://dali.hfpthk.cn/Article/details/gt2elohjmmo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cheryme.top/Article/details/gt2mdrdsclb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.9152youxi.cn/Article/details/gt2jffcirsg.html

Java: (int) 'A'; (char) 65
来源：http://dali.svipenyu.cn/Article/details/gt2sbgybsud.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gotoacloud.top/Article/details/gt2wvdonvef.html

Ruby: "A".ord; 65.chr
来源：http://dali.iojbl.cn/Article/details/gt2ttmgzsyo.html

C#:   (int)'A'; (char)65
来源：http://dali.jinqigfzy.top/Article/details/gt2smepgkiz.html

[A19] 交换两个变量
来源：http://dali.yj20258.top/Article/details/gt2cbpytqnr.html

Py:   a, b = b, a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhotvinl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.andypj.xyz/Article/details/gt2jmdhhyxy.html

JS:   [a, b] = [b, a];
来源：http://dali.cqqwz.cn/Article/details/gt2ootyaazb.html

TS:   [a, b] = [b, a];
来源：http://dali.c1oappe.top/Article/details/gt2uajwoedi.html

Java: int t = a; a = b; b = t;
来源：http://dali.hammf.cn/Article/details/gt2tqhyshll.html

Go:   a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gt2nagagqvi.html

Ruby: a, b = b, a
来源：http://dali.gzhubu.top/Article/details/gt2pkaafkkj.html

C#:   (a, b) = (b, a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2wiytfhmk.html

[A20] 读取标准输入
来源：http://dali.yueranfly.top/Article/details/gt2rzmgmacd.html

Py:   name = input("请输入：")
来源：http://dali.316326.xyz/Article/details/gt2whhpkofa.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xziqi.cn/Article/details/gt2mffouhjw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cqqwz.cn/Article/details/gt2mkiepfdu.html

TS:   // Node.js：readline 模块
来源：http://dali.dashuyun.cn/Article/details/gt2bnnsipjv.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ehwqpu.com/Article/details/gt2bgdvoxcq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.c1oappe.top/Article/details/gt2wzyjmjqq.html

Ruby: gets.chomp
来源：http://dali.vqdsnc.cn/Article/details/gt2bzkhluvo.html

C#:   Console.ReadLine();
来源：http://dali.zhongyouzk.top/Article/details/gt2jcirbviz.html

[A21] 保留指定小数位输出
来源：http://dali.sysykeji.top/Article/details/gt2eixicrnp.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxuanxn.top/Article/details/gt2trnlwmex.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcovrcms.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gt2gmodlnzl.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gt2akusuivp.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gt2xgcqcewq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yueranfly.top/Article/details/gt2xafwwjcf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gt2rdlzrrxv.html

C#:   3.14159.ToString("F2")
来源：http://dali.hysaishi.cn/Article/details/gt2taaufpax.html

[A22] 获取字符串长度
来源：http://dali.yj202588.top/Article/details/gt2cddsppmq.html

Py:   len(s)
来源：http://dali.jyoumei.cn/Article/details/gt2sjshnlnf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenzaomai.com/Article/details/gt2xjwxfxse.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.vqdsnc.cn/Article/details/gt2yluqgvby.html

TS:   s.length
来源：http://dali.cashguo.top/Article/details/gt2maylvdep.html

Java: s.length()
来源：http://dali.jyoumei.cn/Article/details/gt2henmplin.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2jjnwvfrc.html

Ruby: s.length
来源：http://dali.xinyue.icu/Article/details/gt2zuplwlgu.html

C#:   s.Length
来源：http://dali.sxryk.cn/Article/details/gt2mdkfxaos.html

[A23] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gt2iqhchvln.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ooxietat.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sweek.top/Article/details/gt2mkqmrtpb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nomtnsdh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gt2jhnivrym.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptnlxval.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shzxlz.cn/Article/details/gt2rpqfnpvc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.fengsongda.top/Article/details/gt2lgihkirg.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hammf.cn/Article/details/gt2czxrsppq.html

[A24] 去除首尾空白
来源：http://dali.gaohongyu789.top/Article/details/gt2sjwljtzu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oelostvj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yanxiufei.cn/Article/details/gt2uzszvife.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gt2vwrumier.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fengsongda.top/Article/details/gt2ofkkhpak.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hywenlv.cn/Article/details/gt2byrjjpkz.html

Go:   strings.TrimSpace(s)
来源：http://dali.tianlin.xyz/Article/details/gt2fnmnzyip.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yueranfly.top/Article/details/gt2kjfcocnz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.9152youxi.cn/Article/details/gt2dwidzdcr.html

[A25] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2ewaijgvn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhoulong.xyz/Article/details/gt2wehfcohz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aizwys.cn/Article/details/gt2tcgbtxvz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxuanxn.top/Article/details/gt2gefaxhcv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sweek.top/Article/details/gt2ojvfyxwj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daria6918.cn/Article/details/gt2squfqbro.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jiagoushi.top/Article/details/gt2pidqemji.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dashuyun.cn/Article/details/gt2tgwprfuw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gt2lbjaafse.html

[A26] 类型转换总览
来源：http://dali.tianlin.xyz/Article/details/gt2mvfnfckb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xinyue.icu/Article/details/gt2pcfsixlj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.mhx1999.top/Article/details/gt2xjxdbjfx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cdnleiting.top/Article/details/gt2sftsertz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xziqi.cn/Article/details/gt2thcesygv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gt2fuufpzml.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yuxming.cn/Article/details/gt2vweoyzxd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhoulong.xyz/Article/details/gt2wwxyojlm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxinkj.top/Article/details/gt2hqabgrfr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2wihsxksb.html

B. 流程控制
来源：http://dali.cqqwz.cn/Article/details/gt2apnkpoaj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgujokig.html

[B01] 条件判断 if / else
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxykpdyp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gotoacloud.top/Article/details/gt2laisplwa.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2cpiysnpa.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gt2fnoovqxz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gt2oezwmvey.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2vivznlwo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jianghu66.top/Article/details/gt2ubclrnko.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hfpthk.cn/Article/details/gt2hkljzfqq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gt2oomfqfjs.html

[B02] 多分支 else if / elif
来源：http://dali.tanke756.top/Article/details/gt2sfiqopyr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cucudq.cn/Article/details/gt2eilgofso.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ivjysdsb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gt2bprktudp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gt2uqnrotdq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gt2tydjmjxb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuawhydo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shuidangran.top/Article/details/gt2tjrmpxow.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gt2fobojhkc.html

[B03] switch / match / case
来源：http://dali.birdmap.top/Article/details/gt2pfvqtdip.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shzxlz.cn/Article/details/gt2gfdvowjd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2deapihku.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gt2fvwhfnrl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfzpcmys.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gt2bhmsjxaw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxinkj.top/Article/details/gt2mhzuhjeh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dianchejie.cn/Article/details/gt2qxspssnh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.daria6918.cn/Article/details/gt2xlftysii.html

[B04] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gt2rwcspuwe.html

Py:   for i in range(10): print(i)
来源：http://dali.yanxiufei.cn/Article/details/gt2pamxkicl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.svipenyu.cn/Article/details/gt2rtrjvuto.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gt2fhlboplt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lotgmeuj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gaohongyu789.top/Article/details/gt2blmwbnpc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xuanzx.com/Article/details/gt2inmwecvh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.9152youxi.cn/Article/details/gt2kcsqdypv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2bkiwlqmv.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgxjnwzu.html

Py:   for item in arr: print(item)
来源：http://dali.ppjwa.cn/Article/details/gt2csgckfpc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yongpay.top/Article/details/gt2inxacxnb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2nkqrrmis.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egfsavft.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guannengcc.top/Article/details/gt2yajnjrhh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgfzy.top/Article/details/gt2bjtljbio.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gt2otknjpxv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2qcztzdak.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gt2laojgujl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.smart0.xyz/Article/details/gt2oujtqwfl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.bjfxy.top/Article/details/gt2cmzjfols.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gt2ctkrooxf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.andypj.xyz/Article/details/gt2huhqfzbw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shuidangran.top/Article/details/gt2dvezjfcq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.svipenyu.cn/Article/details/gt2knodwlqt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.andypj.xyz/Article/details/gt2zpbeshfa.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.dianchejie.cn/Article/details/gt2qzzokhqm.html

[B07] while 循环
来源：http://dali.yj20258.top/Article/details/gt2yifvzpqi.html

Py:   while i < 10: i += 1
来源：http://dali.yuanzhike.top/Article/details/gt2mcnnosab.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.316326.xyz/Article/details/gt2hdiawmka.html

JS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gt2csbqlowi.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gt2nuxlolsv.html

Java: while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gt2lnmveqio.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yanxiufei.cn/Article/details/gt2mwjlfzke.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkhscily.html

C#:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gt2qqmvxztc.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gt2qlmbdsuf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.haohaochexian.top/Article/details/gt2mggubqff.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cashguo.top/Article/details/gt2hsbpdorp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gt2wordmbeh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2ombavnhv.html

Java: do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2kqjllugh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gt2gjfhheke.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.mhx1999.top/Article/details/gt2dpmlzzun.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2zaxdwxin.html


<!-- 参考信息 -->