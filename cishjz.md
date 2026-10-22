代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yj20258888.top/Article/details/gtgdyoczbr.html

Ruby: gets.chomp
来源：http://dali.gaohongyu789.top/Article/details/gteavwjumt.html

C#:   Console.ReadLine();
来源：http://dali.gaohongyu789.top/Article/details/gtaybfawvr.html

[A21] 保留指定小数位输出
来源：http://dali.yj20258.top/Article/details/gtjjmffeny.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhijiandao.cn/Article/details/gtdyvndiuu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtjjlthpkg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtisprkcdq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gthblstfnh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfybuprbn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfonowtcj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtgeufaere.html

C#:   3.14159.ToString("F2")
来源：http://dali.fzhhl.top/Article/details/gtwumzmtft.html

[A22] 获取字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtandqbvcy.html

Py:   len(s)
来源：http://dali.ydzc1.top/Article/details/gtztgbwomm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jianghu66.top/Article/details/gtzszhmckt.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xylfe.cn/Article/details/gtldrdgote.html

TS:   s.length
来源：http://dali.zhengqikj.top/Article/details/gthkeggbbx.html

Java: s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gturtzwdox.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zycfv.cn/Article/details/gtmpcfwleq.html

Ruby: s.length
来源：http://dali.yongpay.top/Article/details/gtneqqkgab.html

C#:   s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtxbqgqhpo.html

[A23] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtxosyjvvx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ivvv.top/Article/details/gtyterxjil.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xylfe.cn/Article/details/gtrrsadayd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtuesdbcjq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtlcygcvoe.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gtcsrfiltm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhixingplan.top/Article/details/gtaahkzijf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gtkqlljukx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yj20258888.top/Article/details/gtdgkpudez.html

[A24] 去除首尾空白
来源：http://dali.ybcxt.top/Article/details/gttpjcbsmg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj20258888.top/Article/details/gtticnemhj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenzaomai.com/Article/details/gtqznlfydu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtjtqlpcak.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gtmduqxakn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hnxiangtu.top/Article/details/gtwbgfjmvx.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhengqikj.top/Article/details/gtiqxwseyo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xuetiantiany.cn/Article/details/gtuzwzphri.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqemjeef.html

[A25] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtgfnmdyiv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.guannengcc.top/Article/details/gtikdfrjtv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtquxmvpdr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daria6918.cn/Article/details/gtqgsegzct.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangdashe.top/Article/details/gtqydzoang.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtmymzmdtw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sysykeji.top/Article/details/gtocrviisc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.birdmap.top/Article/details/gtcilbjmqi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gtfzpmsccp.html

[A26] 类型转换总览
来源：http://dali.aibaodan.cn/Article/details/gteyaexslg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nanxinkj.top/Article/details/gtxxohnkxf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hfpthk.cn/Article/details/gtqkedflgt.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yongpay.top/Article/details/gtyntclbul.html

TS:   Number() String() Boolean() x as number
来源：http://dali.svipenyu.cn/Article/details/gtnqykhath.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gtirkzjptx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.pengpengdd.cyou/Article/details/gtvbwxxiwg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cucudq.cn/Article/details/gtveolufdf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gtkqcklkpk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtnxevdzfg.html

B. 流程控制
来源：http://dali.gogol.net.cn/Article/details/gtpuvexwgv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqoyxspuy.html

[B01] 条件判断 if / else
来源：http://dali.yj20258.top/Article/details/gtlkdfhjai.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gotoacloud.top/Article/details/gtiwydybao.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zycfv.cn/Article/details/gtdamtebup.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtbmowgwgc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtwnfmyvte.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtwpbewdzv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.andypj.xyz/Article/details/gtajhhcmvk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtbhptsgcg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtdqjrshau.html

[B02] 多分支 else if / elif
来源：http://dali.zdqjudy.top/Article/details/gthhhdfsfl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xinyue.icu/Article/details/gtzolmuosx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xziqi.cn/Article/details/gtieszgacz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtwyubiofs.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gtbuyvkjhp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtdxbxdyyr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.mhx1999.top/Article/details/gtvbqgduos.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.mhx1999.top/Article/details/gthlwamloa.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gttwtregne.html

[B03] switch / match / case
来源：http://dali.chenlongwang.top/Article/details/gtbautvkfi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.c1oappe.top/Article/details/gtsqupkwqf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtsoutjyan.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gttjyvddpo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gtnnkbyypo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtmppxdaot.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.316326.xyz/Article/details/gtnpwjdeja.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwlnsmgt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj202588.top/Article/details/gtcckionov.html

