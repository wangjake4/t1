代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.jianghu66.top/Article/details/gtdaffjoxj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.kuanghao11.cn/Article/details/gtagiumtuj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sxryk.cn/Article/details/gtofxlcpza.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fengsongda.top/Article/details/gtafxlgngg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cdnleiting.top/Article/details/gtvfoutsdo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj20258888.top/Article/details/gtcxrmzkjp.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yanxiufei.cn/Article/details/gtvyolvtda.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gtzrhjqmtm.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gtehlhiftj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenlongwang.top/Article/details/gtgczbeqoy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.316326.xyz/Article/details/gtugmakidf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.feifeiyinyue.top/Article/details/gtecncsetm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhijiandao.cn/Article/details/gtfbmmnqgd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gtlspcjgru.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jyoumei.cn/Article/details/gtqqgdznud.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenlongwang.top/Article/details/gtpzhirvho.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhiwuduotai.top/Article/details/gtxrzdkrfi.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzfigkfnj.html

B. 流程控制
来源：http://dali.zhengqikj.top/Article/details/gthrenxxpx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtngbavrwe.html

[B01] 条件判断 if / else
来源：http://dali.yj20258.top/Article/details/gtkjhpnpif.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenjidiqi.icu/Article/details/gthriomqyj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ivvv.top/Article/details/gtwqgoxsvb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gttgqkoiai.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtnmzemgsb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtegaczldu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.havefunace.top/Article/details/gtwykdqikf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.iojbl.cn/Article/details/gtlldtpdpv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhjfzpwo.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258888.top/Article/details/gtpxqabiev.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jlsjyb.cn/Article/details/gtqlxxayfz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.0kj1m.cn/Article/details/gtzoytassu.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gtpfgqgztq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtzuoyutkn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtikxsadye.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cucudq.cn/Article/details/gtblmzfrtu.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jlsjyb.cn/Article/details/gtyzkgcvve.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gthyygnqtp.html

[B03] switch / match / case
来源：http://dali.chenzaomai.com/Article/details/gtdneielrt.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yangfankeji.com/Article/details/gthqgambpi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gttvbztfxp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gttbsyqodl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmakfrnri.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gttdoxijsh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cucudq.cn/Article/details/gthyeztuwm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.haohaochexian.top/Article/details/gtlrcodmsj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ydzc1.top/Article/details/gtowbspeuz.html

[B04] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gtpiqysxok.html

Py:   for i in range(10): print(i)
来源：http://dali.dashuyun.cn/Article/details/gtbumqkeps.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxccohdvr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtlrwfnkgz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtalreatot.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.9152youxi.cn/Article/details/gtqamcqvjx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenlongwang.top/Article/details/gteaustiru.html

Ruby: 10.times { |i| puts i }
来源：http://dali.0kj1m.cn/Article/details/gtnetmpbug.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwahbvor.html

[B05] 遍历数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gtgdijpxkl.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfjpbjua.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gtgpytxkqk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gtugwsyklr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gtznnnfsvj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xuanzx.com/Article/details/gtvmjnhzai.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenlongwang.top/Article/details/gtnsibtbgc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gotoacloud.top/Article/details/gtudzthwme.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigufen.top/Article/details/gtlpyibtua.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gtacfznwnd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guannengcc.top/Article/details/gtainncdik.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.kuanghao11.cn/Article/details/gtakqflomp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gtiwkaztev.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangdashe.top/Article/details/gtbvwxjmcm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gtwqbjmmeb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cashguo.top/Article/details/gtykxfdzyn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yueranfly.top/Article/details/gthvsjxtox.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigufen.top/Article/details/gtcjgeqtnk.html

[B07] while 循环
来源：http://dali.shuidangran.top/Article/details/gtslmskjkf.html

Py:   while i < 10: i += 1
来源：http://dali.yonumen.top/Article/details/gtejeyplkz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.birdmap.top/Article/details/gteetcmfij.html

JS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtfgauuflw.html

TS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtdvttwsbf.html

Java: while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gthblcjlgb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sweek.top/Article/details/gtztxgcqxd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gtidbwscgn.html

C#:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gttkfpqcsb.html

