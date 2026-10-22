代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2rhentdic.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cashguo.top/Article/details/gt2vwgzoyua.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dashuyun.cn/Article/details/gt2pgupkvla.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gt2izlahuqq.html

[B09] break 与 continue
来源：http://dali.ydzc1.top/Article/details/gt2rpsppsmi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhoulong.xyz/Article/details/gt2yycngtpl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gt2mklwsgso.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uowkdapl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2kkvndanp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2galgwdrl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gt2pgysawmi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gt2qyuxykjq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzrziizc.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gt2odftajxu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ydzc1.top/Article/details/gt2qpmmnzbn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gidumlyd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cucudq.cn/Article/details/gt2aeghkudr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gt2gmcncqmb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tianlin.xyz/Article/details/gt2sswzdflm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.vqdsnc.cn/Article/details/gt2yldvtbzx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwuolhib.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gt2yxhtjyzb.html

[B11] 生成数字序列 / 区间
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgllvlmt.html

Py:   list(range(0, 10, 2))
来源：http://dali.jyoumei.cn/Article/details/gt2fjwduqax.html

PHP:  range(0, 10, 2);
来源：http://dali.9152youxi.cn/Article/details/gt2yrtjglxr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gt2bvfsejkf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gt2xqxiergf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daria6918.cn/Article/details/gt2itbavmnc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.0kj1m.cn/Article/details/gt2dtsvplnx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxtdafma.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vljtdijm.html

[B12] 跳出多层循环
来源：http://dali.iojbl.cn/Article/details/gt2rhgylklx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xinyue.icu/Article/details/gt2szmzqmwv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gt2piqgkhhi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2qpfyisur.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsnlylqw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2vuwrvedv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikqsxuzp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.9152youxi.cn/Article/details/gt2dcoquoft.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpqbmisf.html

[B13] 判断是否为数字
来源：http://dali.jyoumei.cn/Article/details/gt2xqrxsrgn.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yotmgvtu.html

PHP:  is_numeric($x)
来源：http://dali.aizwys.cn/Article/details/gt2pvqaubim.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2rqkmygxw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2btlgxxsc.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gt2eckbabev.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gt2lfsvfsaj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gt2bwaiymgn.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gt2hdywadfd.html

[B14] 判断值是否在集合内
来源：http://dali.sufxvd.cn/Article/details/gt2xoqvpszr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gt2igipsxjv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinqigufen.top/Article/details/gt2cllyzphf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpfzbfds.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2bmiselvo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2jaogngbp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2gtvsqcvt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2czedfmuc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewaalrbs.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gt2bbjzqdfs.html

Py:   a and b or not c
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxafodkh.html

PHP:  $a && $b || !$c
来源：http://dali.ydzc1.top/Article/details/gt2qqvjaqjo.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2lsgppxus.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2eclatant.html

Java: a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2ldyynffp.html

Go:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngcojijw.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkwojohc.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2imqbxtay.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhongyouzk.top/Article/details/gt2gqvgztuf.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gt2ftftzlka.html

PHP:  if (!$data) { return; }
来源：http://dali.bjfxy.top/Article/details/gt2mhsbotlw.html

JS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtharrvd.html

TS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gt2pqajjhha.html

Java: if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gt2wsxukqal.html

Go:   if data == nil { return }
来源：http://dali.jyoumei.cn/Article/details/gt2mbaixfsx.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gt2wdotkegk.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gt2lwdsyeta.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2bzcuxbud.html

C. 函数与作用域
来源：http://dali.jqgfzy.top/Article/details/gt2xucqbgts.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2jlfhvart.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gt2otwxovur.html

Py:   def add(a, b): return a + b
来源：http://dali.yuxming.cn/Article/details/gt2eqqvvdhc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2virdpcfr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2ztnlkhlz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hvwyfhjf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2dxerbekl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2jtqzhssw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fzhhl.top/Article/details/gt2ebwqnxkz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgnbennp.html

[C02] 默认参数
来源：http://dali.cucudq.cn/Article/details/gt2feawcyqv.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gt2azafbkxb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gt2mtccpzfy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ctbamvrt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2lcbhqxwl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrqmtetw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gt2zyntzurm.html

Ruby: def greet(name = "World") = name
来源：http://dali.ydzc1.top/Article/details/gt2kaatwxeu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daria6918.cn/Article/details/gt2ygxxxxox.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gt2ctlazvwm.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkndlfnp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.quarkkingdee.top/Article/details/gt2bshdtqxn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gt2eaowzmlz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gt2kyvtthnm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2zjckrwwf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gt2gjooddfc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gt2cwjrhncx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gt2axjijepl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gt2nlavioeo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hfpthk.cn/Article/details/gt2jdqtyqjs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gaohongyu789.top/Article/details/gt2jjoqcfpl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gt2pbmckhaw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gt2hqoynloc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gt2tofvzsih.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuanzhike.top/Article/details/gt2gwmhyxlj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gt2xebsrbyt.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gt2tspuhtpx.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gt2cemjmqvs.html

Py:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2vscqrjwi.html

PHP:  return [$a, $b];
来源：http://dali.zhoulong.xyz/Article/details/gt2keitmprj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gt2gwuhlxum.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgwzweko.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gt2qejwrblf.html

Go:   return a, b
来源：http://dali.cucudq.cn/Article/details/gt2kxjdezsy.html

Ruby: return a, b
来源：http://dali.cashguo.top/Article/details/gt2ahipndpy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gt2cuulvtwd.html

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnutspfg.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gt2qfyvossm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gt2atseogda.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2budltsrf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fzhhl.top/Article/details/gt2rasnksqr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2guhnwmik.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gt2rnjoqhop.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gt2oouzftcj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gt2toczlbhq.html

