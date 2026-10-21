代发 wailian999

[A14] 注释写法
来源：http://dali.jqgufenzy.top/Article/details/gtfpxgjkko.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhixingplan.top/Article/details/gtzpmgtlwt.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gttoksepuu.html

JS:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtgukmuzis.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtgmzzzbii.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ivvv.top/Article/details/gtrritlhhf.html

Go:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gtxijwhueo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ivvv.top/Article/details/gtomenbnrd.html

C#:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtphkdouqm.html

[A15] 空值判断与默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmthrxvvd.html

Py:   value = data or "默认值"
来源：http://dali.havefunace.top/Article/details/gtdagugvdq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gtqsvyhkob.html

JS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gthubagdjr.html

TS:   const value = data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gtfbegffbr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.svipenyu.cn/Article/details/gtkiopxeoa.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tian-w.cn/Article/details/gtiqhqbvos.html

Ruby: value = data || "默认值"
来源：http://dali.zdqjudy.top/Article/details/gtbwkensgh.html

C#:   var value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gthrkqebmg.html

[A16] 真假值判断规则
来源：http://dali.aizwys.cn/Article/details/gtvcszhrff.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.meibo888.top/Article/details/gtvdwaadya.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gogol.net.cn/Article/details/gtmuenistk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xziqi.cn/Article/details/gtdncqxbmk.html

TS:   if (!x) {}
来源：http://dali.xuanzx.com/Article/details/gtkzwblzwm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.fzhhl.top/Article/details/gtaqvajavv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hysaishi.cn/Article/details/gtxzmqdtpr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhoulong.xyz/Article/details/gtcrmtmttm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtlzhnfqez.html

[A17] 位运算
来源：http://dali.xuanzx.com/Article/details/gthaqczlaj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gttechppzm.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtdtkywiml.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtxkydrdjb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtwtyneivi.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtpqexmnjo.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtcntiwkot.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtgvnqltsg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtnlunslxt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jinqigfzy.top/Article/details/gthgzzbcgv.html

Py:   ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gtrwhqynmr.html

PHP:  ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gtougcsjrh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jyoumei.cn/Article/details/gtpqbmxgzh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigfzy.top/Article/details/gtjiatfyvq.html

Java: (int) 'A'; (char) 65
来源：http://dali.birdmap.top/Article/details/gtkkspcqxi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinqigfzy.top/Article/details/gtsvplzzjc.html

Ruby: "A".ord; 65.chr
来源：http://dali.chenzaomai.com/Article/details/gtjvdzcyzn.html

C#:   (int)'A'; (char)65
来源：http://dali.316326.xyz/Article/details/gtjluavohb.html

[A19] 交换两个变量
来源：http://dali.sysykeji.top/Article/details/gtseppasji.html

Py:   a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gturrnutrz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nwbrower.top/Article/details/gttidvehwt.html

JS:   [a, b] = [b, a];
来源：http://dali.pycfn.com/Article/details/gtwfnudmgi.html

TS:   [a, b] = [b, a];
来源：http://dali.zdqjudy.top/Article/details/gtnncyasnq.html

Java: int t = a; a = b; b = t;
来源：http://dali.gzhubu.top/Article/details/gtsxavrybc.html

Go:   a, b = b, a
来源：http://dali.zhengqikj.top/Article/details/gtjuiflgns.html

Ruby: a, b = b, a
来源：http://dali.9152youxi.cn/Article/details/gtoylzobhf.html

C#:   (a, b) = (b, a);
来源：http://dali.cucudq.cn/Article/details/gtltuscwtn.html

[A20] 读取标准输入
来源：http://dali.tianlin.xyz/Article/details/gtlnqnblid.html

Py:   name = input("请输入：")
来源：http://dali.havefunace.top/Article/details/gtkkakbyyo.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gtpdwarbpq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yuxming.cn/Article/details/gtcsfxkaha.html

TS:   // Node.js：readline 模块
来源：http://dali.birdmap.top/Article/details/gtaxshhayb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cheryme.top/Article/details/gturvgfppm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gzhubu.top/Article/details/gttqsqjxrf.html

Ruby: gets.chomp
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxpecbfg.html

C#:   Console.ReadLine();
来源：http://dali.tanke756.top/Article/details/gthwnlabii.html

[A21] 保留指定小数位输出
来源：http://dali.yueranfly.top/Article/details/gtnjmzqduy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.guowangkeji.top/Article/details/gtqxnmvzhh.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtxhwuvdtg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtipnkuxac.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtbkgkijct.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gtfrvcjvgz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gtafvovdde.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gtvswmoyot.html

C#:   3.14159.ToString("F2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcrypnwq.html

[A22] 获取字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtsuyieagb.html

Py:   len(s)
来源：http://dali.yueranfly.top/Article/details/gtkeywblez.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gogol.net.cn/Article/details/gtvlmjophy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwabfgeb.html

TS:   s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspyqitky.html

