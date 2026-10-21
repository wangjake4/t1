代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jlsjyb.cn/Article/details/gtqinvhjun.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.aibaodan.cn/Article/details/gtnxqednnt.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxuanxn.top/Article/details/gtldnocgoz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yonumen.top/Article/details/gtgzvdsttn.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.kuanghao11.cn/Article/details/gtxpvwddgr.html

Ruby: gets.chomp
来源：http://dali.xuanzx.com/Article/details/gtorofpcgx.html

C#:   Console.ReadLine();
来源：http://dali.hysaishi.cn/Article/details/gtgfhobrcu.html

[A21] 保留指定小数位输出
来源：http://dali.guowangkeji.top/Article/details/gtbqgpythn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.guannengcc.top/Article/details/gtusbhpmhd.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmhbjirq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtxsexqpwx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gtwfyovcgw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gtyjusbjwu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtrvnfkqer.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtvetcgzug.html

C#:   3.14159.ToString("F2")
来源：http://dali.birdmap.top/Article/details/gtdmobxdex.html

[A22] 获取字符串长度
来源：http://dali.cucudq.cn/Article/details/gtkdlfectd.html

Py:   len(s)
来源：http://dali.0kj1m.cn/Article/details/gtmhzkbckh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.birdmap.top/Article/details/gtxegjfkmo.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sxryk.cn/Article/details/gtprbojmty.html

TS:   s.length
来源：http://dali.vqdsnc.cn/Article/details/gtoxkjpilx.html

Java: s.length()
来源：http://dali.nwbrower.top/Article/details/gtlvtpbqed.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sufxvd.cn/Article/details/gtorbfjpvr.html

Ruby: s.length
来源：http://dali.cashguo.top/Article/details/gtirwijfgv.html

C#:   s.Length
来源：http://dali.hnqzz.top/Article/details/gtvmaudseg.html

[A23] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtlptyyqpl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.9152youxi.cn/Article/details/gtkulozhdf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.mhx1999.top/Article/details/gtclghihxt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtbncgvtfq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gtwuzkeezu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gtsnzctarv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sufxvd.cn/Article/details/gtpjfnkhul.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtjobpbsze.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hywenlv.cn/Article/details/gtayxgsctq.html

[A24] 去除首尾空白
来源：http://dali.jqgufenzy.top/Article/details/gtwukqhugt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fengsongda.top/Article/details/gtkqavmrzj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkzkbvpc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aizwys.cn/Article/details/gtgyqwcuqr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gtcwoonska.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tianlin.xyz/Article/details/gtmbbqutag.html

Go:   strings.TrimSpace(s)
来源：http://dali.yueranfly.top/Article/details/gtplzpqzzu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hysaishi.cn/Article/details/gtpxobfoxe.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yongpay.top/Article/details/gtjqkcqezc.html

[A25] 字符串比较
来源：http://dali.tanke756.top/Article/details/gttgpjeoiq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuanzhike.top/Article/details/gtornktyfn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jqgufenzy.top/Article/details/gteltmmmtw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangdashe.top/Article/details/gtdtuvsqei.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxikimtf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cashguo.top/Article/details/gtrgsyxkkk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gtriiiaele.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dianchejie.cn/Article/details/gtqpewmknw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hywenlv.cn/Article/details/gtjzlvsfsp.html

[A26] 类型转换总览
来源：http://dali.zhongyouzk.top/Article/details/gtkeiezvvz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daxiang520.top/Article/details/gtzobkivzn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.9152youxi.cn/Article/details/gtqvubkobt.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jlsjyb.cn/Article/details/gtsvrxdgxz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ivvv.top/Article/details/gtfawevyyh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gtrwytgayq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jqgfzy.top/Article/details/gttuydtcxe.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gzhubu.top/Article/details/gtuwirexqw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gtmwywdlba.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtodrfbxvb.html

B. 流程控制
来源：http://dali.yuxming.cn/Article/details/gtqpbaqpnr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjigykopx.html

[B01] 条件判断 if / else
来源：http://dali.xuetiantiany.cn/Article/details/gtwepppvab.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jianghu66.top/Article/details/gtxmqfjdqi.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xinyue.icu/Article/details/gtyzhjavtv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtgtfknzfp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtmgkdcqfu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtgkgrcuss.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258888.top/Article/details/gtxwtaagpr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nanxuanxn.top/Article/details/gtgoycckjj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtidoghybb.html

[B02] 多分支 else if / elif
来源：http://dali.snrcjt.cn/Article/details/gtzwcbpzbf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.bjfxy.top/Article/details/gtfoldnyeo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.guowangkeji.top/Article/details/gtjdhrxkno.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gtqrhhzogo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtjxkxjzvt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtodywlvsj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.birdmap.top/Article/details/gtwbyzvrth.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shzxlz.cn/Article/details/gtoorysomi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtnemwrpqt.html

