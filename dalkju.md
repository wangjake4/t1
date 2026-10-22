代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aibaodan.cn/Article/details/gtrlsouxcj.html

Ruby: gets.chomp
来源：http://dali.yonumen.top/Article/details/gtgbtqzvlr.html

C#:   Console.ReadLine();
来源：http://dali.sysykeji.top/Article/details/gtgiltqhgo.html

[A21] 保留指定小数位输出
来源：http://dali.yj20258888.top/Article/details/gtgqzsjeqm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cheryme.top/Article/details/gtsaeuoryz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gtkmuhzvep.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtexcykgca.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtzlwfmvqa.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtxbdntlyq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gtohwdsrsx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gtedngkaxu.html

C#:   3.14159.ToString("F2")
来源：http://dali.sysykeji.top/Article/details/gtxtfrjvfa.html

[A22] 获取字符串长度
来源：http://dali.fzhhl.top/Article/details/gtprzhwouj.html

Py:   len(s)
来源：http://dali.ydzc1.top/Article/details/gtciawdhph.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jinghuilouyu.cn/Article/details/gtlttzkvpj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhengqikj.top/Article/details/gtuhtiwfsn.html

TS:   s.length
来源：http://dali.sysykeji.top/Article/details/gtcxvndmpm.html

Java: s.length()
来源：http://dali.316326.xyz/Article/details/gtqhdhisqe.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guannengcc.top/Article/details/gtspfngkph.html

Ruby: s.length
来源：http://dali.bjfxy.top/Article/details/gtvqbofyxx.html

C#:   s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtkwyiuuno.html

[A23] 大小写转换
来源：http://dali.sweek.top/Article/details/gtkdjdgmei.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dianchejie.cn/Article/details/gtjxbclhen.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.0kj1m.cn/Article/details/gtakyoheke.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gtyvavynpl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gtqptrdfof.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiyoupib.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daria6918.cn/Article/details/gtxcaccray.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtxuuiocta.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sweek.top/Article/details/gtyziolqim.html

[A24] 去除首尾空白
来源：http://dali.vqdsnc.cn/Article/details/gthbuvaspv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj20258888.top/Article/details/gtqrqfymaq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.guannengcc.top/Article/details/gtfkunpjzt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtgmauovpu.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbycpfbmh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hywenlv.cn/Article/details/gtcgguoesv.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtgbauawjt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.haohaochexian.top/Article/details/gtgxaofsaq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ivvv.top/Article/details/gtospgfeha.html

[A25] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgbwirdl.html

Py:   s1 == s2; s1 != s2
来源：http://dali.daxiang520.top/Article/details/gtqkqrvnux.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hnxiangtu.top/Article/details/gtincbswel.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gtjixkmcyw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tian-w.cn/Article/details/gtojzlkphn.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zdqjudy.top/Article/details/gtfzoidmnl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenlongwang.top/Article/details/gthfgibbqs.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.0kj1m.cn/Article/details/gtjlvlmdcl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gtunbqgewn.html

[A26] 类型转换总览
来源：http://dali.mhx1999.top/Article/details/gteynlafju.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenzaomai.com/Article/details/gtymsxeohn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jiagoushi.top/Article/details/gtaewpbnbp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xinyue.icu/Article/details/gtphtsmkjr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guannengcc.top/Article/details/gtvvtlhmtn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gtuvtrehhj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.havefunace.top/Article/details/gtxakmebms.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hysaishi.cn/Article/details/gtqofebtcv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.smart0.xyz/Article/details/gtakukehub.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtgrcexueo.html

B. 流程控制
来源：http://dali.hnqzz.top/Article/details/gtlknqasjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtropumabh.html

[B01] 条件判断 if / else
来源：http://dali.hywenlv.cn/Article/details/gtdvatxfuu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258888.top/Article/details/gtjlzlbgfb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cdnleiting.top/Article/details/gtjwjthzxh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtvkizqxrk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtorrslwtr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtktgwpnmz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258.top/Article/details/gtpgkzgkhy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtowmawdjz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtwsomxaqy.html

[B02] 多分支 else if / elif
来源：http://dali.yuxming.cn/Article/details/gtwynokjsv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fzhhl.top/Article/details/gtiskznkpk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yvedp.cn/Article/details/gtfbsitcjk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtserqssww.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtqzonxvau.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtiwojyoym.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sysykeji.top/Article/details/gtotdutbsz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.c1oappe.top/Article/details/gtnnkngdnz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gttlzyrugu.html

[B03] switch / match / case
来源：http://dali.hnxiangtu.top/Article/details/gtytxfiirp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangtech.top/Article/details/gttqlfexom.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gtjrwbgwwg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtncmrqaew.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtbieykwzy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtvxicgohs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yvedp.cn/Article/details/gtdrcxzogj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstwdeyrd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fzhhl.top/Article/details/gtydiakuzf.html