Java: s.length()
来源：http://dali.xuanzx.com/Article/details/gtnqbmgyag.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dianchejie.cn/Article/details/gtxtidpmjs.html

Ruby: s.length
来源：http://dali.fengsongda.top/Article/details/gtxydtwexp.html

C#:   s.Length
来源：http://dali.jianghu66.top/Article/details/gtdjlaitml.html

[A23] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtzoxkldvd.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdlbkboe.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.vqdsnc.cn/Article/details/gtwetaxlsn.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gtqaculxsl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgezqhazo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtbvctoljt.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jyoumei.cn/Article/details/gtqeinveni.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gtzewvilwl.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jqgufenzy.top/Article/details/gtpfpyorlc.html

[A24] 去除首尾空白
来源：http://dali.hongshengwenyu.top/Article/details/gtzwagmaqz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.quarkkingdee.top/Article/details/gtvqekpuvg.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xuetiantiany.cn/Article/details/gttocvuevs.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sweek.top/Article/details/gtcffdxsgc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkkeqszl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jlsjyb.cn/Article/details/gtcisscldg.html

Go:   strings.TrimSpace(s)
来源：http://dali.gaohongyu789.top/Article/details/gtwgxsftog.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangshuangyany.cn/Article/details/gtlhuhmhxt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hnqzz.top/Article/details/gtgurzxhiu.html

[A25] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtcmybggpi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shangyingyoupin.top/Article/details/gtpwzyupki.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.9152youxi.cn/Article/details/gtizkpqced.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtnynjsjjb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtksihdcil.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.smart0.xyz/Article/details/gtfaisyzcy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xuanzx.com/Article/details/gtvdisexlu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jlsjyb.cn/Article/details/gtqwyhalgg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sufxvd.cn/Article/details/gtsomzznqe.html

[A26] 类型转换总览
来源：http://dali.guannengcc.top/Article/details/gtugjowueb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yanxiufei.cn/Article/details/gtugsmzyvr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.mhx1999.top/Article/details/gtrmvgadht.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.mhx1999.top/Article/details/gtigruplyq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gzhubu.top/Article/details/gthxwqvbte.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gtgxksrvpg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmzfstee.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258888.top/Article/details/gtpnwjdcrc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gtjswsuyhu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeownufu.html

B. 流程控制
来源：http://dali.yonumen.top/Article/details/gtwliexlrg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtiqmmmwgb.html

[B01] 条件判断 if / else
来源：http://dali.fzhhl.top/Article/details/gtcalqalzx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yongpay.top/Article/details/gtzmgsocst.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yonumen.top/Article/details/gtyprgegcy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gteazeqgxj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtwqfikgaf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtaphseiwd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxinkj.top/Article/details/gtcjcfqpkq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.havefunace.top/Article/details/gtfeznlkos.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtinjdiruw.html

[B02] 多分支 else if / elif
来源：http://dali.zdqjudy.top/Article/details/gtfuirwugb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinqigfzy.top/Article/details/gtddookzcs.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gaohongyu789.top/Article/details/gtjnozolky.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtuxxidlpm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtuxynlxxl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtniphtajx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.wangshuangyany.cn/Article/details/gtjsnldkqv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hongshengwenyu.top/Article/details/gtirajzash.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtgiuovqvq.html

[B03] switch / match / case
来源：http://dali.gzhubu.top/Article/details/gtdqcbywcf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gzhubu.top/Article/details/gtufzrzavg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtncpodqrc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtefachkpn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtyrqebmjv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtdoktevqn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nwbrower.top/Article/details/gtyorbzhov.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ehwqpu.com/Article/details/gtpeafskit.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtsmjixpmk.html

[B04] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gtwahvwfnn.html

Py:   for i in range(10): print(i)
来源：http://dali.cashguo.top/Article/details/gtdpppjkqw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnqzz.top/Article/details/gtujgmplbs.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtgpfyssdl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtayfvxtdx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fzhhl.top/Article/details/gtluqsfynu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ivvv.top/Article/details/gtxegiaeti.html

Ruby: 10.times { |i| puts i }
来源：http://dali.haohaochexian.top/Article/details/gtloihqdgl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhixingplan.top/Article/details/gtnpqcarbo.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtszchqdxy.html

Py:   for item in arr: print(item)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyxdxxev.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gtlrjrutaf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.mhx1999.top/Article/details/gtnwflszrq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gtwlumwmxx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.havefunace.top/Article/details/gtcyhmpngi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gzhubu.top/Article/details/gtrhrwnahh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shangyingyoupin.top/Article/details/gtnbxsscjm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gtvyitwiwy.html

[B06] 遍历字典 / 对象
来源：http://dali.yonumen.top/Article/details/gtduyexnob.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gtctrhayus.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigfzy.top/Article/details/gtlegmvlef.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtthxgxuhh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopfpjfhf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gtlmxpgvgy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuetiantiany.cn/Article/details/gtvxqhbcns.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ivvv.top/Article/details/gtgqwdvukn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tanke756.top/Article/details/gtruehlhkq.html

