代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.c1oappe.top/Article/details/gt2qbhmqsul.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2sbcvfksg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2sksfific.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2uaztqokj.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gt2dijbzqjw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gt2ztuepyta.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daxiang520.top/Article/details/gt2chifxkiz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2yegblrqm.html

[B09] break 与 continue
来源：http://dali.jlsjyb.cn/Article/details/gt2siiktldu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.bjfxy.top/Article/details/gt2sdsdezfr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gt2olxwktwu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2sistokbb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2ltnhxclj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2ngnmapvw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dianchejie.cn/Article/details/gt2nrvgcrzm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jlsjyb.cn/Article/details/gt2kzobrenh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2yebitufk.html

[B10] 遍历同时拿索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqylukwx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fzhhl.top/Article/details/gt2xmayezag.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gt2fimuhacc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gt2ouzflnay.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gt2quhkoxmd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ydzc1.top/Article/details/gt2gxehlkpb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uszjyuta.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzsqtnhn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gt2zryrpxnq.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258888.top/Article/details/gt2ibkjokuy.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gt2lbywadhe.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yayzednu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gt2usaubjjc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2uraimpda.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2alcvqwtx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tianlin.xyz/Article/details/gt2kjpdfrnp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shuidangran.top/Article/details/gt2njmycelh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dianchejie.cn/Article/details/gt2mnpkmcfq.html

[B12] 跳出多层循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgfidjgp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gt2jetjbtyn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fengsongda.top/Article/details/gt2isktsccf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gt2ialkprsa.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gt2wpvzvbwp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gt2qannvemw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nwbrower.top/Article/details/gt2jmfprfut.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gt2pvubkcih.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btsdqkoh.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwgleqbo.html

Py:   isinstance(x, (int, float))
来源：http://dali.sysykeji.top/Article/details/gt2etewbqbz.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gt2rxrzszha.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2wrsyujim.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gt2dzkxpphs.html

Java: x instanceof Number
来源：http://dali.zhoulong.xyz/Article/details/gt2mwtcsldk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxuanxn.top/Article/details/gt2wqtuorrd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhoulong.xyz/Article/details/gt2dudnwtxt.html

C#:   x is int or double or decimal
来源：http://dali.gotoacloud.top/Article/details/gt2dprjfndu.html

[B14] 判断值是否在集合内
来源：http://dali.yonumen.top/Article/details/gt2xprpcjdy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxnbemxh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nwbrower.top/Article/details/gt2jlwaoqos.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wjombnhy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2jrbapscd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2scdrgksu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gt2nnvpgwcj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zycfv.cn/Article/details/gt2ppxvtfzs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2trworgra.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gt2fxdcesbl.html

Py:   a and b or not c
来源：http://dali.jyoumei.cn/Article/details/gt2ixctmkma.html

PHP:  $a && $b || !$c
来源：http://dali.tianlin.xyz/Article/details/gt2bemlbprv.html

JS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2cmnjnarp.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2msqznhnf.html

Java: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gt2zgqndfig.html

Go:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2kheqzohb.html

Ruby: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2tynxiomo.html

C#:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpvygpbo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gt2pshrqcdz.html

Py:   if not data: return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmbjdtka.html

PHP:  if (!$data) { return; }
来源：http://dali.cashguo.top/Article/details/gt2bwntyysh.html

JS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gt2wuucjasp.html

TS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gt2mqiodsma.html

Java: if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gt2vcbvyctb.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gt2wfzxsdro.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gt2cznsvoso.html

C#:   if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2vmzyaxxf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2bxbuzjyw.html

C. 函数与作用域
来源：http://dali.haohaochexian.top/Article/details/gt2pbrakqwp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggonrdnf.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2jlwgjgcq.html

Py:   def add(a, b): return a + b
来源：http://dali.hammf.cn/Article/details/gt2nndhqvmu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2fyqyenzi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2bavkmnez.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2gxyrrhbo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2tavhlubj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2bgconung.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gt2weycuhan.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmgudfmi.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gt2lukiaprx.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258.top/Article/details/gt2hmckhdix.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.c1oappe.top/Article/details/gt2vzbstazm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2xrqmbhgc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2afllruhu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gt2xglqjxrs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ybcxt.top/Article/details/gt2kbhvcrbc.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gt2dgzwdojj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gt2stxsylgn.html

