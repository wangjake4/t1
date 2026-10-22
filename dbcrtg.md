代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuanzx.com/Article/details/gtlecqyezc.html

JS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtwizakajm.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtjugbksui.html

Java: while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsbrzwyto.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj202588.top/Article/details/gthzohlfia.html

Ruby: while i < 10; i += 1; end
来源：http://dali.iojbl.cn/Article/details/gtlfspbxqm.html

C#:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtexigmxhv.html

[B08] do-while（至少执行一次）
来源：http://dali.pengpengdd.cyou/Article/details/gtudbdeotr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxinkj.top/Article/details/gthdrtgewf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jianghu66.top/Article/details/gtzwucvgzt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtnrzfhoym.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtazohbuuh.html

Java: do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gttfgycscq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnqzz.top/Article/details/gtynolkzme.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gtnmimxhtk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gteskpxvmc.html

[B09] break 与 continue
来源：http://dali.yj20258.top/Article/details/gtlmcyetrt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hywenlv.cn/Article/details/gtzifpzmro.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtnyjlzbbp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtdgxxhlyo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtzvlmaizh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtakaotzpk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shzxlz.cn/Article/details/gtodbotbhe.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.feifeiyinyue.top/Article/details/gtgfbbmfbu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtpntfnujl.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gtdgjupksj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxinkj.top/Article/details/gtdbhrirgr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jiagoushi.top/Article/details/gttuuifhtm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtfarkduzt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gtzvlrrgnt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gtjcpxfqgq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuanzx.com/Article/details/gtfyriqebi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.feifeiyinyue.top/Article/details/gtrrzmwnei.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.9152youxi.cn/Article/details/gtddkqlhjh.html

[B11] 生成数字序列 / 区间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdzzyxwd.html

Py:   list(range(0, 10, 2))
来源：http://dali.gotoacloud.top/Article/details/gtqqouiawy.html

PHP:  range(0, 10, 2);
来源：http://dali.smart0.xyz/Article/details/gtzhlhgrnr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtveffpziv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtbkttzjxh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gtwjeuahnb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.svipenyu.cn/Article/details/gtndcxpmnz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxinkj.top/Article/details/gthrwzgfqi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jlsjyb.cn/Article/details/gtxgwgocys.html

[B12] 跳出多层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdywioyi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigufen.top/Article/details/gttasgwhoq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gotoacloud.top/Article/details/gtgwtxthzq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtarcodhej.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtbrdcwbeb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtuqjksjap.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhengqikj.top/Article/details/gtftahgyal.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ppjwa.cn/Article/details/gtxtfzytxy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dashuyun.cn/Article/details/gthjrjqacn.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gtnviohblr.html

Py:   isinstance(x, (int, float))
来源：http://dali.yangfankeji.com/Article/details/gtcsojdamn.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gtutqyziub.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtltgqdthy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtmbgxxmih.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gtrpdvnzsw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gttuagseer.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tianlin.xyz/Article/details/gtnccljmhn.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gtoepngnwa.html

[B14] 判断值是否在集合内
来源：http://dali.gaohongyu789.top/Article/details/gtaxjabfis.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gogol.net.cn/Article/details/gttfiojgny.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pengpengdd.cyou/Article/details/gtovxijnvr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtzvtyuhlx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtvqjfhhek.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258888.top/Article/details/gtturxppmy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gotoacloud.top/Article/details/gtvzoaifjv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtdgydjtms.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtdbajhkiy.html

[B15] 布尔运算与取反
来源：http://dali.gogol.net.cn/Article/details/gtfvxlzhfa.html

Py:   a and b or not c
来源：http://dali.fengsongda.top/Article/details/gtlpkupxxu.html

PHP:  $a && $b || !$c
来源：http://dali.xinyue.icu/Article/details/gtijxyludu.html

JS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtdptqwssl.html

TS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtdsmszpkn.html

