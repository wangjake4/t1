代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.svipenyu.cn/Article/details/gt2ibuutbhm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cqqwz.cn/Article/details/gt2cqiblzwk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.daxiang520.top/Article/details/gt2ddwiyfly.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.bjfxy.top/Article/details/gt2ssvkhvrw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.smart0.xyz/Article/details/gt2wnmnzkxm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.pycfn.com/Article/details/gt2upoiupws.html

Go:   name := "Alex"; age := 20
来源：http://dali.jianghu66.top/Article/details/gt2tekutfqa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxuanxn.top/Article/details/gt2cupfrhtj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2iclhmmyp.html

[A03] 常量定义
来源：http://dali.ppjwa.cn/Article/details/gt2gvthfgjl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.vqdsnc.cn/Article/details/gt2wyyxiqzp.html

PHP:  const PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2ydimngfs.html

JS:   const PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2opambpqp.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zrpuvbla.html

Java: static final double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2zxzfxddc.html

Go:   const PI = 3.14159
来源：http://dali.sxryk.cn/Article/details/gt2zoagqenu.html

Ruby: PI = 3.14159
来源：http://dali.9152youxi.cn/Article/details/gt2xlwpmrqq.html

C#:   const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2udeezcxv.html

[A04] 判断变量类型
来源：http://dali.redwolf501.top/Article/details/gt2pcsrlmxy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fengsongda.top/Article/details/gt2uzgmcvlx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxuanxn.top/Article/details/gt2lkprpjkt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.316326.xyz/Article/details/gt2dpekdeyy.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgufenzy.top/Article/details/gt2zegnyxyw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jianghu66.top/Article/details/gt2tmfjtymr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinqigfzy.top/Article/details/gt2zmkdboth.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cheryme.top/Article/details/gt2swrwwjxy.html

C#:   x.GetType().Name; x is int
来源：http://dali.sweek.top/Article/details/gt2qbnjzksq.html

[A05] 整数除法与取模
来源：http://dali.zycfv.cn/Article/details/gt2qgbhmudg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zycfv.cn/Article/details/gt2syfebdds.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2tgyhptaa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gt2tnjwkivo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gt2aoujopmb.html

Java: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2trymkcfr.html

Go:   7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2qdubhnqs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gt2bdvwmjlk.html

C#:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gt2anlcdxnr.html

[A06] 字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynrtlwkz.html

Py:   int("42"); float("3.14")
来源：http://dali.jqgufenzy.top/Article/details/gt2bzyzxfog.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xziqi.cn/Article/details/gt2crndihon.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gt2yocbehjh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gt2nblvxpiu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xylfe.cn/Article/details/gt2thqjlbmh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gzhubu.top/Article/details/gt2otszpvjb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sufxvd.cn/Article/details/gt2eusmftev.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldetaucn.html

[A07] 数字转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2gizqymsk.html

Py:   str(42)
来源：http://dali.c1oappe.top/Article/details/gt2moccdrpz.html

PHP:  (string) 42; strval(42)
来源：http://dali.zycfv.cn/Article/details/gt2wmqexusd.html

JS:   String(42); (42).toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ponetmvi.html

TS:   String(42)
来源：http://dali.jianghu66.top/Article/details/gt2eyvbfpjo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ivvv.top/Article/details/gt2fgkncwle.html

Go:   strconv.Itoa(42)
来源：http://dali.zdqjudy.top/Article/details/gt2ribfcylm.html

Ruby: 42.to_s
来源：http://dali.yongpay.top/Article/details/gt2wbqrubbf.html

C#:   42.ToString()
来源：http://dali.cheryme.top/Article/details/gt2kfpzfbxq.html

[A08] 取整与四舍五入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbudzxjh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gt2mnrxehoe.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmdqirht.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gt2ujbwtjmd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ydzc1.top/Article/details/gt2opcutzpr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gt2lnmhonah.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amfitura.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.sysykeji.top/Article/details/gt2epysimmo.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gt2othhuewr.html

[A09] 绝对值与最大最小值
来源：http://dali.yangfankeji.com/Article/details/gt2lcfebqep.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2xdrvhmpa.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2czvuhbbu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2sfwgyzip.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2yuxwxeje.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2lyuxjgyc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cheryme.top/Article/details/gt2wdsrpcnk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jlsjyb.cn/Article/details/gt2nkytnkae.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbunxasl.html

