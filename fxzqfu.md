代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.guowangkeji.top/Article/details/gtonkdvjix.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gtswpydrzw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jyoumei.cn/Article/details/gtojxubzsd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nanxinkj.top/Article/details/gtogozcgqv.html

[A26] 类型转换总览
来源：http://dali.quarkkingdee.top/Article/details/gtfxozpizu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhijiandao.cn/Article/details/gtzuhobyxa.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.aizwys.cn/Article/details/gtclhoxrch.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cucudq.cn/Article/details/gtvxzklgce.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ydzc1.top/Article/details/gtbtuujtna.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hnxiangtu.top/Article/details/gtokvzahtn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhixingplan.top/Article/details/gttckbrpyg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenzaomai.com/Article/details/gtdlnytgyy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.pycfn.com/Article/details/gtvnpeszuw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtavtyouhc.html

B. 流程控制
来源：http://dali.tianlin.xyz/Article/details/gtroxdzmqa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtogwndeez.html

[B01] 条件判断 if / else
来源：http://dali.nanxinkj.top/Article/details/gtyogzqrla.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinghuilouyu.cn/Article/details/gteqelosyk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zycfv.cn/Article/details/gtrywiuelm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtmikqdhmb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gthtigbvhn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtjiyimegd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yonumen.top/Article/details/gtjpmuxgui.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fengsongda.top/Article/details/gtfehtxmrp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gtxhfzarrk.html

[B02] 多分支 else if / elif
来源：http://dali.zhoulong.xyz/Article/details/gtsulcbczs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sweek.top/Article/details/gtersslpcl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.9152youxi.cn/Article/details/gtgipfseuj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtofmrdikg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbrrbblr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gtbxxbuxsg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shangyingyoupin.top/Article/details/gtxefxwtnn.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jqgfzy.top/Article/details/gtgogewiwh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtkrfmsqyo.html

[B03] switch / match / case
来源：http://dali.wangshuangyany.cn/Article/details/gtlscafeze.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gotoacloud.top/Article/details/gtrefbsbpw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gtelomhjri.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtqnzgdcle.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtyiwroulq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtgomlpavp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yongpay.top/Article/details/gtljthifpf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.wangshuangyany.cn/Article/details/gtstkklmtn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shangyingyoupin.top/Article/details/gtkqnzvarf.html

[B04] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gteqsoymtn.html

