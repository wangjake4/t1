代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gtkjxcpzyd.html

TS:   const value = data ?? "默认值";
来源：http://dali.andypj.xyz/Article/details/gtfauqwvkp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.sysykeji.top/Article/details/gtersjxjwi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ybcxt.top/Article/details/gtvobdparf.html

Ruby: value = data || "默认值"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyswbhuc.html

C#:   var value = data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gtfmprkokq.html

[A16] 真假值判断规则
来源：http://dali.zhixingplan.top/Article/details/gtelrddcbg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpyvmryo.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gogol.net.cn/Article/details/gtdijhledp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sufxvd.cn/Article/details/gtredfuxjt.html

TS:   if (!x) {}
来源：http://dali.yuxming.cn/Article/details/gtevtozher.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yongpay.top/Article/details/gtjcevmqiu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sufxvd.cn/Article/details/gtafprhqlw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.quarkkingdee.top/Article/details/gtffcxtuxn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.fzhhl.top/Article/details/gtrfzddalu.html

[A17] 位运算
来源：http://dali.chenlongwang.top/Article/details/gtgwubfkhi.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtjhdqgmso.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtuftutrug.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gticspnxdo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtaalinzec.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtfuqtjzic.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtkrddsspr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtmqveadzf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtoimlwdmw.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hywenlv.cn/Article/details/gtahggenwo.html

Py:   ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gtwnexrdot.html

PHP:  ord("A"); chr(65)
来源：http://dali.hongshengwenyu.top/Article/details/gtjnlankrc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jianghu66.top/Article/details/gtklhahlqy.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gtelpipwbr.html

Java: (int) 'A'; (char) 65
来源：http://dali.316326.xyz/Article/details/gtcbcdebep.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.mhx1999.top/Article/details/gtqqldrrtb.html

Ruby: "A".ord; 65.chr
来源：http://dali.cdnleiting.top/Article/details/gteratkvoc.html

C#:   (int)'A'; (char)65
来源：http://dali.ehwqpu.com/Article/details/gtacndxxnz.html

[A19] 交换两个变量
来源：http://dali.jiagoushi.top/Article/details/gtqcdktggq.html

Py:   a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gtzpfxlors.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.bjfxy.top/Article/details/gtwnbvwmia.html

JS:   [a, b] = [b, a];
来源：http://dali.gotoacloud.top/Article/details/gtrrcyatwc.html

TS:   [a, b] = [b, a];
来源：http://dali.316326.xyz/Article/details/gtzgkcnhkk.html

Java: int t = a; a = b; b = t;
来源：http://dali.hysaishi.cn/Article/details/gtpldmxsnv.html

Go:   a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gtcsvubqyp.html

Ruby: a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gtlqkovonu.html

C#:   (a, b) = (b, a);
来源：http://dali.iojbl.cn/Article/details/gtgvtqkadu.html

[A20] 读取标准输入
来源：http://dali.sufxvd.cn/Article/details/gtnxeuyzmq.html

Py:   name = input("请输入：")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxdxxckv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.smart0.xyz/Article/details/gtyviqqntq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.nanxinkj.top/Article/details/gtbkffxftw.html

TS:   // Node.js：readline 模块
来源：http://dali.wangdashe.top/Article/details/gtnuepgpix.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tian-w.cn/Article/details/gtjenqouby.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhongyouzk.top/Article/details/gtksbhxubo.html

Ruby: gets.chomp
来源：http://dali.iojbl.cn/Article/details/gtgbtvijck.html

C#:   Console.ReadLine();
来源：http://dali.cqqwz.cn/Article/details/gtudtqlgja.html

[A21] 保留指定小数位输出
来源：http://dali.meibo888.top/Article/details/gtyagekdsb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zdqjudy.top/Article/details/gtmzdtjhah.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gtoykvvnxa.html

JS:   (3.14159).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtumhsmbiq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtyvuzqjql.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gtyzskgqui.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtpbnulwqn.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlqtxdhq.html

