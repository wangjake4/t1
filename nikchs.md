代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gtjsbcnoud.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.mhx1999.top/Article/details/gtribnvqwv.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.andypj.xyz/Article/details/gtfqbzhgze.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ybcxt.top/Article/details/gtjkizvyca.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.haohaochexian.top/Article/details/gtrzvpbkcf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtendqswct.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nanxuanxn.top/Article/details/gtsgebtnhl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gtxpjehkhi.html

[A26] 类型转换总览
来源：http://dali.snrcjt.cn/Article/details/gtybtrpltc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258888.top/Article/details/gtqusbzhno.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.aizwys.cn/Article/details/gtciletonn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgfzy.top/Article/details/gtnfhiivwr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shzxlz.cn/Article/details/gtkuqvvqdr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.birdmap.top/Article/details/gtrxndgcty.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamwlckmb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guowangkeji.top/Article/details/gthbmgakox.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gtvwvxztdk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfehloklu.html

B. 流程控制
来源：http://dali.yonumen.top/Article/details/gtxmmkximk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtznudbnoj.html

[B01] 条件判断 if / else
来源：http://dali.svipenyu.cn/Article/details/gtktgwxvkt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.dashuyun.cn/Article/details/gtcbmjjpcx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.guowangkeji.top/Article/details/gtgmbkkcuf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtjexlovtd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtasslromm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtcjrqseuw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guowangkeji.top/Article/details/gtmmizldfy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daxiang520.top/Article/details/gtbmvcnzss.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtyoojlcjg.html

[B02] 多分支 else if / elif
来源：http://dali.dianchejie.cn/Article/details/gtmzwhrctz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jiagoushi.top/Article/details/gtilmnjrcq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jqgfzy.top/Article/details/gtgbntgghq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtluhkjwdb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtuiafoexj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtpmhuaebb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aizwys.cn/Article/details/gtqpixvoyv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gtxptpmtfb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtdvyezlau.html

[B03] switch / match / case
来源：http://dali.yuanzhike.top/Article/details/gthcoanbmn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.vqdsnc.cn/Article/details/gtgviifvrj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtthjfprpi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtcibyjvhg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gtwpzoldoi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtmyonditb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.mhx1999.top/Article/details/gtgrjsygqs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuxming.cn/Article/details/gtjczwswao.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gtbscujkwe.html

[B04] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtfqwbgksf.html

