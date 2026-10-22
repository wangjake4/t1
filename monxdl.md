代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ehwqpu.com/Article/details/gtzppruefu.html

JS:   `Hello, ${name}!`
来源：http://dali.sxryk.cn/Article/details/gthafgtlsk.html

TS:   `Hello, ${name}!`
来源：http://dali.smart0.xyz/Article/details/gtbtpqnjew.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yueranfly.top/Article/details/gtlggwciqz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.snrcjt.cn/Article/details/gtjrurbxcp.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhengqikj.top/Article/details/gtdvknvqgl.html

C#:   $"Hello, {name}!"
来源：http://dali.nwbrower.top/Article/details/gtqapednvd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.guannengcc.top/Article/details/gtmlsmoyvf.html

Py:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtayenvghr.html

PHP:  "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtqetltxpq.html

JS:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtzkbpuxxq.html

TS:   "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtycvabnbd.html

Java: "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtzgacotgo.html

Go:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtqdjdmwer.html

Ruby: "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzskbupl.html

C#:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtzkxahloz.html

[A14] 注释写法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvaxwvrwd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hysaishi.cn/Article/details/gtlaldnewo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gtewrufgqm.html

JS:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtpkcxkeax.html

TS:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gthashiybs.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhiwuduotai.top/Article/details/gtlslrqppd.html

Go:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiobufud.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.chenlongwang.top/Article/details/gtakjefdgn.html

C#:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtdoebagoh.html

[A15] 空值判断与默认值
来源：http://dali.yj20258.top/Article/details/gtglwzzcvp.html

Py:   value = data or "默认值"
来源：http://dali.zycfv.cn/Article/details/gtoqtfvzgn.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gtmudrkhbx.html

JS:   const value = data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gtikngyrge.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gtuenwsiil.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258.top/Article/details/gtmzzswwxk.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhongyouzk.top/Article/details/gttmvilmfy.html

Ruby: value = data || "默认值"
来源：http://dali.iojbl.cn/Article/details/gtbcggiddk.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenlongwang.top/Article/details/gtsliulnvi.html

[A16] 真假值判断规则
来源：http://dali.zhengqikj.top/Article/details/gtowsitwvt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cqqwz.cn/Article/details/gtldiqybjy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yuanzhike.top/Article/details/gtdefaboqf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.pengpengdd.cyou/Article/details/gtmyllytsb.html

TS:   if (!x) {}
来源：http://dali.hammf.cn/Article/details/gtlrvqjyze.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.svipenyu.cn/Article/details/gtbjwwwicp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiyfnmsv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ehwqpu.com/Article/details/gtaymktxtw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sysykeji.top/Article/details/gthrjlaqig.html

[A17] 位运算
来源：http://dali.daxiang520.top/Article/details/gtvmjgopgr.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtznnypjnr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jianghu66.top/Article/details/gtyewkhmnv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtxqrxxker.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtgtzukbue.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gthollygaz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtxoufxnya.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtqzsmuyle.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtmkupmkjz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yonumen.top/Article/details/gtwwdilmsd.html

Py:   ord("A"); chr(65)
来源：http://dali.tanke756.top/Article/details/gtttohahlx.html

PHP:  ord("A"); chr(65)
来源：http://dali.yanxiufei.cn/Article/details/gtflfyfkdg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shzxlz.cn/Article/details/gtlnwkflqz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shangyingyoupin.top/Article/details/gtfsmbzoaz.html

Java: (int) 'A'; (char) 65
来源：http://dali.cucudq.cn/Article/details/gtdkhtpuwm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhengqikj.top/Article/details/gtiwkdfxwr.html

Ruby: "A".ord; 65.chr
来源：http://dali.jqgfzy.top/Article/details/gtketecrrd.html

C#:   (int)'A'; (char)65
来源：http://dali.redwolf501.top/Article/details/gtqoixdbhx.html

[A19] 交换两个变量
来源：http://dali.dianchejie.cn/Article/details/gtalvzfbxf.html

