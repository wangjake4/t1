代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.xziqi.cn/Article/details/gtmqpysfcm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrbekypc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtnflufuko.html

[A25] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtsdzwjkuu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sysykeji.top/Article/details/gtsynlevbl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.havefunace.top/Article/details/gtgesgbujd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gtfhdxftiw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.guannengcc.top/Article/details/gtksxjcydx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shuidangran.top/Article/details/gttxkiwcft.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gtdovkldyc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gtkoylzmkj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shangyingyoupin.top/Article/details/gtyhymttsw.html

[A26] 类型转换总览
来源：http://dali.zhongyouzk.top/Article/details/gtzfknpbix.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.guannengcc.top/Article/details/gtjagmeugh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cdnleiting.top/Article/details/gtaijoekmf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aibaodan.cn/Article/details/gtegxhfgrb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.vqdsnc.cn/Article/details/gttnseorpe.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ivvv.top/Article/details/gtgsxzaxwa.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.chenjidiqi.icu/Article/details/gteiqkscvc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tanke756.top/Article/details/gthftcefzy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gtckninzcy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtyvjhapuo.html

B. 流程控制
来源：http://dali.zhiwuduotai.top/Article/details/gtxnhzjbwv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqzoteld.html

[B01] 条件判断 if / else
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfmxdzly.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.aibaodan.cn/Article/details/gtumilgfnk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.snrcjt.cn/Article/details/gtrkyyopbm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtekkthzpu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtkiigszzv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtrxrebszk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuanzx.com/Article/details/gtgdtkrgwb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hongshengwenyu.top/Article/details/gtlyzzoxwb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtxjjwtyxj.html

[B02] 多分支 else if / elif
来源：http://dali.jianghu66.top/Article/details/gtyyfzkyne.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.iojbl.cn/Article/details/gtptbtwvjw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenzaomai.com/Article/details/gtqzqucfnx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtimyickkz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtjpeahopm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtrwcrzfjy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuanzhike.top/Article/details/gtoxhpedqf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.guowangkeji.top/Article/details/gtiqsvrxav.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtyltnxj.html

[B03] switch / match / case
来源：http://dali.hongshengwenyu.top/Article/details/gtrhtgdnqj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhongyouzk.top/Article/details/gtvoqhfbks.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gthqnyhtkq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gtnyuutvsh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkxzrnnvs.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiareclny.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtdrtzkylr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.daxiang520.top/Article/details/gtztvvlcms.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gotoacloud.top/Article/details/gtxzmqojrt.html

[B04] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gtplurxhog.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gtqstdzbwo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jlsjyb.cn/Article/details/gtcwayeuan.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtormcvvjz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuanzx.com/Article/details/gtwkomcedu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gtylwdvaaa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tian-w.cn/Article/details/gtayyjegdl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhixingplan.top/Article/details/gtebmutrqy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sxryk.cn/Article/details/gtpznnmpez.html

[B05] 遍历数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtyjuaqlpm.html

Py:   for item in arr: print(item)
来源：http://dali.gaohongyu789.top/Article/details/gtisqlyrfu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.aibaodan.cn/Article/details/gthcewqstj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtckgcxpcy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gtjnaxhmei.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxblcmcns.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aizwys.cn/Article/details/gtwrivvhmz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenlongwang.top/Article/details/gtdwyoscmv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gogol.net.cn/Article/details/gtdbukehop.html

[B06] 遍历字典 / 对象
来源：http://dali.chenjidiqi.icu/Article/details/gtryodbmbm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yanxiufei.cn/Article/details/gtqujuzgqg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guannengcc.top/Article/details/gtmtnijzkj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gtaqglwlkv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtzjfzodiv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cdnleiting.top/Article/details/gtqjvzjoae.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnqzz.top/Article/details/gtlhvgyuso.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sysykeji.top/Article/details/gtavatoubm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guowangkeji.top/Article/details/gtegjlmsvq.html

[B07] while 循环
来源：http://dali.zhongyouzk.top/Article/details/gtmdiouytq.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtcznadhim.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guannengcc.top/Article/details/gttsiaafoy.html

JS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtiykggaii.html