Java: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtswdmfyqz.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtysarunkq.html

Ruby: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtbobgyusn.html

C#:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtscsumsva.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aizwys.cn/Article/details/gtqwmdqpkq.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gtlzclezms.html

PHP:  if (!$data) { return; }
来源：http://dali.dianchejie.cn/Article/details/gthtmoalvm.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakknqomq.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gthvmccglf.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtmxlrfoqa.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gtanpuivww.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gtwuksgrjo.html

C#:   if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtcvlwahsy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmgahjauy.html

C. 函数与作用域
来源：http://dali.daria6918.cn/Article/details/gtxtujaiou.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtkzrvplta.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtgbeqqkou.html

Py:   def add(a, b): return a + b
来源：http://dali.cheryme.top/Article/details/gtwoalhoga.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtxirvtrab.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtojaerfue.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtdwuvuhqv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtbacxfxqd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zycfv.cn/Article/details/gtzafsgczo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtncflhgte.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtrkppjccn.html

[C02] 默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtrtzlkywy.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtiqbwnxuz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gtszbmixvc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtjhfoocpx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtxicccokd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.feifeiyinyue.top/Article/details/gtqmlkxxif.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.meibo888.top/Article/details/gtbkokumwb.html

Ruby: def greet(name = "World") = name
来源：http://dali.dashuyun.cn/Article/details/gtuunpspvm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gtvqdhjgdo.html

[C03] 可变参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcymeexqd.html

Py:   def total(*args): return sum(args)
来源：http://dali.tian-w.cn/Article/details/gtmdgqqnwb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqxdxmqwp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtsgmgocwe.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtbdypheeu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dianchejie.cn/Article/details/gtiihsimzd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gtzctoehnz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258.top/Article/details/gtbotdgwwy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhoulong.xyz/Article/details/gtzfyaclph.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gtewxmpqly.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtnvpdcsxz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gtowwwdupn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnfiymwab.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.smart0.xyz/Article/details/gtvwszbsai.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gtltamuzun.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gtfsueswpe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtcnezpwhg.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtkwegvncq.html

[C05] 返回多个值
来源：http://dali.daxiang520.top/Article/details/gtwtcumlbv.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gthvrqjtzc.html

PHP:  return [$a, $b];
来源：http://dali.jyoumei.cn/Article/details/gtonnmkswt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtbhqjjluw.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtiplnybxd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomgysdjr.html

Go:   return a, b
来源：http://dali.mhx1999.top/Article/details/gtoztkiazb.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gtsnienlia.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gtpzktffdy.html

[C06] 匿名函数 / lambda
来源：http://dali.guannengcc.top/Article/details/gtmahhgwip.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gtysjdcotm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtisqrbsjx.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtaexrpyfy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtfqhdzrli.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gtvohcateb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtzmtnlghk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtgrgzhtju.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtequomvit.html

[C07] 把函数作为参数传入
来源：http://dali.guowangkeji.top/Article/details/gtagclxwvc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.haohaochexian.top/Article/details/gtvorzoeuj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gthfmcgrsz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gtuhklnacj.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpnykbqh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gtdsqmhgiw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cucudq.cn/Article/details/gtscpivxwu.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gtxblcrcpr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanaqufwm.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gttceogmvd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sweek.top/Article/details/gtgdcoznxf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xziqi.cn/Article/details/gtohdghgyt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtrduguihr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtgkdxzhri.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtrrdfivaj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hysaishi.cn/Article/details/gtgkdgkmhp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gthomokbha.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpiduzxth.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gtabskfejo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtjxjsbzyj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdsxxrfno.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtxobkzweh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gtwosgynki.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gtxgfjfrhq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtskorafbw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtfeyjoqqz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtmzcbqqct.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtajecqzby.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtqiruvgqq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gteaqmrdwg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gtmnofjfpu.html

TS:   同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtqqjxsgtm.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gtpfrgjnlf.html

