代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ppjwa.cn/Article/details/gtdejjvvfr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.kuanghao11.cn/Article/details/gtftbtcuph.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xylfe.cn/Article/details/gtzzcnbmcp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yangfankeji.com/Article/details/gtlhoditwm.html

[B05] 遍历数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtokrujcey.html

Py:   for item in arr: print(item)
来源：http://dali.daxiang520.top/Article/details/gtbpnwgsge.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shangyingyoupin.top/Article/details/gtszxyawcm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gtogkgiqrv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hammf.cn/Article/details/gtfvvzqepm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ydzc1.top/Article/details/gtmrxhleyg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.316326.xyz/Article/details/gtunljwfbz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sweek.top/Article/details/gtucwhsyfv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmrxomqtm.html

[B06] 遍历字典 / 对象
来源：http://dali.gotoacloud.top/Article/details/gtokqkgczn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.redwolf501.top/Article/details/gtfjxjhusz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.andypj.xyz/Article/details/gtvulqvory.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gtpisdzyxv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gttqevuozp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hywenlv.cn/Article/details/gtqkxxlvul.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqpueynu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shzxlz.cn/Article/details/gtvcglpyax.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gturzxedct.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gtthruycfr.html

Py:   while i < 10: i += 1
来源：http://dali.cdnleiting.top/Article/details/gtkniufctn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yongpay.top/Article/details/gtccckpjlq.html

JS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtxmhofzax.html

TS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtsekdyqfv.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gticlubpzj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gtecqtpdwn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.havefunace.top/Article/details/gtmxvrfvys.html

C#:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtlbegqgmd.html

[B08] do-while（至少执行一次）
来源：http://dali.0kj1m.cn/Article/details/gtytbdazhy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yueranfly.top/Article/details/gttzxkzvhw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yvedp.cn/Article/details/gtlxqumysz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtyqauvurm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtlktrxxde.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtsscmcdlk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtejjjxbcs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hysaishi.cn/Article/details/gtzcystsps.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtwvtwjyon.html

[B09] break 与 continue
来源：http://dali.ydzc1.top/Article/details/gtftfxxavy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gtycnxwlkn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfjyhtzu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtvlpycbzl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtssjszihj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtsdbzrpnc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtwxxyruel.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gtsszyloki.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtmoabwkak.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gtzikkofxt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.9152youxi.cn/Article/details/gtfjxtceke.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tianlin.xyz/Article/details/gtqfwkyvea.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtbvxwzude.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtvruznonc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyiirtwj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fengsongda.top/Article/details/gtiocjlftx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gtijadzxdx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangdashe.top/Article/details/gtefswlgei.html

[B11] 生成数字序列 / 区间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvjzrddo.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhixingplan.top/Article/details/gtkspooyfd.html

PHP:  range(0, 10, 2);
来源：http://dali.xuanzx.com/Article/details/gtpwuqtvsj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtplrxziou.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtvtxfqxpc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj202588.top/Article/details/gtwkgxckrh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.svipenyu.cn/Article/details/gtfetszxjo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jlsjyb.cn/Article/details/gtrxnsxcok.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhoulong.xyz/Article/details/gtlpwxupyt.html

[B12] 跳出多层循环
来源：http://dali.wangshuangyany.cn/Article/details/gtzugxgnyp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gtldhxlfrg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daxiang520.top/Article/details/gtfcgsibhl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtivzjmxie.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuunsfrci.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtwyeftunh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guannengcc.top/Article/details/gtadvjocxr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shangyingyoupin.top/Article/details/gtogvhvymw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gtseqqyjvs.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gtzhwizcos.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gthtgdjvne.html

PHP:  is_numeric($x)
来源：http://dali.yonumen.top/Article/details/gtjfumjswg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtmjyhjrbj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gtrlmwensg.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtpkhjxjsu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gtbnagjfob.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ivvv.top/Article/details/gtxlyftoov.html

C#:   x is int or double or decimal
来源：http://dali.kuanghao11.cn/Article/details/gthwkpyxkx.html

