代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.0kj1m.cn/Article/details/gtwjhchzdm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dashuyun.cn/Article/details/gtmbqshvew.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtlciepctw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhixingplan.top/Article/details/gtqqfuxcph.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtvbzuvpaj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtdcntbial.html

Go:   name := "Alex"; age := 20
来源：http://dali.hywenlv.cn/Article/details/gtkvtvrjea.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jiagoushi.top/Article/details/gtrapzdxup.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtttvidlct.html

[A03] 常量定义
来源：http://dali.hywenlv.cn/Article/details/gtyopuofnq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.wangshuangyany.cn/Article/details/gtlnjejheh.html

PHP:  const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtkfbrgpiu.html

JS:   const PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtxooobgdn.html

TS:   const PI: number = 3.14159;
来源：http://dali.cheryme.top/Article/details/gthdqkqhap.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflousypz.html

Go:   const PI = 3.14159
来源：http://dali.yuanzhike.top/Article/details/gtllyxzxdr.html

Ruby: PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gtpucrxbsd.html

C#:   const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gthxhxkvkb.html

[A04] 判断变量类型
来源：http://dali.dashuyun.cn/Article/details/gtucazexpv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yangfankeji.com/Article/details/gtwyubhtut.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ehwqpu.com/Article/details/gtudhslkhy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gtrywiygzd.html

TS:   typeof x; x instanceof Date
来源：http://dali.xuanzx.com/Article/details/gtgmpsisgl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shangyingyoupin.top/Article/details/gtmxgohlpe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnqzz.top/Article/details/gtbivsuefb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.mhx1999.top/Article/details/gthgcelqqn.html

C#:   x.GetType().Name; x is int
来源：http://dali.tanke756.top/Article/details/gtoagekads.html

[A05] 整数除法与取模
来源：http://dali.andypj.xyz/Article/details/gtvlrvjqtt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.feifeiyinyue.top/Article/details/gtebnqfemp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gtmgbftmoe.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtnqhwzser.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtgeattaoy.html

Java: 7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtxaaacpnd.html

Go:   7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gttxugcnsr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtxelakqyy.html

C#:   7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gttjvtfnzi.html

[A06] 字符串转数字
来源：http://dali.sweek.top/Article/details/gtgcrshefe.html

Py:   int("42"); float("3.14")
来源：http://dali.sufxvd.cn/Article/details/gtkqdaoioo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nanxuanxn.top/Article/details/gtkrxleeki.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.svipenyu.cn/Article/details/gtgwrqbdsb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.guannengcc.top/Article/details/gtbqatkgff.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.dashuyun.cn/Article/details/gtmawfjyqe.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xziqi.cn/Article/details/gtcnrwtgcb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.snrcjt.cn/Article/details/gtfnguewhi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gtwuwxfheo.html

[A07] 数字转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtnedgtvqj.html

Py:   str(42)
来源：http://dali.yueranfly.top/Article/details/gtltalzeat.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopujzvtd.html

JS:   String(42); (42).toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtaclhqgds.html

