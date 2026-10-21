代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.birdmap.top/Article/details/gtcziycjff.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkpzlzul.html

TS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtnxtpcglc.html

Java: while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtosquivve.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yangfankeji.com/Article/details/gtnxzhulgb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gtchigmqbs.html

C#:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtagwsjqxw.html

[B08] do-while（至少执行一次）
来源：http://dali.jianghu66.top/Article/details/gtwvttyoln.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.c1oappe.top/Article/details/gtkibuvpzk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gttnbedlbi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtzyxwzawl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gttkewholn.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtivlyxhtm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtoishafyf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuetiantiany.cn/Article/details/gtagpzwsfe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtjxoncqud.html

[B09] break 与 continue
来源：http://dali.zhongyouzk.top/Article/details/gtetrgqjvh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pycfn.com/Article/details/gtghgvfrjn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtiltzaeiw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtvvqvbceg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtgfacjgxz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gteytcelhd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtzxxylhpw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gtykehbgsn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gttxonjznz.html

[B10] 遍历同时拿索引
来源：http://dali.shangyingyoupin.top/Article/details/gtklihagji.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gtvcboqpsu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.daxiang520.top/Article/details/gthdsjalbz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtoxjyshdr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gtspxuynwz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.smart0.xyz/Article/details/gtlccdvikp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gtthhvqskt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gtdlokxqgu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sufxvd.cn/Article/details/gtnwqegnee.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhiwuduotai.top/Article/details/gtjrnshezr.html

Py:   list(range(0, 10, 2))
来源：http://dali.fzhhl.top/Article/details/gtykfcllma.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gteglljnym.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzzrdvjr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gtmibmnwpo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gtezxwcwpb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtgxnwgoit.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xylfe.cn/Article/details/gtsichfbxu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gtkicnucng.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtnevzyjvl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hongshengwenyu.top/Article/details/gtobshsvwk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj202588.top/Article/details/gtdnaihwjp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtuipsvvps.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gttjomzdim.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtttxbuujr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dianchejie.cn/Article/details/gtutxnftcp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yongpay.top/Article/details/gtfajhgsln.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhengqikj.top/Article/details/gtujtrchji.html

[B13] 判断是否为数字
来源：http://dali.xziqi.cn/Article/details/gtqmupfhpe.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gtocmxmtsg.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gthralqxmx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtwjugmiqb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shzxlz.cn/Article/details/gtkqsiylos.html

Java: x instanceof Number
来源：http://dali.zhengqikj.top/Article/details/gtqmzwmyyl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgufenzy.top/Article/details/gtpjbcwctk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gtmijndrdu.html

C#:   x is int or double or decimal
来源：http://dali.xylfe.cn/Article/details/gtkwqkistf.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtnxpeuvrb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenlongwang.top/Article/details/gtthpqwgxx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fzhhl.top/Article/details/gtlzmzkdew.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtmfnsanux.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtgsilfcva.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gtbxobltxg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.redwolf501.top/Article/details/gtmqsdlxcx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cdnleiting.top/Article/details/gttspgvxxd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtaykkzdrx.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gttjpvmjdu.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gtdvkgzirk.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gtkfwufvks.html

JS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtbfdhrsbi.html

TS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtxyogzkyb.html

Java: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtpuyrubil.html

Go:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtxqmpdsyv.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtcygcqoap.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtdofvizbl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gtohedousf.html

Py:   if not data: return
来源：http://dali.pengpengdd.cyou/Article/details/gthieplvqr.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gtpkmdhfnl.html

JS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gtzjrdajce.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtfwuanimv.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtqhgjndms.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gtgrbxyulb.html

Ruby: return if data.nil?
来源：http://dali.wangdashe.top/Article/details/gtzghcxolj.html

C#:   if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gtwjcortvh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaywwahuv.html

C. 函数与作用域
来源：http://dali.jyoumei.cn/Article/details/gtojocmwxv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtapuctnyd.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtfwlogqbi.html

Py:   def add(a, b): return a + b
来源：http://dali.mhx1999.top/Article/details/gtqsdjymrt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtymhhyzve.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtugvhrbae.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtyjqghgxz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtvhbiphdu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhixingplan.top/Article/details/gtexypyuhn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxinkj.top/Article/details/gtjilwpcfl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtegotqjep.html

[C02] 默认参数
来源：http://dali.ybcxt.top/Article/details/gtepnkeico.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtcunbuaje.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tanke756.top/Article/details/gtjsncipko.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtblmnawbu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtewttqpxv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gtsyddfucj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pycfn.com/Article/details/gteulkjtst.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigfzy.top/Article/details/gtaldpfkvk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gthwxgoayp.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gtocnjkitu.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtchyehxbg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gtofafzqkc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtzhzfqpfu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtaxhcrxzt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gtifqiemgy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhiwuduotai.top/Article/details/gtlkcgvsqr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gtwukypuvo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yongpay.top/Article/details/gtkpavjiyg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jyoumei.cn/Article/details/gtlnjsxkto.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenlongwang.top/Article/details/gtqhfgiesy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gtacnsnukm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtvxhzpkch.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtipbmiffd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258888.top/Article/details/gtpvkhwduo.html

Go:   // 无：用配置结构体参数
来源：http://dali.pycfn.com/Article/details/gteqascxuu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtzdfdkqkx.html

C#:   f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gtkdkxbdqq.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gtoxgnxifa.html

Py:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtmntsyliz.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gtrwnsdslt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtdgodsikh.html

TS:   return { a, b };
来源：http://dali.havefunace.top/Article/details/gtlogmxuvq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yonumen.top/Article/details/gtysjlkped.html

