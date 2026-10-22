代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2poeoqagl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.vqdsnc.cn/Article/details/gt2teudtjry.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gt2gdlwdycp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdeurprx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daria6918.cn/Article/details/gt2ihpxunza.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gt2wfryfird.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gogol.net.cn/Article/details/gt2isazmwny.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gt2efkbsxfp.html

[A26] 类型转换总览
来源：http://dali.dashuyun.cn/Article/details/gt2txhowqvm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuxming.cn/Article/details/gt2rawzpiiq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gogol.net.cn/Article/details/gt2rjwhsvvd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.pycfn.com/Article/details/gt2znaxyqja.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pycfn.com/Article/details/gt2cteakcep.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yonumen.top/Article/details/gt2djaxyxrq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dianchejie.cn/Article/details/gt2suusvnig.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppkiwpii.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gt2xsujumfc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2jxqebqsj.html

B. 流程控制
来源：http://dali.svipenyu.cn/Article/details/gt2isqkobvi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxemlwij.html

[B01] 条件判断 if / else
来源：http://dali.smart0.xyz/Article/details/gt2kmgufttn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tanke756.top/Article/details/gt2qgfjhgxd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sweek.top/Article/details/gt2bwxifeaj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gt2joamlwsn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gt2thzwxuhp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gt2mrpyfwoc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jukudssu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hfpthk.cn/Article/details/gt2srzjyynb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gt2slrbnwtt.html

[B02] 多分支 else if / elif
来源：http://dali.kuanghao11.cn/Article/details/gt2nwdbcsic.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xinyue.icu/Article/details/gt2snasaoqa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xinyue.icu/Article/details/gt2nnexnbvp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gt2vwqnmbng.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gt2enlmlwre.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gt2zgdptdid.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.snrcjt.cn/Article/details/gt2gglhstpn.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hysaishi.cn/Article/details/gt2rakfqhti.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gt2vqxwhmwi.html

[B03] switch / match / case
来源：http://dali.hnxiangtu.top/Article/details/gt2kupfvppk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.0kj1m.cn/Article/details/gt2gwoxedww.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gt2qdhnslqd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2oxhojsst.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gt2vlsitqjy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2bxqzxfjh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yangfankeji.com/Article/details/gt2vefywath.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj202588.top/Article/details/gt2dlmwexft.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fengsongda.top/Article/details/gt2ycmwhpua.html

[B04] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gt2fkyzpeni.html

Py:   for i in range(10): print(i)
来源：http://dali.yvedp.cn/Article/details/gt2xsrxvsix.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rppfpxng.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gt2vwvtjrxw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenlongwang.top/Article/details/gt2fokkxijo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.pycfn.com/Article/details/gt2jmjuqchz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yongpay.top/Article/details/gt2qsxblpju.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sxryk.cn/Article/details/gt2nnrhjfkb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhongyouzk.top/Article/details/gt2kpsqmpif.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gt2hgrrngdc.html

Py:   for item in arr: print(item)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xoqmqita.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hmjzfoii.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gt2zyywyaue.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmfoukff.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qiinnqkn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xylfe.cn/Article/details/gt2yanwgoza.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jqgfzy.top/Article/details/gt2stgqdwmw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pifxakur.html

[B06] 遍历字典 / 对象
来源：http://dali.quarkkingdee.top/Article/details/gt2rvtqpcow.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwwsrply.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tian-w.cn/Article/details/gt2vvpadkzk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhongyouzk.top/Article/details/gt2qlttrenh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.bjfxy.top/Article/details/gt2pmnxytti.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.fengsongda.top/Article/details/gt2dxdtrfmu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shuidangran.top/Article/details/gt2pyzytuqb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2aotobzkd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.0kj1m.cn/Article/details/gt2efjpepyh.html

[B07] while 循环
来源：http://dali.zdqjudy.top/Article/details/gt2oyhdjdxl.html

Py:   while i < 10: i += 1
来源：http://dali.yuxming.cn/Article/details/gt2aupqsdkh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2inebpjch.html

JS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gt2jfeoemhn.html

TS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2bvfkasvm.html

Java: while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2kzdbazzq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gt2sehmwzmn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.mhx1999.top/Article/details/gt2spbiwzzy.html

C#:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2znqqgysi.html

[B08] do-while（至少执行一次）
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnfgpxjb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigufen.top/Article/details/gt2isxxvckg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2gwkrpfja.html

JS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2daaziopv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2nkckqple.html

