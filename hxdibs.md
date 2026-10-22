代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.birdmap.top/Article/details/gt2ctsvbrbp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.havefunace.top/Article/details/gt2kvhdzill.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2mynrjzio.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnqzz.top/Article/details/gt2ixamluln.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xinyue.icu/Article/details/gt2xokqvibf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gt2iklaspgy.html

Go:   name := "Alex"; age := 20
来源：http://dali.hysaishi.cn/Article/details/gt2kgygfrul.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxinkj.top/Article/details/gt2dnrvlynu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gt2mpjmkwlg.html

[A03] 常量定义
来源：http://dali.zhengqikj.top/Article/details/gt2hxqhdbra.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yangfankeji.com/Article/details/gt2sektovkl.html

PHP:  const PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2rjnnpxjs.html

JS:   const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtiwesqt.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2jeszceaf.html

Java: static final double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2nwlflmhb.html

Go:   const PI = 3.14159
来源：http://dali.sxryk.cn/Article/details/gt2euzajzyo.html

Ruby: PI = 3.14159
来源：http://dali.nwbrower.top/Article/details/gt2vnebqgvk.html

C#:   const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2drtltuit.html

[A04] 判断变量类型
来源：http://dali.redwolf501.top/Article/details/gt2hllddqnx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.andypj.xyz/Article/details/gt2bnjfvjga.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.dianchejie.cn/Article/details/gt2zmdfckhr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.wangdashe.top/Article/details/gt2lbokvtyk.html

TS:   typeof x; x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gt2mckcywed.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.quarkkingdee.top/Article/details/gt2idbpwyjn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.316326.xyz/Article/details/gt2hoyzomha.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yanxiufei.cn/Article/details/gt2sidgfmtf.html

C#:   x.GetType().Name; x is int
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbqdrwic.html

[A05] 整数除法与取模
来源：http://dali.9152youxi.cn/Article/details/gt2rarugtck.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.vqdsnc.cn/Article/details/gt2vujudwhm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2qhnlksjy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gt2loptnomf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gt2raxpelky.html

Java: 7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2ghuwvpvl.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gt2vtyrzloh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbeehfqf.html

C#:   7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gt2aberjtrs.html

[A06] 字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gt2uxlyxkjw.html

Py:   int("42"); float("3.14")
来源：http://dali.jqgfzy.top/Article/details/gt2hbibgrcy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.aibaodan.cn/Article/details/gt2dkdfokus.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gt2ryquagmd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yanxiufei.cn/Article/details/gt2ctxaybge.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hywenlv.cn/Article/details/gt2toxodhul.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gt2mbsshean.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnxiangtu.top/Article/details/gt2jaivnlyw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhixingplan.top/Article/details/gt2pmfiulvo.html

[A07] 数字转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2siihwscr.html

Py:   str(42)
来源：http://dali.yueranfly.top/Article/details/gt2uckpgatx.html

PHP:  (string) 42; strval(42)
来源：http://dali.shzxlz.cn/Article/details/gt2plvfufkd.html

JS:   String(42); (42).toString()
来源：http://dali.xziqi.cn/Article/details/gt2fuyucygq.html

TS:   String(42)
来源：http://dali.hnxiangtu.top/Article/details/gt2ovyoxlgp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cheryme.top/Article/details/gt2havrrlfa.html

Go:   strconv.Itoa(42)
来源：http://dali.cheryme.top/Article/details/gt2edeppiam.html

Ruby: 42.to_s
来源：http://dali.yuxming.cn/Article/details/gt2gssaqblc.html

C#:   42.ToString()
来源：http://dali.gotoacloud.top/Article/details/gt2cjrjihgf.html

[A08] 取整与四舍五入
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmwkgrop.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gt2vjqfqpaz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zdqjudy.top/Article/details/gt2vrscoqaf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjtjcmst.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj202588.top/Article/details/gt2ucybfdhh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gt2pimvdvib.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gt2infnmsuj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xylfe.cn/Article/details/gt2bzvgxxno.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gt2jrqkypll.html

[A09] 绝对值与最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2hodafsyo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2ktmmgmbd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gt2kiivwapk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.redwolf501.top/Article/details/gt2kxaiygng.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2xtbluvoh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2oczcbmss.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.havefunace.top/Article/details/gt2mohzlybh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yamwzwxk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2pvkdseso.html

[A10] 生成随机数
来源：http://dali.yvedp.cn/Article/details/gt2ieircfoh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwehthqo.html

