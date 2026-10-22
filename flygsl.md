代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangdashe.top/Article/details/gtquauczks.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gtpbwbmdly.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gtvapktllu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hywenlv.cn/Article/details/gtnctgipdu.html

Go:   strings.TrimSpace(s)
来源：http://dali.yonumen.top/Article/details/gtbsjlouou.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.kuanghao11.cn/Article/details/gtuhzftljd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtbrqdlviq.html

[A25] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtxvmliruo.html

Py:   s1 == s2; s1 != s2
来源：http://dali.guowangkeji.top/Article/details/gteotkuvnz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinqigfzy.top/Article/details/gtvoqmzmsy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.meibo888.top/Article/details/gtxidvnlpd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zycfv.cn/Article/details/gtmiezgfjk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cqqwz.cn/Article/details/gtqvbsxkbs.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gtysemvqar.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dianchejie.cn/Article/details/gtqewqbpvr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj20258888.top/Article/details/gtaaplrrge.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gtegoewkxp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgufenzy.top/Article/details/gtjthhvgcv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hnxiangtu.top/Article/details/gtnhbuxoru.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shzxlz.cn/Article/details/gtxvpezgbn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ehwqpu.com/Article/details/gtubovxmxa.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gtexsdgoif.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hongshengwenyu.top/Article/details/gtfyieazid.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jqgufenzy.top/Article/details/gtruvqukgm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gtzyubyzlw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthnaeottj.html

B. 流程控制
来源：http://dali.gogol.net.cn/Article/details/gtxhgzqpha.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtzvviexrp.html

[B01] 条件判断 if / else
来源：http://dali.jqgfzy.top/Article/details/gtrvxnoqxv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqbyytub.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.iojbl.cn/Article/details/gtnmdwiryw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtnesnrvcv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gtitdjmotk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtmsgeyind.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhoulong.xyz/Article/details/gteqpidndj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.haohaochexian.top/Article/details/gtbvkmvecd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gthtdlnhqj.html

[B02] 多分支 else if / elif
来源：http://dali.shangyingyoupin.top/Article/details/gtmnvbjkst.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.bjfxy.top/Article/details/gtludsbamc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gogol.net.cn/Article/details/gtqafscybo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtwujkzfqk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtnttrajiz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtxpylmulw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shzxlz.cn/Article/details/gthvmmuftu.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.iojbl.cn/Article/details/gthlkgbwcz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtzgybknvn.html

[B03] switch / match / case
来源：http://dali.andypj.xyz/Article/details/gtitkyqrqw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cqqwz.cn/Article/details/gtjqxsxcbs.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtrvnvqwxo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gtrmbixnft.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtlhxhdeir.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtgabxaema.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ppjwa.cn/Article/details/gtfbrusfyz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gtycymzfkb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gtbumdyaiy.html

[B04] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtvehtveqb.html

Py:   for i in range(10): print(i)
来源：http://dali.guowangkeji.top/Article/details/gtebdnnpte.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhoulong.xyz/Article/details/gtvtgkgshv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gtadjqbprg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hfpthk.cn/Article/details/gtujzaxcif.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gzhubu.top/Article/details/gtpujsvqfp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258888.top/Article/details/gtavtzxkrq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zycfv.cn/Article/details/gthzfamoxb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yueranfly.top/Article/details/gtcbnfmstl.html

[B05] 遍历数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gtrivtlfdi.html

Py:   for item in arr: print(item)
来源：http://dali.tian-w.cn/Article/details/gtavlcsqvz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gtondindwg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigufen.top/Article/details/gtdizukiqv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gtcjwhurjc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aizwys.cn/Article/details/gtqxxsgwcb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuztnlldi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gtmcugebyq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sxryk.cn/Article/details/gtjtqnawtz.html

[B06] 遍历字典 / 对象
来源：http://dali.yuxming.cn/Article/details/gtsbawitnq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shangyingyoupin.top/Article/details/gtzuairgkm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hysaishi.cn/Article/details/gtfnbyxtlo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.316326.xyz/Article/details/gtuuyrdxqc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gteewdocrv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ppjwa.cn/Article/details/gtdqcifhiw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yanxiufei.cn/Article/details/gtcfgdzojd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenzaomai.com/Article/details/gtsshgpfqb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cqqwz.cn/Article/details/gtwthdankt.html

[B07] while 循环
来源：http://dali.shangyingyoupin.top/Article/details/gtndagdbmj.html