Go:   花括号块级作用域
来源：http://dali.hysaishi.cn/Article/details/gttkzpgiyg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnutwlsj.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtfartvwsd.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gtpatdnyzh.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gtjoaqgipt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuxming.cn/Article/details/gtreambjus.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtljhqcndu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtpwuaskyz.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gtkqcapbxq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gtekirlsfw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gtxqlvzdci.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gtbxjyxxdi.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gtymeymqeh.html

Py:   (lambda: print("run"))()
来源：http://dali.jiagoushi.top/Article/details/gtgdvsggyc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gtfaowpvmf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gthzhwmqpg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmqafvut.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gtbvsvjqkb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtwtinbzwg.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtejboidsj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtsrxxwatp.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gtcrliuxvs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtfoovhbty.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gttmwbanhn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtskfjatoi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtmgqwdlcc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtrcchrkwa.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gtacxijyjh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gtuopxoina.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nwbrower.top/Article/details/gtslftblya.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gtjrhtqyzq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gtufzkvupx.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtrdmuthvz.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtonfkvnys.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gtowiuivxx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258.top/Article/details/gtqhmbnhsv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gtqgltwgad.html

Ruby: # 无泛型
来源：http://dali.hammf.cn/Article/details/gtziegkvpq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gtnwhcxtrt.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gtonkagsho.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gtmvljhwpu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtftkmtwdp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtxcbhdihv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwxhyiewg.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gttrvemgpo.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gtfwemuwna.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbpugyfy.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gttcbvtwfg.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gtpcxmbilx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtwonrwhsr.html

PHP:  // 无重载
来源：http://dali.iojbl.cn/Article/details/gtxtbnqyjb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtcijsfqhf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gtqaitfvtw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gtgxegtzup.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gtgkmtuvjn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtklzlayfo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hammf.cn/Article/details/gtwzonelta.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpfpgxswv.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gtccjqowov.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttjbyigbr.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznlndexa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtetoacrtx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jianghu66.top/Article/details/gtpipcfbms.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gttxswychf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gtkcywhxdg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gtmiuijpau.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtnlqejfoe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtdbftptag.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtwlqpnvjd.html

[D02] 追加元素到末尾
来源：http://dali.jinqigfzy.top/Article/details/gtkjstkfar.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gtmvqdpzfc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjammywpz.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtxosoqrzb.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtwenocgxd.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtpssdjgyq.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngtgbfax.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gtglfamsuu.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gtvytsisrk.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gtfiftxjyi.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gticvmmwpr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cheryme.top/Article/details/gtazikwgtg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ivvv.top/Article/details/gtxokgdvay.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtsyuhteid.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtjrchxuxr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalpwuhtq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tanke756.top/Article/details/gtlzeehtnt.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtehqglpho.html

[D04] 删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxjxvjsy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gtimhsbnye.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gtbssbbvus.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dianchejie.cn/Article/details/gtqqmkjypy.html

TS:   arr.splice(0, 1);
来源：http://dali.tian-w.cn/Article/details/gthbvxtolb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gteypvauue.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gtewkouhop.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwwmctwg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtwexcuxhm.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtiutnfhll.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtlnfgxqat.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtvkyodrcl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtwgojvvcq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gtzazdxrcw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuiivbby.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtuxxiynwh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gthqplifiq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtbnnywypa.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtdjshpjaf.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtqfsoxlja.html

PHP:  count($arr);
来源：http://dali.hnqzz.top/Article/details/gtbzajsqrm.html

JS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtloiimybh.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhqrdkhm.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtnfiwirhm.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtkmyqadjp.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gtvaoeonol.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gtpuizbvel.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gtbhvogrsr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtthtsjrfg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gtzpfkengp.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gthhjmrrcn.html

TS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtdsfujnui.html

Java: list.subList(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtgxdlzrkz.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gtgahlitrv.html

Ruby: arr[1, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtprhwzzwo.html


<!-- 参考信息 -->