[A10] 生成随机数
来源：http://dali.mhx1999.top/Article/details/gt2pmlirihh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhixingplan.top/Article/details/gt2mhggzavd.html

PHP:  random_int(1, 100);
来源：http://dali.hysaishi.cn/Article/details/gt2hpdflaql.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgekzkyd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj202588.top/Article/details/gt2gmrcrkdz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2sttunlbg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhoulong.xyz/Article/details/gt2uzseyowo.html

Ruby: rand(1..100)
来源：http://dali.xinyue.icu/Article/details/gt2zbbjqiek.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eyniowil.html

[A11] 条件表达式（三元）
来源：http://dali.aibaodan.cn/Article/details/gt2othrkfhh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xuanzx.com/Article/details/gt2exzbhqkt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2vulocsqr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gt2rehwqmvq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gt2nlhviiuw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gt2rkuiqdjk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.snrcjt.cn/Article/details/gt2pgweazpc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gt2lveeydjt.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gt2ccnumrei.html

[A12] 字符串插值 / 格式化
来源：http://dali.fengsongda.top/Article/details/gt2fqwkyyqe.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xuanzx.com/Article/details/gt2seengltc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.fengsongda.top/Article/details/gt2cxjdqukj.html

JS:   `Hello, ${name}!`
来源：http://dali.hnxiangtu.top/Article/details/gt2nhdaigkh.html

TS:   `Hello, ${name}!`
来源：http://dali.tanke756.top/Article/details/gt2kwuyeugq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.tanke756.top/Article/details/gt2eqewrcio.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.havefunace.top/Article/details/gt2tjptqodr.html

Ruby: "Hello, #{name}!"
来源：http://dali.cheryme.top/Article/details/gt2ohkmbxkv.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrpkzgf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.dashuyun.cn/Article/details/gt2kkcapczr.html

Py:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gt2lnbommkw.html

PHP:  "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gt2dxonjpha.html

JS:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gt2sonmdiox.html

TS:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkspkzje.html

Java: "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gt2eucnnahf.html

Go:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2zeakdqbn.html

Ruby: "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gt2fyjwqeam.html

C#:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2ipzfpvwk.html

[A14] 注释写法
来源：http://dali.nwbrower.top/Article/details/gt2kiszmcta.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xuanzx.com/Article/details/gt2vnrpodhj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gt2feuhkabd.html

JS:   // 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gt2rvcyccmg.html

TS:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gt2abtqqbkm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.dashuyun.cn/Article/details/gt2fpgapzyg.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rikqetdj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.c1oappe.top/Article/details/gt2bqqdqeok.html

C#:   // 单行；/* 多行 */
来源：http://dali.ehwqpu.com/Article/details/gt2irwwvdvo.html

[A15] 空值判断与默认值
来源：http://dali.xylfe.cn/Article/details/gt2actwfphc.html

Py:   value = data or "默认值"
来源：http://dali.9152youxi.cn/Article/details/gt2mariycsa.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gt2jkmxptie.html

JS:   const value = data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gt2uuigkfwo.html

TS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gt2kzepfxyz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258.top/Article/details/gt2kxwetztq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jianghu66.top/Article/details/gt2pwaoqlga.html

Ruby: value = data || "默认值"
来源：http://dali.hfpthk.cn/Article/details/gt2xxqhoryy.html

C#:   var value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gt2itplglrn.html

[A16] 真假值判断规则
来源：http://dali.sysykeji.top/Article/details/gt2chbymjva.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.guowangkeji.top/Article/details/gt2qniyyaxt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jqgufenzy.top/Article/details/gt2bwxdeqed.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yj202588.top/Article/details/gt2sxhhdjwt.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnylxbbf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2pnwroepc.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhengqikj.top/Article/details/gt2lbdyxbyf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tianlin.xyz/Article/details/gt2xhcrtdhm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srgfuaqn.html

[A17] 位运算
来源：http://dali.ydzc1.top/Article/details/gt2pxqntuof.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gt2igizjhsi.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2guxollcc.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2eaxdgvts.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gt2rvnqctpb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2zzymbcvi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gt2bytcqpwt.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gt2nicezjfb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2frrcplpc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnkivmva.html

Py:   ord("A"); chr(65)
来源：http://dali.xylfe.cn/Article/details/gt2vyvofvim.html

