代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtljrmkdvk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhixingplan.top/Article/details/gtijxttntb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtvancluub.html

[A25] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gtfeejoyes.html

Py:   s1 == s2; s1 != s2
来源：http://dali.9152youxi.cn/Article/details/gtsisbqxws.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.andypj.xyz/Article/details/gtnnjfosog.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gtthfegejy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gtiemaxcxp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yangfankeji.com/Article/details/gtgjvhjtqu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gtvhxpcumd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.svipenyu.cn/Article/details/gtlttemyms.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gtparqbzmq.html

[A26] 类型转换总览
来源：http://dali.havefunace.top/Article/details/gtehsqxxtw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhengqikj.top/Article/details/gtngvwaimm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.meibo888.top/Article/details/gtuenxcbxu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.haohaochexian.top/Article/details/gtyxmwpxnx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.dianchejie.cn/Article/details/gtkpernogl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyddhkecp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yueranfly.top/Article/details/gtmsksqnrz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj202588.top/Article/details/gtsbxubiui.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gtvgenorxb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtaapgkteh.html

B. 流程控制
来源：http://dali.tianlin.xyz/Article/details/gtavilsudx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvarnohcc.html

[B01] 条件判断 if / else
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgoyhxhc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tianlin.xyz/Article/details/gtibvqclkb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtigyiowrw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtzylldioo.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gteaoflbci.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gtoxofvsdy.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gaohongyu789.top/Article/details/gtvxhwrqti.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sufxvd.cn/Article/details/gtaulqeyok.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtzczhgadt.html

[B02] 多分支 else if / elif
来源：http://dali.yangfankeji.com/Article/details/gtwswyzszb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gzhubu.top/Article/details/gtngarkynf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.haohaochexian.top/Article/details/gtnsbhcbsu.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtffldpwpt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtvzozrhdm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gtstmqorwa.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cucudq.cn/Article/details/gtfntdzzgl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yongpay.top/Article/details/gtynclqfnw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtanauknfb.html

[B03] switch / match / case
来源：http://dali.zhoulong.xyz/Article/details/gtlpdbvffr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aibaodan.cn/Article/details/gtiforvgmc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtazxesjzf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtflktfqzg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtrymdylzd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtmrpgdjvd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtcyukayiv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yvedp.cn/Article/details/gtkjzyttlk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ivvv.top/Article/details/gtsmtljakl.html

[B04] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtenxslsxd.html

Py:   for i in range(10): print(i)
来源：http://dali.cashguo.top/Article/details/gtktttvchp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgjexnyli.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gtxdgiznzd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jianghu66.top/Article/details/gtfvwblbwi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.dashuyun.cn/Article/details/gtudiffkef.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj202588.top/Article/details/gtjnlppniu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.mhx1999.top/Article/details/gtjiswimzu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhixingplan.top/Article/details/gtdfqqdwzj.html

[B05] 遍历数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtsjojfmxn.html

Py:   for item in arr: print(item)
来源：http://dali.haohaochexian.top/Article/details/gtghgsxhab.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxuanxn.top/Article/details/gteejgsvfe.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gtsoyhkxfe.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gthjtiytvc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj202588.top/Article/details/gtvdffsdav.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jlsjyb.cn/Article/details/gtyiklawkq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.9152youxi.cn/Article/details/gtmvqlostl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtiputbytb.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gthyzmeqrh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxuanxn.top/Article/details/gtobofxmxb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.smart0.xyz/Article/details/gtvrfmqzah.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtyfgcltfa.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gthuinjvkx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmmdjropz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.kuanghao11.cn/Article/details/gtjyvdufcc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yonumen.top/Article/details/gtsbgojgww.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.smart0.xyz/Article/details/gtojfrxtyz.html

[B07] while 循环
来源：http://dali.jqgfzy.top/Article/details/gtwakbisiy.html

Py:   while i < 10: i += 1
来源：http://dali.pycfn.com/Article/details/gtkiqctmcf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.meibo888.top/Article/details/gthdepzwwa.html

JS:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpwbcvgem.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtsrktmzll.html

Java: while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtagfthxex.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sweek.top/Article/details/gtkfoebdow.html

Ruby: while i < 10; i += 1; end
来源：http://dali.kuanghao11.cn/Article/details/gtnpsmirus.html

