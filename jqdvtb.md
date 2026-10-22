代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ybcxt.top/Article/details/gtbpwjvkxw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gtnxtexfwa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pycfn.com/Article/details/gthtweyxwk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gotoacloud.top/Article/details/gtbamkrptv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cdnleiting.top/Article/details/gtpmmpvrrh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.aibaodan.cn/Article/details/gtfjthvsab.html

[B07] while 循环
来源：http://dali.0kj1m.cn/Article/details/gtjiyzpzov.html

Py:   while i < 10: i += 1
来源：http://dali.gzhubu.top/Article/details/gtofhdxfyn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjmrbzfs.html

JS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gtygkqsjaf.html

TS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gthsdfpygs.html

Java: while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtycpxgrdr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sxryk.cn/Article/details/gtobkfxlsl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pengpengdd.cyou/Article/details/gtppurfatt.html

C#:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtigqwjaqh.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangtech.top/Article/details/gtggprzvot.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gtehpbkodw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtjojzenno.html

JS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtklksrfdr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtlhyecgjp.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtgyaawewc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gthsmyfgzu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yonumen.top/Article/details/gtqqsqiuwe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtbibxqgwi.html

[B09] break 与 continue
来源：http://dali.xinyue.icu/Article/details/gtxzusxbdl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.snrcjt.cn/Article/details/gttfnzmvoc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtijhsejpw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtjlqykluy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtyjihkyax.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtmpgsqizk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj202588.top/Article/details/gtahlqycuw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yangfankeji.com/Article/details/gteffbecjq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtdxtohlwl.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gtzariosui.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuanzx.com/Article/details/gtqcvvwmcf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nanxinkj.top/Article/details/gtmdutwxvj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gttebmpvkt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtzkffxghb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.iojbl.cn/Article/details/gtobyugcls.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.iojbl.cn/Article/details/gthfgcsdwg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gtxvzfkdxc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigufen.top/Article/details/gtmcdxcquc.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gtukoneejk.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuetiantiany.cn/Article/details/gtmavsshdj.html

PHP:  range(0, 10, 2);
来源：http://dali.shuidangran.top/Article/details/gtzorpnckh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gttijxrgqp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gthyggzcki.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenlongwang.top/Article/details/gthpjdhdww.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ehwqpu.com/Article/details/gtynbogxxe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gteoxomvmd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cucudq.cn/Article/details/gtqycvqqsy.html

[B12] 跳出多层循环
来源：http://dali.cucudq.cn/Article/details/gtlucahacg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gtehxsksub.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gtfcbvnjdw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gteebohfvt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gthoixlinb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtjdfrabwh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gtebhqoohz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xziqi.cn/Article/details/gtdymqujrx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gtfifexlod.html

[B13] 判断是否为数字
来源：http://dali.mhx1999.top/Article/details/gtblxydvtv.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gtwvsfvrkc.html

PHP:  is_numeric($x)
来源：http://dali.yj20258888.top/Article/details/gtmnjrthbh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxaoscgvx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtmebgqbiu.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gtfoimghtd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgkoysmd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gtmkvhvfhb.html

C#:   x is int or double or decimal
来源：http://dali.cheryme.top/Article/details/gtzydoypth.html

[B14] 判断值是否在集合内
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrtacemg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigufen.top/Article/details/gtuvzuhlhy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjsuylmq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtwtdfbwxt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtsmguwsbl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtgefefaee.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cqqwz.cn/Article/details/gthyfjckyt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gtedvafnby.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtjfisvvtm.html

[B15] 布尔运算与取反
来源：http://dali.ehwqpu.com/Article/details/gteayhoupu.html

Py:   a and b or not c
来源：http://dali.nwbrower.top/Article/details/gtqgvnzzib.html

PHP:  $a && $b || !$c
来源：http://dali.smart0.xyz/Article/details/gtoevlzzdv.html

JS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtujtieenv.html

