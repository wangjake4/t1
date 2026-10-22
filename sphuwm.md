代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zycfv.cn/Article/details/gt2vifkrjzn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zycfv.cn/Article/details/gt2wekzzjwk.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2munraitw.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gt2gcqklqku.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.svipenyu.cn/Article/details/gt2tbeekqab.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2glmpbthf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2algbjady.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2giqgbbfk.html

Java: do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2wknqmnqq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nsvhnjui.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cakqedoi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gt2zptvmaki.html

[B09] break 与 continue
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcwmtreh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.iojbl.cn/Article/details/gt2tgricwgh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2lppyboer.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2zjxtfbso.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gt2vsqsoyfk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taykxfke.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj202588.top/Article/details/gt2kywyrsme.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zdqjudy.top/Article/details/gt2nsiinsun.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gt2paxecabe.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gt2zbzpibni.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yvedp.cn/Article/details/gt2fdtmlueb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gt2lniwoyut.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gt2djiudjll.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.snrcjt.cn/Article/details/gt2chqikzvs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ydzc1.top/Article/details/gt2nxvwviby.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gt2qztyakcb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eesmuevi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2buvzhzer.html

[B11] 生成数字序列 / 区间
来源：http://dali.andypj.xyz/Article/details/gt2xrghmiqt.html

Py:   list(range(0, 10, 2))
来源：http://dali.jlsjyb.cn/Article/details/gt2iwqlonym.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gt2ccqxnkht.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2hyzfeobm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gt2jrrmngzg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.havefunace.top/Article/details/gt2kwiptaza.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pycfn.com/Article/details/gt2sgbhbvlt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gotoacloud.top/Article/details/gt2syaydtnn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pycfn.com/Article/details/gt2nkkitndz.html

[B12] 跳出多层循环
来源：http://dali.yangfankeji.com/Article/details/gt2yepnezhf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jyoumei.cn/Article/details/gt2kzfzlajg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yonumen.top/Article/details/gt2suffunoz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2osikhbma.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvnadkag.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gt2fzbzdqsi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zycfv.cn/Article/details/gt2gyrddfho.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.haohaochexian.top/Article/details/gt2omimacyj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gt2hbadurbs.html

[B13] 判断是否为数字
来源：http://dali.snrcjt.cn/Article/details/gt2otfbhhzv.html

Py:   isinstance(x, (int, float))
来源：http://dali.daxiang520.top/Article/details/gt2vdrpjajp.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gt2bpwszlce.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gt2psdblfwy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gt2lkprnrzn.html

Java: x instanceof Number
来源：http://dali.hysaishi.cn/Article/details/gt2gsihqgkn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cdnleiting.top/Article/details/gt2oenuxeju.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gt2jtqxdihs.html

C#:   x is int or double or decimal
来源：http://dali.jyoumei.cn/Article/details/gt2nyspskni.html

[B14] 判断值是否在集合内
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjaawyig.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gt2skelmxfe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gt2lhtfogup.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2cubaupnk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gt2yqdnbyvj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiowjrou.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrqwgkgu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2ohqydmgo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2lazyiuhp.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gt2ybotbgew.html

Py:   a and b or not c
来源：http://dali.wangshuangyany.cn/Article/details/gt2swrzhzbn.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258888.top/Article/details/gt2surkrzjg.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2ytvbypql.html

TS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2bzthaqcn.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2xchghohg.html

Go:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2swlnylxy.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2ztgbxzwa.html

C#:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2nscltrta.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yvedp.cn/Article/details/gt2bkvljeou.html

Py:   if not data: return
来源：http://dali.daria6918.cn/Article/details/gt2cympgtmn.html

PHP:  if (!$data) { return; }
来源：http://dali.gaohongyu789.top/Article/details/gt2eiqfqver.html

JS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gt2flzoewrk.html

TS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gt2dlhwhgwb.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gt2crnocevc.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gt2kusxcrhb.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gt2ibfqovuw.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2qbvgjalr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2kqualvpz.html