[B03] switch / match / case
来源：http://dali.ybcxt.top/Article/details/gthumvygxe.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xziqi.cn/Article/details/gtardijpym.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtheitadnr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gtqcmmidxj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtpihlqqmh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtfhscxlup.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtsyhsxrge.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xuanzx.com/Article/details/gtjeijafsm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gtiemkuopz.html

[B04] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gtbeywwkan.html

Py:   for i in range(10): print(i)
来源：http://dali.havefunace.top/Article/details/gtegbqsnrn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hysaishi.cn/Article/details/gtiwrlwdbb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gtggqbpcti.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pycfn.com/Article/details/gtzrfwcmsq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ivvv.top/Article/details/gtopiorkfu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jlsjyb.cn/Article/details/gtdcijzldg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigfzy.top/Article/details/gtlwossdzq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xinyue.icu/Article/details/gtsmyqrdcq.html

[B05] 遍历数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtmmkevmtj.html

Py:   for item in arr: print(item)
来源：http://dali.cucudq.cn/Article/details/gtbmzbwvab.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gthigdrlrs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtkxyzxmlb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtgmkrqpbo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daxiang520.top/Article/details/gtngnxmkld.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dashuyun.cn/Article/details/gtbjglbmmz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sxryk.cn/Article/details/gtybrbgqpp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cqqwz.cn/Article/details/gtrmlhduxp.html

[B06] 遍历字典 / 对象
来源：http://dali.9152youxi.cn/Article/details/gtwpqztnpc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sysykeji.top/Article/details/gthnotvfrh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yonumen.top/Article/details/gtsvyjljrs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gtvaeujjdt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gtarxmhmow.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pycfn.com/Article/details/gtzkdzdmsm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hammf.cn/Article/details/gtbbhbhxca.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jyoumei.cn/Article/details/gtbkmndbmd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sufxvd.cn/Article/details/gtywelshtx.html

[B07] while 循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjycheqvu.html

Py:   while i < 10: i += 1
来源：http://dali.tian-w.cn/Article/details/gtagtazqnh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybqvpihw.html

JS:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtqagdpwxn.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gthtrumnqm.html

Java: while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtnlmzohrt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jyoumei.cn/Article/details/gtycmlwpzn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fzhhl.top/Article/details/gtnvvgpzvv.html

C#:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtwkftpnij.html

[B08] do-while（至少执行一次）
来源：http://dali.jlsjyb.cn/Article/details/gtzqhyqmae.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zdqjudy.top/Article/details/gtihndojvf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtlmbvlshf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtvvbgypli.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtzdolozkf.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttggxtwrw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ppjwa.cn/Article/details/gtxfsysple.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxuanxn.top/Article/details/gtztmbtevi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtbvkbalsn.html

[B09] break 与 continue
来源：http://dali.ppjwa.cn/Article/details/gtcpgqompt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gtwpvtpogd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtadnrequu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtvjjzlvyx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtqvvmcjue.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtwsbqbccr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtroiscfqd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ehwqpu.com/Article/details/gtbinxndbu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtosmfbxjw.html

[B10] 遍历同时拿索引
来源：http://dali.ybcxt.top/Article/details/gtmuhiazcp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ivvv.top/Article/details/gtqzllmhvp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tian-w.cn/Article/details/gtjokobtmv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtmuagawfz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gtusgaynid.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yongpay.top/Article/details/gtqgmgqvtq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cqqwz.cn/Article/details/gttwwamuld.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daxiang520.top/Article/details/gtxgmjzqrx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.meibo888.top/Article/details/gtpvcqzqyk.html

[B11] 生成数字序列 / 区间
来源：http://dali.fzhhl.top/Article/details/gtzczlyhyy.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gtoyxxrojm.html

PHP:  range(0, 10, 2);
来源：http://dali.daxiang520.top/Article/details/gtsbvbrqzs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtcxynszaq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtkmljoely.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuzegndg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yongpay.top/Article/details/gtkqdzszyw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gtkoshrzng.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhixingplan.top/Article/details/gtfuvxhmdt.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslzfluhc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ydzc1.top/Article/details/gtuoannysj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gtxbvhehhg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzadbgslh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtzmnlkluj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtosmcdffj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gtqgvoxewp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgxwwjkq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gtctyanwgk.html

[B13] 判断是否为数字
来源：http://dali.c1oappe.top/Article/details/gtbzduylih.html

Py:   isinstance(x, (int, float))
来源：http://dali.nwbrower.top/Article/details/gtdfjnatkv.html