PHP:  random_int(1, 100);
来源：http://dali.vqdsnc.cn/Article/details/gt2bubjrtpw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbcoklgp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfphdweo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.mhx1999.top/Article/details/gt2tbhsbnuz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yangfankeji.com/Article/details/gt2vqdwctzp.html

Ruby: rand(1..100)
来源：http://dali.andypj.xyz/Article/details/gt2jthtxjis.html

C#:   new Random().Next(1, 101)
来源：http://dali.hammf.cn/Article/details/gt2dbmxctzj.html

[A11] 条件表达式（三元）
来源：http://dali.gzhubu.top/Article/details/gt2lpepepee.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lruztasd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gt2bjpufxbt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gt2syqnavrw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gt2xnjzqkjr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gt2zzakztjr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.chenlongwang.top/Article/details/gt2rrmcqowv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gt2czqztspd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gt2oljauuoh.html

[A12] 字符串插值 / 格式化
来源：http://dali.tanke756.top/Article/details/gt2xwwqnozy.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zdqjudy.top/Article/details/gt2kmpugzcu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yvedp.cn/Article/details/gt2retxffli.html

JS:   `Hello, ${name}!`
来源：http://dali.ehwqpu.com/Article/details/gt2ghlsieny.html

TS:   `Hello, ${name}!`
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbxreslt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.aizwys.cn/Article/details/gt2ilqvvxwr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yj202588.top/Article/details/gt2bomlqblh.html

Ruby: "Hello, #{name}!"
来源：http://dali.gzhubu.top/Article/details/gt2lyugrnsc.html

C#:   $"Hello, {name}!"
来源：http://dali.wangdashe.top/Article/details/gt2hanszkwy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sufxvd.cn/Article/details/gt2lkzeazyb.html

Py:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzducgbv.html

PHP:  "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gt2ixfzndez.html

JS:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2rlqtjilt.html

TS:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2zbswejcr.html

Java: "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2plchonts.html

Go:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgbijgbh.html

Ruby: "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2xflfkzih.html

C#:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwdhssto.html

[A14] 注释写法
来源：http://dali.yvedp.cn/Article/details/gt2ydfmdiag.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.wangdashe.top/Article/details/gt2pqczoqna.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gt2ckaizlcf.html

JS:   // 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gt2mwlcrmtd.html

TS:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gt2hzumcxax.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhixingplan.top/Article/details/gt2axsftngz.html

Go:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gt2junhwsvu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jlsjyb.cn/Article/details/gt2frlkmiqv.html

C#:   // 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gt2ijbfeaqc.html

[A15] 空值判断与默认值
来源：http://dali.jiagoushi.top/Article/details/gt2ygvmtild.html

Py:   value = data or "默认值"
来源：http://dali.9152youxi.cn/Article/details/gt2vczinrii.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gt2cywejvtk.html

JS:   const value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gt2svrtudvx.html

TS:   const value = data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gt2azvlxdfa.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258888.top/Article/details/gt2kfrrencb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.chenlongwang.top/Article/details/gt2zhjdihzx.html

Ruby: value = data || "默认值"
来源：http://dali.gaohongyu789.top/Article/details/gt2excxadtd.html

C#:   var value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gt2ddiszkhq.html

[A16] 真假值判断规则
来源：http://dali.cashguo.top/Article/details/gt2zzwlymbn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.quarkkingdee.top/Article/details/gt2pingehmg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zupfhggf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.dashuyun.cn/Article/details/gt2lofggtgt.html

TS:   if (!x) {}
来源：http://dali.ybcxt.top/Article/details/gt2qemvyohi.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2kxgyluyd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.andypj.xyz/Article/details/gt2ytxcokkc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcnqxqww.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2ppubajwm.html

[A17] 位运算
来源：http://dali.jiagoushi.top/Article/details/gt2unntgiwf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gt2murcewqb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rizfctvs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gt2wsrwfixy.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2slqwthpj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gt2dhijpanz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gt2kdsbffie.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2vinjsene.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2qhtsblxg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.chenlongwang.top/Article/details/gt2vjfwmbba.html

Py:   ord("A"); chr(65)
来源：http://dali.zhongyouzk.top/Article/details/gt2tsgsvxcu.html

PHP:  ord("A"); chr(65)
来源：http://dali.ehwqpu.com/Article/details/gt2gqigtsnh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fengsongda.top/Article/details/gt2rdivztnb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.quarkkingdee.top/Article/details/gt2jjejvwic.html

