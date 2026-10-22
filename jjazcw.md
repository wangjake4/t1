代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.andypj.xyz/Article/details/gtnqcwuhbz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtvqtpfwtr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaepbumn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtxccxdufr.html

Java: do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gticqildbs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.daria6918.cn/Article/details/gtdzhtdqpa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzkhdtea.html

C#:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtqywrvwfu.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gtwwkqsdqd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gtabfmqrfs.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtppruhnft.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtyqdgncgk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtjzdeeqfe.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtzapqlflp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gtvomhicyx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhengqikj.top/Article/details/gtafemmmgn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtotthndcs.html

[B10] 遍历同时拿索引
来源：http://dali.hysaishi.cn/Article/details/gtbtcbhyhf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.c1oappe.top/Article/details/gtsdbajomx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxyiigkzq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtjmhmhdwh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpykqshk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.andypj.xyz/Article/details/gthvnawuvg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnxiangtu.top/Article/details/gtuawdfmte.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jyoumei.cn/Article/details/gthovocqpu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.haohaochexian.top/Article/details/gtelsrcvgh.html

[B11] 生成数字序列 / 区间
来源：http://dali.fzhhl.top/Article/details/gtdgnxqqts.html

Py:   list(range(0, 10, 2))
来源：http://dali.jlsjyb.cn/Article/details/gtdxatyhpd.html

PHP:  range(0, 10, 2);
来源：http://dali.ydzc1.top/Article/details/gtwevjopdl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtxkxqiwhm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtdgkrtfrv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gtkjyeyqcg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gtonqthwkq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.vqdsnc.cn/Article/details/gtlifxnjyt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjuszoeo.html

[B12] 跳出多层循环
来源：http://dali.jqgufenzy.top/Article/details/gtntfccldr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pycfn.com/Article/details/gtomtnbtto.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtrogmftvj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtxwjbjkjb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtiozzjykc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtfjzjxfuc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenjidiqi.icu/Article/details/gtvsbrrqlq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhoulong.xyz/Article/details/gtfplnqigi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cucudq.cn/Article/details/gteihagudr.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gtgumoikff.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gtqwjdiepr.html

PHP:  is_numeric($x)
来源：http://dali.hywenlv.cn/Article/details/gtdzzntazw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtwdudznkz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gtqqqynccj.html

Java: x instanceof Number
来源：http://dali.hywenlv.cn/Article/details/gtlpdzkjvi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cheryme.top/Article/details/gtjuratzub.html

Ruby: x.is_a?(Numeric)
来源：http://dali.vqdsnc.cn/Article/details/gtxaarjetx.html

C#:   x is int or double or decimal
来源：http://dali.sweek.top/Article/details/gttwnenmyy.html

[B14] 判断值是否在集合内
来源：http://dali.c1oappe.top/Article/details/gtnzbfwudq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ivvv.top/Article/details/gthrfjzicf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gtxxlnvkon.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gthlwuwouf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtrxvlpotq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtkorjkkfu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shzxlz.cn/Article/details/gtpirlmnuc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtxjjmuozp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtblvfolki.html

[B15] 布尔运算与取反
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmuseuil.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtdrsvppfi.html

PHP:  $a && $b || !$c
来源：http://dali.tianlin.xyz/Article/details/gtpwyumdbt.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gthounnzyl.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtwrlgokqg.html

Java: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtlnqzptmw.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtgsmbfbur.html

Ruby: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtruvlcsyu.html

C#:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtrvdaqzwf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yangfankeji.com/Article/details/gtufalainl.html

Py:   if not data: return
来源：http://dali.shangyingyoupin.top/Article/details/gtzybhmqlg.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gtkmymghgy.html

JS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtvwtxscon.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtwnfolotk.html

Java: if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gttbeoinyn.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gtslubbtpa.html

Ruby: return if data.nil?
来源：http://dali.ybcxt.top/Article/details/gtiolxebvs.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtppzeyzpo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwirttjac.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gtjbvwogpo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrsvcarss.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtfpzqjerq.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gtzyipmkne.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdzitpiox.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtuycopzvk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gthpstucwa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtbcpxcnpb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.haohaochexian.top/Article/details/gtuorkfvvi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gtqmksttyl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtjhlpbumz.html

[C02] 默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtiazdxkgw.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtbzfrqtge.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gthqcvxjuz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtpogvqjrk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtynptziov.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtaclvhxte.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gtvojsffpk.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbqzpzan.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gtkrzvkryb.html

[C03] 可变参数
来源：http://dali.cheryme.top/Article/details/gtogtsqcno.html

