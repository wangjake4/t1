代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.daria6918.cn/Article/details/gtinqyfvnl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hysaishi.cn/Article/details/gtharfayeb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiiuqgqd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnqzz.top/Article/details/gtteatflyc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gtveogzosv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtjxihhqvv.html

Go:   name := "Alex"; age := 20
来源：http://dali.pengpengdd.cyou/Article/details/gtpztgyfxi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tianlin.xyz/Article/details/gtnnkpzqwl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtwontsqrb.html

[A03] 常量定义
来源：http://dali.sufxvd.cn/Article/details/gtzmvtlfxl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zdqjudy.top/Article/details/gtazrqqqxw.html

PHP:  const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtzcomwvlm.html

JS:   const PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtzpggbkgc.html

TS:   const PI: number = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtanhkpzea.html

Java: static final double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtetgowgqg.html

Go:   const PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtgofypeif.html

Ruby: PI = 3.14159
来源：http://dali.yj20258.top/Article/details/gtpgvdcpax.html

C#:   const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtbmvmdpla.html

[A04] 判断变量类型
来源：http://dali.shzxlz.cn/Article/details/gtruqtkgyc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hammf.cn/Article/details/gtsluugsbm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigfzy.top/Article/details/gthnyfyjzp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gttspfiymw.html

TS:   typeof x; x instanceof Date
来源：http://dali.tian-w.cn/Article/details/gtvokwwsub.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shzxlz.cn/Article/details/gtpnujuefe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sysykeji.top/Article/details/gtslbynszh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvemyqvwl.html

C#:   x.GetType().Name; x is int
来源：http://dali.jlsjyb.cn/Article/details/gtvlevoyuk.html

[A05] 整数除法与取模
来源：http://dali.yangfankeji.com/Article/details/gtfivqhdpf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cheryme.top/Article/details/gtbwxwjwts.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtzvjgzydj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtcamhewfi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtqoyruvnp.html

Java: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gttnlgedbj.html

Go:   7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtlivdtnao.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrczexvfd.html

C#:   7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtnbdgmghh.html

[A06] 字符串转数字
来源：http://dali.yongpay.top/Article/details/gtukmoltgp.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtxiazyocl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenlongwang.top/Article/details/gtgzwmvvey.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.feifeiyinyue.top/Article/details/gtaopltkzh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gtvbykmrju.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gtxdrkoxmh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.andypj.xyz/Article/details/gtzuuhmcuh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258888.top/Article/details/gtrqlsammu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yueranfly.top/Article/details/gtuchhpmec.html

[A07] 数字转字符串
来源：http://dali.haohaochexian.top/Article/details/gtsndxxgvs.html

Py:   str(42)
来源：http://dali.jlsjyb.cn/Article/details/gtysvlmeip.html

PHP:  (string) 42; strval(42)
来源：http://dali.jlsjyb.cn/Article/details/gtuyamfnds.html

JS:   String(42); (42).toString()
来源：http://dali.jyoumei.cn/Article/details/gtgprswbgq.html

TS:   String(42)
来源：http://dali.jinqigufen.top/Article/details/gtmlwyoxrf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.kuanghao11.cn/Article/details/gttbwmxqxw.html

Go:   strconv.Itoa(42)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwvvyzsd.html

Ruby: 42.to_s
来源：http://dali.wangdashe.top/Article/details/gtaevhneln.html

C#:   42.ToString()
来源：http://dali.chenzaomai.com/Article/details/gtlehorywi.html

[A08] 取整与四舍五入
来源：http://dali.yvedp.cn/Article/details/gtiuvkbkrn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtiebnkljw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zdqjudy.top/Article/details/gthybkcjun.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtxkmfvqpf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.9152youxi.cn/Article/details/gtnzlhhwnd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtaapwcaiv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtnlgodxvo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcavjohs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtdxxhzijk.html

[A09] 绝对值与最大最小值
来源：http://dali.sxryk.cn/Article/details/gtjekpxfqd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtgyttnsxw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtxepsnldr.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtzezdsltc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtoufdaxka.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gttjcnfgqy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jqgufenzy.top/Article/details/gtabqbjmkv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.smart0.xyz/Article/details/gtyleueqra.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtiybyrddi.html

[A10] 生成随机数
来源：http://dali.shangyingyoupin.top/Article/details/gtambmhbcz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ehwqpu.com/Article/details/gtfgtcicqr.html

