代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsiixaj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhoaxgm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnvhvgw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmluqgkw.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlnkjjc.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gt2prjifezq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnayxcg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eanwkjfl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njfpekrg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2netzppim.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqsjfkb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrzamvo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imxqxquu.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gt2aekwenud.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkycnnw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvfdajm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2esxhngje.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwrpwwb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shcjuynk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrttpsj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2shjhnavb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfvoale.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jvidurwh.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtappow.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diacxehy.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umovoebg.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpklpmuz.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uibitdzu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2aalidvvu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qllctpdi.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khngeocs.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2twxghdyj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2teqmayzh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubauzzqg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiiseoa.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhrajkg.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2alleslpm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjroudc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsmopoc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2aduvkkfy.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2stfegxry.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmkhmcu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apssjsmi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esdypwni.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnwsxtp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtmfkhn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlponapa.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfrhhdl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sihkprum.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfnozwd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwvqnfv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moclmszf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiybawd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2gaivkkel.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pelmryhe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xisdtxjj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkzfjqm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uipalglk.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoqbevt.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmadjzv.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcolexqz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytydcduz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsatryob.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qswhhhvv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2agznhtrx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmeqetg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mowyccot.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwfkzkk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2vtahdqlw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2imkgwufq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpwndvk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2agruixhl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqmzzds.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftanxblc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrosfip.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoujhqg.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bawtizsj.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2gakhngqv.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxykpnuz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyipoafp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxviitjs.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2wusreihb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmuotlf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlggnns.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2ughhvqjn.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmkjvbd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgvfjjf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdczepvw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjcheca.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrzycwr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iesjeryl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcbopsi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwprytj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2khkwlpqz.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2matqtlwa.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtcvzte.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcudyjf.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rimnashe.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2spwhcaut.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbmgoin.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsvxbas.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jwepxufx.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ghartmhx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2beycqagz.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2tuexkeko.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdrkavk.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gngzkvru.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrijbsa.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2anvrljxn.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjjhumf.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwctbte.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqcpukm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tctvtevb.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wktqddpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiqdiny.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrulxyxo.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvsrkxc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxosdqxt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxsuxmo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsajuqer.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwktsko.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnstwwr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlzjqke.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfwfxqo.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tagokbqy.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2udazuouq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdzzyxi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arjldplw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfagaycj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2todhesla.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxpbxjw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmylkid.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhddvadi.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzezxja.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqyvkle.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwgarfv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvgjxjb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvudawi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvimdmv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyvatxo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2isdmnuaz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvsetgl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrfwmyn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2szdjotgx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2buwllznh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agxwbhsi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdpszqu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxzoxwc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvbsdde.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2owacgndn.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpksotk.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2jelszsiq.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rsshhcpt.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqwkwct.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2lknmxlze.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qyojufnt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwiabcm.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzajlep.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qyomplpr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvswgcw.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2czqmafgr.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2exhlfnwr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjkzvam.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuelamr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqavtmm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxssfpl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2webalngs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjgwzrx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiihkxyz.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2tftgihvc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2yozgugen.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pouqziyg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtaphnf.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqybifdl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jalnqtqp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2kglfhzsq.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlkrage.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2eemkjrmb.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdwntzh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvkmxwd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpaycyf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okmfwkeg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrqpzqn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyrgfzn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2msiuexfd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2spnrzota.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwnxkdh.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyuzegv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2doxfrsjv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgbmflg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvwzwyz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiaptbo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whcfdxyk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wphrivgv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pisuxoim.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdutzxs.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgdsfkx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbfrivs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkpuyyp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2csotkspo.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2effsnbcz.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sclqkcyp.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2shzvfeqy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdvjtsj.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qtafqjyl.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kiimvlje.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wfutpeyp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzrljci.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwydhzhg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2tritvqns.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfazdgbi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2lhreujed.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfsftue.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2dafhimoi.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjloatc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoaoilw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hlftvwyh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzosovw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yntyysyd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2efmvnehg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2repufpku.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsfgqvo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyimfyf.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjsznzj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhgylab.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhztpyam.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcfcsvi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgulllkv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkfqeot.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxupstv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfwczgy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2siijiaal.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwaulap.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2qjduvlsc.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ycytlhov.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtruaoa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnfsruu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntstahqm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfghuggw.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2crbflhfp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxpqzbk.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jeutngmm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgszxkl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2brggsrqs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlqsbtt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvssvgf.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2udncuxvy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwdslmw.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2suurjziz.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsmbbxl.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfumsrb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qffvaqji.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxdwjqb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2adbqaavw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kexuaeuy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsrugdz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2whgkcknj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2snrovnov.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2holsnmob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwunwckr.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ooubllcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2haztawpk.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lccyarfi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2crqbvobm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tftknjne.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxidfpc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2udwkeydf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlbishn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfnpgoo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mfytarhj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlzipsy.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oukqdbzh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2utozyops.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmdjpbe.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iklhrkil.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvggtqws.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oolurcbr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbloqmch.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2skhbbgpl.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfvuumg.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvvebiy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzqjiwg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqznqdwi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdrmhrx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcyalgs.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2msmywolq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2aokzielj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2agzbvzkt.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2abbynqsg.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqqnncg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2asftqaav.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyajhhkl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsokasr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdxrtyi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiexgql.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iihqkrpj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxyyteo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzhezqm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrgmnon.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2offgqlzt.html


<!-- 参考信息 -->