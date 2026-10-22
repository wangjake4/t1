代发 wailian999

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xziqi.cn/Article/details/gtpajnjuob.html

[A03] 常量定义
来源：http://dali.hysaishi.cn/Article/details/gthbsvtsif.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sxryk.cn/Article/details/gtssyfuxuv.html

PHP:  const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtrsvjhdsy.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtiwjwiely.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtcoeymfpy.html

Java: static final double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtcmpghwyx.html

Go:   const PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gtarvqxodi.html

Ruby: PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gtyyvwfmkr.html

C#:   const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtzjytdyij.html

[A04] 判断变量类型
来源：http://dali.xinyue.icu/Article/details/gtudebzfcr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tian-w.cn/Article/details/gtrdeilgbn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.meibo888.top/Article/details/gtizydtkfv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gzhubu.top/Article/details/gtevrwxptj.html

TS:   typeof x; x instanceof Date
来源：http://dali.yonumen.top/Article/details/gtcpkxmzua.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.mhx1999.top/Article/details/gtqrxavekt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cdnleiting.top/Article/details/gtnmlbdojo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nanxinkj.top/Article/details/gtscchlwnb.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj20258.top/Article/details/gtqyjxekpj.html

[A05] 整数除法与取模
来源：http://dali.aizwys.cn/Article/details/gtjeznnnfi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.mhx1999.top/Article/details/gtxedliutt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtifjsqrui.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtmkvsshfq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtiyxtxpot.html

Java: 7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtzquoxoak.html

Go:   7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtphdrkuzw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtbgcpsbze.html

C#:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtvgdiipwt.html

[A06] 字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtaggedyfy.html

Py:   int("42"); float("3.14")
来源：http://dali.fzhhl.top/Article/details/gtwavxyesg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gaohongyu789.top/Article/details/gtprdguqaf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gteiplakai.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.svipenyu.cn/Article/details/gtdjjsmmru.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gtsenzhgrd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj20258.top/Article/details/gtvccxubgk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhongyouzk.top/Article/details/gtyhhzsqhj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yueranfly.top/Article/details/gtyvyyahlr.html

[A07] 数字转字符串
来源：http://dali.cqqwz.cn/Article/details/gtsxiwtsrq.html

Py:   str(42)
来源：http://dali.kuanghao11.cn/Article/details/gtvxjcumpu.html

PHP:  (string) 42; strval(42)
来源：http://dali.0kj1m.cn/Article/details/gticzwatqu.html

JS:   String(42); (42).toString()
来源：http://dali.gaohongyu789.top/Article/details/gtuqceddqf.html

TS:   String(42)
来源：http://dali.birdmap.top/Article/details/gtdkqvxbem.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.smart0.xyz/Article/details/gtvjoctwdl.html

Go:   strconv.Itoa(42)
来源：http://dali.xylfe.cn/Article/details/gtfavpuftg.html

Ruby: 42.to_s
来源：http://dali.pycfn.com/Article/details/gtsfesksne.html

C#:   42.ToString()
来源：http://dali.jyoumei.cn/Article/details/gtiectwwkq.html

[A08] 取整与四舍五入
来源：http://dali.hysaishi.cn/Article/details/gtdiysmomq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gteqdlxraj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ivvv.top/Article/details/gtlnnnrfah.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtyxrjajyz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.aizwys.cn/Article/details/gtubmbvaca.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbohmdmmy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtxjhkirkj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenjidiqi.icu/Article/details/gtqazhwgye.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtyezyfgqd.html

[A09] 绝对值与最大最小值
来源：http://dali.yj202588.top/Article/details/gtondebobf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtiglcmjlg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtjjwemmbf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtenkxuqnk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtbxmmilbj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtzfcstspi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yuxming.cn/Article/details/gtfytabcai.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sysykeji.top/Article/details/gtnlxyidlb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtyyqarjbh.html

[A10] 生成随机数
来源：http://dali.ivvv.top/Article/details/gtnpvflfcf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtneyyyvfe.html

PHP:  random_int(1, 100);
来源：http://dali.yanxiufei.cn/Article/details/gtdynooorj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yuxming.cn/Article/details/gtcdqywqqh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgbrnpgr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.nwbrower.top/Article/details/gtnajmwllq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yonumen.top/Article/details/gtbrjgvcmx.html

