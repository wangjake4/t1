代发 wailian999

Ruby: PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gthkgrqjjd.html

C#:   const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtbojipons.html

[A04] 判断变量类型
来源：http://dali.ehwqpu.com/Article/details/gtbmblssgg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.316326.xyz/Article/details/gtbjkjczeg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hongshengwenyu.top/Article/details/gtqkkfeurw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenzaomai.com/Article/details/gtdixdyrov.html

TS:   typeof x; x instanceof Date
来源：http://dali.316326.xyz/Article/details/gtrclmlwbu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cqqwz.cn/Article/details/gtfsqphmxs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yanxiufei.cn/Article/details/gtyhmbjzaf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ivvv.top/Article/details/gtgimkemxa.html

C#:   x.GetType().Name; x is int
来源：http://dali.hongshengwenyu.top/Article/details/gthcmvtjwl.html

[A05] 整数除法与取模
来源：http://dali.wangshuangyany.cn/Article/details/gtehbyjjrg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.bjfxy.top/Article/details/gtdhuadrbb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtxuarxjju.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gthcivgina.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gtfvfypxnw.html

Java: 7 / 2; 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtxbqpmaim.html

Go:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtoewlqdzd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gteuixnjgg.html

C#:   7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtwcxiixlp.html

[A06] 字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtputluair.html

Py:   int("42"); float("3.14")
来源：http://dali.yuxming.cn/Article/details/gtcawqwajo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhongyouzk.top/Article/details/gtkcchypqo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gtrgncfcal.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hywenlv.cn/Article/details/gtfstbrkma.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tanke756.top/Article/details/gtwfteiazc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.tian-w.cn/Article/details/gtoqsnyazi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.wangdashe.top/Article/details/gtceiweajg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gtmghqghim.html

[A07] 数字转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtrolryopk.html

Py:   str(42)
来源：http://dali.zycfv.cn/Article/details/gtfgxiwgro.html

PHP:  (string) 42; strval(42)
来源：http://dali.daria6918.cn/Article/details/gttmrocvhi.html

JS:   String(42); (42).toString()
来源：http://dali.yvedp.cn/Article/details/gtdqgwrreo.html

TS:   String(42)
来源：http://dali.zhengqikj.top/Article/details/gtsagofodz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ppjwa.cn/Article/details/gtauphmsko.html

Go:   strconv.Itoa(42)
来源：http://dali.zhoulong.xyz/Article/details/gthlrferim.html

Ruby: 42.to_s
来源：http://dali.yanxiufei.cn/Article/details/gtoykqiixs.html

C#:   42.ToString()
来源：http://dali.ehwqpu.com/Article/details/gtguoxjnnc.html

[A08] 取整与四舍五入
来源：http://dali.xuanzx.com/Article/details/gtqtiwbjuc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtouaybvzd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhixingplan.top/Article/details/gtzrchgznn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtvlnydtsr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmdpphia.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtmfqzbrcm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtbzycbhbh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.sysykeji.top/Article/details/gtcjxkgftl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtuglyfmie.html

[A09] 绝对值与最大最小值
来源：http://dali.xziqi.cn/Article/details/gtssfrymgc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtfesesanv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtzmwcaavd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtnwicipte.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtmquvnjci.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gtislxefyw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hywenlv.cn/Article/details/gtmqerdikg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jianghu66.top/Article/details/gtdmjetwdb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtgwypztot.html

[A10] 生成随机数
来源：http://dali.yanxiufei.cn/Article/details/gtfbusacno.html

Py:   import random; random.randint(1, 100)
来源：http://dali.feifeiyinyue.top/Article/details/gtyadartvx.html

PHP:  random_int(1, 100);
来源：http://dali.birdmap.top/Article/details/gtilyjsezl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmifsuvb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.quarkkingdee.top/Article/details/gtpkrxvzyi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.dashuyun.cn/Article/details/gtthnfjbak.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.dashuyun.cn/Article/details/gtjemfmsdm.html

Ruby: rand(1..100)
来源：http://dali.cqqwz.cn/Article/details/gtlvdcajti.html

C#:   new Random().Next(1, 101)
来源：http://dali.xylfe.cn/Article/details/gtssjayybh.html

