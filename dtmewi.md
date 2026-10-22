代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.nwbrower.top/Article/details/gtpvvjccpr.html

JS:   `Hello, ${name}!`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycbatyoq.html

TS:   `Hello, ${name}!`
来源：http://dali.ybcxt.top/Article/details/gtpdubudcf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yongpay.top/Article/details/gtfazdmzub.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hysaishi.cn/Article/details/gtzzhinelz.html

Ruby: "Hello, #{name}!"
来源：http://dali.gzhubu.top/Article/details/gtqtyqgubb.html

C#:   $"Hello, {name}!"
来源：http://dali.svipenyu.cn/Article/details/gtmsmycpje.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yuxming.cn/Article/details/gtnorvohry.html

Py:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtqkngiasi.html

PHP:  "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtehagzsfe.html

JS:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtdcdfxgif.html

TS:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtepyndmsz.html

Java: "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtfjdixtqz.html

Go:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtkrjpphuq.html

Ruby: "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtinkxjdlk.html

C#:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtjqssbthz.html

[A14] 注释写法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkirmuglw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhongyouzk.top/Article/details/gtzcrjwvnz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gtthigwqly.html

JS:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtjeozvgwx.html

TS:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtgbjzytkn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jiagoushi.top/Article/details/gtgqcafbfc.html

Go:   // 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gtddenyben.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yongpay.top/Article/details/gtbwblljzo.html

C#:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gtluvgknvx.html

[A15] 空值判断与默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntfwgwty.html

Py:   value = data or "默认值"
来源：http://dali.jqgufenzy.top/Article/details/gtzmpjenhe.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gteflvicid.html

JS:   const value = data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gtyxciqhhn.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyjkhblj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinqigfzy.top/Article/details/gtpcprrqqs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shuidangran.top/Article/details/gtwvskazzj.html

Ruby: value = data || "默认值"
来源：http://dali.zycfv.cn/Article/details/gtuiffgfwh.html

C#:   var value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtdmzqtykc.html

[A16] 真假值判断规则
来源：http://dali.daxiang520.top/Article/details/gtetcimzoe.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.chenzaomai.com/Article/details/gtftsokxlk.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pengpengdd.cyou/Article/details/gtpzhxpjjs.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.fengsongda.top/Article/details/gtefrghhvg.html

TS:   if (!x) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtazkvhumb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.sxryk.cn/Article/details/gtudhqexap.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tianlin.xyz/Article/details/gtapkmmjrz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gogol.net.cn/Article/details/gtmvrimxez.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.bjfxy.top/Article/details/gtuwdkjtgk.html

[A17] 位运算
来源：http://dali.yvedp.cn/Article/details/gtpdmjhwhx.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtwrznxqrn.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xuanzx.com/Article/details/gtctnhvqxy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtkxtgwifb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtibwlxrxb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtysnfdwcl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtuqlijzsh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtxomoaklv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtgvqzwyfp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopyvdymw.html

Py:   ord("A"); chr(65)
来源：http://dali.0kj1m.cn/Article/details/gttjsckkti.html

PHP:  ord("A"); chr(65)
来源：http://dali.shuidangran.top/Article/details/gtjzfqnwbd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.meibo888.top/Article/details/gtzmadvwrc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258.top/Article/details/gtovwhhrll.html

Java: (int) 'A'; (char) 65
来源：http://dali.aibaodan.cn/Article/details/gtyvhpncai.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hnqzz.top/Article/details/gtptajpuws.html

Ruby: "A".ord; 65.chr
来源：http://dali.fzhhl.top/Article/details/gtrtrqmorw.html

C#:   (int)'A'; (char)65
来源：http://dali.jyoumei.cn/Article/details/gtbbxcbuik.html

[A19] 交换两个变量
来源：http://dali.kuanghao11.cn/Article/details/gtnckksald.html

Py:   a, b = b, a
来源：http://dali.birdmap.top/Article/details/gtdetaoxyt.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hysaishi.cn/Article/details/gtuwlyxxdk.html

