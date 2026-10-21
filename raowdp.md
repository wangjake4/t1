代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gttmazsimu.html

[B02] 多分支 else if / elif
来源：http://dali.9152youxi.cn/Article/details/gtoywctqqv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.mhx1999.top/Article/details/gtdqclcyze.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yuanzhike.top/Article/details/gtykfmgvli.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtgabowtuy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gthnypozcx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtdipzwcvj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cqqwz.cn/Article/details/gtxkpxanow.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jlsjyb.cn/Article/details/gtomnvrltu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtmskwyemn.html

[B03] switch / match / case
来源：http://dali.cucudq.cn/Article/details/gtauchqrog.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guannengcc.top/Article/details/gtkppjszsy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtlsfgcdjz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtorrldpyt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtsaigxtag.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtrksovzww.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtvlpscydf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yanxiufei.cn/Article/details/gtqucuqbuk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gtjdzfbcqm.html

[B04] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gtachmqkgy.html

Py:   for i in range(10): print(i)
来源：http://dali.jyoumei.cn/Article/details/gtftzqlzey.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sweek.top/Article/details/gtfggpabtw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gtajxgtdxd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gtkupcyyrc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.0kj1m.cn/Article/details/gthhfekkpk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnqzz.top/Article/details/gtxnmbrrmk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangshuangyany.cn/Article/details/gtdqzommez.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtnwncwvph.html

[B05] 遍历数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtxdsaonhi.html

Py:   for item in arr: print(item)
来源：http://dali.9152youxi.cn/Article/details/gtikfuhzyr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbzslgttw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gtnkskaisz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenlongwang.top/Article/details/gtvpatxgpw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ppjwa.cn/Article/details/gttznekibp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cashguo.top/Article/details/gtshtylayx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhixingplan.top/Article/details/gtjymqfpxy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.mhx1999.top/Article/details/gtbxgptslx.html

[B06] 遍历字典 / 对象
来源：http://dali.316326.xyz/Article/details/gtyrxsnjdj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gtkzbtxuyl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cheryme.top/Article/details/gtlpmayuaq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnxiangtu.top/Article/details/gtvtgoryvq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gtdkctajrk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgufenzy.top/Article/details/gtsmswnekw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.pycfn.com/Article/details/gtkpbljgvn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nwbrower.top/Article/details/gtiyteyjyx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guowangkeji.top/Article/details/gtzwfjzuoe.html

[B07] while 循环
来源：http://dali.jlsjyb.cn/Article/details/gthfyoulxu.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtgmdhoohm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ivvv.top/Article/details/gtrsgapcki.html

JS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtthvayfof.html

TS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtncmvyush.html

Java: while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtgscfvdyb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.quarkkingdee.top/Article/details/gtrauhxsnl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuetiantiany.cn/Article/details/gtqmpieemb.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtojgujkoq.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258.top/Article/details/gtcolcfriz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigfzy.top/Article/details/gtkfdjnjoa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtejbwugfk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtplpcjoju.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtmtrcwolk.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtxlhptruu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtqhcpfsfi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gtfcbufoup.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gthjmjwvdx.html

[B09] break 与 continue
来源：http://dali.sxryk.cn/Article/details/gtfuegnivv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gtvcfiutkc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtxnnjokqm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtepuuhtyn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtyzcavcmk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtvjdjcmia.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hnqzz.top/Article/details/gtiauuaddd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscazivgi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gthnbdjqnd.html

[B10] 遍历同时拿索引
来源：http://dali.hnqzz.top/Article/details/gtcvwudobm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hfpthk.cn/Article/details/gtnyxjdigr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zdqjudy.top/Article/details/gtehienjvn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtmqeoqtqr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtlfzvshqn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jiagoushi.top/Article/details/gtlkylltsh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gtiswluibg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daxiang520.top/Article/details/gtrjuhkrwz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dashuyun.cn/Article/details/gtantstlbm.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gtknychzeg.html

Py:   list(range(0, 10, 2))
来源：http://dali.snrcjt.cn/Article/details/gtqsvtnnkr.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gthbiegdca.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gthwbdlacx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtdvnjctma.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yvedp.cn/Article/details/gteftepavx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhiwuduotai.top/Article/details/gtnfjkyezv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tian-w.cn/Article/details/gtwlrxrraq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gtrxqsllhu.html