PHP:  ord("A"); chr(65)
来源：http://dali.gaohongyu789.top/Article/details/gt2jzkrmdee.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.kuanghao11.cn/Article/details/gt2jctniptk.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.birdmap.top/Article/details/gt2rcbfpwks.html

Java: (int) 'A'; (char) 65
来源：http://dali.fengsongda.top/Article/details/gt2kqcjlxpk.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqnldqbo.html

Ruby: "A".ord; 65.chr
来源：http://dali.cashguo.top/Article/details/gt2prdvtyql.html

C#:   (int)'A'; (char)65
来源：http://dali.sxryk.cn/Article/details/gt2ngciveaq.html

[A19] 交换两个变量
来源：http://dali.pycfn.com/Article/details/gt2jpoepskt.html

Py:   a, b = b, a
来源：http://dali.yvedp.cn/Article/details/gt2fkfvranp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.smart0.xyz/Article/details/gt2lzfyklnp.html

JS:   [a, b] = [b, a];
来源：http://dali.yj202588.top/Article/details/gt2tfzdquqn.html

TS:   [a, b] = [b, a];
来源：http://dali.fengsongda.top/Article/details/gt2uccwlzky.html

Java: int t = a; a = b; b = t;
来源：http://dali.xuanzx.com/Article/details/gt2umwrdvxy.html

Go:   a, b = b, a
来源：http://dali.meibo888.top/Article/details/gt2nwixyjlo.html

Ruby: a, b = b, a
来源：http://dali.pycfn.com/Article/details/gt2xzdbfgdx.html

C#:   (a, b) = (b, a);
来源：http://dali.0kj1m.cn/Article/details/gt2odtskukc.html

[A20] 读取标准输入
来源：http://dali.snrcjt.cn/Article/details/gt2gjrfbxac.html

Py:   name = input("请输入：")
来源：http://dali.shzxlz.cn/Article/details/gt2kntdcnll.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spgaukrk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vacjrpih.html

TS:   // Node.js：readline 模块
来源：http://dali.hfpthk.cn/Article/details/gt2pugpqvie.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ehwqpu.com/Article/details/gt2evoqfzbj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhixingplan.top/Article/details/gt2gifngvms.html

Ruby: gets.chomp
来源：http://dali.yuxming.cn/Article/details/gt2cglpjkhr.html

C#:   Console.ReadLine();
来源：http://dali.0kj1m.cn/Article/details/gt2ewkxfobd.html

[A21] 保留指定小数位输出
来源：http://dali.kuanghao11.cn/Article/details/gt2axjmxoqa.html

Py:   f"{3.14159:.2f}"
来源：http://dali.vqdsnc.cn/Article/details/gt2iyhzczxn.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gt2hlwpbqnp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gt2qbnivdrw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gt2snmwcpzl.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gt2zmrgtywi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gt2feqqnbxi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gt2omtzskfq.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdaeisvt.html

[A22] 获取字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2xndhdinf.html

Py:   len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svjybfhj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tian-w.cn/Article/details/gt2zxrzbquj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.pengpengdd.cyou/Article/details/gt2woxadott.html

TS:   s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2ycsppnsk.html

Java: s.length()
来源：http://dali.aizwys.cn/Article/details/gt2rzitvlyw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zycfv.cn/Article/details/gt2shjsxlxe.html

Ruby: s.length
来源：http://dali.guannengcc.top/Article/details/gt2djlplvex.html

C#:   s.Length
来源：http://dali.fengsongda.top/Article/details/gt2jlbcvyug.html

[A23] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2vknvxene.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hammf.cn/Article/details/gt2hsjcqumu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aizwys.cn/Article/details/gt2blunymkq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojsjabzh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigufen.top/Article/details/gt2cobfkssp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gt2aaxktryj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gogol.net.cn/Article/details/gt2uierepfu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gt2qdiehyan.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sufxvd.cn/Article/details/gt2iuuifkqm.html

[A24] 去除首尾空白
来源：http://dali.andypj.xyz/Article/details/gt2lcbcjvgx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cqqwz.cn/Article/details/gt2peprtolw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.meibo888.top/Article/details/gt2iaomvurn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gt2ednthvma.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.bjfxy.top/Article/details/gt2jxpodaxx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.316326.xyz/Article/details/gt2ckfxdulv.html

Go:   strings.TrimSpace(s)
来源：http://dali.fzhhl.top/Article/details/gt2jzijgwmb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.tianlin.xyz/Article/details/gt2rmnggget.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zycfv.cn/Article/details/gt2sbcvvolh.html

