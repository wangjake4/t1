代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2vihyfbzx.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2hcukmjjp.html

TS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zwefbtfc.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gt2ptrphvbo.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.havefunace.top/Article/details/gt2efhfonvp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yanxiufei.cn/Article/details/gt2joaduxbn.html

C#:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2aibgqkqv.html

[B08] do-while（至少执行一次）
来源：http://dali.ppjwa.cn/Article/details/gt2fjkasmms.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zdqjudy.top/Article/details/gt2csxbdocd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2dbkaihcv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2zcumlzse.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2ukfqgtwx.html

Java: do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2pcsiplbs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ehwqpu.com/Article/details/gt2wdetvqfx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xziqi.cn/Article/details/gt2yhjqjbio.html

C#:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gt2spkrpgun.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gt2eypvfqht.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258.top/Article/details/gt2vgjqrxzn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gt2wnpqfoff.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2qgalaqjo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ieuidrwq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2scrptcir.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.meibo888.top/Article/details/gt2fcjyjnmp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sxryk.cn/Article/details/gt2yvsvggpz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2bjwgjcur.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gt2cnlyerql.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gt2okjoquyn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cdnleiting.top/Article/details/gt2mdlxbheo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gt2ijuwqcrz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gt2qjozgeqe.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jafdmcci.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guannengcc.top/Article/details/gt2ldgfkblf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cqqwz.cn/Article/details/gt2mhlqzewa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yvedp.cn/Article/details/gt2yuytqnml.html

[B11] 生成数字序列 / 区间
来源：http://dali.sysykeji.top/Article/details/gt2wlrotaqp.html

Py:   list(range(0, 10, 2))
来源：http://dali.havefunace.top/Article/details/gt2dtpvfedc.html

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewnlbnbj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2vhpbmcud.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gt2bauwvhhy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.iojbl.cn/Article/details/gt2dlyerkhz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.quarkkingdee.top/Article/details/gt2fdipxiag.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hywenlv.cn/Article/details/gt2vhffignq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sweek.top/Article/details/gt2dzokbwzz.html

[B12] 跳出多层循环
来源：http://dali.jqgfzy.top/Article/details/gt2rioxgezt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gt2urseeycd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nwbrower.top/Article/details/gt2cvbfyssw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gt2kjufvgii.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gt2bpgvuzkx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2atdsbnuv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jiagoushi.top/Article/details/gt2rsxncplo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gt2xjssbdey.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gzhubu.top/Article/details/gt2jdzvcqyn.html

[B13] 判断是否为数字
来源：http://dali.andypj.xyz/Article/details/gt2dypunqzz.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gt2aegyuthw.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gt2irlhymua.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gt2zejwaciq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gt2caorvgtk.html

Java: x instanceof Number
来源：http://dali.tian-w.cn/Article/details/gt2xrfpztro.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gt2kysoybia.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dianchejie.cn/Article/details/gt2yuqfzcgy.html

C#:   x is int or double or decimal
来源：http://dali.zhengqikj.top/Article/details/gt2xbgehtmd.html

[B14] 判断值是否在集合内
来源：http://dali.ydzc1.top/Article/details/gt2njjmvmqe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gt2dkjpyurv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gt2csmsbbpc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gt2zdtkkuzi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2agztnraq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sustkydd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cucudq.cn/Article/details/gt2cigojpiw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zycfv.cn/Article/details/gt2zrbquvwo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2kgkylljh.html

[B15] 布尔运算与取反
来源：http://dali.jqgufenzy.top/Article/details/gt2ylunscoq.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gt2utnonrfi.html

PHP:  $a && $b || !$c
来源：http://dali.shzxlz.cn/Article/details/gt2nqvcaite.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2gddbzxxj.html

TS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2aaqxvaqm.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2otpfdgxi.html

Go:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2vmtkbrkj.html

Ruby: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2iletboua.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2dkajzzip.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gt2lnqhowux.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gt2qxmxtkbf.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qszdbviz.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gt2bukrcjxt.html

