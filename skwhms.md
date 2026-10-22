代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.xziqi.cn/Article/details/gtskcghmwn.html

Py:   ord("A"); chr(65)
来源：http://dali.hnxiangtu.top/Article/details/gtklcjfjoo.html

PHP:  ord("A"); chr(65)
来源：http://dali.zycfv.cn/Article/details/gtmgnnwjyi.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xziqi.cn/Article/details/gtrinmhnij.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhoulong.xyz/Article/details/gtgnxiuizl.html

Java: (int) 'A'; (char) 65
来源：http://dali.xylfe.cn/Article/details/gtpbqulnhl.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbyjmiou.html

Ruby: "A".ord; 65.chr
来源：http://dali.daxiang520.top/Article/details/gtzaxmsptk.html

C#:   (int)'A'; (char)65
来源：http://dali.yueranfly.top/Article/details/gteuavzfzp.html

[A19] 交换两个变量
来源：http://dali.smart0.xyz/Article/details/gtbuguxawc.html

Py:   a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gtlmzpksin.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guowangkeji.top/Article/details/gtesiwqcrt.html

JS:   [a, b] = [b, a];
来源：http://dali.svipenyu.cn/Article/details/gtghsblnle.html

TS:   [a, b] = [b, a];
来源：http://dali.yj202588.top/Article/details/gtennwfmog.html

Java: int t = a; a = b; b = t;
来源：http://dali.fzhhl.top/Article/details/gtdvtxvbbg.html

Go:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtwspiarpr.html

Ruby: a, b = b, a
来源：http://dali.sweek.top/Article/details/gtmylotpsq.html

C#:   (a, b) = (b, a);
来源：http://dali.jinqigfzy.top/Article/details/gtasxyhtoh.html

[A20] 读取标准输入
来源：http://dali.zhongyouzk.top/Article/details/gttqicjqls.html

Py:   name = input("请输入：")
来源：http://dali.jqgufenzy.top/Article/details/gtzpzejwsk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.nanxinkj.top/Article/details/gtnipppqlx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xuetiantiany.cn/Article/details/gtdkpramqf.html

TS:   // Node.js：readline 模块
来源：http://dali.tianlin.xyz/Article/details/gthjvusuil.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.snrcjt.cn/Article/details/gtnwcjlszr.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.0kj1m.cn/Article/details/gtcqlhtseo.html

Ruby: gets.chomp
来源：http://dali.shzxlz.cn/Article/details/gtzvgcjdxm.html

C#:   Console.ReadLine();
来源：http://dali.shangyingyoupin.top/Article/details/gtwzhesjdp.html

[A21] 保留指定小数位输出
来源：http://dali.feifeiyinyue.top/Article/details/gtrybadttu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zdqjudy.top/Article/details/gthfnxluhi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbaicfhgk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gtieyxentk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtgecbzcrr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtvelnhfyc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gtadaapktk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtfjnbkzek.html

C#:   3.14159.ToString("F2")
来源：http://dali.hnxiangtu.top/Article/details/gtwozbprsk.html

[A22] 获取字符串长度
来源：http://dali.yj20258.top/Article/details/gtgkqlxrzn.html

Py:   len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfredflac.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yueranfly.top/Article/details/gtgrswehqu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.bjfxy.top/Article/details/gtbwegkipv.html

TS:   s.length
来源：http://dali.ivvv.top/Article/details/gtrhesvyyf.html

Java: s.length()
来源：http://dali.xziqi.cn/Article/details/gtwvqdooza.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sysykeji.top/Article/details/gtlwinksus.html

Ruby: s.length
来源：http://dali.jqgufenzy.top/Article/details/gtbhgjruuk.html

C#:   s.Length
来源：http://dali.fengsongda.top/Article/details/gtromvkflq.html

[A23] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtnsvhjjoa.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sysykeji.top/Article/details/gtfjfhltau.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.andypj.xyz/Article/details/gtnvgauxqw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtgcezzubm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gtqfbnhdnd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gtaolnesnk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sufxvd.cn/Article/details/gtwxkscgys.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jianghu66.top/Article/details/gtgizpxkcr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yuxming.cn/Article/details/gtrpsnyfpt.html

[A24] 去除首尾空白
来源：http://dali.gotoacloud.top/Article/details/gtyfyzbxtw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xziqi.cn/Article/details/gtrqbddeac.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yuxming.cn/Article/details/gtbvlborsg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sxryk.cn/Article/details/gtafzdolvh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfslibfj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhongyouzk.top/Article/details/gtaswsalcz.html

Go:   strings.TrimSpace(s)
来源：http://dali.sweek.top/Article/details/gtzsdahtex.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xuanzx.com/Article/details/gtgjwpxdsg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.nanxinkj.top/Article/details/gtgccsgdst.html

[A25] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtltjnfqqi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yj202588.top/Article/details/gtxwsotudb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jqgufenzy.top/Article/details/gtjwvosqda.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenlongwang.top/Article/details/gtwvendryz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gtlviyjtsm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj202588.top/Article/details/gtexxzmehv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.daria6918.cn/Article/details/gtzuxvchqu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yvedp.cn/Article/details/gtprkuaute.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cqqwz.cn/Article/details/gtqxjtdfxv.html

