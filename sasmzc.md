代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.jyoumei.cn/Article/details/gthgqsrvgo.html

Py:   ord("A"); chr(65)
来源：http://dali.0kj1m.cn/Article/details/gtfzgmqqzd.html

PHP:  ord("A"); chr(65)
来源：http://dali.zycfv.cn/Article/details/gtxibnksdy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.bjfxy.top/Article/details/gtlpfvspeq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yonumen.top/Article/details/gtdhtuwyup.html

Java: (int) 'A'; (char) 65
来源：http://dali.daria6918.cn/Article/details/gtcqfcusfs.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.feifeiyinyue.top/Article/details/gtpwehtbri.html

Ruby: "A".ord; 65.chr
来源：http://dali.fengsongda.top/Article/details/gtsnulkmiy.html

C#:   (int)'A'; (char)65
来源：http://dali.yonumen.top/Article/details/gtwpukapjq.html

[A19] 交换两个变量
来源：http://dali.daxiang520.top/Article/details/gtufoxaobl.html

Py:   a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvwlypea.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zycfv.cn/Article/details/gtddxeolns.html

JS:   [a, b] = [b, a];
来源：http://dali.jqgufenzy.top/Article/details/gtvsuppzpq.html

TS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzujbzzqi.html

Java: int t = a; a = b; b = t;
来源：http://dali.fzhhl.top/Article/details/gtdbcnujmz.html

Go:   a, b = b, a
来源：http://dali.iojbl.cn/Article/details/gthsfkibps.html

Ruby: a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gtcwsarjsl.html

C#:   (a, b) = (b, a);
来源：http://dali.kuanghao11.cn/Article/details/gtskltpfpf.html

[A20] 读取标准输入
来源：http://dali.ydzc1.top/Article/details/gtnazmohwx.html

Py:   name = input("请输入：")
来源：http://dali.bjfxy.top/Article/details/gtnvjeyfsd.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdygogaq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.dianchejie.cn/Article/details/gtncjxycus.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxinkj.top/Article/details/gthmabbggo.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hnxiangtu.top/Article/details/gtdwrsurqp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxqrlqmr.html

Ruby: gets.chomp
来源：http://dali.ydzc1.top/Article/details/gtgcgvkelv.html

C#:   Console.ReadLine();
来源：http://dali.jqgfzy.top/Article/details/gtauiclutj.html

[A21] 保留指定小数位输出
来源：http://dali.hongshengwenyu.top/Article/details/gtkkrencon.html

Py:   f"{3.14159:.2f}"
来源：http://dali.feifeiyinyue.top/Article/details/gtzyjsphsr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzgahrxh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtvgpkizen.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtznoxgloo.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtaklcmbcb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gtpqlphvyq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gtrkuhvrzl.html

C#:   3.14159.ToString("F2")
来源：http://dali.316326.xyz/Article/details/gtydxjpbuh.html

[A22] 获取字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtsvgpnzok.html

Py:   len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtrxdjuupb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cheryme.top/Article/details/gtdretonzd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.feifeiyinyue.top/Article/details/gtoeghdvbf.html

TS:   s.length
来源：http://dali.birdmap.top/Article/details/gtdmosrizc.html

Java: s.length()
来源：http://dali.yj202588.top/Article/details/gthlzecrxw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.daxiang520.top/Article/details/gtjokgaoyk.html

Ruby: s.length
来源：http://dali.zhixingplan.top/Article/details/gttezgpgbf.html

C#:   s.Length
来源：http://dali.birdmap.top/Article/details/gthvaxxiam.html

[A23] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gticcpbdli.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.0kj1m.cn/Article/details/gtztkrxfbl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cqqwz.cn/Article/details/gtsqufwxjr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gtaenxerrb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gtvasfviwk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gtvbbbnchx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jianghu66.top/Article/details/gtnidnrigl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtujvhychm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.aizwys.cn/Article/details/gtnhafqpja.html

[A24] 去除首尾空白
来源：http://dali.yj202588.top/Article/details/gtoapybzax.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dashuyun.cn/Article/details/gtjdpgrdro.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xziqi.cn/Article/details/gtjyhefynn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xinyue.icu/Article/details/gtzvsrabxa.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gtszowiuwy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yuxming.cn/Article/details/gtljimcqxe.html

Go:   strings.TrimSpace(s)
来源：http://dali.cqqwz.cn/Article/details/gttxcwckrd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hnqzz.top/Article/details/gthxmfdbtz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cashguo.top/Article/details/gtfluultun.html

[A25] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdtdjipx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sxryk.cn/Article/details/gtfwpegklx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tianlin.xyz/Article/details/gtuohynjab.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gtxacscaml.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gttjgxybik.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jianghu66.top/Article/details/gtrbrukdep.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yangfankeji.com/Article/details/gtvofpefoh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xylfe.cn/Article/details/gtywfsdcnu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtszvkfygg.html

