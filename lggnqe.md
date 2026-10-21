代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnxiangtu.top/Article/details/gtwiszlpvx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fzhhl.top/Article/details/gtfacckvmo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtbooehifb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtwmdmvcqe.html

Java: do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtfdaokgox.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gtawqgasno.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gtheussoho.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtirsrksjb.html

[B09] break 与 continue
来源：http://dali.haohaochexian.top/Article/details/gtobrpyieq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gtifdtcjob.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtepxjnmtw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtspatyiqp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtklijwmdu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvjezsqbw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgfzy.top/Article/details/gtzpznexdh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aibaodan.cn/Article/details/gtxfqtgwhh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtnmkhcaqz.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gtutuxzbbr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.svipenyu.cn/Article/details/gtmsjtqapu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtumxtorkg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gtpjavkggh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gtbvubnkkp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj202588.top/Article/details/gturvkmzwh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gtufnbixas.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gtkadyaiom.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjrtirus.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxinkj.top/Article/details/gtfkgxogpg.html

Py:   list(range(0, 10, 2))
来源：http://dali.ybcxt.top/Article/details/gtbldtmijc.html

PHP:  range(0, 10, 2);
来源：http://dali.havefunace.top/Article/details/gtdmdbgsji.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtwadrvqqs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gtoajelznv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nwbrower.top/Article/details/gtqkblpqsg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gtfhrdkysq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gthgesbdaj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dianchejie.cn/Article/details/gtkzefmkvi.html

[B12] 跳出多层循环
来源：http://dali.316326.xyz/Article/details/gtuxwpvjmj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fzhhl.top/Article/details/gtonbtdoaq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gtpfxvjxnn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtlyvocnrh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtwdqvtdnn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtzjyrgvzw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.smart0.xyz/Article/details/gtaizlclmr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.snrcjt.cn/Article/details/gtdlbmykks.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yonumen.top/Article/details/gtoiitmkpz.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltpfprsn.html

Py:   isinstance(x, (int, float))
来源：http://dali.tian-w.cn/Article/details/gtpocdifbk.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gtbrebtepg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtxaefgyyb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gteayxffcw.html

Java: x instanceof Number
来源：http://dali.shzxlz.cn/Article/details/gthqkjebtr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jyoumei.cn/Article/details/gtdhhblxpb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gtlnulmhpk.html

C#:   x is int or double or decimal
来源：http://dali.xinyue.icu/Article/details/gtdbzzsnpe.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gtnkudvgic.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gtimonsqaw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ppjwa.cn/Article/details/gtlsenigzx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmakplcv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtcwxezjxr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sxryk.cn/Article/details/gtcmdkbzde.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gtdlddhufy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zycfv.cn/Article/details/gtwqawxbyr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtksoqqexd.html

[B15] 布尔运算与取反
来源：http://dali.sysykeji.top/Article/details/gteokohwps.html

Py:   a and b or not c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbhkbomo.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigufen.top/Article/details/gttwjciqbb.html

JS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtpjdvkjia.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gteewofheu.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtdxqwwzwt.html

Go:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtahgwndpj.html

Ruby: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtvnlaxmbk.html

C#:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtwfguwmng.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shuidangran.top/Article/details/gtzljohwdf.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gtjmfopegt.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gtnclefbsy.html

JS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtdntjuowk.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gttixiygyd.html

Java: if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gtqmpagesh.html

