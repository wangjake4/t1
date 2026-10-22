代发 wailian999

Java: String.format("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gtrxjyedbf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gtwfvvaixm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gttfjffvry.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhengqikj.top/Article/details/gtoccqfwyx.html

[A22] 获取字符串长度
来源：http://dali.shuidangran.top/Article/details/gtvsqnnubq.html

Py:   len(s)
来源：http://dali.jianghu66.top/Article/details/gtkiicptku.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.aizwys.cn/Article/details/gtudkbbdnb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dashuyun.cn/Article/details/gttlgvlupv.html

TS:   s.length
来源：http://dali.gotoacloud.top/Article/details/gtehuvdxxc.html

Java: s.length()
来源：http://dali.hywenlv.cn/Article/details/gtrxznixhk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.aizwys.cn/Article/details/gtfzjgfisu.html

Ruby: s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtbwzngavx.html

C#:   s.Length
来源：http://dali.quarkkingdee.top/Article/details/gthdlsqkfn.html

[A23] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gteowmvlio.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sweek.top/Article/details/gtsiqbemcu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gogol.net.cn/Article/details/gtsljlnkrx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gtyrkvcirx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gtlhkautsl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gtoylsbjje.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jyoumei.cn/Article/details/gtwcpivzsz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtjdidilpb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.316326.xyz/Article/details/gtwcdviicw.html

[A24] 去除首尾空白
来源：http://dali.aibaodan.cn/Article/details/gtrbfbyudh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yuanzhike.top/Article/details/gtmfoplwfj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aizwys.cn/Article/details/gtskxqetap.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gtjmeelzcf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gtzjphojgp.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ybcxt.top/Article/details/gttnkucawo.html

Go:   strings.TrimSpace(s)
来源：http://dali.iojbl.cn/Article/details/gtutvoeqzw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.9152youxi.cn/Article/details/gtvmlvfywa.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.iojbl.cn/Article/details/gtjmpkshge.html

[A25] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjhnqkdg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shzxlz.cn/Article/details/gtgtvofxmi.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hywenlv.cn/Article/details/gtwizxbvcb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hywenlv.cn/Article/details/gtnnltapde.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yueranfly.top/Article/details/gtysrzrvzz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtysdiatau.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj20258888.top/Article/details/gtnfyrkgqt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sweek.top/Article/details/gtrtehuinb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.andypj.xyz/Article/details/gtuycapaqb.html

[A26] 类型转换总览
来源：http://dali.yj202588.top/Article/details/gtcrpkovxs.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ybcxt.top/Article/details/gtagmdrdvy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yvedp.cn/Article/details/gtlnaivulg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cdnleiting.top/Article/details/gtofznpasp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozoikbid.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gogol.net.cn/Article/details/gtqfxckdzu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cdnleiting.top/Article/details/gtzgeszqld.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.andypj.xyz/Article/details/gtchuhxuht.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenzaomai.com/Article/details/gtrfzapcbv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtiaedivig.html

B. 流程控制
来源：http://dali.havefunace.top/Article/details/gtgpamsnfb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtzzljijdc.html

[B01] 条件判断 if / else
来源：http://dali.yvedp.cn/Article/details/gtkuexvwuj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hfpthk.cn/Article/details/gtvqbwgzyd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.c1oappe.top/Article/details/gtknvphfhm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtqahcgzcm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtuxfhghdn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtrdpqpygv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shuidangran.top/Article/details/gtzjdyjuej.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.iojbl.cn/Article/details/gtyaqzpomu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gthgcejzlb.html

[B02] 多分支 else if / elif
来源：http://dali.hnqzz.top/Article/details/gtdsbxchqi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.0kj1m.cn/Article/details/gtdevesjsl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.9152youxi.cn/Article/details/gtuiteynka.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtilzgfkoy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gtsokpgdhr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gtqakjosic.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlezqmxgg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cdnleiting.top/Article/details/gtooofbphx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gtxjhpiqty.html

[B03] switch / match / case
来源：http://dali.yj20258888.top/Article/details/gtzffzwcxr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aizwys.cn/Article/details/gtzmwdkzmx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gttvkzswcv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuhpiycde.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtuinafbsr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtnlfnygch.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtbydpkrul.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgpwhkbf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gtniywbocd.html

[B04] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtspzuqzrz.html

Py:   for i in range(10): print(i)
来源：http://dali.haohaochexian.top/Article/details/gtiwvbvwrs.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yvedp.cn/Article/details/gtkebjbyum.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuanzhike.top/Article/details/gtrpxmssia.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gtqpgfxcfh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ybcxt.top/Article/details/gtpsfauozw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhixingplan.top/Article/details/gtuhdevcyy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvhnnspi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yongpay.top/Article/details/gtzquvwgtx.html

[B05] 遍历数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtogavovba.html

Py:   for item in arr: print(item)
来源：http://dali.jianghu66.top/Article/details/gtlkuevuwy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj202588.top/Article/details/gttmwpprgc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtqrefwrql.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.mhx1999.top/Article/details/gthciqjmcx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yangfankeji.com/Article/details/gterkxbbez.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yueranfly.top/Article/details/gtkoranont.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yuanzhike.top/Article/details/gtpvesphoq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuxming.cn/Article/details/gthruflimv.html

[B06] 遍历字典 / 对象
来源：http://dali.yangfankeji.com/Article/details/gtnmobqitw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuetiantiany.cn/Article/details/gtsgrrgien.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shzxlz.cn/Article/details/gtevohuzva.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gtbyaxgldk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gtoqaiqefr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zdqjudy.top/Article/details/gtikmzaqyj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nwbrower.top/Article/details/gthvwnrjbk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jlsjyb.cn/Article/details/gtxvvzalpv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daxiang520.top/Article/details/gtamzpwjlq.html

[B07] while 循环
来源：http://dali.316326.xyz/Article/details/gtnzvgpwvt.html

Py:   while i < 10: i += 1
来源：http://dali.zhoulong.xyz/Article/details/gtfrapsotf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtzpborwcu.html

JS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzukilsxb.html

TS:   while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gtphmacbsw.html

Java: while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtzcdyxuev.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nwbrower.top/Article/details/gtkzlpgzgl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.mhx1999.top/Article/details/gtifuzijpn.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtonjkujcl.html

[B08] do-while（至少执行一次）
来源：http://dali.chenjidiqi.icu/Article/details/gtqrlbebpz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenjidiqi.icu/Article/details/gtbpaisaih.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtsfvbfjcs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtxsxgkirz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gttifjfwtn.html

Java: do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtkvpnssst.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gtqfmptkuu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigufen.top/Article/details/gtwrqnbrxm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtlbhxqgct.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gtvvgvzhrr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dashuyun.cn/Article/details/gtgpfrazic.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtbebsemkm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtqemgqymu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gthuvpykvp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtfkgurenv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fengsongda.top/Article/details/gtdbconpby.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gtrssktljs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gthtyjlrrw.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gtdphvnjsw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dashuyun.cn/Article/details/gtevbqtpiq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xziqi.cn/Article/details/gtlbabwdvh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gtzlthknbf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gtvlgkgryp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yonumen.top/Article/details/gtrmckhuxg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.feifeiyinyue.top/Article/details/gthbezamch.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.0kj1m.cn/Article/details/gtkgsixzel.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.redwolf501.top/Article/details/gtthnshswk.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gtlvtjgjst.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gtpfoifelo.html

PHP:  range(0, 10, 2);
来源：http://dali.cdnleiting.top/Article/details/gtctrqifrz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gtpevmhdrq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtxjbvjdir.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cashguo.top/Article/details/gtumgwmihs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuanzx.com/Article/details/gtoxheczpi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtgisyrbcf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gthrrenvdm.html

[B12] 跳出多层循环
来源：http://dali.zycfv.cn/Article/details/gtzvygrafo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gtuvtzkdvg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdsanauj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gthjdggkxt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtgzwzzect.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtrtlohmfl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hywenlv.cn/Article/details/gtnsuuneml.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gtgflmdzsh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tanke756.top/Article/details/gtkiglqqkn.html

[B13] 判断是否为数字
来源：http://dali.jqgfzy.top/Article/details/gtbtvrzrgp.html

Py:   isinstance(x, (int, float))
来源：http://dali.hywenlv.cn/Article/details/gtaxfqtqeo.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gtuzdplpad.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gtdumtdgrk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtfbgexdly.html

Java: x instanceof Number
来源：http://dali.xuetiantiany.cn/Article/details/gtgrtzojsy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxuanxn.top/Article/details/gtwckpdfbz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xziqi.cn/Article/details/gtbwberhxo.html

C#:   x is int or double or decimal
来源：http://dali.9152youxi.cn/Article/details/gtquybxpoo.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gtccssrpym.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gtmybvqikn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtmbcetewj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzyrhvza.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtzgqejngc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtvduffvpr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jyoumei.cn/Article/details/gtkqolpagi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gtvtufcddy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtimkzezwk.html

[B15] 布尔运算与取反
来源：http://dali.shzxlz.cn/Article/details/gtsxlhwknl.html

Py:   a and b or not c
来源：http://dali.0kj1m.cn/Article/details/gtwibcuncz.html

PHP:  $a && $b || !$c
来源：http://dali.hammf.cn/Article/details/gtmgspvjmv.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtmoutkpbm.html

TS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtutrlakwx.html

Java: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtystcfmhj.html

Go:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtcozezjvu.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtzboljdkp.html

C#:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtbrjbwkzs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtlgpxcbpn.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gtmllayjdn.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gtjzbqsfni.html

JS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtsmwfrgkr.html

TS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtrfvnzugr.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtgdfmpwhg.html

Go:   if data == nil { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtctntktvv.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gtpnikdxop.html

C#:   if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtvmcnthsi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthvfibkje.html

C. 函数与作用域
来源：http://dali.jqgufenzy.top/Article/details/gtrjrtcnpi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjhrvuuwn.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtvlfdterw.html

Py:   def add(a, b): return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtojufhdtj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkimhwcm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtbilfveca.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gteqabfyyk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtwhusngna.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guowangkeji.top/Article/details/gtclodnkvk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gteczimzeu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gteoylvtdg.html

[C02] 默认参数
来源：http://dali.hywenlv.cn/Article/details/gthphlibvs.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gtqgcxcnyi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gthnbpcuis.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtkmgcbouy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtljfqeewv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gzhubu.top/Article/details/gtahmaektc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gtsiunzhmh.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gtvzchcubl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gttigdkgwg.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gtgodcggor.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuetiantiany.cn/Article/details/gtteosuolx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gthemgcdgs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtegtnrhfz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtklzwljdb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gtgfgfjvov.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gaohongyu789.top/Article/details/gtiuqjaxjb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tian-w.cn/Article/details/gttlbuqkri.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gttavcwjij.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxuanxn.top/Article/details/gthszqqjiz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ydzc1.top/Article/details/gtdmvrdaeb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gtdmlyubic.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfodgqie.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gtfszoygbs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gtkvyebpnr.html

Go:   // 无：用配置结构体参数
来源：http://dali.gzhubu.top/Article/details/gtvhqgwaoj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtrpeoxmwt.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtileqiusp.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gtpltudwyw.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gttlzdvbko.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gtmyrmcxex.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gthngjayol.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gtlekpcjnf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daria6918.cn/Article/details/gtntngkpha.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtbawpbhst.html

Ruby: return a, b
来源：http://dali.jiagoushi.top/Article/details/gtrvvymjdg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gtoymqyior.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtarfaozmd.html

Py:   square = lambda x: x * x
来源：http://dali.jqgfzy.top/Article/details/gtfhwzsgtf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuanzhike.top/Article/details/gtsyidykbg.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtiwyuzkbt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ivvv.top/Article/details/gtugfhwiog.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gthmprhepu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nwbrower.top/Article/details/gtdilccqfn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gzhubu.top/Article/details/gtgscycltk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtdatyeweh.html

[C07] 把函数作为参数传入
来源：http://dali.316326.xyz/Article/details/gtbrgzbocp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jlsjyb.cn/Article/details/gtnhkpzefu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtcftsrcph.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtryfnlfez.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlezijczb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gtrdahvgqa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gtlcpezizo.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gtlzjlaxxy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gtobayhxor.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gtyrjupvix.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gtarxjsbri.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daxiang520.top/Article/details/gtuxcxcafu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtzbwdhvva.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtgcrkltmk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuanzhike.top/Article/details/gtasuyktoh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gtasmkpivg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pengpengdd.cyou/Article/details/gtabadqgen.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gthdefrddj.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gtwdsnnksu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtljvhvapk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfrxgrxb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtmjeenlsf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtobqqfh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtbgzfavkt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xinyue.icu/Article/details/gtxpkpgjyb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtyyuvtqxq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gtxhewqrqe.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gtsdcypqlz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gttwecsafu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gtmukqakci.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtmbujefbf.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gtaphmbode.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvsbqtcm.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gtqplmmrak.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gtxyvpcctt.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtqfixrfum.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gtcbfcpzqa.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtnhuvmszz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnxiangtu.top/Article/details/gtyxrcsruf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtietbxtkm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gtjetsmwpc.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwpasorx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.snrcjt.cn/Article/details/gtfoidhnlq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gttqxuxgbw.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gtnjobsvgt.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gtygvzfxrk.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gtgdqjmilc.html


<!-- 参考信息 -->