代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uquqwnfu.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdqodya.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pktdqmwm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygywozcl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcnhhlg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeqahke.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwikgcp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsnqbzb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsnvvto.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnwvzxv.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmqczjj.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vydgqqew.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgytykx.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqfqxts.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2regoiolu.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2geampisv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fkccnaxr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnuapcb.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfnypep.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkektkel.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrticnu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvonwbbm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrufdkes.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2yullwmfg.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuxxzvh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvghrptp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdgjewo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2flwjicnm.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2jorqgotw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zdguvpwm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqqxxiy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etkmsjxy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2waqjcsmz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlagxzl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvlqpcc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdkctjx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgazpow.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2byyejboy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2uarcevyl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkihjvxe.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtkremk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2spaqjwyn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2objjxnss.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sudtgvvn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vblnxuvy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghiqgxdv.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2niwlglmy.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpovllf.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oncywcpg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjbwgxg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfyprva.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwmlrni.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcerwql.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jithhrzh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyyqzzt.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gfurktko.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2sddyhzdh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hujvzkif.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aafbtuuc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nphlvluj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqknqid.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuvhjrt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tczawtgj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmosknx.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2enlllgaz.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2kitfkjzx.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dimxuxjn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhssangj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wldcxois.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2srjepxoy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcedfian.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2suyhabxr.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2emtirwpy.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjvgbqx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2whzkryde.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwuozkb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2grgkqtcy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2alqxwiyr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2adkzwyvc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fngsuyxe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzgysan.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2owrewhsv.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgkuykx.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuqkrhs.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeumfzi.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wblrzzbl.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwessbx.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsclelg.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkrdbgn.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uruymqbw.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2msmgefvu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xbduaedn.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2avkaiqbs.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkyjvvf.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoojwdm.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbfuikq.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojldfqcv.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwnoppp.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2cmipvizx.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkltxdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atrrzsky.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpujtlc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjdpzud.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hagcymba.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxcqivc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2peoizowt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeixloid.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvaiawb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iopebhbq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdktkhac.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qslqrugv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xparrpzn.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdxgxbl.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsclnyh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upwipejs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuftkvcl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okjmkbqe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqankcr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrguaqz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2toiqgzld.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lckeiqpo.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcwjxci.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsgmjgd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdbjsok.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqhlbml.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmakspbd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiumanxs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2espyqklj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpsooeb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeozsrl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnhnfxt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkznljwy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mipdfyrz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqekyxok.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yalfoemy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2yleazkjd.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcsewtd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uklngaot.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaxsqlw.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2yeleodxz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjuyzzw.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbfbcms.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyctxzo.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qewtjsfl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2immmmxzf.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wordtctn.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzklirg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgnvbtm.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gholhvuq.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2njzhgupm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjltrckc.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2devkabsj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgkdczp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qekcfquc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bonxumeb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mikpbwxj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsepgoe.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfxuukv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2hebdbapz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2smjsizwm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkrqplb.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmahlmw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjlpfta.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqxueac.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsokqjw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlzbbmu.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdtgytv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2hqildleu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvqoyso.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njhhmnwy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dywvhotw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2zfikbxxk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvotczjf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tulkunvx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtafkupv.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uzotihqv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oefhaoil.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkjeltr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vomwcyin.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvbihbl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fznivzlx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjgpuff.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjhcqkw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlznghrg.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjhxtvt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2omowmrpp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2jowazthd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lygzokyw.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eadgxycv.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vixxjcxn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoxabdn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2iggoybdb.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zccmajwd.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hthwkmwz.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbdzxyi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2blbrxpst.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2trhpnhvq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2owhjzyyd.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvdufxi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrkwshv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2sohfsymc.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpriwir.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2kosnivhk.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjjqwyp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsignio.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbefhhwh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaehhvj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwgnfyx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ildbqcpw.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2yevewmxd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxocjkgf.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2carzucmy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2altxjhoc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfgfdjx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2retysdbd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwqwroi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyddvma.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzkuest.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoyjavb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxwyekt.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czhgolsk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwznnbw.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdhmcta.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbtwcmb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vozeaotn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnjblwv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tykuaalh.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnpamtj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2lftwhkqz.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaclstk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2linehtrn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgmwkrs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sagmovzb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwezmiz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2blzxcbrh.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlcwrpf.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkjootd.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuyjyer.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzzgvts.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsebosv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dntcvqcl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyvzifs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnwtkwm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxemmvvi.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxtzsxc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2avmncddc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhifhcgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xthsriiz.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2typregld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxzeelk.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxmncwt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2chhewbbl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vunseqbk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2syqxsnkm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfnlosh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbzazri.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjseeda.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rblnfngf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qiriftvc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sxutqnaz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2yoydvgkr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwpyxsu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvexrijm.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnqhzip.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzutwevq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2unbdfoeh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wijtiemf.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eolnvzre.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nuouhtip.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2riateloe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaxlbsi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2easredzx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2blagrrfh.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnabyvy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbzaasg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnprnau.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfcoaxg.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkibvch.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2extnarke.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2btimsbtp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2cptvyuer.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgudxehh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyfxnsx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2udfvxyma.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2taaaszuv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgqphmz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2czxqunbi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaxllkg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaclbjnf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xilvzycl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xriomthn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrpdmbe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrqbceo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ognqajox.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwmcrsa.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lrocnslo.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qphkoevf.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2owviwdol.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrspjts.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsjpsjf.html


<!-- 参考信息 -->