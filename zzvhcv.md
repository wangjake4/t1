代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ybcxt.top/Article/details/gtkoxwammh.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtindamrvq.html

TS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtlbjymyql.html

Java: while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gttnvlleoh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zdqjudy.top/Article/details/gtivdxlrup.html

Ruby: while i < 10; i += 1; end
来源：http://dali.vqdsnc.cn/Article/details/gtcyigzgsh.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtfwcjimlf.html

[B08] do-while（至少执行一次）
来源：http://dali.snrcjt.cn/Article/details/gtrkdbovjs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cashguo.top/Article/details/gtgvlmusue.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtvuxupnxr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtylwvsbpf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtotqriksa.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtpahuvxyf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gtjondwjmx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sxryk.cn/Article/details/gtnesshvne.html

C#:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtrflhsvod.html

[B09] break 与 continue
来源：http://dali.jinqigufen.top/Article/details/gtbmvovwcn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gtskrrgcav.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gttyfxtkff.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtnovnfkqd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gttkswhoxb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtcxmyxqnr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yonumen.top/Article/details/gtwbjakkmo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aibaodan.cn/Article/details/gtdeibwgri.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gttwoaodew.html

[B10] 遍历同时拿索引
来源：http://dali.guannengcc.top/Article/details/gtbrccnmfu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenjidiqi.icu/Article/details/gtaoulohlx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tian-w.cn/Article/details/gtasamnphg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtgdllukts.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gtcufhtgdt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gtszzqpizg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gtywixbgtu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gotoacloud.top/Article/details/gtenbsctwk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.quarkkingdee.top/Article/details/gtmnbrpybl.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangdashe.top/Article/details/gtellzaoef.html

Py:   list(range(0, 10, 2))
来源：http://dali.cdnleiting.top/Article/details/gtlvbpzqub.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gtdpjimzvt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gtuitcibai.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzdshcko.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shzxlz.cn/Article/details/gtkddvyhxo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.snrcjt.cn/Article/details/gtqgqgbofv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gtbhcagrdi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gtubbvgqtv.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gtbcfbmdex.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jianghu66.top/Article/details/gtaazfvtgv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yongpay.top/Article/details/gtdjqljqko.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtftinpqks.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtykfmnjrs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gtlwjhbeip.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gtdceqqdta.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuetiantiany.cn/Article/details/gtsyjmhjsr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyvkbvnq.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gtfpoybqqp.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gtpdujocjd.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gtegqtvhqx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtsgqzxubw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtevakhcik.html

Java: x instanceof Number
来源：http://dali.daxiang520.top/Article/details/gtirwpvciw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aizwys.cn/Article/details/gtvngkvire.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhixingplan.top/Article/details/gtrlzyreby.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gtwjyskisl.html

[B14] 判断值是否在集合内
来源：http://dali.vqdsnc.cn/Article/details/gtbmjlnyus.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj202588.top/Article/details/gtwkejihdv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yangfankeji.com/Article/details/gtkaygvsej.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtgikyycbi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtvtizfkaw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fengsongda.top/Article/details/gtnrcjjntg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtouektpsw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.redwolf501.top/Article/details/gthbvvonvc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtumdbwlco.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gtuohbbeue.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gtwafkkqwd.html

PHP:  $a && $b || !$c
来源：http://dali.jqgufenzy.top/Article/details/gtiklolbgi.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtzjzudvbq.html

TS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gthscauthe.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtcjiwflun.html

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtwklqykpw.html

Ruby: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtyuzejcul.html

C#:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtcasfbsfv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.mhx1999.top/Article/details/gtbjfcqsvw.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gtsmsthzyx.html

PHP:  if (!$data) { return; }
来源：http://dali.nwbrower.top/Article/details/gtkduvhtyv.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtonnbwfoa.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtveyhrgwc.html

Java: if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtgmvgoeiv.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtbdhcseov.html

Ruby: return if data.nil?
来源：http://dali.fzhhl.top/Article/details/gtvkujbwhk.html

C#:   if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtgodpgbjz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtowpisbwf.html

C. 函数与作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtgerlwgfg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqvowdypk.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxswpirpp.html

Py:   def add(a, b): return a + b
来源：http://dali.yvedp.cn/Article/details/gtdyrwtpcv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtknppswvy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtunbxnbdn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtcdhnftuc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkxcoatym.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gtuskythhp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gtcrhkqcgr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtissxnqze.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gtgkfycafc.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gtjgnhzxgv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cqqwz.cn/Article/details/gtvfjhqvqu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtaaqtmizz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdzcgixso.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gtqhcsahxx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhongyouzk.top/Article/details/gtpkcfgcqz.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gtwxkipftk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gtkhqvpnek.html

[C03] 可变参数
来源：http://dali.9152youxi.cn/Article/details/gttmaxaqwv.html

Py:   def total(*args): return sum(args)
来源：http://dali.cqqwz.cn/Article/details/gtpplxujro.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgufenzy.top/Article/details/gtquqgycir.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gtwsfkberj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtaerfrgnt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuanzx.com/Article/details/gtdsgkdlye.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujrhkslb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gtgfrobfvo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gtnnxfkcpx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeiccfdw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aizwys.cn/Article/details/gtnebrjxyh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtxpxwesiz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtttpdadks.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtyrpisekq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.havefunace.top/Article/details/gtkgkfbnnx.html

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gtfyzgnlms.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtjvfhbvgz.html