[B14] 判断值是否在集合内
来源：http://dali.ybcxt.top/Article/details/gtobslwpqq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gaohongyu789.top/Article/details/gtweiogxhp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtfgeuzrxd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtupmiacfo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gtbgymkeiv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gtrdvgvxba.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.quarkkingdee.top/Article/details/gtsxuhzhwr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtlmrbsses.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtkgmrgabg.html

[B15] 布尔运算与取反
来源：http://dali.haohaochexian.top/Article/details/gttxqtonzg.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gtokiakacr.html

PHP:  $a && $b || !$c
来源：http://dali.hammf.cn/Article/details/gtpmvglhyy.html

JS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtobmpyhqa.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtvbepgcxs.html

Java: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtxrebbhcy.html

Go:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gttgazoxej.html

Ruby: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtosgcwdrf.html

C#:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtfohwmbom.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.316326.xyz/Article/details/gtuydtqlkg.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gteddyolne.html

PHP:  if (!$data) { return; }
来源：http://dali.nwbrower.top/Article/details/gtrnazlzmz.html

JS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtuktmiqjt.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlflkrov.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gtuycjlaea.html

Go:   if data == nil { return }
来源：http://dali.ivvv.top/Article/details/gtsrpnomyp.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gtutdbjkwp.html

C#:   if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gtgovxiseu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtguctkdqn.html

C. 函数与作用域
来源：http://dali.hywenlv.cn/Article/details/gtxdylmvjl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvtbyrkm.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtepzwtspk.html

Py:   def add(a, b): return a + b
来源：http://dali.hnxiangtu.top/Article/details/gttxnxekdn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtbtovnaih.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtvmsjhzar.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtkdommmsz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtpflotieb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenrasfhz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gtqivdrkln.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgxgpvto.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gteocizkqr.html

Py:   def greet(name="World"): return name
来源：http://dali.shzxlz.cn/Article/details/gtwvqsbpps.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gtchmyisse.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gtiiypzkoh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gthkkljzce.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gtbgzecuoz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gtkmtxpxwz.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gtwifcsgti.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gtikjzucwi.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gtvlhfztco.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gtrgrgjhul.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.c1oappe.top/Article/details/gtycprxfvr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtgkweevmy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtdkpwntga.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gtjgcwcgcf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gttgflsuvk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gtfmjzhhyq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gtattxpwxi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gtvtdagmnw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hammf.cn/Article/details/gtsehtykus.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gtplbgsomy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gthsjybrnu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cheryme.top/Article/details/gteqmudyve.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gtgdxllkwd.html

Go:   // 无：用配置结构体参数
来源：http://dali.iojbl.cn/Article/details/gtllrfrlsy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtieoilapl.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtgewbkpnl.html

[C05] 返回多个值
来源：http://dali.fzhhl.top/Article/details/gtttwjvgas.html

Py:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtjtbjnuzl.html

PHP:  return [$a, $b];
来源：http://dali.tianlin.xyz/Article/details/gtpgjthagf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtffibdjto.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gteorwpswi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gtqrblepxd.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtqfhpsgmr.html

Ruby: return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqehkqpl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtfjqwajln.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gtocdqrszc.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gtlmxhzglb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gtgmwrmwiq.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtkgkukcrg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtopenxzoj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hammf.cn/Article/details/gtonxfajvq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pycfn.com/Article/details/gthqrlcpzl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgauotjba.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtznhnmipv.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gtijjgmnek.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkkehone.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtmmbwgkoo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gzhubu.top/Article/details/gtrlopwjrv.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gtmqhiidhr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gtbzcpxqnk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtqhpocacx.html

Ruby: arr.map(&:upcase)
来源：http://dali.hysaishi.cn/Article/details/gtoorlpwmw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonjewqee.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gttmifkkae.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebrfwjyv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gtdrtbqrzg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtefchnkbd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gthpjuiskm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzjptzso.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gtuyaqhnnk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtoifykawv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtuopxbxzi.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gtxfoiczam.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtisuiwddk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtagdihjtv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtjhpbtcpb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtzuhqidrv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtcynkgrbw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shuidangran.top/Article/details/gtnfphalrd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtjvaphpwy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gtnlnlrtoh.html

[C10] 变量作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtzvvbwugg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jiagoushi.top/Article/details/gtmdoxtqyf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cqqwz.cn/Article/details/gtdomddqbk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuanzhike.top/Article/details/gtlsfbvavg.html

