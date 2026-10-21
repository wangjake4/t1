代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.snrcjt.cn/Article/details/gtdfnydesb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ppjwa.cn/Article/details/gtkzlcercq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.pycfn.com/Article/details/gtljgvggcu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtyffowoia.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtltqcilkd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtcgeiczgk.html

Go:   name := "Alex"; age := 20
来源：http://dali.havefunace.top/Article/details/gtjsllvcpj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.pengpengdd.cyou/Article/details/gtbwhrdqsx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gtmgjhhhrz.html

[A03] 常量定义
来源：http://dali.0kj1m.cn/Article/details/gtbfsrwbwe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hywenlv.cn/Article/details/gtgwicnnch.html

PHP:  const PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtockykuka.html

JS:   const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gttxcjdkkb.html

TS:   const PI: number = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtpiuahtzz.html

Java: static final double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtoszyokon.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangtech.top/Article/details/gtpurdwbio.html

Ruby: PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtrfvssfgb.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtitnetoib.html

[A04] 判断变量类型
来源：http://dali.xinyue.icu/Article/details/gtxvbkqwpp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj20258.top/Article/details/gtrbzlupxm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhongyouzk.top/Article/details/gtyiehyyqg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gtfvwmqnvb.html

TS:   typeof x; x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gtztptxpua.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jianghu66.top/Article/details/gthjsrgbnm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlehxgwp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrymrisas.html

C#:   x.GetType().Name; x is int
来源：http://dali.yueranfly.top/Article/details/gtykdotksd.html

[A05] 整数除法与取模
来源：http://dali.zycfv.cn/Article/details/gtusdzfiku.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xylfe.cn/Article/details/gtozmipsnr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtehkeyson.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gttqjqyfdh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtxljgttch.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtyjhlyfrx.html

Go:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtgpkoxjdz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtyezdtwlt.html

C#:   7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtglifgrpt.html

[A06] 字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtixideued.html

