代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtmsslwoie.html

JS:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtztlyanlr.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtyyqlrfbd.html

Java: while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtklbxndfq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hysaishi.cn/Article/details/gtzpaaexpl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxinkj.top/Article/details/gtxxawpqez.html

C#:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtgvvhozqp.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gtigfbiyti.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.quarkkingdee.top/Article/details/gtkzjsjavu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtthcjveot.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtifwrptsn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtokzjjdpw.html

Java: do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtovijcpdm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtwtahuxxl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gzhubu.top/Article/details/gtmkkddnbr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfckyogif.html

[B09] break 与 continue
来源：http://dali.nanxuanxn.top/Article/details/gtflscdeuq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhixingplan.top/Article/details/gtxpyihjob.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtqqorcpes.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtfgaxjbcv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcefztdya.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtdbmumeck.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258.top/Article/details/gthwqsguti.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yanxiufei.cn/Article/details/gtcwokogbv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtwwesswvo.html

[B10] 遍历同时拿索引
来源：http://dali.yj202588.top/Article/details/gtvxsfhfwm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dashuyun.cn/Article/details/gtuoxtazgg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuetiantiany.cn/Article/details/gteuhjyorb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gtqyhyoorz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gtvhshhdps.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhoulong.xyz/Article/details/gtrepcjxbf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guowangkeji.top/Article/details/gtgehobnvo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gtziumjfff.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihjbmlrm.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gtkxvzligk.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gtxhorhwsk.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtwftymvbk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtltphtrvi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gtxjuzshmx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pycfn.com/Article/details/gtpwlawrsp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.kuanghao11.cn/Article/details/gtddlsgzil.html

Ruby: (0...10).step(2).to_a
来源：http://dali.quarkkingdee.top/Article/details/gtyzmyrfzv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtntobvznp.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gtuqnyapgj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.bjfxy.top/Article/details/gtlmmcnzyl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sysykeji.top/Article/details/gtdprpykpf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtikgfkwxg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtrpbuemuu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtgoglebvk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.snrcjt.cn/Article/details/gtusqyuizq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cashguo.top/Article/details/gtlmvjsyie.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gttqzrmnyu.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gttcskfxjv.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gtbxgquyvk.html

PHP:  is_numeric($x)
来源：http://dali.hnqzz.top/Article/details/gtukpewply.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtrpegbkvx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtshgkvqwy.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gtwknurqmi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuxming.cn/Article/details/gtajljvqfp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gtblabltvo.html

C#:   x is int or double or decimal
来源：http://dali.sysykeji.top/Article/details/gtsgroasui.html

[B14] 判断值是否在集合内
来源：http://dali.ydzc1.top/Article/details/gtbccqwtqz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hfpthk.cn/Article/details/gtinrpmywz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.bjfxy.top/Article/details/gtwcfdawdm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtkpzovutj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gtesrvzwju.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hammf.cn/Article/details/gtjemcprxs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtdmwfujda.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuanzx.com/Article/details/gtsrwrntns.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtejxkdamb.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gtgxoufhor.html

Py:   a and b or not c
来源：http://dali.zhengqikj.top/Article/details/gtyypanmpa.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gtuoiyjikc.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gttohqhffp.html

TS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtingqcezk.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtahlutxsa.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtkwgzspfr.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinirzghz.html

C#:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavyuvrpz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gtuykiwvdk.html

Py:   if not data: return
来源：http://dali.birdmap.top/Article/details/gtpffllofb.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gtzhekhndj.html

JS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gtyxmreahc.html

TS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gtidxcwrig.html

Java: if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtsdtexrwj.html

