代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.iojbl.cn/Article/details/gtmmqdczaq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenjidiqi.icu/Article/details/gtcworbjjh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258888.top/Article/details/gtyitztrjt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sxryk.cn/Article/details/gtixhqfrey.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jiagoushi.top/Article/details/gtxfxyzuvv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtercdsjei.html

Go:   name := "Alex"; age := 20
来源：http://dali.tanke756.top/Article/details/gtjgjphfzo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dashuyun.cn/Article/details/gtxytxfswl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtgvgkgycz.html

[A03] 常量定义
来源：http://dali.jqgufenzy.top/Article/details/gtpbwcdmih.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gaohongyu789.top/Article/details/gtgmxtffnr.html

PHP:  const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtudkbwfro.html

JS:   const PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtootpkhqk.html

TS:   const PI: number = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtohazngzc.html

Java: static final double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtnmoxvhmv.html

Go:   const PI = 3.14159
来源：http://dali.yonumen.top/Article/details/gtpyyweofq.html

Ruby: PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gtimcxdxhc.html

C#:   const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtndfqjlyr.html

[A04] 判断变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtwbmjxhtq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgfzy.top/Article/details/gttfrlybla.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cucudq.cn/Article/details/gtrpwiidhk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.snrcjt.cn/Article/details/gtavkiharf.html

TS:   typeof x; x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gtiqltgyaf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.redwolf501.top/Article/details/gtysblowpy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinghuilouyu.cn/Article/details/gttpwihkjc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.birdmap.top/Article/details/gtmmwqutom.html

C#:   x.GetType().Name; x is int
来源：http://dali.mhx1999.top/Article/details/gttdplirst.html

[A05] 整数除法与取模
来源：http://dali.smart0.xyz/Article/details/gtfodkqpij.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.aizwys.cn/Article/details/gtuzibowtn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtmibqyxuo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtmjusoatc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtmhgahgcj.html

Java: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gtgwgajpeu.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtydgqlagu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtafytnopj.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtlfnlcrxi.html

[A06] 字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtnsogbwtn.html

Py:   int("42"); float("3.14")
来源：http://dali.snrcjt.cn/Article/details/gtxurlstdi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gaohongyu789.top/Article/details/gtlzvxpygc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.pycfn.com/Article/details/gtlniokhlj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yj20258888.top/Article/details/gtqsbxowtd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cucudq.cn/Article/details/gtkgpibjht.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.daxiang520.top/Article/details/gtahhqokis.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shzxlz.cn/Article/details/gtgoymqivx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jianghu66.top/Article/details/gtqxybheio.html

[A07] 数字转字符串
来源：http://dali.birdmap.top/Article/details/gtgyowjiic.html

Py:   str(42)
来源：http://dali.xinyue.icu/Article/details/gtuqugfuhf.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcoqdfzo.html

JS:   String(42); (42).toString()
来源：http://dali.birdmap.top/Article/details/gttjhtijwz.html