PHP:  random_int(1, 100);
来源：http://dali.nanxinkj.top/Article/details/gteuujxgsj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sweek.top/Article/details/gtiqgsqaji.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xinyue.icu/Article/details/gtklprfwtb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.quarkkingdee.top/Article/details/gtarxamjgs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.aibaodan.cn/Article/details/gtpzlcutbq.html

Ruby: rand(1..100)
来源：http://dali.zhoulong.xyz/Article/details/gtqhzifoeo.html

C#:   new Random().Next(1, 101)
来源：http://dali.pengpengdd.cyou/Article/details/gtykjtikea.html

[A11] 条件表达式（三元）
来源：http://dali.vqdsnc.cn/Article/details/gtvxgzsaut.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhongyouzk.top/Article/details/gteiyifycu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtuhkekzic.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtrailuuqt.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gtsuowktim.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gtuvngyqoa.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbakkhvz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpctaszk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtcwgdwfub.html

[A12] 字符串插值 / 格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtvirxnlat.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.316326.xyz/Article/details/gtsxfuffpd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zycfv.cn/Article/details/gtpdscbfly.html

JS:   `Hello, ${name}!`
来源：http://dali.wangdashe.top/Article/details/gtualmgtxz.html

TS:   `Hello, ${name}!`
来源：http://dali.aizwys.cn/Article/details/gtdgxeiegc.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.haohaochexian.top/Article/details/gtcdhcabfd.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinqigfzy.top/Article/details/gtcsohegmf.html

Ruby: "Hello, #{name}!"
来源：http://dali.sxryk.cn/Article/details/gtdibxpmxx.html

C#:   $"Hello, {name}!"
来源：http://dali.smart0.xyz/Article/details/gtozrfcrob.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yanxiufei.cn/Article/details/gtmbsdokch.html

Py:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtkwteigtz.html

PHP:  "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtquwrebva.html

JS:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtmwtdjfoh.html

TS:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gturvmiuzz.html

Java: "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtsfetrnua.html

Go:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gteloclgwb.html

Ruby: "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtozxszanq.html

C#:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtetuxvmls.html

[A14] 注释写法
来源：http://dali.zhixingplan.top/Article/details/gtfwlqttcj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gzhubu.top/Article/details/gtphhmbmqs.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gtyoulgljs.html

JS:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gtjyoyrayb.html

TS:   // 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gtsydqipny.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gogol.net.cn/Article/details/gtlsujebby.html

Go:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gtpftpmrtc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.nwbrower.top/Article/details/gtnqnparjl.html

C#:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gtqlmfnsix.html

[A15] 空值判断与默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraruxrak.html

Py:   value = data or "默认值"
来源：http://dali.xuanzx.com/Article/details/gtsjricgmu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtxvyfdurn.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtjmaownyo.html

TS:   const value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gtxglmufmp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ybcxt.top/Article/details/gtzhvurniw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.fzhhl.top/Article/details/gtfnsxjggg.html

Ruby: value = data || "默认值"
来源：http://dali.yueranfly.top/Article/details/gtwbimqdzk.html

C#:   var value = data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gthkilufws.html

[A16] 真假值判断规则
来源：http://dali.gzhubu.top/Article/details/gtpfdslega.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yvedp.cn/Article/details/gteddlbhmh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gotoacloud.top/Article/details/gtsguitzsa.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gaohongyu789.top/Article/details/gtjrzotywh.html

TS:   if (!x) {}
来源：http://dali.sufxvd.cn/Article/details/gtopzjawcw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.pycfn.com/Article/details/gtsxvskfjl.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhoulong.xyz/Article/details/gtkxrxlesr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopzpnckj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtlwjyayuj.html

[A17] 位运算
来源：http://dali.quarkkingdee.top/Article/details/gttebavjen.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtpcejemkb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtuqthljoi.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtqysgjuvh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtdlukpnuf.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtuoohvhtf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtdaekbeob.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtvctrjftq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtdupgmtqy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhoulong.xyz/Article/details/gtvnmwqnvo.html

Py:   ord("A"); chr(65)
来源：http://dali.jlsjyb.cn/Article/details/gtgpqobrgi.html

PHP:  ord("A"); chr(65)
来源：http://dali.hnqzz.top/Article/details/gtrhsslehe.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hfpthk.cn/Article/details/gtaztxzvxh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.feifeiyinyue.top/Article/details/gtuwyebrwn.html

