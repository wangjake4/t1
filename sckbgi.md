代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2bmyiqeon.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gt2fiytoqzq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tanke756.top/Article/details/gt2afsupovk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2alhdioct.html

[B09] break 与 continue
来源：http://dali.tian-w.cn/Article/details/gt2mbwivmzc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gogol.net.cn/Article/details/gt2hupqjetu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2abvnkmqj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2dhxwmtiv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2wmjuijbt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2hxuysoni.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.kuanghao11.cn/Article/details/gt2dkmeevna.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxuanxn.top/Article/details/gt2dgltldft.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2fuvpdngz.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gt2xwfsbaav.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.smart0.xyz/Article/details/gt2nrjfkrsh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yueranfly.top/Article/details/gt2mwnqnlrd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gt2vqjmehvz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gt2pdnnbacu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fzhhl.top/Article/details/gt2tbbzijyp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hywenlv.cn/Article/details/gt2ifzkiznu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gt2rjzghill.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.316326.xyz/Article/details/gt2tcvporsk.html

[B11] 生成数字序列 / 区间
来源：http://dali.dashuyun.cn/Article/details/gt2uzaghakw.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgufenzy.top/Article/details/gt2zxygvwyn.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258888.top/Article/details/gt2wjysngvf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gt2swuwpjgb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gt2ugiyvaqj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aizwys.cn/Article/details/gt2cahaxcdz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofqpjtea.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxeagoke.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cheryme.top/Article/details/gt2yqvbmphc.html

[B12] 跳出多层循环
来源：http://dali.cheryme.top/Article/details/gt2dhizfzxf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gogol.net.cn/Article/details/gt2xcagvdax.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gt2uonestfv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gt2uualapqt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drlyiudc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gt2rkzchcah.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hysaishi.cn/Article/details/gt2dsducaml.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sufxvd.cn/Article/details/gt2whtiyqjv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fengsongda.top/Article/details/gt2bdgujqua.html

[B13] 判断是否为数字
来源：http://dali.cucudq.cn/Article/details/gt2sbbrqelh.html

Py:   isinstance(x, (int, float))
来源：http://dali.guowangkeji.top/Article/details/gt2tezrjpkr.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gt2htbkdbcf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gt2sdfxazum.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gt2ujrvtsfa.html

Java: x instanceof Number
来源：http://dali.zhixingplan.top/Article/details/gt2ovlhjgsf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daria6918.cn/Article/details/gt2xsjbufuf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangdashe.top/Article/details/gt2vbabyesq.html

C#:   x is int or double or decimal
来源：http://dali.smart0.xyz/Article/details/gt2mngolapg.html

[B14] 判断值是否在集合内
来源：http://dali.shuidangran.top/Article/details/gt2rfpsofdo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuxming.cn/Article/details/gt2dsxmyhuf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gt2anijszys.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2vhtkvkft.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2ddwfxzxq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2euzesbmi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2fmqckzlh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eujniwmj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2bvjpdhfu.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwntrzx.html

Py:   a and b or not c
来源：http://dali.xinyue.icu/Article/details/gt2dizcoohw.html

PHP:  $a && $b || !$c
来源：http://dali.zhengqikj.top/Article/details/gt2ikdhgdns.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2meiewhxi.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2noxyichc.html

Java: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2gfzhltck.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2bqcbczif.html

Ruby: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2tavmhmkw.html

C#:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2llfatpzr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gt2jdmaipbi.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gt2xdccsnwy.html

PHP:  if (!$data) { return; }
来源：http://dali.dashuyun.cn/Article/details/gt2uckzrflg.html

JS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gt2eythspyn.html

TS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gt2weewmvgg.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmubqzkf.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gt2ixafhpxu.html

Ruby: return if data.nil?
来源：http://dali.aibaodan.cn/Article/details/gt2jnjxieob.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gt2aqzpzvph.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2iysmdlzy.html

C. 函数与作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2rwhncgnb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2fmphiubb.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2snlwolgr.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gt2jlnldxkc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2elfgzvxq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2bhsixroa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tatcxvzc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2jjqtvcgl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2llulqvwx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj202588.top/Article/details/gt2ptjtsqud.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2orgimdkr.html