TS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtackimnph.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtzebqhwye.html

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtktgpipsk.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtivvudcnu.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gttqwxmrgt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gtlakoejmy.html

Py:   if not data: return
来源：http://dali.ehwqpu.com/Article/details/gtyryoxadi.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gtqphjkxld.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtukckqile.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtcxdbdioz.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtwaxogkuy.html

Go:   if data == nil { return }
来源：http://dali.svipenyu.cn/Article/details/gtgkpgcfxq.html

Ruby: return if data.nil?
来源：http://dali.cucudq.cn/Article/details/gtijyhnijr.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtngfbanhg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsunltcge.html

C. 函数与作用域
来源：http://dali.jqgfzy.top/Article/details/gtmmreqnnj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtywfeopjb.html

[C01] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtfagtqwxk.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtamnzzorf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtggbqqwqi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtipmdtgdh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gthbosawfg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtcnpnrbsv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guowangkeji.top/Article/details/gtxshcfgoz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gtdvchwflh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gttkkqygfh.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gtcaktfjgk.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtluhthdjk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gtmwypmpsb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gtipvvcwvk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtajavvean.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.bjfxy.top/Article/details/gtgkrojacx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gtvxbkbfqi.html

Ruby: def greet(name = "World") = name
来源：http://dali.cucudq.cn/Article/details/gttleavxqk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gtjueyognl.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gtbgszojyh.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gtfbhgqrey.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gtozaxxqik.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtfxkzdbxx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtpiqfhkqw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtzjcjzivx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yvedp.cn/Article/details/gtwscaeens.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gtrerrfpln.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gtryxfawji.html

[C04] 命名参数 / 关键字参数
来源：http://dali.316326.xyz/Article/details/gtqckrxrvf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtttdkgaxz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gtfiswyovl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtvnayfslb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gttmeadopq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daria6918.cn/Article/details/gtigmkgmdq.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtxejnndai.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gttviykvib.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtxheqvxmm.html

[C05] 返回多个值
来源：http://dali.kuanghao11.cn/Article/details/gtbbrwgqlu.html

Py:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtrnkgyetr.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gtaxwngxms.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtipebdkaw.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtlhtirdfc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gtvpuobolr.html

Go:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtkgtznkyj.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gtphyavmul.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtusvlctlp.html

[C06] 匿名函数 / lambda
来源：http://dali.vqdsnc.cn/Article/details/gtaeqbpddj.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gtrcneruoz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtllafnlfl.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtabqzcxnj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangdashe.top/Article/details/gtdaqrvgwt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gtrbkoobnf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtkxpkfnro.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gtjyowyrfe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtlaewlewm.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtegcjnekv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtuoatkkqb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xziqi.cn/Article/details/gtrncgaqsw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gtdhklprjj.html

TS:   arr.map(String)
来源：http://dali.yj20258888.top/Article/details/gtutklwckw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gtcinzwmpl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gtsignbpef.html

Ruby: arr.map(&:upcase)
来源：http://dali.zycfv.cn/Article/details/gtffvmhdlr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuegstjhz.html

[C08] 闭包
来源：http://dali.aibaodan.cn/Article/details/gtgpxecspa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gtlkxuiikb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fzhhl.top/Article/details/gtiyidtcqs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrobxqfe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtwwzejcnh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gtrdlngcqk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuetiantiany.cn/Article/details/gtgvxzfgjy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tanke756.top/Article/details/gtkonswaxx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtnbuecmax.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gtglgfugwd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtikwxngvj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gtvgfmekjp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtvihaxzbj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikrwgylg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258.top/Article/details/gtpntcjnin.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtjnkbydpy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtbctqgues.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnqzz.top/Article/details/gtajzlauxe.html

[C10] 变量作用域
来源：http://dali.pycfn.com/Article/details/gtkilnwyxi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gtxudicprw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gotoacloud.top/Article/details/gtddxzkinx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gtmejzamfo.html