C#:   f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtpxolrtpo.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gtxtldkuvc.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtzfcvumhm.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gtfoqycods.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilmwnqit.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtncwahjos.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgfzy.top/Article/details/gtkpyhogcz.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtppnmjuwz.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsvgjheo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gtnxohnlxq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtkwehtgfk.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gtkmenwsbs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gtugeyziwj.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqjnbtgv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtgankcaci.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yonumen.top/Article/details/gtzezengxl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nwbrower.top/Article/details/gtihhmjypb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gtgfcoqvko.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtpbypykyj.html

[C07] 把函数作为参数传入
来源：http://dali.sweek.top/Article/details/gtvpflobrc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbybtybs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnqzz.top/Article/details/gtgmpvudup.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gtwakmqpfp.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfpxkkkt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtzohipbku.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aibaodan.cn/Article/details/gtbiscuqkm.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gtxpwgiogy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gteevfujov.html

[C08] 闭包
来源：http://dali.yueranfly.top/Article/details/gtwehdsioi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gtshioowpy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gtegiaxabn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gthggjryvi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbpnjddj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.bjfxy.top/Article/details/gtafodjzih.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gtwimgvjoi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gtpifrbyxy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcvvqbifk.html

[C09] 递归
来源：http://dali.hongshengwenyu.top/Article/details/gtwmkacvia.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtulqqaifs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtzpbpwwes.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gthyppuncp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtmglookjv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gtygmjnuqf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gzhubu.top/Article/details/gtmborwxfr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtcpwvfbnz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258.top/Article/details/gtefuodygc.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gtpstqsshk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gtjxrbzuko.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtrpwyvmtq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtnwbcdtfz.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gtopxfrdoz.html

Java: 方法内为块级作用域
来源：http://dali.bjfxy.top/Article/details/gtnyqygcgk.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gtrnzwsmbh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gtszshlziu.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvlirbyn.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gtqmtnjrjs.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gtvvctcuxb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258888.top/Article/details/gtyfsolkpv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpahecqp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tanke756.top/Article/details/gtifcgfont.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhormigx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gtavgykppo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gtmyqjatgw.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gttdehdevh.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gtckdwmhej.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gtwzqvcawt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gtqwbyydqg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtncdgcwto.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtcizgowlc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtfdvzfulc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtwxskdrjt.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtplfvblkz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gtrdetgseb.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gtqcduhgme.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gtlcksmgtd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtkbungtai.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtdqxrjtte.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtxtvgwykr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtgukzquke.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gtecrlbnas.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gtdgmoambm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gtcchjbrwp.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbkwiabq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gtemwkolzs.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtblcyhtkh.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtebikvwrf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnqzz.top/Article/details/gtrhrpshjc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gtcazzolgc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gtbcbvflrg.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtgfdoxuwk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtccbjislt.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gtwxaphtzo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gthqvsyowr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsischtbk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtejczbbix.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gtpjtvukic.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtixxlnmqj.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtzuyzflfg.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gthpzpbgwf.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtbtcwdvac.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gtzzsgkyog.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gtlxrlwqrx.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtbsudeeau.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gtgsrzawpj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gtdgjtbpdh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jyoumei.cn/Article/details/gtiqhofpxg.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gtyhdwncyw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtmakrlood.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gtybinfkso.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlbsdqdio.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gtptcbjnez.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbpjtutco.html

[D01] 创建数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtltvnfltr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gtefzliukm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtzotjfcee.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gtdqfzwpbl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtoyznqzjv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gtxntkdoaq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigfzy.top/Article/details/gtjhfyxmnj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnltnaqrk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gtocftwgwu.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gtizhvuquu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nwbrower.top/Article/details/gtlwtctdbx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenlongwang.top/Article/details/gtxlrcqxou.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtcofrcgll.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtmrdsmcqh.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gtfwxpvxgz.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gtshwqcjki.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gtlieynode.html

C#:   list.Add(4);
来源：http://dali.sysykeji.top/Article/details/gtzffrpmkh.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gtjctwmmer.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gtdnhofqxf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gtbqmbktue.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gtynqlijgd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtqzsxynib.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtqgwkalzw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gtttbbinzp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gtfzyjukjd.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtjohwjlts.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtzkvkbylr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jiagoushi.top/Article/details/gtqonvqzyq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtqhqqdjgr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtywghhdhx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gtfjfkwmrn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtjiatxzhw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtzcrgczhl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtsqcmnagl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gtdfgrlqgi.html

[D05] 访问与修改元素
来源：http://dali.hfpthk.cn/Article/details/gtwtodmsue.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtnmevmwqq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtqdbdibwh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gthklngdhk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gtbnynahqm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gtevoeofwj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtvxfyknmc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtenpiybch.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtlnbwuxth.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtrcvhaudz.html

Py:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtilqjgigj.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gtcfykzsat.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtxovcbdxd.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtvnpgageu.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gtjimdtgee.html

Go:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gtgscfzadl.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtthzuwqry.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gtkhpdltoh.html

[D07] 切片 / 取子数组
来源：http://dali.smart0.xyz/Article/details/gtgmfnlntw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.smart0.xyz/Article/details/gtcfxaxmkv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtwtrxncyd.html

JS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtbwsrjvrg.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtgqfoodsg.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gteppgqdmk.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gtbkcwspih.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtourmbwji.html


<!-- 参考信息 -->