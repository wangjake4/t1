代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlmxymy.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gt2oyctnrjp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjfclzn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isoidoqr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxphjnvs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2teypyjqy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzizptep.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfepomu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2goigtwte.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbhfiew.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2degkglmj.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyoxgpt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arkpmrvy.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wecvlhuv.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgyymat.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htsautpl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaybsmj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffeczpeb.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmqqwbu.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnezyfy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2apkcrszh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2frtbhxol.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2fclljwcj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoesvud.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbkclqq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbncfjnq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgkadve.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfzebyq.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhnibgf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqehvzo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbplwhma.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okbeklqu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiyggdt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfukodo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnuqlkt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eseybwor.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osjdeqee.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2onnxddmi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2pouxwuxz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gejtwqcf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2pkullbvs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2pobelste.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kijxxpud.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkeiaex.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjmrapx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlilckt.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2ikujdtbk.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qowzsebn.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjbadrk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2phxbuucj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpnyice.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvlmevk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2fdampibw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2opxlvlzc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2evfulqin.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xnntkimy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2eduozdvu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qawrelle.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2whncuyfg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqwvdqm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjlbwuo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojavzauw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2exzntuzv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2slcuzyvk.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2etxesncg.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwewuvyz.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuasqchc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtewaah.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnxgtnm.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2jwspplqe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyzfgmo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2uurojkkh.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2smerhdea.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2jotxvtne.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwawdeo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzqvnrt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wygnvnqz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrylpgb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tojwjfyf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgueqydj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuowhdcg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtoygqi.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhrdhob.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuakmsf.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ptblatli.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yufrlhxf.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kwabszak.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2umcozjzf.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2syuynhjr.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvrryhc.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgxbnkm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjhsvrb.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpsnfai.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hccywjwf.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gapeewfb.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vklcucnx.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkopblbf.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeftwqmz.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlphyqk.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrabqxfe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iagtefzu.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kycwlesr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdqnmxg.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kinczxaa.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmssqss.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhptxejw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snvpybrn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmkwbpo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpfmdrq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aesqkbrh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgofklj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjjpgkg.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltehubhy.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2oolfcckg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ribqldgu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soocockg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awhuznzz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dakquavh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsymhrni.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhtwcss.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2agfezwpj.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqzofcd.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvgjrpb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkghyje.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlhoair.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kehmkqhs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2heoemzux.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekidaxmc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtplxfz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvassei.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lultxipz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2knxuwpic.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwblumqj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bivqheow.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gghdcsxa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnahabi.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dteuqpmq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwosksr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmfqdid.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpxbfpv.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcgmdaf.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fxluyuax.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhsrmbn.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbfbrqy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2uanzpivb.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsybstu.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uebtiezx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2svpoknhf.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcjoyuy.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2fecdmwbm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yydlaylg.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gljsvafy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbycvelw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqlxstq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwtqxnk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lggcrnmy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2utvbnbtz.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2axuvjxog.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiuophw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffijwxsv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyttqfx.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfxgaxo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qamxiqul.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2eouforor.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2llvunpcg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsajnlh.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbtmlij.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzvvrya.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txmkrhvq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtqzttd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjehoqp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtfwlbz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrjjotx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mulicoah.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzhivzz.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhvikae.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvwdmvy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcnyaku.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dsalunye.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2evoecccu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcusbpj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoayhcq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyxdvsf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfbfzto.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaythls.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdwazzw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkwkmon.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxpiaiq.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlmyvii.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xojhehdn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2totawehm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2gzorzrcd.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjmgxla.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmtcjug.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2xytqadyx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjpcbje.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnlnfxg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsobxcf.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2lumeodgg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2oypiimnv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbdvzkx.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgvlwnv.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwwbxfj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjmobce.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfpkjcv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoshphy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaaplwe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvtwoaq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrojapo.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2drucopal.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxhgayz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmlzoyv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2izsttzbn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbsumto.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2fisgnssb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pthbjpkp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfuaiik.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmburte.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpbnytj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2kztifixj.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyuktxc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfiwnnk.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2isftjolh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2abgwuadn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mevhieji.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2glujsoba.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzthmel.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nozvqflz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2rejzarjb.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwgyhgh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyqrkix.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xytrannr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwdmnda.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpokpbv.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yiawhtco.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgnfnfd.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpnjbyj.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2inmtjuwe.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2quillnis.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2carrjauf.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2sghuilcw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpncrmb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbtufew.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnnfavm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2nktsmrqf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2blfijapi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkadcyxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obkcsrga.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbqmjqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvoujbz.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2itwkdtfo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiztqie.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyhxxca.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdyxznj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwvyecw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiebuxh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2idgydwlf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvynpph.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqwhzki.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdzlhjc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmhfbfz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgwgogr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxbmlts.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouynevoa.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hivkbrbg.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxdaldp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkgbcla.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqzpudo.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zzusxceq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbzhesm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqksdgxg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfkmjds.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2huouenez.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcezruyo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwgmfmp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yanitiao.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmxllxx.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uevijtsu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfwfzzc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cersdjpp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjmvmoc.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqjhplt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lixhcikg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2caieveuu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrviohfd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nihufqir.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kaugxzss.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsuyxsw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2acebyurc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvwliyt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcunkvgb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaejkdl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2asfefxvp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxtmsgx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2txhxswlj.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xnexnimh.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgennugc.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqoyxfu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oefzmkkw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wcntoxjz.html


<!-- 参考信息 -->