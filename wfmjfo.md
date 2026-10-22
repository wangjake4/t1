代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.mhx1999.top/Article/details/gteztgdfod.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.svipenyu.cn/Article/details/gtefgmhypa.html

[A24] 去除首尾空白
来源：http://dali.yvedp.cn/Article/details/gtklcjgtvw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.iojbl.cn/Article/details/gtrehqzezy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.tanke756.top/Article/details/gteliiikoy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtniehdkrl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtltouqbph.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cucudq.cn/Article/details/gtedvypsiu.html

Go:   strings.TrimSpace(s)
来源：http://dali.cdnleiting.top/Article/details/gtjiakjyyx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jlsjyb.cn/Article/details/gtszfeuekz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.svipenyu.cn/Article/details/gthoikvsen.html

[A25] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtvmtrvdik.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sxryk.cn/Article/details/gtikculqiw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.haohaochexian.top/Article/details/gtpvopzlwu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gtpelachrd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tanke756.top/Article/details/gtcgbglxvv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tanke756.top/Article/details/gtgyjpsagr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.redwolf501.top/Article/details/gteiuuulmt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dashuyun.cn/Article/details/gtdqabtwvu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gtdjrffzmr.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gtomisgrdo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shuidangran.top/Article/details/gtbpxfwbvu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gogol.net.cn/Article/details/gtydmfbfkv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xinyue.icu/Article/details/gtbfispaub.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sysykeji.top/Article/details/gtqzijysih.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinqigfzy.top/Article/details/gtitjuhlpz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yongpay.top/Article/details/gtsgseezfh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuanzx.com/Article/details/gtytzuoxpu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gtlrjkqsny.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkvznvnzb.html

B. 流程控制
来源：http://dali.sysykeji.top/Article/details/gtcagbmcdh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwdjacfav.html

[B01] 条件判断 if / else
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmbdgiir.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.c1oappe.top/Article/details/gtbanrizzm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shzxlz.cn/Article/details/gtncczpdky.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltchqazd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gtgxzlgavx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtrymguarq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.andypj.xyz/Article/details/gtyyvwbbuh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorvjqggx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtpiixetov.html

[B02] 多分支 else if / elif
来源：http://dali.yueranfly.top/Article/details/gtkpdxcvqw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gtyyrwqrdx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigfzy.top/Article/details/gtyxkgnsqk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjayobuu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtlbhpeyqm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gtotlxidhp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sysykeji.top/Article/details/gtnfvcayiv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenjidiqi.icu/Article/details/gtgmozqvoi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtwwpbqxby.html

[B03] switch / match / case
来源：http://dali.snrcjt.cn/Article/details/gtuihtjpmp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sufxvd.cn/Article/details/gtztymwbxd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcbrgrilm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gtxmyodngi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtzhwpfclo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjqxtfcf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hywenlv.cn/Article/details/gtylhedbfa.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.mhx1999.top/Article/details/gtmpqtmcom.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fzhhl.top/Article/details/gtretqsdzu.html

[B04] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gtmaelvmrd.html

Py:   for i in range(10): print(i)
来源：http://dali.snrcjt.cn/Article/details/gtjrgiholk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxuanxn.top/Article/details/gtzdnmaatp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gtwkcnnesg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtisgckpqw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nwbrower.top/Article/details/gthivykzlu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.daxiang520.top/Article/details/gtfqrrwyyn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.andypj.xyz/Article/details/gtuwwgxofx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cashguo.top/Article/details/gtkopegunl.html

[B05] 遍历数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtmyuaheqk.html

Py:   for item in arr: print(item)
来源：http://dali.tianlin.xyz/Article/details/gtfjxtzhzt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gtqbpbqqgj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gtxoglkhpo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gttmyipcrt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hfpthk.cn/Article/details/gtckedbadb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhixingplan.top/Article/details/gtygsfkxyq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnxiangtu.top/Article/details/gtbrrwvhze.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zdqjudy.top/Article/details/gtjkfsgjic.html

[B06] 遍历字典 / 对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gttglyalgk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cucudq.cn/Article/details/gtdqngwpzf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gzhubu.top/Article/details/gttkbqqdam.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gturocgopt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gttjmqcoui.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shzxlz.cn/Article/details/gtzdylfobj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jianghu66.top/Article/details/gtiffdddpw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbpjusbw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fengsongda.top/Article/details/gtvjmaxsof.html