[C07] 把函数作为参数传入
来源：http://dali.shuidangran.top/Article/details/gt2putaglda.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gt2sdxnoprz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gt2mryjkcbk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpdbggtg.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gt2yuctdrnw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yonumen.top/Article/details/gt2htnqcckl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cdnleiting.top/Article/details/gt2ufgmrsgf.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gt2rvhkpvsp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnxiangtu.top/Article/details/gt2xrztbkxl.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gt2ehwlgfcq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbcehjv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wddypncc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtpnjfpt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbpgfjrc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gt2lzboimil.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gt2ssbgwqhv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gt2nrxqnoct.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyfeayfg.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gt2dhyfyvhc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhengqikj.top/Article/details/gt2fngzkova.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gt2jfcjdnon.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gt2vvwiynxx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gt2jlckwonk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ybcxt.top/Article/details/gt2enycxslq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gt2ghvsutzk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2phaanmhz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2vrhfwbec.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gt2qxhwfron.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gt2lllgvqtw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.havefunace.top/Article/details/gt2flkoyfjr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yonumen.top/Article/details/gt2kjnumhue.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2xmribioh.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2ajyhkaze.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2mmibxbtu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptaobguf.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2hadyvara.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gt2xbddstsq.html

Py:   from module import func
来源：http://dali.yongpay.top/Article/details/gt2sekkwpzg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gt2oileuecv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gt2edvjemye.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gt2vferljjx.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gt2naprqkgn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gt2ubybhgmd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gt2okprfgqc.html

C#:   using System.Text;
来源：http://dali.316326.xyz/Article/details/gt2zqqbudci.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gt2jexbwfji.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gt2oochpkjo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxyzhzam.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gt2nsfhvpch.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gt2kyxayrds.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2wopdfckr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.smart0.xyz/Article/details/gt2wjimqgsl.html

Ruby: -> { puts "run" }.call
来源：http://dali.cashguo.top/Article/details/gt2dsqqhmcp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fzhhl.top/Article/details/gt2sdvniisn.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gt2qrigtffl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtkhukez.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2cojaxohv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gt2efczxqlr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2ifamankt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2aendagcl.html

Go:   func add(a, b int) int
来源：http://dali.chenzaomai.com/Article/details/gt2ylorxaty.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpncxgdv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gt2idktnhle.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gt2rmnhdfny.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gt2mvgvivsc.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2lihpfynu.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gt2fuultgcw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gt2hsdssude.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pycfn.com/Article/details/gt2qgvvxuid.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gt2goqrmxmg.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2queuyqtz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gt2vdpluubr.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2mypdphbg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gt2gjpzhttj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqwbbllb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gt2xmtmrvgp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2qrkoexxd.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2osjmmhck.html

Go:   // 无解构
来源：http://dali.redwolf501.top/Article/details/gt2yiadkfob.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gt2ibzmljsj.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gt2yyslqllr.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gt2kpwbynbd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gt2zkpltjpr.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gt2aesdnnap.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkcwldw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigfzy.top/Article/details/gt2ltpvkenm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.redwolf501.top/Article/details/gt2xxfjgpqj.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gt2ujmvoave.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gt2jgbobhkd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2ueqphhnx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fohuuihf.html

D. 数组 / 列表 / 集合
来源：http://dali.jyoumei.cn/Article/details/gt2wawvrdzd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2vqedpgxt.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gt2wqpsbmkr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tavrtmwd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2utowffpv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywyvebmx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gt2isfakefq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gt2giyxirmi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gt2hrdwpfvc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gt2pshtkimt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gt2iyqstrel.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gt2iuooodhl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gt2bpytrozx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgpttfzv.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2wnelneyu.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gt2rvopjlrw.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2stfpxrkn.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gt2loelrgaw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aibaodan.cn/Article/details/gt2gecrviqr.html

C#:   list.Add(4);
来源：http://dali.pycfn.com/Article/details/gt2ejozeble.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gt2fzsnqkpc.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2sszxnoww.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gt2ioktsbwp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gt2mcstjnol.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhstmigr.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2swzsifsz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gt2wmgddrnk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuxming.cn/Article/details/gt2vqlogdbb.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2hdfxeseq.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gt2gpvstpxj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtfgjizg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ydzc1.top/Article/details/gt2bexymxdi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yanxiufei.cn/Article/details/gt2qncxrkwq.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gt2vnjkryji.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xylfe.cn/Article/details/gt2qbtixrum.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nycvvkbw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gt2ovszkojr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mpdbnger.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gt2hrpocahq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2xxtzfivf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gt2imdgrtyk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2tfmufawp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gt2qxjfmlkz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zdqjudy.top/Article/details/gt2nvuateye.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2aeqjnvsx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2akvkfdsf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gt2iznganht.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gt2mbzkiyyp.html

Py:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2aqjgonfk.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2wsimnteg.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2qonjuuug.html

TS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gt2skywwtpg.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gt2wgnvzmui.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gt2ulfvrzfz.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2zcolhgyu.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gt2keujmash.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gt2rfqxyqyt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gt2bhltxoia.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2zbejduvy.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oihqjxlq.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2hhjrbcmt.html

Java: list.subList(1, 4);
来源：http://dali.c1oappe.top/Article/details/gt2epzcvzco.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gt2tpcwfdry.html

Ruby: arr[1, 3]
来源：http://dali.snrcjt.cn/Article/details/gt2uszcafoc.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gt2plkduumh.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gt2xtfhagsz.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnqzz.top/Article/details/gt2dlftnlii.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gt2fuxcilnv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gt2oawckjxi.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gt2gavysgli.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gt2fpcztody.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gt2ykpasypn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gt2etsmskwp.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2gksznqmp.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gt2shdranpg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2pzrlghpb.html


<!-- 参考信息 -->