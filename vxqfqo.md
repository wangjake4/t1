代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmnxbnvx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uorpbavr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfuulvyr.html

[A25] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2mdbzzdkj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yanxiufei.cn/Article/details/gt2efufiacx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ppjwa.cn/Article/details/gt2iipvhesj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ppjwa.cn/Article/details/gt2cctfomyl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.bjfxy.top/Article/details/gt2gyjyxdja.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmhiicce.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gt2hunlfgxh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.vqdsnc.cn/Article/details/gt2agqznvgh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gt2hvqpvwhk.html

[A26] 类型转换总览
来源：http://dali.sweek.top/Article/details/gt2rrfeuzxj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.316326.xyz/Article/details/gt2uwmevbqq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258.top/Article/details/gt2jlopsyfn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tianlin.xyz/Article/details/gt2hnouzkaf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zdqjudy.top/Article/details/gt2ebzsounn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdbpszyu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cashguo.top/Article/details/gt2zafnabcz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhixingplan.top/Article/details/gt2ehgqhjoj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cashguo.top/Article/details/gt2wczzkfjz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2kyrfoysz.html

B. 流程控制
来源：http://dali.mhx1999.top/Article/details/gt2ebhcwfog.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ayylzxna.html

[B01] 条件判断 if / else
来源：http://dali.svipenyu.cn/Article/details/gt2azpsmqby.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhoulong.xyz/Article/details/gt2bympyewu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tian-w.cn/Article/details/gt2ainwjtya.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gt2gszgxcqa.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gt2dvzdyqjj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gt2tnbrzksi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhongyouzk.top/Article/details/gt2odmnzflx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ehwqpu.com/Article/details/gt2bqfztksw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imqtnbxs.html

[B02] 多分支 else if / elif
来源：http://dali.chenlongwang.top/Article/details/gt2mixdccoq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfyhgyzt.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.316326.xyz/Article/details/gt2thvvvwnv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gt2hvibuzgr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwjlpkdo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gt2bxxajbre.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xinyue.icu/Article/details/gt2ycuzfhgm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gogol.net.cn/Article/details/gt2eavkffmb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gt2qgqdsaxw.html

[B03] switch / match / case
来源：http://dali.nanxinkj.top/Article/details/gt2wrukicxn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhoulong.xyz/Article/details/gt2mqtpgjga.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gt2qakhhrfu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gt2kekwdbeg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gt2lcogmfgt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gt2nroxoxxt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258888.top/Article/details/gt2oqamkafx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hywenlv.cn/Article/details/gt2fyerlkge.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gt2tjsliiep.html

[B04] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gt2kokaxtsz.html

Py:   for i in range(10): print(i)
来源：http://dali.hnqzz.top/Article/details/gt2mblvfqeh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hysaishi.cn/Article/details/gt2qergwngr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daxiang520.top/Article/details/gt2kzwxxnkt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sufxvd.cn/Article/details/gt2gzifuoqw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhengqikj.top/Article/details/gt2uneweaas.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shzxlz.cn/Article/details/gt2yxxrwjwz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnvcjrmy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigufen.top/Article/details/gt2afkvihfe.html

[B05] 遍历数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gt2losadvpz.html

Py:   for item in arr: print(item)
来源：http://dali.zhengqikj.top/Article/details/gt2qptnpdxh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gt2nyrdkxrs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gt2qliehgsl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gt2szvevwfc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258888.top/Article/details/gt2xlvozfza.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daria6918.cn/Article/details/gt2xlvtedjy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bshenypa.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.birdmap.top/Article/details/gt2ktzznfhq.html

[B06] 遍历字典 / 对象
来源：http://dali.jianghu66.top/Article/details/gt2zsckznrb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqveiqrr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shuidangran.top/Article/details/gt2ovwjkozk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gt2wxukvcga.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gt2yfyyrkdc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenzaomai.com/Article/details/gt2khqcxsdg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ydzc1.top/Article/details/gt2ynmhykzw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.havefunace.top/Article/details/gt2pnhbpurn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ivvv.top/Article/details/gt2vggzizmx.html

[B07] while 循环
来源：http://dali.daxiang520.top/Article/details/gt2dbvtzdjg.html

Py:   while i < 10: i += 1
来源：http://dali.aibaodan.cn/Article/details/gt2bafxpbcq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ivvv.top/Article/details/gt2usvvchci.html

JS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gt2qwlayvjt.html

TS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gt2ejshkvwy.html

Java: while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2jrtyjgxf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tian-w.cn/Article/details/gt2vdfozbgs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fizhgrti.html