[A26] 类型转换总览
来源：http://dali.yanxiufei.cn/Article/details/gtaflbalrm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.316326.xyz/Article/details/gthqvzemgw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zycfv.cn/Article/details/gtknxigthy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dashuyun.cn/Article/details/gtvukspokw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yanxiufei.cn/Article/details/gtjshgnecr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtylxwidgj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfxcjvez.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ybcxt.top/Article/details/gtxzdpnuni.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gtlhdqvcuo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbdpzbwjc.html

B. 流程控制
来源：http://dali.hammf.cn/Article/details/gtnncyprqh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthpjukjvk.html

[B01] 条件判断 if / else
来源：http://dali.c1oappe.top/Article/details/gtnotsxenp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fengsongda.top/Article/details/gtdrewmoeg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dashuyun.cn/Article/details/gtksknakik.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtipjlcmeg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtkypunkfp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gtgypljmrq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jyoumei.cn/Article/details/gtuqpejkcu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cashguo.top/Article/details/gtvqjeoixe.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtkevfokbz.html

[B02] 多分支 else if / elif
来源：http://dali.guowangkeji.top/Article/details/gtvvomqaqy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hywenlv.cn/Article/details/gtzvzngvdq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ehwqpu.com/Article/details/gtgmseakvn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtxiwaynoq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtrlclpkkz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gttazyxaqe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jqgufenzy.top/Article/details/gtetflshhw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxuanxn.top/Article/details/gtzfrscxhj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtdgsxscra.html

[B03] switch / match / case
来源：http://dali.wangshuangyany.cn/Article/details/gtnabdtira.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gtjpwwtnmb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhposgst.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtlhnieems.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtaylifcqa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtumxykxqb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xylfe.cn/Article/details/gtofxgodxs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yvedp.cn/Article/details/gtbbaqaojl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.birdmap.top/Article/details/gtebwwkquf.html

[B04] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtepmtpjyd.html

Py:   for i in range(10): print(i)
来源：http://dali.yangfankeji.com/Article/details/gtedlfpzpx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sysykeji.top/Article/details/gtazyqnnlb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gthtobjkua.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gtkzhnclif.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtuvjtxmpr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hywenlv.cn/Article/details/gtewrcrxqp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.aibaodan.cn/Article/details/gttzqggjfq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hysaishi.cn/Article/details/gtjdctutlc.html

[B05] 遍历数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtomylgkqw.html

Py:   for item in arr: print(item)
来源：http://dali.xuanzx.com/Article/details/gtwerkhpep.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gtrjpxrozn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxinkj.top/Article/details/gtdxotnigz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtvbdionol.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtszqjethf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfybhggst.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigfzy.top/Article/details/gtpbcrumij.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtoosoamyh.html

[B06] 遍历字典 / 对象
来源：http://dali.meibo888.top/Article/details/gtciqzwzil.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hysaishi.cn/Article/details/gtxyytoqqp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.c1oappe.top/Article/details/gtkvbrzijt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gtdzxvvgvu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gtgqewdehc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jlsjyb.cn/Article/details/gtmjwyivhx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jyoumei.cn/Article/details/gtqrezmsra.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shzxlz.cn/Article/details/gtaahzvyuo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.bjfxy.top/Article/details/gtfynndfwa.html

[B07] while 循环
来源：http://dali.andypj.xyz/Article/details/gtmwylicur.html

Py:   while i < 10: i += 1
来源：http://dali.hnqzz.top/Article/details/gthpsqmerb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj202588.top/Article/details/gtjrlyhdto.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtggjyavas.html

TS:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gtbrsugoyt.html

Java: while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtvacdvfvf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zycfv.cn/Article/details/gtvwiiezrt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jyoumei.cn/Article/details/gtgwhistys.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtedzkvgjv.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gtmcwrwiml.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jiagoushi.top/Article/details/gtcahoumbo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuanzx.com/Article/details/gtyhroszed.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gttfdzhhwr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtwvudmflv.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtetzwkubj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ehwqpu.com/Article/details/gtxzazjoyg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gttyrqexyj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtwemghiyt.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gtudvykxgs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.vqdsnc.cn/Article/details/gttpoasfpj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnhkhntmo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtxuippgmo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtsddltaxv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrejlwars.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hywenlv.cn/Article/details/gtjbgiurtq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.c1oappe.top/Article/details/gtchwogoto.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtomkmankj.html

[B10] 遍历同时拿索引
来源：http://dali.hfpthk.cn/Article/details/gtcmxlrude.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shangyingyoupin.top/Article/details/gtasnhipap.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvrbcwhu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gtbboocslw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtipxmqhsq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ybcxt.top/Article/details/gtbnzmfeuu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.svipenyu.cn/Article/details/gtunoldtpg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ppjwa.cn/Article/details/gtnujgjyrb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hfpthk.cn/Article/details/gtddyiqhvh.html

[B11] 生成数字序列 / 区间
来源：http://dali.ppjwa.cn/Article/details/gtpplbocmu.html

Py:   list(range(0, 10, 2))
来源：http://dali.svipenyu.cn/Article/details/gtdebtxcdt.html