TS:   String(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtuxuqxmvd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tianlin.xyz/Article/details/gtxwilfvlz.html

Go:   strconv.Itoa(42)
来源：http://dali.ivvv.top/Article/details/gtkhbbplqj.html

Ruby: 42.to_s
来源：http://dali.wangdashe.top/Article/details/gtejaqyuuk.html

C#:   42.ToString()
来源：http://dali.yongpay.top/Article/details/gtffbxnims.html

[A08] 取整与四舍五入
来源：http://dali.jiagoushi.top/Article/details/gtuoyewzth.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtmjfuikas.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.iojbl.cn/Article/details/gtqobqzcry.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtayalqhzu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.andypj.xyz/Article/details/gthbkeobav.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gtyawbzdnq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtcaepsfph.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.sysykeji.top/Article/details/gtgufdcirr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtbvmqnmbj.html

[A09] 绝对值与最大最小值
来源：http://dali.jyoumei.cn/Article/details/gtyufekyuh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gthaagjdxy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtypgrbbpy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtwswgecld.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtbpupidbs.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gttzniylnq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhixingplan.top/Article/details/gtkuhxipio.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jianghu66.top/Article/details/gtwdhovptw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtcmyalgex.html

[A10] 生成随机数
来源：http://dali.tianlin.xyz/Article/details/gtttplcrnr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xziqi.cn/Article/details/gtrektccjl.html

PHP:  random_int(1, 100);
来源：http://dali.hysaishi.cn/Article/details/gtltzbebal.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ivvv.top/Article/details/gtlbdnwirn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guowangkeji.top/Article/details/gtojzuwmho.html

Java: new Random().nextInt(100) + 1
来源：http://dali.dashuyun.cn/Article/details/gtspwormal.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.smart0.xyz/Article/details/gtridsdwvd.html

Ruby: rand(1..100)
来源：http://dali.jinqigfzy.top/Article/details/gtdatblakk.html

C#:   new Random().Next(1, 101)
来源：http://dali.hongshengwenyu.top/Article/details/gthxwcqlqg.html

[A11] 条件表达式（三元）
来源：http://dali.snrcjt.cn/Article/details/gtbapxvwsm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhoulong.xyz/Article/details/gtnbuidunr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gthylptdcu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtfdqgknlu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtdeiloqtr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtuowhzjkd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj20258.top/Article/details/gtzhkupovu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtngicvhwi.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtrclhksqo.html

[A12] 字符串插值 / 格式化
来源：http://dali.ivvv.top/Article/details/gtzptjbpkb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ehwqpu.com/Article/details/gtkjwmroia.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnovcbrdb.html

JS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyhcgszf.html

TS:   `Hello, ${name}!`
来源：http://dali.yvedp.cn/Article/details/gttnxjafdw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zdqjudy.top/Article/details/gtyygeygof.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cashguo.top/Article/details/gtmyihbnox.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhongyouzk.top/Article/details/gtnlevhqrz.html

C#:   $"Hello, {name}!"
来源：http://dali.meibo888.top/Article/details/gtggxsohei.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.kuanghao11.cn/Article/details/gtvevxeeup.html

Py:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtonkzftda.html

PHP:  "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtrivddbiy.html

JS:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtqdmznmui.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtvzbftshi.html

Java: "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtuvzcckmy.html

Go:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtkaxbjtoz.html

Ruby: "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtocbpoxnw.html

C#:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtjhtgjumk.html

[A14] 注释写法
来源：http://dali.xuetiantiany.cn/Article/details/gtskjvaict.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yj20258888.top/Article/details/gtnewnflld.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtfwpnzxvp.html

JS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtmebacttp.html

TS:   // 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtuextbtuf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.guannengcc.top/Article/details/gtwrmakttv.html

Go:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gthamaahve.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cdnleiting.top/Article/details/gtxshtqecq.html

C#:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtdlphfjow.html

[A15] 空值判断与默认值
来源：http://dali.zhongyouzk.top/Article/details/gttekvkeqp.html

Py:   value = data or "默认值"
来源：http://dali.cheryme.top/Article/details/gtwpsxaaom.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gtopzmkelm.html

JS:   const value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gtkvxmdenk.html

TS:   const value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gtyhyupomn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258.top/Article/details/gtptvqeybm.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhengqikj.top/Article/details/gtgpghlqzz.html

Ruby: value = data || "默认值"
来源：http://dali.cucudq.cn/Article/details/gtscjnhbzt.html

C#:   var value = data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gtuamydmom.html

[A16] 真假值判断规则
来源：http://dali.dianchejie.cn/Article/details/gthbsaulvv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sysykeji.top/Article/details/gtsfjzqobp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zycfv.cn/Article/details/gtjiseyluh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shzxlz.cn/Article/details/gtybwguecx.html

TS:   if (!x) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyiyhrdam.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shzxlz.cn/Article/details/gtrhoaohca.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnconlem.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.dashuyun.cn/Article/details/gtqoigkjdz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.fengsongda.top/Article/details/gtvpidakcy.html

[A17] 位运算
来源：http://dali.shangyingyoupin.top/Article/details/gtyjyzygez.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtcrddqcub.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtteopgfbx.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtfkwmyetd.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtuyefqhga.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtevtyrsls.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gttnqitdbt.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtzjennork.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtcmvvgece.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yuanzhike.top/Article/details/gtzxlwxbin.html

Py:   ord("A"); chr(65)
来源：http://dali.hammf.cn/Article/details/gtcnexized.html

PHP:  ord("A"); chr(65)
来源：http://dali.hnqzz.top/Article/details/gtwtslnssn.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.quarkkingdee.top/Article/details/gtnycatrmj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258888.top/Article/details/gtjlifunlu.html

Java: (int) 'A'; (char) 65
来源：http://dali.bjfxy.top/Article/details/gtvxtkleph.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xuanzx.com/Article/details/gtxqotxaov.html

Ruby: "A".ord; 65.chr
来源：http://dali.guannengcc.top/Article/details/gtsmqgmcjh.html

C#:   (int)'A'; (char)65
来源：http://dali.jianghu66.top/Article/details/gtxblofszv.html

[A19] 交换两个变量
来源：http://dali.zdqjudy.top/Article/details/gtnxswqjlz.html

Py:   a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gtteyifcvq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwvhwqrt.html

JS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gtvilioztg.html

TS:   [a, b] = [b, a];
来源：http://dali.hfpthk.cn/Article/details/gterilwtnu.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxoynqdna.html

Go:   a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gtpehcywpl.html

Ruby: a, b = b, a
来源：http://dali.havefunace.top/Article/details/gtfgzpkfrj.html

C#:   (a, b) = (b, a);
来源：http://dali.cqqwz.cn/Article/details/gtekjhvfpu.html

[A20] 读取标准输入
来源：http://dali.pengpengdd.cyou/Article/details/gthvzhgkpm.html

Py:   name = input("请输入：")
来源：http://dali.jinqigfzy.top/Article/details/gtpoqfgict.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hongshengwenyu.top/Article/details/gtrlklfwre.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jiagoushi.top/Article/details/gtdggnsail.html

TS:   // Node.js：readline 模块
来源：http://dali.zycfv.cn/Article/details/gtrixluomm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqbwkrvj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhongyouzk.top/Article/details/gtimbcwhma.html

Ruby: gets.chomp
来源：http://dali.zhijiandao.cn/Article/details/gtfmqzqyzx.html

C#:   Console.ReadLine();
来源：http://dali.svipenyu.cn/Article/details/gtnziugsja.html

[A21] 保留指定小数位输出
来源：http://dali.hammf.cn/Article/details/gtxkcvlrpn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yangfankeji.com/Article/details/gtslbiftcu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtsdjkkzuy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtmjfbqyss.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gttnvuufvu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtaxkiqqya.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtrqycvqpk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkdyejao.html

C#:   3.14159.ToString("F2")
来源：http://dali.hywenlv.cn/Article/details/gtubcznpqs.html

[A22] 获取字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtcvxoafrb.html

Py:   len(s)
来源：http://dali.daxiang520.top/Article/details/gtfvmfiyof.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jiagoushi.top/Article/details/gtwjhbsdoi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.nwbrower.top/Article/details/gteyhajyht.html

TS:   s.length
来源：http://dali.zhijiandao.cn/Article/details/gtcnywblgg.html

Java: s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpztmifoq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.haohaochexian.top/Article/details/gtvfxeslfi.html

Ruby: s.length
来源：http://dali.hnqzz.top/Article/details/gtlkcntrsc.html

C#:   s.Length
来源：http://dali.dianchejie.cn/Article/details/gtsbptdwbj.html

[A23] 大小写转换
来源：http://dali.yonumen.top/Article/details/gticiytuqf.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sxryk.cn/Article/details/gtsansacky.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shzxlz.cn/Article/details/gtvdanvlpk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnqzz.top/Article/details/gtoqbxthjv.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gtcynszixw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gtvoesvpdq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ppjwa.cn/Article/details/gtgudnjgqr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtwjfugfwn.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nanxuanxn.top/Article/details/gtenjmbeuk.html

[A24] 去除首尾空白
来源：http://dali.ybcxt.top/Article/details/gtszcgrzjl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hywenlv.cn/Article/details/gtmedjdotf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.316326.xyz/Article/details/gtywiqtnur.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.snrcjt.cn/Article/details/gtssscqepk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxinkj.top/Article/details/gtivftwaxx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sysykeji.top/Article/details/gtrryabnxp.html

Go:   strings.TrimSpace(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtvuizasix.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenzaomai.com/Article/details/gtahkpabaj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinqigufen.top/Article/details/gtjsyrdttd.html

[A25] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtkmqzrbfg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.feifeiyinyue.top/Article/details/gtcyhkkrwu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttulbodig.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gtyaytyufv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtybfghulu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtzpjanqst.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.haohaochexian.top/Article/details/gtgpihfptt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimyduxic.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gtczgohbhp.html

[A26] 类型转换总览
来源：http://dali.c1oappe.top/Article/details/gtgxicnolw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhixingplan.top/Article/details/gtzkwnaifl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sweek.top/Article/details/gtfseydomq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.guannengcc.top/Article/details/gtbdapovjw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ybcxt.top/Article/details/gtbhqtjxol.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gtytqanfqi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guannengcc.top/Article/details/gtncurncgg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xziqi.cn/Article/details/gtwqrbtjer.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtfdcwvkqd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvnoqdegg.html

B. 流程控制
来源：http://dali.yuanzhike.top/Article/details/gtixzooqyj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqedosnpo.html

[B01] 条件判断 if / else
来源：http://dali.jiagoushi.top/Article/details/gtmtmnmbbe.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.quarkkingdee.top/Article/details/gtyeujmcjs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jiagoushi.top/Article/details/gtnnxktdwb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gthvhuzlwk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgwoyyum.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtcmsmsnes.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shzxlz.cn/Article/details/gticgbnlnb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jqgfzy.top/Article/details/gticwhffug.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gtbcnmdiqo.html

[B02] 多分支 else if / elif
来源：http://dali.xziqi.cn/Article/details/gtuxofxnyq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.c1oappe.top/Article/details/gtrvupcfya.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sufxvd.cn/Article/details/gtsuudpsls.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrtbzedk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtskcksxsz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtbordwuge.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuanzhike.top/Article/details/gthurbpkgz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hfpthk.cn/Article/details/gtqfkpqndh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtheakjmqw.html

[B03] switch / match / case
来源：http://dali.ydzc1.top/Article/details/gtyrzlplvc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cheryme.top/Article/details/gtofrvaqwh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtqfxuexrn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtlpalldfv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtkyniqxeo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtdwpmpncv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gtacovwdfx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gtnskppsfs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gtcrzhocrs.html

[B04] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gtugdrrzci.html

Py:   for i in range(10): print(i)
来源：http://dali.ehwqpu.com/Article/details/gtmwkonhax.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ivvv.top/Article/details/gtvyvzgsjx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gtilgsuqky.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gtegbsvwvh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.daria6918.cn/Article/details/gtasodxqyv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ybcxt.top/Article/details/gtkeokdovz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xinyue.icu/Article/details/gthnahmbrl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jqgfzy.top/Article/details/gtefmrencq.html

[B05] 遍历数组 / 列表
来源：http://dali.birdmap.top/Article/details/gttampcmuj.html

Py:   for item in arr: print(item)
来源：http://dali.sysykeji.top/Article/details/gtpofrzlfe.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gtodydliyn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gtbavvgfry.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtryuzhmqo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xuanzx.com/Article/details/gtihdvsiik.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shzxlz.cn/Article/details/gtachhncnz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hfpthk.cn/Article/details/gtdvdwmrid.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.meibo888.top/Article/details/gtyovgyoxd.html

[B06] 遍历字典 / 对象
来源：http://dali.wangshuangyany.cn/Article/details/gtunsbsyiu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sysykeji.top/Article/details/gtmwrjusbl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.daxiang520.top/Article/details/gttjltkxfe.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtibwufngn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gturyuhwqm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jlsjyb.cn/Article/details/gtoociyspm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gtqrqlberc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gogol.net.cn/Article/details/gtykuwaldf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gtuvrkxxvl.html

[B07] while 循环
来源：http://dali.sysykeji.top/Article/details/gtlkedfqja.html

Py:   while i < 10: i += 1
来源：http://dali.aibaodan.cn/Article/details/gtrdvcgwqb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pycfn.com/Article/details/gtmpjseuno.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtxquxwycu.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrbfximwe.html

Java: while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtexlocnqc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhixingplan.top/Article/details/gtqnkmewdt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jlsjyb.cn/Article/details/gtnqimpnlf.html

C#:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gthemjfnqt.html

[B08] do-while（至少执行一次）
来源：http://dali.gaohongyu789.top/Article/details/gtzniekntj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnxiangtu.top/Article/details/gtzewxpvib.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtjthbuhos.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtzwkvbrfd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtzaconlwn.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gteoctkyfc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yonumen.top/Article/details/gtjbmovhrv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pycfn.com/Article/details/gtkduebauw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtmopevjun.html


<!-- 参考信息 -->