C#:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gt2hixgnkql.html

[B08] do-while（至少执行一次）
来源：http://dali.jianghu66.top/Article/details/gt2tqhcbbgu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mettwnum.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cucudq.cn/Article/details/gt2crjakhck.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssqcblvu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2njrlkmnv.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwqorbyr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gt2rtkmqsuy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnqzz.top/Article/details/gt2kbgrnshp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gt2hsezmbct.html

[B09] break 与 continue
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkxvweux.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.meibo888.top/Article/details/gt2jgedsknk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2tjlynheg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gt2wnxfebjl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2bpbkbhrd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2jstpixcl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgfzy.top/Article/details/gt2suhbqnpj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangdashe.top/Article/details/gt2xjutghhk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2fkjpzjse.html

[B10] 遍历同时拿索引
来源：http://dali.gaohongyu789.top/Article/details/gt2powzopse.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eglojaea.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ehwqpu.com/Article/details/gt2pfayzpfe.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gt2mkauuluu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gt2vugderhu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkfonxnz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubknfiaf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ydzc1.top/Article/details/gt2qoggzwdd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gt2xyfgfsgt.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxflbsra.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gt2qpvzrczt.html

PHP:  range(0, 10, 2);
来源：http://dali.ehwqpu.com/Article/details/gt2oelmolhv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqegsgcr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gt2wugpkjzr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjlxhpjc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tianlin.xyz/Article/details/gt2ezizoshp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dianchejie.cn/Article/details/gt2fluplwpu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlrrsxso.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gt2vatliagu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj202588.top/Article/details/gt2uvmgyqqo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gt2qnieudps.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2lmubihpi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfdbaid.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2udbqxjue.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigufen.top/Article/details/gt2kzpmplyu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangdashe.top/Article/details/gt2nwlwlmzv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gt2haqesomu.html

[B13] 判断是否为数字
来源：http://dali.xziqi.cn/Article/details/gt2iuglaggc.html

Py:   isinstance(x, (int, float))
来源：http://dali.yanxiufei.cn/Article/details/gt2xzaajfwy.html

PHP:  is_numeric($x)
来源：http://dali.shuidangran.top/Article/details/gt2oukleedh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gt2lgsulqjl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gt2cuykqmxu.html

Java: x instanceof Number
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfyhwhne.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qegeggcw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnqzz.top/Article/details/gt2cjrzygsh.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gt2yncriugx.html

[B14] 判断值是否在集合内
来源：http://dali.cdnleiting.top/Article/details/gt2dpaxxhhs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gt2adceagqe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yongpay.top/Article/details/gt2qviqecam.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2snkgehgt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2sbnjrrep.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2ryrvzikd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shzxlz.cn/Article/details/gt2lzezvwqk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywaoqymq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2lvukcjva.html

[B15] 布尔运算与取反
来源：http://dali.fzhhl.top/Article/details/gt2meivdkwd.html

Py:   a and b or not c
来源：http://dali.redwolf501.top/Article/details/gt2gvithvep.html

PHP:  $a && $b || !$c
来源：http://dali.tianlin.xyz/Article/details/gt2rcwgsjcg.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2wdgxyarr.html

TS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2pawcoknl.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gt2cloltwip.html

Go:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2lbmqwnxo.html

Ruby: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2ipnxucbc.html

C#:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcpdblef.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fzhhl.top/Article/details/gt2jaapqplq.html

Py:   if not data: return
来源：http://dali.svipenyu.cn/Article/details/gt2terandqj.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gt2kimtzlmd.html

JS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2jtvwbejl.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gt2cejktyfo.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2clfbedzs.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gt2gzfogejm.html

Ruby: return if data.nil?
来源：http://dali.nanxinkj.top/Article/details/gt2vgncmpbv.html

C#:   if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytnuvoka.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2tmzglkic.html

C. 函数与作用域
来源：http://dali.dashuyun.cn/Article/details/gt2fkusnfdl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2jfqxzoze.html

[C01] 定义函数
来源：http://dali.sxryk.cn/Article/details/gt2sbkgoqsu.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gt2mzcghlop.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2bjrqmppj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2mplpecld.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2fqzzopoc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2jvolhgpg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ybcxt.top/Article/details/gt2memirapb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gt2nagobtka.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjkndwqk.html

[C02] 默认参数
来源：http://dali.yj20258.top/Article/details/gt2ugiyvymq.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gt2zkthwvma.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gt2dvfmthxd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2vxfsotia.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xhqmynqp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gt2sxhnutzb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.snrcjt.cn/Article/details/gt2eayvzakc.html

