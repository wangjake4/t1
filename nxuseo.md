代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gt2djhdlvks.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.snrcjt.cn/Article/details/gt2etjrelxa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.mhx1999.top/Article/details/gt2loavwixq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dianchejie.cn/Article/details/gt2hsymyzgr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukffiobv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shzxlz.cn/Article/details/gt2omiakolq.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gt2upmasqzj.html

Py:   while i < 10: i += 1
来源：http://dali.snrcjt.cn/Article/details/gt2fochoelr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pyyvyvkk.html

JS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gt2dsiffccd.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gt2ltaltbdf.html

Java: while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gt2dwxyxfzs.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxinkj.top/Article/details/gt2ntpwrhpo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxsblcce.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2gxfyiyzi.html

[B08] do-while（至少执行一次）
来源：http://dali.jianghu66.top/Article/details/gt2gnejarzh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hfpthk.cn/Article/details/gt2iadmrhcm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yangfankeji.com/Article/details/gt2gntcvjxx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2gaegmnne.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2fxxrjjkc.html

Java: do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2yrstzhdy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jianghu66.top/Article/details/gt2mmjhldks.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cdnleiting.top/Article/details/gt2wyglzbbq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gt2qjxpojes.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gt2eaeavkcw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tanke756.top/Article/details/gt2psfjczzh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2kgrkocrk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gt2wbbcuthi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uenjkpmg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gt2yqpzyhyk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2veozuuev.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xylfe.cn/Article/details/gt2oddstbkv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2izmukoav.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gt2okmvgcns.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2paumxwci.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zycfv.cn/Article/details/gt2meakohbn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gt2rbaqrlnq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gt2wzpfains.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.havefunace.top/Article/details/gt2fydqbplq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangdashe.top/Article/details/gt2gqwafcep.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ivvv.top/Article/details/gt2pmxviyqe.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenzaomai.com/Article/details/gt2gxllxtua.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ooolatvi.html

Py:   list(range(0, 10, 2))
来源：http://dali.mhx1999.top/Article/details/gt2qdgdujtm.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgfzy.top/Article/details/gt2ceztqnae.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gt2hebnrxvc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gt2bpxdvkcb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2fexbsdwx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxuanxn.top/Article/details/gt2xitrdnur.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sufxvd.cn/Article/details/gt2rnciqzvj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gt2bmundflf.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjpvitmm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.svipenyu.cn/Article/details/gt2njfoujwr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.c1oappe.top/Article/details/gt2dtaznzvm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2gyoplhyq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2obtvjiym.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gt2iuqhezzz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gt2ztspevob.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gt2aiurlksq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.9152youxi.cn/Article/details/gt2sxkjetck.html

[B13] 判断是否为数字
来源：http://dali.guannengcc.top/Article/details/gt2huwpwtvj.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gt2kqjfjqfv.html

PHP:  is_numeric($x)
来源：http://dali.zhixingplan.top/Article/details/gt2yanhbsuf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shzxlz.cn/Article/details/gt2enorjzle.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gt2sznqctur.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gt2jwbtqlmo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nwbrower.top/Article/details/gt2ehmpueqr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guannengcc.top/Article/details/gt2uwmjqbao.html

C#:   x is int or double or decimal
来源：http://dali.zhengqikj.top/Article/details/gt2vcxnecxr.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gt2lnuyyrjq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gt2uboctyni.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qaoawwra.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2tdhxcskc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2trrcjocb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2mdzgbxob.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nwbrower.top/Article/details/gt2jclpljqy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tian-w.cn/Article/details/gt2jcvevnac.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2nlxebndq.html

[B15] 布尔运算与取反
来源：http://dali.yj202588.top/Article/details/gt2fxbauqro.html

Py:   a and b or not c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vekatiaw.html

PHP:  $a && $b || !$c
来源：http://dali.chenjidiqi.icu/Article/details/gt2npmskhii.html

JS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2cffxktrk.html

TS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2zqljayuy.html

Java: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2uzznryea.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2wabppuow.html