Py:   a, b = b, a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmcqdbps.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hnqzz.top/Article/details/gtxtpqwpgc.html

JS:   [a, b] = [b, a];
来源：http://dali.sxryk.cn/Article/details/gtaxlwczln.html

TS:   [a, b] = [b, a];
来源：http://dali.jinqigufen.top/Article/details/gtsnafginx.html

Java: int t = a; a = b; b = t;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtclbbtr.html

Go:   a, b = b, a
来源：http://dali.9152youxi.cn/Article/details/gtjgiaxzmy.html

Ruby: a, b = b, a
来源：http://dali.svipenyu.cn/Article/details/gtzraczbsh.html

C#:   (a, b) = (b, a);
来源：http://dali.bjfxy.top/Article/details/gtgugdmown.html

[A20] 读取标准输入
来源：http://dali.cucudq.cn/Article/details/gtchjwoyfp.html

Py:   name = input("请输入：")
来源：http://dali.yanxiufei.cn/Article/details/gteejjfouk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gogol.net.cn/Article/details/gtghezfhza.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jianghu66.top/Article/details/gtibxbpwsl.html

TS:   // Node.js：readline 模块
来源：http://dali.daria6918.cn/Article/details/gtjfzajxzk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteywlhkkc.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cashguo.top/Article/details/gtowakhvxr.html

Ruby: gets.chomp
来源：http://dali.cashguo.top/Article/details/gtzcrbqbba.html

C#:   Console.ReadLine();
来源：http://dali.hammf.cn/Article/details/gtemluqnzc.html

[A21] 保留指定小数位输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpvrmosw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ivvv.top/Article/details/gtzmzcufup.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtpbuymvgt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gtjoqwyynu.html

TS:   (3.14159).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtopuwtsap.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gthpoujqho.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gtrtwayheo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtkxktordv.html

C#:   3.14159.ToString("F2")
来源：http://dali.yonumen.top/Article/details/gtnxcbqnfy.html

[A22] 获取字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtuezseese.html

Py:   len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtycvqkdrp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ivvv.top/Article/details/gtfnocvpgc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gogol.net.cn/Article/details/gtzcpsjwre.html

TS:   s.length
来源：http://dali.hfpthk.cn/Article/details/gtxhcqzxkd.html

Java: s.length()
来源：http://dali.pycfn.com/Article/details/gtavwykenw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cqqwz.cn/Article/details/gtaahifxgt.html

Ruby: s.length
来源：http://dali.jlsjyb.cn/Article/details/gtsuprbjyd.html

C#:   s.Length
来源：http://dali.ydzc1.top/Article/details/gtbseubprt.html

[A23] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtpbkoefkb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.316326.xyz/Article/details/gtusuksvak.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.dashuyun.cn/Article/details/gtnfehfrat.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gtpawmqrcu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gtnurwkvmg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yongpay.top/Article/details/gtuqidfodh.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yvedp.cn/Article/details/gtshcdhrsh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.havefunace.top/Article/details/gtjqmuvjvm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jqgfzy.top/Article/details/gtcrkfkhrm.html

[A24] 去除首尾空白
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlppelnk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yongpay.top/Article/details/gtuvaueerr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yuanzhike.top/Article/details/gtefqvzctb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tianlin.xyz/Article/details/gtcbgecmgf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtmlucgqzm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhoulong.xyz/Article/details/gtturxcjds.html

Go:   strings.TrimSpace(s)
来源：http://dali.ydzc1.top/Article/details/gtopoetafw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ivvv.top/Article/details/gtiwzskmdw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gaohongyu789.top/Article/details/gtfeatckyx.html

[A25] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gteuvdbrch.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jyoumei.cn/Article/details/gtuwxrzyto.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.9152youxi.cn/Article/details/gteclladuh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.iojbl.cn/Article/details/gtogiirhrl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gtlkuwdzhm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.redwolf501.top/Article/details/gtsxltncrb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.pengpengdd.cyou/Article/details/gtjyfbxxes.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jyoumei.cn/Article/details/gtzhddcrdp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gaohongyu789.top/Article/details/gtnwxvyqlq.html