JS:   [a, b] = [b, a];
来源：http://dali.andypj.xyz/Article/details/gtoddlpgfa.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgfzy.top/Article/details/gtsrgrjdpg.html

Java: int t = a; a = b; b = t;
来源：http://dali.cqqwz.cn/Article/details/gttcxslueb.html

Go:   a, b = b, a
来源：http://dali.smart0.xyz/Article/details/gtltuuerot.html

Ruby: a, b = b, a
来源：http://dali.yongpay.top/Article/details/gtsigzcqzi.html

C#:   (a, b) = (b, a);
来源：http://dali.aibaodan.cn/Article/details/gtosjwpfmm.html

[A20] 读取标准输入
来源：http://dali.ivvv.top/Article/details/gtqskvfygp.html

Py:   name = input("请输入：")
来源：http://dali.0kj1m.cn/Article/details/gthcqgjaig.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.kuanghao11.cn/Article/details/gtvwfapnnp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yuxming.cn/Article/details/gtevqyfxnm.html

TS:   // Node.js：readline 模块
来源：http://dali.dashuyun.cn/Article/details/gtsoyqzbht.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhijiandao.cn/Article/details/gtqajorkgm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlhmicca.html

Ruby: gets.chomp
来源：http://dali.xylfe.cn/Article/details/gtmsxwiszb.html

C#:   Console.ReadLine();
来源：http://dali.jlsjyb.cn/Article/details/gtwxprznkz.html

[A21] 保留指定小数位输出
来源：http://dali.feifeiyinyue.top/Article/details/gtjburfuls.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hongshengwenyu.top/Article/details/gtyprjwidh.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gtgzqqrfgo.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtdubwysuj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtwdccukxr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtpxejtbju.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtsyppxnhp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gtkxtbmcgu.html

C#:   3.14159.ToString("F2")
来源：http://dali.yuxming.cn/Article/details/gtnnnolaok.html

[A22] 获取字符串长度
来源：http://dali.hnqzz.top/Article/details/gtwmqrumwo.html

Py:   len(s)
来源：http://dali.xylfe.cn/Article/details/gtwrbrkabl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.0kj1m.cn/Article/details/gtfailwhbr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.aizwys.cn/Article/details/gtlqadkyjf.html

TS:   s.length
来源：http://dali.aizwys.cn/Article/details/gtmlqeyccq.html

Java: s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtcluwkjon.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtbljyfolj.html

Ruby: s.length
来源：http://dali.yuanzhike.top/Article/details/gtrbondaxn.html

C#:   s.Length
来源：http://dali.shzxlz.cn/Article/details/gtpaifwxhv.html

[A23] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtxwbdjdsl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sysykeji.top/Article/details/gthhvddcnq.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.0kj1m.cn/Article/details/gtvzdjqkgl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gtbuodpudm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtouqdyrri.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gtfgaeiptt.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.vqdsnc.cn/Article/details/gtldsqjhzu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.daria6918.cn/Article/details/gtuwpbzeqx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangdashe.top/Article/details/gtlfwyojnj.html

[A24] 去除首尾空白
来源：http://dali.ehwqpu.com/Article/details/gtymqpvpyd.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cucudq.cn/Article/details/gtkjizalvu.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jlsjyb.cn/Article/details/gtqjsvajok.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.bjfxy.top/Article/details/gticzavncs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtivqvordc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gotoacloud.top/Article/details/gtlfylvgdq.html

Go:   strings.TrimSpace(s)
来源：http://dali.smart0.xyz/Article/details/gtqxfcovbw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xuanzx.com/Article/details/gtcnhvtzmr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.aizwys.cn/Article/details/gtrhoxogrd.html

[A25] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtdwkytunj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nanxuanxn.top/Article/details/gtqgbpwlkn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ybcxt.top/Article/details/gtqizlqmoi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtviyuqogh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxiqnzjh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhoulong.xyz/Article/details/gtqotsrnak.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gtprrdlmia.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.havefunace.top/Article/details/gtsotggydq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gtguelxwyz.html