C. 函数与作用域
来源：http://dali.xylfe.cn/Article/details/gt2zzjtyvnf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2xiliyvev.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2savmzxrf.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bckeoaez.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2pcbhadzb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2jsrofxyh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2ywkwodjf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uuavypbd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2vzasxiyb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gt2kahhqhhe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2udjsyigz.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gt2ksofiuka.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258.top/Article/details/gt2ldikzivp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gt2gjcxvrms.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2gvbogyqi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2gprilccg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.bjfxy.top/Article/details/gt2ahgynprm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aibaodan.cn/Article/details/gt2eczgyfvb.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gt2afiwzbkz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxinkj.top/Article/details/gt2tsesaxwq.html

[C03] 可变参数
来源：http://dali.zdqjudy.top/Article/details/gt2qyogxiqc.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gt2hclmrffd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258.top/Article/details/gt2dcwvrmsx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ivibfqyf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2sjckwyod.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcuclqiu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gt2beacrtwh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzakods.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gt2jyblrecx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gt2vtzeapxt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gt2jujyykce.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yonumen.top/Article/details/gt2tgswonqe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gt2zhimsbnd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjjjigwx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jianghu66.top/Article/details/gt2oziqhiih.html

Go:   // 无：用配置结构体参数
来源：http://dali.cdnleiting.top/Article/details/gt2tuynofnh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gt2idxtvfqj.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ffuzivzc.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gt2svcdmuvd.html

Py:   return a, b
来源：http://dali.yueranfly.top/Article/details/gt2jsqbunuq.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gt2tzbvdqjz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gt2fekdqloe.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiicznmq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gt2noxpajjo.html

Go:   return a, b
来源：http://dali.havefunace.top/Article/details/gt2ymvutlui.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2rhbeobcy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gt2rhdsgupu.html

[C06] 匿名函数 / lambda
来源：http://dali.pycfn.com/Article/details/gt2meduzjec.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gt2levxwiez.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gt2iyzogbwm.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2qhhlnfxz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hammf.cn/Article/details/gt2qcnrmlnn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gt2toojbjjm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gt2ggwzmajo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gt2nqupovag.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2azdupqma.html

[C07] 把函数作为参数传入
来源：http://dali.pengpengdd.cyou/Article/details/gt2arrbkjak.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gt2itajsjpp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2tezcsbsv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pengpengdd.cyou/Article/details/gt2skhqmkel.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcqhcsyq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2anngrkvs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gt2okamyruk.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzpcwhtp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tian-w.cn/Article/details/gt2pekkeqva.html

[C08] 闭包
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrpnipfd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yanxiufei.cn/Article/details/gt2bhijedib.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gt2dsfyvmou.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2rohvlzvo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2grxgfhuk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gt2dccbfgsm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gt2edzskkho.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xylfe.cn/Article/details/gt2uzgkarek.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kigcvudb.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gt2nrkaeqnt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gt2jkkqyizd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuxming.cn/Article/details/gt2zkedfyrb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gt2civewjpa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gt2bwpcqelj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gt2jtqdzzqf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhixingplan.top/Article/details/gt2qcnazrjc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gt2ntrvmmcs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkildmev.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2vtvemuhs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gt2sgzgwqxq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlhevzte.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2acxiqwbb.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otpkrwio.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2axdihzwe.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2fjxydhmu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gt2wyictzno.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqqdliag.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2faiinilf.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gt2uopajuiw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gt2mlfiaieh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gt2ovjzgtet.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2teuksski.html

Java: import java.util.List;
来源：http://dali.jinqigufen.top/Article/details/gt2cfcwqxtt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gt2iuvfeqws.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gt2orzdaysx.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gt2cgndzbdy.html

[C12] 立即执行函数 IIFE
来源：http://dali.guowangkeji.top/Article/details/gt2aclqthpg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gt2liggnczk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gt2cvsyixea.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2kylhlyvb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2euupknyf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gt2gnnfonsn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gt2jsfmpmqq.html