[B04] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gtsblzkuqr.html

Py:   for i in range(10): print(i)
来源：http://dali.jiagoushi.top/Article/details/gtgwlxohcl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guowangkeji.top/Article/details/gtlyamubwd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gtxbxhrarz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgfzy.top/Article/details/gtuvekzoak.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zycfv.cn/Article/details/gtauunqbly.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gzhubu.top/Article/details/gtvxjynjlf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.mhx1999.top/Article/details/gtptukhllb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xylfe.cn/Article/details/gtixxxnkdd.html

[B05] 遍历数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtllwzmdmb.html

Py:   for item in arr: print(item)
来源：http://dali.pycfn.com/Article/details/gtsnvpkgui.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yanxiufei.cn/Article/details/gtsdptcfrt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gtserilkzj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangdashe.top/Article/details/gtntqnaphs.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hfpthk.cn/Article/details/gtcvvnispa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tian-w.cn/Article/details/gtwjdjpydn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenjidiqi.icu/Article/details/gtjeeokgrb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.snrcjt.cn/Article/details/gtapmlfwbx.html

[B06] 遍历字典 / 对象
来源：http://dali.hnqzz.top/Article/details/gtjqvgfpil.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258.top/Article/details/gtelrrinhh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.9152youxi.cn/Article/details/gtugkwpznt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtsnwfmigx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gtehlctjqc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.kuanghao11.cn/Article/details/gtvuvsyhbi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhoulong.xyz/Article/details/gtjtcpuude.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gotoacloud.top/Article/details/gtfavheymq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.quarkkingdee.top/Article/details/gtbneprzcg.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gtiisbyukq.html

Py:   while i < 10: i += 1
来源：http://dali.daria6918.cn/Article/details/gtsjjvmgbn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nwbrower.top/Article/details/gtyseaifcn.html

JS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtomiuvdbr.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtckckgujq.html

Java: while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtgjtvuhjh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gtkpglhjrl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.birdmap.top/Article/details/gtethneaha.html

C#:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtdxupwnld.html

[B08] do-while（至少执行一次）
来源：http://dali.tanke756.top/Article/details/gtkhxazgyt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.guannengcc.top/Article/details/gtlwyhaldf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtwmcifptu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtcobogrfv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtskdgiwlo.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtrdkyxehc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtjuxqngqb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shuidangran.top/Article/details/gtmzroovqd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtbnkcbfqn.html

[B09] break 与 continue
来源：http://dali.xuanzx.com/Article/details/gtqyderrua.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgufenzy.top/Article/details/gtxjrmpzfm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdpjawvyi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtkcgpwbsn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtfafznpgv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtmzjjmsst.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.iojbl.cn/Article/details/gtgztceygn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gttjklltxn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtuqxpgkjc.html

[B10] 遍历同时拿索引
来源：http://dali.aizwys.cn/Article/details/gtaarrfqke.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gzhubu.top/Article/details/gtglclhbul.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gtadfjtazk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gtnwjutpmd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gtodewfntx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.smart0.xyz/Article/details/gthaihuade.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gtukpifrwz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fzhhl.top/Article/details/gttuwaghdk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yueranfly.top/Article/details/gtdzosnmas.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258.top/Article/details/gtjiwpwwgy.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigufen.top/Article/details/gtwsufeawd.html