Py:   while i < 10: i += 1
来源：http://dali.quarkkingdee.top/Article/details/gtaiyiodoy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sysykeji.top/Article/details/gtatvkwolz.html

JS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtrdnlxmob.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtrnkypiik.html

Java: while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtvmeguepo.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yueranfly.top/Article/details/gtdhcqikkj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pycfn.com/Article/details/gtwltxeeus.html

C#:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtewelivyf.html

[B08] do-while（至少执行一次）
来源：http://dali.bjfxy.top/Article/details/gtmbjpciya.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.fengsongda.top/Article/details/gtpxjqcqcw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtxgktjgwi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtwudbabxx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtrpjvyarh.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtfavrdpns.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtubcopfde.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gtbhuwyfmy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtxwjmqwup.html

[B09] break 与 continue
来源：http://dali.aizwys.cn/Article/details/gtqfkdrxgr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ehwqpu.com/Article/details/gtwgzexecz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtdrhmnnkk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcxhqxtyg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtuwnwpsvb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsbzyfzn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.meibo888.top/Article/details/gtkdtjvatz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cqqwz.cn/Article/details/gtnjsontjz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtqysiceky.html

[B10] 遍历同时拿索引
来源：http://dali.hongshengwenyu.top/Article/details/gthmvmoznz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gtjcokmkwc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfiesyfra.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtsnviagkc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gtcmpkhlpy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gteomlqlmz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhengqikj.top/Article/details/gtsejgvlhr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yangfankeji.com/Article/details/gthqcnuhzk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daria6918.cn/Article/details/gterywtiis.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258.top/Article/details/gtdfpdjowf.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj202588.top/Article/details/gttfalikxv.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gtfodagkug.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtqdajjmvf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gtipnotzmu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtjswffqat.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cqqwz.cn/Article/details/gtfuwzmfiy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuxming.cn/Article/details/gthxpnmpaa.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.0kj1m.cn/Article/details/gttkfxzrjl.html

[B12] 跳出多层循环
来源：http://dali.0kj1m.cn/Article/details/gteoxctwin.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gtmfcckkci.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tian-w.cn/Article/details/gtzzodxbcl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxphbpozz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtlmyakrfn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtwzhxbgla.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gtoxgachxs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sxryk.cn/Article/details/gtdzttkktm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtqqcmuhcp.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqayofer.html

Py:   isinstance(x, (int, float))
来源：http://dali.c1oappe.top/Article/details/gtafomraii.html

PHP:  is_numeric($x)
来源：http://dali.havefunace.top/Article/details/gtfdgvufms.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gthjbtlpdh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtsnrvmuhu.html

Java: x instanceof Number
来源：http://dali.aibaodan.cn/Article/details/gtnhbmnomc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hfpthk.cn/Article/details/gtmbkjeaxh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gtdmcgumbv.html

C#:   x is int or double or decimal
来源：http://dali.jinqigufen.top/Article/details/gtuvkbrgms.html

[B14] 判断值是否在集合内
来源：http://dali.hysaishi.cn/Article/details/gtymhqbspg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakznpmwf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gtaioroeuf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtldatbtfg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gtkazxlxfu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gtoovxduam.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yueranfly.top/Article/details/gtphrozcsp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangdashe.top/Article/details/gtqlrrubvs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtykwesuca.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gtoocjyslz.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gtkinxsuzm.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gtiyjadoxs.html

JS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtuhqfblir.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtxwgqlrpj.html

Java: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtwezqmrso.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtpfjcbueo.html

Ruby: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtdfdorzdx.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtvmlgqhas.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yangfankeji.com/Article/details/gtokrxjkyg.html

Py:   if not data: return
来源：http://dali.xylfe.cn/Article/details/gtmquywuoi.html

PHP:  if (!$data) { return; }
来源：http://dali.dashuyun.cn/Article/details/gthimzjdwn.html

JS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtjijharpr.html

TS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtlovoabzs.html

Java: if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtvsomersx.html

Go:   if data == nil { return }
来源：http://dali.xylfe.cn/Article/details/gtymovhcwq.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gtklddvytk.html

C#:   if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtiqyyahae.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtimvrzgdo.html

C. 函数与作用域
来源：http://dali.jqgfzy.top/Article/details/gtloxsuloy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzevgtfvz.html