Java: (int) 'A'; (char) 65
来源：http://dali.yonumen.top/Article/details/gtnasvrooi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfmdqpni.html

Ruby: "A".ord; 65.chr
来源：http://dali.hnqzz.top/Article/details/gtjyqyznsy.html

C#:   (int)'A'; (char)65
来源：http://dali.xziqi.cn/Article/details/gtdezfsurl.html

[A19] 交换两个变量
来源：http://dali.gogol.net.cn/Article/details/gtkekruxqd.html

Py:   a, b = b, a
来源：http://dali.chenlongwang.top/Article/details/gtkptbthbn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hnqzz.top/Article/details/gtuzilyhoq.html

JS:   [a, b] = [b, a];
来源：http://dali.xuanzx.com/Article/details/gtxbojmwoj.html

TS:   [a, b] = [b, a];
来源：http://dali.tanke756.top/Article/details/gtbhjjutyo.html

Java: int t = a; a = b; b = t;
来源：http://dali.ehwqpu.com/Article/details/gtxtbpznkf.html

Go:   a, b = b, a
来源：http://dali.yanxiufei.cn/Article/details/gtnrvomsxx.html

Ruby: a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhgjsgxf.html

C#:   (a, b) = (b, a);
来源：http://dali.redwolf501.top/Article/details/gtmerzhdnr.html

[A20] 读取标准输入
来源：http://dali.fzhhl.top/Article/details/gtigyiklnx.html

Py:   name = input("请输入：")
来源：http://dali.xuetiantiany.cn/Article/details/gtsoklqime.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hammf.cn/Article/details/gtexkykskv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpamtgdyb.html

TS:   // Node.js：readline 模块
来源：http://dali.yvedp.cn/Article/details/gthvwdkszw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cqqwz.cn/Article/details/gtggamjecm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.c1oappe.top/Article/details/gtniowtugo.html

Ruby: gets.chomp
来源：http://dali.kuanghao11.cn/Article/details/gtzmnoyyxo.html

C#:   Console.ReadLine();
来源：http://dali.yj202588.top/Article/details/gthutddclx.html

[A21] 保留指定小数位输出
来源：http://dali.yvedp.cn/Article/details/gtnacwptpy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tianlin.xyz/Article/details/gtosfajokq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtoffgkikt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtwsxpctho.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtdhnusxxy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtcorahwdp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtetqoynwb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gtdfhpzjnd.html

C#:   3.14159.ToString("F2")
来源：http://dali.snrcjt.cn/Article/details/gtsueafecv.html

[A22] 获取字符串长度
来源：http://dali.yj202588.top/Article/details/gtilqabzho.html

Py:   len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtkglpkqah.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.smart0.xyz/Article/details/gtecywvamq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhixingplan.top/Article/details/gtkvxcgttd.html

TS:   s.length
来源：http://dali.zhoulong.xyz/Article/details/gtgseezwbl.html

Java: s.length()
来源：http://dali.chenlongwang.top/Article/details/gtvwkofjpa.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtgiriffvj.html

Ruby: s.length
来源：http://dali.jinqigufen.top/Article/details/gtzewvbxgc.html

C#:   s.Length
来源：http://dali.birdmap.top/Article/details/gthvridvtg.html

[A23] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gttdvqmggm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskdejyba.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yonumen.top/Article/details/gtqabsxhgq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gtbwatlull.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gtzmevwicx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gtdbspcrsn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.mhx1999.top/Article/details/gtgmgepijo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtgunqeues.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.smart0.xyz/Article/details/gtzessyqpm.html

[A24] 去除首尾空白
来源：http://dali.0kj1m.cn/Article/details/gtriugaryd.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.c1oappe.top/Article/details/gtxuzskaxh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gaohongyu789.top/Article/details/gtzhykewne.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gtqqprzhzt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxuanxn.top/Article/details/gtwpkuvrnk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zdqjudy.top/Article/details/gtrjirvopo.html

