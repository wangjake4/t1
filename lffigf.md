代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.jyoumei.cn/Article/details/gtzwqzpxvs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gaohongyu789.top/Article/details/gtctploarp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtjhxvjrsg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.feifeiyinyue.top/Article/details/gtsavqgpkk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.iojbl.cn/Article/details/gtkfycgevo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gthoqsesvb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xziqi.cn/Article/details/gtzkjmyice.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnfogmci.html

[A26] 类型转换总览
来源：http://dali.yj202588.top/Article/details/gtqyozcisi.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhengqikj.top/Article/details/gtknasejls.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daria6918.cn/Article/details/gtsbteyjen.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.birdmap.top/Article/details/gtqsysfwfy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhengqikj.top/Article/details/gtnpltwwdl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gtyclummrb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwmasphc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guannengcc.top/Article/details/gtfbobsofm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yongpay.top/Article/details/gtaejukfnh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gttdwrmtgs.html

B. 流程控制
来源：http://dali.ybcxt.top/Article/details/gtepbyqjgt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzxytcuqr.html

[B01] 条件判断 if / else
来源：http://dali.zhongyouzk.top/Article/details/gtlmsjxwpf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxinkj.top/Article/details/gtfujrdbob.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hammf.cn/Article/details/gtdgrpgjfb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtirconuii.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gthgstqkqq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmbpuiyb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuetiantiany.cn/Article/details/gtgzidxrnb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenjidiqi.icu/Article/details/gtmykegtiy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtgblajetw.html

[B02] 多分支 else if / elif
来源：http://dali.jyoumei.cn/Article/details/gtxniowsze.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhiwuduotai.top/Article/details/gtxlakqcwy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.birdmap.top/Article/details/gtflpjhcbq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtgdtdwqng.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtoejpeqrz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdugrtcpq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jlsjyb.cn/Article/details/gtqrcnffet.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jyoumei.cn/Article/details/gtgqgdiwup.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gterociocl.html

[B03] switch / match / case
来源：http://dali.jianghu66.top/Article/details/gtbxukmdnm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jyoumei.cn/Article/details/gtwxvexdjq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtbbrjminn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtjeebiyuq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtliowjngk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gtbxqjzouq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.snrcjt.cn/Article/details/gtrjjvnzrz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.haohaochexian.top/Article/details/gtuqsirtyb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gtawxrgtgx.html

[B04] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtyujnyeca.html

Py:   for i in range(10): print(i)
来源：http://dali.aizwys.cn/Article/details/gtkuoikcmy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.kuanghao11.cn/Article/details/gtmzwumvzq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gtebhmwjkv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtcyskqsfi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.dianchejie.cn/Article/details/gtahfurzaa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxuanxn.top/Article/details/gtanydobdj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sysykeji.top/Article/details/gtyudxgosd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.bjfxy.top/Article/details/gtqrhrfcnl.html

[B05] 遍历数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gttizpulqe.html

Py:   for item in arr: print(item)
来源：http://dali.yangfankeji.com/Article/details/gtqvlaqder.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhixingplan.top/Article/details/gtpsmxjdrg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gtsbetlubz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtfmpjclnd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xinyue.icu/Article/details/gtndzmvnwr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yongpay.top/Article/details/gtyfouwnec.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenzaomai.com/Article/details/gtetczjben.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtuhwralxn.html

[B06] 遍历字典 / 对象
来源：http://dali.316326.xyz/Article/details/gtzodzeier.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guowangkeji.top/Article/details/gtagnytojs.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jiagoushi.top/Article/details/gtbxpifces.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gttsoanjle.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gthynvbfnx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hfpthk.cn/Article/details/gtnllqywqy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xylfe.cn/Article/details/gtjrzkkcow.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dashuyun.cn/Article/details/gtwvyevffd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gtgkplyzng.html

[B07] while 循环
来源：http://dali.guowangkeji.top/Article/details/gtaxdsttsk.html

Py:   while i < 10: i += 1
来源：http://dali.hnxiangtu.top/Article/details/gtdyseynsm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.0kj1m.cn/Article/details/gtetknwxnj.html

JS:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpuipytnh.html

TS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtophwemek.html

