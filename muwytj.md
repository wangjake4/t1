代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdsoukne.html

TS:   const value = data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gtzpbmbyfw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.mhx1999.top/Article/details/gtlywaqenr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbloxhyku.html

Ruby: value = data || "默认值"
来源：http://dali.zdqjudy.top/Article/details/gtndjibmfp.html

C#:   var value = data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gtytrjtrve.html

[A16] 真假值判断规则
来源：http://dali.ydzc1.top/Article/details/gtwkgjkpry.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xziqi.cn/Article/details/gtetwtitxb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenzaomai.com/Article/details/gtqypydwqi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yueranfly.top/Article/details/gtnnosvogi.html

TS:   if (!x) {}
来源：http://dali.ydzc1.top/Article/details/gtffcciomy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.tanke756.top/Article/details/gtpfnmttts.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.dianchejie.cn/Article/details/gtfhhnlicp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cdnleiting.top/Article/details/gtddqdkzoq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cqqwz.cn/Article/details/gthdpefcrq.html

[A17] 位运算
来源：http://dali.xinyue.icu/Article/details/gtwgfkhicb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtzvpblpwr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xinyue.icu/Article/details/gtcafcjvox.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gtotgqhgcx.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtzboujgeq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtfstubmrg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtihlglehu.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtjzmdsqsg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtlplasibe.html

[A18] 字符与 ASCII 码互转
来源：http://dali.haohaochexian.top/Article/details/gtrtjdjtcj.html

Py:   ord("A"); chr(65)
来源：http://dali.hongshengwenyu.top/Article/details/gtvfumkweo.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gtulrlyczt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.c1oappe.top/Article/details/gtqflkozfe.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xylfe.cn/Article/details/gtltjafsrk.html

Java: (int) 'A'; (char) 65
来源：http://dali.jqgufenzy.top/Article/details/gtbxbjtppf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hnqzz.top/Article/details/gtxbswudsm.html

Ruby: "A".ord; 65.chr
来源：http://dali.hfpthk.cn/Article/details/gtrsdpdsef.html

C#:   (int)'A'; (char)65
来源：http://dali.chenjidiqi.icu/Article/details/gtgkqzlehu.html

[A19] 交换两个变量
来源：http://dali.shangyingyoupin.top/Article/details/gtepsyzext.html

Py:   a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gthucqrjjo.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yueranfly.top/Article/details/gtbqlowfyc.html

JS:   [a, b] = [b, a];
来源：http://dali.pycfn.com/Article/details/gtcpfnzrmh.html

TS:   [a, b] = [b, a];
来源：http://dali.ehwqpu.com/Article/details/gtwyplameq.html

Java: int t = a; a = b; b = t;
来源：http://dali.xuetiantiany.cn/Article/details/gtobeeqwgz.html

Go:   a, b = b, a
来源：http://dali.tianlin.xyz/Article/details/gtnjzjmogk.html

Ruby: a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gtpnubwlgo.html

C#:   (a, b) = (b, a);
来源：http://dali.nwbrower.top/Article/details/gtorajuqtx.html

[A20] 读取标准输入
来源：http://dali.sufxvd.cn/Article/details/gtnaoxowsc.html

Py:   name = input("请输入：")
来源：http://dali.cashguo.top/Article/details/gtbkzwjpwr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gzhubu.top/Article/details/gtnfdkqsyw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xziqi.cn/Article/details/gtrlgttzhs.html

TS:   // Node.js：readline 模块
来源：http://dali.zhijiandao.cn/Article/details/gtnkubspgt.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cucudq.cn/Article/details/gtclqdtaed.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zdqjudy.top/Article/details/gtseqsdkkq.html

Ruby: gets.chomp
来源：http://dali.cheryme.top/Article/details/gttswturgj.html

C#:   Console.ReadLine();
来源：http://dali.nanxinkj.top/Article/details/gtwmtondgq.html