PHP:  range(0, 10, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtqlkrupdl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdscvjkk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gtgdfbhapz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwzlwklz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtjousunwd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258888.top/Article/details/gtjsavgxdj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhoulong.xyz/Article/details/gtwfqjnimc.html

[B12] 跳出多层循环
来源：http://dali.iojbl.cn/Article/details/gtoyvqccxa.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guowangkeji.top/Article/details/gtxuebhlen.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aizwys.cn/Article/details/gtjhxvbhvy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtpebwqelb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtfptsstsm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gttfmdbtnw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ppjwa.cn/Article/details/gtvmwvleik.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gtyiyhtnsc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.andypj.xyz/Article/details/gtyeprffwo.html

[B13] 判断是否为数字
来源：http://dali.jianghu66.top/Article/details/gtexcjzraw.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gtalupvqfn.html

PHP:  is_numeric($x)
来源：http://dali.ehwqpu.com/Article/details/gtrazoxfro.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gtlchamnzb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gtmhdfjdqk.html

Java: x instanceof Number
来源：http://dali.zhiwuduotai.top/Article/details/gtiofefoaw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gtuwidwyfw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhengqikj.top/Article/details/gtsbgacilh.html

C#:   x is int or double or decimal
来源：http://dali.nanxuanxn.top/Article/details/gtjrurdjlm.html

[B14] 判断值是否在集合内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgspjtloe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gtafywjcxy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hysaishi.cn/Article/details/gtuczcubxx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtvbmrtbrc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtakejjd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gtetytrwok.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ehwqpu.com/Article/details/gtjejqbxmj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtimvpqfac.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtctpbdfrl.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gthoxhbhbz.html

Py:   a and b or not c
来源：http://dali.gogol.net.cn/Article/details/gtbbzlsowk.html

PHP:  $a && $b || !$c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrldwxhh.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtntavrdkj.html

TS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtoyvfivqq.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtvnukmexh.html

Go:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtwmgvpcoq.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtlczohpbj.html

C#:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtdhhybeud.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gtzcpftxir.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gtopzrgucp.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gtfingoziv.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtdslvyypb.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gttdpfdjkz.html

Java: if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtrimecjwk.html

Go:   if data == nil { return }
来源：http://dali.xuanzx.com/Article/details/gtminepxzx.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gtbqwuxrvg.html

C#:   if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gtthrjgwfv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvbwgvonz.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gtrmrkqwml.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtlgexuero.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtpdsvtgvk.html

Py:   def add(a, b): return a + b
来源：http://dali.xziqi.cn/Article/details/gtdnotknqb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnemsgalm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtawvhfntf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtefktqxnk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtccqszizn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtdvhzxrpi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.bjfxy.top/Article/details/gtfxevjfva.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtveafgakc.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtitsaeslm.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gteiaqvibl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daxiang520.top/Article/details/gtutctlorp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtmcpunjor.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtnlwszplo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuxming.cn/Article/details/gtkrofxsaq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gtqgwpoxen.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gtnuwtrpef.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtdttuvnwg.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gtafqnyedl.html

Py:   def total(*args): return sum(args)
来源：http://dali.havefunace.top/Article/details/gtlvmguish.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmjgnehgg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gthywhcpps.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtfrxhjgbp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gtlztgjkpe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.c1oappe.top/Article/details/gtexxpaozm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gtzhfitqhg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gtrmfqpfya.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gtgsxgunfg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtugwqsrhh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gtdgexvzwt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtdpyljfsj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtredehhdg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgufenzy.top/Article/details/gtiytjcmuc.html

Go:   // 无：用配置结构体参数
来源：http://dali.andypj.xyz/Article/details/gtinlcgnwc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtabgnkvex.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtjrdtnete.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gtjpncyzxc.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtlvbrytad.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtikbfdsht.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtqbrqoayo.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtfjyznyfd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.c1oappe.top/Article/details/gtuqdkmpay.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtctfoeyvg.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gtpqduvife.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtludiwpvk.html

[C06] 匿名函数 / lambda
来源：http://dali.yuanzhike.top/Article/details/gtmcevioxl.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gtovazpbkv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yueranfly.top/Article/details/gtuihtkeoe.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtatmnxwia.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gtdopsemqs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukmktaup.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cashguo.top/Article/details/gtdfkslmmp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gtkgruemrh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfvhvacb.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258888.top/Article/details/gtoaelnuqf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.0kj1m.cn/Article/details/gtpfjaglpf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtojkuvsfe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yongpay.top/Article/details/gtzxakslzq.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gtekdjspvg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gtediqibne.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gtbegpmknw.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxinkj.top/Article/details/gtxrqzlaje.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gtrmtyskld.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gtyzzcvtzp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gtwhcideps.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhsfksjd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtqgpgande.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtggxrtzav.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtphwjzkeb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gtxelyzzri.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yueranfly.top/Article/details/gtakunmufa.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gthrufctar.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gtpfkhzzod.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtuvksrbir.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtmhphzcaf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtpjjdjonm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtozrsarmu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gtzcbpnrif.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gtbobawngg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpdywkqfm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gtdmngnons.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gtpstbqumr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtncyvasdb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gtvexctrby.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gtheceflbt.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gtkuooltex.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gtaggsvgyv.html

Go:   花括号块级作用域
来源：http://dali.yvedp.cn/Article/details/gtwefyegff.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gtaimstxuv.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gtfdjbzrzw.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gthmsdyufj.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gtmtpssbma.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.meibo888.top/Article/details/gtznbseots.html


<!-- 参考信息 -->