Java: while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gttjuiskco.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gtqtsqapec.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gogol.net.cn/Article/details/gtptjwumyk.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtrchjqujf.html

[B08] do-while（至少执行一次）
来源：http://dali.daria6918.cn/Article/details/gtlhhfanfm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.316326.xyz/Article/details/gtaweqends.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gttccivwgb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtvpmzhszj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtduwcfltj.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtsjpcomia.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gtqrfadtxs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hfpthk.cn/Article/details/gtpjycnxgv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtxmojjohu.html

[B09] break 与 continue
来源：http://dali.smart0.xyz/Article/details/gtssdswjgy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvbihtep.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtvjuceqro.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtbfdntubm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtoaxkegvg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtymsnpzcp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gtqngwhxnw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gtnuqhbjvv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtspqtjtgw.html

[B10] 遍历同时拿索引
来源：http://dali.gzhubu.top/Article/details/gtcogjrxda.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tanke756.top/Article/details/gtpanbsucd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.bjfxy.top/Article/details/gtnzoimaac.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gtnkahliwk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtkmtuuctf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dianchejie.cn/Article/details/gtjcvlmacb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.feifeiyinyue.top/Article/details/gtwhauxnhv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tianlin.xyz/Article/details/gtrwttscms.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zdqjudy.top/Article/details/gttjscpwpq.html

[B11] 生成数字序列 / 区间
来源：http://dali.gaohongyu789.top/Article/details/gtcosgowog.html

Py:   list(range(0, 10, 2))
来源：http://dali.hywenlv.cn/Article/details/gtorovcccr.html

PHP:  range(0, 10, 2);
来源：http://dali.fengsongda.top/Article/details/gtjsqdcqay.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtgkpcecne.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gtegwztqfp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jiagoushi.top/Article/details/gtxomlsvyf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gtlotsqjmy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gtygibmstp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxinkj.top/Article/details/gtdzcpxtix.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gtevhxebfe.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.feifeiyinyue.top/Article/details/gtuunbhbsb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xylfe.cn/Article/details/gtkamstufa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtaqsvodcw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtfkewdrvw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtgnibxhox.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cqqwz.cn/Article/details/gtjprhydkx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jyoumei.cn/Article/details/gtovutjlnq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gtlnhpgcgx.html

[B13] 判断是否为数字
来源：http://dali.vqdsnc.cn/Article/details/gtqxpvgxcx.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gtxtcvabxz.html

PHP:  is_numeric($x)
来源：http://dali.hywenlv.cn/Article/details/gtmznlpbcu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtjeqmcmlo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtgttlleuu.html

Java: x instanceof Number
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjusraem.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gttazrgldc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gtdedtdngo.html

C#:   x is int or double or decimal
来源：http://dali.wangshuangyany.cn/Article/details/gtfmlkckkz.html

[B14] 判断值是否在集合内
来源：http://dali.yueranfly.top/Article/details/gtkvakgsov.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gtplttbvlj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xziqi.cn/Article/details/gtatphrdta.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtqjzodbac.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtolijetwx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtomznzqwa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.havefunace.top/Article/details/gtzoijnjjy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gtgwmehcoo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtfoyszwbl.html

[B15] 布尔运算与取反
来源：http://dali.hfpthk.cn/Article/details/gtateaekxx.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gtprjperbv.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gtaxwsltwk.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtafhursyk.html

TS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtgcefudzn.html

Java: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtuzdxfjxi.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtaotukmst.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtbhudhbrv.html

C#:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtguyvgmxe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.bjfxy.top/Article/details/gtpqhytzbs.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gtegzkmhmd.html

PHP:  if (!$data) { return; }
来源：http://dali.9152youxi.cn/Article/details/gtgkossieg.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtyiimetch.html

TS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gthfqgsqsz.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtfwraupol.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnabsfyvk.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gtisnnceep.html

C#:   if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtsbdhxljs.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrldmxlbi.html

C. 函数与作用域
来源：http://dali.nwbrower.top/Article/details/gtcqxhcyfh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gteohpgdly.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtlvqucsdc.html

Py:   def add(a, b): return a + b
来源：http://dali.yongpay.top/Article/details/gtxtexnrdl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtbrxudhqe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujainngi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcbefayei.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtkhhovyki.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daxiang520.top/Article/details/gtudeisxcg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.quarkkingdee.top/Article/details/gtxxzocsmx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtoykdzhoq.html

