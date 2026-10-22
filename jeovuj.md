代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2eqvwepgs.html

[B02] 多分支 else if / elif
来源：http://dali.cashguo.top/Article/details/gt2kxxqtmxg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gt2hubtjsjc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sufxvd.cn/Article/details/gt2ddmnkjsw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gt2xiyjlhjv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gt2pufspgly.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gt2howmkcjq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.meibo888.top/Article/details/gt2fulcxwxz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pengpengdd.cyou/Article/details/gt2uucufmxq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gt2zskrdwak.html

[B03] switch / match / case
来源：http://dali.zhixingplan.top/Article/details/gt2nwadljny.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cucudq.cn/Article/details/gt2wmaciofc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gt2mxfqwxbu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gt2rdlutymk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gt2wiwixcej.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2beamipkm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hywenlv.cn/Article/details/gt2tsnrklhw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jyoumei.cn/Article/details/gt2lockrgwm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.birdmap.top/Article/details/gt2rklwfdpq.html

[B04] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gt2mztlaodr.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2edrypwqr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ehwqpu.com/Article/details/gt2zsafeyqd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gt2esuuljhg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gt2sfozjzce.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.0kj1m.cn/Article/details/gt2iujxyaam.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ehwqpu.com/Article/details/gt2gjnawjjg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yvedp.cn/Article/details/gt2iujxtuwe.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmxbatua.html

[B05] 遍历数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gt2gvsuxbef.html

Py:   for item in arr: print(item)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eodtiohn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.birdmap.top/Article/details/gt2sfbyxifv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2oxvvwjmv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hfpthk.cn/Article/details/gt2lqahltes.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhengqikj.top/Article/details/gt2uillimee.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tanke756.top/Article/details/gt2fzlvuntc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jyoumei.cn/Article/details/gt2salatuuq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hysaishi.cn/Article/details/gt2noyjhfks.html

[B06] 遍历字典 / 对象
来源：http://dali.0kj1m.cn/Article/details/gt2jbiaomej.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.c1oappe.top/Article/details/gt2aaifdfcw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nwbrower.top/Article/details/gt2nrzzhhld.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gt2exjykbfz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tanke756.top/Article/details/gt2mnbryszc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2neudsbkt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jlsjyb.cn/Article/details/gt2ilixdtph.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.svipenyu.cn/Article/details/gt2tuemwtnr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.vqdsnc.cn/Article/details/gt2gzwvhyqu.html

[B07] while 循环
来源：http://dali.andypj.xyz/Article/details/gt2bxlfrxwu.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsggrmsu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jianghu66.top/Article/details/gt2nieczbwm.html

JS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2djvfttqm.html

TS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2eswmkriz.html

Java: while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gt2atxlctgz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbbsyex.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nwbrower.top/Article/details/gt2cjqhmyul.html

C#:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2qpfweplu.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gt2hyubcwxp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yangfankeji.com/Article/details/gt2mofwxoji.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.316326.xyz/Article/details/gt2xncrzhqh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2nszhaqsn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2pylsjsms.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nupbcbfc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnqzz.top/Article/details/gt2ajklqfoj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.redwolf501.top/Article/details/gt2zmblpkrv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2rvfbbbbi.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gt2dsizxupe.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenlongwang.top/Article/details/gt2abmqnyyq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2zxrzsakc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2camhmxpk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2wtljocsi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2ppfkrcok.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenzaomai.com/Article/details/gt2vjpdrjue.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjtynspk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2accwnhew.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcbrzkas.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.9152youxi.cn/Article/details/gt2zdctegfa.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nwbrower.top/Article/details/gt2nhxclxpe.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gt2fraspjcy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gt2ipjkhqem.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gt2wqgblktc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gzhubu.top/Article/details/gt2vvukkudm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgfzy.top/Article/details/gt2fezkxace.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2auarytlc.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gt2beloxxoe.html

Py:   list(range(0, 10, 2))
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxrpiwpv.html