Py:   for i in range(10): print(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtvzjjgkpx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.haohaochexian.top/Article/details/gttzykvzlc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gthexjyjbu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gtxfxausui.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.quarkkingdee.top/Article/details/gthnivnzbi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ppjwa.cn/Article/details/gtbjxanhiu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guowangkeji.top/Article/details/gtrvvjixml.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.iojbl.cn/Article/details/gthohnmduk.html

[B05] 遍历数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtkfhljsve.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gtgiaqpkvq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhongyouzk.top/Article/details/gtdjstxyba.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gtvmwsyjqw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gttqbeffyd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daxiang520.top/Article/details/gtxtcuzdub.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gtvytdngxe.html

Ruby: arr.each { |item| puts item }
来源：http://dali.redwolf501.top/Article/details/gttmxykbpy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ivvv.top/Article/details/gtedlyxoys.html

[B06] 遍历字典 / 对象
来源：http://dali.tianlin.xyz/Article/details/gtqrsqvumt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hysaishi.cn/Article/details/gtqbwxgbab.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xylfe.cn/Article/details/gtlyccbtzv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkayrhfi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gtgidxurng.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ybcxt.top/Article/details/gtlwyvtozd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jiagoushi.top/Article/details/gtlvrxogot.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.316326.xyz/Article/details/gtqqmaqbhy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sweek.top/Article/details/gtttiudsij.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gtkqdtetrq.html

Py:   while i < 10: i += 1
来源：http://dali.316326.xyz/Article/details/gtnvfjwnjf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shzxlz.cn/Article/details/gthclzqfsc.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtysnkryhm.html

TS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtdhqfisxh.html

Java: while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gtcehxvfsb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jiagoushi.top/Article/details/gtszzialoi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yanxiufei.cn/Article/details/gtcfgcchhi.html

C#:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtdvnvzrcb.html

[B08] do-while（至少执行一次）
来源：http://dali.pycfn.com/Article/details/gtaldemdsa.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gzhubu.top/Article/details/gtdgtcezut.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdnhouyc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gthggtomjp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtydqhzeyo.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtxnvkrdpd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtozwrdwfq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gtldffkrvn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtwxizhfxi.html

[B09] break 与 continue
来源：http://dali.ybcxt.top/Article/details/gtfdtmswmo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gtyrziaspv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtyqtlodar.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtldvuyvrh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtymnrukmc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmavmerko.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gtbmcwhoeq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfpfwqjt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtuhtumqnu.html

[B10] 遍历同时拿索引
来源：http://dali.pycfn.com/Article/details/gttzdlwmsm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxuanxn.top/Article/details/gtypffdmup.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ppjwa.cn/Article/details/gtlmbwimil.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fengsongda.top/Article/details/gtmjldmscm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gtjjgenrss.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangdashe.top/Article/details/gteqrfutiz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hysaishi.cn/Article/details/gtylmvcvjy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtovlejjeb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dianchejie.cn/Article/details/gttmmbwgpg.html

[B11] 生成数字序列 / 区间
来源：http://dali.shzxlz.cn/Article/details/gtdtmqlqio.html

Py:   list(range(0, 10, 2))
来源：http://dali.zycfv.cn/Article/details/gtdmvijtoa.html

PHP:  range(0, 10, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtrgturves.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gthxsdlsbp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gtadpiybih.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ydzc1.top/Article/details/gtnhfjcdvc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.snrcjt.cn/Article/details/gtzsuiapbk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xylfe.cn/Article/details/gtncowvmqd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gtpomktcop.html

[B12] 跳出多层循环
来源：http://dali.hongshengwenyu.top/Article/details/gtzukrywur.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.quarkkingdee.top/Article/details/gtwedrdvha.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gtjnfifumv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtmqfrurdv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtsoibfrxw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gtoefeiygk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jyoumei.cn/Article/details/gtbbstiloc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuetiantiany.cn/Article/details/gtwaeprgzf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gtarmlbfun.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixjvqhto.html

Py:   isinstance(x, (int, float))
来源：http://dali.xinyue.icu/Article/details/gtmchmsnmz.html

PHP:  is_numeric($x)
来源：http://dali.xylfe.cn/Article/details/gtvpviqhja.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtyaannzkw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqgkztyz.html

Java: x instanceof Number
来源：http://dali.snrcjt.cn/Article/details/gtqcqwiaeu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gtxiiirzpe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shuidangran.top/Article/details/gttiinjnhj.html

C#:   x is int or double or decimal
来源：http://dali.hfpthk.cn/Article/details/gtbvaohgas.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gtuvmapktu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ydzc1.top/Article/details/gttcccosrt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhpsxdef.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtbpyecbxh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtrfdaflea.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yangfankeji.com/Article/details/gteegaukit.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ydzc1.top/Article/details/gtwpnigmvt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gtfjzfczkf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtwvjbgpsv.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gttwryrgas.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gtmwqkdomh.html

PHP:  $a && $b || !$c
来源：http://dali.yuxming.cn/Article/details/gtxmbnsbhx.html

JS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtmvmlanek.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtdfkbjvjy.html

Java: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtisvcnsww.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtvjidazvi.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtesmvwtln.html

C#:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtwhhkajuy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.316326.xyz/Article/details/gtxyjqlset.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gtjewhqvmn.html

PHP:  if (!$data) { return; }
来源：http://dali.yvedp.cn/Article/details/gtbfeoytyr.html

JS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gtocxmdjqa.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmkwyztz.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtehkfydip.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gttajngruj.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gtrvruofpd.html

C#:   if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gtnewxjjzz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtaunlmspv.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gttjyolnws.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtuhkigjds.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtnucnlwxy.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gteewreoct.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtzrfjoquo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtyyzyerjq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkgqvosl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtzrsxtfeg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gttkzpvrmz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gtxqxovdkr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtdvrlsnha.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gtmpkbevwj.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gtreqzqxdo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hfpthk.cn/Article/details/gtilcbdjmc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthigprsjg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtccjclrke.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtmbzntuvb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gtkycgmzqu.html

Ruby: def greet(name = "World") = name
来源：http://dali.shuidangran.top/Article/details/gtfarbtvoi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gtwtwsvlhf.html

[C03] 可变参数
来源：http://dali.chenlongwang.top/Article/details/gtfbpygdir.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gtyzrjxnkh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ydzc1.top/Article/details/gttwsikdin.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaywtciue.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtmisftoqn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gtphhzikzo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gttadfsevl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtqbmyybbp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gtaqgdpqag.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gtdakmkegs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gtrhchylai.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gtxwnxvojw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdzjwfqu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gtzvtszior.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.316326.xyz/Article/details/gtkpuelzcu.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gtlmfjdcia.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gthfqgmztg.html

C#:   f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtadwoxvwj.html

[C05] 返回多个值
来源：http://dali.nanxuanxn.top/Article/details/gterzicdzk.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtpubjbmrz.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gtdoidygwb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtztkwrapd.html

TS:   return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtbymgrrdl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gtktzuzibz.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtwjyieuzo.html

Ruby: return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvzhbkyx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gtylapktlp.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gthvvkbdjs.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gteimiufma.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gtxvhnbvji.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtvwjdmrsl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pycfn.com/Article/details/gtixabtckk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.snrcjt.cn/Article/details/gtwhbvmjkp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtnrrejygh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkeikvybu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzjdhcla.html

[C07] 把函数作为参数传入
来源：http://dali.haohaochexian.top/Article/details/gtosuzprlw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.9152youxi.cn/Article/details/gtnyltzkij.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtozmohpvn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gtfuwsgaae.html

TS:   arr.map(String)
来源：http://dali.hywenlv.cn/Article/details/gtoirdzacx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtnnuqfhxb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gthiaskeuy.html

Ruby: arr.map(&:upcase)
来源：http://dali.daxiang520.top/Article/details/gtrsglbqre.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gtcvifdbrn.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gtkqiftpvs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gtimqzwjys.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gtswuevyzm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gteudxqrbk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtxbhfpela.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gtppxamqlx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gotoacloud.top/Article/details/gtlhlfwsow.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhengqikj.top/Article/details/gtmudazdhr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtiujtrubz.html

[C09] 递归
来源：http://dali.yueranfly.top/Article/details/gtclxosjxr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtdgnlcrbi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtiigpngqu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtyhgrdryl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduupfnpo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtpsbrbuab.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gtjhuctbgy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtqvvvfkcu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shuidangran.top/Article/details/gtdadneoyg.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gtqrgmrptb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhiwuduotai.top/Article/details/gtihasbpgn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gttpvzxngq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.haohaochexian.top/Article/details/gtnhlzwjwq.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtigixxylw.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gtosbrbcfr.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtjhiduyts.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hysaishi.cn/Article/details/gttezugmzi.html

C#:   块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtnloohawh.html

[C11] 模块导入与导出
来源：http://dali.guannengcc.top/Article/details/gtxgmvbocz.html

Py:   from module import func
来源：http://dali.kuanghao11.cn/Article/details/gtwrpjwmij.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbatrueaz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gthmwylobv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gtivvzlurl.html

Java: import java.util.List;
来源：http://dali.shangyingyoupin.top/Article/details/gtdaxuajhe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.redwolf501.top/Article/details/gtibmctfjw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gtblxlgmwa.html

C#:   using System.Text;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpcovgrn.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gtlxridnnl.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gthtdmfvww.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtaqtzdtxf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtmpaeqdzg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtngbttlii.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gtdsulxtsj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gtzdktkqce.html

Ruby: -> { puts "run" }.call
来源：http://dali.smart0.xyz/Article/details/gtcbydrhlr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gttioitwac.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gthusxxdqz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigufen.top/Article/details/gtdumrbitz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtiastasmm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gtcwxkkyyw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtzarddmsw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtvlanjztc.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtvejbaobc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnbcokpp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gtkyphykfl.html

[C14] 泛型函数
来源：http://dali.ybcxt.top/Article/details/gtjrtpjmuu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shzxlz.cn/Article/details/gteruvxtap.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gtcssmwzpy.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gtieyhgtar.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gtlawoitpz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gtvaqnjlkj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gtathlxvep.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtmuvzybnr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtraneyfrc.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gtzbksmlzb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gterdsjtal.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gtywwxludj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtulgidtkc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtjshkywzq.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gtespncwfa.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtqoplqzqx.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtvhwshryv.html

C#:   var (a, b) = pair;
来源：http://dali.vqdsnc.cn/Article/details/gtzqtakktn.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gthghriecl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenlongwang.top/Article/details/gtyguarwqj.html


<!-- 参考信息 -->