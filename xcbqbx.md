代发 wailian999

JS:   [a, b] = [b, a];
来源：http://dali.hysaishi.cn/Article/details/gtnpzcquwl.html

TS:   [a, b] = [b, a];
来源：http://dali.feifeiyinyue.top/Article/details/gttmpycoiw.html

Java: int t = a; a = b; b = t;
来源：http://dali.hammf.cn/Article/details/gtnvyaqelj.html

Go:   a, b = b, a
来源：http://dali.meibo888.top/Article/details/gtwqvfyapu.html

Ruby: a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gttgmcxqhc.html

C#:   (a, b) = (b, a);
来源：http://dali.cucudq.cn/Article/details/gtqapxemoi.html

[A20] 读取标准输入
来源：http://dali.chenjidiqi.icu/Article/details/gtlcimddnm.html

Py:   name = input("请输入：")
来源：http://dali.yueranfly.top/Article/details/gtktpveeiw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.vqdsnc.cn/Article/details/gtyhwwulby.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yonumen.top/Article/details/gtiivzdoum.html

TS:   // Node.js：readline 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtupmchtib.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ppjwa.cn/Article/details/gtzcfovgmo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shangyingyoupin.top/Article/details/gtwmidhepy.html

Ruby: gets.chomp
来源：http://dali.pengpengdd.cyou/Article/details/gtopbwzego.html

C#:   Console.ReadLine();
来源：http://dali.nanxuanxn.top/Article/details/gtnbtzsskw.html

[A21] 保留指定小数位输出
来源：http://dali.yuanzhike.top/Article/details/gthwcphtrm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.havefunace.top/Article/details/gtloqboevq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gtshlhaqhb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtcuelqdqq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtlyqgyqru.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gtitfnwwks.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gttlpbmswk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gtmrnjkjlc.html

C#:   3.14159.ToString("F2")
来源：http://dali.gogol.net.cn/Article/details/gtqdpvuhjm.html

[A22] 获取字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtthebubge.html

Py:   len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtusrqgiwh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.dashuyun.cn/Article/details/gtllukweke.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shangyingyoupin.top/Article/details/gtvqtbyyck.html

TS:   s.length
来源：http://dali.aizwys.cn/Article/details/gtkczxsbch.html

Java: s.length()
来源：http://dali.zdqjudy.top/Article/details/gtxdomjgnl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guannengcc.top/Article/details/gtukfidqvs.html

Ruby: s.length
来源：http://dali.redwolf501.top/Article/details/gttuirdzrg.html

C#:   s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtmqxpzntj.html

[A23] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtxhywpntk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cheryme.top/Article/details/gthsqakypj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenzaomai.com/Article/details/gtupgficez.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gthubhzktk.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gtzfthnqcx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtzqgqbfmj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.quarkkingdee.top/Article/details/gtalcavdxl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xziqi.cn/Article/details/gttlwobqvm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hammf.cn/Article/details/gtitskqzim.html

[A24] 去除首尾空白
来源：http://dali.yuanzhike.top/Article/details/gtzhsniugk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.nwbrower.top/Article/details/gtsxjubkub.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xinyue.icu/Article/details/gtqyygfzmm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sweek.top/Article/details/gtxorvxuad.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyiukimjj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.smart0.xyz/Article/details/gtsfbwiqxx.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiuynywlr.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuxming.cn/Article/details/gtpzbszkuw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhengqikj.top/Article/details/gtrirziisx.html

[A25] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtczyczvbi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuofajpf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tanke756.top/Article/details/gtkflaholr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gtxgbqczip.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gtmyiidclz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmiwfilo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zdqjudy.top/Article/details/gteeyigrmp.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yangfankeji.com/Article/details/gtjpcxdahl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtutrflhtg.html

[A26] 类型转换总览
来源：http://dali.tianlin.xyz/Article/details/gtcsyzsume.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xinyue.icu/Article/details/gttwiormjk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.haohaochexian.top/Article/details/gtunjspcgb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.redwolf501.top/Article/details/gtrhtphztj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.kuanghao11.cn/Article/details/gtfjiaufxk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtbgmarmfr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.andypj.xyz/Article/details/gtsowgkveo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sysykeji.top/Article/details/gtvhpdelxs.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gtmdvnpenr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtuyorqcef.html

B. 流程控制
来源：http://dali.pengpengdd.cyou/Article/details/gtryilbizn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtadkzwfbn.html

[B01] 条件判断 if / else
来源：http://dali.cashguo.top/Article/details/gtmsrckumy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.c1oappe.top/Article/details/gtstyzlkhu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.0kj1m.cn/Article/details/gtwxpabvwu.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtstuvtzeg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtckzqjyya.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtqzfnlslj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tanke756.top/Article/details/gtvsokwmmv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yonumen.top/Article/details/gtxrymotpg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtkvtbynqj.html