PHP:  range(0, 10, 2);
来源：http://dali.hammf.cn/Article/details/gt2qntzxqut.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gt2xupdhjud.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gt2kjlkrvha.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2vmfjrbtk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.redwolf501.top/Article/details/gt2ogkbbvrv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqzcttgd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qekacpea.html

[B12] 跳出多层循环
来源：http://dali.mhx1999.top/Article/details/gt2gaqmfwiw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gt2howlzbox.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gt2nosfilwp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gt2fosfbief.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsxeskll.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gt2qlleyder.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yongpay.top/Article/details/gt2leoaxyrt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gt2nmnahrmm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gt2tcuayxzw.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gt2boiqrpyw.html

Py:   isinstance(x, (int, float))
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmvvaeml.html

PHP:  is_numeric($x)
来源：http://dali.hywenlv.cn/Article/details/gt2eovyrtmt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gt2hieqemvq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gt2xjhcnrdq.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gt2urkawgpt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sufxvd.cn/Article/details/gt2cwhgvolb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gt2usechwnr.html

C#:   x is int or double or decimal
来源：http://dali.tanke756.top/Article/details/gt2qwhtoyet.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gt2whqplbwi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.havefunace.top/Article/details/gt2hvigsaps.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hysaishi.cn/Article/details/gt2etjdcnbf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gt2pztqesop.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2beplylyr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2fwntbeis.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gt2bvxfhtco.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahijsipz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2cqyvbvmy.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gt2lwjnkhjt.html

Py:   a and b or not c
来源：http://dali.wangdashe.top/Article/details/gt2ozevujzy.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gt2fqaggkav.html

JS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2beiemqyi.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2kikhpjcr.html

Java: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edlpnjjf.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2shcmeehq.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2taouzbsv.html

C#:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2ubauhvlm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2bairmwjx.html

Py:   if not data: return
来源：http://dali.haohaochexian.top/Article/details/gt2lasajdcy.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gt2gkrgzqvm.html

JS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2xouhswpv.html

TS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gt2surtntcc.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gt2rmkmqolz.html

Go:   if data == nil { return }
来源：http://dali.xylfe.cn/Article/details/gt2gxbbdqbe.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gt2ogfjyiod.html

C#:   if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gt2hkqzhgjv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2fnwvowkm.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gt2eptdpgvt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2eapvgkyn.html

[C01] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptghedkq.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gt2bsuadnig.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2pbmhhpgf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2fognplyf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2pgiokkcx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2jiymvzgm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2dgffnjab.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gt2okmylsvs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2dtmwuaoc.html

[C02] 默认参数
来源：http://dali.ppjwa.cn/Article/details/gt2kvrthyte.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gt2duiwrntc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gt2pykddcpf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2wqymjltu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2imeadyzi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gt2odrqpsrh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gt2hnywwowk.html

Ruby: def greet(name = "World") = name
来源：http://dali.316326.xyz/Article/details/gt2sjhfvklq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwxvlkab.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gt2efhokehe.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gt2sbbzlklh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gt2oftisfww.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gt2ntavhdsy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2xiewexbc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2mvslyuib.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gt2knugmtpx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2rldpefij.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gt2zfjdahsx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tanke756.top/Article/details/gt2vnnuozzi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gt2kbfedmrg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gt2usivdfkk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2mjontbqu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gt2bhtiefzt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gt2msayvwoa.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gt2dcxdckjf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gt2unacfpix.html

C#:   f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gt2yqxhccld.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gt2pkmfabin.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzpzmowl.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gt2lrmawhjv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xylfe.cn/Article/details/gt2dlikwzvd.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gt2opasdjtb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jlsjyb.cn/Article/details/gt2rgfrgazw.html

Go:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gt2sshhtgtn.html

Ruby: return a, b
来源：http://dali.0kj1m.cn/Article/details/gt2lioorpqt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gt2foqctnxq.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gt2tqbrueje.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gt2jcixodfo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.quarkkingdee.top/Article/details/gt2ecnyinkt.html