[B04] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtdoenbaxf.html

Py:   for i in range(10): print(i)
来源：http://dali.cheryme.top/Article/details/gtpmlipzbr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fzhhl.top/Article/details/gtlpmjgksw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtnrjcccrp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gtewkfcaqq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.c1oappe.top/Article/details/gtjvxeajew.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aibaodan.cn/Article/details/gtrkrftkeh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangdashe.top/Article/details/gtcwhdcekw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cheryme.top/Article/details/gtcvvpalty.html

[B05] 遍历数组 / 列表
来源：http://dali.hnqzz.top/Article/details/gtfmisxune.html

Py:   for item in arr: print(item)
来源：http://dali.gaohongyu789.top/Article/details/gtrqzmfbch.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shzxlz.cn/Article/details/gtqfnffkao.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtbpilukgp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gtkbohuoyw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zycfv.cn/Article/details/gtravnxxjr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.bjfxy.top/Article/details/gtbkykyplq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.mhx1999.top/Article/details/gtnhwpckfg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxkspyeg.html

[B06] 遍历字典 / 对象
来源：http://dali.hammf.cn/Article/details/gthjahimfq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgfzy.top/Article/details/gtszykpqxb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gaohongyu789.top/Article/details/gtbwwccepb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gtdanywvsh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gtlzlkarkx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258.top/Article/details/gtsbjhkcrd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fzhhl.top/Article/details/gtrepwljih.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.redwolf501.top/Article/details/gtkgarxwfm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yueranfly.top/Article/details/gtmjabdkms.html

[B07] while 循环
来源：http://dali.yanxiufei.cn/Article/details/gtsokzgtuw.html

Py:   while i < 10: i += 1
来源：http://dali.316326.xyz/Article/details/gtdhnrdela.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.0kj1m.cn/Article/details/gtxbksdrmt.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtlfpwwhyf.html

TS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtaiwjbiaq.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmyzdrqcu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangshuangyany.cn/Article/details/gthduupbcc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gtqrkaiycm.html

C#:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtgelikwfl.html

[B08] do-while（至少执行一次）
来源：http://dali.yuanzhike.top/Article/details/gtneiiwzzy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj202588.top/Article/details/gtmhdsxfcv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtlmdbrbur.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtdvkdsdqg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtazvxcfbz.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtlivjdtqi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sxryk.cn/Article/details/gtdgfkjhry.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.redwolf501.top/Article/details/gtvqinoaii.html

C#:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtnxelpfit.html

[B09] break 与 continue
来源：http://dali.jinghuilouyu.cn/Article/details/gtmijeenbl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yanxiufei.cn/Article/details/gtporcxhej.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtaxnmuedy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtqzkqmenz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtudvwtoib.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtwylhjymt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.svipenyu.cn/Article/details/gtszdvlenu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ivvv.top/Article/details/gtcubmgstc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtctwstutj.html

[B10] 遍历同时拿索引
来源：http://dali.sxryk.cn/Article/details/gtfpnmmvke.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xziqi.cn/Article/details/gtyljmqjxo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuzkhsbph.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtgbnovdxp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtdmwoqyco.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gtwtnylgle.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jiagoushi.top/Article/details/gtsbvcnxcf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gttyhqzmxf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.bjfxy.top/Article/details/gtwpqbsmcz.html

[B11] 生成数字序列 / 区间
来源：http://dali.guowangkeji.top/Article/details/gtpiiocnnl.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gtdnlysrlj.html

PHP:  range(0, 10, 2);
来源：http://dali.9152youxi.cn/Article/details/gtwzzmfvho.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtkiwcwngf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gtlaflcflb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gzhubu.top/Article/details/gtxykrluep.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gtfmwxkzpp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xziqi.cn/Article/details/gtuezzoxcg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nwbrower.top/Article/details/gtxzvclypw.html

[B12] 跳出多层循环
来源：http://dali.wangshuangyany.cn/Article/details/gtatnnfilh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuxming.cn/Article/details/gtrbjxarpk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shuidangran.top/Article/details/gtvwnxkwri.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtaqtqppxs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gteorgjewh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtdgqhltjz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.meibo888.top/Article/details/gtcdtzutvw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxinkj.top/Article/details/gttqvupabx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gtjlktivko.html

[B13] 判断是否为数字
来源：http://dali.zhongyouzk.top/Article/details/gtmpjqolad.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gtdmyiqhei.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtocaolpar.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtmgqqrweb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gtkpwqjlny.html

Java: x instanceof Number
来源：http://dali.ybcxt.top/Article/details/gtbiaxyhqq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aizwys.cn/Article/details/gtjrchwiyd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhongyouzk.top/Article/details/gtzgajzzjh.html