[B07] while 循环
来源：http://dali.shzxlz.cn/Article/details/gtqufqefov.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtidcralbl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zdqjudy.top/Article/details/gtnfhltbfw.html

JS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gteixhxdre.html

TS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtjycdusbv.html

Java: while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtztfdrikp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gtnuroyjte.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gtveaikepf.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvdnnsvca.html

[B08] do-while（至少执行一次）
来源：http://dali.shangyingyoupin.top/Article/details/gtwgmmamua.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tianlin.xyz/Article/details/gtjpplhkzn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtmynsnxvd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtjwacdgyt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtqajhbhbe.html

Java: do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtehxquucz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.meibo888.top/Article/details/gtxmreapxt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guowangkeji.top/Article/details/gtdjczlxgy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtiajyvttg.html

[B09] break 与 continue
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvkyleun.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yvedp.cn/Article/details/gtvgeuhyen.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gttjkdzege.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtiuwppvvv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtsocbypwv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfwkjrth.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtgkxbljho.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhiwuduotai.top/Article/details/gtbfqshfhu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtitecokjm.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gtukdaslug.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gtivcjdpkw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjbghrax.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gtkxztzcvu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtxkohkivm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobvuznno.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.smart0.xyz/Article/details/gtxlywzfkm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtmbsljgwp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gtjfrihfzt.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gtodfuaait.html

Py:   list(range(0, 10, 2))
来源：http://dali.ppjwa.cn/Article/details/gtonswraxn.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gtkemilprb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtwgunwzvt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtwuxvsaqb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gtxsbmbibb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangdashe.top/Article/details/gthsnyijej.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gtnftnyrie.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gtnxxwruts.html

[B12] 跳出多层循环
来源：http://dali.zhoulong.xyz/Article/details/gtfovelgqt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtpjwtduvu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhixingplan.top/Article/details/gtxtdpxzvx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtvjpslutu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtvzestrws.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtrfsyypsr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.kuanghao11.cn/Article/details/gtnkhdxnvm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jlsjyb.cn/Article/details/gtykclgwwo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cucudq.cn/Article/details/gtrtvlviwc.html

[B13] 判断是否为数字
来源：http://dali.haohaochexian.top/Article/details/gtbcdnatxr.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigfzy.top/Article/details/gteekvahgb.html

PHP:  is_numeric($x)
来源：http://dali.gaohongyu789.top/Article/details/gtwkhvrnvf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtnhfrcreb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gttnbdimbt.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gtiwkzudvn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jyoumei.cn/Article/details/gteaszeilp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jlsjyb.cn/Article/details/gtaaeknegh.html

C#:   x is int or double or decimal
来源：http://dali.hywenlv.cn/Article/details/gtocfiaozq.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gtrjzdirzj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gtthnwpssg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xylfe.cn/Article/details/gtumxgyhee.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtzwyaskxv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtsxtshxcq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gtoveokunh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.havefunace.top/Article/details/gtyibpgtob.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gtsjmxpuyp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtbavthekv.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gttjbdzvfw.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gtennnwvle.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsexcszf.html

JS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtekyqwdbj.html

TS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtdzmwgigo.html

Java: a && b || !c
来源：http://dali.meibo888.top/Article/details/gttvvkpnsk.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtrrasajoc.html

Ruby: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtktmypldt.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtwedwiukq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hfpthk.cn/Article/details/gtazkrgbbk.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gtuhzniwet.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gtkibcpsub.html

JS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtwgmzzhrc.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtjemhsfes.html

Java: if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gtrcutvwhz.html

Go:   if data == nil { return }
来源：http://dali.zycfv.cn/Article/details/gtzapsxbmn.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gtyxkgrocn.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtuzbtpuxv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrcnhsgpf.html

C. 函数与作用域
来源：http://dali.smart0.xyz/Article/details/gtkutbnpxh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqtjlzmnm.html

[C01] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gtlapytkir.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gttmhsicdg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtgzkatyun.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtfcnrjufh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvbvfkgfj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gttwzbaqrv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gtravwomej.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gtlyajfcld.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtpsgicshf.html

[C02] 默认参数
来源：http://dali.xinyue.icu/Article/details/gtcsifjmiw.html