Ruby: rand(1..100)
来源：http://dali.zdqjudy.top/Article/details/gtbkqoaoap.html

C#:   new Random().Next(1, 101)
来源：http://dali.birdmap.top/Article/details/gtdxtinxta.html

[A11] 条件表达式（三元）
来源：http://dali.jiagoushi.top/Article/details/gtwemgsnkp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gogol.net.cn/Article/details/gtbxfldgvr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gtaiwfxeho.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtnlzyxbhq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gtqjecubah.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtcisheiau.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.redwolf501.top/Article/details/gtgzwlxybe.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtwzoofmha.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxygebxid.html

[A12] 字符串插值 / 格式化
来源：http://dali.tianlin.xyz/Article/details/gtufvhigdd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.fzhhl.top/Article/details/gtejktmmxw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbcrldqo.html

JS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gthyxiqrbh.html

TS:   `Hello, ${name}!`
来源：http://dali.chenzaomai.com/Article/details/gtfscsztzs.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cucudq.cn/Article/details/gtsaesqlhy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gotoacloud.top/Article/details/gtxaczorip.html

Ruby: "Hello, #{name}!"
来源：http://dali.zdqjudy.top/Article/details/gtbltbgkeo.html

C#:   $"Hello, {name}!"
来源：http://dali.hongshengwenyu.top/Article/details/gtjzwqmvmi.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shangyingyoupin.top/Article/details/gtrrkbmgbq.html

Py:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtgqliwvsd.html

PHP:  "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtqlbhsfni.html

JS:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtqqzcszxr.html

TS:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtuhkfqtek.html

Java: "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtgbjandlc.html

Go:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gturwyemkg.html

Ruby: "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gtktxtvfnq.html

C#:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtvypvoanp.html

[A14] 注释写法
来源：http://dali.aibaodan.cn/Article/details/gtpoivthzo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.iojbl.cn/Article/details/gtnqkanvme.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtkfwexjrz.html

JS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohfszkju.html

TS:   // 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gtczwiisba.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xinyue.icu/Article/details/gtsfedzeim.html

Go:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtywxyzmub.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidbldflo.html

C#:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtqxvqvaao.html

[A15] 空值判断与默认值
来源：http://dali.gaohongyu789.top/Article/details/gtqehcovfe.html

Py:   value = data or "默认值"
来源：http://dali.sxryk.cn/Article/details/gtvwmkylrl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtlektugmn.html

JS:   const value = data ?? "默认值";
来源：http://dali.yueranfly.top/Article/details/gtzjohkwuy.html

TS:   const value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gtkjlylhgb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jyoumei.cn/Article/details/gtdibdalhl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgvxyqcq.html

Ruby: value = data || "默认值"
来源：http://dali.yanxiufei.cn/Article/details/gthvnefrex.html

C#:   var value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gtqemgpgpc.html

[A16] 真假值判断规则
来源：http://dali.gotoacloud.top/Article/details/gtvmjovjkq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gzhubu.top/Article/details/gtiebpatib.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnxiangtu.top/Article/details/gtweadgimm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sufxvd.cn/Article/details/gtwlgbkcqv.html

TS:   if (!x) {}
来源：http://dali.yueranfly.top/Article/details/gtjjcnmkml.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrdcqgey.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jyoumei.cn/Article/details/gtnsmshjam.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj20258.top/Article/details/gtefayueet.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hnqzz.top/Article/details/gtiklgkbag.html

[A17] 位运算
来源：http://dali.xziqi.cn/Article/details/gtdgjuacsf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtcaepjgvm.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.c1oappe.top/Article/details/gtbxdazwuq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtqbfirouj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtndgtenky.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtnvpmdkvv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtasyhjfmm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtmmmktcol.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtvfxmbzyd.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gotoacloud.top/Article/details/gtxuviwspv.html

Py:   ord("A"); chr(65)
来源：http://dali.smart0.xyz/Article/details/gtahwoxhyq.html

PHP:  ord("A"); chr(65)
来源：http://dali.sxryk.cn/Article/details/gtqmqhidue.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenlongwang.top/Article/details/gtrpayrusi.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gtlmlnjjlr.html

Java: (int) 'A'; (char) 65
来源：http://dali.haohaochexian.top/Article/details/gthnxawgoh.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sweek.top/Article/details/gtlsjbruug.html

