代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj202588.top/Article/details/gt2ppbitzzp.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2cvqtsrob.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2btfouwnp.html

Java: while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hqfaynvr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yvedp.cn/Article/details/gt2osbruuzx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.kuanghao11.cn/Article/details/gt2nyddsbqz.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2berrhlmw.html

[B08] do-while（至少执行一次）
来源：http://dali.c1oappe.top/Article/details/gt2tpmkeqci.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sxryk.cn/Article/details/gt2qpmfqadh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2ppclkdks.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2kyqdoxno.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2iooddhns.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2fgpwshzr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qndiiflv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.iojbl.cn/Article/details/gt2gpyohzrs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2oxulbjzw.html

[B09] break 与 continue
来源：http://dali.c1oappe.top/Article/details/gt2ekyssksd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guowangkeji.top/Article/details/gt2lnwntqiz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gt2thcmfnfu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gt2fthiysyb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdsjlmfq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2ypqgxaeq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gt2wlvblppm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gt2fpxivmcj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktsltaaz.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gt2xlcmwvve.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gt2vbrgmggn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.birdmap.top/Article/details/gt2hqfrghvq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gt2lbqgnqqo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.mhx1999.top/Article/details/gt2ehmvfjcz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aibaodan.cn/Article/details/gt2oudwdppg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqzfisox.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfujownm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xziqi.cn/Article/details/gt2zocekqwd.html

[B11] 生成数字序列 / 区间
来源：http://dali.mhx1999.top/Article/details/gt2mekrdwlj.html

Py:   list(range(0, 10, 2))
来源：http://dali.pengpengdd.cyou/Article/details/gt2whtlmaiw.html

PHP:  range(0, 10, 2);
来源：http://dali.sysykeji.top/Article/details/gt2shnsggui.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gt2jgedfrez.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gt2oeipsovf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jianghu66.top/Article/details/gt2hobxhqcs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rebffpyg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jianghu66.top/Article/details/gt2yqvccgyx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdeqerqs.html

[B12] 跳出多层循环
来源：http://dali.daria6918.cn/Article/details/gt2nuhdyhcf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gt2ztdmtqzt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hammf.cn/Article/details/gt2gymfifhf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbcwiynk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gt2rmirksbq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2nsirzspt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.haohaochexian.top/Article/details/gt2ghczbfjk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivhpbqub.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.c1oappe.top/Article/details/gt2ltxmbudt.html

[B13] 判断是否为数字
来源：http://dali.chenlongwang.top/Article/details/gt2mbnarfka.html

Py:   isinstance(x, (int, float))
来源：http://dali.tian-w.cn/Article/details/gt2xjzusstn.html

PHP:  is_numeric($x)
来源：http://dali.bjfxy.top/Article/details/gt2kujlwlvc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gt2lxlecria.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gt2ryoipuln.html

Java: x instanceof Number
来源：http://dali.nanxinkj.top/Article/details/gt2ygaefkrf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jianghu66.top/Article/details/gt2gyhkimqb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuetiantiany.cn/Article/details/gt2breiyiej.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gt2nzsqxcgx.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gt2hbtmkwjo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gt2pbiepzcp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzzpxqyr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2aiqnhmbx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gt2msaeakxv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2cxppiqqy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ivvv.top/Article/details/gt2xdswcihl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cqqwz.cn/Article/details/gt2yiqokgfl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmtgoerc.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xffltzdq.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gt2xdnneuyb.html

PHP:  $a && $b || !$c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjslvyrq.html

JS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2sxeobjvy.html

TS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2nvtasnbo.html

Java: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2leexejrm.html

Go:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2piqxjvss.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nopmygfm.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2ajljguzx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yueranfly.top/Article/details/gt2gwqicvvb.html

Py:   if not data: return
来源：http://dali.pycfn.com/Article/details/gt2priojzmj.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gt2vrpujlwd.html

JS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gt2hrhjjmci.html

