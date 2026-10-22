代发 wailian999

Java: String.format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtdmqephoo.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtbyreapdb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwopvzjut.html

C#:   3.14159.ToString("F2")
来源：http://dali.dianchejie.cn/Article/details/gtfoumvote.html

[A22] 获取字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtihjpzywx.html

Py:   len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gthuswtgte.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xylfe.cn/Article/details/gtqomohpyz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinghuilouyu.cn/Article/details/gtywiqjnhu.html

TS:   s.length
来源：http://dali.yj202588.top/Article/details/gtqegkohpd.html

Java: s.length()
来源：http://dali.pycfn.com/Article/details/gtnkvmfjbd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtytyapwhk.html

Ruby: s.length
来源：http://dali.vqdsnc.cn/Article/details/gtwremjoqj.html

C#:   s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtkueddodh.html

[A23] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtyezkgdtn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dianchejie.cn/Article/details/gtllxmfpoh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ivvv.top/Article/details/gtqhqfnznl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtpwxtescm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gtecdlygma.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gtgctuzdxr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.quarkkingdee.top/Article/details/gtscdgbwss.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtgjugoial.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daxiang520.top/Article/details/gtxarlurty.html

[A24] 去除首尾空白
来源：http://dali.ehwqpu.com/Article/details/gtxbvmcxne.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cqqwz.cn/Article/details/gtcjitndnd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gogol.net.cn/Article/details/gtdxvcaune.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gtvmgbmusq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tianlin.xyz/Article/details/gthekxkpto.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.birdmap.top/Article/details/gtqksrpbox.html

Go:   strings.TrimSpace(s)
来源：http://dali.sweek.top/Article/details/gtekptcroe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daxiang520.top/Article/details/gtrvhpzzri.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcjzyufj.html

[A25] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtjernvkjg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yj20258888.top/Article/details/gtwbejbluf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.havefunace.top/Article/details/gtkwykdhoh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jyoumei.cn/Article/details/gtxtzbbisb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gtfyftnvsi.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.fengsongda.top/Article/details/gtzuhnhtls.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.haohaochexian.top/Article/details/gtpdlcvvzl.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.smart0.xyz/Article/details/gtvdorcgne.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtzurnikva.html

[A26] 类型转换总览
来源：http://dali.jqgufenzy.top/Article/details/gtmqnikisa.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sweek.top/Article/details/gtdfxqjtrq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.andypj.xyz/Article/details/gttrgunqtz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgufenzy.top/Article/details/gtgfrehizb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.bjfxy.top/Article/details/gtxbpoisor.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gtcouefcsa.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xuetiantiany.cn/Article/details/gtqoluxdcw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sweek.top/Article/details/gtulubsgyu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gtpdalqhdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqnzojonr.html

B. 流程控制
来源：http://dali.guowangkeji.top/Article/details/gtjdfsluds.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtphajrcqj.html

[B01] 条件判断 if / else
来源：http://dali.hammf.cn/Article/details/gtnextiylf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinqigufen.top/Article/details/gtmjcvfiop.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.c1oappe.top/Article/details/gtuuzixvtz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtoxhzcana.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtuvoemybi.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtglmpoccr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ydzc1.top/Article/details/gtcrzpqlpd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtucdpkwuj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtrhwcplpg.html

[B02] 多分支 else if / elif
来源：http://dali.yueranfly.top/Article/details/gtktljihmk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.bjfxy.top/Article/details/gtdqersdww.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwykuziyb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtwnycdpzl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtcitnwwpg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gtpajqfexr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.iojbl.cn/Article/details/gtswmsjypp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhijiandao.cn/Article/details/gtszrtwawf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtxdvnipza.html

[B03] switch / match / case
来源：http://dali.tanke756.top/Article/details/gtohfmgmfy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yueranfly.top/Article/details/gtigbzjpwe.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gtyhduaaxe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtaxusduee.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gtxypxdsys.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtmppuuixw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hysaishi.cn/Article/details/gtwvxffqgu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.tianlin.xyz/Article/details/gtmasdberu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtmfoicgdc.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtmkivemjf.html

Py:   for i in range(10): print(i)
来源：http://dali.sufxvd.cn/Article/details/gtmbhpohyr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuxming.cn/Article/details/gtsvriwuwg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfjqffpz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tianlin.xyz/Article/details/gtbjfkfgfx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aibaodan.cn/Article/details/gtdoewrdcl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xuetiantiany.cn/Article/details/gtjohcidbc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hysaishi.cn/Article/details/gtrcgtvnbp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtguxvzxmo.html