[B08] do-while（至少执行一次）
来源：http://dali.9152youxi.cn/Article/details/gtnwpopkbo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dianchejie.cn/Article/details/gtkcwuhidv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtwwodrmry.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtdglgmxzr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtolotzcmb.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtlfesjxgr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.316326.xyz/Article/details/gtafqftmsm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhixingplan.top/Article/details/gtmhkzxgyo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gthjivjguy.html

[B09] break 与 continue
来源：http://dali.hnxiangtu.top/Article/details/gtnrjgzpmz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shangyingyoupin.top/Article/details/gtlahdowss.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtofqcveaw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtmoelubfn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtsqhaynqy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtgeqbtegw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtmaevgttf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gtyqagqtpi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztlrlyah.html

[B10] 遍历同时拿索引
来源：http://dali.haohaochexian.top/Article/details/gtgtmkilsj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gthhnwvqvl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgufenzy.top/Article/details/gtyzlkaejf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gtbdsqfygt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtqsoreoei.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aizwys.cn/Article/details/gthvmrbgpn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shzxlz.cn/Article/details/gtgrbjjxcb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gtddanmjce.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zdqjudy.top/Article/details/gtrfsnipet.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhengqikj.top/Article/details/gtyjfkjmue.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gtbvpjmdek.html

PHP:  range(0, 10, 2);
来源：http://dali.ydzc1.top/Article/details/gtaketcdnx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gtqtrrlwjh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtqnyqjmyl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cdnleiting.top/Article/details/gtaltkfevz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258.top/Article/details/gtqnllqwys.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhixingplan.top/Article/details/gttonsuptq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pycfn.com/Article/details/gtsiiumyzz.html

[B12] 跳出多层循环
来源：http://dali.tian-w.cn/Article/details/gtzwplsvty.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcffbkiby.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gtqegtysdq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtcfhexnjm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtodgrmglo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtpjqnghnx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.svipenyu.cn/Article/details/gtfzsdicdx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cdnleiting.top/Article/details/gtpbllgvml.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gtszulzgax.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gtbrkefojz.html

Py:   isinstance(x, (int, float))
来源：http://dali.mhx1999.top/Article/details/gtcjzpieeq.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gtsipfavsn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtwtuvnajz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqaomxtk.html

Java: x instanceof Number
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrlwhqka.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258888.top/Article/details/gtznmaskay.html

Ruby: x.is_a?(Numeric)
来源：http://dali.9152youxi.cn/Article/details/gtiylnznod.html

C#:   x is int or double or decimal
来源：http://dali.smart0.xyz/Article/details/gtgzshzxqd.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gtrdwikfsx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigfzy.top/Article/details/gtwatttoid.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gtjyjrolep.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gtchmvcchk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtibsfcgtf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtrutkynvy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.mhx1999.top/Article/details/gtivcykjli.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.meibo888.top/Article/details/gtklutrwkx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtgfglarxw.html

[B15] 布尔运算与取反
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyxdpstr.html

Py:   a and b or not c
来源：http://dali.zycfv.cn/Article/details/gtxbgaknih.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gtgrpxdmpz.html

JS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtbmtmgsxm.html

TS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtgjwjkkpk.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtyiwozytt.html

Go:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtopmfmskg.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtgbvmrivd.html

C#:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gttphbdgiv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gtbziolrkp.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gtrtxymlnx.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gtlxzhmpqo.html

JS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtwpunezus.html

TS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtkystiwlx.html

Java: if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gtctmrqqtx.html

Go:   if data == nil { return }
来源：http://dali.guowangkeji.top/Article/details/gtfsolveam.html

Ruby: return if data.nil?
来源：http://dali.daria6918.cn/Article/details/gtajeubvob.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtxtyjwfev.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpadtiubg.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnsxiibe.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtptqywkem.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtcsenlylz.html

Py:   def add(a, b): return a + b
来源：http://dali.birdmap.top/Article/details/gtirpejswa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtjcbexbjr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtzkjttvsy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtoawzptrp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtezcjpjcm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gtowwtwifx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hysaishi.cn/Article/details/gtqbhbcels.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtrtvcqunm.html