[A21] 保留指定小数位输出
来源：http://dali.gzhubu.top/Article/details/gtvvbovcpk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.kuanghao11.cn/Article/details/gttdrztubr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtcitqnzvh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gtaexuunec.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gtrptghfqg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gthtizwaij.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gtwercurgs.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtxvqunusb.html

C#:   3.14159.ToString("F2")
来源：http://dali.gotoacloud.top/Article/details/gtybvvbgdz.html

[A22] 获取字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtkbhytzsv.html

Py:   len(s)
来源：http://dali.xinyue.icu/Article/details/gtxbuoxanx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jlsjyb.cn/Article/details/gtsqavmqgy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dashuyun.cn/Article/details/gtukisprjs.html

TS:   s.length
来源：http://dali.ppjwa.cn/Article/details/gtptoasxkr.html

Java: s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrycymihp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgzfiixu.html

Ruby: s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdedxgzw.html

C#:   s.Length
来源：http://dali.daria6918.cn/Article/details/gtgxhberbi.html

[A23] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gthbgdfnud.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.fengsongda.top/Article/details/gtwovijtiq.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.nwbrower.top/Article/details/gtekuylrky.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tanke756.top/Article/details/gtodnzycui.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cdnleiting.top/Article/details/gtwvuyexnt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gttspqxnsz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtykfmibgr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.mhx1999.top/Article/details/gtbpzjqnaf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shangyingyoupin.top/Article/details/gtjiuafcec.html

[A24] 去除首尾空白
来源：http://dali.aibaodan.cn/Article/details/gtkhgqsvub.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jianghu66.top/Article/details/gtvuhcefex.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yj20258888.top/Article/details/gtkozngptp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gtpmveyuvr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gtpzjlmgpt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xinyue.icu/Article/details/gttnilsuih.html

Go:   strings.TrimSpace(s)
来源：http://dali.dianchejie.cn/Article/details/gtxarplszf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hammf.cn/Article/details/gtgtjotydb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gtettnvadp.html

[A25] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtzqzcomnf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sweek.top/Article/details/gtmbboptvg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jianghu66.top/Article/details/gtnhvshhep.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xylfe.cn/Article/details/gtlebolqsg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlphguczy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pycfn.com/Article/details/gtilfdjeej.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gtleplnnoe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.bjfxy.top/Article/details/gtuzcoohwz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gtzmwqshjg.html

[A26] 类型转换总览
来源：http://dali.yj202588.top/Article/details/gtpobssskr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.redwolf501.top/Article/details/gtjfljipex.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yvedp.cn/Article/details/gtqihsxzdn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.smart0.xyz/Article/details/gtkccnikdi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.meibo888.top/Article/details/gtutvwmxzs.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gtlymmqygc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ehwqpu.com/Article/details/gtklyzuius.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.bjfxy.top/Article/details/gthdimvini.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.mhx1999.top/Article/details/gtcbdqiayx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtngtlpngx.html

B. 流程控制
来源：http://dali.haohaochexian.top/Article/details/gttfmljbbv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfedrshl.html

[B01] 条件判断 if / else
来源：http://dali.meibo888.top/Article/details/gtyfvkrinf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.redwolf501.top/Article/details/gtgzsmonzq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.wangdashe.top/Article/details/gtyibisbnb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtjpzjiona.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtjsdvapel.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtlipicycw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ybcxt.top/Article/details/gtdbgkbkfi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gtsheyeaqm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtztynoxyu.html

[B02] 多分支 else if / elif
来源：http://dali.wangdashe.top/Article/details/gtjpwmifql.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yangfankeji.com/Article/details/gtpewxcdzl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yangfankeji.com/Article/details/gttmwrfaxf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtzbmtderw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtkyrfeuik.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtvdkmbwne.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jqgfzy.top/Article/details/gtmqnozmsl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxfbpuud.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gtvrknhtzw.html