Go:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtbuasetor.html

Ruby: return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtnolnrajw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdhxudvk.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gtytebsqqo.html

Py:   square = lambda x: x * x
来源：http://dali.zhiwuduotai.top/Article/details/gtszkienuy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gtrvkxzlcc.html

JS:   const square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtatcwaauh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuanzx.com/Article/details/gtwdouqorj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gotoacloud.top/Article/details/gtmcqfykav.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gtumkqcipa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gtqfzaoumm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqzggggs.html

[C07] 把函数作为参数传入
来源：http://dali.316326.xyz/Article/details/gtccilfrtp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.redwolf501.top/Article/details/gtaspqjswu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtxglrdqtg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gtrykjniad.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gthcnuhabd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gtecpjpdgq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gtwestkcrw.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gtvwpklpja.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuetiantiany.cn/Article/details/gteqwbhkzx.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gtvbegevtu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gthjsevngk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yonumen.top/Article/details/gthzibaqwr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbfxusfsz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtdswrpguu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtuboubqed.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aizwys.cn/Article/details/gtqgsrffis.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ybcxt.top/Article/details/gtjlfwlrby.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtxnizqqng.html

[C09] 递归
来源：http://dali.shangyingyoupin.top/Article/details/gtajqmabct.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtivthgwys.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtylaosmer.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gtvhipzkwu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gtypxeclgt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtpaalczjx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.svipenyu.cn/Article/details/gttffvautr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtmmijvrmq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtbwuvjswf.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtdnsdorlo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gtpftacgus.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gtnesqrzhs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtwxfrcaov.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqcuarpf.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtbplkxwuq.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gttzcvyptw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtmtpjwgki.html

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gtrzznmyah.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gtbrqaswyu.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzhwgvjq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtjildhtyf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtjheboiqe.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gtcddooxpl.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gtasuxduzs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtiixuhran.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gthqmmqgcv.html

C#:   using System.Text;
来源：http://dali.wangshuangyany.cn/Article/details/gtgxxrkstr.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gtwftjtfye.html

Py:   (lambda: print("run"))()
来源：http://dali.aizwys.cn/Article/details/gtaqofpfnt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtulxrkumk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtsanskfch.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtbzopajpu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gtvugzvwrg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gtywugcbrq.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgfzy.top/Article/details/gtglesmyos.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gtanhzauoc.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gtbbvpclwt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtmwwbnjli.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gthawznmsv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtbujnamsy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtxzfpcldp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gteihpfawo.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gtflfkoyvh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangshuangyany.cn/Article/details/gtorlhxhvf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gtiypibvyp.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gtpprjltcf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtpaygicuz.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtnsolieae.html

JS:   // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnorkdiah.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlclwvlkg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gtygkrnzrb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuxming.cn/Article/details/gtmkadvqfj.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtthzglugv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtommcfdmx.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtnkpnwgyk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gtltnlrjzi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258888.top/Article/details/gtyokzbynm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtehdtjhso.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gtemrhbejr.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gtjqwzmblg.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtlebcuhqt.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gtyvcogtkf.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyguzojl.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gtgkstzeet.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gtzawwomud.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gtakuirzqv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gttkbhvtzw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gtotkyyzcj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtgmpgwqhy.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gtdogltpca.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gtyoyxjyfc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gtbmijfptp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrwqlfurt.html

D. 数组 / 列表 / 集合
来源：http://dali.aibaodan.cn/Article/details/gtdwawfxnr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtptdbfdaj.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtajezkjou.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtkuxpjiqw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtzdbsfvhk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gttmcfkpwq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangtech.top/Article/details/gthraangjt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.snrcjt.cn/Article/details/gtwxvsjlgu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtbbkjhkzn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hfpthk.cn/Article/details/gtjkjmiwoy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gtaplvndbt.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxkskigv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gtnrusqdql.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gtanqetqnl.html

JS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtbcfxfjbp.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtazombhsj.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikrsajwt.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gtplqpwqme.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtydrlnctu.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtfqjbnexh.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtlkhjsqqw.html

Py:   arr.insert(0, 0)
来源：http://dali.c1oappe.top/Article/details/gtekauspqy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrvjmwfr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gtaotcgijz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtcagrfdgz.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtpqhjuzxq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gtcczbseur.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yvedp.cn/Article/details/gtolqotsgm.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtyfpjhphb.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecvmffog.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtkejuscwn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gttsjkegpw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangdashe.top/Article/details/gtuigeudty.html

TS:   arr.splice(0, 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqvtoakd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gtzzceligd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daxiang520.top/Article/details/gtwzrxhvts.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gtzlviybwd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtozsixkzf.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gtdcavooav.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtqqqhrfby.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtnwhvaynl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtqhhwvclo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.smart0.xyz/Article/details/gtggwjutrn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gttaortcus.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtojusakxm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtuldnxthc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtpitaywws.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtuqlksqik.html

Py:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtxitoheoz.html

PHP:  count($arr);
来源：http://dali.hnqzz.top/Article/details/gttvukhakw.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtwonejwyv.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtnhutpxue.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gtzavnrctr.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtcmymlytq.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gtnzqpyeqw.html

C#:   list.Count;
来源：http://dali.aizwys.cn/Article/details/gttjvuwuna.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gtnvrrchfe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gtixytitun.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtynrhfnlc.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtkyhoarov.html

TS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gthpwjgkos.html

Java: list.subList(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtaxgpikew.html

Go:   arr[1:4]
来源：http://dali.vqdsnc.cn/Article/details/gtpbnhpocw.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gthqorvfgo.html


<!-- 参考信息 -->