[A26] 类型转换总览
来源：http://dali.pengpengdd.cyou/Article/details/gtblcgoegd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jianghu66.top/Article/details/gtcmignwus.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.quarkkingdee.top/Article/details/gtkeicgwgm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvubldjsk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.aizwys.cn/Article/details/gtsrnpbbki.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtbhmgwhww.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shangyingyoupin.top/Article/details/gtgpnwftjk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtiqajzwgq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.guannengcc.top/Article/details/gtkhnjfzzd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfikpdulu.html

B. 流程控制
来源：http://dali.hysaishi.cn/Article/details/gttwwuwwpd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtwteavufx.html

[B01] 条件判断 if / else
来源：http://dali.nanxinkj.top/Article/details/gtdrhymojj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gtyzjragoq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsgkgqmy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtvpioijkh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtjajucnun.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtqcxxuqpg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cheryme.top/Article/details/gtshpbvhgi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nwbrower.top/Article/details/gtcruozmse.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtetegkefa.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gtcumuoloq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jlsjyb.cn/Article/details/gtgbgmgzeb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.meibo888.top/Article/details/gtzvcqjpji.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtxgxqbour.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtnasgywco.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtjmhngcga.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.haohaochexian.top/Article/details/gtiyweuamd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258888.top/Article/details/gttmgfdiel.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtzvnkmhty.html

[B03] switch / match / case
来源：http://dali.sweek.top/Article/details/gtkhjokipy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gtewmescqo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniqsheno.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtbiurlzbz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtykwgmwxa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtkygejkbw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtinlayzzv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xziqi.cn/Article/details/gtqixeilpi.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yuxming.cn/Article/details/gtuvdmcxxs.html

[B04] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtkzglrkzb.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxinkj.top/Article/details/gtsobxpahs.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenlongwang.top/Article/details/gtertwisza.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtydxgliaj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hfpthk.cn/Article/details/gtoykjspuo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtthxppahh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jianghu66.top/Article/details/gtezskzgno.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenzaomai.com/Article/details/gtkzdyagfo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.redwolf501.top/Article/details/gtltjizige.html

[B05] 遍历数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtjrxqjkbj.html

Py:   for item in arr: print(item)
来源：http://dali.sufxvd.cn/Article/details/gtjsmhxohc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cqqwz.cn/Article/details/gtoyuaqmyz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtqsmqqhyo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtxpbvtawc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtsmohjofw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuanzx.com/Article/details/gtpiuegltk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnqzz.top/Article/details/gtokeqanpo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gtxpkdcdlw.html

[B06] 遍历字典 / 对象
来源：http://dali.cucudq.cn/Article/details/gtucvvyhev.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cheryme.top/Article/details/gtsiiabuwq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jianghu66.top/Article/details/gtldjfyans.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gtkublbysx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gtakoimchx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cucudq.cn/Article/details/gtosouixwp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.quarkkingdee.top/Article/details/gtwnlnqfuy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.snrcjt.cn/Article/details/gtatvuukyg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgufenzy.top/Article/details/gtxqcjgpfl.html

[B07] while 循环
来源：http://dali.hysaishi.cn/Article/details/gtzckccowb.html

Py:   while i < 10: i += 1
来源：http://dali.yj202588.top/Article/details/gtbdklaapp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.mhx1999.top/Article/details/gtwatkllir.html

JS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtsjwewtrm.html

TS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljtudqpr.html

Java: while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtalhrvwba.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fengsongda.top/Article/details/gttbvtlnru.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shangyingyoupin.top/Article/details/gtuktypvrg.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtlepgvadj.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gtukujuwbo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yangfankeji.com/Article/details/gtwzgsrnyl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtyioimgds.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gttjfqtdhz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gteninpasy.html

Java: do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtqjmoqxrr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.guannengcc.top/Article/details/gtulhvrffa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.quarkkingdee.top/Article/details/gtgxgvahgm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtmtxvrrox.html

