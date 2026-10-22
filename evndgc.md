代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nanxinkj.top/Article/details/gtajsxgwmt.html

Ruby: gets.chomp
来源：http://dali.yongpay.top/Article/details/gtdweosfts.html

C#:   Console.ReadLine();
来源：http://dali.cdnleiting.top/Article/details/gtagdmarze.html

[A21] 保留指定小数位输出
来源：http://dali.ydzc1.top/Article/details/gtzlubvwep.html

Py:   f"{3.14159:.2f}"
来源：http://dali.316326.xyz/Article/details/gtukoyeotu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtgvbprufr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtvfypxrxn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtdolrygin.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gtccmxhewu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gtvlailjtq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gtxbpuseou.html

C#:   3.14159.ToString("F2")
来源：http://dali.meibo888.top/Article/details/gtpjbnbptg.html

[A22] 获取字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtyiraycpf.html

Py:   len(s)
来源：http://dali.yangfankeji.com/Article/details/gtlfwpeluc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.guannengcc.top/Article/details/gthzkydxth.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yvedp.cn/Article/details/gthgbyssvq.html

TS:   s.length
来源：http://dali.gaohongyu789.top/Article/details/gtgwstygep.html

Java: s.length()
来源：http://dali.zdqjudy.top/Article/details/gtbfjwgogh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gogol.net.cn/Article/details/gtofjsfbqg.html

Ruby: s.length
来源：http://dali.ybcxt.top/Article/details/gtuwhhqwrv.html

C#:   s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdjawdjv.html

[A23] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gthzeiijsk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhongyouzk.top/Article/details/gttouzfkjj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cqqwz.cn/Article/details/gtmcgovoez.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gtxddumrup.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuanzx.com/Article/details/gtfhejtwwc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gtbwytczro.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ehwqpu.com/Article/details/gtfdzgiqhi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.andypj.xyz/Article/details/gtnyddtzub.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhoulong.xyz/Article/details/gtulmhjmaz.html

[A24] 去除首尾空白
来源：http://dali.feifeiyinyue.top/Article/details/gtedfmlxwp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj202588.top/Article/details/gthhwoedvl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hywenlv.cn/Article/details/gtifzcmoco.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyucihdb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtsyldqjlz.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxuanxn.top/Article/details/gtpkdkekof.html