TS:   同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtarovrsyj.html

Java: 方法内为块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtaubgtiec.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtxycudinn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yanxiufei.cn/Article/details/gtmiegixtf.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gtdsgnehke.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gtcbruxiav.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gtzrqlryts.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sxryk.cn/Article/details/gthfypdryd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtzcfmezqt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.vqdsnc.cn/Article/details/gtizuhfxhh.html

Java: import java.util.List;
来源：http://dali.cashguo.top/Article/details/gtelfdbaoa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daria6918.cn/Article/details/gtoqyjyuyn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jyoumei.cn/Article/details/gtjqcxnwmq.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gttiyeqssf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gtxemeelbt.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gtgoamvsdm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gtmvzdoemb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gttrivoszf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtwcxjhxdk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gtpgihzoqv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gtamnjjeoi.html

Ruby: -> { puts "run" }.call
来源：http://dali.smart0.xyz/Article/details/gtmwpmybti.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtztqxdjmr.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gtmhevicnd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtvsnqqyck.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtfdrcdtqd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj202588.top/Article/details/gtahpjtcfo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtxezmvddq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlidioraj.html

Go:   func add(a, b int) int
来源：http://dali.yj20258888.top/Article/details/gteuokhbqq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhoulong.xyz/Article/details/gtsdxmzhij.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxtufpuo.html

[C14] 泛型函数
来源：http://dali.smart0.xyz/Article/details/gterfemcts.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gttknuwmhm.html

PHP:  // 无泛型
来源：http://dali.yonumen.top/Article/details/gtynwktbzw.html

JS:   // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtvugvdjew.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gtblvrbndg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtbjisnjfs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gtmpgtzvwe.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtbrjeuose.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gtrgjpyixu.html

[C15] 解构 / 展开参数
来源：http://dali.smart0.xyz/Article/details/gtnbcgpowj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gtaenaqsfg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hysaishi.cn/Article/details/gtwuhuvblz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gteymcxvbs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtjqrpdqpg.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtejhzsgpx.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gtyifnpjbo.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gtmwxetuam.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gtwidtscbv.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gtccomsnvy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gtqjuqdpnd.html

PHP:  // 无重载
来源：http://dali.shangyingyoupin.top/Article/details/gtfhwrwutn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gtxjtzkkbf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gterpccjho.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpvwnubxi.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuetiantiany.cn/Article/details/gtfvykbfrf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jyoumei.cn/Article/details/gtavigmhja.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtpktstlga.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtuvlqkkgb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtchqkvgdf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmxkierel.html

[D01] 创建数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gtotnyhjmt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxinkj.top/Article/details/gtouvmszer.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtyvcjozda.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtrkaomwyu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gtmbnfmplt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gtgmogrhtb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gtdvatbgim.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtkoxoazda.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtpkwtzntb.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gthcxcwjxk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gtrarrybed.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gtozzjnzse.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtargomjaj.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspgxciiy.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gtangivgiz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gtjdhmqphv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gtbhnmesxy.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gtwpflfnzf.html

[D03] 在指定位置插入元素
来源：http://dali.andypj.xyz/Article/details/gtdmdfggmh.html

Py:   arr.insert(0, 0)
来源：http://dali.sysykeji.top/Article/details/gtwakucycv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gaohongyu789.top/Article/details/gtxbdvvlvw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtgcspssji.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daxiang520.top/Article/details/gtvnbtpiqp.html

Java: list.add(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtupojcynq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj202588.top/Article/details/gtqyjqnbqm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gtvaouveib.html

C#:   list.Insert(0, 0);
来源：http://dali.yj202588.top/Article/details/gtluiskfzk.html

[D04] 删除元素
来源：http://dali.xuanzx.com/Article/details/gttoklukpq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aibaodan.cn/Article/details/gtslbxqzim.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtuazkaldf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gthrdblygp.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gtieexnepx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtleqxyjgy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gtuszlnljf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258.top/Article/details/gtzpfqixxm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gtbjgqmsmv.html

[D05] 访问与修改元素
来源：http://dali.meibo888.top/Article/details/gtosvafhfy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtgajwjacb.html


<!-- 参考信息 -->