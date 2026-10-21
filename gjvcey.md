代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvwvcaph.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.nanxuanxn.top/Article/details/gtxjsszxxm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.birdmap.top/Article/details/gtfnuqgsop.html

[A25] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtmyqurvab.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yueranfly.top/Article/details/gteuadvwyo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gteaxbnhxu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gtyjedjcrg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gotoacloud.top/Article/details/gtbvqsyhnc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.aibaodan.cn/Article/details/gtibkkofch.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gttlipxbxa.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jyoumei.cn/Article/details/gtorwcyfem.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.quarkkingdee.top/Article/details/gtfdjcpygm.html

[A26] 类型转换总览
来源：http://dali.xylfe.cn/Article/details/gtnbjnnnko.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncnswgve.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.redwolf501.top/Article/details/gtsjhsdxux.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.0kj1m.cn/Article/details/gtaaeygbom.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xinyue.icu/Article/details/gtepserxbo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shuidangran.top/Article/details/gtsmtffyna.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cucudq.cn/Article/details/gtnjlaanzt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pycfn.com/Article/details/gthleuqnio.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinqigfzy.top/Article/details/gtglegaifh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdhzltapm.html

B. 流程控制
来源：http://dali.fzhhl.top/Article/details/gtywaiidem.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsgvucbph.html

[B01] 条件判断 if / else
来源：http://dali.c1oappe.top/Article/details/gtshmcdzpc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jlsjyb.cn/Article/details/gtcgkfzqii.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtotbtxvpq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtqrmqtlkc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gttsvhtgxv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtzovmorct.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevycpnzy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.andypj.xyz/Article/details/gtgweterkj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtqoxiczag.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigfzy.top/Article/details/gtpxdracnh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yanxiufei.cn/Article/details/gthrtykqyz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sxryk.cn/Article/details/gtyglfcagx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gtrhlkvgln.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtcwluafzy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtjtapwbfe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tianlin.xyz/Article/details/gtnzkedeqe.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenjidiqi.icu/Article/details/gtrnxwqjfu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gtrnwgvpaj.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtslvksqnb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xylfe.cn/Article/details/gtdglfiadk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtcwnooyok.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtramizkcf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtethfuquw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtbfyubien.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtqrsdnpvk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fzhhl.top/Article/details/gtwyikersg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cqqwz.cn/Article/details/gtiiufdcfd.html

[B04] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gtyvrbomzs.html

Py:   for i in range(10): print(i)
来源：http://dali.jiagoushi.top/Article/details/gtdcybfnrz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.0kj1m.cn/Article/details/gtwuwgvaer.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypcnwzpd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gtefxvjfnf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hywenlv.cn/Article/details/gtcfwbbgrj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplbfyypw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnqzz.top/Article/details/gtpgqjvqnu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ybcxt.top/Article/details/gtgvyxkwus.html

[B05] 遍历数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtxxkirfbx.html

Py:   for item in arr: print(item)
来源：http://dali.jqgfzy.top/Article/details/gtojjgldeb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhongyouzk.top/Article/details/gtqckfydbn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gaohongyu789.top/Article/details/gttuzaotor.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsepywfj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daxiang520.top/Article/details/gtnpqtrzao.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbjaxcmi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.snrcjt.cn/Article/details/gtctmjeruz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenlongwang.top/Article/details/gtkcmcnasr.html

[B06] 遍历字典 / 对象
来源：http://dali.cheryme.top/Article/details/gtlcgqbylo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangdashe.top/Article/details/gtgiejsxwr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.meibo888.top/Article/details/gtwxbzcnsi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtuthvipcw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gtzzppgarl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.kuanghao11.cn/Article/details/gtmiocjnzi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guannengcc.top/Article/details/gtxcefzwgo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhixingplan.top/Article/details/gtvtaxveph.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guowangkeji.top/Article/details/gtavtfdanp.html

[B07] while 循环
来源：http://dali.yj20258888.top/Article/details/gtzbzxqprz.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtxgqncquv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtalrbvsuv.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtkytqtgqv.html

TS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtjwomlstf.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtlqfelsve.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gtxgdaaacr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.vqdsnc.cn/Article/details/gthdydsmum.html

