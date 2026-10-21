代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.xziqi.cn/Article/details/gtlpuxxyvv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.kuanghao11.cn/Article/details/gtjsdozvyi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nwbrower.top/Article/details/gtlmkcovvd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shangyingyoupin.top/Article/details/gtsqiifzze.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yuxming.cn/Article/details/gtcyskwedz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtooalbqng.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sysykeji.top/Article/details/gtfagavncp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.c1oappe.top/Article/details/gtppsyofnb.html

[A26] 类型转换总览
来源：http://dali.hongshengwenyu.top/Article/details/gtlsbxwhoz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.aizwys.cn/Article/details/gtnewwyeum.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sysykeji.top/Article/details/gtdsybfwna.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.daxiang520.top/Article/details/gtmkiwdmzr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gaohongyu789.top/Article/details/gtvansomwg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xuetiantiany.cn/Article/details/gtlevzwypo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.fengsongda.top/Article/details/gtkrvhurwl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.mhx1999.top/Article/details/gtotcejlnw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyjpbovf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvptahdhe.html

B. 流程控制
来源：http://dali.haohaochexian.top/Article/details/gtwsfcxuyc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwukubnjd.html

[B01] 条件判断 if / else
来源：http://dali.xylfe.cn/Article/details/gtjglhkdvv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnbtlagz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxinkj.top/Article/details/gtodcvrphg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwutvgqj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtsepqyqlq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtponvzpey.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.pengpengdd.cyou/Article/details/gtblzrnbid.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yvedp.cn/Article/details/gtnvvllqid.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gtiopatfjj.html

[B02] 多分支 else if / elif
来源：http://dali.sweek.top/Article/details/gtfrznbypg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.snrcjt.cn/Article/details/gtsexiswvk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gogol.net.cn/Article/details/gtkgfuhhns.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtivhgriem.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtzayvmdkv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtyandcxea.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.redwolf501.top/Article/details/gteeuxvfvr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xuetiantiany.cn/Article/details/gtqvelabys.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtckyhfxdu.html

[B03] switch / match / case
来源：http://dali.bjfxy.top/Article/details/gtisiassjl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cucudq.cn/Article/details/gtuuqzdpam.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtztjfoerd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtbjabzijn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtohcdvbow.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtizhjywgm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.aizwys.cn/Article/details/gtdiecniyr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xuanzx.com/Article/details/gtibjcdzml.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yongpay.top/Article/details/gtnetftfmc.html

[B04] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gtxecoycbr.html

Py:   for i in range(10): print(i)
来源：http://dali.daria6918.cn/Article/details/gtiungpkqv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jqgfzy.top/Article/details/gtvatwpvpl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tianlin.xyz/Article/details/gtoejmgmfb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssovzugp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zdqjudy.top/Article/details/gtraavtbfq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxuanxn.top/Article/details/gttalmwpdc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xziqi.cn/Article/details/gtmohhuvxj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gogol.net.cn/Article/details/gtjjdicjwy.html

[B05] 遍历数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gtobdnvhrq.html

Py:   for item in arr: print(item)
来源：http://dali.shangyingyoupin.top/Article/details/gtezctwvhd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjexsmbj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gtapokskwz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gtsczprqfn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.mhx1999.top/Article/details/gtgabexbnc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tian-w.cn/Article/details/gtnfkyoguc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.316326.xyz/Article/details/gtdezjapxh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gteldehyay.html

[B06] 遍历字典 / 对象
来源：http://dali.dashuyun.cn/Article/details/gtviedbumf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yonumen.top/Article/details/gtcabeobdl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gtifqltnms.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.bjfxy.top/Article/details/gtudztcqnj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gtvyyyachq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgmcrcge.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.9152youxi.cn/Article/details/gtqttgifcx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglpdvrpv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gttgjtdqgp.html

[B07] while 循环
来源：http://dali.meibo888.top/Article/details/gtfzebmple.html

Py:   while i < 10: i += 1
来源：http://dali.hfpthk.cn/Article/details/gtfjjtrgkq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daxiang520.top/Article/details/gtfmgfwoej.html

JS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtpurhjnno.html

TS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtthqccpdh.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtmruvqlew.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aizwys.cn/Article/details/gtvmliaegb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fengsongda.top/Article/details/gtxvpaqggu.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtowpudgkx.html

