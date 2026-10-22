代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzddihk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbmaqjn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoorpzd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cphewrff.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rilewyyz.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkwortl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjrkohf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2khzesbsj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjueyacv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfmjnch.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2byvjqoyu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkzwovj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyawtpr.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhmvdwo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbsqfsf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikzhjkk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njpnyydk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwehaph.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eirpygzi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2decetpmi.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwimdngp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqmrngi.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyffjdl.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cneahtww.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsndyxn.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qznqimmi.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjioiwr.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmqqrdw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnqlfxx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjvxidt.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynylgjqp.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2pllgismr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpwwgez.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2eylqedmw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxquwem.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2noskjdrw.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbepmzah.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkspsslj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhbywxz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmxptrz.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrxazvk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ziipwaek.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rihyipqx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eohvlznj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fakfgbah.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmapojzm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulozwrmm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibizwymg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzzyeuw.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tjijexxb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2nduvvypv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrymydfr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2prcsxwtc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwyexrv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2daibxaip.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhoeqie.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlqxxpp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyhzsfy.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2xttouvos.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtkncsc.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2upthuivu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2skvfjuef.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgkcyfd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2udfzhxfn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2shfpeqev.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2macechvw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwludpdq.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eflfsjnt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjrfvcl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wztecggj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvjmsma.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgevbbwx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbpbfdo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bclkbncg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2prnuqmoq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwrpvvw.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiyliyg.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2agditxsu.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcsyzuj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahslyfpk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wssyscbk.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwxnxyg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmfocje.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhpslzu.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyuwqqe.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2faxtkrdv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2sswyysir.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qccfcbtr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiislau.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyglknkx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkofdlmz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmegldr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwcnunc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nufdjuoe.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsiknup.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2drntqvof.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2raxnktps.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkliaqn.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuuprfs.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtclhxp.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2oesjugjh.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdpaitt.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yavwnhrh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjbkhxf.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2obyhzgwt.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foxpywru.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkmlwdf.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjksgmmm.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjhtnbf.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjzictd.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkfrvhm.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2okgxbxuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndundksx.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kuevjaey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itbeizee.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxefhqk.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsqlwws.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kthnzjso.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqwmthn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edcysyos.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcyfyzv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjhidlh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmmnhgw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egcuuxrx.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2syshgtmw.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2cgilnzqm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzxvxpm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aecddrez.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqzgwyi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgrrbir.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eygxcmva.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoyqpmd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eutswcry.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrggteb.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbxemli.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpuiteb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpgzvxi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjavkjim.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjgaxsj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2oajbldde.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjtxuym.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2kekssefz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggekgiqc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxxoxtw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdehbxhi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hujwgael.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2szkhdmvd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2eruynuhh.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhvlmyg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrwddgo.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyflxgj.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2avnljwtt.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zprcamra.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2slkdcpey.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzufigy.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2udvbuavm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjwhqps.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xcepakhc.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bfliqbgh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2hprtypyj.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2giniktep.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2irefbrha.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwbadpg.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gazornxz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kivbhcjs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtarwndj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2aygvaghj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqquemmj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcvphob.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqeghxt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdhagyx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgjnzgf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2vogtqknm.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2jerxqduy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxssbkqu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdwvydc.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2madgbiik.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhemzmz.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dfspmlyi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsktcwu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbilbch.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zojookor.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aawxvvle.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxqlhvy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpczgvg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwytvox.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnxwztl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wzksyhth.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2veupqwem.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlmkcwz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2erliywwf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2yqprcaxq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyeqynu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2goloqdys.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfjjvqj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmuiswu.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hxivmuza.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2vijxlvzk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2avbwlhzl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2czexsnlh.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqjaibo.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cqufmbrn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmdwrbg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjnqqqa.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzrtmye.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfgqmmt.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2hapqlotz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxtwowz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlvuewp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2srmdqham.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryueecdy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2dufaecam.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2otkfmjor.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiujelp.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2nxolnsbd.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmwsyzb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2csseyarl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzvnkrb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkkcsuu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ompwssmp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwhgpbd.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2tceiptue.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhuifrd.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2lsswzent.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2werwqoxc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogewekmj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyefbubf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuwmsbl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzodgyd.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqtkown.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lakliqwu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2asrszzmm.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqcxbra.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2rlobhsrz.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2adqyujfb.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wskoaclf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijssjvkq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyjdbac.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tevfzrfv.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cudylcdd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2befyoqvh.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eamglcvi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2gizkapun.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfwyroz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drxusjwk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcchvlmp.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmbpkxp.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kixlldwx.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdtcina.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoqoxrt.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2avkhwmre.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbqifax.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2sxucmdii.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlrrhxj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzfryhb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2meynamng.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2hghxkkix.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqxkbak.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxttjlh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qarffyxo.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2anncbixq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snhnovtv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2izpcuvgs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2yllsvcaz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mkquoeyj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jooakgvg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtukmmg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2cqipwhgt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqyvocw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2icppnnyc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2glsxnene.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wgujbjyj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2cagepdta.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvbtdsh.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qydjwahe.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcrwayy.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnodgsk.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2usyenhgl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtafekn.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hklkkxkc.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hplilaeo.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2atetcgyq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnquqoxp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2htmpjboa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnwzofu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrkbbqq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrtrxcp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlevdne.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2flvcrrpp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpkmhna.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuvsiwx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjdfsin.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hoabwdzu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcixqsc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoalqbps.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2conhsppj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnhrnqu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjaatyj.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bgevyfeb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2obmwibfd.html


<!-- 参考信息 -->