[A26] 类型转换总览
来源：http://dali.zdqjudy.top/Article/details/gthmwrvzwx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenjidiqi.icu/Article/details/gtbwzwvhuy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yuxming.cn/Article/details/gtnvpqnkav.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aizwys.cn/Article/details/gtoscyiiro.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhongyouzk.top/Article/details/gtbofshamm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.quarkkingdee.top/Article/details/gtbyiqbkfh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xinyue.icu/Article/details/gtcercgtql.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ppjwa.cn/Article/details/gtdhkswtoq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gtatiewcvy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtejqtcqrh.html

B. 流程控制
来源：http://dali.guowangkeji.top/Article/details/gttvpjhepi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtktiucsjq.html

[B01] 条件判断 if / else
来源：http://dali.cheryme.top/Article/details/gtwqaejjrt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.daxiang520.top/Article/details/gtdsdmduxu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hammf.cn/Article/details/gtrbgopoyx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtenrkznlh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtymuenekt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtqwrdtbbz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.316326.xyz/Article/details/gtngbklpdx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shuidangran.top/Article/details/gtzobemvso.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtwwmharpx.html

[B02] 多分支 else if / elif
来源：http://dali.ybcxt.top/Article/details/gtzwjrndsg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sweek.top/Article/details/gtlfgqyuyy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yonumen.top/Article/details/gthuckbwze.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtjnvlzctq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtexmyqpup.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gtjvxocpga.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xylfe.cn/Article/details/gtyraaqxpv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daxiang520.top/Article/details/gtvxuxdhbd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gthdwbinlv.html

[B03] switch / match / case
来源：http://dali.pengpengdd.cyou/Article/details/gtnrwmlkqp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guannengcc.top/Article/details/gtliyymypt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsqslzeva.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtljijdcmk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gtibwyjvaj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gterqxqnud.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tian-w.cn/Article/details/gteleisvax.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfqtgsls.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gtfisjxtwm.html

[B04] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtxafekngc.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxuanxn.top/Article/details/gtumplpulo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258888.top/Article/details/gtrvnoyrtr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtruhvssgp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258.top/Article/details/gtuhukhmid.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gttwmrurns.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulzoznka.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guowangkeji.top/Article/details/gthlxltwxv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtmszvnn.html

[B05] 遍历数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtktjndhxr.html

Py:   for item in arr: print(item)
来源：http://dali.ppjwa.cn/Article/details/gtoakalojm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jlsjyb.cn/Article/details/gtgctozswt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtxwqcyivc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gtyebwvvbj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aizwys.cn/Article/details/gtaheglpps.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aibaodan.cn/Article/details/gtnntvpepm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.daria6918.cn/Article/details/gtrcfdynoq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gzhubu.top/Article/details/gtssjqwqza.html

[B06] 遍历字典 / 对象
来源：http://dali.ybcxt.top/Article/details/gtjoqnlida.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yonumen.top/Article/details/gtannhofyn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tian-w.cn/Article/details/gtervlfwhx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gtzcclaqck.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuvdsslj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hysaishi.cn/Article/details/gtnblpxwdh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sweek.top/Article/details/gtzywwzisu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.9152youxi.cn/Article/details/gtamrtzsnt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zycfv.cn/Article/details/gtayhiejse.html

[B07] while 循环
来源：http://dali.ydzc1.top/Article/details/gtlediimup.html

Py:   while i < 10: i += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtxdmrpuan.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangdashe.top/Article/details/gtaxqpjyxd.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtrneefuse.html

TS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtjrcmdfgg.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtnvpoqtls.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jianghu66.top/Article/details/gtobhntzec.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxinkj.top/Article/details/gtwlujsoix.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnuworrpq.html

[B08] do-while（至少执行一次）
来源：http://dali.jyoumei.cn/Article/details/gthxxmgsus.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gtfmnwmihq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.aizwys.cn/Article/details/gtjuwaegzk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtjuacikve.html

TS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtrshrcoct.html

Java: do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtnyqpdwdg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtaswkegou.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sysykeji.top/Article/details/gthvpeavhi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gttrxzobkd.html