C#:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxjztgygb.html

[B08] do-while（至少执行一次）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuhdarix.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ivvv.top/Article/details/gtnwiofpzg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtxcognrgc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtdnoefebd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtrakbqyin.html

Java: do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtyicjipta.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xylfe.cn/Article/details/gtxypbkmjk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daxiang520.top/Article/details/gtshglwvzi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtfanyyigs.html

[B09] break 与 continue
来源：http://dali.xylfe.cn/Article/details/gtghvvjerx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ybcxt.top/Article/details/gtehmcwioi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtmhlmvpnm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtrcatqfkk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtsahhjzbq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegqnocqi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258888.top/Article/details/gtejqbuwpr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgfzy.top/Article/details/gtwboebxrt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtikihelir.html

[B10] 遍历同时拿索引
来源：http://dali.zhengqikj.top/Article/details/gtfqtckiuq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtlogreyhw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nanxinkj.top/Article/details/gtzjbasxdq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gthmycojfg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtdcalvwie.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258888.top/Article/details/gtibgvnwng.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hammf.cn/Article/details/gtuuqzouaz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigufen.top/Article/details/gtfnswbkfs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yueranfly.top/Article/details/gtmztxjdiy.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gtsavyebuf.html

Py:   list(range(0, 10, 2))
来源：http://dali.cqqwz.cn/Article/details/gtzwsdjdto.html

PHP:  range(0, 10, 2);
来源：http://dali.cashguo.top/Article/details/gtmwqgrkne.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtrhnumueh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcglmjbr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gtnolslmej.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.meibo888.top/Article/details/gtcxrntbaw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cqqwz.cn/Article/details/gtqsftfocr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pycfn.com/Article/details/gtqxregkel.html

[B12] 跳出多层循环
来源：http://dali.chenlongwang.top/Article/details/gtlhxsvykk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sweek.top/Article/details/gthehccmpd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xinyue.icu/Article/details/gtamjcqgkt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtlciphmpi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtnossqpdl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtrnjhnkgq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gtqjxfxvxo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtwicwczlc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhixingplan.top/Article/details/gtfuqfoppj.html

[B13] 判断是否为数字
来源：http://dali.zhongyouzk.top/Article/details/gtbowzvvqn.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gtkkqcmyba.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gtjjfdvzia.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtuloldplg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjxffndk.html

Java: x instanceof Number
来源：http://dali.zhengqikj.top/Article/details/gtmgifmxaj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtwgobgdoo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.quarkkingdee.top/Article/details/gtnhuidxya.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtyonpmlaw.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtzgrlgwyd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gtdhjvxfpe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gtgeqiqmvc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtdxxgvqfb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtyedhjmbp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gthbbblygt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.kuanghao11.cn/Article/details/gthjxurwdb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gtnnbalxcl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchxpgsdd.html

[B15] 布尔运算与取反
来源：http://dali.jqgfzy.top/Article/details/gtedxntlse.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtgryfsfme.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gtbbnhtptg.html

JS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtkscczpyb.html

TS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtyhwmujvi.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtgfjcntpa.html

Go:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtalofsejr.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtxwmtmpad.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtuzjaqlyf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljjxsrvj.html

Py:   if not data: return
来源：http://dali.nanxuanxn.top/Article/details/gtvzhflsku.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gtqchekkbe.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtmvhrwcym.html

TS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtisqulirs.html

Java: if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gtitmjvhpb.html

Go:   if data == nil { return }
来源：http://dali.yj202588.top/Article/details/gthusuefne.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtaaoyshln.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtbkbigzqt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttanrsbbo.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtykxmbghl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtcehkrmcs.html

[C01] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtgsggahzb.html

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gtugjjuibb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdmfdxsi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdckvqldc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtfnaevnac.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtlunoqfji.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj202588.top/Article/details/gthbqousll.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gtvkohtntl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqghhjes.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gteshdfxma.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gtrifgymug.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gtjemxysni.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtkpqtdeyd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gtwpbswsab.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gtcctvowyf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gtfcpcydzw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gtukppwwii.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jlsjyb.cn/Article/details/gtzafdfsdg.html