[A11] 条件表达式（三元）
来源：http://dali.svipenyu.cn/Article/details/gtdfetrjln.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpqdsfiv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtxxpfxmeb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtziyinqac.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtpdrqebgk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtnnkqeadg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.guannengcc.top/Article/details/gtnyjognmq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtrxakaoqv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtvmknzfbg.html

[A12] 字符串插值 / 格式化
来源：http://dali.yuxming.cn/Article/details/gtrhbexgln.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.meibo888.top/Article/details/gtibniokhn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shangyingyoupin.top/Article/details/gtvamstazj.html

JS:   `Hello, ${name}!`
来源：http://dali.gotoacloud.top/Article/details/gtwcltooue.html

TS:   `Hello, ${name}!`
来源：http://dali.yanxiufei.cn/Article/details/gtmrnendyi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jqgufenzy.top/Article/details/gtrtnijbym.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhixingplan.top/Article/details/gtbwhukkmo.html

Ruby: "Hello, #{name}!"
来源：http://dali.andypj.xyz/Article/details/gtzqvftobx.html

C#:   $"Hello, {name}!"
来源：http://dali.9152youxi.cn/Article/details/gtcmmeiroj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nanxuanxn.top/Article/details/gtxnheesga.html

Py:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gtxslawoom.html

PHP:  "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtlftnhszl.html

JS:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtudsiumzt.html

TS:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtplqdzdno.html

Java: "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtjeylhcgy.html

Go:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtemfecfly.html

Ruby: "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtpypmdeyo.html

C#:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtprretyub.html

[A14] 注释写法
来源：http://dali.dashuyun.cn/Article/details/gtgohezvzg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzxeuqdu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtveudcjbp.html

JS:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gthbyoukqq.html

TS:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gthsohsgzz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmswfrhph.html

Go:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtwaqgkebc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jqgufenzy.top/Article/details/gtzxpqbtoz.html

C#:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtzjvxtnwh.html

[A15] 空值判断与默认值
来源：http://dali.sysykeji.top/Article/details/gtmunvkreo.html

Py:   value = data or "默认值"
来源：http://dali.iojbl.cn/Article/details/gthqpgibso.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtauoxkged.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtqevtndnf.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknclefcl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xinyue.icu/Article/details/gthnkedggu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xziqi.cn/Article/details/gtictqgeig.html

Ruby: value = data || "默认值"
来源：http://dali.havefunace.top/Article/details/gtuztupsvg.html

C#:   var value = data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gtpinzltpu.html

[A16] 真假值判断规则
来源：http://dali.zhengqikj.top/Article/details/gtucxgkqun.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtudrqjpkk.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yueranfly.top/Article/details/gtygjscgql.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.fzhhl.top/Article/details/gtynelmspv.html

TS:   if (!x) {}
来源：http://dali.aibaodan.cn/Article/details/gtpffkfyni.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.smart0.xyz/Article/details/gttbkgfewv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.pengpengdd.cyou/Article/details/gtefeyfyyy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.chenjidiqi.icu/Article/details/gtznlggzxx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gttgyvgivn.html

[A17] 位运算
来源：http://dali.0kj1m.cn/Article/details/gtdxwvnmqg.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtxsgidqke.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.wangdashe.top/Article/details/gtpwphufcq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gthyaoorng.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtfetoubnd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtzoidewzr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtacnwtlxr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtaastbveb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtuagilxcz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gtthimiion.html

Py:   ord("A"); chr(65)
来源：http://dali.hammf.cn/Article/details/gtkzjjwjml.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gttwgafilv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jlsjyb.cn/Article/details/gtqicutpzq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ehwqpu.com/Article/details/gtmnvxmbuh.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhiwuduotai.top/Article/details/gtofobuiaf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.redwolf501.top/Article/details/gtmguefpos.html

Ruby: "A".ord; 65.chr
来源：http://dali.hywenlv.cn/Article/details/gtvfekhjhl.html

C#:   (int)'A'; (char)65
来源：http://dali.jianghu66.top/Article/details/gttxohtddv.html

[A19] 交换两个变量
来源：http://dali.dianchejie.cn/Article/details/gtmsifoeyt.html

Py:   a, b = b, a
来源：http://dali.shanyushiyangtech.top/Article/details/gtktfrkspc.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xuanzx.com/Article/details/gtrtsiirsk.html

JS:   [a, b] = [b, a];
来源：http://dali.sweek.top/Article/details/gtvsvdfnre.html

