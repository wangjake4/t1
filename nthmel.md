代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.fengsongda.top/Article/details/gt2bajlyimn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj202588.top/Article/details/gt2zxdyythx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2ydfnjakj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2wddbuhkb.html

Java: do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2fcvjkrsf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tianlin.xyz/Article/details/gt2uxlssxmm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnxiangtu.top/Article/details/gt2kwumdfru.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2gqndotnf.html

[B09] break 与 continue
来源：http://dali.xziqi.cn/Article/details/gt2hmdlionp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnxiangtu.top/Article/details/gt2rqcfhknm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2yftmtste.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdsdwcbx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2tswpajfu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkwzuwdb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gt2lcjaktyq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gt2dayszasj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2uidyzkgl.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gt2nllchpqz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvwnfogv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hammf.cn/Article/details/gt2kwylleyc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gt2bamamjmz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gt2mdgfuwpt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gt2rugymsbh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gt2napocytg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gt2hecxviql.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.0kj1m.cn/Article/details/gt2rxxovvtk.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gt2xlgnrjma.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wltzeqrg.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jaumvrky.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gt2aeffxazr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gt2mqpxjkgb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2hdfrzwag.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aibaodan.cn/Article/details/gt2dmvjzdrr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aeiekpbz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvepheyz.html

[B12] 跳出多层循环
来源：http://dali.316326.xyz/Article/details/gt2synzeonh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jyoumei.cn/Article/details/gt2zgjthxaf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gt2tethgowc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gt2khaidnls.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gt2ruwpcyry.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gt2ijntfdfd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shzxlz.cn/Article/details/gt2dtbllvzd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2khuntwax.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gt2dpizojvf.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gt2lgtylyel.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gt2iqmgymqu.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gt2amwjnndq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258888.top/Article/details/gt2clbfwjfs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gt2axnpbybk.html

Java: x instanceof Number
来源：http://dali.316326.xyz/Article/details/gt2shwrtonj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.c1oappe.top/Article/details/gt2ssvgyuyp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tian-w.cn/Article/details/gt2mviiqpgg.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gt2jofjbytz.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gt2swwuiksp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqrqnukb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.9152youxi.cn/Article/details/gt2iobxsqvs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2swtwktod.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2yxcdzzmv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2phrbbbcn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.snrcjt.cn/Article/details/gt2yuqdgjjw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2atqpsuoy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2pwkrumls.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2euhvjeqd.html

Py:   a and b or not c
来源：http://dali.sysykeji.top/Article/details/gt2lbgnkrnk.html

PHP:  $a && $b || !$c
来源：http://dali.dianchejie.cn/Article/details/gt2mkidwuzv.html

JS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2ikkpcbpn.html

TS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2vrluenxq.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2mgmjblaj.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2wjvpgthh.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2aelfbvyf.html

C#:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2eleqywkt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gt2iqgimbml.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gt2bdjhqivt.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gt2qodncazp.html

JS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gt2auupnzqm.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2ymzrulnx.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gt2lkcpeqfp.html

Go:   if data == nil { return }
来源：http://dali.hnxiangtu.top/Article/details/gt2hskxjrgj.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkjbykzh.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gt2jlyrpgil.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2vjkpevuj.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gt2yhbplpjo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2sbpewwnx.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2tnenutan.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2oxigsgxs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2rqlgmyut.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2pnxoytlo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2mpwlqzwr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2gtgxpvmo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmxyaeea.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gt2whgelzbj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2ntozbivw.html

[C02] 默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxcbvcji.html

Py:   def greet(name="World"): return name
来源：http://dali.zhixingplan.top/Article/details/gt2dzidxahd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhengqikj.top/Article/details/gt2mainmoho.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2amtpdgvn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gt2ntbhjivb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2aajhrega.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tianlin.xyz/Article/details/gt2rsegreln.html

Ruby: def greet(name = "World") = name
来源：http://dali.vqdsnc.cn/Article/details/gt2jheaxxxn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gt2edvoekyv.html

[C03] 可变参数
来源：http://dali.yvedp.cn/Article/details/gt2jcqhasov.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gt2cnvpwyil.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gt2plxcllwu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gt2yvlnbmwc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gt2iwcqikaj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gt2xdvnqbow.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gt2oumnianb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjrlflge.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.andypj.xyz/Article/details/gt2dlpvaqdq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gzhubu.top/Article/details/gt2wkwkditi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gt2hmjrgnhr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gt2yzpdadnc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2bxcomxnl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjhdzlaf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqoeolpm.html

Go:   // 无：用配置结构体参数
来源：http://dali.xinyue.icu/Article/details/gt2pdnpeuda.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gt2qtjlbxje.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gt2umyuvejp.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gt2gclyzdwg.html

Py:   return a, b
来源：http://dali.birdmap.top/Article/details/gt2mlbwgxhy.html

PHP:  return [$a, $b];
来源：http://dali.jiagoushi.top/Article/details/gt2rnqxnyxf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gt2sjkzscxn.html

TS:   return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gt2xczgatsu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gt2qsnphzhg.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gt2bnhlddft.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2sorjqhrb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gt2eoyhsvda.html

[C06] 匿名函数 / lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2vhyhkyri.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gt2gaelejlf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shzxlz.cn/Article/details/gt2qimdelus.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gt2bzmuszjj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gt2kzkqcfrb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yongpay.top/Article/details/gt2boqhubpi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ybcxt.top/Article/details/gt2exgibwhg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gt2iqxhtnas.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2bgsbjxez.html

