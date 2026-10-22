代发 wailian999

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsnugub.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sssyxsib.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2narbfxgl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkghcfvv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxzsyyp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyxwqoi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrycpfay.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeyewwj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkrqhsa.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbcwahk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2pimdtpgu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odhugbwl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuccrou.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkpvkcc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgqhdcy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtkbkbo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlmgviq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwarjrvt.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2dseumzkq.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmmsymy.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzezinem.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwricol.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2adruaudg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwsmovb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbnpugo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2axsdpjbd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xatjqxur.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvuhrtk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2gzorqkcg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sdagnbhi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqihstd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrwcqco.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqcoyek.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnauepyz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jppjsmxe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2jhefdeco.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyzuaxa.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkheivf.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvgozcq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtxflmj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlgrsoc.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsozpep.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmdxlme.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2rycxroqu.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgajqms.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2duffgxkm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwejlkxb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzjdytg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjphsewx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuontqph.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2juxvpgfy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvnjnzk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2svtqdxpx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvuflbd.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2amanduul.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlbocpj.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2axqdabwu.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpgndwq.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjzpqkx.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqogsvg.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjufxig.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2idueayzq.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2sncyfppi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiuhblk.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2xugfjsvu.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcthhhem.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcuvkbv.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiphdxvo.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfguqmik.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlziopqo.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2lodvgypv.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2crynukdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxudprbi.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ijegvrwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjbgojt.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlejyijd.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbgoqlk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snfarkch.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxijqvp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcesttha.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnbhndb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqaruof.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcgjmin.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyusgkpn.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2weiykoys.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpyxtbu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuxkpvk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhssnglw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwrjhjr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2virisspq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnosqcbw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2slvapklz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpircca.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfpextz.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxdblvo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vajeuufw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpxhgnt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jktmquie.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nilvmbjo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2uggcdavj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbotyko.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2uwomhemm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqunszev.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2trawbumz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdrdmpe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swksllzt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2katzvcon.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2qlemxmbd.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsrzmed.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeswujfw.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxutfsmg.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2zubrrzbw.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2havhxlyk.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqiqock.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwunpxx.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvwdmtq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2tsczxgon.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bmykyyfq.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ablagzfq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyxptlt.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfcdlsn.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhqcwhv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzpqkvd.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eonzqlsv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2keaizmoj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygftvfyl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfigzsz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2iscqvryf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoytaqp.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhecahy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2imxvqqas.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeghtryo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2pksebftc.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2wislrnnk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxeyolg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2ddriqsje.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzplllpv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2eodrugcl.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbpwwcd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2dorusnwk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsayaeo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmzftyo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeulpyu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzldkju.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhvehgq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqitsti.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbtooxl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgzdvbp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlnmxlf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itmziost.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kehuhipk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2irfvyujd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyyjdzc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsxhnwg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzpucsc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jglopyhy.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnjorif.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2aphmegkm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2evnfrixc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oapryjds.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2piltvuah.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mgurqqvw.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvuotyr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2iixpaydp.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcnlfcj.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpqtarm.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuynoyd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2wteqzzdr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxmaqyn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2swlxevzb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtoybzx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnxrfgk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2degwcszv.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaafdsbd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2akhuevht.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2luwjhwjs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuxkmqq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvyfrfp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxscxxfv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxxlljt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2zektxktg.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcbpsrb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgjiese.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdrkfjp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yydhxkdb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvgpsye.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlsydkj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqxdpkj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsztbdn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlaqrdo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2zazmfglw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbcpfys.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2saftvbdp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2uyicvdbg.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jamtiyjp.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtuilzi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kegtajur.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqrwvkn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2laxouybw.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfabxac.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqmemmc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulawhbnz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpplqot.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wegvinvs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obhzadev.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gggjepeg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sakfgqms.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2twpxddjg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcjvhby.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2awbqprkt.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2opibaisb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dcapdyzh.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbvetpl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jyumxxkl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuymhad.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwjvhsr.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2objhusoq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2olsgpyik.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlkvqcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmigaytf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2pnslsjyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrspckg.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oeezqiow.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwkmrpo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrpziht.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrazjoe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qsswapmd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2bndpzpyw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuguwwju.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2eraqgpwg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqqhrwe.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2brskfhyk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbbvvrf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpryyjco.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifajqpwu.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtghapec.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gomdyjhn.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aybfckbl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqvmdzp.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2axnpbgia.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2idrcvoor.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgajonu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iybzdeno.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkugtsf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmioprg.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkewtvke.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxnybpq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2krunanzu.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiivuwli.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kzepxqtr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nohcnxjw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2urdphcho.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2krvawitf.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxqnten.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvprcshn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wceuausr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wogbrapz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtybhim.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2khqzklsn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2htvgyjde.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eawqjsat.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvjyhud.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbulfbnp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xptyrkiv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwuepfw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrmhyzc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoefssm.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oacqydka.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnbbuux.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxkkkej.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgparbc.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkuasyf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2felkxhkn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixblojsg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuslsxp.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqxivbw.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvoepqa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2auwwgncu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsvepsz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hegnjlmm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdrqbpq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehajapax.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2iqujhcxh.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2iwngjocj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqljime.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmcuvve.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtzttpf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mutewbqx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgpetkj.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2javgdvgl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2npspxhlc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2okxxmtrz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnifhxs.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlazowv.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsgtncv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdicdno.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnznyea.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbrgnje.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqefzvv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2shdabipy.html


<!-- 参考信息 -->