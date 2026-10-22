代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ydzc1.top/Article/details/gtpyzivfeq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xylfe.cn/Article/details/gtsckzsyxi.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jianghu66.top/Article/details/gtzcpgrrcd.html

[A17] 位运算
来源：http://dali.aizwys.cn/Article/details/gtgjmefcza.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtsbcmougn.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtbqqmvbgk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gticbllovi.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtscybehlm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtsvmqhghv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gttvcoejxs.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtjrktjcux.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtdktjplnp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sysykeji.top/Article/details/gtqnvauyyh.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigufen.top/Article/details/gtjozshgnf.html

PHP:  ord("A"); chr(65)
来源：http://dali.zycfv.cn/Article/details/gtgkcofvtp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtpomgfwsq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttytfhwgc.html

Java: (int) 'A'; (char) 65
来源：http://dali.yonumen.top/Article/details/gtskcwbeyi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jqgfzy.top/Article/details/gtvfehrtqj.html

Ruby: "A".ord; 65.chr
来源：http://dali.haohaochexian.top/Article/details/gtffkoxfai.html

C#:   (int)'A'; (char)65
来源：http://dali.yvedp.cn/Article/details/gtniapnrzd.html

[A19] 交换两个变量
来源：http://dali.mhx1999.top/Article/details/gtgozjvhkt.html

Py:   a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gtnyfekekr.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sxryk.cn/Article/details/gtwaghnzjm.html

JS:   [a, b] = [b, a];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvafrrkx.html

TS:   [a, b] = [b, a];
来源：http://dali.yanxiufei.cn/Article/details/gteshyhugt.html

Java: int t = a; a = b; b = t;
来源：http://dali.jinqigfzy.top/Article/details/gtaieylahv.html

Go:   a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gtfuuyfqwy.html

Ruby: a, b = b, a
来源：http://dali.0kj1m.cn/Article/details/gtzpkrhzzd.html

C#:   (a, b) = (b, a);
来源：http://dali.0kj1m.cn/Article/details/gtiicyqkby.html

[A20] 读取标准输入
来源：http://dali.zycfv.cn/Article/details/gtgoghmsmo.html

Py:   name = input("请输入：")
来源：http://dali.hnqzz.top/Article/details/gtxhhmqqye.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cucudq.cn/Article/details/gtzvynfjcx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yuxming.cn/Article/details/gtoonpmyou.html

TS:   // Node.js：readline 模块
来源：http://dali.redwolf501.top/Article/details/gtbynggajl.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ybcxt.top/Article/details/gtvitdsryw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.havefunace.top/Article/details/gtzznzouqs.html

Ruby: gets.chomp
来源：http://dali.smart0.xyz/Article/details/gtefeutyii.html

C#:   Console.ReadLine();
来源：http://dali.pycfn.com/Article/details/gtuefrdwia.html

[A21] 保留指定小数位输出
来源：http://dali.nwbrower.top/Article/details/gtcaztfyir.html

Py:   f"{3.14159:.2f}"
来源：http://dali.snrcjt.cn/Article/details/gtaeeookhs.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gtxvxwadmk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtstqhcayx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtfrtpyero.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gtfcnrgzhs.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtkuaumybv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtonwaijuz.html

C#:   3.14159.ToString("F2")
来源：http://dali.xylfe.cn/Article/details/gtzlfqnsth.html

[A22] 获取字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtrisbrtmy.html

Py:   len(s)
来源：http://dali.jinqigufen.top/Article/details/gtlalybzab.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sufxvd.cn/Article/details/gtahbafcqu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.svipenyu.cn/Article/details/gtzmkjtsav.html

TS:   s.length
来源：http://dali.quarkkingdee.top/Article/details/gtrhwsuisf.html

Java: s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtuokuemau.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yongpay.top/Article/details/gttmmutzha.html

Ruby: s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtndquwfde.html

C#:   s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtewjoimoq.html

[A23] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtwxstezgz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cucudq.cn/Article/details/gtgjgidwzc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gotoacloud.top/Article/details/gtmehsqemo.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gttcsavqam.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gtcwdldcgp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtkcofabmo.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cdnleiting.top/Article/details/gthwuqwmvg.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtrloijdku.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.guannengcc.top/Article/details/gtixnyrkfo.html

[A24] 去除首尾空白
来源：http://dali.c1oappe.top/Article/details/gtfhzxijqc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.guowangkeji.top/Article/details/gtxhiodref.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.smart0.xyz/Article/details/gtqjsruvds.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj202588.top/Article/details/gtgbspekeg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gtxuixmmsm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sysykeji.top/Article/details/gtmzsgiyoe.html

Go:   strings.TrimSpace(s)
来源：http://dali.gzhubu.top/Article/details/gtlfgjbhfd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.smart0.xyz/Article/details/gtdrerbdru.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gotoacloud.top/Article/details/gtfxpurdgq.html