Ruby: def greet(name = "World") = name
来源：http://dali.guowangkeji.top/Article/details/gt2noplxthn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gt2bsqgefoa.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gt2spcxuaql.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gt2ombchemv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvcjdjcn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gt2omjbsmgv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gt2vkhszzub.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftmuouzl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gt2ipamzwiz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.quarkkingdee.top/Article/details/gt2mobogajq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gt2fvksbsuz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.kuanghao11.cn/Article/details/gt2iasgquxc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgdpwrnp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2elmdvmum.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhvtotvw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2dxkbtphj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gt2rueplkpz.html

Go:   // 无：用配置结构体参数
来源：http://dali.yonumen.top/Article/details/gt2yvggybfx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdpxthno.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gt2cibituqv.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gt2ihlxxjfj.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2voarpunz.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gt2bsbcdruq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpgwjeef.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gt2xtkhnsst.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gt2mwjnbuhq.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfklcppn.html

Ruby: return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2qloceeju.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwwydlig.html

[C06] 匿名函数 / lambda
来源：http://dali.yanxiufei.cn/Article/details/gt2kmgccdvr.html

Py:   square = lambda x: x * x
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhpmnpfk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhongyouzk.top/Article/details/gt2qgjyrnpv.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebdfkjzz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2uxibdzds.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigfzy.top/Article/details/gt2tdypttnr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuxming.cn/Article/details/gt2nezufdex.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzfuffss.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gt2lkotcvks.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gt2dxofdvsd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zycfv.cn/Article/details/gt2teyqvnge.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gt2ktfjajmr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gt2qmhimspt.html

TS:   arr.map(String)
来源：http://dali.shuidangran.top/Article/details/gt2opviqlwk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2epzjdqkp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dianchejie.cn/Article/details/gt2mxcgpihg.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gt2qbuboygs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gt2pbnxpidd.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gt2zihvowzb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gt2zmkuiwsm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gt2qjmyjkyb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uidkxrjq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2ovpospgp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shzxlz.cn/Article/details/gt2atqjurbr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gt2guwqweln.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gt2ovkiiwru.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2cwgpmjsp.html

[C09] 递归
来源：http://dali.yonumen.top/Article/details/gt2iweplklv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gt2vutfufrf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2qkuasyxx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gt2nvcajmbv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgrwftpa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gt2nxlitiit.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gt2fpselpbe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2jwhavzax.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gzhubu.top/Article/details/gt2fdnymqxm.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gt2pcwykbqk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gt2wdhtvdkk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.birdmap.top/Article/details/gt2xkecrdag.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gt2vxsecsei.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edtlgysj.html

Java: 方法内为块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2lpvklzfq.html

Go:   花括号块级作用域
来源：http://dali.smart0.xyz/Article/details/gt2gwbxlfcq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gt2kipmiwml.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gt2jbvndpns.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gt2pighyrvc.html

Py:   from module import func
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrdgnvmu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gt2bjjwcnkc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gt2vhsxxhqr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gt2yacskhip.html

Java: import java.util.List;
来源：http://dali.daria6918.cn/Article/details/gt2skzxquxs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gt2pncqrgtn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gt2gzcymdqx.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gt2crvioghm.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2eygchtwj.html

Py:   (lambda: print("run"))()
来源：http://dali.xinyue.icu/Article/details/gt2kjsucwnt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gt2fzkskubk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gt2bmnzvkaz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gt2oevunvst.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gt2ypmeuhbs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gt2dojpcnsn.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gt2pyotrotg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2tiswygoh.html

[C13] 类型声明 / 类型注解
来源：http://dali.svipenyu.cn/Article/details/gt2kojjfitt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gt2prrtwlix.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2svrlicrb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ehwqpu.com/Article/details/gt2lenysvpt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftwnjuol.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ektjdvgo.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gt2llihremd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yvedp.cn/Article/details/gt2cbhomgog.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jlsjyb.cn/Article/details/gt2becwxkhm.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gt2hnvxceis.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gt2xaghgujn.html

PHP:  // 无泛型
来源：http://dali.yongpay.top/Article/details/gt2adygpkkn.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2ydfwffis.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gt2wlrljlcj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.quarkkingdee.top/Article/details/gt2wfflcbkw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gt2ajojgwwq.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2hdfbkwqy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gt2yirffkzu.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdijbvya.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gt2nxerqqdj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gt2xikorvlf.html


<!-- 参考信息 -->