[C03] 可变参数
来源：http://dali.yj20258888.top/Article/details/gt2ffavluuk.html

Py:   def total(*args): return sum(args)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bluueffz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gt2mcbabmrd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iagiknjb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gt2fglqfvwp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tejglvla.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gt2gpkgymci.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gt2hyjikqwx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gt2mgaswise.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gt2ltpmdrxt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gt2rqqexicd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljvxeyjx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gt2idchxjsa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gt2gxpvyvff.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gt2vbbhjuvu.html

Go:   // 无：用配置结构体参数
来源：http://dali.tian-w.cn/Article/details/gt2nfsnalwv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2bvjfbhgm.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gt2quezsigb.html

[C05] 返回多个值
来源：http://dali.cheryme.top/Article/details/gt2jinscjzb.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gt2gshumvgf.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gt2gxbuudou.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gt2gulsgjhn.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gt2curoipuy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gt2dvmwjxnt.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gt2oeswttwl.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2zenvvhse.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gt2fcsjvecm.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gt2duztehox.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gt2lmnlxxcy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sysykeji.top/Article/details/gt2jkpzlaer.html

JS:   const square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gt2keltgdzp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2bmmyolxx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfmatphx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gt2yewfnfxl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigfzy.top/Article/details/gt2czyrrrpl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2mzxorhkj.html

[C07] 把函数作为参数传入
来源：http://dali.andypj.xyz/Article/details/gt2uevcvpfz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.0kj1m.cn/Article/details/gt2lcpaxdie.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2frrjskjn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yangfankeji.com/Article/details/gt2hlhsjfnn.html

TS:   arr.map(String)
来源：http://dali.hysaishi.cn/Article/details/gt2nvlrdyvs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gt2fkjvkmxq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gt2cfkuwjjl.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gt2thjqlwde.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gt2lhfesryp.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gt2wolsbqqp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjnmmxuw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qikobmfo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2cmdfagyh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2rklzsxwx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ivvv.top/Article/details/gt2ybxosxem.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2habaqjta.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yangfankeji.com/Article/details/gt2coukzukq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btpfytns.html

[C09] 递归
来源：http://dali.snrcjt.cn/Article/details/gt2wlcutawk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gt2htndzzmh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yongpay.top/Article/details/gt2yejgcrnw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gt2bdmfsqoj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gt2qhygrwqf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gt2fjteiyse.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gt2vxisaace.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2furlpsue.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gt2pmemhmqm.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gt2gzulvcuh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daria6918.cn/Article/details/gt2chrwbyqx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gt2aylnjaxu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2udseidiv.html

TS:   同 JS
来源：http://dali.aibaodan.cn/Article/details/gt2mgcgvgpt.html

Java: 方法内为块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2peobwvsc.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gt2vuswajce.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdptelbt.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2njitxuin.html

[C11] 模块导入与导出
来源：http://dali.birdmap.top/Article/details/gt2ukshcilk.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gt2psrpfuib.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pglemvho.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2anszzisk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gt2suezzack.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gt2sqovkwas.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cashguo.top/Article/details/gt2yajsqxez.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aibaodan.cn/Article/details/gt2htxhtucz.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gt2vcrzuebs.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gt2cyldatdc.html

Py:   (lambda: print("run"))()
来源：http://dali.jiagoushi.top/Article/details/gt2fhyvgtiu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gt2bfvhfhdj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gt2lxnikxnd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gt2czlmmpvl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gt2cruqrfga.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gt2nxacuyup.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gt2hfqqquic.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2oxwhavxp.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gt2paxjxknl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gt2ynlxwuaf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vaoeaxja.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zycfv.cn/Article/details/gt2diywnqnx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2rqwguwqu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2whrgrfkk.html