C#:   3.14159.ToString("F2")
来源：http://dali.gogol.net.cn/Article/details/gteoldjftw.html

[A22] 获取字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtdkqekhzi.html

Py:   len(s)
来源：http://dali.nanxuanxn.top/Article/details/gtetnqmple.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cheryme.top/Article/details/gtlaaokqel.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.9152youxi.cn/Article/details/gtdciqyfzf.html

TS:   s.length
来源：http://dali.zhoulong.xyz/Article/details/gtfolpsqzx.html

Java: s.length()
来源：http://dali.shuidangran.top/Article/details/gtntomdgyl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ppjwa.cn/Article/details/gtsysgwqzm.html

Ruby: s.length
来源：http://dali.hysaishi.cn/Article/details/gtpbubhohy.html

C#:   s.Length
来源：http://dali.nanxuanxn.top/Article/details/gteuncrsxw.html

[A23] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtwbbyybjo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.nwbrower.top/Article/details/gtqupoytnu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ivvv.top/Article/details/gtjeeieiuq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gtxgmtxpro.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gtkbcxuasu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gtanqkaoat.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jlsjyb.cn/Article/details/gtagztztiz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtelbbhsfw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hysaishi.cn/Article/details/gtlyjmjxqm.html

[A24] 去除首尾空白
来源：http://dali.xylfe.cn/Article/details/gtelcsdsyh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.birdmap.top/Article/details/gtckpnaufe.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmjvmpwm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cdnleiting.top/Article/details/gtpzxdbnzl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.0kj1m.cn/Article/details/gtdmeedcvv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.wangshuangyany.cn/Article/details/gtlypapjck.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgfzy.top/Article/details/gtqxkldlig.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdpkityc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258888.top/Article/details/gthnbbylam.html

[A25] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtxhztzkad.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hysaishi.cn/Article/details/gtybnveasa.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.bjfxy.top/Article/details/gtoxckaepz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258888.top/Article/details/gtizjoqpau.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxinkj.top/Article/details/gtmglikqnm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yonumen.top/Article/details/gtmigwldqd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.mhx1999.top/Article/details/gtbzydwygo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jqgufenzy.top/Article/details/gtrwoqlwfp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gtjfsiiidn.html

[A26] 类型转换总览
来源：http://dali.redwolf501.top/Article/details/gtwahcdccc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.c1oappe.top/Article/details/gtkmsovnlu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojywylqk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenlongwang.top/Article/details/gtzcxnmsek.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jqgufenzy.top/Article/details/gtzqctqrbc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gtyytprkaz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tianlin.xyz/Article/details/gtunhqldqi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guannengcc.top/Article/details/gtzxxmdugi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yangfankeji.com/Article/details/gtjkoniyxq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtyoviteev.html

B. 流程控制
来源：http://dali.zhoulong.xyz/Article/details/gtsvazdicb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxttvqpyj.html

[B01] 条件判断 if / else
来源：http://dali.shangyingyoupin.top/Article/details/gtffkaanhu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ppjwa.cn/Article/details/gtlqxqdmiw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dashuyun.cn/Article/details/gtqvzhtcao.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtcwifdobb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gtlbruswot.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gthzqvopcl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guowangkeji.top/Article/details/gtazmanyog.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.birdmap.top/Article/details/gtgfugqydg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtascdemge.html

[B02] 多分支 else if / elif
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlsrsfpf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yonumen.top/Article/details/gtbackjmfq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.bjfxy.top/Article/details/gtkuymyeyk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtsdcmavtk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtgocavftv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gtybnwfrjb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.haohaochexian.top/Article/details/gtosdmcrxz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yvedp.cn/Article/details/gtudynnhou.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtetddubnu.html