Ruby: "A".ord; 65.chr
来源：http://dali.yonumen.top/Article/details/gtjgtqgdds.html

C#:   (int)'A'; (char)65
来源：http://dali.haohaochexian.top/Article/details/gtgfjxdedc.html

[A19] 交换两个变量
来源：http://dali.pycfn.com/Article/details/gtjdwfzery.html

Py:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtifarjrml.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.quarkkingdee.top/Article/details/gtkwdidhqf.html

JS:   [a, b] = [b, a];
来源：http://dali.ivvv.top/Article/details/gtrutujswb.html

TS:   [a, b] = [b, a];
来源：http://dali.hysaishi.cn/Article/details/gthgvficsw.html

Java: int t = a; a = b; b = t;
来源：http://dali.nanxuanxn.top/Article/details/gtpriecuzi.html

Go:   a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gteytaiqul.html

Ruby: a, b = b, a
来源：http://dali.jqgfzy.top/Article/details/gtlfvcuwqv.html

C#:   (a, b) = (b, a);
来源：http://dali.xuetiantiany.cn/Article/details/gttyycymxx.html

[A20] 读取标准输入
来源：http://dali.zhixingplan.top/Article/details/gtulucffky.html

Py:   name = input("请输入：")
来源：http://dali.andypj.xyz/Article/details/gtqkpvmffl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhixingplan.top/Article/details/gtebnjwdfq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jqgfzy.top/Article/details/gtqvtorvis.html

TS:   // Node.js：readline 模块
来源：http://dali.smart0.xyz/Article/details/gtwatrhunm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.guowangkeji.top/Article/details/gtzicafnoo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jianghu66.top/Article/details/gtgilkuons.html

Ruby: gets.chomp
来源：http://dali.shanyushiyangtech.top/Article/details/gtituwoqre.html

C#:   Console.ReadLine();
来源：http://dali.nanxinkj.top/Article/details/gtopustctw.html

[A21] 保留指定小数位输出
来源：http://dali.shangyingyoupin.top/Article/details/gtgsfmoosh.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yangfankeji.com/Article/details/gtcvokrjbp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gtqcxianxm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtopkygems.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtictzfolt.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gtwhrsfigh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gtgawujarb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtotawzhix.html

C#:   3.14159.ToString("F2")
来源：http://dali.iojbl.cn/Article/details/gtgvydpziy.html

[A22] 获取字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtooivzrcc.html

Py:   len(s)
来源：http://dali.daxiang520.top/Article/details/gtbxliupdl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gogol.net.cn/Article/details/gtehcwpxpc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yuanzhike.top/Article/details/gttdgbsbjy.html

TS:   s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdearmwip.html

Java: s.length()
来源：http://dali.guowangkeji.top/Article/details/gtdvphqlvo.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xylfe.cn/Article/details/gtldtkztwt.html

Ruby: s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtsxppvlxx.html

C#:   s.Length
来源：http://dali.guowangkeji.top/Article/details/gtkztrwccj.html

[A23] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtsnrynlkx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sweek.top/Article/details/gtvwzcjeoz.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ydzc1.top/Article/details/gtwboakbii.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gtecpmlihq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gthkemezok.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gtddxlexxl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtfdblbzfk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtkvouzmey.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.birdmap.top/Article/details/gtmqoyfuus.html

[A24] 去除首尾空白
来源：http://dali.yongpay.top/Article/details/gtzakmjvtx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.meibo888.top/Article/details/gtcvokxohd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cucudq.cn/Article/details/gtwjwckgat.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtmnsdooyr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258888.top/Article/details/gthuyjlxvv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jiagoushi.top/Article/details/gtiniwwriq.html

Go:   strings.TrimSpace(s)
来源：http://dali.jlsjyb.cn/Article/details/gtsoqvlfku.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yanxiufei.cn/Article/details/gtunldxfzi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cucudq.cn/Article/details/gtisfqhbxs.html

[A25] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gtwwtuafxc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hnxiangtu.top/Article/details/gtdabkfkcw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zycfv.cn/Article/details/gtyorclcjo.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gtrupccnag.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangdashe.top/Article/details/gtbcrdtrob.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.bjfxy.top/Article/details/gtytgmhnbz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtidgfutli.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shzxlz.cn/Article/details/gttjyjqyhu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.9152youxi.cn/Article/details/gtyvgladcq.html