[B05] 遍历数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtipvpyyxh.html

Py:   for item in arr: print(item)
来源：http://dali.ybcxt.top/Article/details/gtwqnvvglg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yvedp.cn/Article/details/gtudzrkjxh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guowangkeji.top/Article/details/gtftjjxslp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gtyfhyuwkj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daria6918.cn/Article/details/gtbmxyeecr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhengqikj.top/Article/details/gtgwcyndrx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangshuangyany.cn/Article/details/gtxcqrendk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtienatgfo.html

[B06] 遍历字典 / 对象
来源：http://dali.wangshuangyany.cn/Article/details/gtoisjrhlb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gogol.net.cn/Article/details/gtxwgpwasb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258.top/Article/details/gtszqtdurq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gtbivqbgbn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gtncmlmdyz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.mhx1999.top/Article/details/gtjjmoxdju.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.snrcjt.cn/Article/details/gtcbtfudox.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.0kj1m.cn/Article/details/gtdqcvnael.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nwbrower.top/Article/details/gtaehzqcxs.html

[B07] while 循环
来源：http://dali.sweek.top/Article/details/gtzxzkpwhy.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gthwscifpp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.andypj.xyz/Article/details/gtaiadukln.html

JS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtorcvprtx.html

TS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtbzzuulls.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtdsiqudnd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jianghu66.top/Article/details/gttqdgrrcy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.quarkkingdee.top/Article/details/gthaknoged.html

C#:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtzctoavlt.html

[B08] do-while（至少执行一次）
来源：http://dali.hnxiangtu.top/Article/details/gtffctneph.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sysykeji.top/Article/details/gtrftnwkkn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fzhhl.top/Article/details/gttzyxpbce.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtjemipuav.html

TS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtzuppybhd.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtqvyxkwez.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gtzsicrvvg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.9152youxi.cn/Article/details/gtkxiaayay.html

C#:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtbazptpjf.html

[B09] break 与 continue
来源：http://dali.xuanzx.com/Article/details/gtxqzgfokv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttagbfjg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gthskmzhrh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtbayjbhfq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtglhrpbck.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtwpzijbpm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yueranfly.top/Article/details/gteblqdxgl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gtocgrbwaj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtxphmndpn.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gtjzizyswx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gtkynipafn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.birdmap.top/Article/details/gtdvwsnani.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtsfndbryg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.bjfxy.top/Article/details/gtssydwcxy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ydzc1.top/Article/details/gtinekcioo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.mhx1999.top/Article/details/gtwmxlvgvo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cheryme.top/Article/details/gtoqwoybod.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daria6918.cn/Article/details/gtkysqvily.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenjidiqi.icu/Article/details/gtjrfajesn.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gtsbhuauuy.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gtclwosvrr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gtunmesyzy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtnkutvsbm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ehwqpu.com/Article/details/gtndckxhef.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hywenlv.cn/Article/details/gtamjwdwox.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gtanbwqabw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258888.top/Article/details/gtuplaazfl.html

[B12] 跳出多层循环
来源：http://dali.zdqjudy.top/Article/details/gtzuztzzsg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xinyue.icu/Article/details/gtpiurppfh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hysaishi.cn/Article/details/gtucxtvtxm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtvmcigzfq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtvpqkbizd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtjugkujju.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuxming.cn/Article/details/gtfvyabtqc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gtfyurvpqn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gtrqrzscis.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtrkajgfvj.html

Py:   isinstance(x, (int, float))
来源：http://dali.daria6918.cn/Article/details/gtrqyzerxh.html

PHP:  is_numeric($x)
来源：http://dali.yuxming.cn/Article/details/gtiwnenwjh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gtedzhpudf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtvipmpteq.html

Java: x instanceof Number
来源：http://dali.hnxiangtu.top/Article/details/gtkaizsxyv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jlsjyb.cn/Article/details/gtiihqwytm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gtidlwteix.html

C#:   x is int or double or decimal
来源：http://dali.xuanzx.com/Article/details/gtcxdlumns.html

[B14] 判断值是否在集合内
来源：http://dali.c1oappe.top/Article/details/gttmqtjdkl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangdashe.top/Article/details/gtbcuhofpm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gtmipjjrud.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gtkrbdayed.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gtzpkvxrek.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtumdswgsd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtpkocjjnm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtwmzegfpv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtlcjqpsfe.html

[B15] 布尔运算与取反
来源：http://dali.quarkkingdee.top/Article/details/gtwpxpfjpq.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gtxadnjcal.html