[B12] 跳出多层循环
来源：http://dali.fzhhl.top/Article/details/gtqjnonseq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sweek.top/Article/details/gtwtfhnoyb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cqqwz.cn/Article/details/gtvrtjbnsa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtsistrkcb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtoplbviyc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpsluzpx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jyoumei.cn/Article/details/gtluktxbtf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhoulong.xyz/Article/details/gttcinyrti.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpzjedtz.html

[B13] 判断是否为数字
来源：http://dali.fzhhl.top/Article/details/gtezxkoutv.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gtoomwuffn.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gttozlillz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtqenxuvgk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gthrxfepvf.html

Java: x instanceof Number
来源：http://dali.iojbl.cn/Article/details/gtghbernkm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gtohllkkqn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gtmzekkteq.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gtnuilupiw.html

[B14] 判断值是否在集合内
来源：http://dali.gzhubu.top/Article/details/gtrrtwgoan.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gtqaijynlz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gtsqhfyqse.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gtvimlkjzc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gtabhivryy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gtildrxyfo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.haohaochexian.top/Article/details/gttfwgojde.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxmvjsux.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtkzenozyt.html

[B15] 布尔运算与取反
来源：http://dali.yueranfly.top/Article/details/gtgndiwagc.html

Py:   a and b or not c
来源：http://dali.zycfv.cn/Article/details/gtwbmmokcr.html

PHP:  $a && $b || !$c
来源：http://dali.jqgfzy.top/Article/details/gtzpmpxtva.html

JS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtyyepkfkl.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtnyijbtfj.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtdjfncqoy.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtmipzlzgs.html

Ruby: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtsgzraapb.html

C#:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtoszbsvee.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gtgmtijaym.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtweqmvjnk.html

PHP:  if (!$data) { return; }
来源：http://dali.cdnleiting.top/Article/details/gtvxmgsyvu.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrrktqmr.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtegyodabv.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtndccqpex.html

Go:   if data == nil { return }
来源：http://dali.yongpay.top/Article/details/gtcvivzpyp.html

Ruby: return if data.nil?
来源：http://dali.cqqwz.cn/Article/details/gtxydzfkke.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtasjctjtv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtbubtgpgu.html

C. 函数与作用域
来源：http://dali.yuxming.cn/Article/details/gtqslchjqg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcckokuph.html

[C01] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtvytlknaz.html

Py:   def add(a, b): return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtiigisnpp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtbstbkxsy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtwugogyuu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtqtjrpbms.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuqfknlk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gtsskuicor.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gtziedwuzk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtaafncjrr.html

[C02] 默认参数
来源：http://dali.zhixingplan.top/Article/details/gtulolhftz.html

Py:   def greet(name="World"): return name
来源：http://dali.aibaodan.cn/Article/details/gtsisnqkuu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnxiangtu.top/Article/details/gtkmthbexd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gttgheajvi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtfuwyyksa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtlxxtkfwy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gthzbviayf.html

Ruby: def greet(name = "World") = name
来源：http://dali.snrcjt.cn/Article/details/gtjfvbhtam.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gtmmxxpgqp.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gtglpgonym.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gtdqjwujgz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gtwdpwsfwp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtzxqxnpja.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gthlpruyuo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtrtdhqujh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cashguo.top/Article/details/gtyowwlvng.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnqzz.top/Article/details/gtunkxyuxa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gotoacloud.top/Article/details/gtopmbfhyd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gttcbrtshu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gzhubu.top/Article/details/gtkmpalguf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gtazzfyyoy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtombshkkg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzlrrljq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gteeoybbme.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gtaoqikpds.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtgmfwacfk.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtrpcntsgt.html

[C05] 返回多个值
来源：http://dali.yj20258888.top/Article/details/gtoxizqqpr.html

Py:   return a, b
来源：http://dali.yongpay.top/Article/details/gtpkcspwhn.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gtpslghzkk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtidvdpvec.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtxzwlcllc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gtsejxeuwn.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gtsnivgokx.html