Java: do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2khxfatua.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iuuxadon.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.meibo888.top/Article/details/gt2nfcsnsic.html

C#:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2yotgoqya.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gt2ltnalxqp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gzhubu.top/Article/details/gt2eqrseafm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2fomtqcjr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpuwnyjw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gt2bhqcirrk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2buldhfai.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gt2uwciejgm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yangfankeji.com/Article/details/gt2dozcpqxd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2epkzoneo.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gt2cegcxnun.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tian-w.cn/Article/details/gt2qimziein.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nwbrower.top/Article/details/gt2hswobkri.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gt2wnxcjbto.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gt2frecjpgt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gt2arvhizpa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubdzcorw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.smart0.xyz/Article/details/gt2cirwsxde.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gt2kveqpjpq.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gt2ytwtcvtb.html

Py:   list(range(0, 10, 2))
来源：http://dali.tanke756.top/Article/details/gt2ilomurbw.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gt2wwhujrix.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gt2nmnqnbwv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gt2bbqzcysk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2rafqbznv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gzhubu.top/Article/details/gt2xfnjcizb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ydzc1.top/Article/details/gt2teroldnw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj202588.top/Article/details/gt2buiarhlw.html

[B12] 跳出多层循环
来源：http://dali.hfpthk.cn/Article/details/gt2ogzniscc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shzxlz.cn/Article/details/gt2iihsqfow.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.haohaochexian.top/Article/details/gt2opiwtfib.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gt2bwruaqhg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gt2tuqdiygi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gt2lxpvzari.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dashuyun.cn/Article/details/gt2wtjibuuv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqyjijnt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.bjfxy.top/Article/details/gt2qoyhxvhi.html

[B13] 判断是否为数字
来源：http://dali.xziqi.cn/Article/details/gt2emqowkdw.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenlongwang.top/Article/details/gt2mkhyzzbb.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gt2rtxrbyob.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gt2wstteuqb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gt2crnwopau.html

Java: x instanceof Number
来源：http://dali.yanxiufei.cn/Article/details/gt2ulzferpk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhongyouzk.top/Article/details/gt2puoznzma.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2detyugxf.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gt2svjofiuv.html

[B14] 判断值是否在集合内
来源：http://dali.chenlongwang.top/Article/details/gt2jiqnlpzq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhwzvubz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gt2fjkaiypx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2htbshqll.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2gfbqwkhq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxsntbbo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcwwhjfa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsmkhlcc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2ucqivndw.html

[B15] 布尔运算与取反
来源：http://dali.yongpay.top/Article/details/gt2cxmxrfwo.html

Py:   a and b or not c
来源：http://dali.yj20258888.top/Article/details/gt2kxasykej.html

PHP:  $a && $b || !$c
来源：http://dali.0kj1m.cn/Article/details/gt2zawqgfkt.html

JS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2yqeyfvcd.html

TS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2opucexad.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmxyhmyy.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2jtdxyisv.html

Ruby: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2nlblppqj.html

C#:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2jwcxmfos.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnqzz.top/Article/details/gt2jpncchpb.html

Py:   if not data: return
来源：http://dali.xuanzx.com/Article/details/gt2koqiexnf.html

PHP:  if (!$data) { return; }
来源：http://dali.daxiang520.top/Article/details/gt2ulwgpdyc.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gt2rwnvhlge.html

TS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gt2nztwzgsp.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gt2tfzzwgnr.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gt2yogaqhnt.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gt2kecehacb.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gt2ocvbryus.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukdxumgg.html

C. 函数与作用域
来源：http://dali.jinqigufen.top/Article/details/gt2bvjgpssn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqqeutib.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gt2cpnyugub.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gt2moarihri.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2qsxswwne.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2lwricilk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2cqfqmhqw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2gxkdnkbq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gt2tizfkouu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gt2xcnareio.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2plnggqgs.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gt2lcitmuqj.html

Py:   def greet(name="World"): return name
来源：http://dali.fzhhl.top/Article/details/gt2rkrfwpjp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ybjtbnso.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gt2geazfrss.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2whmnquee.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gt2tpzufxfo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gt2oskbuxez.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gt2vkolobwv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jlsjyb.cn/Article/details/gt2jcclxzkb.html

[C03] 可变参数
来源：http://dali.xinyue.icu/Article/details/gt2gylasxit.html