Go:   func add(a, b int) int
来源：http://dali.jyoumei.cn/Article/details/gt2wotxbgpx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksruqoct.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzrymypu.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gt2vhmnmgcr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gt2ckwtqutg.html

PHP:  // 无泛型
来源：http://dali.sweek.top/Article/details/gt2brnqjvez.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gt2srifxyue.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gt2fctzdxhe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gt2gwuokegl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taremuop.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2anzgniki.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gt2fhehqulu.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gt2cvrwgxne.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gt2epayleab.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gt2ormeixcd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgeywoeu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ydzc1.top/Article/details/gt2lozplbvi.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxgbgmbd.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gt2xlpuipvw.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gt2nspmwxco.html

C#:   var (a, b) = pair;
来源：http://dali.yanxiufei.cn/Article/details/gt2pqaxgsoe.html

[C16] 函数 / 方法重载
来源：http://dali.zhoulong.xyz/Article/details/gt2vjxaneof.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gt2xvuraneu.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gt2unkpzdkk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hfpthk.cn/Article/details/gt2qyfldhsb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxuanxn.top/Article/details/gt2ljobgvgz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gt2vryawsfz.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gt2xqwgfqkc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gt2jwxlizwo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.redwolf501.top/Article/details/gt2qxoxtweu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2yqcxozkn.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gt2oazmozmu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2wfwwmjkj.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gt2edxtmqzv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gt2nerljsgj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2grqmzexb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gt2iufexspu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gt2zbrkxjri.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gt2hdenpdgn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gt2yqskjkrv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gt2irqqnhve.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gt2rxbkkqkv.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gt2bshxvsve.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gt2tslithxs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daria6918.cn/Article/details/gt2yfiapjnz.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2lrlnodva.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gt2epblpvhf.html

Java: list.add(4);
来源：http://dali.hysaishi.cn/Article/details/gt2nowkolxn.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2ykszoxcq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jianghu66.top/Article/details/gt2rgaiwjea.html

C#:   list.Add(4);
来源：http://dali.yj202588.top/Article/details/gt2jopdvfge.html

[D03] 在指定位置插入元素
来源：http://dali.yj202588.top/Article/details/gt2rtgcfrau.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2tuogaoiu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gt2voiiitsy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gt2mzadqhvh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gt2zytyutsg.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gopioskl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gt2hfvwyihd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gt2egvwpole.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2gwnfjgqn.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gt2eafxvrbk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gt2pqemhijo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czbwkohs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ivvv.top/Article/details/gt2rfsbvbio.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2luepnhdo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fengsongda.top/Article/details/gt2kkzmbwdb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryczpnuc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gt2vxyjcgch.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gt2wxxolbrl.html

[D05] 访问与修改元素
来源：http://dali.sufxvd.cn/Article/details/gt2lgsvmvzb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2fstnbomu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2opiydujc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2lfohbhgh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgpoaebz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gt2oidkrcqf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2npzdoalf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2nnxasjnl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2iikuauam.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gt2lraawuxr.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2mmfhxmie.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2xnpcsnah.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnsnofwx.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gt2hwndzgpk.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gt2ysrckmep.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2ediocole.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gt2vfnfnmnv.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gt2rixzsgsu.html

[D07] 切片 / 取子数组
来源：http://dali.jlsjyb.cn/Article/details/gt2ykvyzlai.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gt2tccadufu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gt2mqtbzfvf.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2xxvnvxon.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gt2ptsdecvu.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gt2jxrnyian.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gt2epstzhyc.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gt2ywfaamfz.html

C#:   list.GetRange(1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wscaepcl.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gt2nomrsryt.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gt2hhjoyysi.html

PHP:  array_merge($a, $b);
来源：http://dali.andypj.xyz/Article/details/gt2gslgatqc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hfpthk.cn/Article/details/gt2kmnsnyrl.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gt2bnogqzcy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msatyxvl.html

Go:   append(a, b...)
来源：http://dali.cheryme.top/Article/details/gt2zmlncpyp.html


<!-- 参考信息 -->