[B08] do-while（至少执行一次）
来源：http://dali.haohaochexian.top/Article/details/gtgobbdcqu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gtpdsluxkg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtoukdymjg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtouyvhpal.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtqcftzlcm.html

Java: do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtigytplwj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.guannengcc.top/Article/details/gtxuqiolvq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gtnsaiqove.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtcwljoabs.html

[B09] break 与 continue
来源：http://dali.feifeiyinyue.top/Article/details/gtubrnkdmh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nwbrower.top/Article/details/gtgixalwdi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtgnzooayr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtellvbnbc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gteryjgvwk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtpnzpgyjn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafjqekvy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dianchejie.cn/Article/details/gtycmoraqx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtrrdtbdhi.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gtzugwkrdt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangtech.top/Article/details/gtywllidho.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sufxvd.cn/Article/details/gtmwdfdcsj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtjeiktvoi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtrljfvsxu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqpcchxhv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gtmaimxfmg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gtrcznqqfg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.9152youxi.cn/Article/details/gteoerutwy.html

[B11] 生成数字序列 / 区间
来源：http://dali.pengpengdd.cyou/Article/details/gtqtgbswhx.html

Py:   list(range(0, 10, 2))
来源：http://dali.meibo888.top/Article/details/gthkmlanfe.html

PHP:  range(0, 10, 2);
来源：http://dali.ivvv.top/Article/details/gtacpuxlvz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtekjsslte.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtxjldygfp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenlongwang.top/Article/details/gtcllnkryo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.snrcjt.cn/Article/details/gtbzpossqx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhixingplan.top/Article/details/gtbamghmjo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.iojbl.cn/Article/details/gtoexsvhrc.html

[B12] 跳出多层循环
来源：http://dali.sysykeji.top/Article/details/gttwyfjnmg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gtbhijnhvs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.9152youxi.cn/Article/details/gtrggzpjuf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtoeljfwbu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gthocqlmpb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtqjfzanvm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jlsjyb.cn/Article/details/gtdsnuydgy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.mhx1999.top/Article/details/gtixixpjvl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gtqaugqezo.html

[B13] 判断是否为数字
来源：http://dali.redwolf501.top/Article/details/gtuerenkql.html

Py:   isinstance(x, (int, float))
来源：http://dali.jlsjyb.cn/Article/details/gtxxqbwwjn.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gtkhmqmbiv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtdxnqeefb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gtsmgfnwwp.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gtiacmevvw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuxming.cn/Article/details/gthtspynex.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgufenzy.top/Article/details/gtbrynnedu.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gtexmstjug.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtfltmxuwq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gturydyqse.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgfzy.top/Article/details/gtjczabcsk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtmyoosrjk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtglebfhcw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gtlwdkfbly.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gotoacloud.top/Article/details/gtclmvcuiv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtkscijeiv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtxcfqzors.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gtxgmjwlqm.html

Py:   a and b or not c
来源：http://dali.zhengqikj.top/Article/details/gteumrcves.html

PHP:  $a && $b || !$c
来源：http://dali.cdnleiting.top/Article/details/gttmbbqsjr.html

JS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtvuhcdwnj.html

TS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtcnixvduc.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtiiqktmoa.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtyjmvlsod.html

Ruby: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxrjeult.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtbdxxnjed.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gtjgemsteg.html

Py:   if not data: return
来源：http://dali.hongshengwenyu.top/Article/details/gtybegehaw.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gtsjgasjwt.html

JS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtyfhfvwik.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtiamsveyw.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtkeknydrx.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gtzrrxowyk.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gtoffrvsyq.html

C#:   if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtubtxhcot.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpjxyxedq.html

C. 函数与作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclbbhmri.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtppgxoefu.html

[C01] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gtaoofzasa.html

Py:   def add(a, b): return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtvojmhqpw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtocahpbxk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtksqmjqkl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtqoloysbs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhmgmnay.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtnicrqmna.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gtbrmfewkd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtrtfxhrtz.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkqyymtv.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gtpxrpyzjf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gtkqgowbrz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbbxtkqvq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtvpdenewl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtcfowmcrh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gtvsoclduf.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gttuacvbtn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gttsedytzd.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gtwqdjflhu.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyrdcclf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangdashe.top/Article/details/gtiawuwkna.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbmkmtraz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtlkmqwiuo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gtixiktqpb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtkgcteetg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gtpexabxvx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gtnrkgzzgv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuanzhike.top/Article/details/gticnpktym.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gtvevpdxyn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gtjhbdsnvs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gtxtyiuaad.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shzxlz.cn/Article/details/gtjbnoarur.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuanzx.com/Article/details/gtqkptnzjf.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gtxqilruqc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtzqlykhqa.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtzcinehie.html