[C02] 默认参数
来源：http://dali.guowangkeji.top/Article/details/gt2wzbcjlwi.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gt2rrbcufjn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shzxlz.cn/Article/details/gt2kjkmjdiu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdxgfyka.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqdpmbpt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cdnleiting.top/Article/details/gt2gljqjhlv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cqqwz.cn/Article/details/gt2ftcufgct.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gt2belwqqkz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuanzhike.top/Article/details/gt2xjfpaqxg.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bawyimaq.html

Py:   def total(*args): return sum(args)
来源：http://dali.birdmap.top/Article/details/gt2odvidjvy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gt2luwlkxef.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gt2vgrlmnvb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brszlxsh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigufen.top/Article/details/gt2pgbcdzhu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrgpezqe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.smart0.xyz/Article/details/gt2olmigwyw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgzsafao.html

[C04] 命名参数 / 关键字参数
来源：http://dali.smart0.xyz/Article/details/gt2dtozaaxj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gt2owuoufod.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gt2agrjldfb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2pccnjwhf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuanzx.com/Article/details/gt2ytvosgln.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gt2zcdxbjnx.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gt2vawwyzzt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gt2prxmjqjt.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpuhnvqo.html

[C05] 返回多个值
来源：http://dali.redwolf501.top/Article/details/gt2oiowussx.html

Py:   return a, b
来源：http://dali.mhx1999.top/Article/details/gt2yfchgjap.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gt2jjrzqsgx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gt2nyrxpgml.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gt2bbugzgce.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgufenzy.top/Article/details/gt2kmlstgnj.html

Go:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2efwondrz.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gt2wamjeypp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gt2yzelxwjn.html

[C06] 匿名函数 / lambda
来源：http://dali.zhongyouzk.top/Article/details/gt2sehygkfo.html

Py:   square = lambda x: x * x
来源：http://dali.nanxuanxn.top/Article/details/gt2udxrjydm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tianlin.xyz/Article/details/gt2arnjxtfm.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gt2afdtlgty.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2pobfscxw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.birdmap.top/Article/details/gt2eesjjhjt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gt2smcadama.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gt2yydxillv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uynebteq.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258888.top/Article/details/gt2zzdfxccn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gt2qhnnkcro.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gt2qzbywrlc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gt2gmblwgae.html

TS:   arr.map(String)
来源：http://dali.quarkkingdee.top/Article/details/gt2umdhnnit.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gt2zvilunmp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tianlin.xyz/Article/details/gt2rgvmfuke.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gt2wyzdkbua.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gt2ydqhwgku.html

[C08] 闭包
来源：http://dali.jinqigufen.top/Article/details/gt2udxwhlzz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gt2mnqbkphy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ozgcsxcl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2ahlyykco.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2ioyrbmcx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gt2dijkrizr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.birdmap.top/Article/details/gt2qyzddmmz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gt2chfjmfct.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2zihyjsgy.html

[C09] 递归
来源：http://dali.sufxvd.cn/Article/details/gt2xaaiauzp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2wliaijfz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gt2sdzgomvf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gt2kbppfstb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gt2wdvzemgi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhisfhzx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltoqcecf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gt2ctircejt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gt2chwsazev.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gt2lwvnoujg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gt2iffnfvmu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkqypqqh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djynrubv.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gt2ekkasexb.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2imkvfmif.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2znhnclvs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gt2kpbxpfxo.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gt2qgvlojks.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gt2nukqtqxg.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gt2cfdicgqd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gt2bffrpqhh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gt2tdoxqbzk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gt2wjjnwagy.html

Java: import java.util.List;
来源：http://dali.nanxinkj.top/Article/details/gt2rhhmbdga.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xziqi.cn/Article/details/gt2jlcsqpal.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gt2cuprdxri.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gt2mhkqnapd.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gt2vkllfqek.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gt2mgvobozj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gt2ezpjxafn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gt2ycshvwfn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gt2gqlvxnzh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gt2tncofgyr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.vqdsnc.cn/Article/details/gt2yhpaxdup.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gt2ufgsmnce.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2wauddtgl.html