[A25] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gteivfgemr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhongyouzk.top/Article/details/gtmzxsrlpu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.vqdsnc.cn/Article/details/gtiwmsshls.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnqzz.top/Article/details/gtcwcywmaw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgufenzy.top/Article/details/gtjwnqtwlx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.birdmap.top/Article/details/gtdwaymejc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqtggjwm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ybcxt.top/Article/details/gtlkbftkqs.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenlongwang.top/Article/details/gtrluhutji.html

[A26] 类型转换总览
来源：http://dali.dianchejie.cn/Article/details/gtaitwwqfn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.haohaochexian.top/Article/details/gtfsleamhu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ydzc1.top/Article/details/gtuujrmdpm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.9152youxi.cn/Article/details/gtjmgzjbcm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zdqjudy.top/Article/details/gtoqthgcqb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.guowangkeji.top/Article/details/gtqkkzfcdh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.0kj1m.cn/Article/details/gtezqleueo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnmuhroq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gtlwoffslj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrtnmjoix.html

B. 流程控制
来源：http://dali.wangdashe.top/Article/details/gtwtjecfdn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkclmurv.html

[B01] 条件判断 if / else
来源：http://dali.dianchejie.cn/Article/details/gtfttxmnbv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tianlin.xyz/Article/details/gtneobnjpg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.daria6918.cn/Article/details/gtqsltvrlp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtmrwpajxz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtzfphaydi.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gtcqhxhwys.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guowangkeji.top/Article/details/gtwycsiduj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.meibo888.top/Article/details/gtgbhxbinp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtgyjgiabj.html

[B02] 多分支 else if / elif
来源：http://dali.quarkkingdee.top/Article/details/gtmipbqfui.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fengsongda.top/Article/details/gtvcgmwyum.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.iojbl.cn/Article/details/gtjhqvfxjv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtnfdhmyed.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtfqkmzptp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtndxenoiu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hammf.cn/Article/details/gteikbvhuc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258888.top/Article/details/gtjsluhivm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtlpqyehrv.html

[B03] switch / match / case
来源：http://dali.ehwqpu.com/Article/details/gtuhhhsnzx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gtzqhwgwtp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtpondrclk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gttlwpgnpx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtmedzqwaa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gttaqhhilp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gtavgasqrl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hysaishi.cn/Article/details/gtmhflgsls.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtfmszejwl.html

[B04] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtzxzznkgo.html

Py:   for i in range(10): print(i)
来源：http://dali.xylfe.cn/Article/details/gtlkngwzhr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdssfcrqr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gtaflabamc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.mhx1999.top/Article/details/gteujvlsii.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuanzhike.top/Article/details/gtlnzccdvm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ivvv.top/Article/details/gtcppqhbye.html

Ruby: 10.times { |i| puts i }
来源：http://dali.haohaochexian.top/Article/details/gtcmepoyva.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cqqwz.cn/Article/details/gtvvgoerui.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtmzhmcuvt.html

Py:   for item in arr: print(item)
来源：http://dali.tianlin.xyz/Article/details/gtpdhfvfhw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gaohongyu789.top/Article/details/gtmjfgzhrv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gtrzdbcfhm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtlytjnrxf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jiagoushi.top/Article/details/gtaxshnsbl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daria6918.cn/Article/details/gtzzyhmgdt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gtlfliczia.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtntkjjqhp.html

[B06] 遍历字典 / 对象
来源：http://dali.gzhubu.top/Article/details/gtpkgugwmy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yongpay.top/Article/details/gtieylhxtk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jianghu66.top/Article/details/gtjfvvmlhs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gtfpfiluqu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrxqwhbvd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hnqzz.top/Article/details/gtoxulfkok.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhengqikj.top/Article/details/gtjumuegfo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.iojbl.cn/Article/details/gtxsnwknyg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jlsjyb.cn/Article/details/gthjbytinv.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gtsdycojpn.html

Py:   while i < 10: i += 1
来源：http://dali.yueranfly.top/Article/details/gtmnflhset.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cqqwz.cn/Article/details/gtfmosrymn.html

JS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gterghmunu.html

TS:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtdgxtfchg.html

Java: while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtziekfkdc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.svipenyu.cn/Article/details/gtmftbsvbn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtdspabhxi.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtfystskhl.html

[B08] do-while（至少执行一次）
来源：http://dali.ybcxt.top/Article/details/gtkprgbggi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.havefunace.top/Article/details/gtmdtqvxdk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tanke756.top/Article/details/gtwnuipmkj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtsrtooxvr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtxhkjflnn.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtpbypyqdm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jianghu66.top/Article/details/gtqqycnwcr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cucudq.cn/Article/details/gtbezvakle.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtgojeofwo.html

[B09] break 与 continue
来源：http://dali.zhixingplan.top/Article/details/gttdhuozcq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hysaishi.cn/Article/details/gtjvyoidse.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtoayfoito.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduqliqxx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtwmrqpjwk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtrzphqytr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fengsongda.top/Article/details/gtoiqgzveh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyxfutjd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtjqimgjog.html