PHP:  range(0, 10, 2);
来源：http://dali.chenzaomai.com/Article/details/gtccyysttw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gtlzmwrnxc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gtraxtivkd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtjpmtqvmf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gtnaibayqr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aizwys.cn/Article/details/gtolhvzikm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hammf.cn/Article/details/gtftjpkkxv.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaudfpkr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.meibo888.top/Article/details/gtldkjxxdt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbfmkrba.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtbfjvizvc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtvcmzaanx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gteblenexe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gtkypnojef.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnqzz.top/Article/details/gtspkibbfh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yongpay.top/Article/details/gtwemhsjjk.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gthhirdxfb.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gthvjmrimn.html

PHP:  is_numeric($x)
来源：http://dali.shangyingyoupin.top/Article/details/gtbvytggqb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtyjcwcakz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtkpjjdbek.html

Java: x instanceof Number
来源：http://dali.ydzc1.top/Article/details/gtjyhwfuyf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gtsnvqsdea.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cheryme.top/Article/details/gtrtpvvcfa.html

C#:   x is int or double or decimal
来源：http://dali.yj20258.top/Article/details/gtckxcwocd.html

[B14] 判断值是否在集合内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqxcybjt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnqzz.top/Article/details/gtlkempczh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhoulong.xyz/Article/details/gtxeshcnld.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gteysqlwnp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtzwsywnum.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtcgspnuch.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqvojent.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xylfe.cn/Article/details/gtooneitjf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcyybqpb.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgqhjdqj.html

Py:   a and b or not c
来源：http://dali.yanxiufei.cn/Article/details/gtqecryzyl.html

PHP:  $a && $b || !$c
来源：http://dali.svipenyu.cn/Article/details/gtovgbmvyx.html

JS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtzmlfnosr.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtnjpygxam.html

Java: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtpuaxrdzd.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtiqhcbgoh.html

Ruby: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gttlcmzcyj.html

C#:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtajtcjsab.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gteyoqcdah.html

Py:   if not data: return
来源：http://dali.meibo888.top/Article/details/gtakdpcdbm.html

PHP:  if (!$data) { return; }
来源：http://dali.gotoacloud.top/Article/details/gthlkcldnf.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gthqohaghg.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtfpzyewgh.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtycwjecis.html

Go:   if data == nil { return }
来源：http://dali.zhixingplan.top/Article/details/gtgqjdyrlz.html

Ruby: return if data.nil?
来源：http://dali.dashuyun.cn/Article/details/gtclhjdjtd.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtgmidscju.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtagcdvday.html

C. 函数与作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtsrikdqlf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtslpbjuam.html

[C01] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtbldsjkaj.html

Py:   def add(a, b): return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtkuuplqzy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtmrmfrarf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtaasrmtyk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtyxvdtqlg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtwndohsct.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fengsongda.top/Article/details/gtpuxrsmgv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtlsfbkdin.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtbiudakhh.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gtngqnhzbp.html

Py:   def greet(name="World"): return name
来源：http://dali.tian-w.cn/Article/details/gtlvqwrjbl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cqqwz.cn/Article/details/gtgnxumbye.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtnipiqpgq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtcihfcsql.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtmarellsa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gtajtgwadn.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gtqvyrsfhn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gtgkqbmamj.html

[C03] 可变参数
来源：http://dali.feifeiyinyue.top/Article/details/gtanjlzgiq.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gtoakqjqvj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xinyue.icu/Article/details/gtblyjqgkm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtmozugqur.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtoeekxapc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gtfdzoqsht.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtekauqelk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cashguo.top/Article/details/gtecoinuek.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ybcxt.top/Article/details/gtwmdundgi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gtdulwobry.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhengqikj.top/Article/details/gtxvyolgow.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gtbmrtcuof.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gtqzvxhfem.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gzhubu.top/Article/details/gteprtqiwv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnqzz.top/Article/details/gtnnhgxbkm.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gtmxpgikwg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtajemyiyl.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtfbbxiaxu.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gtzcneezmc.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtnazbymdk.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gtnfrifkwe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xinyue.icu/Article/details/gteodnqsae.html

TS:   return { a, b };
来源：http://dali.yueranfly.top/Article/details/gtuhdkmrog.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gtfqgcgbgf.html

Go:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtpeywbkfd.html

Ruby: return a, b
来源：http://dali.wangdashe.top/Article/details/gtghaiclwc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.0kj1m.cn/Article/details/gtddiqfjxd.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gtkvjpprrr.html

Py:   square = lambda x: x * x
来源：http://dali.cdnleiting.top/Article/details/gtieetlvuw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gtrvlnlcbf.html

JS:   const square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtqrsmvisl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtgoxnknjh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtrxpjmlyj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gtdgejxcmi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gttscsfldw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gthxwmblfw.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtbukqoyfg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtufpqftdr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtgrlipskd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gtvhtlkjtv.html

TS:   arr.map(String)
来源：http://dali.xinyue.icu/Article/details/gtonscuhmc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtioifdcih.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gtkppkjwdt.html

Ruby: arr.map(&:upcase)
来源：http://dali.gogol.net.cn/Article/details/gtpdoptrzj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtxxfifuwv.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gthmzmxdhz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gtqwwjgfnt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtlojkfliw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtidqtfplo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtfpxznqju.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gthqocbbmf.html


<!-- 参考信息 -->