[C02] 默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtzeaysnom.html

Py:   def greet(name="World"): return name
来源：http://dali.zdqjudy.top/Article/details/gtrrimqcml.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdvgfolan.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtlngjzrcv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtbppcjjph.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.havefunace.top/Article/details/gtpofeyitj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnltpsjd.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gtwhbrzjxx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.andypj.xyz/Article/details/gtjzeqhxcm.html

[C03] 可变参数
来源：http://dali.hywenlv.cn/Article/details/gtmavoirps.html

Py:   def total(*args): return sum(args)
来源：http://dali.guannengcc.top/Article/details/gtyjowdfwy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gtqiehaahh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gtjtxjygza.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gtdynfxkil.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gtxaflqfqy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gthmveajeh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtxxcdnyux.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gtfvbffcpc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gtemdexufm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gttjvjpozm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gtcggysthp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtbmavkgzu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gtyaztdxte.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gaohongyu789.top/Article/details/gtyqilpbag.html

Go:   // 无：用配置结构体参数
来源：http://dali.nwbrower.top/Article/details/gtugwliomh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtyivwlsxe.html

C#:   f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtqubbasad.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gtdfpvuikz.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtkibcnpii.html

PHP:  return [$a, $b];
来源：http://dali.xylfe.cn/Article/details/gtongoeelq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtogdpeydm.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gthtjpuado.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gttpqddfqp.html

Go:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtxlywhplp.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gtrrzltfph.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.meibo888.top/Article/details/gtlmvqvjbe.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtnyjqqjvn.html

Py:   square = lambda x: x * x
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqczbwzwx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gtsggjmxay.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtbmguzabg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtczkuqodf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gotoacloud.top/Article/details/gtkupuxakb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gteiidwuox.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnqzz.top/Article/details/gtlheexhxh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gtnobuvpzm.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gttfrkoaji.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ybcxt.top/Article/details/gtpcnjxlfd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtzsvslgzg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gtyyejbjky.html

TS:   arr.map(String)
来源：http://dali.yuxming.cn/Article/details/gtyqtvppdi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gtlwjjwitd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gtcxciinob.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtvpwvhqkx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gtswyjxooa.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gtwlhmdmay.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gtxgahyaoq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtnvdlbkjj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtaognpdwc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtlwueuddc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gtqeszzchw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gtxcwltcat.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gteeuluzwu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpxffbyd.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gtaqggefxq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gtppwezwyk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtfugfrzla.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtnynfsuqd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtjjszdloe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fzhhl.top/Article/details/gtawaxxblt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gtcynssilp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gthjkbbecw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtxvtohzqw.html

[C10] 变量作用域
来源：http://dali.sxryk.cn/Article/details/gtdzytxmlo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtzdtyizxg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtngophhbg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gtqorvkmvg.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtqmujaory.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gtpmokmqos.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gtkrygauhm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgfzy.top/Article/details/gtokotmbch.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtqbsodley.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkozuuzsi.html

Py:   from module import func
来源：http://dali.hysaishi.cn/Article/details/gtyeekcupk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtovffqzau.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gtjjacxjww.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gtlosmtpbp.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gtnxqrpgca.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gtxejqfhcg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gtfpzueriu.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gtotatpvkp.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtdteqqhya.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtotgfagtq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gtwjdtxfve.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacbcrkoc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtsknlnojg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gtaugdtgqj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258.top/Article/details/gtsfvesxzz.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gtdphhcmau.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtrpuadrfw.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gtxnbhutev.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtfsdrxjzj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtwkoounky.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ehwqpu.com/Article/details/gtkhtotjww.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtucitmbqu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcakkivu.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gtvfqngjoe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gtwartiqgj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtytrztelw.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gtqnfkvedz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gtyzirhoge.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtnhmxbune.html

JS:   // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtnfgxtbcb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtemtaavhj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwrfhtqu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gtzhihkggd.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtaxcwgqxb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gtgbejpsdi.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtpuywegza.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gtlolzqqdh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gthvnobyld.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtubvivhdz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvfcdsaqq.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtrvqvvacm.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtbvtuaulm.html


<!-- 参考信息 -->