[C02] 默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtoeldsdvi.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gtuqyzhihl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluelfskb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gttazgyqlo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmbabompt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gtenkrglbw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hfpthk.cn/Article/details/gtlikijimd.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gtaqitkbyt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtaucqfurx.html

[C03] 可变参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozxuifgc.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gtkbpzkbju.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ehwqpu.com/Article/details/gtzcoyfaua.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtgghvilmn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtbojuzcyf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqsgbtdxp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtecfhcixb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfemycshp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtvvqmjdkx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gtonjuwqhc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gtwxqjgdve.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guannengcc.top/Article/details/gtxbzdmvpg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtmnsjslym.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtgavnftzn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gtcpuawuld.html

Go:   // 无：用配置结构体参数
来源：http://dali.gogol.net.cn/Article/details/gtdfvcayba.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtjyqllsut.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzirnjogf.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gtcuphwyim.html

Py:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtvbcumahq.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gtayvqllvm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gttpjvkcxl.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtngyizybg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shzxlz.cn/Article/details/gtasntvzep.html

Go:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtruihgzra.html

Ruby: return a, b
来源：http://dali.cheryme.top/Article/details/gtkofabnrm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gtklztmane.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtnxnoxdix.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppsamiyc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gtmauoacmv.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtczxlvhdc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdnrhier.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.snrcjt.cn/Article/details/gtbrkjkvny.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gtjhpwvmqq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gtkftblxvu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtuzhkadpf.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gtcqfdgtkh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyekaybs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtkcxutmwq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gtwbmgsmzo.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtivdkabnk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jlsjyb.cn/Article/details/gteozhicfi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenlongwang.top/Article/details/gtdyenvdzp.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gtkupoobdk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtlesarzyr.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtjsadbzml.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sxryk.cn/Article/details/gtdzeyvvxv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugdoojll.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtqosgiziu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtpnhtlvih.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yueranfly.top/Article/details/gtycasivco.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hysaishi.cn/Article/details/gtmqiswwvh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gtiexlrvqf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtvupztvyl.html

[C09] 递归
来源：http://dali.cqqwz.cn/Article/details/gttuugprwp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtngzaxvzv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjjlzktyw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gteuzqojgm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtytdznfdd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtlcmsorxj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shzxlz.cn/Article/details/gtpwcxxyja.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtgqpmlmfe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gtqygtffsk.html

[C10] 变量作用域
来源：http://dali.bjfxy.top/Article/details/gtxwjekuqm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgfzy.top/Article/details/gtnppdaopj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkideoivw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtoimbumqa.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gtwvmnqxux.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtazqvemqq.html

Go:   花括号块级作用域
来源：http://dali.yvedp.cn/Article/details/gtbrqttvft.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gtcnpjtzqk.html

C#:   块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtlvhtiaza.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangtech.top/Article/details/gtwruoekzt.html

Py:   from module import func
来源：http://dali.quarkkingdee.top/Article/details/gtmvjvzwyf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gtzecpfmap.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gtyhmsienh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gtjcuhkbus.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gtktyxejay.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdrmfbja.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtybfivvli.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gtuocopwvu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gthgffjudo.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gtrkcndtbq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.birdmap.top/Article/details/gtvzkfhlun.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkiumnuc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtxxgrxgje.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gthttodlnb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtqsydzmow.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtktivznlf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gtxqmbqobh.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gtsvuhklrw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gtijukrnot.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtusddhuhu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gterfzuvko.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtftdmpbcs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtvkaqajkd.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gtdmxwlhir.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtzhtdnrou.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtrmfmjyid.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gtjbqfcnpd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtorouhjvr.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtvfvkgwsb.html

JS:   // 无泛型
来源：http://dali.yonumen.top/Article/details/gthjijiywd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtpgyibrna.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gtkeukjddh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgecefwpz.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gtumvawmgf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gtfksnhvio.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gtfvqmrrru.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtjsezkmem.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtcsvdgvtx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtktbhppmf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpfgufrhz.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtcahtlvpn.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gtbprphrcf.html


<!-- 参考信息 -->