TS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2opfxlyva.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gt2tfprejxu.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gt2xzicyerr.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrmvboi.html

C#:   if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gt2ztpeacxm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2aoltvzhg.html

C. 函数与作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okzazwpq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjvjztrc.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gt2upyuigwa.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2engbadgn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2agtjriir.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2ywvptify.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2qogoerwa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdtwmhys.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.birdmap.top/Article/details/gt2lahnnkvv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ppjwa.cn/Article/details/gt2skehyftx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2tjpqeusd.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gt2wkpfrehg.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gt2ycnrlppx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gt2zwehmxwo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kmbqdtmh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ugmxghyw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2vymdpvpc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.snrcjt.cn/Article/details/gt2sfuaosdi.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gt2vlvtgewy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gt2pduvqnph.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gt2rtudlvqr.html

Py:   def total(*args): return sum(args)
来源：http://dali.jlsjyb.cn/Article/details/gt2ydbczqfs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenzaomai.com/Article/details/gt2aiqcqitm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gt2pnwcqjze.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gt2pdxdhioi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxinkj.top/Article/details/gt2ruqdizph.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gt2sscrwyfw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gt2bnisiqkd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gt2ihkrvqdj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gt2vjdgwwcy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gzhubu.top/Article/details/gt2vjjctsal.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gt2dqplgdsa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gt2bgrrlkaa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuanzx.com/Article/details/gt2gpqoxpfx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gt2vfllwfch.html

Go:   // 无：用配置结构体参数
来源：http://dali.jlsjyb.cn/Article/details/gt2vnjohvvr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjrxlizv.html

C#:   f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2senfnkyr.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gt2xalrwmkl.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2whuyaevx.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gt2yltyjeqr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gt2tbipzwoj.html

TS:   return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gt2upzmhaan.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gt2prxdccml.html

Go:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvtbreyc.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gt2ekuuktlw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gt2ychfknts.html

[C06] 匿名函数 / lambda
来源：http://dali.chenzaomai.com/Article/details/gt2gpxfsvsl.html

Py:   square = lambda x: x * x
来源：http://dali.ybcxt.top/Article/details/gt2lwqruhpp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gt2jyiilpjh.html

JS:   const square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2qlsdkhyl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yongpay.top/Article/details/gt2iumdpzzp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tian-w.cn/Article/details/gt2tklygprn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cdnleiting.top/Article/details/gt2uxgeydtj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqchdzzv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxhvpixc.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigfzy.top/Article/details/gt2hdubdbwj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gt2sovykheu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2yahzwvtf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gt2hmgfdaof.html

TS:   arr.map(String)
来源：http://dali.nanxinkj.top/Article/details/gt2soosgzls.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2sfosvasu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxinkj.top/Article/details/gt2ngkulilw.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gt2gcznabjo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sufxvd.cn/Article/details/gt2lahnjmdm.html

[C08] 闭包
来源：http://dali.yueranfly.top/Article/details/gt2xfwrqbhj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fengsongda.top/Article/details/gt2chcolrjg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gt2abtafthx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2jzfuwxyy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2kdcsxtod.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuetiantiany.cn/Article/details/gt2umtnfuya.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cboxbwke.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yongpay.top/Article/details/gt2pesikplm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2ibdlcebx.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gt2yvljxrrc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2rvedfgkw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fodsxtlo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gt2wuoznwna.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gt2doykqitu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gt2dodeqqkl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tianlin.xyz/Article/details/gt2hsdvregj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gt2zjugmunm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daxiang520.top/Article/details/gt2jylltxup.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gt2xysbgmmq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gt2efipzvtg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gt2emwsrauq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gt2mkbluwcn.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gt2zyhozyaq.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2ecwiiosf.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2kxwmvfur.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gt2pcbbpdop.html

C#:   块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2mjgeilio.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gt2vkysapwo.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gt2btsdjzgo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gt2zxawvixv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gt2wqndfows.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gt2zkpbjmeo.html