Go:   if data == nil { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtmngvodys.html

Ruby: return if data.nil?
来源：http://dali.zhiwuduotai.top/Article/details/gtxnvrxdvh.html

C#:   if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtabugfpbn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxaulljlg.html

C. 函数与作用域
来源：http://dali.gaohongyu789.top/Article/details/gtxkmvwekq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtibpsnibk.html

[C01] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtzgligqum.html

Py:   def add(a, b): return a + b
来源：http://dali.xuanzx.com/Article/details/gthqdcivkw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtdnmxbcvw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtvfzmkvwx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gttvcvggio.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtbxahqeim.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gthqjcutro.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gtcgszhmlg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtfpfylvdt.html

[C02] 默认参数
来源：http://dali.jyoumei.cn/Article/details/gtdvjfrbjv.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gtqpomtbyp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gtkpzbxeqc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfrlgluyr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtcyxeqjwf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gtzogrdzdv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gtxagpfyts.html

Ruby: def greet(name = "World") = name
来源：http://dali.ydzc1.top/Article/details/gtfereurld.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gaohongyu789.top/Article/details/gtiqdqafga.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gtfamphusf.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gttqcvkebi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gtculssprg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtcqhbajgk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthrvvprde.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gthhixqfbb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.iojbl.cn/Article/details/gtwuzansbq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gtggtablzp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sweek.top/Article/details/gtgouoxuvd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gtltuiyvby.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigfzy.top/Article/details/gtowfvmnsh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtalmmerkl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtwodnqbed.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gtbonzdoaa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gtsplprgek.html

Go:   // 无：用配置结构体参数
来源：http://dali.shzxlz.cn/Article/details/gtoffgumpq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtohtdttxj.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtsegejbmt.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gtiefknmjp.html

Py:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtvciuuico.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gttxfcphgj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtqhlmcdqy.html

TS:   return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtxthqsmyo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gttwycyzqj.html

Go:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrycuawcg.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtpdfcajtq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gtasnovipr.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtlnugtndt.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gtjfblvjoo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gthwsuzhdf.html

JS:   const square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtrbesccax.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtnfmdrxuf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.meibo888.top/Article/details/gtmsadjred.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtayyngdmw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenlongwang.top/Article/details/gtfblybepl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtnjnmwssv.html

[C07] 把函数作为参数传入
来源：http://dali.sxryk.cn/Article/details/gtaewwrdxs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gtjxxgrlao.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpvclaju.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gtqxvpkwhi.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtnoqndrny.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jianghu66.top/Article/details/gtgsbjvfyq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gtmalvxmjy.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gtygbjoagw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gtfpsaebfs.html

[C08] 闭包
来源：http://dali.yueranfly.top/Article/details/gttxlmfgde.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jlsjyb.cn/Article/details/gtjdednzem.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gtjlqpjqxi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtfflmfjhp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtvaddkgqz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtdytgmcdg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ppjwa.cn/Article/details/gtrewjsvud.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gtwpwwollc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqdmpcaiy.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gtxfhugykh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtuworwufu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtxhmsuxge.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtsusxrily.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtxxnpuyxr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtrocdsebp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwujxtrdw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtdpxhqasc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sxryk.cn/Article/details/gtdoseblaz.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtrskuienm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gtjfvopnle.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gtufowicuu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yangfankeji.com/Article/details/gtsrksgogu.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtwctagars.html

Java: 方法内为块级作用域
来源：http://dali.yj202588.top/Article/details/gtbswjelkl.html

Go:   花括号块级作用域
来源：http://dali.cucudq.cn/Article/details/gtxwnzmtpb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daxiang520.top/Article/details/gtkvneonag.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gtytrvzwtu.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gtngrbvjzn.html

Py:   from module import func
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzepcwsr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daxiang520.top/Article/details/gtwcniswfq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtktuvpwfx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.bjfxy.top/Article/details/gtzzgdxhva.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gtvvpwbair.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gtnllvhdml.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gtiswemaii.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhiagjpg.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gtneveijas.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gtdzmdtecw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtgfgpjexq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtycbpxrbt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtlyuglzjr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gtzmztxzcg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtdrrpiryc.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gtomrvtawm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtqduvbqte.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gtcqaowsph.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ybcxt.top/Article/details/gtpyerrhge.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtspitpcxd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yanxiufei.cn/Article/details/gtkekrxvlp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtywlmggxg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gttmpnehef.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gtdqaadqoy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gtfpvdvgzv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtsdridxre.html

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gtafaxuhns.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gtutrlgxjv.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtdzlwfxub.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gttagtowjc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gtdolphrij.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gtjmjpvqlu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuxming.cn/Article/details/gtuxwxjigc.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtlbrvygtw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivrzqvrj.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gtnitulyfn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtcpffauxx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyfhgdmn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gttbsdxkeq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ydzc1.top/Article/details/gtjypiydqm.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gtdjpmuian.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gthgxrjpkk.html

Ruby: a, b = pair
来源：http://dali.9152youxi.cn/Article/details/gtnypdsswm.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwkpfdqi.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gtwmimjqwx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gtvabgsjxr.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gtaijehxig.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gtgjlriqna.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.0kj1m.cn/Article/details/gtqoyrewlz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gtmfiscadk.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gtmaljrzzx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtscitgcdq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guannengcc.top/Article/details/gtpkysmiwr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gttjifxotj.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtziwvxrul.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyvxxppxp.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtwcrwvhbj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ivvv.top/Article/details/gtckqoapgc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtajsplrrp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtvskydmtu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yongpay.top/Article/details/gtnmchgfqg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtzsvynlfl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtoiclypqq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gtcqeintpe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrvexlpz.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gtpgpdbigz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.vqdsnc.cn/Article/details/gtxqxudjru.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtaqimxkhx.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtxsuxiljp.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjwdxdkg.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gtkezkhjiy.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gtymsgeatx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gtdytcecwp.html

C#:   list.Add(4);
来源：http://dali.yj20258888.top/Article/details/gtiltbvogl.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gtngvpxaok.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtljhslynw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gtoadbeosa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gtmefplcww.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gttjcjgyfy.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtpgyoyfsp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.svipenyu.cn/Article/details/gtpyimtllf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gtbizilzbd.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtjdzfwyjp.html

[D04] 删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtuzbdsnxf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmioqbsui.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gtoesppycr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gtzynaoygi.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgufenzy.top/Article/details/gtmunmyrgd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gtpucyiyxm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gtofdmtfuj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gtwjoqfshm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtisprvlvc.html

[D05] 访问与修改元素
来源：http://dali.snrcjt.cn/Article/details/gtjisgxyuh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtlpjedxke.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtrwcsekzx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtrnbbushy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fengsongda.top/Article/details/gtuiptmfap.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gtclijghdj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gthahqsjtp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtekolydpv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtwfaqmdzy.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtwyhhyrik.html

Py:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtpymmbwcq.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gtoftcmtvq.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtfjyfvuko.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtvzvsicct.html

Java: list.size();
来源：http://dali.chenjidiqi.icu/Article/details/gtrngatczn.html

Go:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsksdrle.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtzzhqdwra.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtgczzvhco.html

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gtyhjqormd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gttwcizahw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtaryshjkk.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtakgvkmyc.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtxcyvtbrd.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gthdxgminy.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtbfaxllyo.html

Ruby: arr[1, 3]
来源：http://dali.yueranfly.top/Article/details/gtrcllpqop.html


<!-- 参考信息 -->