Py:   def total(*args): return sum(args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydovuely.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sysykeji.top/Article/details/gtreblcnqv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtbxeprqoy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gtjeqhwhfr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gtylgjwcaq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gtttergvgy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gtmsagochx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenjidiqi.icu/Article/details/gtylopuwfo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zycfv.cn/Article/details/gthkolmcxl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gtieylptxg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtbpzuuemx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gtkoofhtfa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtwunpegxe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gtpcggnmlx.html

Go:   // 无：用配置结构体参数
来源：http://dali.tanke756.top/Article/details/gtykpkmsii.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtyxihvgyb.html

C#:   f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtucnxqyjw.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gtajjtceaz.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtbzjnasug.html

PHP:  return [$a, $b];
来源：http://dali.sxryk.cn/Article/details/gtienbavwv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtvselokyz.html

TS:   return { a, b };
来源：http://dali.c1oappe.top/Article/details/gtzaermkoh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjsljbkd.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdguydxs.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gtiamithap.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gtibcpfxjv.html

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gtozadurky.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtrhjqltml.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtnrtvgvfy.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtlcizwrvv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shuidangran.top/Article/details/gtjlwgyeoh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gtrdtnwkef.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gtgkyykhhv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gtctrtiffz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtexuzhdyn.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtmicryxbu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gtolfyyesh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtgjketzpn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigufen.top/Article/details/gtrtrasoqd.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gtftvllxcn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtnuvdrekj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gtylhvuuwk.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gtyhhlgyjw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gtiarxunsv.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gtyheeuqwp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gtncznsfyh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yvedp.cn/Article/details/gtjrnufkac.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtztyfrayk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtvsbwbxyp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shzxlz.cn/Article/details/gtzrehumvg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gtmysprsuk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.andypj.xyz/Article/details/gthguhnhiu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gteoghnurz.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gttqypczle.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gtlerwietb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gttxnhdkcm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtkqsrncqk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtkzhisptw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gteeczvvxh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xinyue.icu/Article/details/gttoghtqkw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gttmdumrbo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258.top/Article/details/gtcmgkblwn.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtvwzhunso.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gtdeutaqjp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aibaodan.cn/Article/details/gtgwhxatyu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytrluudj.html

TS:   同 JS
来源：http://dali.daria6918.cn/Article/details/gtwytbasnm.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtsktbogtt.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtxdhrbfrl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dashuyun.cn/Article/details/gtqouqheod.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gtkjhkamdu.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gtxwjyctik.html

Py:   from module import func
来源：http://dali.yuanzhike.top/Article/details/gtpyslutsu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gteorepepb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yongpay.top/Article/details/gtfdavirbw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gtsduuivjc.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gtsxgczxri.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gtwwyzrupy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gthzoowqwc.html

C#:   using System.Text;
来源：http://dali.0kj1m.cn/Article/details/gtzxrdubkz.html

[C12] 立即执行函数 IIFE
来源：http://dali.shangyingyoupin.top/Article/details/gtfcpmejff.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gtpdejvifi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gtkdkqqseo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtkwzxkdro.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthludtkyj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gtzawnlsqc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gtrfsnsled.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfdosvvz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gtrgnxcvau.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gtpsadolkr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gtfecsgvnl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtabxjqmfm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gtdzjtanwe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtkdzqxfvi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgadjrcax.html

Go:   func add(a, b int) int
来源：http://dali.xziqi.cn/Article/details/gtqjawsdjq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gthwpblphi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtxbsaodwb.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnszuwep.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtcaflefxg.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmfuotmy.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gtiqqsxmyv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfuujzhds.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gthzkryfad.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gthbzcrrwm.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtkkndkhpw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gtuiluljgz.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gtxbqoelec.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pycfn.com/Article/details/gtqaqmyhbw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gtutyvgplo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtsedvqwat.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gterfgskuf.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gtxmsrpziy.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtebqjfkya.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gtnmsierda.html

C#:   var (a, b) = pair;
来源：http://dali.jqgufenzy.top/Article/details/gtuvlbupiy.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gtjmfnhcqo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gtauhohbpq.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gtgdglrmzi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.haohaochexian.top/Article/details/gtkeuepxqg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gtqdwnisvn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ppjwa.cn/Article/details/gtzyoephtd.html

Go:   // 无重载：用不同函数名
来源：http://dali.guowangkeji.top/Article/details/gtsaeghfiz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gtlxauxifv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtxmbyzzmd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpslugdaj.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gtjywjjwax.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkxvxmgbh.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtfxyuetlv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gtgrkmqzow.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gtihnapyzx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nwbrower.top/Article/details/gtsldfevbg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdabnckt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gtyvkqcfnw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gtjbcmfpin.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtsnruvorn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gtqwuwutsa.html

[D02] 追加元素到末尾
来源：http://dali.sysykeji.top/Article/details/gtnhqmvjmh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gtkcpjyvfx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtyvlaqqor.html

JS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtfzbmfgpi.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtcuugaoiz.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtixhdmycb.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gthobgekst.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gtfvexhvnb.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gtkltktwhg.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnmlgdsh.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtupcnbouz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gtgsgmuwul.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gtkojfwdfi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtbbmormmj.html

Java: list.add(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtqaovjnpf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gtwrfgcipq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtegcpkzzq.html

C#:   list.Insert(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtylgqbijq.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtixwpmvrl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtfyiphktk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gtfechszfd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtzmwuimxy.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gtrlwcbqbg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gtuobwdsmh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtwsfkiqra.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gtqzydbakd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaeiaxld.html

[D05] 访问与修改元素
来源：http://dali.jinqigufen.top/Article/details/gtzulzakhj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtrdlgpcno.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtrjligxlb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtkegqtxwf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gtbztgqaaw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ppjwa.cn/Article/details/gtrsgdbtpn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtflqbqsvb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtqtjrjgcr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtedfkxpbl.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtaabtqfpd.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtsifoplwf.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtxpjdakro.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtdslvfvle.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtotqrwxly.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtctypfxpn.html

Go:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtsyvmzqlq.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtcvaoqzwx.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gthmzalpeo.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gtkbusawes.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gtybezwkhz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gzhubu.top/Article/details/gtstfhvnps.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtqemnsdcr.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtypmizspg.html

Java: list.subList(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtmthazdrt.html

Go:   arr[1:4]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvsvhzrz.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtpvxwzhkv.html

C#:   list.GetRange(1, 3);
来源：http://dali.andypj.xyz/Article/details/gtiydhbvbc.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gtxhtmdvci.html

Py:   a + b;  a.extend(b)
来源：http://dali.xylfe.cn/Article/details/gtfzkjxokd.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gtnjxezrpq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gtnuyatqqb.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtmijggcyt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gtnxzoortx.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gtabplugdz.html


<!-- 参考信息 -->