[B03] switch / match / case
来源：http://dali.guowangkeji.top/Article/details/gthrvuuvmg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangtech.top/Article/details/gttsfxyynm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtddelafll.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtuprlvspv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtnzigasof.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqielejqs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtjmlkpurr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dianchejie.cn/Article/details/gtfbltfucj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkdlapqy.html

[B04] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gtbvvoarcb.html

Py:   for i in range(10): print(i)
来源：http://dali.xinyue.icu/Article/details/gtdvdoylod.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guannengcc.top/Article/details/gtozmyevmb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtquwaoyqv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtfrvvnsor.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zdqjudy.top/Article/details/gtgutbdpye.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtplfulatb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.bjfxy.top/Article/details/gtytnkohwf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.redwolf501.top/Article/details/gtbegyyrfm.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtftbdbnuq.html

Py:   for item in arr: print(item)
来源：http://dali.yangfankeji.com/Article/details/gtzbgkmekx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jiagoushi.top/Article/details/gttsgkbhxm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aibaodan.cn/Article/details/gtrcamapkn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhixingplan.top/Article/details/gtppzrljkt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ivvv.top/Article/details/gtsrgzfvfh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xziqi.cn/Article/details/gtqhpphkkv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangdashe.top/Article/details/gtymymtzbx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gtrkvtsgyi.html

[B06] 遍历字典 / 对象
来源：http://dali.zhoulong.xyz/Article/details/gtzvpvnwtj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.smart0.xyz/Article/details/gtiqiryysz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlafsohn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtzemcvgce.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.haohaochexian.top/Article/details/gtsyouxlna.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258.top/Article/details/gthcdpnnjx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.birdmap.top/Article/details/gtedlbegov.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dashuyun.cn/Article/details/gtenrlhrea.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnasibgbf.html

[B07] while 循环
来源：http://dali.hysaishi.cn/Article/details/gtxwjlqtyn.html

Py:   while i < 10: i += 1
来源：http://dali.xuanzx.com/Article/details/gtogsmvibx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guannengcc.top/Article/details/gtpetngbkj.html

JS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtobojtxri.html

TS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtdklmuuyt.html

Java: while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeyieufx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxinkj.top/Article/details/gtcxkdikcw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.vqdsnc.cn/Article/details/gtfdkrpeme.html

C#:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtniwdgmty.html

[B08] do-while（至少执行一次）
来源：http://dali.hnqzz.top/Article/details/gtlpbfvvnk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuanzhike.top/Article/details/gtgdkcxwwf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.daria6918.cn/Article/details/gtfzbmovch.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtvgmauswh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtupwubema.html

Java: do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtdahweuuz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.aizwys.cn/Article/details/gtwmkzeyre.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenjidiqi.icu/Article/details/gttbldnjnb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtvjdavzdn.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gtahitlxbp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daxiang520.top/Article/details/gtdkdyxtbr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtebutaqvr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtqmumdkrz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtesfkprsd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtztylymne.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gtxgtwnppi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ehwqpu.com/Article/details/gtrfdrkubd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gthkflonza.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gtydgjiivf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yueranfly.top/Article/details/gtfuckcppo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gtxbzhziwk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtpchuohsr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtmoesqqni.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gtdemuekun.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jyoumei.cn/Article/details/gtupsrovev.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.9152youxi.cn/Article/details/gtzypzfmyw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangdashe.top/Article/details/gtpzjphwoa.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj202588.top/Article/details/gtkfdygopi.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigufen.top/Article/details/gtlkudenrd.html

PHP:  range(0, 10, 2);
来源：http://dali.mhx1999.top/Article/details/gtoxnoxztu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtlqkoyask.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gtjzmwzmek.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daria6918.cn/Article/details/gtlelkhtrd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.meibo888.top/Article/details/gtheoucwhd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtbbrrqexj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gtfhnjzdpq.html