Ruby: return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtjlkccddh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gthukdodyd.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gtesewpdmo.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258888.top/Article/details/gtxpwncnty.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shangyingyoupin.top/Article/details/gtmywbdrvg.html

JS:   const square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajlkapmg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fzhhl.top/Article/details/gtxyumofad.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gttdoaxtci.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhongyouzk.top/Article/details/gttixwvngu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gtlvuxjjco.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gttpfhuaeh.html

[C07] 把函数作为参数传入
来源：http://dali.pycfn.com/Article/details/gthhlhzxcf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gtwqviqukt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xziqi.cn/Article/details/gtvqqwutfk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yanxiufei.cn/Article/details/gtkznkrhmc.html

TS:   arr.map(String)
来源：http://dali.hysaishi.cn/Article/details/gttmjzgmvx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aizwys.cn/Article/details/gtmehcnwvo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gtnnuoufbv.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtaomkfzhr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gtkozwecyi.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gtoxvnmaqz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gtchxznpua.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtihxgyyfk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtshgqyopp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtwwcbfwtn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gtprnpmlbr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtevpzmqlc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gtuookudlt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtauvfnadc.html

[C09] 递归
来源：http://dali.hfpthk.cn/Article/details/gttynwlggd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtfrkjnqzk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtuhwicpxa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtvpaiuaml.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtlhvtxjuk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtlhtttzae.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gtrstkumjc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gthrlncqvc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xinyue.icu/Article/details/gterfgkenq.html

[C10] 变量作用域
来源：http://dali.zdqjudy.top/Article/details/gtmorpmfeg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gtpqeqiqjb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuxming.cn/Article/details/gtsmjyxunb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtwrcroqmv.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gthityvsxg.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gtqudakkxp.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtzcnlwluv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gtomavlgkj.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gtatevjzbh.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gtpxslkypt.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gtnumqtjdm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gtaywscirb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtbxvrrdeb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.vqdsnc.cn/Article/details/gtplvuamhc.html

Java: import java.util.List;
来源：http://dali.yvedp.cn/Article/details/gtjlnoedju.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jianghu66.top/Article/details/gtgruexohv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gtghyrfkoj.html

C#:   using System.Text;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifnjhcgc.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaadozsvh.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gttsurcllq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.kuanghao11.cn/Article/details/gtrhisrjdb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gttbpwlkfk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtultyydjd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gtirsjtred.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gtzxviqcjr.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtcpxgfcph.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxnskxftz.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gtbgychbyj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shuidangran.top/Article/details/gtpiiobhck.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtvadqlklx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gtmsjcqmpu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gttngizjsl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtbsdfrhys.html

Go:   func add(a, b int) int
来源：http://dali.vqdsnc.cn/Article/details/gtkkathwbn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gtmtxblnba.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtqgtyjgzl.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gtroonhtyt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gtlilmsqjq.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtdlqzxjpi.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gteymiotci.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gtsqxqwamr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gtpdsquwxs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gtzvpjpdsj.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtndijumft.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigfzy.top/Article/details/gtzqyhinur.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gtotjpswym.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pycfn.com/Article/details/gtxbjludjl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gtqoloahfw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtuxawytwt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtfvoupogc.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtyhlnwpsc.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gtywnaefrq.html

Ruby: a, b = pair
来源：http://dali.hnqzz.top/Article/details/gtozejqxxk.html

C#:   var (a, b) = pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtphtvvyvq.html

[C16] 函数 / 方法重载
来源：http://dali.zhoulong.xyz/Article/details/gtsnuqnjcy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gtherrawcy.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtsdwvqrwt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gthwaqlzmz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gtqjojirya.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcaceodja.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gtercxplym.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gtupcpipmn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gtcjlsokcu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthjtirqxw.html

D. 数组 / 列表 / 集合
来源：http://dali.meibo888.top/Article/details/gtxlhduwke.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrfotsryi.html

[D01] 创建数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtpddddoyq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gtkavvbnyi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gtlfgapxre.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtabcncrme.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gtdgcmqjcr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxemkvwjl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscyrrjhi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gtmxcteeil.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzopqkxuq.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gthcepqdmf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwoumjwp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gtyfbeuoxu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtgpllenzh.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtdmhxjfpb.html


<!-- 参考信息 -->