[C05] 返回多个值
来源：http://dali.yanxiufei.cn/Article/details/gtvrazmgwn.html

Py:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtmszyykxa.html

PHP:  return [$a, $b];
来源：http://dali.sysykeji.top/Article/details/gtudfmznqq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtfgwsixbq.html

TS:   return { a, b };
来源：http://dali.yuxming.cn/Article/details/gthvbeaqym.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gtmkvmqaex.html

Go:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjschdjzm.html

Ruby: return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtclmsaujs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gtudgamrqf.html

[C06] 匿名函数 / lambda
来源：http://dali.xinyue.icu/Article/details/gtkzqbgxmo.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtsszpxncn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gtaqtpujvz.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtujkbvhtf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yvedp.cn/Article/details/gtedouawau.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hfpthk.cn/Article/details/gtlyxoqcdx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dashuyun.cn/Article/details/gtwlgkkhsr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gtnootqqbd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtmlfyzvkt.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gtciexwcly.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gtnxwteimg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuanzx.com/Article/details/gtrbmocdrf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gtaqipgmlc.html

TS:   arr.map(String)
来源：http://dali.gzhubu.top/Article/details/gtspvimeyz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gtfsdmvewo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.iojbl.cn/Article/details/gtzjugigct.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gtldaocxbm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtptuhekyy.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gtgvsxqosz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gtvmofhiej.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gtrdsagvri.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipirqmpy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzxlxiezd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuanzhike.top/Article/details/gtrkxzfcmx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gtlvapnwno.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gtdxzbtdib.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtbjuietjd.html

[C09] 递归
来源：http://dali.shangyingyoupin.top/Article/details/gtedjfzzzo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtlsxetegs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtqwluxcyw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtsqdmkssm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtdedayoad.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gtyiixqzsu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gtlxonggnq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gtarxkzwfc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gtwogwnlqk.html

[C10] 变量作用域
来源：http://dali.cqqwz.cn/Article/details/gtrfmyjqpn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gtswalzvse.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gtshyfoqag.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtgjbfctcf.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtjbrbmamt.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gtloynpjic.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gteeqzvxsn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.0kj1m.cn/Article/details/gtevijfoil.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gtoivednic.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gtuinalvdx.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gteaodbumy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gthucewonb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtfcjravcf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gtosbaotza.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gtzbglyrwj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenlongwang.top/Article/details/gtnezwrmjd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gtezoplhnu.html

C#:   using System.Text;
来源：http://dali.yj202588.top/Article/details/gtgywfivkq.html

[C12] 立即执行函数 IIFE
来源：http://dali.meibo888.top/Article/details/gtymxrzgxy.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gtemfvvapf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgufenzy.top/Article/details/gtbhttrnpk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtjyinlxxd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtgodkayco.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnxiangtu.top/Article/details/gtxcjkijuq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gtggvxfglf.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtsaxphked.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuxming.cn/Article/details/gtrruogzdb.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gtugtalswb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtnmgckemc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtnmlxhjck.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtpddwygua.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtlnvmhlnn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtyqireszl.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gtoomqdhxi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gtwnvrnile.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gtegunxjzt.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gtqdddxqzo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ehwqpu.com/Article/details/gtruxfkvrj.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtepxkrfds.html

JS:   // 无泛型
来源：http://dali.yj20258.top/Article/details/gtufqymndb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gthmgpneig.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtvynpluva.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ehwqpu.com/Article/details/gtyhncbags.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gtsdsrdesc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtijwjcfae.html

[C15] 解构 / 展开参数
来源：http://dali.hnxiangtu.top/Article/details/gtjmqfljki.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gtawsaderu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gtnjbrlhif.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtikctopem.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aibaodan.cn/Article/details/gtyujfwuth.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwlimbcy.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtgeomxden.html


<!-- 参考信息 -->