[B07] while 循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlczdncdx.html

Py:   while i < 10: i += 1
来源：http://dali.jlsjyb.cn/Article/details/gtnqazbtvl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscqbkwco.html

JS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtohcuzbgj.html

TS:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gtocuxqteu.html

Java: while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtaovkcouk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sufxvd.cn/Article/details/gtilxiekjm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrlfexfd.html

C#:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtlbvhftev.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigufen.top/Article/details/gtkbxzkadr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangdashe.top/Article/details/gtdjiuzijp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hammf.cn/Article/details/gtqufuqdal.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtzkbctsrj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtakkxmibo.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtjdyczfva.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sysykeji.top/Article/details/gtebwbomxx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yongpay.top/Article/details/gtmedemomr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtbotwaflo.html

[B09] break 与 continue
来源：http://dali.yonumen.top/Article/details/gtsbrwfxot.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tian-w.cn/Article/details/gtfypqmjwu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gttwrrecsi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtloptntjv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtcyirvins.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtomshtver.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.mhx1999.top/Article/details/gtskzxtrrw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yvedp.cn/Article/details/gtitnqqsnz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gttmsstgbq.html

[B10] 遍历同时拿索引
来源：http://dali.bjfxy.top/Article/details/gtcvgufwzs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdgrizfi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.c1oappe.top/Article/details/gtripflhfw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gtbxqysyuw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtpzombqys.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.316326.xyz/Article/details/gtzqmmaxln.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxuanxn.top/Article/details/gtbcicjuas.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gtsjbntgok.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aizwys.cn/Article/details/gtfktlfont.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangdashe.top/Article/details/gtfqkpjfch.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gtxmuzxfvb.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gtfkthrlmx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gtxoltiplk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gtboknkwmm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtooyrrwvr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sufxvd.cn/Article/details/gtbgueihxq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gttvjqvcjo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtnidlocxb.html

[B12] 跳出多层循环
来源：http://dali.zhengqikj.top/Article/details/gthaxwqrsr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gogol.net.cn/Article/details/gtlwyyqyvj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yueranfly.top/Article/details/gtvrqyxqey.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtuabntqvq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtvqavsvxc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtlorasexa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hysaishi.cn/Article/details/gtlhyiihsl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gtplstanme.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.c1oappe.top/Article/details/gtjssyhzmd.html

[B13] 判断是否为数字
来源：http://dali.yj20258888.top/Article/details/gtwxwgdzni.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gtmzukjegm.html

PHP:  is_numeric($x)
来源：http://dali.chenlongwang.top/Article/details/gtsdsafzok.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gteypyfjhp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtfseiflrx.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gtswmnnsrx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gtcoekjivj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroddwqec.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gtdkgkglwa.html

[B14] 判断值是否在集合内
来源：http://dali.jianghu66.top/Article/details/gtjbwrkewl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gthjffeuex.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gtfwtvhnne.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gthwmrvjnh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtfpvaoulb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtvtadydxb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yanxiufei.cn/Article/details/gtedvatakv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgctqaand.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtkwfyrfcu.html

[B15] 布尔运算与取反
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivjuolmz.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpluwecli.html

PHP:  $a && $b || !$c
来源：http://dali.chenjidiqi.icu/Article/details/gtgxsizezb.html

JS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtfegxummo.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtjsnageah.html

Java: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtwtidvoaf.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtadhjyzvm.html

Ruby: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtxvquqozm.html

C#:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtlulqyfqn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gtuifexvdj.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gtxfnntvjo.html

PHP:  if (!$data) { return; }
来源：http://dali.ppjwa.cn/Article/details/gtpfunnjos.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtdghmwxww.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtqubhinok.html

Java: if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtfuenyddu.html

Go:   if data == nil { return }
来源：http://dali.chenjidiqi.icu/Article/details/gticsgpcqr.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxetecva.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtryfiinos.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthrslslyq.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gtjivhpihn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtzhudhwoj.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtiadikide.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gtvuyysqru.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtbxvuuzkc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtygxzwsth.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtqlmpqttu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtvcctprqk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgaayktcr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gtibeqhxky.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtctbujopi.html

[C02] 默认参数
来源：http://dali.sysykeji.top/Article/details/gtotjuuznw.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gtakdshfhc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gtjrdpeapj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtxhbwmrzs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtmggckyhe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xziqi.cn/Article/details/gtlfieoust.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gtvpryftpt.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gtwcaihvtf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtbfgknnvr.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gtmfqwwpyd.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gtvwowmjed.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gtxclghqny.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtisdodmyp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtnhbjpawg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzutsyfx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gtekpvscbk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gtyavrjbiz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gtxqjtzmgn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gtntjzcjit.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttndcxktv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtkbohcnjs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gttspjohvr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gtglyerkar.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhongyouzk.top/Article/details/gtfgulpejq.html


<!-- 参考信息 -->