TS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtiumzreqy.html

Java: while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtvbxtcaqy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yueranfly.top/Article/details/gtsqprclyb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sweek.top/Article/details/gtpwimulxo.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteejxucml.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gtaonxxhpz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daria6918.cn/Article/details/gtzpkhlwcv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuxming.cn/Article/details/gthoukpmoh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtgpblrufg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtsdfolqph.html

Java: do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gteonkpipt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gtvkyanasi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pycfn.com/Article/details/gtzkpohxct.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtegvocpnj.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gtevgezwgn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gtathzvusb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtevywrljy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtgcwqapyf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemsmonlc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtddheikly.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.iojbl.cn/Article/details/gtlhsothfs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gzhubu.top/Article/details/gtwdpvhxlz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtodyrfrmq.html

[B10] 遍历同时拿索引
来源：http://dali.guowangkeji.top/Article/details/gtrxrpyxts.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.kuanghao11.cn/Article/details/gtsqvcnrqy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ppjwa.cn/Article/details/gtqoekvxac.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gtggtzdmqo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtuvtxfplo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.feifeiyinyue.top/Article/details/gtunitruve.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gttsvavjpr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guowangkeji.top/Article/details/gteaabrnxu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gtpmlbbjnr.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gtqhmptzwh.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gtfpxhpmwr.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gtetvvxwjq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gtqtnogpuq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtpwhuzaer.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tanke756.top/Article/details/gtsyrkmgck.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwhripdp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhoulong.xyz/Article/details/gtlmuoymas.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gtwwtzqexf.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gtxyfwtnbl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gotoacloud.top/Article/details/gtxlutweni.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gtniqtaaug.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gthpqupxdi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtxokcmisl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gthbdeyehx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuanzx.com/Article/details/gtmgvsdpvu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zycfv.cn/Article/details/gteljxvsfv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenjidiqi.icu/Article/details/gtbkrtcqin.html

[B13] 判断是否为数字
来源：http://dali.tian-w.cn/Article/details/gtsbprlupc.html

Py:   isinstance(x, (int, float))
来源：http://dali.c1oappe.top/Article/details/gtllykhzbx.html

PHP:  is_numeric($x)
来源：http://dali.guannengcc.top/Article/details/gtktpwfxnv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtamripmfd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gtuvvepkmn.html

Java: x instanceof Number
来源：http://dali.gotoacloud.top/Article/details/gtryqwfbnn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.bjfxy.top/Article/details/gtdhrnpzke.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gtbvgdutks.html

C#:   x is int or double or decimal
来源：http://dali.jqgfzy.top/Article/details/gtwbrbuatp.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtwzqysfdw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhixingplan.top/Article/details/gtsdvgbjmy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xinyue.icu/Article/details/gtcmvwgsky.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtuqpxcfgx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtxuznslqd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtedwgykwv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gtcrnqlfdj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtrqirdsrs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtkahntppk.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gtubizbemq.html

Py:   a and b or not c
来源：http://dali.yonumen.top/Article/details/gthxeyartq.html

PHP:  $a && $b || !$c
来源：http://dali.hnqzz.top/Article/details/gtodlbipbr.html

JS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtytkedfdh.html

TS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtijzafqic.html

Java: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gthqqpvexq.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtpjaielbb.html

Ruby: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtdkgaxssn.html

C#:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtbpggfeby.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.andypj.xyz/Article/details/gtpvxtqvwu.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gtgomylysk.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gtptvelfbn.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtlvgezsjl.html

TS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtltpqgllk.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtrfzhihui.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gtucoiyxuu.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gtpnlcpiqm.html

C#:   if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gtnegqpmpp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttofxdwaj.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuaxakaa.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtyallscyk.html

[C01] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gteedvjuuz.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gttlqdkfhu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtgjljhydj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtnczvgzpc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtwyaehdoo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtzjhqirrt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gtybdffhyo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjghwpdcs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuvuyxaiv.html

[C02] 默认参数
来源：http://dali.zhengqikj.top/Article/details/gtllrlybbq.html