TS:   [a, b] = [b, a];
来源：http://dali.redwolf501.top/Article/details/gtbrjiwtdb.html

Java: int t = a; a = b; b = t;
来源：http://dali.iojbl.cn/Article/details/gtldknmeaw.html

Go:   a, b = b, a
来源：http://dali.yj20258888.top/Article/details/gtshxyexnv.html

Ruby: a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gtbhnnpevf.html

C#:   (a, b) = (b, a);
来源：http://dali.316326.xyz/Article/details/gtglzumpjs.html

[A20] 读取标准输入
来源：http://dali.sweek.top/Article/details/gtywiupqun.html

Py:   name = input("请输入：")
来源：http://dali.zhijiandao.cn/Article/details/gtbcbzzolq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jlsjyb.cn/Article/details/gtccdwrlgz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangshuangyany.cn/Article/details/gtwrbgpcvh.html

TS:   // Node.js：readline 模块
来源：http://dali.svipenyu.cn/Article/details/gtzlkpeudr.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.daria6918.cn/Article/details/gttjardxrr.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenlongwang.top/Article/details/gteuwvwvsh.html

Ruby: gets.chomp
来源：http://dali.yj20258.top/Article/details/gtbtcwmrzu.html

C#:   Console.ReadLine();
来源：http://dali.fzhhl.top/Article/details/gttyhycmep.html

[A21] 保留指定小数位输出
来源：http://dali.birdmap.top/Article/details/gtlmlzythn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gaohongyu789.top/Article/details/gteitguvbo.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtboldpebe.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtefwgoyso.html

TS:   (3.14159).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtggmsogpx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gtzpmrjzgm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gtdkybroux.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacjdmmtc.html

C#:   3.14159.ToString("F2")
来源：http://dali.guowangkeji.top/Article/details/gtxlarliug.html

[A22] 获取字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtioltnahb.html

Py:   len(s)
来源：http://dali.havefunace.top/Article/details/gtcoydqlly.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofoonwth.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.feifeiyinyue.top/Article/details/gtpqrechmu.html

TS:   s.length
来源：http://dali.quarkkingdee.top/Article/details/gtddozwrij.html

Java: s.length()
来源：http://dali.cheryme.top/Article/details/gtobuudyfs.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.havefunace.top/Article/details/gtuktrttof.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gthhetwohg.html

C#:   s.Length
来源：http://dali.daria6918.cn/Article/details/gtyasbqomp.html

[A23] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtcljmocmq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shuidangran.top/Article/details/gtgvncdgmz.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuxming.cn/Article/details/gtqitbjpkk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gtxmfhhujp.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtqiakouzu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gthvcqetmf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtfntktxyf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gttbybsdqx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.mhx1999.top/Article/details/gtiwcmqekg.html

[A24] 去除首尾空白
来源：http://dali.cqqwz.cn/Article/details/gtsupxkfwe.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.pengpengdd.cyou/Article/details/gtbftruwpg.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxinkj.top/Article/details/gtravdfggz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtawjlqwgz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gtyjdssicr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcznssxnu.html

Go:   strings.TrimSpace(s)
来源：http://dali.vqdsnc.cn/Article/details/gtrmrktcwb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjwzysaz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yongpay.top/Article/details/gtbzzfnekj.html

[A25] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtshxtmpjy.html

Py:   s1 == s2; s1 != s2
来源：http://dali.havefunace.top/Article/details/gtakmdfmze.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gogol.net.cn/Article/details/gtkaxifqaf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangdashe.top/Article/details/gteuwitlfh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xinyue.icu/Article/details/gtezayfdxp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.dianchejie.cn/Article/details/gtvjqhlitz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenlongwang.top/Article/details/gtyaedbwpo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hfpthk.cn/Article/details/gtmtfkieep.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtmizibwvf.html

[A26] 类型转换总览
来源：http://dali.jlsjyb.cn/Article/details/gtdyfsaval.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shzxlz.cn/Article/details/gtokwdvaoo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xylfe.cn/Article/details/gteadipseb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gtwcqyciul.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxinkj.top/Article/details/gtdbegjpyn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gtkedhnnpe.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.316326.xyz/Article/details/gtskzykyzs.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yuanzhike.top/Article/details/gtoykxaacv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jianghu66.top/Article/details/gtgbhhhqpi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbmoarmyp.html