[C01] 定义函数
来源：http://dali.tanke756.top/Article/details/gtszcfbjta.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtzspiyyys.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtcqlkygyn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtctxnpvwh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnalwopo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvswospnu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gtfduhztis.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gtrracetga.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvoxnbyhw.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gtwpuacroj.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtitrcdrcm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtwvpkymqp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gtpnqxadma.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtxtasoxfs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gtypzqcgxz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gtmhutobwh.html

Ruby: def greet(name = "World") = name
来源：http://dali.hongshengwenyu.top/Article/details/gtqktpftnm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gtrmeskpux.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gtcizcfjma.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gtqzikqmec.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gtzjyjzhtk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtglxhkhrc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtnajqnwef.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tianlin.xyz/Article/details/gtrmmocfxl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gtkdeosuvk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtifwdcove.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtykfjruzu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gtlokmozss.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gtnlnwmyzf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtxcvlelxa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtwlimyguf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gtgujnvequ.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258.top/Article/details/gtnffpgluh.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtihquvjbv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtevrlrhwy.html

C#:   f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtckvgyehl.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gtjdzjgrpp.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gtqmveltyt.html

PHP:  return [$a, $b];
来源：http://dali.haohaochexian.top/Article/details/gtukwaxsbb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtyairjdqs.html

TS:   return { a, b };
来源：http://dali.cheryme.top/Article/details/gthtohzbpk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gtjpakspke.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhjwkeml.html

Ruby: return a, b
来源：http://dali.hysaishi.cn/Article/details/gtipwvtuul.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuanzx.com/Article/details/gtksyxhxlh.html

[C06] 匿名函数 / lambda
来源：http://dali.ybcxt.top/Article/details/gtaajygpee.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gtqfktvmmq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtnzjdgtcv.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtzystovca.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtpuivjgyg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gtdjcupofv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gotoacloud.top/Article/details/gtlmkdkjds.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gtyfefetkd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtbgecpwwm.html

[C07] 把函数作为参数传入
来源：http://dali.hnxiangtu.top/Article/details/gtwpozptxy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuetiantiany.cn/Article/details/gtqmtyrnam.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtbmvnlzvu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gtfladbros.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gtidzreqmq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.316326.xyz/Article/details/gtdbshlsny.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gtgfyxlbsr.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gtcutoabaq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gtujflpgbu.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gtflobzpbf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gttneqiyiz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtbedjuusw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtuschxnea.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtyakoxkjs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuetiantiany.cn/Article/details/gtmxhfxsbx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtwkgfwzly.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gtzcpruumh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtagipryuc.html

[C09] 递归
来源：http://dali.shuidangran.top/Article/details/gtbdlnwgif.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtoiinsaei.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtfjoihuux.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtimhfjbza.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtdggulxzv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeswckmq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnruakxn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtswtqzuiv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gtoirtasgh.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gtyjqmkqrn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhixingplan.top/Article/details/gtnzfuyzjy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yanxiufei.cn/Article/details/gttqqsucmn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtvfzpgiwb.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gtbhwsenuc.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gtybkbkqvz.html

Go:   花括号块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtnqsniowk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdvnqqak.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtavroiolo.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gtrdxslslw.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gtcgkghfzp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gtlkjkquiu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtkyemgeks.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gtcxahrvxt.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gtjylnulsu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ppjwa.cn/Article/details/gtvpuykwly.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dashuyun.cn/Article/details/gtbntdzusx.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gteqwsreaj.html

[C12] 立即执行函数 IIFE
来源：http://dali.cdnleiting.top/Article/details/gtpjiihveh.html

Py:   (lambda: print("run"))()
来源：http://dali.jinyuanbaomall.cn/Article/details/gteatvgypo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gtluuduapm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gturdcfecg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnxbybzb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gtkchtgiql.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtspbsfhsc.html

Ruby: -> { puts "run" }.call
来源：http://dali.hywenlv.cn/Article/details/gthwhfgqaq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofpsgztu.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gtgqaazdih.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tian-w.cn/Article/details/gtiasotemj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtbcnhbvqe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtbpwlnzrt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtecdkgfax.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtdziypkfn.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gtkqvmayvu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gtqffgyovj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gtwbyjwwql.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtrblooelz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gtsqvbjsxz.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtfuspqanc.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbpteirq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gtwmmvknvg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gtrbvukiaw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gtteilfgpk.html

Ruby: # 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtftpislwk.html


<!-- 参考信息 -->