[C07] 把函数作为参数传入
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctoswbqe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gt2pcgjppgp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2dhjojirw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gt2jnzkhrop.html

TS:   arr.map(String)
来源：http://dali.ivvv.top/Article/details/gt2ptmvbgzd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gt2eidpfatb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gt2nnjymniu.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigufen.top/Article/details/gt2qjvnvwii.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqvkambe.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vlazqwss.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gt2bumwfupu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cqqwz.cn/Article/details/gt2kewcfxos.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2wuizeexk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2mtjsczee.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gt2jiezrhyt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gt2fgwpbllo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2werarsvl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2qvvpsver.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gt2jxertmax.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gt2nfgwqiut.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agxspysk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idutevsz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gt2vjpamfzo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2llgufzvd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gt2emlcmfag.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gt2qruobfdk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xinyue.icu/Article/details/gt2pidstpkz.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gt2wmerqpqr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gt2ultlniyf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gt2lcenassb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzdhjlms.html

TS:   同 JS
来源：http://dali.cashguo.top/Article/details/gt2uvtgnhsh.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2tcdlvtto.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2xuaplryo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gzhubu.top/Article/details/gt2gxrlsgna.html

C#:   块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opxfionj.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jurjulxs.html

Py:   from module import func
来源：http://dali.yuanzhike.top/Article/details/gt2latuldip.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kndqmgfo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gt2mryoykkd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gt2oxpahhzl.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gt2labbmhux.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jiagoushi.top/Article/details/gt2euzsgrdf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivxbgdvl.html

C#:   using System.Text;
来源：http://dali.yonumen.top/Article/details/gt2ubhjmwxh.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gt2yaslqwok.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gt2gsoawezi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gt2dvlvuupd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gt2ifkdzgha.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gt2xykqpaup.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gt2odwkmelf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gt2xailkjjm.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gt2furatoph.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2szjhyswk.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gt2bwltuzpy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gt2bcfxldtz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eczbbjcv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gt2smqahmlk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2umzmugeo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2jucguxkj.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gt2oeakefhv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gt2isckohxl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gt2gbdnygin.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gt2valkjjls.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hongshengwenyu.top/Article/details/gt2onnosrij.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2kqzgwrlv.html

JS:   // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gt2vyagpaet.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hywenlv.cn/Article/details/gt2valteqyu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gt2ghzqwhjc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gt2upvoronb.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gt2fleebich.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlhyiecb.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gt2srjfkvxf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gt2xswjlkyq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gt2rvbndljy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgbmhgtu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2txotjhgf.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2gbdqsgji.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2ytcepoen.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdeksjhl.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyzpnvwn.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gt2bthbqtun.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gt2hckyrzrr.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gt2uwrykveo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gt2drlqmmrt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gt2bxtavzul.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2qfdxrrdx.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gt2qzxusbnc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gt2okcrkygs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuirxyrn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2zjwxpced.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gt2jzwgjobk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2rourisjy.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gt2svltaneo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gt2acqavyjg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gt2ypaeswql.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2sesnslmu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gt2xdntrnlq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gt2ejulrbhd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gt2xdmxglgc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2fxepbljb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gt2eftwhktx.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gt2iusamxoq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ybcxt.top/Article/details/gt2upgqdsay.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2tqtiqlbc.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gt2ycvodrhc.html

TS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gt2oibpdywx.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2vxufjwsl.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2hpezlqqu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gt2fofpcavf.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gt2crqumydf.html

[D03] 在指定位置插入元素
来源：http://dali.tian-w.cn/Article/details/gt2bjnrqwas.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2amgmqrtd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnokpbff.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gt2ijhrkxxc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbnxlvib.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2mrjzhqfv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2welgeuec.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tanke756.top/Article/details/gt2ceubrion.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2huwjtbna.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzbhckus.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2rxiyqilw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2tuniqktc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gt2ifruieyr.html

TS:   arr.splice(0, 1);
来源：http://dali.yanxiufei.cn/Article/details/gt2tarzoljr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258.top/Article/details/gt2juvgsocs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gt2qitowjkr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gt2sdcnuoih.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gt2syvapbhw.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gt2fjtpvgdl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2fcohiafj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gt2wxkmqjfw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2pkcaxqvl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hywenlv.cn/Article/details/gt2gnbgxtdh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gt2sbsaftyy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2rdeahqkt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2irnbckty.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2msbxqjfb.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gt2gycfjafx.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2orpayhgl.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2nanmrzxn.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tynwagao.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gt2zdcatjwy.html

Java: list.size();
来源：http://dali.yvedp.cn/Article/details/gt2kouqnjbw.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2lpmqgjnb.html

Ruby: arr.length; arr.size
来源：http://dali.fengsongda.top/Article/details/gt2agpgldeo.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gt2rzqpjdzt.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2iccrcogj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gt2ebgfptyg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gibutnsw.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2xyamrpic.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tegctnjz.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2iyvfnxvo.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gt2kgazapey.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gt2hauqcbnz.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2uhcwcgdk.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gt2xndiukgj.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gt2isbkfadt.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gt2wyjkltub.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gt2lmoktecu.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gt2mrjelzsv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2rpkdlbxf.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gt2kegcabkl.html


<!-- 参考信息 -->