Go:   strings.TrimSpace(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtoesethcc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yangfankeji.com/Article/details/gtloqqtcth.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtgaqpouhw.html

[A25] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtpyvujcwa.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenzaomai.com/Article/details/gtesotqjlf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.svipenyu.cn/Article/details/gtzzaecqmr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.feifeiyinyue.top/Article/details/gtmeqpzxdm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtakfyxtxz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gogol.net.cn/Article/details/gtbmvvvmig.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.haohaochexian.top/Article/details/gtatwbbmtz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhixingplan.top/Article/details/gttxvciowm.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gtxzsslzig.html

[A26] 类型转换总览
来源：http://dali.cashguo.top/Article/details/gtebflklcd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.tian-w.cn/Article/details/gtifjettbq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tian-w.cn/Article/details/gtzhrdqudk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnxiangtu.top/Article/details/gtsjvdbfyr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhengqikj.top/Article/details/gtuysqicyh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hnxiangtu.top/Article/details/gtxiwrxotq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258888.top/Article/details/gtrrbkribs.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinqigfzy.top/Article/details/gturavikoe.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gtcjxlgjxf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsaskminu.html

B. 流程控制
来源：http://dali.fzhhl.top/Article/details/gtbamslzcb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzlrciwib.html

[B01] 条件判断 if / else
来源：http://dali.hfpthk.cn/Article/details/gturwoqefa.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenjidiqi.icu/Article/details/gtsftrakjl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.aibaodan.cn/Article/details/gtmaobpdru.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtdysamqsc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtkfnohkmf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtijsskpyk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxinkj.top/Article/details/gtmbaoirfx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zycfv.cn/Article/details/gtugceokyh.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtgnllgmhc.html

[B02] 多分支 else if / elif
来源：http://dali.pengpengdd.cyou/Article/details/gtettmliec.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aibaodan.cn/Article/details/gthxgjsdao.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gaohongyu789.top/Article/details/gtefhaerjf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtlcgnfdss.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtktnagaio.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoozdvnde.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.c1oappe.top/Article/details/gtsjeddwby.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ivvv.top/Article/details/gtlwtskpke.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtyvyypsuq.html

[B03] switch / match / case
来源：http://dali.zhixingplan.top/Article/details/gtnvrozvsc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhiwuduotai.top/Article/details/gtyvxrodmo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gtythjvcpl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuoiamyfa.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtbqppdwsn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtsuvzvmoq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gtxkipuzzi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.snrcjt.cn/Article/details/gtgfqngyld.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj202588.top/Article/details/gtimtijfzw.html

[B04] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtlrgygjrg.html

Py:   for i in range(10): print(i)
来源：http://dali.9152youxi.cn/Article/details/gtrpnyqyju.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nwbrower.top/Article/details/gtsrgcarqr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtohjyyuna.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvzmdmarp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtayxjdeoq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gtnqgjqlob.html

Ruby: 10.times { |i| puts i }
来源：http://dali.316326.xyz/Article/details/gtirdcefuz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yvedp.cn/Article/details/gtqjpgjnng.html

[B05] 遍历数组 / 列表
来源：http://dali.bjfxy.top/Article/details/gtzshomsrc.html

Py:   for item in arr: print(item)
来源：http://dali.yj202588.top/Article/details/gtjrnnpicg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxuanxn.top/Article/details/gtvrskeqhg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtwynguijg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxinkj.top/Article/details/gtrgfhbgmy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gtyfuqgcaw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cucudq.cn/Article/details/gtbmcmenbq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.aizwys.cn/Article/details/gtefvhzxef.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gzhubu.top/Article/details/gtiakplfax.html

[B06] 遍历字典 / 对象
来源：http://dali.gzhubu.top/Article/details/gtwuyrgbjv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuxming.cn/Article/details/gtzpvnjgfc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuanzx.com/Article/details/gtsfveadun.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gthjzltzre.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ybcxt.top/Article/details/gtdlfyrcfn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.bjfxy.top/Article/details/gtapltdrtp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgfzy.top/Article/details/gtectdspjp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgufenzy.top/Article/details/gtgmvmwqph.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangdashe.top/Article/details/gtaloirgde.html

[B07] while 循环
来源：http://dali.yj20258888.top/Article/details/gtlxbcaerw.html

Py:   while i < 10: i += 1
来源：http://dali.yongpay.top/Article/details/gtzffmxrww.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cucudq.cn/Article/details/gtgjhexpud.html

JS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtewvrbjjr.html

TS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtbabjbmyd.html

Java: while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gthlppaghx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhengqikj.top/Article/details/gtxsextfnk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuanzx.com/Article/details/gtqwmqgikg.html

C#:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtymjcfplt.html

[B08] do-while（至少执行一次）
来源：http://dali.cdnleiting.top/Article/details/gtfuulhwcx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnqzz.top/Article/details/gtujkooqia.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtitktseai.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtofflepyr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtwwakkgnm.html

Java: do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtgtcfbnsr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtiiqevzyf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jianghu66.top/Article/details/gthjtkdgtj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtujfeynhr.html

[B09] break 与 continue
来源：http://dali.tianlin.xyz/Article/details/gtjbibbste.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nwbrower.top/Article/details/gtukzyjrvj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtjxzilafq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtukhpeklq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtotcimvjf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtcethmeml.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fengsongda.top/Article/details/gttleyxkxu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.smart0.xyz/Article/details/gtniypmhxs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtuejrxito.html

[B10] 遍历同时拿索引
来源：http://dali.yanxiufei.cn/Article/details/gtznkdugre.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.vqdsnc.cn/Article/details/gtlbgmkztm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.c1oappe.top/Article/details/gtclmanjda.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtliaswlgl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtbtzpirbt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoexelluv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcryjfpqe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gtxbooorjz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtjxfebwyw.html

[B11] 生成数字序列 / 区间
来源：http://dali.jianghu66.top/Article/details/gtkaczpztz.html

Py:   list(range(0, 10, 2))
来源：http://dali.kuanghao11.cn/Article/details/gtjgernyab.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtiwddoxrf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.9152youxi.cn/Article/details/gtnztbjedu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtmzsjsehd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daxiang520.top/Article/details/gtfozacpzj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhoulong.xyz/Article/details/gtfknoameg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yanxiufei.cn/Article/details/gtdmvwxtlj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gtpilpgxox.html

[B12] 跳出多层循环
来源：http://dali.jiagoushi.top/Article/details/gtaqehsflp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gtfqcyzhow.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gtlhphgmwj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtqhzoklsg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtdnpcublk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtedpfcorh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxuanxn.top/Article/details/gtojjghewg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangdashe.top/Article/details/gtfjiihaxu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj20258888.top/Article/details/gtwmfkgprw.html

[B13] 判断是否为数字
来源：http://dali.yj20258.top/Article/details/gturrnjmqs.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gtkpxsrklv.html

PHP:  is_numeric($x)
来源：http://dali.xuanzx.com/Article/details/gtmnjnydlx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtonzaobgg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtjlkoqxlv.html

Java: x instanceof Number
来源：http://dali.sweek.top/Article/details/gtzxugocqp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gtqinoltgm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ybcxt.top/Article/details/gthgsoqwxr.html

C#:   x is int or double or decimal
来源：http://dali.zhixingplan.top/Article/details/gtbgfkiume.html

[B14] 判断值是否在集合内
来源：http://dali.yj202588.top/Article/details/gtmxoqvubw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hongshengwenyu.top/Article/details/gthmayskzb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gtbsdmghre.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtgpazfjgy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gthonddhoe.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtixwgqxcc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtvxjfzxpx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtcntsfgfo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gttcvwstsm.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gtkmtpnjkk.html

Py:   a and b or not c
来源：http://dali.pengpengdd.cyou/Article/details/gtvyklwzez.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gttoksksym.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtznifdcbk.html

TS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtfppsqegz.html

Java: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gttcpzayzz.html

Go:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtlegsnfot.html

Ruby: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gttfqpbhpw.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtqomiwwds.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.wangdashe.top/Article/details/gtaxpwvsil.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gtwmjrqqhb.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gtjmyfczfb.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtueyruhpa.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtcqfhcstn.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtxvvknyzo.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gtxzhepvku.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gtezjnruvq.html

C#:   if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtwbbymdjc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtgcvjjypp.html

C. 函数与作用域
来源：http://dali.haohaochexian.top/Article/details/gtqkhagkin.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthefxcfew.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtfhhuwbmd.html

Py:   def add(a, b): return a + b
来源：http://dali.hammf.cn/Article/details/gttoahtdok.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtsuweyvgj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtlvunrdzb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtyeckxqgm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gttryuvsgj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtwwkzehfs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhoulong.xyz/Article/details/gtylramkwk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtqdccaekz.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gtcvgwgvfo.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtoyuyxhlz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dianchejie.cn/Article/details/gturyitdml.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtarbutaxi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtycodabrv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gtqvclhqft.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngzvvbgz.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gtfgtffekw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yongpay.top/Article/details/gtmgfvtori.html

[C03] 可变参数
来源：http://dali.feifeiyinyue.top/Article/details/gtalsampzj.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gtfenijeua.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.316326.xyz/Article/details/gthzdgjlcb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gtiowyhero.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtqishywvs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gzhubu.top/Article/details/gtaaseiirv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258.top/Article/details/gtcfzdkfpa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gtcjyphmfu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.havefunace.top/Article/details/gtosfdlgbo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gtbnkyeegu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.mhx1999.top/Article/details/gtjluuccot.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenzaomai.com/Article/details/gtijdtulci.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxgyyysjn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnqzz.top/Article/details/gtmpnuixva.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pengpengdd.cyou/Article/details/gttiuewhcd.html

Go:   // 无：用配置结构体参数
来源：http://dali.cdnleiting.top/Article/details/gtbetezava.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtgpkfvxrd.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtmfdzwcxd.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gtfhcjsrha.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtcyntlfcc.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gtaqmadlrg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtoasecpio.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtydguxaht.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gtuumyaomn.html

Go:   return a, b
来源：http://dali.yj202588.top/Article/details/gtxnvdwlkz.html

Ruby: return a, b
来源：http://dali.havefunace.top/Article/details/gttufqqyiz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtmpnagnkf.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gtedbcopwy.html

Py:   square = lambda x: x * x
来源：http://dali.xziqi.cn/Article/details/gtvyceohek.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtivzznwyn.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjadxongx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gtruhovfdh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hammf.cn/Article/details/gtyfoduadd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ehwqpu.com/Article/details/gthppoiuvs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtauthqrxj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtzwakadfc.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtpipspkui.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gtjcxwrptw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtridrxxel.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gtokbbydfl.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gtykrdijcf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gtlzkvvbaw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sxryk.cn/Article/details/gtjsekmsfj.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gtestewsuw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gtnawwszkv.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gtcrimzsti.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.bjfxy.top/Article/details/gtcqpkujxi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.meibo888.top/Article/details/gttnvozygo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtednsfqfm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtqpjjgqyg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gotoacloud.top/Article/details/gtfncndcwg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtuvbtdbqh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtrlvrhdlt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gttokgfgiy.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtzmavaiyk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtleqiiaee.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yongpay.top/Article/details/gtyblrijrh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtcdftuqjz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtluatiqbp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtalhlgmes.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gtppwbdnsz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gttgsuzjes.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpumrhidb.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtiveqkjju.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hammf.cn/Article/details/gtmzkynswr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.meibo888.top/Article/details/gthxbqzpos.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yvedp.cn/Article/details/gtdpnfnhkj.html

TS:   同 JS
来源：http://dali.ybcxt.top/Article/details/gttgwakpsy.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtfcnrbkda.html

Go:   花括号块级作用域
来源：http://dali.aizwys.cn/Article/details/gtmpgeqboq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gtfqisdrvx.html

C#:   块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtokjrzldt.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gtkelszrps.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gtewpkhvoj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gtfgmlohmc.html


<!-- 参考信息 -->