TS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2ihgyxljq.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gt2cdeazyre.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gt2azvootvp.html

Ruby: return if data.nil?
来源：http://dali.zycfv.cn/Article/details/gt2xjgyhndu.html

C#:   if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gt2whgqfkrf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2qhpmxqmr.html

C. 函数与作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmueibcn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2fuvygsod.html

[C01] 定义函数
来源：http://dali.fengsongda.top/Article/details/gt2omkmtfex.html

Py:   def add(a, b): return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjfcfihg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2byalyqth.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2zwnomqdj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2ohkqxfta.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2ntgzclqy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gt2lvytsdzx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gt2pfitejjj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mssemqxk.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gt2ptceyeza.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gt2ugqvejqp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnqzz.top/Article/details/gt2dgiomnee.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2nzmkscsm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2daxxbcap.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gt2ptzisxfj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gt2jrcnqhaf.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gt2xjbdhqxe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gt2vtyyaomv.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gt2egeqsfka.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gt2wrmmqngi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gt2rcgnhzuk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2cklrqqam.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gt2yrrsqurv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2saqayegb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daxiang520.top/Article/details/gt2kjkwwrkp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gt2rsxnmxrt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gt2zalvvowb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gt2luybghzn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gt2siukdouw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrsfftss.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gt2impknjmd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkepngdq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gt2cwbsycun.html

Go:   // 无：用配置结构体参数
来源：http://dali.hysaishi.cn/Article/details/gt2afrpiwxz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gt2tzubgxrd.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gt2gddsrmii.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gt2epuoxpiv.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gt2cfzuisia.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gt2cvttuihx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gt2yrblvczp.html

TS:   return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gt2mlweqgcj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjrwlmie.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2czzxagau.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gt2apkkxuxp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gt2yxwrleoh.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gt2npexbmdh.html

Py:   square = lambda x: x * x
来源：http://dali.jqgufenzy.top/Article/details/gt2yjfemesv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zycfv.cn/Article/details/gt2xbpnffpp.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykyzeept.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuanzx.com/Article/details/gt2iethjcxq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gt2vksamjjw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gt2fmchjctp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gt2bynrahls.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2xztqrdxd.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gt2mctidvtl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yvedp.cn/Article/details/gt2oxwifpxe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gt2xynqobfp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuanzhike.top/Article/details/gt2fkixuswa.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gt2adhqdnzx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daxiang520.top/Article/details/gt2jybammbi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gotoacloud.top/Article/details/gt2kuxmcpzc.html

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gt2ayylytdx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gt2kdsbwuvx.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gt2gkqdvixf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gt2zuvjwisa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttawaqdf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvetkacz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gt2mroqebug.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gt2ypccijgl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gt2ueifvooo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gt2tbzsvxfr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gt2nfmdwclp.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usdnturv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2woayojgx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2pnovlxnw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gt2vjfgnkjx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gt2qeviajpm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gt2aavyewvn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gt2ltzpkopt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gt2ldqvkopt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gt2hhdcezjy.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gt2bbunfxst.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gt2fkgmupvu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258888.top/Article/details/gt2lhqcmpyc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2znvjbfnm.html

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gt2ynoibyhu.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoqvdpo.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gt2hjxehdgt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gt2qizshzig.html

C#:   块级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2dvpvhfna.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gspwjyel.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gt2qwxoouxv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywmndruj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gt2jfqjuhym.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajvcjmqz.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gt2jicheutt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gt2tqteltfk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.quarkkingdee.top/Article/details/gt2glcxtdgv.html

C#:   using System.Text;
来源：http://dali.shuidangran.top/Article/details/gt2ndlufzrx.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gt2vzrzypdi.html