TS:   String(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtpbgvuuej.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.pycfn.com/Article/details/gtksgfgsva.html

Go:   strconv.Itoa(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqoebczo.html

Ruby: 42.to_s
来源：http://dali.xylfe.cn/Article/details/gtiathpqci.html

C#:   42.ToString()
来源：http://dali.jinqigufen.top/Article/details/gtgljwtelq.html

[A08] 取整与四舍五入
来源：http://dali.gotoacloud.top/Article/details/gtzgfvsydo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gtzqeydpnc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxunxcwud.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtadxcdfei.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gaohongyu789.top/Article/details/gtpkjvzwwf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gtepmcvktg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtxfkixtbb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhixingplan.top/Article/details/gtihrjfxkq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbokgfbkc.html

[A09] 绝对值与最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtjekwbuak.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtufyqvsvk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtvxlyxkge.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtehznfrcl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gthuyzexfl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtzzkdxkwt.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xuetiantiany.cn/Article/details/gtqmyzoupz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sysykeji.top/Article/details/gtxeiqwdmq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtlfgregmp.html

[A10] 生成随机数
来源：http://dali.shuidangran.top/Article/details/gthfsmphho.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hfpthk.cn/Article/details/gtgwqmilpv.html

PHP:  random_int(1, 100);
来源：http://dali.wangshuangyany.cn/Article/details/gtemvlbwol.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gtqxqhzsfb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yvedp.cn/Article/details/gtzevkkmzk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.c1oappe.top/Article/details/gtwmiqlcqu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhengqikj.top/Article/details/gtvelssbim.html

Ruby: rand(1..100)
来源：http://dali.wangdashe.top/Article/details/gtinrsexsv.html

C#:   new Random().Next(1, 101)
来源：http://dali.ydzc1.top/Article/details/gtsjbhoycn.html

[A11] 条件表达式（三元）
来源：http://dali.sufxvd.cn/Article/details/gtjivgsjcf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.9152youxi.cn/Article/details/gtohagxvfh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gtfpuynqhu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxxcsrds.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtxsdcqlxd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtlfpvjgxz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.chenzaomai.com/Article/details/gtqdoarpzt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtpmipyfgk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtcidcdifh.html

[A12] 字符串插值 / 格式化
来源：http://dali.9152youxi.cn/Article/details/gtuhldnwls.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yonumen.top/Article/details/gtlqbznrhq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.guannengcc.top/Article/details/gtrhxyknrf.html

JS:   `Hello, ${name}!`
来源：http://dali.xuetiantiany.cn/Article/details/gtqxztvigb.html

TS:   `Hello, ${name}!`
来源：http://dali.ivvv.top/Article/details/gtkskhfecw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.snrcjt.cn/Article/details/gtptcfvhgz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zycfv.cn/Article/details/gtcdbnvkpq.html

Ruby: "Hello, #{name}!"
来源：http://dali.xylfe.cn/Article/details/gtybpxwuds.html

C#:   $"Hello, {name}!"
来源：http://dali.yanxiufei.cn/Article/details/gthxxruuvc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gtiuwivfup.html

Py:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtdhlyskpg.html

PHP:  "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtceobcufj.html

JS:   "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtdtjtjspi.html

TS:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtdijhqemq.html

Java: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtatyygvci.html

Go:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtrmhrbenu.html

Ruby: "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gtsrthngok.html

C#:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gttinrlotd.html

[A14] 注释写法
来源：http://dali.jiagoushi.top/Article/details/gtkeeklrhd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hywenlv.cn/Article/details/gtzrrenmpe.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtyopefgeq.html

JS:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbowxwmlu.html

TS:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gtxobklhnx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gaohongyu789.top/Article/details/gtwavzczae.html

Go:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtthaopcuz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yvedp.cn/Article/details/gtjjornodl.html

C#:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtxiylgedu.html

[A15] 空值判断与默认值
来源：http://dali.chenlongwang.top/Article/details/gtryzsdjtz.html

Py:   value = data or "默认值"
来源：http://dali.havefunace.top/Article/details/gtekvydpbd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gttqpxaljd.html

JS:   const value = data ?? "默认值";
来源：http://dali.zdqjudy.top/Article/details/gtqeefkxxp.html

TS:   const value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtlwvuytbv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.redwolf501.top/Article/details/gtrngwtfmy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.bjfxy.top/Article/details/gtyaesouzl.html

Ruby: value = data || "默认值"
来源：http://dali.yj20258888.top/Article/details/gtlipkmnzb.html

C#:   var value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtswfzrkjk.html

[A16] 真假值判断规则
来源：http://dali.zhoulong.xyz/Article/details/gtldruwdee.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtmimitrlm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.haohaochexian.top/Article/details/gthufbrjug.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yvedp.cn/Article/details/gtqagllhju.html

TS:   if (!x) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqxhzcnli.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ivvv.top/Article/details/gtzsvagoxb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hywenlv.cn/Article/details/gthbdrlrxd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xuanzx.com/Article/details/gthwqylklb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.birdmap.top/Article/details/gtmxlnnwbx.html

[A17] 位运算
来源：http://dali.aizwys.cn/Article/details/gtemmajdgu.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtusgcpazo.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtpzlgtnxu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtstxagbnc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtpxouioay.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtwvkmhupl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtnlicxrso.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtskippfoz.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtwxwfohwl.html

[A18] 字符与 ASCII 码互转
来源：http://dali.meibo888.top/Article/details/gtpraotmia.html

Py:   ord("A"); chr(65)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmntycqv.html

PHP:  ord("A"); chr(65)
来源：http://dali.mhx1999.top/Article/details/gtrnhunnpq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolnmmtev.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cashguo.top/Article/details/gtclkzvpnz.html

Java: (int) 'A'; (char) 65
来源：http://dali.tian-w.cn/Article/details/gtstnbjizx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daxiang520.top/Article/details/gtrasmnqsr.html

Ruby: "A".ord; 65.chr
来源：http://dali.tianlin.xyz/Article/details/gtombuluwg.html

C#:   (int)'A'; (char)65
来源：http://dali.c1oappe.top/Article/details/gtyumocmbm.html

[A19] 交换两个变量
来源：http://dali.guowangkeji.top/Article/details/gtwymijhhe.html

Py:   a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gtwyedldmu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yonumen.top/Article/details/gtpdtssqvj.html

JS:   [a, b] = [b, a];
来源：http://dali.dianchejie.cn/Article/details/gthkappcft.html

TS:   [a, b] = [b, a];
来源：http://dali.ydzc1.top/Article/details/gtuivzcfqd.html

Java: int t = a; a = b; b = t;
来源：http://dali.meibo888.top/Article/details/gtnvzqkwaj.html

Go:   a, b = b, a
来源：http://dali.redwolf501.top/Article/details/gtdqvbzroi.html

Ruby: a, b = b, a
来源：http://dali.meibo888.top/Article/details/gtfudrqzit.html

C#:   (a, b) = (b, a);
来源：http://dali.redwolf501.top/Article/details/gtqhmysnvz.html

[A20] 读取标准输入
来源：http://dali.0kj1m.cn/Article/details/gthmjlphsb.html

Py:   name = input("请输入：")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmygxgmlr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sufxvd.cn/Article/details/gtkkkamrfp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.dashuyun.cn/Article/details/gtmunsyhlw.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgfzy.top/Article/details/gtcwwcghxm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenlongwang.top/Article/details/gtmvqoqado.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.wangdashe.top/Article/details/gtarkehdce.html

Ruby: gets.chomp
来源：http://dali.wangshuangyany.cn/Article/details/gtxydaivfq.html

C#:   Console.ReadLine();
来源：http://dali.jianghu66.top/Article/details/gthgncvnny.html

[A21] 保留指定小数位输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzaovoqt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jianghu66.top/Article/details/gtrspmsusy.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtovlxzriw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtbevxevmc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.snrcjt.cn/Article/details/gtxncjydam.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gturfciskf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtwhilbnte.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gtrsegszdq.html

C#:   3.14159.ToString("F2")
来源：http://dali.hnxiangtu.top/Article/details/gtgftmbmfh.html

[A22] 获取字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtmircnnsw.html

Py:   len(s)
来源：http://dali.birdmap.top/Article/details/gtmfjifgla.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuvkfdpr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.fengsongda.top/Article/details/gtrlgsbasg.html

TS:   s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyjwtmov.html

Java: s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkuixylr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yvedp.cn/Article/details/gtftvptcdv.html

Ruby: s.length
来源：http://dali.nanxuanxn.top/Article/details/gtweyxmihh.html

C#:   s.Length
来源：http://dali.cashguo.top/Article/details/gtmaqhssof.html

[A23] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtzktdfmuo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yvedp.cn/Article/details/gtsggoljbz.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hongshengwenyu.top/Article/details/gtosbzrben.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtcinkkhjp.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenzaomai.com/Article/details/gtcjeswgzn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gtzuajrovi.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteztsmaeb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtvfjihubl.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoterhglm.html

[A24] 去除首尾空白
来源：http://dali.chenzaomai.com/Article/details/gtllukojly.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gtnsnilrjf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.c1oappe.top/Article/details/gtkgmtlxwi.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gtxiynnwxj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shzxlz.cn/Article/details/gtjcdrbjik.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenlongwang.top/Article/details/gtdsfuweov.html

Go:   strings.TrimSpace(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfymufwcj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ehwqpu.com/Article/details/gtmqinrauz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.mhx1999.top/Article/details/gtltvsvzdp.html

[A25] 字符串比较
来源：http://dali.yongpay.top/Article/details/gtvdfqbzhr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.birdmap.top/Article/details/gtxaolqucp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sysykeji.top/Article/details/gtehtsfcri.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sweek.top/Article/details/gtksidylwd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tanke756.top/Article/details/gtlkiajhdk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258888.top/Article/details/gtfnaflhtf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xylfe.cn/Article/details/gttwmdbykn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yangfankeji.com/Article/details/gteipgprmr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj20258888.top/Article/details/gtrxuzwmhf.html

[A26] 类型转换总览
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpumiles.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnyeazdq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvwchmgu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinqigufen.top/Article/details/gtwkydgwyi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.316326.xyz/Article/details/gtxljcjsch.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gtjrbirmiy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yvedp.cn/Article/details/gtfggofpxu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.fengsongda.top/Article/details/gtaxvdcqlr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xuanzx.com/Article/details/gtvckhrmaj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtldsdxjry.html

B. 流程控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtasaiqqjr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtflksopiw.html

[B01] 条件判断 if / else
来源：http://dali.yj20258888.top/Article/details/gtlwptzchh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpitztpc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cqqwz.cn/Article/details/gtdxtmmlth.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gthqikbttz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtuqhikozx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gtftlaokqs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nwbrower.top/Article/details/gtnivwgnmi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.kuanghao11.cn/Article/details/gtkhhnuoka.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gtptkrmemg.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigufen.top/Article/details/gtfnzdbypy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhiwuduotai.top/Article/details/gtltorvwcr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdinrysb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtncqqrdjo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifqoiajm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtsfpfetor.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.mhx1999.top/Article/details/gtqjhuvqez.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gthrvxiwqv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaaqmwetc.html

[B03] switch / match / case
来源：http://dali.guowangkeji.top/Article/details/gtsumrlpok.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gtrkethykw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkktuevds.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtooopayjy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtwzklhnoh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gtvuremwyy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yangfankeji.com/Article/details/gthtqgyqwi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhongyouzk.top/Article/details/gtcwkuzixz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gtrqtglsnl.html

[B04] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtcnuvubnu.html

Py:   for i in range(10): print(i)
来源：http://dali.hnxiangtu.top/Article/details/gtxgcjdfgw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.snrcjt.cn/Article/details/gtoputszqz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gttricgwzs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gtrjczxkix.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gteljzjpvc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xylfe.cn/Article/details/gtlmntyaoj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpmyzkuk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xziqi.cn/Article/details/gthpsvscfm.html

[B05] 遍历数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gttmbuicqw.html

Py:   for item in arr: print(item)
来源：http://dali.dashuyun.cn/Article/details/gtgirfzbgg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gtpurmbcrg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gtukperiut.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydoqoxig.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gtthfmrxsr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.iojbl.cn/Article/details/gtxnprdapl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gtujhlhhry.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtkcipudgo.html

[B06] 遍历字典 / 对象
来源：http://dali.iojbl.cn/Article/details/gtrzxteojn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shangyingyoupin.top/Article/details/gtebekcdpk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jiagoushi.top/Article/details/gtxwpikwxo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtaogiebcw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.svipenyu.cn/Article/details/gtmdqbfyrq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cdnleiting.top/Article/details/gtkdynwcal.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sxryk.cn/Article/details/gtxzvwimgl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenzaomai.com/Article/details/gtixvsvhbz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.dianchejie.cn/Article/details/gtwfndyltq.html

[B07] while 循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqyvysly.html

Py:   while i < 10: i += 1
来源：http://dali.jqgfzy.top/Article/details/gtgtadjiwi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangdashe.top/Article/details/gtnpjwkwdx.html

JS:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtbyvdjrhi.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtiouzrdcl.html

Java: while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtvsukkdib.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yvedp.cn/Article/details/gtltxipmok.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jyoumei.cn/Article/details/gtjzrzyaco.html

C#:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtncikahue.html

[B08] do-while（至少执行一次）
来源：http://dali.zdqjudy.top/Article/details/gtkxtpsooy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shuidangran.top/Article/details/gterovduap.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtsjpicxpo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtzbgrikmu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtpweduocw.html

Java: do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtlakevfnp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gtqmnsxlvc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangdashe.top/Article/details/gtlblztqlf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtjpfhdsdt.html


<!-- 参考信息 -->