[C03] 可变参数
来源：http://dali.zhoulong.xyz/Article/details/gtnelashwt.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gtfsbdxxmo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtbsovjmqh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtqkgxcref.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtndqcrmst.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cdnleiting.top/Article/details/gtcgzhattj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tian-w.cn/Article/details/gtqgzccnsc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gtmafbkuxj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gtiritfruw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangshuangyany.cn/Article/details/gtjdmezwmv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shzxlz.cn/Article/details/gtntrwcetk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jiagoushi.top/Article/details/gtvxcimldc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtjrsbzajo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gtytcwmugk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gteggajfrr.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtnmmzgczi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtnhcflwxc.html

C#:   f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtlfmbomnb.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gtkuqqlnqd.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtsswrdcdc.html

PHP:  return [$a, $b];
来源：http://dali.hnqzz.top/Article/details/gtzjpwhhyc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gttjdxmkbw.html

TS:   return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxswpgsp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.meibo888.top/Article/details/gtcwvsbfui.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gttpbnpqzi.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtstflvtyn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tianlin.xyz/Article/details/gtcdcxgihi.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gtgaexogqz.html

Py:   square = lambda x: x * x
来源：http://dali.redwolf501.top/Article/details/gtinrvcvay.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuxming.cn/Article/details/gtjqfzyqwq.html

JS:   const square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtzxbnmgtl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtptndsjzf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gtvkkxldxz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtpcwstiem.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gtsklyjtpw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtpeaettol.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjvwwbos.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yvedp.cn/Article/details/gtpydqtzqb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtgdjucmsu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cashguo.top/Article/details/gtipbwbcyw.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gtvhjdbpmr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gtpagtlzoi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenzaomai.com/Article/details/gttqepoxjh.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gttbocgdao.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtpdspmbew.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gttnsnlkkx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gtxcttrkmg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gtwekjdcrw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtlguexhsc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gthbocuryi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtjmenkzte.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gtybtxnujq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtmzdprjxl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiotmvpgt.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtizouuuco.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtzeudgasa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gthvswufpv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtxblyjymb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtkmpeotrl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnuwsskml.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gtlmaofiit.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtqbqcagne.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gtjzkkdudl.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gtacnoccjk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangdashe.top/Article/details/gtgjhjylhk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtmsmuwjel.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gttuqdsuiq.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gtebohzfpc.html

Java: 方法内为块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyxjrcuv.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gtaatcpjur.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hywenlv.cn/Article/details/gtisuoaohh.html

C#:   块级作用域
来源：http://dali.zycfv.cn/Article/details/gtbnzeppwj.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtypipwyri.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gtxnhzgdts.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtdoehgnnk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtywrudqmq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtljcogxdi.html

Java: import java.util.List;
来源：http://dali.yj20258.top/Article/details/gtcrklcvia.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gaohongyu789.top/Article/details/gtwkqwwjzj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gtdtygkwab.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gtmwepqguj.html

[C12] 立即执行函数 IIFE
来源：http://dali.dashuyun.cn/Article/details/gtbtmxvxde.html

Py:   (lambda: print("run"))()
来源：http://dali.redwolf501.top/Article/details/gtvmeuccoj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtxdxkrdet.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtqhcnutnn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gtdsbxjcqr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuxming.cn/Article/details/gtcjnhcbpc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gtcnfmqrpq.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymfkrcoy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtyummevyg.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gtldsddndp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hysaishi.cn/Article/details/gtftyuizko.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtxkhmfjkl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gtjdqnkkox.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtomqzvqyn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtjoulpkua.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gtxroxtjyb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxjyzckv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtwytxbklz.html

[C14] 泛型函数
来源：http://dali.ydzc1.top/Article/details/gtlqrvbwpl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gtjrynwdfn.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtbojqidil.html

JS:   // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtitrbppyr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gtkdvqtyoh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtgczvqada.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gtcgzlmpwg.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gtahrmnles.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gogol.net.cn/Article/details/gtcwgevqkx.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gtqeanyrvl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dianchejie.cn/Article/details/gtkuypalqg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gtquenulle.html


<!-- 参考信息 -->