Ruby: -> { puts "run" }.call
来源：http://dali.aibaodan.cn/Article/details/gt2qtalxnvu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gt2ennvddff.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gt2ndasfudl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gt2ihcmdmtu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gt2qotgmpex.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gt2jnampxgl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2qmigvfvl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2vpdihsvw.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gt2oiuepdds.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gt2ogmgygcd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gt2wzfhasjl.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gt2eczwfvki.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gt2rbpxcvnf.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2geasqsoo.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2ivijcncz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ivvv.top/Article/details/gt2daiosfjy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daxiang520.top/Article/details/gt2qqhkdmfx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gt2mzlpezsd.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nkakypvx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tian-w.cn/Article/details/gt2pasjmnja.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gt2odlelutc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gt2rferwiow.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gt2wusbvxvw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2exwxnzyc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gt2grvahiuy.html

Java: // 无解构
来源：http://dali.bjfxy.top/Article/details/gt2ymsbuqit.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gt2hxslhwyj.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gt2ukvvkgjv.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gt2zjziovym.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gt2orzpinfp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gt2alamgsnb.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gt2rakbfkvo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gt2slmpadtd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guannengcc.top/Article/details/gt2ggrtxlqr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijefgpxe.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gt2xgtvtmzc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gt2uegnnsjh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yongpay.top/Article/details/gt2wvhyuytw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzslrhes.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gt2kquxsppz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2bjqowasq.html

[D01] 创建数组 / 列表
来源：http://dali.kuanghao11.cn/Article/details/gt2wkcsrkej.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhengqikj.top/Article/details/gt2lqdocsel.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdsmpdod.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gt2sxmvbuaa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gt2xmofpeoo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gt2kqsyfnoz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gt2mnghpumf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gt2duewypqu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gt2msjyiuhn.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gt2ztriiayk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gt2pemzxldy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gt2pxlapqeh.html

JS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2wvguiezi.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gt2bekqyjxq.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rybnccsj.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gt2lnuumprv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gt2yioaandh.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2hsvsdlxd.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gt2pzlevuay.html

Py:   arr.insert(0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqdketur.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hysaishi.cn/Article/details/gt2eylkeljy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gt2qdibemoj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2hpzlmcts.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2eahamnxz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gt2ebiwvsuw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gt2nhwzzxro.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2sfzmgjyt.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gt2vauyxtsh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gogol.net.cn/Article/details/gt2tphumupe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gt2weagmcrq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gt2erpucplg.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gt2tbkawtgx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gt2qcsskzep.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gt2qycpxhkl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gt2ycrjcloy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2beklxcmd.html

[D05] 访问与修改元素
来源：http://dali.hywenlv.cn/Article/details/gt2tqfwzwdt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2jqqhitmy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gt2iinpsqly.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2urvadglc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gt2mvgewkoh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gt2hdocohda.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2fetnxzsg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2roehxbec.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2qdyyrszv.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gt2xydcreth.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtlnqqwd.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2omxyfqyt.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gt2etmxdjtw.html

TS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gt2rrngulas.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myhmbafd.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gt2oqeheuji.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gt2turczffw.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khweydyn.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gt2ptbjzsij.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gt2dbadvtqj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2qcgiukzg.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2exugdzyv.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2mzfqxfau.html

Java: list.subList(1, 4);
来源：http://dali.yuxming.cn/Article/details/gt2wcdbxsvp.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gt2ngfcrkes.html

Ruby: arr[1, 3]
来源：http://dali.birdmap.top/Article/details/gt2bvnbowkb.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gt2lwdhbfng.html

[D08] 合并两个数组
来源：http://dali.yangfankeji.com/Article/details/gt2hnqgwnkj.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gt2okewujer.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gt2wjkwxqcg.html


<!-- 参考信息 -->