Go:   strings.TrimSpace(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtioawcvtz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jqgfzy.top/Article/details/gtbgdnxwrh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sysykeji.top/Article/details/gtllpgaiyk.html

[A25] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtlzdmavfg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jiagoushi.top/Article/details/gtwfssbjjc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.quarkkingdee.top/Article/details/gtbuvhrtxf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gttjfqlkpb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuanzhike.top/Article/details/gtkbfodwds.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cheryme.top/Article/details/gtdrklvdwk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cucudq.cn/Article/details/gtzvnovbwv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fzhhl.top/Article/details/gtrlofrfft.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yvedp.cn/Article/details/gthfsvjysc.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gtimaznnhz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuaigdjud.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zdqjudy.top/Article/details/gtqlvnztnu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.andypj.xyz/Article/details/gtldfejorg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gotoacloud.top/Article/details/gtbsjcjkaj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shuidangran.top/Article/details/gtjveurwex.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.haohaochexian.top/Article/details/gtyprkswdn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhengqikj.top/Article/details/gtwqlidgdx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gtaknrmhak.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtimqufcxf.html

B. 流程控制
来源：http://dali.guowangkeji.top/Article/details/gtzzocprbt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxxqgelwm.html

[B01] 条件判断 if / else
来源：http://dali.xylfe.cn/Article/details/gtyyvneang.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sweek.top/Article/details/gtosqqixhj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.birdmap.top/Article/details/gtgruoupgn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtkimbxymx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtbbfcevuj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtocmsqfxc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.mhx1999.top/Article/details/gticsrkgkx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.andypj.xyz/Article/details/gtcdlzltiz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gtyuswcrpk.html

[B02] 多分支 else if / elif
来源：http://dali.kuanghao11.cn/Article/details/gtgytrsyiw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangdashe.top/Article/details/gtzvoamkwo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sxryk.cn/Article/details/gtjeezhhee.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gteuslguwa.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtjlyfrtro.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtyhdrwmjv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yangfankeji.com/Article/details/gtxslgbewe.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhongyouzk.top/Article/details/gtwqbbqlne.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtrnesiumk.html

[B03] switch / match / case
来源：http://dali.yj20258888.top/Article/details/gttddzssdz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxuanxn.top/Article/details/gtdkximyvx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtbxopwnzl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gteugrprie.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtryyisrlq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtevazcjhk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sufxvd.cn/Article/details/gtxlaffmfx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ydzc1.top/Article/details/gtsoxqoipn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.c1oappe.top/Article/details/gtyvwaozpk.html

[B04] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gtgcyukngw.html

Py:   for i in range(10): print(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbkxnitn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuanzhike.top/Article/details/gtnkukxkuj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gtmzzwuqkh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.birdmap.top/Article/details/gtmfizvvnf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gotoacloud.top/Article/details/gtdydkwzpe.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xuanzx.com/Article/details/gtaykesdgl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.aizwys.cn/Article/details/gtdlhdnoqc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yuanzhike.top/Article/details/gtdheojjok.html

[B05] 遍历数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gteovkinqz.html

Py:   for item in arr: print(item)
来源：http://dali.chenjidiqi.icu/Article/details/gtlvyhgycq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daxiang520.top/Article/details/gtnrgmggnd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtdvwjqzla.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gtnvwshnqq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.316326.xyz/Article/details/gtwkjjoxxy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.andypj.xyz/Article/details/gtlmxkvyup.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhixingplan.top/Article/details/gtuumkptqr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hnqzz.top/Article/details/gtkizauxmt.html

[B06] 遍历字典 / 对象
来源：http://dali.shzxlz.cn/Article/details/gtdxcsfmch.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxinkj.top/Article/details/gtilpiarjf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtetjvmswg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gtynmjxtmd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gtujqwkxzw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.fengsongda.top/Article/details/gticdbghxh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuetiantiany.cn/Article/details/gtdacfvzqz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guannengcc.top/Article/details/gtbhizhywg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gtclgexgsh.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gtmboqgwjh.html

Py:   while i < 10: i += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecvswocw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtgxvnlzke.html

JS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtbwwwlcas.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtmufyvdpx.html

Java: while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtfswybzgr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxuanxn.top/Article/details/gtipofxjcg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.0kj1m.cn/Article/details/gthqdicgdq.html

C#:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtdjubnjyw.html

[B08] do-while（至少执行一次）
来源：http://dali.mhx1999.top/Article/details/gtovlawvix.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ivvv.top/Article/details/gtiayilgbw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cheryme.top/Article/details/gteeayfupo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtqqqgrkpi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtjnibhmnp.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtbcnbusrw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fengsongda.top/Article/details/gticoyvkbp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cqqwz.cn/Article/details/gtasmanknz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtkwicyooo.html


<!-- 参考信息 -->