PHP:  $a && $b || !$c
来源：http://dali.jqgfzy.top/Article/details/gtbmvbccbf.html

JS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gturlmkwlw.html

TS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtvzvuhojt.html

Java: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtrrbgwrye.html

Go:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtcdvjjfws.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtnocrlbhn.html

C#:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtqzgjlhvl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gogol.net.cn/Article/details/gtshlcjmvj.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gttiiybovs.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gtqurfnyvz.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gtpfuojlbu.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtiknhfich.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtgmnzqdjk.html

Go:   if data == nil { return }
来源：http://dali.guowangkeji.top/Article/details/gtnccdmaaz.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gtugffrzcl.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gttmjcoyxp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtsoctnauv.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gtgorjwjla.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcjhrsyax.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtykbbddct.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtpletorde.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcctdcpwr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gthrgkxarg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtmxrvazhv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtbdveuxcp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gtobiqpxqf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangshuangyany.cn/Article/details/gtmrkpyqen.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtqkriaenp.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gtcapnrumr.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gtvtikmuzv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gtuvddfacv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtmxhgopuv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtuuurwnjw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gtpezudncq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gtbjiamjfv.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gtewzmrewx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yanxiufei.cn/Article/details/gtuouvixcq.html

[C03] 可变参数
来源：http://dali.hysaishi.cn/Article/details/gttgagyvca.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiydasid.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cashguo.top/Article/details/gtytojgnya.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gtyqodghtx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtznvxctow.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cqqwz.cn/Article/details/gttrxmguyn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258.top/Article/details/gtpoxiuaud.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gtmotbvwys.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gtgciljzhu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gtwbpihwmu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gaohongyu789.top/Article/details/gtzvbmcbtg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gtfhbhgsyk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtuvxisbhn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gtiwtfpany.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gtiqrhgehp.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gtezujlkwa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtwumbxsty.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gthszhmwvs.html

[C05] 返回多个值
来源：http://dali.haohaochexian.top/Article/details/gttqmyxfzj.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtzgtpwcwf.html

PHP:  return [$a, $b];
来源：http://dali.jiagoushi.top/Article/details/gtxdqcbwvn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gthixqfsqb.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtyurlwioq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gtnpwtywoh.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gthpwecvgb.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gteylwjufp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.quarkkingdee.top/Article/details/gtoldwamls.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtqvmvgups.html

Py:   square = lambda x: x * x
来源：http://dali.jqgufenzy.top/Article/details/gtodhaslru.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtupnturuf.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtbbartnoj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtybvnestc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigvlqpre.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtqwjngfhh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxinkj.top/Article/details/gtipgzzoqa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gthriqwdkt.html

[C07] 把函数作为参数传入
来源：http://dali.kuanghao11.cn/Article/details/gtwtqliqoc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gtjqvxlqdz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aizwys.cn/Article/details/gtcnkwhdyr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqzaeqpk.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gtzqnafskx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuitzpleh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gtetyrecwf.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gtntobvpin.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtwgnuumba.html

[C08] 闭包
来源：http://dali.cashguo.top/Article/details/gtbbiltymi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangdashe.top/Article/details/gttxlimazq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnwdfgfgf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gthhvttvxg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtmilepmpe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gthnqaczrc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hfpthk.cn/Article/details/gtayjcfmsk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtvjbtdnup.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtbnjpcfwt.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gtwbwjxmlj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtdvvakbdy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtrqgazcck.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtsspdeztx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtpfarltza.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gtbhctkhaw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtefxauxha.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtxtrjlssu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlmyjhir.html

[C10] 变量作用域
来源：http://dali.ppjwa.cn/Article/details/gtmgjfyiia.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gtepvptrmc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtetwgznbk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gtvoentatq.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gtnlxoidzy.html

Java: 方法内为块级作用域
来源：http://dali.yueranfly.top/Article/details/gtrddlhxnn.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtvkzchiqh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.birdmap.top/Article/details/gtjhhbrdqt.html

C#:   块级作用域
来源：http://dali.nwbrower.top/Article/details/gtyvvxylfp.html

[C11] 模块导入与导出
来源：http://dali.gzhubu.top/Article/details/gthwugqygg.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gthynqmcem.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtkmubwglh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gtyooogthg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yangfankeji.com/Article/details/gtqvtjonjg.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gtgcxlxgwh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxinkj.top/Article/details/gtolstppsl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gtexslmnyi.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gtvtrjczvv.html

[C12] 立即执行函数 IIFE
来源：http://dali.nwbrower.top/Article/details/gtsmemppza.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gtdblifvty.html


<!-- 参考信息 -->