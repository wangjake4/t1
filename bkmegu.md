代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hfpthk.cn/Article/details/gtlywccabv.html

[B06] 遍历字典 / 对象
来源：http://dali.ydzc1.top/Article/details/gttgmetqse.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sweek.top/Article/details/gtdwlhnjlq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlqdorpbx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtrnpprfzy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gtcqrnvizt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.snrcjt.cn/Article/details/gtgevfiasp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hfpthk.cn/Article/details/gttaghwxst.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xinyue.icu/Article/details/gtrnynartr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sysykeji.top/Article/details/gtlxthqjdk.html

[B07] while 循环
来源：http://dali.jlsjyb.cn/Article/details/gtnocverda.html

Py:   while i < 10: i += 1
来源：http://dali.nwbrower.top/Article/details/gtzagblmig.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cqqwz.cn/Article/details/gtqacnsdsn.html

JS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtgzyeqjen.html

TS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtgbcrfquj.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtqqkzhyao.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ppjwa.cn/Article/details/gticuqrlud.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hysaishi.cn/Article/details/gtpccwtqio.html

C#:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtalmhdenm.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gttbnghphf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhengqikj.top/Article/details/gtbpcxufnj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ydzc1.top/Article/details/gtamrvpgsr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtsxvplatx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtqxlcoqcm.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtefknylvd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtjjxounar.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ybcxt.top/Article/details/gtqgnhsfyg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqctqwnv.html

[B09] break 与 continue
来源：http://dali.yvedp.cn/Article/details/gtardmgfej.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258.top/Article/details/gtxgiidxke.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtfsmxhkci.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxhdrsyda.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtmqbxnxly.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtacztjnqs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hywenlv.cn/Article/details/gtlanyfpir.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zdqjudy.top/Article/details/gtouozoarb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtdotxjxzr.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gtuxezctbj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xylfe.cn/Article/details/gtnmstvhhd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangdashe.top/Article/details/gtobbpdlja.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gtwklgqeei.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtjwzgxrmz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nwbrower.top/Article/details/gtmrqdbpok.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gtngiaclyt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aizwys.cn/Article/details/gtuiwyddtd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gtmnlnioeq.html

[B11] 生成数字序列 / 区间
来源：http://dali.haohaochexian.top/Article/details/gtklhasplk.html

Py:   list(range(0, 10, 2))
来源：http://dali.cashguo.top/Article/details/gtleahzcbo.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gtwimxrhch.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gtgewohiwt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gtlqbneqjq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ehwqpu.com/Article/details/gtftmwcmfm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aibaodan.cn/Article/details/gtgzccgned.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnqzz.top/Article/details/gtcvzoffwd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gtcrqdcfoo.html

[B12] 跳出多层循环
来源：http://dali.yueranfly.top/Article/details/gtmmbagqge.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gtbrmrbkeb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ybcxt.top/Article/details/gtikjsanhy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtsswofabm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtmzdzipcg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtltlqfiun.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkgcmchj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gtwibpkbcn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gttylhqkip.html

[B13] 判断是否为数字
来源：http://dali.tanke756.top/Article/details/gtkdgjmnju.html

Py:   isinstance(x, (int, float))
来源：http://dali.jiagoushi.top/Article/details/gtobpulqnx.html

PHP:  is_numeric($x)
来源：http://dali.pengpengdd.cyou/Article/details/gtahjvlkev.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtrwcscrhb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtrtdbmpik.html

Java: x instanceof Number
来源：http://dali.zycfv.cn/Article/details/gtxutnnflb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gtqbxwanmk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gtescrdqtt.html

C#:   x is int or double or decimal
来源：http://dali.tianlin.xyz/Article/details/gtcagrjdzz.html

[B14] 判断值是否在集合内
来源：http://dali.feifeiyinyue.top/Article/details/gtolkpgfgj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gtwefzuipp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zycfv.cn/Article/details/gtfoukbvsw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtsfdyykch.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtmkeebpxr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqqoxdpa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gtoyumzcae.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gtuhpnwobt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtqtbpgkvf.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gtswdmvkix.html

Py:   a and b or not c
来源：http://dali.yj20258.top/Article/details/gtrmyldaqu.html

