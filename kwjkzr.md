代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcxbnzo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qccofbnh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cskhvzdm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uauuotyy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwcpxhb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qilcqaqf.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsgcubp.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyxrhxi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrolworf.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2higwwhqh.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asfglvkh.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhapnmax.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkocsgw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuxrbil.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxgyiru.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmpgvgc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhoaovu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqfrler.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnceqjl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2apgoymhf.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2efkpwvrh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2favdppqk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zpveksdj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlachzpl.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2sytrjjtw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpttsff.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvfozkf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfudwegm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgognzjq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuipssq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpynfles.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pupdeqcb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsjwpxj.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcftsaj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2wticclyq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uydxrhqs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmouwvh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2umwmmgfo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2veogeeer.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmeltuq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpbxbyf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlskpxz.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuqoudr.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2uustbwkg.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbycwxae.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2abejrrpi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpjfjcg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnhspdd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2trlxsdrz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkzfmiq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdbnggg.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2frnrypjw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2bgozmaix.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2puvrwiep.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yurshncy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2askmmfwe.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dspgsgpw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jviivasm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdunuap.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2liwbelrw.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lhznofgq.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjixmiko.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkjadih.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2impeismo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuqiydv.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2bqicuvwf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuruzylz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2jumzujfw.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpmrzsy.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2avywemmi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2xltteeam.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwqvylq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuzhits.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2murrljrz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcgakve.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2olianpew.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyamrrhj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmqvbgt.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2ovodrirw.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2csjrknsz.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2dsosmuln.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fbadcfcg.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrezovj.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcwxdjb.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhwslpu.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcdkoip.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2camxfflf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ponjbfss.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtkcwti.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wywyloes.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnwuliw.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvghltr.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfnjqdk.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcplcieu.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzlzlqx.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2covufcof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxypywy.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uahexidq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnexgwp.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2admnocsw.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzouyod.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmkahjo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrrradv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hawiqnhh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcztxpgf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkjapfm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ghixjhxw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfdckqb.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2chpkijys.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2yccjyvxh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqpxhvx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvoizfs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuftbrl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxsmrov.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfupwthv.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bonjsabh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfktpkbc.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrjqqfu.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvkpgox.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2urnxeiol.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcaaudm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxliiyis.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkcsari.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjqmrqi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sullrxzd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2znqvcwci.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzfacde.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpskxsvf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2crddhatu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eevxspea.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2atdhnmgq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2hugoklaj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooomaefi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiiynnv.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlytzat.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2izkorsaq.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2htncodyy.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2avfzzrjy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2eqccktbx.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2dythcxgc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2amrehebv.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fevuleit.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtjcwlz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2rbttlopd.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hzghetjs.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ecftmorx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpglzmh.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2heteeuuu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2svxtzdvi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2abkkjwil.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpzndeb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lppiyjob.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cklpwkhz.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2xvegmrfh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhwkhuv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeczgwz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzwbppp.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2elglmnxc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbfqyet.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2irlpkuqe.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2pylnwpii.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoxfchz.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2unkqyijz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2nikptedg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tynlcfoo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbgtqvy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpuoiom.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzafpio.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrixkhy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aroirbac.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvixjqr.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrvysxz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkttmggw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djorhzgl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kjymkoxc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2coeevanu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqludhvi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qykndber.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rudzkbcu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoknnomu.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtvvzhp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2svdibkyl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2sbobmmmf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2knhnymcn.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjdckoz.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vivbujxy.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fpibacym.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqwglds.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdcoiza.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlpdajc.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqrenru.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2kprhlicm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dumkxlpw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvejqoud.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2aondomzl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2idwyelov.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsqxobz.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsswultl.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbxziqr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2bblyntvu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2riscywgy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqapemj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kujzeujk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgfkbqo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2euaukegj.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2dddtcfoq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnmiwaj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2perjlvqz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvwfyav.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lganpdrl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2hymcnjdb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2denfofci.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhclxxlw.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2jahgenem.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdikxxlc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2valsuiks.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rirvqqjd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzteans.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbzanea.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fshyisrt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkpgcfy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imrvwshi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjzchuo.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2shzkhabj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoqkzkw.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpnzjps.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxiqbda.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcbkkew.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfxilbn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbbvalw.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpxpshy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2syuzjqgr.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmrmazb.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmyqctg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2frfcgxbn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbmomed.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkmhpnk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzeoggf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wxshjfmp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exiqnzez.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2olfbaowl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nemddfzd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhvlepq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcopdoh.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvfjrje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgukrmg.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwslvxg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbxxpkb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2razvflix.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvwejqd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdwadzw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpawosv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdygwdfs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeohchb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbiwhqn.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2drmzlgna.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlavqkc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sumgxjjn.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjiaacj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xodhjyrq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2omnojpjb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmobxpy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvrgmdw.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgduusu.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fsowbywq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqwxnio.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjicstnn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgbhapl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibilfuap.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmqfdiz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjxgatk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxaejgl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xounflhy.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uqspqvew.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxmasze.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtntffqq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfgvlea.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfzlhai.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ownjxjsa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjvcoie.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wklrqvjz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtbaiqo.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqzjkjk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwoiosz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvxcddv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2miroyqga.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kogghgoh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2okehkbnh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2snelavss.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwbeiqv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjswmiy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zppjxbbn.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcahpwo.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtcdwnc.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvelaml.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnmhkkh.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nafxpytb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaupcjg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfkupiv.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuyfbdr.html


<!-- 参考信息 -->