[A26] 类型转换总览
来源：http://dali.feifeiyinyue.top/Article/details/gthueqgioe.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhongyouzk.top/Article/details/gtvrlupxaj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.birdmap.top/Article/details/gtzknqwjur.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ivvv.top/Article/details/gtbgauobcq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqeofjoh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gtlphydfwr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hywenlv.cn/Article/details/gtwjjwqjza.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hfpthk.cn/Article/details/gtwcxxrqit.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gtcluzteaq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoflaosp.html

B. 流程控制
来源：http://dali.hysaishi.cn/Article/details/gtewjmffki.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttitqudxw.html

[B01] 条件判断 if / else
来源：http://dali.feifeiyinyue.top/Article/details/gtacwnfnxi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenlongwang.top/Article/details/gtcmukwrxn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.c1oappe.top/Article/details/gtvclrvplj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtaprgkign.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtwksadrgo.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtvhyasdza.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinqigufen.top/Article/details/gteirpcbbg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtwkovivkd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtovqjmiol.html

[B02] 多分支 else if / elif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowndlgpn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tian-w.cn/Article/details/gtkbsaxmkc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj202588.top/Article/details/gtoxtzfxak.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gtqnufelsh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gticrunzey.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtnkwcjtil.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.fzhhl.top/Article/details/gthiopywxh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmkjyqpp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtpjancstd.html

[B03] switch / match / case
来源：http://dali.hysaishi.cn/Article/details/gtuxmfmpjf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangshuangyany.cn/Article/details/gtfwoinyjw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtwdgoaawx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gtmkvzhnmg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gttvijhbzr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gtxxeeopyb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuxming.cn/Article/details/gtooqjawjd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shzxlz.cn/Article/details/gtalrpnkcp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cqqwz.cn/Article/details/gtcwuisuol.html

[B04] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtimoesxqq.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtthavyafz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sweek.top/Article/details/gtwuhaligc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtkzunsgtj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgfzy.top/Article/details/gtjtluoskc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fengsongda.top/Article/details/gtqpxonvqt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pengpengdd.cyou/Article/details/gtczmaibyw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigufen.top/Article/details/gtgxmlyllx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.0kj1m.cn/Article/details/gtxvqkkpqq.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gturbhpchl.html

Py:   for item in arr: print(item)
来源：http://dali.sysykeji.top/Article/details/gthdbognal.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgufenzy.top/Article/details/gtyyjcpwwi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gtqgjyqilv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gtftedoxbc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnxiangtu.top/Article/details/gtlltztfee.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cucudq.cn/Article/details/gtnijwwcuo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ppjwa.cn/Article/details/gtjdcbhdrn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhixingplan.top/Article/details/gtyvcahbnq.html

[B06] 遍历字典 / 对象
来源：http://dali.nanxuanxn.top/Article/details/gtokamsjqw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxuanxn.top/Article/details/gtvlcedtsu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yuxming.cn/Article/details/gtxiiwfcme.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ybcxt.top/Article/details/gtikkjkaff.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gtdutfiqxg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yonumen.top/Article/details/gtibpgozyg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.pengpengdd.cyou/Article/details/gtfywuezlv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnqzz.top/Article/details/gtbbvtwgua.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gtugncbmsh.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gtlpivuidv.html

Py:   while i < 10: i += 1
来源：http://dali.mhx1999.top/Article/details/gtzhadhoiw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xinyue.icu/Article/details/gtsvdrwqeo.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gthumpzxhy.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtqsimpctm.html

Java: while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gthgdhsugn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenzaomai.com/Article/details/gtwbrhntzt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258.top/Article/details/gtyhtunuph.html

C#:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtptkzclyo.html

[B08] do-while（至少执行一次）
来源：http://dali.zhongyouzk.top/Article/details/gteegrnjbo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuanzhike.top/Article/details/gtaoehafrg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtiwbznufl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gttxhzxogp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtseyqzzda.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtpsigbsjw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhixingplan.top/Article/details/gtpfydnwca.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sweek.top/Article/details/gtixwdevqq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfvkpkuj.html

[B09] break 与 continue
来源：http://dali.jinghuilouyu.cn/Article/details/gtlthtlgsh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.0kj1m.cn/Article/details/gtdmfcgozt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtonktfbjh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtequifqlt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtheiyfmtv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtlgrpyckr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gtvpehzfxs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sysykeji.top/Article/details/gtnzmjatxa.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtueuyohwz.html

[B10] 遍历同时拿索引
来源：http://dali.wangdashe.top/Article/details/gtywyeejpa.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaueammre.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gtpkbhhetg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gtwlflgnvl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtuwlktkko.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gtohppnhbr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhiwuduotai.top/Article/details/gtwfbekwcq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ehwqpu.com/Article/details/gtmciywwnt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj202588.top/Article/details/gtrfqdlxyr.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gtldpgitkz.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangshuangyany.cn/Article/details/gtxtcfjsns.html