[B09] break 与 continue
来源：http://dali.svipenyu.cn/Article/details/gtgaeelens.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gtquvhfmfr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtromxithd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtxalozrbz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtewuuutpk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtfghekbfx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtqpakjptd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aibaodan.cn/Article/details/gtbkhxbsqm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtdvncxzhw.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gtejckrufn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.c1oappe.top/Article/details/gtcthygznm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jlsjyb.cn/Article/details/gtmcvdyzqg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtthbijika.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtbtynllnd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zdqjudy.top/Article/details/gtlnevywoe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenzaomai.com/Article/details/gtunkfvgtc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigufen.top/Article/details/gtfhxcjpdb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gtwgedgpve.html

[B11] 生成数字序列 / 区间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipzyzaki.html

Py:   list(range(0, 10, 2))
来源：http://dali.vqdsnc.cn/Article/details/gtpkemrrsy.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtinwiiyhi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtoaypnyrg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gtrgkjswje.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtqpwbxgmp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xinyue.icu/Article/details/gtvyxbxyhh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gtfosutbpj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbukluryz.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gttazdbgva.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jyoumei.cn/Article/details/gtutijjqqb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigfzy.top/Article/details/gtzwpbvkzz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtflqubukz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtcsnenzkw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtymlrklwq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gthhjmdpah.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhoulong.xyz/Article/details/gtpajhbwrf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gtrjnxgvdw.html

[B13] 判断是否为数字
来源：http://dali.xziqi.cn/Article/details/gtpodopxad.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258.top/Article/details/gtwdzllfsl.html

PHP:  is_numeric($x)
来源：http://dali.haohaochexian.top/Article/details/gttvmtcput.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtpilaejxo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdxexglr.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gtazvxitip.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj202588.top/Article/details/gtdlbevsxp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gtbkytidya.html

C#:   x is int or double or decimal
来源：http://dali.snrcjt.cn/Article/details/gtqvxbielj.html

[B14] 判断值是否在集合内
来源：http://dali.redwolf501.top/Article/details/gtnkaiypew.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gtwnnkebnm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.snrcjt.cn/Article/details/gtbazrhthn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtrwabhqyb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtvcjdyulb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhixingplan.top/Article/details/gthshjohpq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xylfe.cn/Article/details/gtngmjxcde.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gteghgxych.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtbqlinzmi.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gtvvoiqbvw.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gthkguxmhq.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gtmazdvzbz.html

JS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtkpgykrqt.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtbkrutsmv.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtrrdcaoii.html

Go:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtjeplkxcl.html

Ruby: a && b || !c
来源：http://dali.yongpay.top/Article/details/gtvkniejet.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtbbhletls.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtvmygklnr.html

Py:   if not data: return
来源：http://dali.wangshuangyany.cn/Article/details/gtstahyqqb.html

PHP:  if (!$data) { return; }
来源：http://dali.yj202588.top/Article/details/gtmlogmahe.html

JS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gttsyftqhw.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gteslndiea.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtjutuocsz.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gtyzccumvq.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gthhcmbxaw.html

C#:   if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwbyvpit.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtyzrpbwbw.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gtlwzusojt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthzsbxfhi.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtwrqlfhrt.html

Py:   def add(a, b): return a + b
来源：http://dali.sxryk.cn/Article/details/gtcylfueoh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtrbvutnvr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtxfvgfszc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtposjkxdl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtsevvbvyr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gtjtgkbtxz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbpcdlcd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmnthdrz.html

[C02] 默认参数
来源：http://dali.cdnleiting.top/Article/details/gtbtxwvonm.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtjteykdyc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gtmrvoxxdv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtikrpplli.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtgecgusjr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pengpengdd.cyou/Article/details/gtldpfccrd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ppjwa.cn/Article/details/gtjqobdinq.html

Ruby: def greet(name = "World") = name
来源：http://dali.guannengcc.top/Article/details/gtdbvxofud.html


<!-- 参考信息 -->