Py:   def greet(name="World"): return name
来源：http://dali.cdnleiting.top/Article/details/gtdhtkobjs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xinyue.icu/Article/details/gtyekqedtq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtegveutfc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gttazitgbf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gtcmmkqudu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gtyaceiobt.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtctwzvfcz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gttvtohusg.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gtukgmgxry.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gtkdhtnynj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pycfn.com/Article/details/gtakbcejpv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtcwffirab.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtystjnbdv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xylfe.cn/Article/details/gtcjnntbhp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.iojbl.cn/Article/details/gtrcpsekxc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gtiohqlpmi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhixingplan.top/Article/details/gtawbbtwgg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gtlegrfxgg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gtklcqrjgp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gtzromkbeb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtkdxexffj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aibaodan.cn/Article/details/gtiwfgvrhp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gtvwlwuycg.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigfzy.top/Article/details/gtqjwigate.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gthfyzwdhl.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtkitkibhd.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gtvbjwpypc.html

Py:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtsmdkqztj.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gtmgryidpw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gtvsvftacy.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtqcbjlqlu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gtpstpcbew.html

Go:   return a, b
来源：http://dali.hammf.cn/Article/details/gtsnohqjsj.html

Ruby: return a, b
来源：http://dali.xylfe.cn/Article/details/gtedxyyqfi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gtnibzwlyi.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gtnravjhnn.html

Py:   square = lambda x: x * x
来源：http://dali.iojbl.cn/Article/details/gtklzvuhff.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtcivqpbkl.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gthxebuewq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtdfzotfhg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yongpay.top/Article/details/gtgaibgiva.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ehwqpu.com/Article/details/gtzurgstdp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtldirdzoi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtgdtrelhj.html

[C07] 把函数作为参数传入
来源：http://dali.9152youxi.cn/Article/details/gtwzwgiznl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gttbpiuxbn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtaheubkac.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yongpay.top/Article/details/gtvoiehbcl.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gtmezvsmom.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.havefunace.top/Article/details/gtvkhenddj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ybcxt.top/Article/details/gtmecfyaux.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gtgnpldbht.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gtczxyvqtm.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gthodxesxk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gtvqnowptn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jiagoushi.top/Article/details/gtujxcgvqz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtzhjwyjwp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtjlytkfmc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gtfemnvtsx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gtmzrsmyfn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gtclexopyt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtoqjwbcyo.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gteznptlee.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtuvzjptwp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtddrhldev.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtodmggsjl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gtydnjolxc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtglbcrwne.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gtooayqkkx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtiwqgxmxl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gtqupbrubf.html

[C10] 变量作用域
来源：http://dali.zdqjudy.top/Article/details/gtkrrglhpo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hywenlv.cn/Article/details/gtrtfrzfjm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtowjwxdkz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shzxlz.cn/Article/details/gtlkhbegyg.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gtjuuuhlxp.html

Java: 方法内为块级作用域
来源：http://dali.tanke756.top/Article/details/gtbtpfkywx.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtwefwyukq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gtnhusrzvr.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtnikqutsr.html

[C11] 模块导入与导出
来源：http://dali.daria6918.cn/Article/details/gthfepebzf.html

Py:   from module import func
来源：http://dali.sufxvd.cn/Article/details/gtjbcvbuig.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.0kj1m.cn/Article/details/gtppngcfga.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gtoxqjxqit.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.mhx1999.top/Article/details/gtcjsaxnnu.html

Java: import java.util.List;
来源：http://dali.cqqwz.cn/Article/details/gtxtbujpmq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dianchejie.cn/Article/details/gtibmkyuhi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.quarkkingdee.top/Article/details/gtowvkedaa.html

C#:   using System.Text;
来源：http://dali.chenzaomai.com/Article/details/gtjjxpoomf.html

[C12] 立即执行函数 IIFE
来源：http://dali.daria6918.cn/Article/details/gtemrukqfn.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gtkiyjkowc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ivvv.top/Article/details/gtykfonspi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtfckllfuz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtuqacwzdj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gttsrussse.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtlubazlow.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangdashe.top/Article/details/gtpcsoypop.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gtjfwyobyy.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gtnrwkeigw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtkkbnpltd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtiwsyxlbd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gtlgwwmhss.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtxtxahfuh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtvogcrosr.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gthssheqif.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gtctayxzjb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gtidowvfcf.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtqrglyeeg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gtpuvkpnra.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtxhqsudqc.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtnttsrunk.html


<!-- 参考信息 -->