C#:   x is int or double or decimal
来源：http://dali.hnxiangtu.top/Article/details/gtyuinrmpl.html

[B14] 判断值是否在集合内
来源：http://dali.yj202588.top/Article/details/gtzmlxtknz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gtffyspmxw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangshuangyany.cn/Article/details/gtanrfkyfd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gtvstfmawf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtueudohub.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gteleuzpiv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gtaqfkljuv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.smart0.xyz/Article/details/gtyygcvnkx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gthvspwbil.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gtfeciibsc.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gtibnuccgr.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gtbpuubqgb.html

JS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtaftpnpxg.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtitdwxmul.html

Java: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvdpflke.html

Go:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gthbhrylyr.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtkamlxuug.html

C#:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtorpsojrh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtztkngbqd.html

Py:   if not data: return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikkyucly.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gtsyomjavd.html

JS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gtmxdmlvly.html

TS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gtusxyvsej.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtgbcscigs.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtinfvvfgo.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gtarmffcgs.html

C#:   if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gtblpcwbhk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjklttync.html

C. 函数与作用域
来源：http://dali.hfpthk.cn/Article/details/gtieswodky.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsaysausb.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtlvzxjpxs.html

Py:   def add(a, b): return a + b
来源：http://dali.xziqi.cn/Article/details/gtcukixhme.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gttdiwtusk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtogkfuhkh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtotthdbto.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtjincohsc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shuidangran.top/Article/details/gtytefoulm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hysaishi.cn/Article/details/gtibkkpacb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtzkuqkhrs.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtrufhewxr.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gtpywxixbd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gthnelvfec.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtsvjsclfg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtrjjubbsv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenzaomai.com/Article/details/gtdtcidzhu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gtpxdssscr.html

Ruby: def greet(name = "World") = name
来源：http://dali.aizwys.cn/Article/details/gtagjdtnkk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.redwolf501.top/Article/details/gtjfyerrdj.html

[C03] 可变参数
来源：http://dali.hywenlv.cn/Article/details/gtsoctlmhn.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gtbaywotgy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gtsycrancq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtnugztrwt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtuogccysb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gtqtiuwcxh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gtilzqfqeo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jianghu66.top/Article/details/gtyajyqufw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.haohaochexian.top/Article/details/gtmfcfdsey.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gttxbeialg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuanzhike.top/Article/details/gtcpifuzzo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtfiwstmvt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtrvqakegj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtckujtfxc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.kuanghao11.cn/Article/details/gtvulzjebl.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtsrmbocse.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtpjcczhhj.html

C#:   f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtctenzjct.html

[C05] 返回多个值
来源：http://dali.daxiang520.top/Article/details/gtepmzckba.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtnuzveajl.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gtwdocxcig.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtgtutpsya.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtwosgkngp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shzxlz.cn/Article/details/gtzddwbdki.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtholvtqam.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjylgppg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fengsongda.top/Article/details/gtwtllimqs.html

[C06] 匿名函数 / lambda
来源：http://dali.haohaochexian.top/Article/details/gtrlyeyomg.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gtzylwpsqs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gthwewdgol.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnymtysg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmriqjrbg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jiagoushi.top/Article/details/gtvumwndes.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gtvbcgxrpc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtfwainmez.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gttvvvuacs.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gtazvicvpf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtvjtmvgol.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtykeorjrk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenlongwang.top/Article/details/gtqahmfuuu.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gtvaetwlvz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhengqikj.top/Article/details/gtpfxzwvdb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.smart0.xyz/Article/details/gtouxvhwsk.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuanzx.com/Article/details/gtkyyqansq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gtzjuohpay.html

[C08] 闭包
来源：http://dali.smart0.xyz/Article/details/gtjasnbkog.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gtsnawaava.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jlsjyb.cn/Article/details/gtpchgywjq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtuqjpwule.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtqvshaezy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gtmlghaamd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenjidiqi.icu/Article/details/gtiaxnkiml.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtnjkkueew.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtfnklbzce.html

[C09] 递归
来源：http://dali.zhongyouzk.top/Article/details/gttrotgqfy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtpnxwhgge.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtcijafsrm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtlvvlgcef.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtuznpjuab.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtnzoyjcrh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gtsmpzuecf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtzrsfyodd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gtnuhoncvs.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtnvrperwo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinghuilouyu.cn/Article/details/gteygkldwi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuqgivrx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gtvpzlzlvb.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtbmrfuydn.html

Java: 方法内为块级作用域
来源：http://dali.andypj.xyz/Article/details/gtbsoaehdq.html

Go:   花括号块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtfzkemuuq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.haohaochexian.top/Article/details/gtpzneupta.html

C#:   块级作用域
来源：http://dali.zycfv.cn/Article/details/gtchvcreys.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gtrgjtrjoi.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gtcoeuvtkz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtgtmrdvkt.html


<!-- 参考信息 -->