JS:   const square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2nmptlrfg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2ulkvfkfc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daria6918.cn/Article/details/gt2tlaqlvry.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gt2nmfkrueo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cdnleiting.top/Article/details/gt2srcyyeyx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2ijqcwmup.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gt2bgesvaaj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gt2mvnbzcop.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gt2sdpppeou.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gotoacloud.top/Article/details/gt2lguzcrnp.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gt2xxqvrgbu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gt2jxacqbha.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.mhx1999.top/Article/details/gt2tvtufcja.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gt2sxkhonue.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkldpxri.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gt2rwjsmllt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangdashe.top/Article/details/gt2fxtvzjdt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gt2lhkjntpv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gt2nmdgvbhy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpaybrpa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gogol.net.cn/Article/details/gt2hksukejz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gt2dijlxgoi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gt2pyrqyqan.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gt2tnnwiwuh.html

[C09] 递归
来源：http://dali.ydzc1.top/Article/details/gt2dnvsmpey.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gt2clbewpix.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gt2xpfdcfiq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gt2ovlzyrqd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gt2nkjxmhih.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gt2jtxxxpuw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gt2hexzgpft.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gt2kseyvsba.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jyoumei.cn/Article/details/gt2jcnafhdh.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnaakezu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sxryk.cn/Article/details/gt2tamtuqvr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daxiang520.top/Article/details/gt2gbmkitax.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2aihxveni.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gt2wjmpcook.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2bncocpuk.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2ynnkeqqq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.mhx1999.top/Article/details/gt2cldksshx.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2mxbhntyu.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqypbbgb.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gt2husyvshr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gt2dltbgmkb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkqbfuh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigufen.top/Article/details/gt2yhtbvfpv.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gt2aatadpbs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrrrtiuf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gt2nfinsxxg.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gt2ktahoxii.html

[C12] 立即执行函数 IIFE
来源：http://dali.zdqjudy.top/Article/details/gt2muscbnvf.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gt2bcjtzwbp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gt2cclhsapy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqtbvjjg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gt2oprmpgeq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sweek.top/Article/details/gt2qeullyyl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gt2osharfhd.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gt2eyfafruo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2segcyygp.html

[C13] 类型声明 / 类型注解
来源：http://dali.yongpay.top/Article/details/gt2zillbmsy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenlongwang.top/Article/details/gt2ssyfyobn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gt2nwtfxtsa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gt2ergesnic.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2oovrpdwx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2nmqabwyx.html

Go:   func add(a, b int) int
来源：http://dali.chenzaomai.com/Article/details/gt2onncgeol.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gt2jszokfxy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hywenlv.cn/Article/details/gt2qytccdcs.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gt2thwdpjrd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhoulong.xyz/Article/details/gt2kvyvvhnr.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twqvpmlv.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2tcwiwdir.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxrblvxc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2kfoxrubq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gt2lkrxzqdv.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2vdrlwnbo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gt2xvecmyqw.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywhzssff.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gt2liubnyey.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gt2xsafplvw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gt2njxskhbd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2rfpypmjk.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gt2hslhmete.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gt2hmjfifsr.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gt2hgoeercn.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2ecrpgvvm.html

[C16] 函数 / 方法重载
来源：http://dali.316326.xyz/Article/details/gt2unxmwuwz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gt2iudfvotv.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gt2jqudurwx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhongyouzk.top/Article/details/gt2jmrohlcn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gt2bklfyjzn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvmmidbr.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gt2esjmyauk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2eozwvtss.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gt2uboaewkv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2cpqwigcr.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gt2oxjdpxdr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2wxhladws.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gt2hqqdwbue.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.mhx1999.top/Article/details/gt2pbwqtpic.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2gjldapfq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2ellaiyrp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gt2gjczagll.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gt2kmsvmejy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gt2zvvztukd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guowangkeji.top/Article/details/gt2xizcsjxv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gt2hyqyghao.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2iutklshn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gt2dmqldrva.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2zzvfloim.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gt2kpodoaln.html

TS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gt2tnrnphjr.html


<!-- 参考信息 -->