[C13] 类型声明 / 类型注解
来源：http://dali.andypj.xyz/Article/details/gt2kdueveup.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gt2dusodtfd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2esfpqvug.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gt2nftnyugw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2bjjutsnz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzwgsoqd.html

Go:   func add(a, b int) int
来源：http://dali.meibo888.top/Article/details/gt2cezpqpjw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gt2gqtvgevh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sweek.top/Article/details/gt2nqohzodr.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2inkcbosz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zyirtzyi.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2qepkmwya.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2nvwaxwuo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gegfvajx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2inhbwdyw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gt2svobgukb.html

Ruby: # 无泛型
来源：http://dali.andypj.xyz/Article/details/gt2liiqaefx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gt2itdoquju.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gt2cnpaqysw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuanzx.com/Article/details/gt2glnbtisn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hysaishi.cn/Article/details/gt2hvoddpoy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzanzbay.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgfzy.top/Article/details/gt2srbchgzd.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2brptejag.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gt2avrxcfrb.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywyspely.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gt2achqhlxu.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gt2xjoxvuxl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gt2gifgcikt.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gt2wfoylyhx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dsxpstle.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gt2qgxhwpza.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2exwopsnn.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gt2krayibdc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gt2kopezzhn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cdnleiting.top/Article/details/gt2lvnxklyi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2kdhwmqqd.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gt2tdvyslke.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eiysaxfg.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gt2epsxlmdp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdmpwnfh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gt2eqnuuvvm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gt2mfsrtyxn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gt2eghbhlml.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gt2mswyhbyc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwsxbigy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gt2lgnmxjvd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gt2yiblhqgu.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gt2ueqevhhh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gt2wqngfxba.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.redwolf501.top/Article/details/gt2xlfhghmp.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2zzqmcydp.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2wjuphrpg.html

Java: list.add(4);
来源：http://dali.ydzc1.top/Article/details/gt2eophtgcv.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gt2wahppdhb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtmcmzio.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gt2jfuhiaai.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gt2hvrkbqmm.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2okoelsqj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gt2nztcxnnj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gt2ccssztly.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2psxuskxz.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2xjmsmhyc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yubxeinu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gt2ypcojrcr.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gt2koadffof.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2ckzjrscj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2knjuonvz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2wvwkodvr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gt2rdcloarw.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gt2gizmkzed.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gt2mtmbmzzh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gt2jdkykyul.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shuidangran.top/Article/details/gt2pcukrtox.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gt2ygjoroor.html

[D05] 访问与修改元素
来源：http://dali.yj202588.top/Article/details/gt2rmhqowtl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gt2frqbldbd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gt2inlwcyhk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2uvsanprd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gt2yauypiwa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gt2cykxskbs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2tjtohjhu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2poupbnay.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2hcbcznys.html

[D06] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gt2ixyggjvq.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2zboocutf.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2sywbbfav.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2tifzzikz.html

TS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vuqadhwv.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gt2nuknlpuy.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ladmqcld.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gamrdlar.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gt2badhpiiu.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usvpnnwo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gt2bpvqzjpm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258.top/Article/details/gt2pfugflmm.html

JS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2hpbmropq.html

TS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2idloglej.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2wpopmvxo.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjxznlzg.html

Ruby: arr[1, 3]
来源：http://dali.aizwys.cn/Article/details/gt2adrhdxjl.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gt2jjkuatdi.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gt2xvxfhhgi.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gt2vvndftvu.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egptciii.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gt2ihvhlfqs.html

TS:   [...a, ...b];
来源：http://dali.gaohongyu789.top/Article/details/gt2rfmlqjqz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nadfbnos.html

Go:   append(a, b...)
来源：http://dali.cheryme.top/Article/details/gt2snhcruol.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gt2orabnnpm.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2guogsbpw.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gt2vhsjsjts.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gt2kmnqrtxq.html


<!-- 参考信息 -->