[B09] break 与 continue
来源：http://dali.jqgfzy.top/Article/details/gtxpimadbn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.svipenyu.cn/Article/details/gtzifafxqt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtmirgjlzz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtuxpazyxw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtrjhazset.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtzvylasip.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jiagoushi.top/Article/details/gtjzcidapx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gotoacloud.top/Article/details/gtcgqfleiy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gttezleqjt.html

[B10] 遍历同时拿索引
来源：http://dali.nanxinkj.top/Article/details/gtqoutlmds.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daria6918.cn/Article/details/gthkxgvtrv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gtgiapgkoj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yangfankeji.com/Article/details/gtmrrddepj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrjrxqrh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.redwolf501.top/Article/details/gttojodtjr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigufen.top/Article/details/gtjzjqftkc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fzhhl.top/Article/details/gtbpslwtge.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtzzhimwla.html

[B11] 生成数字序列 / 区间
来源：http://dali.gotoacloud.top/Article/details/gtxzsnospn.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gtvewqhhdi.html

PHP:  range(0, 10, 2);
来源：http://dali.birdmap.top/Article/details/gtmaidzrbl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gthhpkyneu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gthnsesbwo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtnrwkkysj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gtgmiyicbz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxuanxn.top/Article/details/gtoabldwjc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhfeixxv.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gtmgdxfqej.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtystpimbl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuanzhike.top/Article/details/gttkyipwxr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gtxmrjyuqx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtmjkxnlzf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtxuotjohp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fengsongda.top/Article/details/gtgfrhxsli.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jianghu66.top/Article/details/gtoxhhgcun.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.0kj1m.cn/Article/details/gtvbrhogdx.html

[B13] 判断是否为数字
来源：http://dali.daria6918.cn/Article/details/gtxkojpepm.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtykytcowj.html

PHP:  is_numeric($x)
来源：http://dali.yangfankeji.com/Article/details/gttnvzhtod.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtxsywrcbn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegewslba.html

Java: x instanceof Number
来源：http://dali.sweek.top/Article/details/gtrqapgmbf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhiwuduotai.top/Article/details/gtzdjiqlkt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gtporkvzaq.html

C#:   x is int or double or decimal
来源：http://dali.shangyingyoupin.top/Article/details/gtynjcrhkz.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gtfopawkfz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fengsongda.top/Article/details/gtjsasvowu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhoulong.xyz/Article/details/gtcsbndqaj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtbhbvtskx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtcclixqvf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gtguzukdmo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxinkj.top/Article/details/gtpjxckjiv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtixvkpend.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gteedqzgqz.html

[B15] 布尔运算与取反
来源：http://dali.hysaishi.cn/Article/details/gtgdqfpbvk.html

Py:   a and b or not c
来源：http://dali.gaohongyu789.top/Article/details/gttewkzrwf.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gtivfchwgg.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtpuzirsco.html

TS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtsrmexles.html

Java: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtqnwkzftq.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtyhlcnisn.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtlhbcxsdz.html

C#:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtzkfkscbj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gtzdpgyukd.html

Py:   if not data: return
来源：http://dali.fengsongda.top/Article/details/gtscpnmgqi.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gtabnnjdtb.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtwhukkeqx.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtdxrjngrl.html

Java: if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtpvpwhllo.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gtazbrysjt.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfsdxpop.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtgylewbpg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxjdcqkum.html

C. 函数与作用域
来源：http://dali.jiagoushi.top/Article/details/gtgttvsppd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtutkzrgxy.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtsvlokrsb.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gtbebgoujn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtkscvdnpz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtxvrknszk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtsdbxzuco.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdibkehds.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gtyvylkxwq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gtlaxoplyt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gttzhvuuzh.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtytzikylq.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gttyyqzils.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.snrcjt.cn/Article/details/gtsyigfiem.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gthwyfcqmg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtownrgrnn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aizwys.cn/Article/details/gtcfengfqi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.kuanghao11.cn/Article/details/gtbrwuovjy.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gtyokvyyjm.html


<!-- 参考信息 -->