Java: (int) 'A'; (char) 65
来源：http://dali.ivvv.top/Article/details/gt2pklecqur.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hnqzz.top/Article/details/gt2sbgpwcsd.html

Ruby: "A".ord; 65.chr
来源：http://dali.zdqjudy.top/Article/details/gt2illrldgi.html

C#:   (int)'A'; (char)65
来源：http://dali.chenlongwang.top/Article/details/gt2sdqiqooo.html

[A19] 交换两个变量
来源：http://dali.316326.xyz/Article/details/gt2zaoigfiv.html

Py:   a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gt2folglwin.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinqigufen.top/Article/details/gt2wsubcoto.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigufen.top/Article/details/gt2kwzechfr.html

TS:   [a, b] = [b, a];
来源：http://dali.xuanzx.com/Article/details/gt2mymakvdc.html

Java: int t = a; a = b; b = t;
来源：http://dali.jqgfzy.top/Article/details/gt2kogjbhpb.html

Go:   a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efukgmsr.html

Ruby: a, b = b, a
来源：http://dali.andypj.xyz/Article/details/gt2sxyddqqz.html

C#:   (a, b) = (b, a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iltuegjj.html

[A20] 读取标准输入
来源：http://dali.pengpengdd.cyou/Article/details/gt2cykczgdr.html

Py:   name = input("请输入：")
来源：http://dali.jinqigufen.top/Article/details/gt2efgblrig.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.aibaodan.cn/Article/details/gt2nlgzcvop.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hammf.cn/Article/details/gt2bcsrraoi.html

TS:   // Node.js：readline 模块
来源：http://dali.daria6918.cn/Article/details/gt2olcdrzyf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.fzhhl.top/Article/details/gt2xwfekyjl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzammvah.html

Ruby: gets.chomp
来源：http://dali.guowangkeji.top/Article/details/gt2opxewokm.html

C#:   Console.ReadLine();
来源：http://dali.zdqjudy.top/Article/details/gt2pdffrinv.html

[A21] 保留指定小数位输出
来源：http://dali.jianghu66.top/Article/details/gt2xuesbaui.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ppjwa.cn/Article/details/gt2tlmqodcl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gt2xauwsgfl.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbevufsg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gt2lqqxaiik.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gt2jlqwywez.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gt2tywspnml.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gt2imrmgaat.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjaimdlc.html

[A22] 获取字符串长度
来源：http://dali.zycfv.cn/Article/details/gt2jmbsvgky.html

Py:   len(s)
来源：http://dali.yuxming.cn/Article/details/gt2spcmaepk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.guowangkeji.top/Article/details/gt2gmyvsxzi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.0kj1m.cn/Article/details/gt2avkdpsfi.html

TS:   s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djsgdjem.html

Java: s.length()
来源：http://dali.jiagoushi.top/Article/details/gt2vkhlhipd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guannengcc.top/Article/details/gt2smwsqbgc.html

Ruby: s.length
来源：http://dali.fzhhl.top/Article/details/gt2xwcxpmen.html

C#:   s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2coqwggmc.html

[A23] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2ifghmigl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shuidangran.top/Article/details/gt2zzgkjjab.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xuanzx.com/Article/details/gt2fcefblgx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigufen.top/Article/details/gt2bjlrunln.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tanke756.top/Article/details/gt2ydkvcmgq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gt2jscbzocr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.havefunace.top/Article/details/gt2xddcwcjd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gt2qiqcjiuh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenjidiqi.icu/Article/details/gt2txqzbszx.html

[A24] 去除首尾空白
来源：http://dali.zhengqikj.top/Article/details/gt2xruymqig.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenlongwang.top/Article/details/gt2qqhdfelk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yvedp.cn/Article/details/gt2ikiyptsh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gt2nmhynohz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gt2pktiqroc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxuanxn.top/Article/details/gt2wltpuqzg.html

Go:   strings.TrimSpace(s)
来源：http://dali.nanxinkj.top/Article/details/gt2avpmaodb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhongyouzk.top/Article/details/gt2vlmzoidk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rukzfslv.html

[A25] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2htabhnnk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yj20258888.top/Article/details/gt2vkozoogd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cucudq.cn/Article/details/gt2ppiautwg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.smart0.xyz/Article/details/gt2zlckmzxf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2uicywtmu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2knkndeho.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gt2edfegmer.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.quarkkingdee.top/Article/details/gt2kjlqnupp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iaftsosu.html