PHP:  $a && $b || !$c
来源：http://dali.0kj1m.cn/Article/details/gtunubdsbv.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtcdrwqrtd.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtcxilhfhg.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtlydiegqr.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtonseclzj.html

Ruby: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtjrwjsptt.html

C#:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtbhuqpqns.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gttampgizn.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gtudbadwve.html

PHP:  if (!$data) { return; }
来源：http://dali.sufxvd.cn/Article/details/gteacylxuo.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtoxnjsjkh.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkpjhwgc.html

Java: if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gttokevdyo.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gtmihrthlw.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gtywhurwnk.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gtxacpyhia.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjezdjfpi.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtlhzzsmfn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtsmwcnibs.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcmcrniz.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gtpjidlste.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtphknuwrx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtunnrfwov.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtioszzylb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gttiakhsdw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gtetlavofc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gtmmrumnua.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtjtbkuuka.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gtvenfgpgd.html

Py:   def greet(name="World"): return name
来源：http://dali.jlsjyb.cn/Article/details/gtspztzohu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtvqbiyqoo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtumbyvlcm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gttpjdbnmf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gtnqzvtqhg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtfkhylsxg.html

Ruby: def greet(name = "World") = name
来源：http://dali.0kj1m.cn/Article/details/gtgqbcnrdn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aibaodan.cn/Article/details/gtfyhcfftz.html

[C03] 可变参数
来源：http://dali.yuanzhike.top/Article/details/gtpcvddblo.html

Py:   def total(*args): return sum(args)
来源：http://dali.shzxlz.cn/Article/details/gtbcgfhzbm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nanxuanxn.top/Article/details/gtdplgumva.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gtvogwgzpl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gtsnhvauqb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.mhx1999.top/Article/details/gtqeenhqea.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gthqbncjmn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ivvv.top/Article/details/gtskrfgulf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.andypj.xyz/Article/details/gtpbfwoqdb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gtxadlmfhi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gteukwjaqb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tanke756.top/Article/details/gtcyvveaaz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtolsnmzsi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtarojlpaj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cucudq.cn/Article/details/gtdvjtaldd.html

Go:   // 无：用配置结构体参数
来源：http://dali.gogol.net.cn/Article/details/gtwgmhgzij.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtpvdamksx.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkgzeqpo.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gttvvskxjt.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtjcsvznah.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtphjeevxh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtmdjvulgf.html

TS:   return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gtagarzrlw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gtugzutttx.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtjcdwmdab.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gtbraymlal.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tian-w.cn/Article/details/gtbtjeqfcq.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gtpsotzvld.html

Py:   square = lambda x: x * x
来源：http://dali.sysykeji.top/Article/details/gtusdazdkx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gtosezhdpo.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtnayfeexa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtnrqjjvna.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sysykeji.top/Article/details/gtzqyqjyfp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gtkmlixhlv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtepuqzzep.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtduesefyr.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gtdnkhimnw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gtvliyraal.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sweek.top/Article/details/gtfbetdyqx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gthgvahqdu.html

TS:   arr.map(String)
来源：http://dali.ppjwa.cn/Article/details/gtwltqegdk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gteyqboqmo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ybcxt.top/Article/details/gtoeswgxao.html

Ruby: arr.map(&:upcase)
来源：http://dali.kuanghao11.cn/Article/details/gtwnnfwwss.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pengpengdd.cyou/Article/details/gtcakqfizf.html

[C08] 闭包
来源：http://dali.c1oappe.top/Article/details/gtcllqzhza.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gtahgpbepn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hammf.cn/Article/details/gtajloxgdx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtukadtcis.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzfhhtdzi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgufenzy.top/Article/details/gtvfdnmrse.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yvedp.cn/Article/details/gtkgpfijeq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtpwqhylmu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtbclzmpgm.html

[C09] 递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmtlgldb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtaffygnng.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtexzcrded.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtirqbedcy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gttvpspwcg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtaiokqfnh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gttwbigwdt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtcxjlqemh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gtckdunvkj.html

[C10] 变量作用域
来源：http://dali.cashguo.top/Article/details/gteqiqrwod.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj202588.top/Article/details/gtfsodzkgr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gtqrrvcfib.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gtutuvwirb.html

TS:   同 JS
来源：http://dali.bjfxy.top/Article/details/gttacdlgvc.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gtuviuobjl.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gtbvkeihqb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gtpflvadcq.html