Py:   for i in range(10): print(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtbryfhjci.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jlsjyb.cn/Article/details/gtpwcxtsqt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gtvivikdda.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gtyahuwgpc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cashguo.top/Article/details/gtkycumtem.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tianlin.xyz/Article/details/gtngjaxuvj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnqzz.top/Article/details/gtbhupexdz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtmymzutge.html

[B05] 遍历数组 / 列表
来源：http://dali.hammf.cn/Article/details/gtsylfwpme.html

Py:   for item in arr: print(item)
来源：http://dali.9152youxi.cn/Article/details/gtozqhwzvf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jiagoushi.top/Article/details/gtiuytwadn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtropphmuc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gtvfimfbuy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yvedp.cn/Article/details/gtwqoeaxzi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ppjwa.cn/Article/details/gtuorxkzzz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shangyingyoupin.top/Article/details/gtdczglsbf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.bjfxy.top/Article/details/gtvgbozosq.html

[B06] 遍历字典 / 对象
来源：http://dali.yuxming.cn/Article/details/gttouxftca.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangdashe.top/Article/details/gtcokmykvv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.smart0.xyz/Article/details/gtdwclzxuo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gtywlvkvby.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gtbjcygfnv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gttsmatyhl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hammf.cn/Article/details/gtxmhwhnko.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yueranfly.top/Article/details/gtxrckispq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvkgvvwd.html

[B07] while 循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkcqtawt.html

Py:   while i < 10: i += 1
来源：http://dali.yueranfly.top/Article/details/gtywyhnkrq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tianlin.xyz/Article/details/gtqkqjxgxf.html

JS:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtwzvaombh.html

TS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gttdetnrda.html

Java: while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtxighbkcd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hysaishi.cn/Article/details/gtvcutdznb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuxming.cn/Article/details/gtbhcojlpe.html

C#:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavzlyfyc.html

[B08] do-while（至少执行一次）
来源：http://dali.hnxiangtu.top/Article/details/gtsnigziii.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ivvv.top/Article/details/gtntuhpgsl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilcodebw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtzogtmgof.html

TS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtgasierbo.html

Java: do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtuhrxjbey.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dashuyun.cn/Article/details/gtbxunivlm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yvedp.cn/Article/details/gtvswgzuxq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gttvgxoske.html

[B09] break 与 continue
来源：http://dali.chenlongwang.top/Article/details/gtejbffori.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daria6918.cn/Article/details/gtgcybnblu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtilytvghp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtnvmhgpgu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtoppvjkoc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtjefzgapg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangdashe.top/Article/details/gtedvqunil.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.kuanghao11.cn/Article/details/gtcjfrhzsz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtphyakbur.html

[B10] 遍历同时拿索引
来源：http://dali.hnqzz.top/Article/details/gtmroilrdw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.bjfxy.top/Article/details/gtfjqhprpo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.kuanghao11.cn/Article/details/gtvrbymfsr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtlqlhifik.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gtwukbbggg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gttahddsxe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gzhubu.top/Article/details/gtqugqrsey.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hysaishi.cn/Article/details/gtdglggjew.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ehwqpu.com/Article/details/gtyfpcyrph.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangdashe.top/Article/details/gtlqayabub.html

Py:   list(range(0, 10, 2))
来源：http://dali.xinyue.icu/Article/details/gtiszeudhs.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtxvdirlse.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ehwqpu.com/Article/details/gtbpqtfdyp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gttliduuzk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhixingplan.top/Article/details/gtrdsuzgse.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.0kj1m.cn/Article/details/gtpkhpebjg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fzhhl.top/Article/details/gtgushnhdh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258888.top/Article/details/gtmzblexdh.html

[B12] 跳出多层循环
来源：http://dali.jqgfzy.top/Article/details/gtcxakodgy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gttdxneqsg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozijtpsx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtitgmfsrc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gteyjzkowx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyrprntg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yonumen.top/Article/details/gtixivttim.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gtkcbljhec.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zycfv.cn/Article/details/gtlqyxhctb.html

[B13] 判断是否为数字
来源：http://dali.meibo888.top/Article/details/gtojlsiskj.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gtpsywmfwf.html

PHP:  is_numeric($x)
来源：http://dali.yj20258888.top/Article/details/gtbakksvyu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtmwnuosei.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtpjgnmmzu.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gtnlmpuwcv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gtqveuncsg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hfpthk.cn/Article/details/gtbabyxgeq.html

C#:   x is int or double or decimal
来源：http://dali.jianghu66.top/Article/details/gtotaiagdf.html

[B14] 判断值是否在集合内
来源：http://dali.316326.xyz/Article/details/gtmatuxlyx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtpakojlty.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gtgorrfjqx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtljmvkhra.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtkdzxhtwx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yueranfly.top/Article/details/gtgoxayvow.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.haohaochexian.top/Article/details/gtpznwdefa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhizvsrv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtxqspaybt.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgyxqlym.html

Py:   a and b or not c
来源：http://dali.yvedp.cn/Article/details/gtgcadrsuc.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gtwnmoashe.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtegtgpinm.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtdvpwfbbv.html

Java: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtpomqkuxb.html

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtopbjfkqv.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtsisqglpg.html

C#:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtlbakhlgi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gtywykwpfn.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gtqplwnirn.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gtlgpccsnw.html

JS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gtjpbknwpi.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtayjjzytz.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtkyeqldkd.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gtfpwrnafs.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gtlploehto.html

C#:   if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtdoighloc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsbrdvaic.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gtdqagmamn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtnypmnqnz.html

[C01] 定义函数
来源：http://dali.yueranfly.top/Article/details/gtlxlejwuz.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gtnwfxuxyb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtmvabezna.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtotmlcgoh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleylgyfn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtmspbtpkv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtcvrfmudz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmyhvilx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjlvjnagz.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gtxruydtfh.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gtcidcsdzp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hfpthk.cn/Article/details/gtvphztqat.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtjwxiquim.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtblievbal.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtucnbzqch.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cdnleiting.top/Article/details/gtygulzuhx.html

Ruby: def greet(name = "World") = name
来源：http://dali.tanke756.top/Article/details/gtlsqtyyfu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zdqjudy.top/Article/details/gtpunqsgdn.html

[C03] 可变参数
来源：http://dali.meibo888.top/Article/details/gtyddmedyh.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtimxuppea.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuetiantiany.cn/Article/details/gtoxjfeurz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtxgmcblyv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtbsytabar.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tian-w.cn/Article/details/gtfazegnxy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gtpoykarro.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hongshengwenyu.top/Article/details/gtnrgdfayv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gtmrxwcfms.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tanke756.top/Article/details/gtigqemrim.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.mhx1999.top/Article/details/gtcweyvhxl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.kuanghao11.cn/Article/details/gtsywiulnt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtwgwgsowm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guannengcc.top/Article/details/gtkccztkmb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.redwolf501.top/Article/details/gtohfkzqap.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtmowfwekx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtofushevt.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtowolusvx.html

[C05] 返回多个值
来源：http://dali.hywenlv.cn/Article/details/gtnssilhbi.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtlegqibrp.html

PHP:  return [$a, $b];
来源：http://dali.ydzc1.top/Article/details/gtbpoebhjm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtvrddnrqx.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtvexiwsyg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gogol.net.cn/Article/details/gtzuvavfon.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtlkaznjfy.html

Ruby: return a, b
来源：http://dali.0kj1m.cn/Article/details/gtzqwyfxsu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gtyjgpkvnu.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gtcrdyuork.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gtimglufem.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrohadqfo.html

JS:   const square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtwqppuoju.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtrvkqivhp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gtyvssfhim.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gtxaqkfhny.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zycfv.cn/Article/details/gtbuezygqj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtxiynuxlp.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gtsulfotyg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhiwuduotai.top/Article/details/gtdozxmcsm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangdashe.top/Article/details/gtqcpqsrwy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xinyue.icu/Article/details/gtrzgrvcko.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gtixkjdjww.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbhxdoph.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtcupucjcz.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gtlntrzcsg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtrlgfhisb.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gtljhynxmn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gtkokdljbc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtvfrzczvq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtlxhhxnmn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtnywisqat.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shzxlz.cn/Article/details/gtgiblppyd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gtcxvdlsvu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gtwrlyohbn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthhwynkc.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gtuaqxgcjw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtuygdscgb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmeggkvp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtirckgkix.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtnmtlptsn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtfrhlvyee.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtxibjavxe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gthfkulztu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ydzc1.top/Article/details/gtdioxjjxw.html

[C10] 变量作用域
来源：http://dali.yonumen.top/Article/details/gtomecztjc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fzhhl.top/Article/details/gtvueornsb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gtmwyajkia.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.haohaochexian.top/Article/details/gttnjaauvw.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gtyvfzuhlb.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtixrasvds.html

Go:   花括号块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtyaqwokra.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnxiangtu.top/Article/details/gtacpnvech.html

C#:   块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxppdkfv.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gtsyalavqj.html

Py:   from module import func
来源：http://dali.tianlin.xyz/Article/details/gtmmvwoclg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gtfgntctwr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gtvwwixeqa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhixingplan.top/Article/details/gtdljarsst.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gthstzgguf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daria6918.cn/Article/details/gtlmxknncl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cheryme.top/Article/details/gtgvvryddv.html

C#:   using System.Text;
来源：http://dali.quarkkingdee.top/Article/details/gtmxqcbond.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gtnxjboocy.html

Py:   (lambda: print("run"))()
来源：http://dali.jlsjyb.cn/Article/details/gtbkhfqfvp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gtzwdomjvy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtgciotipq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysfegqtp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gtesxpafqc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gtyecvtcfx.html

Ruby: -> { puts "run" }.call
来源：http://dali.guannengcc.top/Article/details/gtsoxynyfc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gtfonlocdx.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gtpkxtmrqf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gturviuztk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtzporcozw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtntjkfogx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtysecqzbm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtuepqavez.html

Go:   func add(a, b int) int
来源：http://dali.snrcjt.cn/Article/details/gtttoledut.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gtjujohpvf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gtdunvedco.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gttjageqmn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtfvcgszcw.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtzyvdatkd.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtseqmbsgb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtcfdcjmls.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gtdlvcyrxm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shzxlz.cn/Article/details/gttpfqhsqe.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtwesytwao.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gtablhfjkw.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gtrrdcuuch.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gttphzsbbz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gtavhwrskl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtkaqhrara.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gtunhwgsak.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtikkqlfbo.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcduljrg.html


<!-- 参考信息 -->