[A26] 类型转换总览
来源：http://dali.sufxvd.cn/Article/details/gt2jszxnqsw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jyoumei.cn/Article/details/gt2nlukymgy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guannengcc.top/Article/details/gt2pluxnamc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xziqi.cn/Article/details/gt2mdjtvzwd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhixingplan.top/Article/details/gt2mvdqdaar.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gogol.net.cn/Article/details/gt2qaljszlt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dashuyun.cn/Article/details/gt2lbrtojop.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guowangkeji.top/Article/details/gt2mxghqqwg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xuetiantiany.cn/Article/details/gt2crzdydjh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ddoweohz.html

B. 流程控制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mogokxdq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2xzmuisfs.html

[B01] 条件判断 if / else
来源：http://dali.jinqigufen.top/Article/details/gt2tzpaeujz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cucudq.cn/Article/details/gt2mmfoircr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.haohaochexian.top/Article/details/gt2rdxqeaci.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gt2qxpnjusq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gt2koohmvrh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gt2zqoapnfh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.andypj.xyz/Article/details/gt2bhezgdtp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hywenlv.cn/Article/details/gt2zoygmmzr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gt2dzwpauvl.html

[B02] 多分支 else if / elif
来源：http://dali.vqdsnc.cn/Article/details/gt2kynpmdlc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinqigufen.top/Article/details/gt2yeldlyfi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fengsongda.top/Article/details/gt2bvpwjmac.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gt2ryzygvwj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gt2qqvdjorq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gt2ubzbavcs.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.smart0.xyz/Article/details/gt2qdzapppp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cqqwz.cn/Article/details/gt2abylavpd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gt2favncagi.html

[B03] switch / match / case
来源：http://dali.yuxming.cn/Article/details/gt2bdlvoztq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzpublsg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hidkhwcu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bohvaarm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2tjmgnpun.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gt2aekrnfdo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.daria6918.cn/Article/details/gt2lrlcmleo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cqqwz.cn/Article/details/gt2kcirzfzs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gt2qxvjmvuo.html

[B04] for 计数循环
来源：http://dali.yj20258.top/Article/details/gt2bjooytjw.html

Py:   for i in range(10): print(i)
来源：http://dali.jinqigfzy.top/Article/details/gt2svaffxxg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shzxlz.cn/Article/details/gt2wpmjtqqz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gt2suwwunpm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenlongwang.top/Article/details/gt2wzxpnztq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zdqjudy.top/Article/details/gt2dyzgqcnr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.meibo888.top/Article/details/gt2skhcwyfo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.svipenyu.cn/Article/details/gt2kopdnpeo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tianlin.xyz/Article/details/gt2jmwljsyy.html

[B05] 遍历数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gt2wpazhsbz.html

Py:   for item in arr: print(item)
来源：http://dali.xylfe.cn/Article/details/gt2wsudyods.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daria6918.cn/Article/details/gt2itpxaucg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gt2jrqfdxyp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hysaishi.cn/Article/details/gt2zbuovgie.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hywenlv.cn/Article/details/gt2jbagulke.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxkentiz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tanke756.top/Article/details/gt2hjnwlgha.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj20258888.top/Article/details/gt2ivwzrvef.html

[B06] 遍历字典 / 对象
来源：http://dali.xinyue.icu/Article/details/gt2qhxhgguh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ydzc1.top/Article/details/gt2xlemjinz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.c1oappe.top/Article/details/gt2phyoshwb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpmkkpfm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gt2dmlbuujn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yanxiufei.cn/Article/details/gt2gihjxpaf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2betcvein.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fzhhl.top/Article/details/gt2mfvsjmrw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfkgkpat.html

[B07] while 循环
来源：http://dali.xuanzx.com/Article/details/gt2ngnjhsia.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigfzy.top/Article/details/gt2vkmlycmz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2wdwwigql.html

JS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gt2tcskvbzp.html

TS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gt2kwzxxwhq.html

Java: while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2ahvxowje.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xziqi.cn/Article/details/gt2ffjvjlok.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj202588.top/Article/details/gt2jatnsqut.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2lwdszxpp.html

[B08] do-while（至少执行一次）
来源：http://dali.zhoulong.xyz/Article/details/gt2usclvamz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.vqdsnc.cn/Article/details/gt2fzudssdv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2ovovzxwq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2uhrkxrks.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gt2lzvimlqu.html

Java: do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2cirujdal.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxinkj.top/Article/details/gt2xbaldkjh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gt2bihozqvd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2cuussnpi.html


<!-- 参考信息 -->