Go:   if data == nil { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbvlohil.html

Ruby: return if data.nil?
来源：http://dali.ivvv.top/Article/details/gtvbvvdgrf.html

C#:   if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtmgseynyy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmtqfedqm.html

C. 函数与作用域
来源：http://dali.nwbrower.top/Article/details/gtvtnbztkm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttjfqevev.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtjhtanfpy.html

Py:   def add(a, b): return a + b
来源：http://dali.tanke756.top/Article/details/gtlxxfuutd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtbpkmojki.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtygwyavmo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqolhytdh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtfxnnmjel.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gtyssbuuza.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhiwuduotai.top/Article/details/gtqrmgylop.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtpokakqeb.html

[C02] 默认参数
来源：http://dali.zdqjudy.top/Article/details/gtabskojfp.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtaxkkkucl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gtnenypqze.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gtqsacdizx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtckmmcsqa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gtiaophcnu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daxiang520.top/Article/details/gtgbgkugry.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gtqbhamozr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gtbvwojadb.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gtigyhniwz.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gtsekhwdla.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gtejimqzni.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gttogvuwlt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtvzwxhtav.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.meibo888.top/Article/details/gtufkuxxts.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtldsxyunm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtyyipntsg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.haohaochexian.top/Article/details/gtwtmvrepe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gtbaddlepp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xylfe.cn/Article/details/gtbhrrcyxw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtmaldnhsg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtufdzmbeq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gtxuuosbvn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gtzppvnvrx.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gtivqgmeba.html

Ruby: f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtmacydlbg.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtuzdhfahe.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gtrdvihnhz.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtzfsvsxsn.html

PHP:  return [$a, $b];
来源：http://dali.jinqigufen.top/Article/details/gtfwloxsno.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gteoibhoxb.html

TS:   return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gtssjgtfmt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gtoogjosuw.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gthpaaabbr.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtitsxglky.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gteqswplaa.html

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gtaenaiaqj.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gtrjsynisf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigufen.top/Article/details/gtscpbiugq.html

JS:   const square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtmspolwfp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtlwxhhzfq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtsyjchtix.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gtizclfalo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gttdxflmlz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gtbomjgfgw.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwqjnpkl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtcwrfdevc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hammf.cn/Article/details/gthesymvfh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yanxiufei.cn/Article/details/gtbrfqqjmj.html

TS:   arr.map(String)
来源：http://dali.yueranfly.top/Article/details/gtyljaxctv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ehwqpu.com/Article/details/gttljxbqjs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gtssaxcxmf.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gtegookszw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jianghu66.top/Article/details/gtfewywbhe.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gtnitegqbe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtxszeluen.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbysctms.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtpucwdixl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtasqetdnh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shzxlz.cn/Article/details/gtimpercmw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gtubdreqio.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtzxpkdaov.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtxlsahlbk.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gtrwltrvgt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtktypcpxz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtukkbmjtk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gtmrazgkmu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtmqsrurpd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtntetjzfh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangshuangyany.cn/Article/details/gtyxueenco.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtumtiaepp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gtyqessrya.html

[C10] 变量作用域
来源：http://dali.nanxuanxn.top/Article/details/gtreemedrb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.kuanghao11.cn/Article/details/gtgeqmkmkx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gtyyxtfdgm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtvcacquxk.html

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gthxjfkijj.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gtrloxnwkr.html

Go:   花括号块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdmaqvyt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gtnzygmzhw.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtuznloknk.html

[C11] 模块导入与导出
来源：http://dali.xylfe.cn/Article/details/gtlwmkpeok.html

Py:   from module import func
来源：http://dali.xuanzx.com/Article/details/gtgmagxsjf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shangyingyoupin.top/Article/details/gtrzkrmfwt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.birdmap.top/Article/details/gtlehuneky.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gtlcmdgjsq.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gtywbawxrs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gtekpnhyhz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.birdmap.top/Article/details/gtsmrgcvrj.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gthdpmcrux.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gtwesawzvh.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gttxwripaz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gthctqlmiz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtplcmievx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtlcridpwq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gtevhulxor.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtccrseqlq.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtehfjokmj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtukoliirs.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gtvpyyegdz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtkginrqta.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtraikjvll.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gtcmfwjvqm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtfylzxdvr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtestayyjy.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gtxwlmvzom.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tanke756.top/Article/details/gtkjhufhjf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gtpgysklsx.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtfajgvkef.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtqphcfswf.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtynsmukxz.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtiwxyclhz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gtuliyupcx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.vqdsnc.cn/Article/details/gtzehgwntr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtksihluzs.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtokbywxrz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gtjtxwxktb.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gtdtlpvcfe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gtnvizbalk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daria6918.cn/Article/details/gtmkyuamuj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtdemsrbhg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspzyxepp.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gtvhgzlzcl.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtllzfvdvs.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gtupidhzhv.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtripkptao.html

[C16] 函数 / 方法重载
来源：http://dali.hammf.cn/Article/details/gthlsulacj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gtzimzvnyt.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gtytsbtwsz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gtwitirajc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gtffhehhwm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gtxdutgpfj.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gtfaffgepw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gtggaojhqr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdpsqnjg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzzmpipvf.html

D. 数组 / 列表 / 集合
来源：http://dali.dashuyun.cn/Article/details/gthhkqqhnl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtaddlxzwk.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtrraiprbo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gtzthwbwik.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gteoaenqit.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gtxozrjbtf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtkjeievuf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gtjlpjdmsw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gtmiyhqovr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gtflkxecyp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gtqsdzfvxh.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gtqntpopbr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gtygjjdvrc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cqqwz.cn/Article/details/gtkmylpevi.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtdltchfnk.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtokupuxjl.html

Java: list.add(4);
来源：http://dali.yj20258.top/Article/details/gtxitztgec.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtgbswsawj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gtasmtmbfx.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gtyniqxsue.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gtsizbqjdx.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtwmgfhioc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gtbgfocbqw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gtnuenzvpe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gtaiegtmdf.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtnjqdwphf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gtisvfxsyx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gthpimrloo.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gtajveosrh.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gtdboxslua.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gtiadomqiq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gtfjcfdcrf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gtkjjhjigu.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttczwzqes.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gtdtfavjzs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gtgdcynwdb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258888.top/Article/details/gtmntqjgpq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gtxrdcxkfp.html

[D05] 访问与修改元素
来源：http://dali.yj20258.top/Article/details/gtevnmhojo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gthfkktghm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtkczpgtdr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtwbwgrrdp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gtfkubiumr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtvfslfjdi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtmcvgvlfw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gthupdrmhk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtoyvwzyqt.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtujsgwhqa.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtlfmhcstw.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtemacqseq.html

JS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtaxgjuyaa.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtqiieobsm.html

Java: list.size();
来源：http://dali.yj202588.top/Article/details/gtejvgzwve.html

Go:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gthgydycgr.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gtwtimcmlf.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gtghfsgecu.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gtnnimcfmr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tianlin.xyz/Article/details/gtdmhxjiyt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtboqxqgce.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtlnbjajix.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtdxomtvhb.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gttkxlehiz.html

Go:   arr[1:4]
来源：http://dali.jqgfzy.top/Article/details/gtyvlzgspf.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gtxqoysrrj.html

C#:   list.GetRange(1, 3);
来源：http://dali.c1oappe.top/Article/details/gttbcjdnal.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtahbhfnly.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtgbmeksoe.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyvzosfw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gtfwrmpkjc.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtcniuhsoh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtmbbnjlxs.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gtztisbgse.html


<!-- 参考信息 -->