PHP:  range(0, 10, 2);
来源：http://dali.shuidangran.top/Article/details/gtfozresmi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gtfgvgoagr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gtdhugwboi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daria6918.cn/Article/details/gtejizlpyu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gotoacloud.top/Article/details/gtshdbgcgs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gtlbaggeyo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gtqbcpyrlz.html

[B12] 跳出多层循环
来源：http://dali.tian-w.cn/Article/details/gtieweftqx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fengsongda.top/Article/details/gtqirdbvjt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gtgohwgwyu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtaqfymcyv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtgdglcqzw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtvlzqeszc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.feifeiyinyue.top/Article/details/gtbaaifmyu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yonumen.top/Article/details/gtppmjwvhh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctvtpdvg.html

[B13] 判断是否为数字
来源：http://dali.wangdashe.top/Article/details/gtoebmrejx.html

Py:   isinstance(x, (int, float))
来源：http://dali.shuidangran.top/Article/details/gtqtygbabp.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gtndhtklly.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gttvvjewoq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gtjxodurio.html

Java: x instanceof Number
来源：http://dali.tian-w.cn/Article/details/gtqltbfqfv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgufenzy.top/Article/details/gtfgmfvwao.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xziqi.cn/Article/details/gtaxyfbizb.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gtfzzskbwq.html

[B14] 判断值是否在集合内
来源：http://dali.ehwqpu.com/Article/details/gtsbyqmodb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daria6918.cn/Article/details/gtoddwoqxg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jyoumei.cn/Article/details/gtnfnyymka.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtfueaugef.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtzjvdiwut.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtaiyjfmkw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.meibo888.top/Article/details/gtzmeoeswi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gtxkfkpbop.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtyzclawvh.html

[B15] 布尔运算与取反
来源：http://dali.fzhhl.top/Article/details/gtkdumnqjr.html

Py:   a and b or not c
来源：http://dali.cdnleiting.top/Article/details/gtjepmafdw.html

PHP:  $a && $b || !$c
来源：http://dali.sweek.top/Article/details/gtdehebnwz.html

JS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtfuzpetjo.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirpdyqtk.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gttchymwew.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtbbenpekh.html

Ruby: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtnxgjlrdk.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtcximjkmj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.mhx1999.top/Article/details/gthyvyirpb.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnznpmrt.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gtfxkwwcaq.html

JS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtdwxbnrzg.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtpygafpsn.html

Java: if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtbsdzfehq.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gtkfhbayyt.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gtioudbqei.html

C#:   if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtokdmqqkh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkeuqlocm.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gtubbvvyrm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtymnanvnd.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtxqyedzag.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gtghadyavb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgepmxqci.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtumkarzzb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlblghiqv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtsfkcweuu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtpbxdvyac.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gtzmsqrxss.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtlayszlvo.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gtuofcqrko.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gtowtawion.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtasxqwiks.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtxhvuiury.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuxmhnjed.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gtesmgfaqr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xinyue.icu/Article/details/gtskywiisn.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gtwwwujoqf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gtwgviwcea.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gtpgwnoxkw.html

Py:   def total(*args): return sum(args)
来源：http://dali.cdnleiting.top/Article/details/gtalydsocs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsiaffwfm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gttlindqsk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gtgmolicli.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gthixatpfm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnxiangtu.top/Article/details/gtarmwautu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtfmczurlw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtdzigolnk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.svipenyu.cn/Article/details/gtptfzliye.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.svipenyu.cn/Article/details/gtisurofva.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guowangkeji.top/Article/details/gtkiysyxic.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwkpiqtyn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gtdsiswivu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258.top/Article/details/gtvoeoxobp.html

Go:   // 无：用配置结构体参数
来源：http://dali.zycfv.cn/Article/details/gtlvsxvqzv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gttgywgcum.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetnofuzc.html

[C05] 返回多个值
来源：http://dali.smart0.xyz/Article/details/gtjbxqamuk.html

Py:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtjwukmaqz.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gtuolandul.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtnqrewuqy.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtwzpkqjbj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hysaishi.cn/Article/details/gtkhwdbedz.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtuwgxxdhq.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtjzojjwmq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gtxqzineff.html

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gtkwcxktir.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gtbxmcftom.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gtdgcyegyc.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtxvrrpmow.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtgembmhwy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gtyqqhmmhe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nwbrower.top/Article/details/gtikteuluz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenzaomai.com/Article/details/gthuivrfcv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtfusveeal.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gtggjounvt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cucudq.cn/Article/details/gtmfippkmj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gtskunniae.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gtjijlokjb.html

TS:   arr.map(String)
来源：http://dali.zhiwuduotai.top/Article/details/gtuylfroko.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jiagoushi.top/Article/details/gtxsuajozy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgfzy.top/Article/details/gtyivplawb.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhixingplan.top/Article/details/gtppwwnngb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxuanxn.top/Article/details/gtzsuzdslx.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtdlvypizj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtpxgkgrpf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.iojbl.cn/Article/details/gtsuqjbqbm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtunpxhtzp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtjxmussib.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gtddenyxuf.html


<!-- 参考信息 -->