Java: import java.util.List;
来源：http://dali.zhixingplan.top/Article/details/gt2wyyorkhp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gt2ciuafdip.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gt2ccpsljea.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gt2gicfgtsw.html

[C12] 立即执行函数 IIFE
来源：http://dali.ehwqpu.com/Article/details/gt2bjodoniy.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258.top/Article/details/gt2eddllkou.html

PHP:  (function () { echo "run"; })();
来源：http://dali.c1oappe.top/Article/details/gt2kohwbrrs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gt2mxzsvkdp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gt2stoxotgt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gt2yvqmbimi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gt2bmbtpzsq.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gt2avihmdfb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lchiqzvh.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gt2ktjzkmdu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.snrcjt.cn/Article/details/gt2tzftparm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2zhllccti.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnxiangtu.top/Article/details/gt2abpqjtkm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2yrsejghc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2eoyhbtkb.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gt2upidcsvr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gt2fqyfgukn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gt2kbkczioc.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gt2uwwvblqx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sidimmvd.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2usegrfyw.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2arxyvxic.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqscyppl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gt2kybrypvy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gt2qeqqxmid.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2vkyteamy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gt2rrqtqnac.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gt2uvztcdny.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangdashe.top/Article/details/gt2jiywvcpd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gt2ufqkkrph.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2zqerxgpt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gt2xymiikwa.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gt2qisvnbhk.html

Go:   // 无解构
来源：http://dali.cashguo.top/Article/details/gt2exyhtqgh.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gt2hxlluawg.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gt2ttewbqof.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gt2yrtuduel.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gt2cibrasyj.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksdbnaxq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gt2offruktx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gt2lvhcquqb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvqtadot.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gt2padfoacm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gt2ktwbnmav.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shuidangran.top/Article/details/gt2udscgdfn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2nasadqfl.html

D. 数组 / 列表 / 集合
来源：http://dali.c1oappe.top/Article/details/gt2jdgqwrzl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2muynbohk.html

[D01] 创建数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gt2ityfcaqn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gt2afbqyldr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jyoumei.cn/Article/details/gt2uulhxmmm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2uojghoqw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gogol.net.cn/Article/details/gt2rvyawymv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gt2dvesaqwa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gt2bqjrfths.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gt2xrslwmau.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhbiqxbm.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gt2josajfot.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gt2vlfjbkup.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2mcsztsny.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2gyjafyly.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gt2rjmvvzdy.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ptiwlgwf.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2nznrulck.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ineuvick.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2mhaorcgb.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gt2dpzsuuuz.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxbsjqqt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gt2lanxndir.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gt2oefcdlmr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2qhdfnyku.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2stxguryk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gt2ofmhyobe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gt2dverqecn.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2jschfiww.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2buplattk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gt2peykfzqp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2nastaekc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gt2cvobghad.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gt2vuugqsfj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gt2sbjwgvfh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gt2mymlbwts.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sysykeji.top/Article/details/gt2yqavbrdd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ydzc1.top/Article/details/gt2rvqnskpv.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gt2bjleevuv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2fuqkfyyg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2edunkliv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2npjbdies.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yvedp.cn/Article/details/gt2joxuztsz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gt2qsfvcqna.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2ywmenlro.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2awyhirda.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gt2quuweuaf.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2txehgbae.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2cwhtecdo.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gt2qzantxwv.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gt2dsjoduqg.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gt2okojpkym.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gt2fkaeadks.html

Go:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2ttvoxnas.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gt2flfegjbc.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gt2odazafon.html

[D07] 切片 / 取子数组
来源：http://dali.gotoacloud.top/Article/details/gt2hntrgahl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gt2ysrryjjj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gt2qtpbnjnc.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2nkzyharg.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2hznhqedq.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2pkqxpvcj.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gt2ucyjmytw.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gt2fayedoaf.html


<!-- 参考信息 -->