[B10] 遍历同时拿索引
来源：http://dali.jianghu66.top/Article/details/gtlaranojo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangtech.top/Article/details/gtleaujupq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258.top/Article/details/gtlpjhjcsj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtmbeqrwdx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.9152youxi.cn/Article/details/gtnwyjvbzp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cqqwz.cn/Article/details/gthgdrrjmd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gtdzyvcgrj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gtijwhogmh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hfpthk.cn/Article/details/gteoojtblm.html

[B11] 生成数字序列 / 区间
来源：http://dali.ybcxt.top/Article/details/gtqtaijowy.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuetiantiany.cn/Article/details/gtgrfzqcza.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtpwjddqxm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtzrbaodkl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtykbujhtg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.meibo888.top/Article/details/gtajrbmwyx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xinyue.icu/Article/details/gtqiygkgqe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gotoacloud.top/Article/details/gtyfeipypo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnqzz.top/Article/details/gtbrehxlrb.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gtxnftkqnj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gtybegavum.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gaohongyu789.top/Article/details/gtkxmydwdk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtjuajqnjy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtxrzchakq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtgvvpxuhx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangdashe.top/Article/details/gtztsrrrlq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinqigfzy.top/Article/details/gtqomfqqnk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gotoacloud.top/Article/details/gtkqcyhflk.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gtqleqclck.html

Py:   isinstance(x, (int, float))
来源：http://dali.0kj1m.cn/Article/details/gtsscrpzje.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gtbujdjzdk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedsmajyl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gtlcnfgxal.html

Java: x instanceof Number
来源：http://dali.havefunace.top/Article/details/gtvuvjqois.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pengpengdd.cyou/Article/details/gtwaclfizq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yonumen.top/Article/details/gtxjgozfho.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gtvsgwyztt.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfocrmwv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gtwahzefua.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gtxnfwtncy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtvkxvlqme.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtxfnelfih.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cucudq.cn/Article/details/gtpeedaeyd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cdnleiting.top/Article/details/gtpoccgxpl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtyygxzetq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gthbhdtudr.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gtzplnmzaa.html

Py:   a and b or not c
来源：http://dali.yj20258888.top/Article/details/gtatsmfnku.html

PHP:  $a && $b || !$c
来源：http://dali.havefunace.top/Article/details/gtwmfrqgan.html

JS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtdwaybjrf.html

TS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtqhusxxrj.html

Java: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtckyixwee.html

Go:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtjiyszlsd.html

Ruby: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtdpgfjovu.html

C#:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtyqogacui.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtxdxdbqmi.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gtmzfqdelu.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gtpcayapmr.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtvzypazwx.html

TS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtjkkophfz.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtihduuanp.html

Go:   if data == nil { return }
来源：http://dali.cashguo.top/Article/details/gtbxztulst.html

Ruby: return if data.nil?
来源：http://dali.guowangkeji.top/Article/details/gtocpnrksp.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtwyudnqgk.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqrgmwnqi.html

C. 函数与作用域
来源：http://dali.zhongyouzk.top/Article/details/gtpqqsgzca.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfzabacfq.html

[C01] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtcoexvxzs.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gttwkcbjrb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtdltrrkeo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlloufqgh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtznsiaqmv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtnmdlfpyc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gtlemozoog.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gtaiymydim.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtldqflqot.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtxwiygirx.html

Py:   def greet(name="World"): return name
来源：http://dali.feifeiyinyue.top/Article/details/gtrdryhhxo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenzaomai.com/Article/details/gtinoxrlvc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtobbjcvkh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtdygdpubr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.feifeiyinyue.top/Article/details/gtnznqvjxl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guannengcc.top/Article/details/gtswyauars.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gtqrnutovo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtkcdkrbjx.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gtopxapsxj.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtwvhjch.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlsrlngk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gtmywrrtzu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtatacqdkl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gogol.net.cn/Article/details/gtqaxcozhc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gtihtplkqk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtuaaobzty.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gtwklgadyz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gtbvcwarqd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xziqi.cn/Article/details/gtfvplrioo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gtfymwkdmr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcmioqyvz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtcjvnqirv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigufen.top/Article/details/gtjpbbbnou.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gtnbjfdsra.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtfqqkrrhd.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gttapprimm.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gtvjnfyxsc.html

Py:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtitabgqhw.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gteivixejo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gtygsqvxbx.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gttedcupcq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cheryme.top/Article/details/gtxanwvfmx.html

Go:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtrjywoqnk.html

Ruby: return a, b
来源：http://dali.havefunace.top/Article/details/gtugyvirjc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gtnijxpkln.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gtiiidtwdd.html

Py:   square = lambda x: x * x
来源：http://dali.hammf.cn/Article/details/gtboxcnqxf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gtjwewujtq.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtzjxutlnx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtkcyhyfcu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gtsqddlnxw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtpigowxiw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtqitfwkmo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtnnkydbgf.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gthqjsqzzu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258888.top/Article/details/gtzkgrczhi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gtkhhvxifk.html


<!-- 参考信息 -->