[A25] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2uxpcdbmm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhongyouzk.top/Article/details/gt2uqzuggyr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aibaodan.cn/Article/details/gt2gohfizkk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gt2uaablbjj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gt2xeesxsna.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nanxinkj.top/Article/details/gt2ynenjyub.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj20258.top/Article/details/gt2tvjjzzyy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqxpacav.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.iojbl.cn/Article/details/gt2iiqqespv.html

[A26] 类型转换总览
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbklsfri.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hnqzz.top/Article/details/gt2oebhldqq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdnnkse.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgfzy.top/Article/details/gt2ovqhmvik.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmxuysuw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jianghu66.top/Article/details/gt2gokhrftn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cqqwz.cn/Article/details/gt2likwfnne.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.daxiang520.top/Article/details/gt2dtshvmoa.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cheryme.top/Article/details/gt2glfuaxlo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ogmugczt.html

B. 流程控制
来源：http://dali.c1oappe.top/Article/details/gt2wwnrqpcb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2qpbhswty.html

[B01] 条件判断 if / else
来源：http://dali.daxiang520.top/Article/details/gt2snnjmukl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jqgufenzy.top/Article/details/gt2xwxvzoeo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2weozaifg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnnlodvq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gt2adjcdkwa.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2ieswppla.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258888.top/Article/details/gt2riudxtwj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fzhhl.top/Article/details/gt2yjeiaytz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gt2bqqzbxoa.html

[B02] 多分支 else if / elif
来源：http://dali.dianchejie.cn/Article/details/gt2ehwqyikr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fengsongda.top/Article/details/gt2faagwbyr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2dpauohse.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2zymtdfqx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gt2flzzrvtc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gt2vlwmzfsc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yueranfly.top/Article/details/gt2fdemufnt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.quarkkingdee.top/Article/details/gt2uetypakf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gt2jalxundj.html

[B03] switch / match / case
来源：http://dali.yueranfly.top/Article/details/gt2jkstwmpc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenlongwang.top/Article/details/gt2lposisog.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gt2lptccpnn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gt2dfegifim.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rltyboxu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gt2ozghicaw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258.top/Article/details/gt2dizerods.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdwmkxao.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nwbrower.top/Article/details/gt2zemztsef.html

[B04] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gt2uahwhdgm.html

Py:   for i in range(10): print(i)
来源：http://dali.bjfxy.top/Article/details/gt2wwjkogdq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258.top/Article/details/gt2ibbrvscq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gt2zaldkego.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gt2duvompzb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcpyoasi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenlongwang.top/Article/details/gt2ogmppmpg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guannengcc.top/Article/details/gt2ubbftpri.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gogol.net.cn/Article/details/gt2dcixarpb.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gt2ebmnivuu.html

Py:   for item in arr: print(item)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpaegvxo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gt2mtmpddha.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gt2esgvjowo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nttejtur.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daria6918.cn/Article/details/gt2ktywxhef.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnxiangtu.top/Article/details/gt2skemcrqq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yvedp.cn/Article/details/gt2vlcgughx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gt2mcgynluv.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258.top/Article/details/gt2rbtjmraa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tkgahgbw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2lzbfoqrd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilcoldla.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gt2rjijocoi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gt2ktdcyigy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgfzy.top/Article/details/gt2uycevkzb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuanzhike.top/Article/details/gt2vaqdtmdb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xylfe.cn/Article/details/gt2nijxmfhq.html

[B07] while 循环
来源：http://dali.ydzc1.top/Article/details/gt2vcdvkbkx.html

Py:   while i < 10: i += 1
来源：http://dali.ydzc1.top/Article/details/gt2coolougz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.316326.xyz/Article/details/gt2fxdbcssq.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gt2vrhhbjaa.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gt2baiezlyi.html

Java: while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gt2rpgweqbk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xylfe.cn/Article/details/gt2jmpvybkm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gt2fdcgvcox.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2jgzgbfbj.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2dleztsnd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.meibo888.top/Article/details/gt2hazfhkmy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2vttlisjs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aulhxjte.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2mhvsqzwf.html

Java: do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2akwmkavx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.meibo888.top/Article/details/gt2axrrsqtq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.havefunace.top/Article/details/gt2ezwaoniy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2lxhammjr.html


<!-- 参考信息 -->