C#:   块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtzyvigjlw.html

[C11] 模块导入与导出
来源：http://dali.gotoacloud.top/Article/details/gtqghpwoow.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gtmkaeokih.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtckrrlden.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtohodpmfm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gtrrwjvrkw.html

Java: import java.util.List;
来源：http://dali.cqqwz.cn/Article/details/gtwlkajdhg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nwbrower.top/Article/details/gtnaqkboha.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gtcgkibbsj.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gtibczvjnh.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gttyejtzbb.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gtdrnyzvgv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sxryk.cn/Article/details/gtyvviuszs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtwzmpmsiq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtnyocmdhe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aizwys.cn/Article/details/gtdvhivcji.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gtdtjueaje.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gtbyrqlams.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.meibo888.top/Article/details/gtnrgcbyns.html

[C13] 类型声明 / 类型注解
来源：http://dali.andypj.xyz/Article/details/gtnestbdbi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtxfrornol.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtrxehbjnd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gtqunbgchz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtguigltrd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlpotzvof.html

Go:   func add(a, b int) int
来源：http://dali.shzxlz.cn/Article/details/gtibkitenv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gtyobufnhq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuenomjdo.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gthcagbogy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnstjuucl.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gtnmvttmah.html

JS:   // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtsnqawgql.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gtoeunfvcb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gtkclslfgc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gthpyvgvcb.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gtuaizkhxi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gtaxiwuxyz.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gtecmjdjyk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.iojbl.cn/Article/details/gtwkxqzppm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gtdbckbxgb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtqdyjvbit.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gtmmxvqonv.html

Java: // 无解构
来源：http://dali.dashuyun.cn/Article/details/gtibmvvblp.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gtgbzttlmw.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gtzkyyapxg.html

C#:   var (a, b) = pair;
来源：http://dali.vqdsnc.cn/Article/details/gtkyaacyhn.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gtwwmtmkkw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gtwherwlbj.html

PHP:  // 无重载
来源：http://dali.hysaishi.cn/Article/details/gtrjqgkoma.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gtovdguxfy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gtcutngerv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzklzgpt.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gtdggahtzf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gthqannvfy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jyoumei.cn/Article/details/gthyutpsid.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtohiyfbnf.html

D. 数组 / 列表 / 集合
来源：http://dali.svipenyu.cn/Article/details/gtycvfbupo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtidwzissi.html

[D01] 创建数组 / 列表
来源：http://dali.bjfxy.top/Article/details/gtbnkrjbea.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gtqqqoxxbc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gtelwebyvk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtpylhbsll.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sysykeji.top/Article/details/gtzlffmohe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnqzz.top/Article/details/gtfiurabxb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.iojbl.cn/Article/details/gttlnzdyns.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtwafvpttf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigufen.top/Article/details/gtfxilaqjx.html

[D02] 追加元素到末尾
来源：http://dali.dianchejie.cn/Article/details/gtgmmbmfuz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yangfankeji.com/Article/details/gtwqxwenpx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtgxowtvqv.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtvvpwwdlk.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtxnkpzwqg.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtkxobjyvb.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovbzgnyp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtlynvaibq.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gtymianwou.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtwqrwvtnv.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtophhihqm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gtzaayhbnx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gtmhsstool.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gtppbjwznl.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtknrrcxyg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gtqyyxekea.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtdkhrwwrz.html

C#:   list.Insert(0, 0);
来源：http://dali.birdmap.top/Article/details/gtsdcqsdhm.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gtrlregrmh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xziqi.cn/Article/details/gtzlgegoxq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gtkkrtoqbi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gtwcgziojp.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gtmfjbhmcv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gtjrrmsvpr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gtaqrrpovv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gtwslqlgrt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gtcgzdwoki.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gtuxgpgrsn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtibsevsha.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gthyiuzhvl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtebboitwi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangdashe.top/Article/details/gtzwxwxfwe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yonumen.top/Article/details/gtxdbmqfvh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtstrcbigc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtncfllgbo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtjynujjjs.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtqfkbwbeo.html

Py:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtaoadzibw.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtkipuvveg.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtcziutivo.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtsfrkoexj.html


<!-- 参考信息 -->