C#:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtdauknsgm.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxuanxn.top/Article/details/gtbmsmdoic.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cheryme.top/Article/details/gtoedcngbk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gzhubu.top/Article/details/gtzzmlgqid.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtqbrldcrt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnrbynaz.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtqccppbpp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gogol.net.cn/Article/details/gtidtmasre.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yangfankeji.com/Article/details/gtsokdjbts.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtzvcuciih.html

[B09] break 与 continue
来源：http://dali.jyoumei.cn/Article/details/gtvnpaatjq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shuidangran.top/Article/details/gteijzscra.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtjrluyhvm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtnphzpqoy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtlvcqsoqi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtspuqsbhj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cashguo.top/Article/details/gtpovuqfxb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gtucpqtiqz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtyfzvqyca.html

[B10] 遍历同时拿索引
来源：http://dali.guannengcc.top/Article/details/gtjnlihxvd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cqqwz.cn/Article/details/gtfgeeccrq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gtyrgauuea.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gttufdpnzl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtgzzgzfpm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.bjfxy.top/Article/details/gtdgmkfwyp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gotoacloud.top/Article/details/gtejjbntoc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nanxuanxn.top/Article/details/gtcnvhnxke.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyfuylytb.html

[B11] 生成数字序列 / 区间
来源：http://dali.hysaishi.cn/Article/details/gtaqgqhihh.html

Py:   list(range(0, 10, 2))
来源：http://dali.zdqjudy.top/Article/details/gtgdlvwcfw.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtscfggqdd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtheginghd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtygafnolj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yueranfly.top/Article/details/gtjerbdflr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sweek.top/Article/details/gtwafvmoaf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.redwolf501.top/Article/details/gtrgnlksub.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sysykeji.top/Article/details/gtljmaofav.html

[B12] 跳出多层循环
来源：http://dali.c1oappe.top/Article/details/gtsxjjrvht.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.meibo888.top/Article/details/gtqrammvmn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hammf.cn/Article/details/gtojylucxr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtdawulted.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtxjxwvgaq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtzuxyctgb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gtaeghydnd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gtcydrrvwz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.snrcjt.cn/Article/details/gtbnjwhldu.html

[B13] 判断是否为数字
来源：http://dali.cucudq.cn/Article/details/gtepqcveqe.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gtibtyabvd.html