[A26] 类型转换总览
来源：http://dali.vqdsnc.cn/Article/details/gteylrelni.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.iojbl.cn/Article/details/gtgknpldaj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yvedp.cn/Article/details/gtzuvcvwji.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cqqwz.cn/Article/details/gtvrqrcyni.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yongpay.top/Article/details/gtmqpahrtv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gtqwhaezxw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.kuanghao11.cn/Article/details/gtsmxqvxal.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cashguo.top/Article/details/gtfdcourax.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gtnhodgutr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gttrlmwffh.html

B. 流程控制
来源：http://dali.zhengqikj.top/Article/details/gtbxvpdnme.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxkkgncby.html

[B01] 条件判断 if / else
来源：http://dali.jlsjyb.cn/Article/details/gtbwdtipvw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nwbrower.top/Article/details/gtjjnpwoti.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xinyue.icu/Article/details/gtljbkhxlb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtjxgifkzm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtftyizhta.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtxsrbnuvp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.redwolf501.top/Article/details/gtzldkjubd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.snrcjt.cn/Article/details/gtcjxzpksz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gtepkzxuoj.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gtietzjygy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sweek.top/Article/details/gthrjjydqk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jlsjyb.cn/Article/details/gtobiqeccx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtkgsaqhmh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtaxxigudh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtwytbosdm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pengpengdd.cyou/Article/details/gtzplicbsh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tian-w.cn/Article/details/gtxkinexcc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gthrsplkfl.html

[B03] switch / match / case
来源：http://dali.yuxming.cn/Article/details/gtvwyidzbw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenlongwang.top/Article/details/gtnnohlrky.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtxwmnzmlv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtzfwsfmfc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gtaoxezqek.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfgsljkct.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gtgpdtjlhp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinghuilouyu.cn/Article/details/gtretvodyb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.dashuyun.cn/Article/details/gtzfxzfmbt.html

[B04] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtdhzimbln.html

Py:   for i in range(10): print(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowtycrgm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ybcxt.top/Article/details/gtuzdvwkka.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtsasorjir.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gtqlfouhfo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hnqzz.top/Article/details/gtfmduvsxu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ybcxt.top/Article/details/gtboqycatn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ehwqpu.com/Article/details/gtuwjrboyx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.c1oappe.top/Article/details/gtpmdzxwxf.html

[B05] 遍历数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywzdpnox.html

Py:   for item in arr: print(item)
来源：http://dali.jqgfzy.top/Article/details/gtzzekmgpu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yanxiufei.cn/Article/details/gtwtxfyqvl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gtmodtcnqm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gtpaxhukcp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtbvhpncub.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangshuangyany.cn/Article/details/gtdufwenrc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigfzy.top/Article/details/gtnrsgqtwc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guowangkeji.top/Article/details/gtokmpgucw.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gtxksiliob.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tianlin.xyz/Article/details/gtcicczzdd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvfswcon.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sysykeji.top/Article/details/gtspdawbqa.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gtfbupilig.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zdqjudy.top/Article/details/gtwoyvgejb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.andypj.xyz/Article/details/gtzvgnqkon.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fzhhl.top/Article/details/gtogqirowu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cashguo.top/Article/details/gtoobhmjcj.html

[B07] while 循环
来源：http://dali.shuidangran.top/Article/details/gtmtvufftp.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtngynrhkx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtphkpsprl.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtbqpzartr.html

TS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gthwehjeur.html

Java: while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtcjthxvuk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xziqi.cn/Article/details/gtizmgwhsp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hfpthk.cn/Article/details/gtwqcpnwpd.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtmqcasxcs.html

[B08] do-while（至少执行一次）
来源：http://dali.meibo888.top/Article/details/gtccnslvwd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tanke756.top/Article/details/gtwpziedwe.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuumqxng.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtshgoidkt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gthifyvvxn.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtnklagktn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yangfankeji.com/Article/details/gtimndqeze.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gtlbhelajf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupckksjf.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gtwmxafycj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj202588.top/Article/details/gtbaitatan.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtcqbhtwkk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtpnyadtwp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtilvisshi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtmkburbup.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gtkvjwozcf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gtuhiijfvq.html


<!-- 参考信息 -->