PHP:  is_numeric($x)
来源：http://dali.zhongyouzk.top/Article/details/gtawbvwgvi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtkrxkyeta.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gtfixjospz.html

Java: x instanceof Number
来源：http://dali.redwolf501.top/Article/details/gtadpecodj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gtovvbevmy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gtfqlpxcaq.html

C#:   x is int or double or decimal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwvxeuqo.html

[B14] 判断值是否在集合内
来源：http://dali.sufxvd.cn/Article/details/gtpqixwyan.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvazzfhm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gotoacloud.top/Article/details/gtvitvjqax.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtsbhldrtb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtxihwoigm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtjhpqonfz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigufen.top/Article/details/gtnwqijkaz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtxbscjnos.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqetdxhz.html

[B15] 布尔运算与取反
来源：http://dali.svipenyu.cn/Article/details/gtukxwpvlh.html

Py:   a and b or not c
来源：http://dali.hammf.cn/Article/details/gtqeiezagi.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gtzyzaumvl.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtxsexpzvb.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtbyilnkmo.html

Java: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtrasebyzs.html

Go:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtuknywwbs.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtwshdsmcp.html

C#:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtorvwolow.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtjqceaaas.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gttsubkbgx.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gtdutkcpcq.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtbxqcbgvx.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtcjonrlia.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gttnehqutp.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gtlcvcedlh.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gtwpvzbrki.html

C#:   if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtpqcyxdsm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtiqmsalbv.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gtdohuolhd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttahxunwx.html

[C01] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtnshvhxhc.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlvyefmi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtcbkejrnp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtgzznxatp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtsqtxwnsv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtfrrmserp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgcqycli.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gtzvftvmiq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtjblsrpjz.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gtpmwxjchz.html

Py:   def greet(name="World"): return name
来源：http://dali.cqqwz.cn/Article/details/gthibkmptt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjerfxap.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtzzfigots.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfthaprd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ivvv.top/Article/details/gtuofvmmhm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cqqwz.cn/Article/details/gtsrsuazwz.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gtqtypzdmk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gtzftoscyp.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoawxwtcf.html

Py:   def total(*args): return sum(args)
来源：http://dali.cdnleiting.top/Article/details/gtauurddgj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dianchejie.cn/Article/details/gtjbavzhuo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtmonljqlf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gtizyyxvkx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.meibo888.top/Article/details/gtgmcntqse.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqonelqxx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgufenzy.top/Article/details/gtfwudaqcy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.birdmap.top/Article/details/gtgfzgcukp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gzhubu.top/Article/details/gtgksehgcu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangshuangyany.cn/Article/details/gtfopixfjl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gtlbywazmi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtjrsjbiim.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcngouxaa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gtcrzsiubc.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gturhykzju.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtmoguxcye.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtcjnfbhcc.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gtzxfdiubc.html

Py:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gtkysxuuvl.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtkxkvguri.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gtwdurehoy.html

TS:   return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtniyojdvi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gttrgistzc.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtoprvydck.html

Ruby: return a, b
来源：http://dali.dianchejie.cn/Article/details/gtemaqcnzt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gtjqpfyuhv.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gtoxfgeyrw.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtkwfiydkz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gtjhhhgjfv.html

JS:   const square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtsfijndeo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtiyvmshdl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenlongwang.top/Article/details/gturwcspdu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gtvfrblnct.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sysykeji.top/Article/details/gtnrffyuzi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtippobluv.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gtvovzyqdb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gtodgcenjp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nwbrower.top/Article/details/gtevomevcj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gtckyusjee.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gtkmexuqur.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrnxckud.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shangyingyoupin.top/Article/details/gtfctnewyu.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtxqgplhfa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gtzvtxgfxa.html

[C08] 闭包
来源：http://dali.ivvv.top/Article/details/gtirkxtjwh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gtbiihscwc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zdqjudy.top/Article/details/gthifhuxdu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtulprknuf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtvubzwyys.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tianlin.xyz/Article/details/gtcowmprwr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gtquzwrbnf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sweek.top/Article/details/gtpyzqydrr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtzadsgmil.html

[C09] 递归
来源：http://dali.yj202588.top/Article/details/gtzigocvdr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtofvpsxls.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtztbfgnki.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtlqzicdqy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtatinorya.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtyqbexgqt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gtwnnkhmqe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdalejylc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gttqwessgz.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtftamjgte.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cashguo.top/Article/details/gtibwkrvxx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gtequcruss.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtavolsebw.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtalxojxai.html

Java: 方法内为块级作用域
来源：http://dali.cashguo.top/Article/details/gtkqqrgwxm.html

Go:   花括号块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtfxfyqenu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gtjavjostu.html


<!-- 参考信息 -->