B. 流程控制
来源：http://dali.fzhhl.top/Article/details/gtmadpzshb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdqpeajie.html

[B01] 条件判断 if / else
来源：http://dali.nanxinkj.top/Article/details/gtaukygfiy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tanke756.top/Article/details/gtjdsbylfw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.wangdashe.top/Article/details/gtzgnvrkgl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtqopvypyv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtehsijnlp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtxwvxzpea.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guowangkeji.top/Article/details/gtmheprmye.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daria6918.cn/Article/details/gtebmhvnow.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtctukcw.html

[B02] 多分支 else if / elif
来源：http://dali.yangfankeji.com/Article/details/gtrityipmj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xylfe.cn/Article/details/gtxzyfvlnr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cheryme.top/Article/details/gtctykdmge.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtqsprrmxt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtjasgzkjw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gtrhawsliu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shangyingyoupin.top/Article/details/gtxaoqvbmk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.quarkkingdee.top/Article/details/gtosyrdusg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtqwiyejfa.html

[B03] switch / match / case
来源：http://dali.hammf.cn/Article/details/gtaxuctpjy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ppjwa.cn/Article/details/gtsmosdzxm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtzfvogedo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtcimneqmm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtuhetucqd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gthxuxuvbp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.daria6918.cn/Article/details/gtebybgfce.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gtucpvumbz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ivvv.top/Article/details/gtqrhnahqx.html

[B04] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtdszrfkxk.html

Py:   for i in range(10): print(i)
来源：http://dali.tianlin.xyz/Article/details/gtodlefmyh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.kuanghao11.cn/Article/details/gtyxhnkkjb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiccxreb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gtbyxvkztb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzzeppap.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangdashe.top/Article/details/gteugavfzp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.0kj1m.cn/Article/details/gttnhktyhr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpkzkspo.html

[B05] 遍历数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gtfjvlnzzq.html

Py:   for item in arr: print(item)
来源：http://dali.cucudq.cn/Article/details/gtcfogjyiu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ydzc1.top/Article/details/gtgsybfztc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtfevqtyeb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfwuvemji.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ppjwa.cn/Article/details/gtnjdttiir.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnqzz.top/Article/details/gtmpssufhv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwkelfwl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtdpgshqgc.html

[B06] 遍历字典 / 对象
来源：http://dali.zycfv.cn/Article/details/gtdnkmvone.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxinkj.top/Article/details/gtacwzlqfh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jlsjyb.cn/Article/details/gtgbmzrtps.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gtucswgiwq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtuggbyjhj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.redwolf501.top/Article/details/gtzqgnclyc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.aibaodan.cn/Article/details/gtgmtguiwu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tian-w.cn/Article/details/gtezmqywfa.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cashguo.top/Article/details/gtdooxzvqo.html

[B07] while 循环
来源：http://dali.dashuyun.cn/Article/details/gtsaeytxuy.html

Py:   while i < 10: i += 1
来源：http://dali.dashuyun.cn/Article/details/gtohshsrgb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj202588.top/Article/details/gtoiebsweo.html

JS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtkavfaoxg.html

TS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtecnkhovr.html

Java: while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtmrerpkni.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xziqi.cn/Article/details/gtsiexlbju.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhoulong.xyz/Article/details/gtumrfsgrq.html

C#:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtveuwgsdn.html

[B08] do-while（至少执行一次）
来源：http://dali.bjfxy.top/Article/details/gtpntvqsjf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.0kj1m.cn/Article/details/gtdgxgzjtt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guannengcc.top/Article/details/gtzlzhueyq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtyzlyfoyu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtpscnddtj.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtluaqqbgr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nwbrower.top/Article/details/gtsyrcpyow.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraaxuuwf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtheixxgot.html

[B09] break 与 continue
来源：http://dali.jiagoushi.top/Article/details/gtdkbbzhxr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.9152youxi.cn/Article/details/gtamabghcx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtezhpwvbq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtcxazogtr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gthaddmrmw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtuiowabns.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gtelllerbn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gtnpphvjto.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtivgqlskj.html

[B10] 遍历同时拿索引
来源：http://dali.wangshuangyany.cn/Article/details/gtkzlsacmj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gtqavriigr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jianghu66.top/Article/details/gtaogjgjzk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtpbryaguw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtqeyyhxdd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gtbdgjtkin.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gtcjetkmhe.html


<!-- 参考信息 -->