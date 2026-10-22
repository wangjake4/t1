代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeibaar.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwofrmx.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiysqbn.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmcshdz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhixaxv.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erjvuaqm.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aczspuyd.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfpnmcu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sftpvrjd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2osoqolba.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpyhguw.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2weymguhj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxbhzwm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsqioem.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbcrztf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqplerm.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkwrhwq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2huinlwip.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkwsghn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjgjniw.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2womgrwok.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsncqqj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2illticyh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzgcnpj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdozwlta.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exilegkg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgcrsdq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfdrxtr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cubvjket.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqyaerk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvyevdc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szoztdnc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2mydfdqdw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdvgxwv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfpcxsv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwotquy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2slqmsgmt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgmcdtm.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmgbhaa.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2nygcluep.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbrtnrt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjdjymo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbtiivl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2midkxtlp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhzyyig.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjvfubq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tspouwaw.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eryqoszi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyvveld.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vklgpwco.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoigoxq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgypguvz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrimsif.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2umxeutox.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcnpldz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2feclcfws.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2csfmswhf.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2przkfpli.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjvilxu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2swkgxdfl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2guijiksn.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2uynklbka.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwemocv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkgfyzy.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbpcgvp.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2stkjugzo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2odqhyiqs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzvkhcs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvxxzas.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2owxdeaxa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbiitev.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoxuxpu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzwylon.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaburvi.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2hvldwzvt.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2icnufwvy.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgcfwvr.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvhvrjl.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2umxbmszm.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fssvdvfj.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vowcmsai.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgitmmy.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lgarpwdo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2asnurjbz.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2gswzramn.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rczokbxt.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkdxgar.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdsndwa.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtkudht.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfukzyd.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzkerds.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyuwqlg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amlurnok.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2afpwvyho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szgsnnwe.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usmgqhau.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkewylq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjvjhaz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvozwzxy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwavusnp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cswbzjfc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyozfdq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kaauurhm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bngyveua.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxaagxw.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2vecodzey.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxumvara.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2siprspff.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxftvax.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtnzpve.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvbtkud.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2drbtwalf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jntvtbvc.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlffpmu.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2czzsoknv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bymwycjd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uynbdqyc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrhsafn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvexqpzh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyislwkj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjknngiy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2usyjctfc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaaszda.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmqzxtr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvygroiu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xklrbyhp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqrusmx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2dsijwybj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmdhayk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuowlkc.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqsemkv.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyebftq.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyxyglt.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iolegyuq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdbwvwe.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2grgqgmmt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkewgha.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2alurkuyg.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhiique.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2gztkvcqj.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbrbirp.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2qigpdlaz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvrcdkx.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdulrpob.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdguuuxs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmilszl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyxekhc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnisieab.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbyyybk.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2peymzjmb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2lihjkewb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaxoymm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2osuskbvc.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2tynggtsd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyndjri.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2npzgdexg.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjekdeyd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2jyllrgth.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yrioyuyk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbnupvo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlydzvk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivalquiq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbwgoom.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzbiwtm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbayqeb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcirvpk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwwvrfl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vseplrnc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiprlcav.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrexycj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbfreak.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdmnffo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thdhrioc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sszicltu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrbaios.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tijpgavf.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iydpkpnm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2uzickgjy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbvcfcp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2furnasom.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hmegjdnh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzojkyl.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdhyler.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2accylguk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tufsxnej.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfdrxpu.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsbzyqv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2lunaqtsb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjozrbj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhxwrkh.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2sslbsxii.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2srlpsivd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2guufxtaw.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoosshu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlvcbvy.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2llsxhrtw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmigwfi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxkurge.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lcituikw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkuvbun.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2aajgjygu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuheizj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzspwxb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2yaowgsqc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jldgtgiu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvlfudg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdgndup.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2harbtepr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsphqsp.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqludhd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdysyekk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2liedlahi.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kflscent.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2elhcbcwi.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpvzipj.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2uryyphim.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgovihqk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmduyku.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ourvhqie.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xowdirtj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfchjnx.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2svyjoudg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2zoppwuph.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yctebxko.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnnwmqx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcehasxv.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjlfgly.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sthmfwtf.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2tyskaaad.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzfklux.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqtztsy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gueynzcq.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiuugsb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dryoybim.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzvvfpu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiwoxye.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjsvqvp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhfpbtj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lojojezi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knnxeenz.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrzbylu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfjkkwj.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwizmhu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2txofltcq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ewienffg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnqszij.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjlnpue.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuommwz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxysuvk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rotkbnqw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfyqsge.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xutaklbm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvjtanb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2juekxnvb.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2boewbgvr.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsjxbtw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiteuyy.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfruhcdc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2flwhwqos.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2omdrswwn.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2slymguqx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpqtfek.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoyvmwr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cklphpkj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeyncpg.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjbdhzz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzqmglw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeudpdzv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqgntaa.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcqnvfb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsdlewb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmsfydk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqxhxll.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsxjmrd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqsebfs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaoeddk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhccjxmy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhycjgio.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgfxrnc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2riylfroz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfxuqrt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtbxtli.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsqmxhx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjrlain.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvducnn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2saiciiev.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxwkeho.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvcnacv.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkucopt.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlnfdep.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wsezkewx.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkvvjal.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2bsltsiuc.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvkdrvl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfrrfen.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrzfnhd.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2etsvknqn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2parpbhdt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrtyqzd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdamprz.html


<!-- 参考信息 -->