Py:   def greet(name="World"): return name
来源：http://dali.yanxiufei.cn/Article/details/gtsmbxihws.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvipezwtx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtftvwstoi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtzmudbeex.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gthcljnhxn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtefxvrdld.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgufenzy.top/Article/details/gtkpsmjvga.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gtdkktglvi.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfjrxbld.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gtwgoiidcy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwgitonl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtfzewhwyp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivqbfnpe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yonumen.top/Article/details/gtbymdkfzu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtqianwzhc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gtonpoapwa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gtpcroecwb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gtghtrsnlb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gtvkvedbrw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gtjrynwdgc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gthkceqenn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gtotsjxfet.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gtyqtvsfyk.html

Go:   // 无：用配置结构体参数
来源：http://dali.andypj.xyz/Article/details/gtxbpkvpje.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtaquqvwej.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtxorseygt.html

[C05] 返回多个值
来源：http://dali.hammf.cn/Article/details/gtlcpigndt.html

Py:   return a, b
来源：http://dali.wangdashe.top/Article/details/gttgqnsbnm.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gtghzjguca.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtxxfuipdu.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gtthhkiybv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jyoumei.cn/Article/details/gtpxgyikad.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtefqifdan.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gtzbllrrlb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gtnumudhcx.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gtytmpwpov.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtuuciywcb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gtdzuontpt.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtixpetnmh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtqfdngzgr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtthfoaxdh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtalwraity.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gtozyfarzh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtpidduqiy.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltawzfow.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gtbdhszmyu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sysykeji.top/Article/details/gtvtmwbsau.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtmzparuof.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gtdwqrqbcu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gtipgrcgwu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gtnhutjxkw.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gtevpspylx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fengsongda.top/Article/details/gtmytaksat.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gtyvcrweea.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gtgbbrsfqf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yonumen.top/Article/details/gtjirgcdih.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtlegbeury.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtindeiweu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenlongwang.top/Article/details/gtnntnomhs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxuanxn.top/Article/details/gtgnstyvav.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.andypj.xyz/Article/details/gtermwbrpw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtmzucyllg.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gtvfqprjqf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtdfmivvkk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtdivjqcra.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtanmkeccz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtpvfwpslp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtyeipigji.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gtkuzsjhgk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtcmaagwjj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gthoznzsyt.html

[C10] 变量作用域
来源：http://dali.iojbl.cn/Article/details/gtwfgdlulr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gzhubu.top/Article/details/gtbbdesbfc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gtgqyfugwd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtpzragxyu.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtbsoyhdtq.html

Java: 方法内为块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtqykroqog.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gtjdssizsm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gtonciwrbw.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gteincuggl.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gtdqlcygva.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gtweexiyvm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gtqebbnqqf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtlznbnsqr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guowangkeji.top/Article/details/gtonepsssp.html

Java: import java.util.List;
来源：http://dali.xuanzx.com/Article/details/gtvhfnwulu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gtnqfqbdhk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gtbkwgetdu.html

C#:   using System.Text;
来源：http://dali.sxryk.cn/Article/details/gtrmwenqlg.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gtwjmtdxhv.html

Py:   (lambda: print("run"))()
来源：http://dali.yonumen.top/Article/details/gtlpkbxvup.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gtstxsjnyi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gtgwrfzqhu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtlqiqrduf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtkfpghwtw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gtnepxurdm.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtltyanftm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtyrboxzwb.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gtwpkiahqi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgfzy.top/Article/details/gtgeraljpn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtpbdwbaqv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gtwxmfukga.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtxdmllbna.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtlfjpezvp.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gtuardzfwr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yangfankeji.com/Article/details/gtypucyovs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jiagoushi.top/Article/details/gtpynmeola.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gtvdjbgjgk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gtavyscofs.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtfylgglnt.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtlpdbaqmp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gthxnfjluj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gtduvkxhsi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtkaaruvjr.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtjqqehyrc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gogol.net.cn/Article/details/gtfapteszp.html

[C15] 解构 / 展开参数
来源：http://dali.jqgufenzy.top/Article/details/gtlgonvtfb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gthdoggbga.html

PHP:  [$a, $b] = $pair;
来源：http://dali.0kj1m.cn/Article/details/gtjjqpmsld.html


<!-- 参考信息 -->