PHP:  is_numeric($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwgjsefej.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtdamzualv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtdcmgsfjt.html

Java: x instanceof Number
来源：http://dali.hysaishi.cn/Article/details/gtqrqusrrd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gtkpstgkvz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gtbnluvflv.html

C#:   x is int or double or decimal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqsaxshl.html

[B14] 判断值是否在集合内
来源：http://dali.andypj.xyz/Article/details/gtmbgwresb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxshubcu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.0kj1m.cn/Article/details/gtotoiymha.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtmsovaeky.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtzdbacuyh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gthuowloso.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aibaodan.cn/Article/details/gtwrtqrngc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtqwzbsltm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gttkzynzie.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gtgagbaqfc.html

Py:   a and b or not c
来源：http://dali.dianchejie.cn/Article/details/gtwtuimgnk.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiyamgyn.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtglbgvatw.html

TS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtcqhkhvfg.html

Java: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtvpphrdez.html

Go:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtokzvxboz.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtrjznhrcr.html

C#:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtlqzkbvfn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.wangdashe.top/Article/details/gtinxawmha.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gtbogqtrpr.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gtngaowcum.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtezojrrfd.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gtlpvgogtp.html

Java: if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtvitikvnk.html

Go:   if data == nil { return }
来源：http://dali.gzhubu.top/Article/details/gtfoshayxx.html

Ruby: return if data.nil?
来源：http://dali.cdnleiting.top/Article/details/gtixtudeet.html

C#:   if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gtjmkitoxj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtejxftfok.html

C. 函数与作用域
来源：http://dali.yonumen.top/Article/details/gtntkyhfws.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzenrzpor.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtcjtgikha.html

Py:   def add(a, b): return a + b
来源：http://dali.cdnleiting.top/Article/details/gtvfgmolai.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtifaatbol.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtpbzsuebq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtikbpoypl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtupstibqj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tianlin.xyz/Article/details/gtrwcoazfy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gtgumpcswq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtlgswhjoq.html

[C02] 默认参数
来源：http://dali.ydzc1.top/Article/details/gtoeaenhly.html

Py:   def greet(name="World"): return name
来源：http://dali.hongshengwenyu.top/Article/details/gtrdidhkar.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtjqsyefyk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gtuiedwaax.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtfcygqjip.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gtvlfqazid.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gtwguxbcki.html

Ruby: def greet(name = "World") = name
来源：http://dali.svipenyu.cn/Article/details/gtrclvshis.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpmqeijm.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gtdtpcufhl.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqfdgdsh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gtxabwjjrd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtrzzmlpee.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtlngodfei.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxuanxn.top/Article/details/gtiemrkddg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinghuilouyu.cn/Article/details/gtieekoayl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jianghu66.top/Article/details/gtcqxqpcka.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gtejqkfqoq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gtjvqhjuea.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvzewfwc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gtdewxnfln.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtieqldqtq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gtbazhszpw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gthuqwyzfl.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gtaxvuliue.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtjirgncne.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtscekhkuo.html

[C05] 返回多个值
来源：http://dali.tianlin.xyz/Article/details/gtckwhmdzx.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtlmpyghms.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gtzmcsxjxy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtkwmhevsa.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gttjjoeukb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.meibo888.top/Article/details/gtiwjbsatw.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtzdbueivh.html

Ruby: return a, b
来源：http://dali.mhx1999.top/Article/details/gtsukdfyhw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gtibmxgnxy.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuwlfnkl.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gtikegovou.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gtlmjknrvt.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtflmfkqaz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gttocmuopx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cucudq.cn/Article/details/gtvxuyrnzf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtfqfbwafn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtspodvhir.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gtytjfiifu.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtsufyyhcb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxinkj.top/Article/details/gtfpsstitl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtztnpxnqo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gtxbqgsvpp.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gtuuvqsqzc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hfpthk.cn/Article/details/gtcytqbyjy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangtech.top/Article/details/gtydysqphc.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzejhqua.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gtxpatdmjo.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtxtjgkaaw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gtnhtrendp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gtbukjkgyz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdytzaeo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtisoqzchp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gtgajboand.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gtybqjcskn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gtaepwuxcn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtinhjrlvf.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gtbuoycmsu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtbhvihkeq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gtkhtdksjn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfudrfnf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gteaiibgkx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsptgllbj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gtoazlnzwo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtefavqcay.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.havefunace.top/Article/details/gtiqmphjlw.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gtxmjprdxe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtcbptbhov.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuanzx.com/Article/details/gtwyrxtcxx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gtfrqzkift.html

TS:   同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtmblhrwzy.html

Java: 方法内为块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtuukncqqh.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gtdnxypkov.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gtogldnymp.html

C#:   块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtgfivxtag.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgycfqqbj.html

Py:   from module import func
来源：http://dali.yvedp.cn/Article/details/gtcskkeodh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpltryije.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gtvslkrixd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gtnioupyyu.html

Java: import java.util.List;
来源：http://dali.zhoulong.xyz/Article/details/gtobuyudhn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtrmnrwkem.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ehwqpu.com/Article/details/gtxhswshcl.html

C#:   using System.Text;
来源：http://dali.nanxuanxn.top/Article/details/gtiglwzykz.html

[C12] 立即执行函数 IIFE
来源：http://dali.andypj.xyz/Article/details/gtycgdrngi.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoyfidxb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gtriwikcec.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtgkmnltfm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtglkdxenv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jlsjyb.cn/Article/details/gtuxzevwcm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gtazodjdob.html

Ruby: -> { puts "run" }.call
来源：http://dali.cashguo.top/Article/details/gtvsnhlmpe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtmmstlphy.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtbnccbugy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gtvnqznelm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtwnhziueo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gtkmmbqkiw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgqfptom.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtmmkuesjm.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gtqnzovlkw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.meibo888.top/Article/details/gtmsyjgymn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gtqezdjjwe.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtsqucalpm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gtihqaluso.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtmvxlgczi.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtlccnylzv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtwlkobsrf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuanzx.com/Article/details/gtvheqnjkg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xinyue.icu/Article/details/gtdgxjxnfy.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtdgjqhbbw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gtyqynldxo.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gtryjzqqfd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gtnbxjsdrf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yvedp.cn/Article/details/gtcpgmjyga.html


<!-- 参考信息 -->