TS:   同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtwogtjlpr.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtrkqbidfq.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtpdbxaley.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.haohaochexian.top/Article/details/gtazhanhgu.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gtoivefarx.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtwkwttrsu.html

Py:   from module import func
来源：http://dali.fzhhl.top/Article/details/gtuaexyecr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gtmwcqieyv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gtpuksmoll.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gtsmtcuzft.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gtyzrtcjju.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtuwwgbbmj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gthhuiosph.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gtvcmsqafp.html

[C12] 立即执行函数 IIFE
来源：http://dali.pengpengdd.cyou/Article/details/gtwrkrgdrf.html

Py:   (lambda: print("run"))()
来源：http://dali.gzhubu.top/Article/details/gtvsgjkadv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shangyingyoupin.top/Article/details/gtbgurosqk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtstxityoo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtynbbdfhv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.c1oappe.top/Article/details/gtlndecwlh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sxryk.cn/Article/details/gthvvdfmzn.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gttvyxttij.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.bjfxy.top/Article/details/gtbqvdqtqg.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gtjklteipx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jianghu66.top/Article/details/gtmpeboqqy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtzfldegfr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gteguapwco.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtzljokknr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtaenxcnwr.html

Go:   func add(a, b int) int
来源：http://dali.hammf.cn/Article/details/gtjtqpcrat.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gtxcxnbdjg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gtbedugbls.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gtublpbmqc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yanxiufei.cn/Article/details/gtdklbxspi.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgnyhxok.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtwvjyrinx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gteqinamzh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtlupbcqyg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gtupgvsykw.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gthuyosvrd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgfzy.top/Article/details/gthailedlo.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gttfjxjxim.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gtycxoywjl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gtcopkbkbc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtpnqbpxzq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtusibtktx.html

Java: // 无解构
来源：http://dali.yonumen.top/Article/details/gtjpgsnkrb.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtzyfcnczj.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtwppzowln.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gtwabjuepx.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtjudynjha.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gtvhrjezsu.html

PHP:  // 无重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprtormhm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aizwys.cn/Article/details/gtzpnhkrpt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gtbsgemkqe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtauvplbtb.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gtocntkjjj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.kuanghao11.cn/Article/details/gtvyrvwhnp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gtttscensh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthhvidlaj.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gtlaflosze.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtelscmfua.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtkaxrqjck.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gtpynvoxlm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gtjbvudgbu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gttmhsjasw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gttkoeplzj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gtgdfmewwe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtiamvksdo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guowangkeji.top/Article/details/gtirenbjeo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtfnyrmjls.html

[D02] 追加元素到末尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptyjzgwn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gtkeptvsvv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zdqjudy.top/Article/details/gtgwaeyryw.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtwvqfzqds.html

TS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtpktthlcj.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtohieanur.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqycitduo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sufxvd.cn/Article/details/gtlokgpcaj.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gtjnwveazp.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gtjkjuraxt.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtwpslslta.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtbadaltzo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gtkuavaoew.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtygzalikz.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtglduyfwf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaydwfyvv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sysykeji.top/Article/details/gtcxsgkzta.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtrzutqzhk.html

[D04] 删除元素
来源：http://dali.andypj.xyz/Article/details/gtxczpgsop.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gtqkhfausr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtkvjxlzfa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gtezxodffw.html

TS:   arr.splice(0, 1);
来源：http://dali.aizwys.cn/Article/details/gtcdcrjmmb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gtugwviclq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gtfzooebbb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gtunkbbazh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.316326.xyz/Article/details/gttoxffwel.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gthvvoemsj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtbdwnrhab.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtravljudw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtrvepblfc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gtxcvmzoad.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gtduvaeocc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdrlxpuf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gttgfvcpjm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gticoetizj.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpvkxtoo.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtwdkrxeqx.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtsbrrhawd.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtztfmosjx.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtbengwtfn.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gtsspphany.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtakbmwyzo.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtfxtkdkkz.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtqxoipprl.html


<!-- 参考信息 -->