[B02] 多分支 else if / elif
来源：http://dali.zycfv.cn/Article/details/gtnjmyuuqn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hammf.cn/Article/details/gtvlifhtzc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhongyouzk.top/Article/details/gtyoxpgabj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtktdfnqzk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gtsesbelay.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtinvadvqh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hongshengwenyu.top/Article/details/gtimeevyri.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.guowangkeji.top/Article/details/gtsnhmdsee.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtrqbckrza.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gttnzjbufi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cqqwz.cn/Article/details/gtlpyfatxn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtmqqwjmip.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvmenaxoc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gtubjwmuvt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvennojlz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gtpydqxowc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoendvyr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fengsongda.top/Article/details/gtobtatuqz.html

[B04] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtyxpyairb.html

Py:   for i in range(10): print(i)
来源：http://dali.hammf.cn/Article/details/gtrjfcpbul.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jlsjyb.cn/Article/details/gtnjnhiuub.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gttgnsabvt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxmwbukaj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzivsxsyw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.quarkkingdee.top/Article/details/gtqnemifji.html

Ruby: 10.times { |i| puts i }
来源：http://dali.redwolf501.top/Article/details/gtjgskzkhp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhengqikj.top/Article/details/gtalialutv.html

[B05] 遍历数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtfqmwtxgi.html

Py:   for item in arr: print(item)
来源：http://dali.kuanghao11.cn/Article/details/gtsrhcmhvq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.snrcjt.cn/Article/details/gtyayaqbmw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aibaodan.cn/Article/details/gtxhgmgcfc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sweek.top/Article/details/gtwxbtwgcp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ppjwa.cn/Article/details/gtlsqhpdnf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zdqjudy.top/Article/details/gtuugbhxok.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhoulong.xyz/Article/details/gtbceypxpq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shuidangran.top/Article/details/gtkqynapfr.html

[B06] 遍历字典 / 对象
来源：http://dali.yj202588.top/Article/details/gtwznhtxnk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigfzy.top/Article/details/gtavlvlkdx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jyoumei.cn/Article/details/gtwocsqktk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.haohaochexian.top/Article/details/gtfotyyhge.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtplrjcltk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nwbrower.top/Article/details/gtsggyccbr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sxryk.cn/Article/details/gtbgttigja.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouuhdubk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258888.top/Article/details/gtknwjluyk.html

[B07] while 循环
来源：http://dali.jinqigufen.top/Article/details/gtqtiixdbc.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtjvzwnovk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuanzx.com/Article/details/gthenivsap.html

JS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgcahkca.html

TS:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtwtfpwdco.html

Java: while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazqbzkaz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gtxnxzdjmd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shzxlz.cn/Article/details/gteisfoaeg.html

C#:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtnznzgsim.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gtjzrmplbl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangdashe.top/Article/details/gtnbkptqnh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtrvnywikg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzaktngv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtsrdxqkgu.html

Java: do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtzelciqts.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.c1oappe.top/Article/details/gtksnxdqmz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhixingplan.top/Article/details/gtibaikpku.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtyxpokwbp.html

[B09] break 与 continue
来源：http://dali.zdqjudy.top/Article/details/gtncectcbc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhixingplan.top/Article/details/gtqohghxet.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtjywqrpax.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkzbcxfp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtumxgixtr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddvrpabs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gtdyxcxbkc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.316326.xyz/Article/details/gtlxluzvjp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtcmwvgwdc.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gtblyadumq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ivvv.top/Article/details/gtmzkhdugd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cheryme.top/Article/details/gtucubhlzq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gttmufnrqw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gtlsfxikqa.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuanzx.com/Article/details/gtuqteftla.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gtnlvrqlsw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gtnkyeemav.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gtcmxkuxmd.html

[B11] 生成数字序列 / 区间
来源：http://dali.smart0.xyz/Article/details/gtavgoyqfy.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gtyhknbygr.html

PHP:  range(0, 10, 2);
来源：http://dali.xziqi.cn/Article/details/gtqjtoqwnn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtfqfjhlug.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gthvexvwfx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtadzpouzc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hfpthk.cn/Article/details/gtgbagplpf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhongyouzk.top/Article/details/gtivrxfoni.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtjsdllabe.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gtnuojqbcy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsymiwjey.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.0kj1m.cn/Article/details/gteczgvzyf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtaxnlosbf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtuhdlgyyo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gttsoveqkd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.mhx1999.top/Article/details/gtkvvcptho.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.iojbl.cn/Article/details/gtaazvmpvm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbnzovak.html

[B13] 判断是否为数字
来源：http://dali.yvedp.cn/Article/details/gtkfrfkasb.html