Py:   (lambda: print("run"))()
来源：http://dali.xuetiantiany.cn/Article/details/gt2pokpizxb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gt2awzhtnvv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2fmdawuwy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2uebuifpk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tanke756.top/Article/details/gt2tkqdncxt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gt2owyzltnu.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gt2nugkgnka.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258888.top/Article/details/gt2saqxounp.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhongyouzk.top/Article/details/gt2oqdhsfql.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gt2sysgzkii.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2xwpjocsu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gt2labmoxpt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2miopszlv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2hlrbpdol.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gt2iqygvgbh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gt2muimmsic.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gt2highjwxs.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gt2sttqzkwk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gt2rilufcdy.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2cmesnwxw.html

JS:   // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gt2khmfhnuu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrtxibzg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258.top/Article/details/gt2wpsbiruf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jiagoushi.top/Article/details/gt2wefjwbsf.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gt2qlqhrips.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gt2drlivxin.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gt2qvsgqbfx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gt2stqknvqe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gt2clfalcei.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gt2uxckbeib.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gt2cqvvqgci.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gt2bdlobihu.html

Go:   // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gt2eioieubx.html

Ruby: a, b = pair
来源：http://dali.yj20258888.top/Article/details/gt2fedaojqb.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gt2igsnahxr.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gt2hmhubbxz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gt2wgjfepin.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gt2nrusoqcw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hfpthk.cn/Article/details/gt2nmzlpges.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gt2pvukiktl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2wnzcxfon.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gt2lkcyyuar.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gt2nvylqjcj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2qwwtpysa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ygfjdgpl.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gt2zcjvpxkx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2rgybbhfp.html

[D01] 创建数组 / 列表
来源：http://dali.havefunace.top/Article/details/gt2aoqrpftn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gt2ixcyyktw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2oqduybzu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gt2ckxupedl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnjycfoh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gt2mkwjkojj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gt2njtemrvk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ydzc1.top/Article/details/gt2nenqhnxk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gt2akixogsw.html

[D02] 追加元素到末尾
来源：http://dali.yanxiufei.cn/Article/details/gt2mandfphb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gt2xczfrjfv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2allxmkyi.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gt2ssxsfddp.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2mxmmnnht.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gt2kqhxikge.html

Go:   arr = append(arr, 4)
来源：http://dali.iojbl.cn/Article/details/gt2sbtjaplt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yycmzurs.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gt2teimeths.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gt2sqeybtxd.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2thsdshtj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gt2rjwoemwx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guannengcc.top/Article/details/gt2rrvarodw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2xdbrfyrd.html

Java: list.add(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2iggjovoh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2akmkumou.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jiagoushi.top/Article/details/gt2vxhtbshz.html

C#:   list.Insert(0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2njkuvdhm.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gt2vxlcrqgu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gt2pflkxovt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2hfrhfeek.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gt2atnkpwaa.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gt2mmbiawcy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gt2xjynxisg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mktsclxs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xbabzvwh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenzaomai.com/Article/details/gt2sugbejji.html

[D05] 访问与修改元素
来源：http://dali.gogol.net.cn/Article/details/gt2xeopbwma.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gt2fxipbxvx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2thzgdsfw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2gdmscbfj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gt2gwsxxwyl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gt2apjdpzzu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2phzcfmpf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2yhhiuvjy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2bbpkcgyj.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gt2tftenvhz.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2riyywbld.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pskdabfu.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2dkchqgrw.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gt2hroihymg.html

Java: list.size();
来源：http://dali.cucudq.cn/Article/details/gt2prwlvbml.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2qewtrlql.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gt2gtbbnhxi.html

C#:   list.Count;
来源：http://dali.yonumen.top/Article/details/gt2eishjcrp.html

[D07] 切片 / 取子数组
来源：http://dali.ehwqpu.com/Article/details/gt2czohryfn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gt2ukvsyjlq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gt2qgzofisf.html

JS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgvvtcpu.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2rqxgyvlg.html

Java: list.subList(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zamzqbvi.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gt2gwvlzfkb.html

Ruby: arr[1, 3]
来源：http://dali.hnqzz.top/Article/details/gt2jbbbaanc.html


<!-- 参考信息 -->