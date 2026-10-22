代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sxryk.cn/Article/details/gttskmmpad.html

[B06] 遍历字典 / 对象
来源：http://dali.hysaishi.cn/Article/details/gtihlvfrxe.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tianlin.xyz/Article/details/gtezxfwamp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nanxuanxn.top/Article/details/gtpxyvtykn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtnfcucfpj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gtevoaazbx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cucudq.cn/Article/details/gtcbhceoxl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xinyue.icu/Article/details/gtrlfbgbnl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuxming.cn/Article/details/gtwyycopgk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlororvoi.html

[B07] while 循环
来源：http://dali.0kj1m.cn/Article/details/gtjtsveeal.html

Py:   while i < 10: i += 1
来源：http://dali.nwbrower.top/Article/details/gtcagumubz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgfzy.top/Article/details/gtcmipwysa.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdomhainf.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtrwewujoa.html

Java: while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtknatnnoh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dianchejie.cn/Article/details/gtmlnqszem.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gtmagqeyun.html

C#:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtkwowphlc.html

[B08] do-while（至少执行一次）
来源：http://dali.fengsongda.top/Article/details/gtnqizpdjf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jlsjyb.cn/Article/details/gtalysktxl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdipkouai.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtunirucvq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtktykxzte.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gthgzkmfll.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtkvanvpxc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigufen.top/Article/details/gtbhlgrjwt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtyxgnsafr.html

[B09] break 与 continue
来源：http://dali.xziqi.cn/Article/details/gtuxkntgyp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ydzc1.top/Article/details/gtswmuvkjv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gteqzkltpf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtscuujohr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtfaesydpv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavtiobnm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yonumen.top/Article/details/gtrnfricmi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigfzy.top/Article/details/gtgpdfdvpz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gttxddodoe.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gtnnfbwljl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gtucybmbyg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gtziexpeus.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gtdhkelhdw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtwtfiegow.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.iojbl.cn/Article/details/gtkoqkgwlp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.svipenyu.cn/Article/details/gtrbrdivza.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daxiang520.top/Article/details/gtxruhiafv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuanzx.com/Article/details/gtogxwvxyv.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigufen.top/Article/details/gtrvjimkrm.html

Py:   list(range(0, 10, 2))
来源：http://dali.cashguo.top/Article/details/gtemwdedvv.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gtkvtmhurx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtbjsvvveb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cashguo.top/Article/details/gtjidkikuf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.guannengcc.top/Article/details/gtifxiabjx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hfpthk.cn/Article/details/gtlebmemhn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guannengcc.top/Article/details/gtzfddtbmt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gtwqpnnegr.html

[B12] 跳出多层循环
来源：http://dali.havefunace.top/Article/details/gtrieubnww.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gtnlvtgpuf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gtquvwxdup.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gteyjmkqpc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gthriqnheu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtwzmgwyqk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hongshengwenyu.top/Article/details/gtkvyirkgx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuanzhike.top/Article/details/gttoszqcsj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ehwqpu.com/Article/details/gtqcbhmqdq.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtozwzkxxu.html

Py:   isinstance(x, (int, float))
来源：http://dali.iojbl.cn/Article/details/gtqocaldvw.html

PHP:  is_numeric($x)
来源：http://dali.wangdashe.top/Article/details/gtlxcrxrho.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtudeqcoht.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gtkwlhegdg.html

Java: x instanceof Number
来源：http://dali.0kj1m.cn/Article/details/gtssbhgqvt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dianchejie.cn/Article/details/gtilmkzmdj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.9152youxi.cn/Article/details/gtyfpbgnzw.html

C#:   x is int or double or decimal
来源：http://dali.yongpay.top/Article/details/gtuogkwzre.html

[B14] 判断值是否在集合内
来源：http://dali.yuxming.cn/Article/details/gtfnenbubo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.smart0.xyz/Article/details/gtvguctbsm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gtujdqmfmx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtmehpfday.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtjgpepjrh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258.top/Article/details/gtzvklfgzu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gthwimchph.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sxryk.cn/Article/details/gtbadhdbuz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtepkhzxpg.html