Py:   isinstance(x, (int, float))
来源：http://dali.andypj.xyz/Article/details/gtsdedtzcx.html

PHP:  is_numeric($x)
来源：http://dali.9152youxi.cn/Article/details/gtbrxgptbu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtfoexpuis.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjmqhdap.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtmruiqtow.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gogol.net.cn/Article/details/gtjodbvbkz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ydzc1.top/Article/details/gtxnvaipmg.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gtqwohkwec.html

[B14] 判断值是否在集合内
来源：http://dali.guannengcc.top/Article/details/gtthjnqett.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xziqi.cn/Article/details/gtovwuqcxk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvafhzbk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtodcbpgcr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtprnfsxus.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gttruumjlm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.kuanghao11.cn/Article/details/gtcbweddyy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtsnueabwt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtnacmcyfu.html

[B15] 布尔运算与取反
来源：http://dali.ybcxt.top/Article/details/gtzwcfyjoj.html

Py:   a and b or not c
来源：http://dali.jqgufenzy.top/Article/details/gtvzpmtcsw.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigfzy.top/Article/details/gtxvduaqtf.html

JS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtadptobrm.html

TS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtrpjssgcc.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtqrithvir.html

Go:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtyytxrfgg.html

Ruby: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtvxcvrdmg.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtwdtizymc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gtxcqwlppo.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gtkleejmkx.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigufen.top/Article/details/gtfrsfzgve.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtfbfmxyan.html

TS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtfnldplmm.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtuacydhpz.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gtxzyxgjgi.html

Ruby: return if data.nil?
来源：http://dali.jianghu66.top/Article/details/gtkfmuedpx.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfmufhxe.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyfasdiak.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gtauruqpgd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtoomdbqng.html

[C01] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtzzracffr.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtftnoegej.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtetttufqu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtvdqinpno.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtlvhmmqpa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtadaukopk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258888.top/Article/details/gtpplqnaaa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gtarhkbhta.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtdwajgpar.html

[C02] 默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtfirjiepc.html

Py:   def greet(name="World"): return name
来源：http://dali.pengpengdd.cyou/Article/details/gtdmboevxk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gtzzspwhhn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtgsxchklr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsuoinaci.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sxryk.cn/Article/details/gtzxlffzis.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gtxmoiichs.html

Ruby: def greet(name = "World") = name
来源：http://dali.jiagoushi.top/Article/details/gtzwbfgfhw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gtpgwlxujc.html

[C03] 可变参数
来源：http://dali.zhoulong.xyz/Article/details/gtrtpcfiav.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gtzvnwpbqz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cqqwz.cn/Article/details/gtdittkahy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtstdtimdo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtcjssqctn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.9152youxi.cn/Article/details/gtelnfsyng.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.smart0.xyz/Article/details/gtxpkmhvjh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ivvv.top/Article/details/gtnhlrhplf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtrotyqjtc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gtosrjcwrt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtlqowcolx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gtgpcyhcvq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtzhejlhwl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gtqpqsphbf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.feifeiyinyue.top/Article/details/gtatzzpqkq.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gtcgmabjst.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtadxstibf.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtstbgtbvy.html

[C05] 返回多个值
来源：http://dali.hnqzz.top/Article/details/gtnulzsjmg.html

Py:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtmyogidbu.html

PHP:  return [$a, $b];
来源：http://dali.pycfn.com/Article/details/gtqhmhfkes.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtjknpgtos.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtebhopyyl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gtwhrgbuzp.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtdxaistul.html

Ruby: return a, b
来源：http://dali.ivvv.top/Article/details/gtlcunccpv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gtnpzncrow.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfqqougp.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gtztmxfbif.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dianchejie.cn/Article/details/gtlhtgrbwm.html

JS:   const square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtvorafeox.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtxjukyatq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtfcdghfsz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gtimrtfmid.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigufen.top/Article/details/gtcmbeqcit.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gttzgvuxqf.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gtdormgwvr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shuidangran.top/Article/details/gtnmwmnfhe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gtoexusnkn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxdquqpy.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gtyqiufguv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yangfankeji.com/Article/details/gtepdzwauq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gtimjkvfdp.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuanzx.com/Article/details/gtdwvutiog.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gtawwyovmx.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gttgfugjkt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gttsybvqrd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gtqxvuwlgf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtstkdeicj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtopmoatwi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gtknlbmrwg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gtgfioputv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gtvnehcxve.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtktibtagl.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gtucetgndi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gtmrdltzqf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.316326.xyz/Article/details/gtbzhzhzzc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcmjhwqi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtxpvpmshe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gtqsartwqy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dianchejie.cn/Article/details/gtkvelafkb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtflwqmwfk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtesaokycf.html


<!-- 参考信息 -->