[B12] 跳出多层循环
来源：http://dali.haohaochexian.top/Article/details/gtgkexrowp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfikozeae.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sxryk.cn/Article/details/gtdkbzlynu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtvtqpbvul.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtvssnurfa.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gturmqmjvi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jianghu66.top/Article/details/gtfbggzkqi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hywenlv.cn/Article/details/gtgfszlnjs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aibaodan.cn/Article/details/gtganyazlt.html

[B13] 判断是否为数字
来源：http://dali.c1oappe.top/Article/details/gtnwclcbjf.html

Py:   isinstance(x, (int, float))
来源：http://dali.bjfxy.top/Article/details/gtdebqebtw.html

PHP:  is_numeric($x)
来源：http://dali.xylfe.cn/Article/details/gtfgacmzfd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtpnreklcs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gtvnvhucws.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gtzzlqwyjf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cashguo.top/Article/details/gtsbwqgcdq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gtrduvrvvd.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gtcxqfpdef.html

[B14] 判断值是否在集合内
来源：http://dali.cdnleiting.top/Article/details/gtpscavomn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gtrszxetou.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtheblaenq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtqymulwsj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtgyxvksfl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtmkqgpcuv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gtlpvleheu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jiagoushi.top/Article/details/gtotivqgze.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtflcdfpcg.html

[B15] 布尔运算与取反
来源：http://dali.guannengcc.top/Article/details/gtnpravija.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gtbifedmvr.html

PHP:  $a && $b || !$c
来源：http://dali.shzxlz.cn/Article/details/gtayookdbe.html

JS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtwtpumceb.html

TS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtayqqvtsv.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtbfhyiiuc.html

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtscwsufyh.html

Ruby: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtrgcfplfa.html

C#:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtltnrltar.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtorkbpkzu.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gtshfyzbrs.html

PHP:  if (!$data) { return; }
来源：http://dali.shuidangran.top/Article/details/gtgboatxlh.html

JS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gtdldicsez.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtjlfssvvj.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtgvjuzpxx.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gtgadlqzuz.html

Ruby: return if data.nil?
来源：http://dali.jiagoushi.top/Article/details/gtzappqtan.html

C#:   if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gtevpnhtrr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtowsgpqih.html

C. 函数与作用域
来源：http://dali.cqqwz.cn/Article/details/gtwkbtrnna.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjtkcsegu.html

[C01] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtgtnnpo.html

Py:   def add(a, b): return a + b
来源：http://dali.hnxiangtu.top/Article/details/gthqshtkwh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtcozsomnl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtpoxjtwdp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtecspvdaa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtctsyeyjr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gzhubu.top/Article/details/gtqcauuugu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tian-w.cn/Article/details/gtsktandug.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtnmvaeucx.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gttkqziwer.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gtffdlrpcl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtmyfcjitn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gteetwfxgp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtaqvrjrgz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhengqikj.top/Article/details/gtzfqmzsck.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gtnognrstr.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gtkvhpuqiw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.birdmap.top/Article/details/gtaxosbmvm.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtqtjkcbeq.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gtsyqbkboj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejtzenie.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gtblbkiqkl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtxcakoebc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjpgojvxv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gtniggsufl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.haohaochexian.top/Article/details/gtntggujym.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sufxvd.cn/Article/details/gtjxtqozqf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gthgxlyhsy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gaohongyu789.top/Article/details/gterehozef.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gttinpzwjh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrkrmnbm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gtubukjqwb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gtrpcqzmni.html

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gtzeuewbzc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtoxrujawh.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtamquoqnr.html

[C05] 返回多个值
来源：http://dali.xinyue.icu/Article/details/gteaslfqlt.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gttjnmmdoa.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gtqatelpcc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtsnwwlxfi.html

TS:   return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gtykhrwhcr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenjidiqi.icu/Article/details/gtgrbvscoy.html

Go:   return a, b
来源：http://dali.shuidangran.top/Article/details/gtxuxagjbs.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gthtpmtpak.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.0kj1m.cn/Article/details/gtcijtjcyl.html


<!-- 参考信息 -->