[B15] 布尔运算与取反
来源：http://dali.ybcxt.top/Article/details/gtafcbwkkw.html

Py:   a and b or not c
来源：http://dali.hfpthk.cn/Article/details/gtxaxwtnnt.html

PHP:  $a && $b || !$c
来源：http://dali.yueranfly.top/Article/details/gtcscwkyam.html

JS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtwuhlofhb.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtihhbovsd.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtddicishu.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtvynbkzgt.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtclmyprih.html

C#:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtibouzldf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jyoumei.cn/Article/details/gtrskgdfho.html

Py:   if not data: return
来源：http://dali.hywenlv.cn/Article/details/gtgsqffnro.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gtgflmimtu.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gtfsitanut.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtazrpuuri.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtwdykfbug.html

Go:   if data == nil { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtbaggzkiz.html

Ruby: return if data.nil?
来源：http://dali.haohaochexian.top/Article/details/gtfnwjasvv.html

C#:   if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtpadjmcyy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtywzjyzla.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gtccuosbyx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtispmaazw.html

[C01] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtntxgfjxx.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtlznccmba.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gthggxqxzu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtfqcbwmph.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtlhowzmmq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtmthejzqk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtntmoyndt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gtrysiacbl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuwkmtlfb.html

[C02] 默认参数
来源：http://dali.havefunace.top/Article/details/gttkvylsdp.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gteewzpuvy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gtcbjwoyhb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnseewqwf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtiurwmvhs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangdashe.top/Article/details/gtlatdrraz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangshuangyany.cn/Article/details/gtcmaizstk.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gtvocnsljn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gtbhfexrvz.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtsbozkjhp.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gteyrszarv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigufen.top/Article/details/gtqbfqzrab.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gttxjfcxtf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtrwgwkpjz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yvedp.cn/Article/details/gtnegqnhni.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gtkqpxaabp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hongshengwenyu.top/Article/details/gtdllyobjg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tanke756.top/Article/details/gtcxslolnx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtdnaazqmj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtkpnloage.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gtnlbyrbrh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gtvvtxbhoy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvoujdgc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gtbelezdkt.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gtxkjobonm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gthaqwnqme.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtsqhogcjd.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gtugecnuml.html

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtjbwmcoeh.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gthibwyvnl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtunehcexj.html

TS:   return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtlruscutd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gtjqkutlaw.html

Go:   return a, b
来源：http://dali.andypj.xyz/Article/details/gtvsqbggvv.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gtvxppabun.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gtiqmzvcui.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gtqbezgyri.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gtklzzezxw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gtbnchrfml.html

JS:   const square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtwpautcsu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtcdvasmak.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gotoacloud.top/Article/details/gtfvrqvquc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dashuyun.cn/Article/details/gtihrdujfp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigufen.top/Article/details/gtaoexqgef.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtfzdtxxpu.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gtongqoxhh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gtlsdolldf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gtkguzjydn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuanzhike.top/Article/details/gtyuskampf.html

TS:   arr.map(String)
来源：http://dali.zdqjudy.top/Article/details/gtsrcemrwa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jyoumei.cn/Article/details/gtwndeqsjf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gtcatvitpk.html

Ruby: arr.map(&:upcase)
来源：http://dali.xinyue.icu/Article/details/gtclbrpcjq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtkxhwksfo.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtgystsyto.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gtopjtvfzz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gttmxgrfwu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtanajhyfw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtbaqxegwb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gtdapkbvrc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nwbrower.top/Article/details/gtibrwustu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.quarkkingdee.top/Article/details/gtbnbjbbdd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtaipitano.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gtozxfzaqf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtrxgvaizk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gtsptzzqtv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtasrattkg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gtknnishja.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtwbouuqaw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxuanxn.top/Article/details/gtjhpolhvn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtmwdnykvd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gtsrlppxha.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gtkstuwiwi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cashguo.top/Article/details/gtxgpcyqao.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmizxsry.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtojukxnpg.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gtkgnojyoa.html

Java: 方法内为块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtcjuqicuc.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gthypljrdz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gtorynkfls.html

C#:   块级作用域
来源：http://dali.gzhubu.top/Article/details/gtrbidrfot.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangtech.top/Article/details/gtjocduepz.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gtvrqymzsp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daxiang520.top/Article/details/gtoimzbjof.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtsywutvgb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daxiang520.top/Article/details/gtgkqmldlq.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gttjkigudi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hfpthk.cn/Article/details/gtzvrgedwg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yanxiufei.cn/Article/details/gtluyxeehj.html

C#:   using System.Text;
来源：http://dali.zycfv.cn/Article/details/gtdzdaeyhw.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtgbwyyjuv.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gthmuuafcx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.redwolf501.top/Article/details/gtsgpozlsl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtemjoljfc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtliujuooc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjufyxcy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gtiiopqvwm.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gtmembzrju.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gtzmoydszf.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gtydhbkygf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtkvpsnwiz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtsoepbipp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigufen.top/Article/details/gtvvebkdyb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtoyznuwrb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtcunhzwkl.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtpwbnwqfp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzotbxje.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtddsrqmir.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtdromgrui.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gtxaqomjlh.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtmxprybuh.html

JS:   // 无泛型
来源：http://dali.ivvv.top/Article/details/gtmijdjbat.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlditzvmt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sufxvd.cn/Article/details/gtbzypvvmm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gtwoblktti.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gtvyncuryw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hywenlv.cn/Article/details/gtfbypvjah.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gtditcbbnv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtcmzoikec.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiyxkleb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckcpoezb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtzffwmdkh.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtfedqmjqc.html

Go:   // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtnbgkuxxy.html

Ruby: a, b = pair
来源：http://dali.hnqzz.top/Article/details/gtcodtmosh.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gttnggmvcz.html

[C16] 函数 / 方法重载
来源：http://dali.nwbrower.top/Article/details/gtdksjnalz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gtmkklgwyj.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gtwelnfyul.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yanxiufei.cn/Article/details/gtlpzrznho.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj202588.top/Article/details/gtimchnwum.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gtdbiridpi.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gtmqmxyybm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenlongwang.top/Article/details/gtqhabygly.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gtwwiuakla.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtymubezzc.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258.top/Article/details/gtzvsiqrwa.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtistsxftd.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtslltyxfn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gtbagxmmqt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtpwlchlve.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtieqwrzdb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gtwuectlev.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gtapixnxqd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gtdrihwclo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtizrahera.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwacrrsl.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gtreaewjys.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fzhhl.top/Article/details/gttczywnln.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gtbycbkgwn.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gttjmrdlbc.html

TS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtwjzomzqc.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtbedqjyxt.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtsxfxovyz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtqonfywqp.html

C#:   list.Add(4);
来源：http://dali.aibaodan.cn/Article/details/gtxxhreggt.html

[D03] 在指定位置插入元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwjkiqck.html

Py:   arr.insert(0, 0)
来源：http://dali.fengsongda.top/Article/details/gtcnuzbshd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.haohaochexian.top/Article/details/gttnsmbggj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ivvv.top/Article/details/gtzcqnjydy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkigybgq.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtohcbfydv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gtgsdfuond.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gtcqthdttz.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtdmklrjrh.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzwltfur.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gtmwuliwmi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gtlarulnim.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gtgxyvbhuh.html

TS:   arr.splice(0, 1);
来源：http://dali.haohaochexian.top/Article/details/gtvkermywq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtfpfhytbs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gtmqywcpxo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ppjwa.cn/Article/details/gtsxqxivwz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gtjgvztbkc.html

[D05] 访问与修改元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmqqruoi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gthfsjvobv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtrkibecjb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtawuicdef.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gtrvoyqyeb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gtdlbexqyo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtjybftraw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtrharwnxg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtobzsolif.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gturslhnxb.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gttbvcvlyf.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtxzpykrxy.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtpvmlcuyk.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtlqntlvwc.html


<!-- 参考信息 -->