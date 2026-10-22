代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbfatuq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akezrlvq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clxjrptt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbijfri.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlpqbkw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lluuvqji.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mljkqagm.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnbrkqe.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baeuwcgr.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvqmbhx.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqzneyz.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txxhrtth.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqorekk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fraakpiu.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uauljvtr.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzolagd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2tonrxixq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlnbpad.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzxscrk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2omsekfev.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmguougf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhodfrwh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2klssipsm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwulteh.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuwnpma.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2opbnaapm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtevpzz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbgwxya.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldumfjnb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2endoqwub.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsknugrd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpksgvp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmpoywq.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2czzoykrx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2czoupiee.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilptzdnl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2vtknwekb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2xamdsnza.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmsmnjw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpmukpp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2urtobykk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mguoslof.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwgoiwa.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwfqdhc.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpuhfue.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhjutnh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2srtlcdir.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxogxtto.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyqlseo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyzivzg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcymtzvn.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2otkikioq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgnzeil.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdvqicn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sykfhztt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwezkwzv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtytcml.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cndfnvpb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvcqykz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqfzxsy.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2goadxcli.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2irnnvhlk.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgczcgi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2muzruybr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuxwzmz.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2cakljytb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgoevpq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiulfkg.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2glfvyjvn.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhfqzkt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgieqmi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbfflne.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2byopiuwn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2emgzgllj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xromejsk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzvpjrg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eojutmhy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqmjill.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcqhise.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnyzbki.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdwwyyr.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqcsfra.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiqqite.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fobtbuee.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoihezb.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2oiookric.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwqkvtk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vnojrljn.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhxiymn.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrunexf.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfywpgc.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryitqfnk.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtpytni.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejltmgcy.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ieexzdrp.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhujqddo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeqzctj.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kywpkorj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btcffngr.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tegkphbm.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmkudgp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxedetl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uohrofwy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msvotfpk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agaxitwt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjhotaa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsxrcgn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdoxjjs.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhczktb.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ethvjpyi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfnuzkt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crifxfel.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvxgvlq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zwomdzet.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sltsrwof.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zklfweqr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwmxvpx.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2moepqinx.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pptykpje.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2auazozdk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvomrjbn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaizxgs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaojjvl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2rthbvqln.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaxxdxk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ymornlww.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjuisik.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlgzjil.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuvfbrn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsrwiyk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xaafsamt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkycwdo.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqxcuat.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzqonzf.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeyuxne.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbheintj.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2tkufnywe.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbeempi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2duqjwqnv.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qqftjiuy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbbvmgr.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdkgjey.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2iknqycta.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgdgomt.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbqspuk.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfwrpai.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mygilybz.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyvcmay.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrazlul.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aenoiodl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2snwljlkm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2echdjpxs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqamwfn.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2hyatejko.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2uggxokfu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnclegxj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgvzncy.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfhjwty.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzeyiyr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwztxjq.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfowwos.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdyvhqm.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmhuybw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjovbhe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxcijfn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moocromj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqlpbib.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdfcmuz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uftbqdbn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2upcntkvh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qytbhtnl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2olmbyjnq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoztevg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2guzyshfc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vhupsqah.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2epygerit.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkddhqzg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzyzrdy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxliamd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxmxdjh.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2keuunpay.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzodgsw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqgzieq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfcepsc.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yjanusfw.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2civqklyu.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2egwetdms.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmrancr.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvwtnzk.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtnfyvx.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeesbpn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhsupwk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdyfnie.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2agjurywp.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpydkij.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2phqbgvsr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcwscrq.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbcmpbp.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjdddni.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuunphyi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2retgivnz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2llfjsoxu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbdqbgp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjihhqp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcfumrb.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2zqczqpgv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njnxmxdw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2eprwqzmj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmouyfx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clajizeq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2szmhpxby.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyyzqqj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sryhcnyn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqyhbaz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaojoou.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2fstagndh.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmdphue.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2credoson.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbkqbdn.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfweoyct.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbvafnx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfabuas.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cceuqnle.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiosslj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnsxzkl.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhzmgeu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrxqtan.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynypsqao.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxxtxye.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pplxxpws.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xgurtleu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoaqdgl.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2djoqwykw.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2roxhndww.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvsrhzn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxvmpjf.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrpisua.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpydlur.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sibiyoec.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owujptwp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2krqroepe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmsbnsn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqgmxwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqlxepz.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfwqkqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqajtpvi.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pakoznhk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxskcnm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fozlyonh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwykbut.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqcfdxs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdxjaay.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkohkzrd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2umhzccjl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2snhitouq.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgjnquj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2igxitciz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgptqij.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjhlmlf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmuzubn.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnvdjix.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhouhufq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2imnehjld.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gadoyklk.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyingmd.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuhsafx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoagbva.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvbnoph.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2itizmewo.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfzfrpp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuqdggj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mikvyyjx.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2reweccbe.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhxxogi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsloofjl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2obumrlmg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhahvlbv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdyjbqc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvrgots.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2obyinwxg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmyxhht.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2muvhdamt.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tmincnyj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqkpaek.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmlrnkr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pssdvhpa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwynqtum.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2htkrcaky.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoxelax.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkvffxw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uowpizvy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyozhng.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrybtvv.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzjvpbk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2klanqtlq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eddjoxur.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nircvvbz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnlsdcg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxgdlzl.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlrjzbk.html


<!-- 参考信息 -->