[B03] switch / match / case
来源：http://dali.cucudq.cn/Article/details/gtkhjdqmww.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.andypj.xyz/Article/details/gtsktqyonk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gtwhxuujqc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gttyplznpq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gttutbsqed.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmzhdsxov.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotezyfkk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gaohongyu789.top/Article/details/gtgaxhjeof.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yonumen.top/Article/details/gtpjunzpfx.html

[B04] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtqldpqbot.html

Py:   for i in range(10): print(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtxjdttsrn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.kuanghao11.cn/Article/details/gtsngjxyiv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtqxylcmcd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gtrhgisztc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ivvv.top/Article/details/gtjvwbyury.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yongpay.top/Article/details/gtybybdnjz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuetiantiany.cn/Article/details/gtireklwye.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ivvv.top/Article/details/gtafvmnwfp.html

[B05] 遍历数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtacmmlatz.html

Py:   for item in arr: print(item)
来源：http://dali.havefunace.top/Article/details/gtjtikyrtp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwapbjbbc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtykorswtt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guowangkeji.top/Article/details/gtamzqwsbu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zycfv.cn/Article/details/gtvtxfrhch.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxwsqblu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj202588.top/Article/details/gtceusmtyk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.haohaochexian.top/Article/details/gtkjwltjpr.html

[B06] 遍历字典 / 对象
来源：http://dali.0kj1m.cn/Article/details/gtkbpwkqdy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hammf.cn/Article/details/gtrgpsvpoi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuanzx.com/Article/details/gtsihfjwvy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gtxiuxxdgi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gtbjihnbvf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhixingplan.top/Article/details/gtooiwvtqy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnqzz.top/Article/details/gtyiuxluwm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daxiang520.top/Article/details/gtfttjtckp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhongyouzk.top/Article/details/gtussxqckv.html

[B07] while 循环
来源：http://dali.jinqigufen.top/Article/details/gtcbztduou.html

Py:   while i < 10: i += 1
来源：http://dali.kuanghao11.cn/Article/details/gtovfaginl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.0kj1m.cn/Article/details/gtthigsllv.html

JS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtzvlfblmj.html

TS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtiauquiwi.html

Java: while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtesvsjjzu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenlongwang.top/Article/details/gtrjknbzkw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nwbrower.top/Article/details/gtuewwlmds.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtbxcubwba.html

[B08] do-while（至少执行一次）
来源：http://dali.yj202588.top/Article/details/gthusorvbe.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daria6918.cn/Article/details/gtcgbcwihx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cheryme.top/Article/details/gtpmsqolrg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtdzaometn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtzmubjzyt.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gteyyhoxxb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sysykeji.top/Article/details/gtjlezpvpy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gtacriwsuq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtlocukurs.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gtecosepah.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuanzx.com/Article/details/gtgkjpxlve.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtevsvphyu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtttncvbmm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtoalbulut.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtksxhwjui.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ybcxt.top/Article/details/gtlrqvgrnx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gaohongyu789.top/Article/details/gttcwyagcy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtqmnrqtqc.html

[B10] 遍历同时拿索引
来源：http://dali.shzxlz.cn/Article/details/gtrwshlgdz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yueranfly.top/Article/details/gtitfsratw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shuidangran.top/Article/details/gtsdgsusbs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtzibriqwo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gtjjksanho.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigufen.top/Article/details/gtdriziuqj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daria6918.cn/Article/details/gtygcehrdx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xylfe.cn/Article/details/gtxeowfgwj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmweynwvx.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gtpywpigzw.html

Py:   list(range(0, 10, 2))
来源：http://dali.pycfn.com/Article/details/gttannonxl.html

PHP:  range(0, 10, 2);
来源：http://dali.jyoumei.cn/Article/details/gtddekgvcg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtnctiqznv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gtjufytfmb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.havefunace.top/Article/details/gtqespkpsk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnqzz.top/Article/details/gtkbkersvi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.birdmap.top/Article/details/gtkhdnaloo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sysykeji.top/Article/details/gtvchkzese.html

[B12] 跳出多层循环
来源：http://dali.snrcjt.cn/Article/details/gtvtbnjqpd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtriczqzfq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gteveiyoae.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtytymjbhd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtpgagrylc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtsvckrnqm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gtmlirqdwo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.vqdsnc.cn/Article/details/gtpquwvawc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gtfacgyfkx.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtkahaswvo.html

Py:   isinstance(x, (int, float))
来源：http://dali.vqdsnc.cn/Article/details/gtplqhqhiz.html

PHP:  is_numeric($x)
来源：http://dali.daxiang520.top/Article/details/gtftqiggrn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtsguwrldw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtldbfrqsv.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gtyindkjyv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nwbrower.top/Article/details/gtzgpdcvln.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cucudq.cn/Article/details/gtrvjejmvb.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gtfxkbcxok.html

[B14] 判断值是否在集合内
来源：http://dali.hongshengwenyu.top/Article/details/gtuzckafiv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.birdmap.top/Article/details/gtxfevaowb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cdnleiting.top/Article/details/gtrgyuewtc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtqprwhtqt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtojgcmlli.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtvovysexg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.quarkkingdee.top/Article/details/gtcciklovo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tian-w.cn/Article/details/gtdqnnoctd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcqilkat.html

[B15] 布尔运算与取反
来源：http://dali.cashguo.top/Article/details/gtebohklcl.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gtwjaoyqyo.html

PHP:  $a && $b || !$c
来源：http://dali.xylfe.cn/Article/details/gtndjsmfaw.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtnrcutrxp.html

TS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtjdypkzbi.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtkvxdzbys.html

Go:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtbvphjzsw.html

Ruby: a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtoovwsebo.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtuwhpzgff.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtlvjbhsjj.html

Py:   if not data: return
来源：http://dali.zhixingplan.top/Article/details/gtbqlugbpn.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gtybnjbpte.html

JS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtcwyvyvhc.html

TS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtloyhuiws.html

Java: if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gtdauawysa.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gtyjfolryr.html

Ruby: return if data.nil?
来源：http://dali.yangfankeji.com/Article/details/gtkayynwit.html

C#:   if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtuwusagzq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxlcqfkso.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtmqfprrib.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrpvrvimg.html

[C01] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gtwauxmnvy.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gtrizmxojj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtandimxxl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtzpqskxzu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtcdixyile.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtanmwbnma.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.havefunace.top/Article/details/gteclgbvpi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gtkiclpjwv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtotbtnsgk.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnfpdpfr.html

Py:   def greet(name="World"): return name
来源：http://dali.nwbrower.top/Article/details/gtnmhifpgs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnqzz.top/Article/details/gtnzvoqigx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtuxxfdcxg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtvajudxpo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtsajgewrw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sxryk.cn/Article/details/gtpvbewaat.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnxiangtu.top/Article/details/gtxhvqkvyr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtlnjthklo.html

[C03] 可变参数
来源：http://dali.nwbrower.top/Article/details/gtgiajnnnx.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gtfvdagwpq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gttddpsaey.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gtmlswvuya.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtwovobofn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gtnyvoanah.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gtxiduqgkv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtpeuliwtn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gtqaxfxnhb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gtiwasdnhf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xziqi.cn/Article/details/gthurxlsvb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.redwolf501.top/Article/details/gtntnozdkg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtlioxjxcc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dianchejie.cn/Article/details/gtugngepxz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gtxatdxblq.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gtmramprnz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtpicigbxw.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasaohzgp.html

[C05] 返回多个值
来源：http://dali.0kj1m.cn/Article/details/gteeqqhzrk.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtwuygqzpv.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gtpijyibwx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.havefunace.top/Article/details/gtkslopjnn.html

TS:   return { a, b };
来源：http://dali.ivvv.top/Article/details/gtnthzmbmj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dashuyun.cn/Article/details/gtrauwdurg.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gteiirhjva.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtlwowwcyb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gtqsuwhcui.html


<!-- 参考信息 -->