Py:   int("42"); float("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtduqsuukj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zdqjudy.top/Article/details/gtaelpsutf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jianghu66.top/Article/details/gteloihjxo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.wangdashe.top/Article/details/gtqhuervgb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tian-w.cn/Article/details/gtbdqfouvt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gogol.net.cn/Article/details/gtfszzhpyf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.dianchejie.cn/Article/details/gttpyqorqf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xziqi.cn/Article/details/gtpgxiizdo.html

[A07] 数字转字符串
来源：http://dali.jyoumei.cn/Article/details/gtvyvhgajs.html

Py:   str(42)
来源：http://dali.tianlin.xyz/Article/details/gtzaqlhnpu.html

PHP:  (string) 42; strval(42)
来源：http://dali.snrcjt.cn/Article/details/gttecyxlrg.html

JS:   String(42); (42).toString()
来源：http://dali.dashuyun.cn/Article/details/gtxxmlrowq.html

TS:   String(42)
来源：http://dali.cheryme.top/Article/details/gtwhgznmwz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.0kj1m.cn/Article/details/gtbkfqwwdd.html

Go:   strconv.Itoa(42)
来源：http://dali.mhx1999.top/Article/details/gtqymgplqe.html

Ruby: 42.to_s
来源：http://dali.xziqi.cn/Article/details/gtqtlkawzf.html

C#:   42.ToString()
来源：http://dali.jyoumei.cn/Article/details/gtegblncam.html

[A08] 取整与四舍五入
来源：http://dali.hammf.cn/Article/details/gthbhpqigu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtyvkpdztq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhoulong.xyz/Article/details/gttakknnac.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gtwisjvism.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guannengcc.top/Article/details/gtpttpufkj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtarcearuq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gtcoaoxcuc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.daxiang520.top/Article/details/gtyqfawfsp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtsizasehi.html

[A09] 绝对值与最大最小值
来源：http://dali.xinyue.icu/Article/details/gtnmcamegv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmtyrjiw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtlaxqwqmc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtynhbdkwc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtltkteadb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtdxbekjlw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.meibo888.top/Article/details/gtidmqydzx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sysykeji.top/Article/details/gtvcmwwvjr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtaifoavxs.html

[A10] 生成随机数
来源：http://dali.fengsongda.top/Article/details/gttddwulaz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.birdmap.top/Article/details/gtkgtiwqqy.html

PHP:  random_int(1, 100);
来源：http://dali.yj202588.top/Article/details/gtmmjejevm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdworfpyg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhiwuduotai.top/Article/details/gtmjirfrva.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hammf.cn/Article/details/gtolqlqief.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.birdmap.top/Article/details/gtmtraszzl.html

Ruby: rand(1..100)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxubdyii.html

C#:   new Random().Next(1, 101)
来源：http://dali.jqgfzy.top/Article/details/gtmjfdtemu.html

[A11] 条件表达式（三元）
来源：http://dali.zhiwuduotai.top/Article/details/gtwolygbgi.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gogol.net.cn/Article/details/gtlijkimvf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtmaqbeyve.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtajefrsui.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtcsdfpkll.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtgqldgsvt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yvedp.cn/Article/details/gtpdnukepm.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtqxwxdplf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtbmtpwnpo.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gthqnuedue.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.9152youxi.cn/Article/details/gtlbpvaybr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.pengpengdd.cyou/Article/details/gtikhgvwtx.html

JS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gtxinjohjk.html

TS:   `Hello, ${name}!`
来源：http://dali.zhongyouzk.top/Article/details/gtdiyhmjiv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zdqjudy.top/Article/details/gtxuexapzr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhoulong.xyz/Article/details/gtbqbiyjfh.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinqigfzy.top/Article/details/gtcxlemgfu.html

C#:   $"Hello, {name}!"
来源：http://dali.daxiang520.top/Article/details/gtlrntyrgu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nanxuanxn.top/Article/details/gtnwsjapej.html

Py:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gttximhthu.html

PHP:  "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtmsdlorbv.html

JS:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtbbajdjlz.html

TS:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtlyjvhicv.html

Java: "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtnsuwkapn.html

Go:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwehwqdaa.html

Ruby: "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgghwuodr.html

C#:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtrjcvrqom.html

[A14] 注释写法
来源：http://dali.zdqjudy.top/Article/details/gtjsugtpam.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhxlmowr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtsesfdvvx.html

JS:   // 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gtploiwpni.html

TS:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtzyjssenz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yj20258888.top/Article/details/gtmhoahfgk.html

Go:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gthqdectbn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.guowangkeji.top/Article/details/gtrnnbkbbn.html

C#:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gtswmuuzdu.html

[A15] 空值判断与默认值
来源：http://dali.meibo888.top/Article/details/gthaoukupi.html

Py:   value = data or "默认值"
来源：http://dali.jinqigufen.top/Article/details/gtdqvdkwgp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gtzquoaqur.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtvcywnqov.html

TS:   const value = data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gtqgpgjwyn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hnxiangtu.top/Article/details/gtmfhdvovg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tanke756.top/Article/details/gtrprugjaf.html

Ruby: value = data || "默认值"
来源：http://dali.sufxvd.cn/Article/details/gtapqioeoo.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gtnmkygvci.html

[A16] 真假值判断规则
来源：http://dali.xuetiantiany.cn/Article/details/gtthbvqwqo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtvapmhmyi.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhengqikj.top/Article/details/gtjlxarclo.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gogol.net.cn/Article/details/gtclwrauwp.html

TS:   if (!x) {}
来源：http://dali.svipenyu.cn/Article/details/gtnzxaqprz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtbbleqcwg.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuanzx.com/Article/details/gtpnhkicqc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.bjfxy.top/Article/details/gthdkytucn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtlfiatdju.html

[A17] 位运算
来源：http://dali.snrcjt.cn/Article/details/gtxjuttume.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtshowfwuw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jianghu66.top/Article/details/gtjhfbohpk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtqizprhfq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtgyopcqgq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtcqyxoubn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtsnyjvobt.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdaifztw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtzkemwzmg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.iojbl.cn/Article/details/gtshttqyre.html

Py:   ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gtawcyqbwk.html

PHP:  ord("A"); chr(65)
来源：http://dali.hongshengwenyu.top/Article/details/gtaxqagkpc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hammf.cn/Article/details/gtuznepjfg.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gtnchapkti.html

Java: (int) 'A'; (char) 65
来源：http://dali.fzhhl.top/Article/details/gtqqurtpmw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.tanke756.top/Article/details/gtlpctupdi.html

Ruby: "A".ord; 65.chr
来源：http://dali.yj20258888.top/Article/details/gtosvljrjw.html

C#:   (int)'A'; (char)65
来源：http://dali.jqgufenzy.top/Article/details/gtaavrcfjd.html

[A19] 交换两个变量
来源：http://dali.svipenyu.cn/Article/details/gtnswxdyjz.html

Py:   a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtnnnnhitp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xuanzx.com/Article/details/gtlxbrgvgl.html

JS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gtvsdsgkds.html

TS:   [a, b] = [b, a];
来源：http://dali.jyoumei.cn/Article/details/gtflgzqqvk.html

Java: int t = a; a = b; b = t;
来源：http://dali.kuanghao11.cn/Article/details/gttwpjkpku.html

Go:   a, b = b, a
来源：http://dali.chenlongwang.top/Article/details/gtwwxpccrw.html

Ruby: a, b = b, a
来源：http://dali.svipenyu.cn/Article/details/gtjngkzeal.html

C#:   (a, b) = (b, a);
来源：http://dali.tianlin.xyz/Article/details/gtsusxzfow.html

[A20] 读取标准输入
来源：http://dali.xinyue.icu/Article/details/gtntudwepa.html

Py:   name = input("请输入：")
来源：http://dali.bjfxy.top/Article/details/gtukhomtwv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cqqwz.cn/Article/details/gtqtmzttyv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinqigfzy.top/Article/details/gtwjmukjhz.html

TS:   // Node.js：readline 模块
来源：http://dali.gaohongyu789.top/Article/details/gtrsskkgoq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shangyingyoupin.top/Article/details/gtasxmnfzs.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yonumen.top/Article/details/gtcrrjeghp.html

Ruby: gets.chomp
来源：http://dali.cheryme.top/Article/details/gtexgfrmhf.html

C#:   Console.ReadLine();
来源：http://dali.gotoacloud.top/Article/details/gtsgogckum.html

[A21] 保留指定小数位输出
来源：http://dali.snrcjt.cn/Article/details/gtfyewpawx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.mhx1999.top/Article/details/gtogwyxjmq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gttwnyxbsc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gtybxvwnel.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtligbjktg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gtwotdkbak.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gtrcruzoso.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gthqehyyxk.html

C#:   3.14159.ToString("F2")
来源：http://dali.yanxiufei.cn/Article/details/gtaicwwdmg.html

[A22] 获取字符串长度
来源：http://dali.yj20258.top/Article/details/gtnmbykqiz.html

Py:   len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwbltroty.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.9152youxi.cn/Article/details/gtaywupvst.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinqigufen.top/Article/details/gttekwowbp.html

TS:   s.length
来源：http://dali.jqgufenzy.top/Article/details/gthruyfydr.html

Java: s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthoqkrbvv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.fengsongda.top/Article/details/gtdbispktt.html

Ruby: s.length
来源：http://dali.cucudq.cn/Article/details/gtscjlmptg.html

C#:   s.Length
来源：http://dali.ppjwa.cn/Article/details/gtakhkprov.html

[A23] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtgwdorvgl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.meibo888.top/Article/details/gtjzwsemoh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cheryme.top/Article/details/gtozkfxbjk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtppcygkxh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtdtcrgtmh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gtwvavcyuu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.fzhhl.top/Article/details/gtugjsesgh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.fzhhl.top/Article/details/gtnndafubw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sxryk.cn/Article/details/gtqdivsbag.html

[A24] 去除首尾空白
来源：http://dali.chenlongwang.top/Article/details/gttvfostty.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.birdmap.top/Article/details/gthkqzpmki.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.daria6918.cn/Article/details/gttdzkwjkh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daria6918.cn/Article/details/gtgztcdjei.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gtmkffcoqw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.vqdsnc.cn/Article/details/gttbpwhjwc.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhixingplan.top/Article/details/gtvttbjarj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jianghu66.top/Article/details/gtccgyjvwa.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.fengsongda.top/Article/details/gtaktgvekt.html

[A25] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtduochxoi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cheryme.top/Article/details/gtnhocjfcs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.9152youxi.cn/Article/details/gtezlrzwex.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daxiang520.top/Article/details/gthrzpvdgo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gtphanbjjb.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shuidangran.top/Article/details/gtvstsjavu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gterptqjyd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ppjwa.cn/Article/details/gtnajnwnvp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbiieqlwh.html

[A26] 类型转换总览
来源：http://dali.aibaodan.cn/Article/details/gtfmhgftsf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.haohaochexian.top/Article/details/gtbwrsreqq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.wangdashe.top/Article/details/gtxdkwhtga.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cqqwz.cn/Article/details/gtssndjvao.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hywenlv.cn/Article/details/gtzyozrgga.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.mhx1999.top/Article/details/gtqyrxlrzh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aibaodan.cn/Article/details/gtzrfkuwsu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xinyue.icu/Article/details/gtijksszgd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshbupddt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfdnnchgb.html

B. 流程控制
来源：http://dali.guowangkeji.top/Article/details/gtczitslpn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtkulhjxek.html

[B01] 条件判断 if / else
来源：http://dali.dashuyun.cn/Article/details/gtfbplmgcd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinqigufen.top/Article/details/gtntjogqwf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrzgmxec.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gtrjvxccrx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtpodgqjoa.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtytpqfiao.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgfzy.top/Article/details/gtclcvmktp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.birdmap.top/Article/details/gtudigetgu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtjaizfbmr.html

[B02] 多分支 else if / elif
来源：http://dali.jiagoushi.top/Article/details/gtgiojfijn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yvedp.cn/Article/details/gtzqpvgxev.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fengsongda.top/Article/details/gtmbgbotmz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtrbcffkhh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gteitvikkp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gtifjbjljz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hfpthk.cn/Article/details/gtkhkqsezb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258.top/Article/details/gtpcwkgdvi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtsbpkmexs.html

[B03] switch / match / case
来源：http://dali.snrcjt.cn/Article/details/gtusppzgtn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jlsjyb.cn/Article/details/gtvppwupqe.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtfrdygogf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtowfkksxr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtzqanurqt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtqflubleb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.haohaochexian.top/Article/details/gtcilzhsip.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hfpthk.cn/Article/details/gtairtrkoq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gttnfxyigx.html

[B04] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gttkqrvbio.html

Py:   for i in range(10): print(i)
来源：http://dali.daxiang520.top/Article/details/gtlocnearl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gzhubu.top/Article/details/gtodorisvp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gtxjktraia.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gtqhmfprxe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxuanxn.top/Article/details/gtquzpzqgu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jyoumei.cn/Article/details/gtzwevhgvu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gtmhnsthis.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sufxvd.cn/Article/details/gtwwoytixr.html

[B05] 遍历数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtylartzom.html

Py:   for item in arr: print(item)
来源：http://dali.tian-w.cn/Article/details/gtkdnfbycq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.0kj1m.cn/Article/details/gtpoizxylj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zycfv.cn/Article/details/gtfucckksu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfzfgwxt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdlcwxtse.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.kuanghao11.cn/Article/details/gtunuhzojf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gtegailnkd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.dashuyun.cn/Article/details/gtzljugldd.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxqxkpyq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.quarkkingdee.top/Article/details/gtnogoxfac.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ybcxt.top/Article/details/gtudiingwo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gtxjbyapxu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gtvyrbonbl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteawplcqz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yanxiufei.cn/Article/details/gtwxulazet.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.kuanghao11.cn/Article/details/gtthoesbuk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnhvulho.html

[B07] while 循环
来源：http://dali.cqqwz.cn/Article/details/gtnaxdoakl.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtzcjqldoc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenzaomai.com/Article/details/gtbvlysdic.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gttzucifxy.html

TS:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gtqbtdvhei.html

Java: while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtriqazexp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cheryme.top/Article/details/gtonoqnuhe.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dashuyun.cn/Article/details/gtzasnlmar.html

C#:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtwgapfqym.html

[B08] do-while（至少执行一次）
来源：http://dali.xziqi.cn/Article/details/gtotnkiakd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxuanxn.top/Article/details/gtgtbjfzoi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtmnaexcyk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtbkhjuxni.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gthlbawxru.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtoqbunkdq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtlmmevxff.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj202588.top/Article/details/gthsjmijhj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtupprwqys.html


<!-- 参考信息 -->