Py:   def total(*args): return sum(args)
来源：http://dali.redwolf501.top/Article/details/gt2bwyksbje.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuxming.cn/Article/details/gt2jparndwa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gt2jhqktjtf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gt2rjwdncjb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangdashe.top/Article/details/gt2bpmseyqf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.redwolf501.top/Article/details/gt2ctdomkgm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gt2rmwexbnn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gt2grfsrcue.html

[C04] 命名参数 / 关键字参数
来源：http://dali.kuanghao11.cn/Article/details/gt2srrlzkmc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gt2zbpntseg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwnhuyhc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gt2zjmtoovn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gt2fadouuqp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.havefunace.top/Article/details/gt2ynificlc.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gt2fwqgbfbj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gt2fjboueem.html

C#:   f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gt2wdpcllkq.html

[C05] 返回多个值
来源：http://dali.quarkkingdee.top/Article/details/gt2jtveyymt.html

Py:   return a, b
来源：http://dali.yongpay.top/Article/details/gt2zxbqmnul.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gt2rqlrzlmd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nwbrower.top/Article/details/gt2ywacpurt.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gt2gvjmzmfq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gt2umnclvje.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gt2yfneyaft.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2ydfbiqhz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gt2fnolmhzy.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gt2csaatnqc.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gt2sdffplty.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gt2gworpzbf.html

JS:   const square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gt2fnfkpqur.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2hnzxsjob.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258888.top/Article/details/gt2hiuqvxip.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iaklcscm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gt2ntnzsysf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2djdgrspf.html

[C07] 把函数作为参数传入
来源：http://dali.c1oappe.top/Article/details/gt2zwfagdtz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rcaslqns.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2iwfldwlr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gt2sjedqtyv.html

TS:   arr.map(String)
来源：http://dali.quarkkingdee.top/Article/details/gt2vrqenygq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2jurccumi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jlsjyb.cn/Article/details/gt2ipinmfmm.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gt2yxkgjkpg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gt2pgomjpja.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gt2hcuzwnci.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ydzc1.top/Article/details/gt2qszqpwuo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hammf.cn/Article/details/gt2fmqzgipc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gt2wtttjcqz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2kowrbjhx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gt2qbtkwegv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gt2qgwrmwex.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2ladiggrg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gt2beurzysi.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gt2zwyrmykv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2binrljjd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gt2fqexwszx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gt2vcxodxjs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gt2bcvdnbet.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gt2ahyonojb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gt2ufqjwqzp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gt2ttvgwyst.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gt2qvlyomrq.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gt2boifwczf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cheryme.top/Article/details/gt2etpfwwqd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigfzy.top/Article/details/gt2rynbbogt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yueranfly.top/Article/details/gt2amvuvtwx.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gt2dcsuimos.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2zykrsdlq.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2pumfogjh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gt2xweuqvtg.html

C#:   块级作用域
来源：http://dali.daxiang520.top/Article/details/gt2uulcxevq.html

[C11] 模块导入与导出
来源：http://dali.gotoacloud.top/Article/details/gt2ljtpdxnt.html

Py:   from module import func
来源：http://dali.cqqwz.cn/Article/details/gt2ovlteumf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnqzz.top/Article/details/gt2jyxbzoxs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gt2rlasgxvx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gt2ragtpbob.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhmdtnci.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxxlccze.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gt2tikbadmx.html

C#:   using System.Text;
来源：http://dali.zhongyouzk.top/Article/details/gt2vjbphnas.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigufen.top/Article/details/gt2wdtgaplc.html

Py:   (lambda: print("run"))()
来源：http://dali.smart0.xyz/Article/details/gt2tpydyzyt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gt2ewddwcnn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gt2yobodlmq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gt2msjtqvhz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gt2prftbjyn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgfzy.top/Article/details/gt2kmalfkib.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gt2ounxywfb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gt2zfcppubh.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gt2nquutpno.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2iptozmvk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2newzeefs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2arhpszxj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2lzqxmuwk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2bdalgspn.html

Go:   func add(a, b int) int
来源：http://dali.jianghu66.top/Article/details/gt2klikcela.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gt2hwsnnpsb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gt2buhmpagk.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gt2xsbkppcc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gt2zfqgctqo.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2fuqcyhff.html

JS:   // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytbtfipq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ihlvazmt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gt2bbkecqgk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gt2jayaccui.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gt2bvacmeat.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gt2wjrpbvie.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gt2prmyzrlq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gt2dpzpyrmu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gt2ardjuzvb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gt2qmcvypqk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewskgauj.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gt2wpqwflhp.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gt2rjmhpepx.html


<!-- 参考信息 -->