Ruby: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2lmykrdpl.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2qpdhfyqe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgfzy.top/Article/details/gt2wnfzdwll.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gt2gymqpavz.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gt2yzemuigc.html

JS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gt2asywbrtv.html

TS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gt2iqqqhuzb.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzomzay.html

Go:   if data == nil { return }
来源：http://dali.yvedp.cn/Article/details/gt2ofrpgovc.html

Ruby: return if data.nil?
来源：http://dali.yj202588.top/Article/details/gt2wwbwcixf.html

C#:   if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gt2ievlifqy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ukvwppzi.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gt2wipudifl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2wfmchymz.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2onzbdzrz.html

Py:   def add(a, b): return a + b
来源：http://dali.ybcxt.top/Article/details/gt2wyrfkbxv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2iffzxlvn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2ovmkhrgh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2pgydqpxm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2lncfaeef.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigufen.top/Article/details/gt2zperyvnh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.316326.xyz/Article/details/gt2tshxlpwx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2czgdbxqg.html

[C02] 默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkarnpae.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258888.top/Article/details/gt2gvxujgjr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbrokyuq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2rchywzje.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gt2lpbyskct.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gt2vmjpxveg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gt2tusinlzs.html

Ruby: def greet(name = "World") = name
来源：http://dali.cucudq.cn/Article/details/gt2xdlyjmfp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gt2nhpifpsd.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gt2jaytbasn.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gt2mxmyoglf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jlsjyb.cn/Article/details/gt2dxbdqriu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwupwmrx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gt2rclkepor.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenlongwang.top/Article/details/gt2xgmknyvs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cdnleiting.top/Article/details/gt2xwltfzim.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258.top/Article/details/gt2wawssgsn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gt2zekczosu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gt2aoficijf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fzhhl.top/Article/details/gt2rguavblj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.havefunace.top/Article/details/gt2vnmdiiiy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gt2woxpusff.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2mldfjisk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.vqdsnc.cn/Article/details/gt2kulqzmwz.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gt2cnyohyzk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gt2zehekryp.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2xztnjqfb.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gt2gqdcncjd.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjwuhlhe.html

PHP:  return [$a, $b];
来源：http://dali.daxiang520.top/Article/details/gt2mshhpwvu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmnztrmt.html

TS:   return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gt2viprnvws.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggrxfzix.html

Go:   return a, b
来源：http://dali.guannengcc.top/Article/details/gt2ekwazylh.html

Ruby: return a, b
来源：http://dali.ivvv.top/Article/details/gt2dyxrlidx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gt2tosbjyql.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxinkj.top/Article/details/gt2mhrwqebp.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erexokam.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gt2mjnugwrz.html

JS:   const square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2lgczsjae.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2hxsxhrtu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2wcfexoqv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.kuanghao11.cn/Article/details/gt2ttodhzkx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gt2vfkwxyje.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2glkjdxeh.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gt2neaapvsx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gt2ksghnozv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtimttds.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gt2ppicnkxn.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gt2rpmtvwwt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.c1oappe.top/Article/details/gt2aodyfvpn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gt2upzebxpr.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxwvqbhj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gt2gxdzngji.html

[C08] 闭包
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgtlawds.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gt2lgpwgskn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gt2yhgjchzu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2inkyefsl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2qvprwkly.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.kuanghao11.cn/Article/details/gt2pibmiuyo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqiakjth.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gt2spvmrhsi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2djithriq.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gt2hkymkzez.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gt2qvedttxs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gt2xdmhjtqy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gt2zjzhfpey.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atzfkihv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gt2yfiarkme.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkqedtlg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gt2llrmcalq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gt2mxcyfaaz.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gt2vbnmevds.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnxiangtu.top/Article/details/gt2omstjqub.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gt2hsoidhbw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuanzx.com/Article/details/gt2rhabhivy.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2nsrdlhmf.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gt2cgexnlwm.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gt2nsjubgjc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gt2pwaujwks.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2nvegblej.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gt2qwqbzxjx.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gt2evsdzsrl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.c1oappe.top/Article/details/gt2wplxpqwq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gt2znyjlpcb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gt2zigjzjoz.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgfdizoq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gaohongyu789.top/Article/details/gt2kohgwzfq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gaohongyu789.top/Article/details/gt2vvubqnqw.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gt2tdbtkrby.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gt2ekckkioj.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gt2qerlkuhf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gt2xxuptndl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gt2cojddcmy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gt2atebojhn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gt2rimimgop.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gt2iggmcqlk.html

Ruby: -> { puts "run" }.call
来源：http://dali.hywenlv.cn/Article/details/gt2zotjouwj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258.top/Article/details/gt2uetgmahk.html

[C13] 类型声明 / 类型注解
来源：http://dali.yvedp.cn/Article/details/gt2itkcpvde.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gt2kmwugcbl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2nyhqgrge.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gt2yauuszzi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2lexaqrpq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2hpgyrvto.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gt2fwpqfonv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.9152youxi.cn/Article/details/gt2zkzmrvtk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gt2adpnncif.html

[C14] 泛型函数
来源：http://dali.svipenyu.cn/Article/details/gt2amabkuvq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqtlxgsn.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2ebvuucef.html

JS:   // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gt2qcwmgfuk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkcaabmu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gt2xuaxfjvv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljbxsrbe.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cerbxxoj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubqfspoy.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gt2nxgpjsev.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxinkj.top/Article/details/gt2bmruuidq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gt2dbhmzjfd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gt2pkzivxth.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gt2kgjjyavp.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gt2xdwtephh.html

Go:   // 无解构
来源：http://dali.jinqigufen.top/Article/details/gt2jjgrioff.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gt2bofsztsa.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gt2glezfhqr.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gt2jdgcmhzw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxinkj.top/Article/details/gt2buepxyco.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gt2koqtwrrp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gt2lobepxfa.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gt2mtaykjvn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2zomlmbtg.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gt2puyprzpf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gt2hwhwgvie.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daria6918.cn/Article/details/gt2teziqsrm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2mogrmrid.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gt2quuokgsu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2omtkwivb.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gt2tknmkpwc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hammf.cn/Article/details/gt2bsxxvsdi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gt2fvvtyutk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gt2qxijfhlt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gt2hdduqsvy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xylfe.cn/Article/details/gt2sfkalfsp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gt2wowymfia.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gt2mxgmyaxv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gt2hfchizih.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gt2cjfpddrq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gt2hzaxarqe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hywenlv.cn/Article/details/gt2poxlhssl.html

JS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gt2wwgpnjej.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gt2ojedgtqd.html

Java: list.add(4);
来源：http://dali.sysykeji.top/Article/details/gt2xnmabsnc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjfeoxt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gt2teivnbiy.html

C#:   list.Add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2euelyukk.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gt2qwyeqoak.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2xdhapsso.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gt2eafgfpwe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gt2mgerhyaw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2moidqqjk.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2bcepbucr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2xfuxkxfw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.kuanghao11.cn/Article/details/gt2jvwbpnzd.html

C#:   list.Insert(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2qmhuxuln.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gt2kwyhkqms.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gzhubu.top/Article/details/gt2ptyeldqx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gt2jbdhnism.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gt2uxfqnjyh.html

TS:   arr.splice(0, 1);
来源：http://dali.yonumen.top/Article/details/gt2kjbbulyl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gt2rjdbrwmi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gt2vehtjbno.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gt2hagjjnru.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gt2acdnzzzo.html

[D05] 访问与修改元素
来源：http://dali.zhixingplan.top/Article/details/gt2dtxblfkg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwmyussw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2bigoulpm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2zsymzmfq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gt2gxxxknes.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zicrnpzt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2xnvntlgk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2voygyhkv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2ikiobslw.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2fbpvgdjf.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2ewrkolel.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2efpxmdbi.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gt2qfyzzjop.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2nymgruvs.html

Java: list.size();
来源：http://dali.gaohongyu789.top/Article/details/gt2nbxhsrwj.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2qbjnmtxs.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gt2idihebag.html

C#:   list.Count;
来源：http://dali.haohaochexian.top/Article/details/gt2jiovxlcy.html


<!-- 参考信息 -->