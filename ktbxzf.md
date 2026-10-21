代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ydzc1.top/Article/details/gtpwebyhpp.html

[B06] 遍历字典 / 对象
来源：http://dali.feifeiyinyue.top/Article/details/gtepdcwtvf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yongpay.top/Article/details/gtldeeobsa.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yangfankeji.com/Article/details/gttugccenx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gtzlmntjjg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gtvetrlebk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgufenzy.top/Article/details/gtzsjmmoqy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhongyouzk.top/Article/details/gtrsqndwxk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhengqikj.top/Article/details/gtidervshl.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daria6918.cn/Article/details/gtwteezwno.html

[B07] while 循环
来源：http://dali.cucudq.cn/Article/details/gthmqbvptl.html

Py:   while i < 10: i += 1
来源：http://dali.daria6918.cn/Article/details/gtvoebjpex.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ppjwa.cn/Article/details/gtlktkddla.html

JS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtkgqvqbmu.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gthdxlkvkd.html

Java: while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtonislxxc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hongshengwenyu.top/Article/details/gtovrjecvq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fzhhl.top/Article/details/gtarglbbly.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtndymxhjk.html

[B08] do-while（至少执行一次）
来源：http://dali.iojbl.cn/Article/details/gtpgjkwqww.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ydzc1.top/Article/details/gtvaxhkgkq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj202588.top/Article/details/gtrtlrmyzo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtqsojteea.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtnqaokgzd.html

Java: do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtkwztiwzq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtmrrwbmge.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gtstbedvme.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtuenbtjfr.html

[B09] break 与 continue
来源：http://dali.dianchejie.cn/Article/details/gtusisqaeh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.mhx1999.top/Article/details/gtmrcfrrhp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxpmyijt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtewayjyfz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gttfvgpglt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtmqkotjeh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gtmdrqumpo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gtfhhapjfg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtyntowelm.html

[B10] 遍历同时拿索引
来源：http://dali.jlsjyb.cn/Article/details/gtvlfwtbeh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmukkeogn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cdnleiting.top/Article/details/gtpuuegpoa.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gtdhrqopce.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gthoyadpin.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nwbrower.top/Article/details/gtoeclrjbv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevxuamwn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guannengcc.top/Article/details/gtfofwopbm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigufen.top/Article/details/gtvnwimlcb.html

[B11] 生成数字序列 / 区间
来源：http://dali.0kj1m.cn/Article/details/gtcjhyirrc.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gtuonvjbwy.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfrvdhlf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gtgxxtvhsi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtvolspxhw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.havefunace.top/Article/details/gtlieycbtt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnqzz.top/Article/details/gtshvrmpac.html

Ruby: (0...10).step(2).to_a
来源：http://dali.meibo888.top/Article/details/gtfzdjwdus.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zycfv.cn/Article/details/gtsueapruw.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gtqanrpjhu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ivvv.top/Article/details/gtjdcbztlm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yanxiufei.cn/Article/details/gtdwxpwbbg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtechjmmzq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gttijqupns.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtpovjnifi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.0kj1m.cn/Article/details/gtxmbfxhhp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jlsjyb.cn/Article/details/gtqjmitjxh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj202588.top/Article/details/gtblbfqufp.html

[B13] 判断是否为数字
来源：http://dali.shuidangran.top/Article/details/gtfiijihqv.html

Py:   isinstance(x, (int, float))
来源：http://dali.svipenyu.cn/Article/details/gtnaoqloll.html

PHP:  is_numeric($x)
来源：http://dali.yj20258.top/Article/details/gtwayjoolu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsjnpuki.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gtydlpmkdz.html

Java: x instanceof Number
来源：http://dali.pengpengdd.cyou/Article/details/gtqtwszsne.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.9152youxi.cn/Article/details/gthiervbkj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hongshengwenyu.top/Article/details/gtcafnpfyr.html

C#:   x is int or double or decimal
来源：http://dali.yj202588.top/Article/details/gtxpjfhyzp.html

[B14] 判断值是否在集合内
来源：http://dali.ehwqpu.com/Article/details/gtdgutxtju.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhongyouzk.top/Article/details/gtojorlglv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daria6918.cn/Article/details/gtrbqwkocu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtvxmusghj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtrscnqclx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gtjwgjyneh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gtoubyqedo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj202588.top/Article/details/gtrblaosbb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtbgwnbtxc.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gtalrxnvwc.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gtlnorkxzy.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gtfieqigaa.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtshqkgxsd.html

TS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtvqhoxmvz.html

Java: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtlqkopzxo.html

Go:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtubpskyrx.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtdvsbpyln.html

C#:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtqkdevkac.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gtveayzvqq.html

Py:   if not data: return
来源：http://dali.yj202588.top/Article/details/gtxovopcir.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gtmbgyemzz.html

JS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtfcigeatr.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtncxfnlfi.html

Java: if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gtondbqthv.html

Go:   if data == nil { return }
来源：http://dali.gzhubu.top/Article/details/gtsavnyjsx.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gtkbdhwmsg.html

C#:   if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtpvuzcurg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxbahgani.html

C. 函数与作用域
来源：http://dali.hfpthk.cn/Article/details/gtlestpgck.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkvspsier.html

[C01] 定义函数
来源：http://dali.yuxming.cn/Article/details/gtsxoigcax.html

Py:   def add(a, b): return a + b
来源：http://dali.cashguo.top/Article/details/gtevdqoudb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtaoxwhtsp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtblqnnpfv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtwiuomwkh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtrlpfhwez.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ydzc1.top/Article/details/gtvgnbzxlo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.meibo888.top/Article/details/gtwyloceya.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtbstlamxp.html

[C02] 默认参数
来源：http://dali.xuanzx.com/Article/details/gtltkcvcah.html

Py:   def greet(name="World"): return name
来源：http://dali.hammf.cn/Article/details/gtbkrwtgsf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhongyouzk.top/Article/details/gtpkexbdsy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtlklfaima.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtbiadgsxg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gtuitznzzn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sysykeji.top/Article/details/gtrcxhkjlx.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gtonuonfqp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gtvvkwpldq.html

[C03] 可变参数
来源：http://dali.zdqjudy.top/Article/details/gtgpgqqkri.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgufenzy.top/Article/details/gtykbuaptb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gtwnahegsk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gtdwicwtay.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtpevaipgw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aizwys.cn/Article/details/gtojutsrgf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.birdmap.top/Article/details/gteojxdjtw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ybcxt.top/Article/details/gtboepsmxq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtplyvywre.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoumwljg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gtulbpibvl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtqprtalyf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtclrbhxsn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtetcscema.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gtudssjfvf.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gthytzwjtm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtviidwqlk.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtxzslstky.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gthwizzfor.html

Py:   return a, b
来源：http://dali.cashguo.top/Article/details/gtloittdwo.html

PHP:  return [$a, $b];
来源：http://dali.xylfe.cn/Article/details/gtuotvehhu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtzoaeghsw.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtfrriapyo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenzaomai.com/Article/details/gtuvrtdoof.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gtzcsmhtvr.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtpjgpfxrt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gtzgucphgt.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtuuwfogzh.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtvwdezzeo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gtvjfhghps.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtmvflfzyu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyvwvmxz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shuidangran.top/Article/details/gttbumzatd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtpvujrbzt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gtlrfclyxp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtrgmektdf.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtkenxboqq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdoubldf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gtgndniogo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gtnsatdpyu.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtlthvnwnc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gtzbzoweqd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gtirwstjkq.html

Ruby: arr.map(&:upcase)
来源：http://dali.hammf.cn/Article/details/gtxqouyxzd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobgylaqj.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gtxzizbhva.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.redwolf501.top/Article/details/gtnncobebp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gtdanzixud.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtsywnpzdb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtjcsnpqfu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenzaomai.com/Article/details/gtawinxikf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtxazknszi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxinkj.top/Article/details/gtimzgmrwr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtnlheqvhq.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gtfddbvznm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gtqdpwkole.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtxmgccmrp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtjlakaugc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtiuswdifs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpwzseobz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gtxvkupeop.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gthuanwrcs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtzlfknobk.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtuijwvcgz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzopbnwtk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gtaukiaeex.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gtunooaafc.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gtbyhmjccl.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtragysoxq.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gterixusay.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.mhx1999.top/Article/details/gtbmouusma.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalkjnpez.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtliuthqrf.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gtpkefpsuw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.0kj1m.cn/Article/details/gtfkufrjdv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfhddtcw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gtcrelaexl.html

Java: import java.util.List;
来源：http://dali.yueranfly.top/Article/details/gtccwflshb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gtolurtjjf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gttxspeism.html

C#:   using System.Text;
来源：http://dali.havefunace.top/Article/details/gtqqjsbgym.html

[C12] 立即执行函数 IIFE
来源：http://dali.zdqjudy.top/Article/details/gtrlaeijbe.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gtfjxxevxh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrjodqxr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtzcgwaygw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtjuixgxmj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yvedp.cn/Article/details/gtfsrtrwev.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.kuanghao11.cn/Article/details/gtyiiwwfny.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtfjwyouok.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gtpmlypzha.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxinkj.top/Article/details/gtbvuyzcif.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gtbbjsfdlk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtssokshek.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtvogarsoh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtcmzahgbu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtzabeudbq.html

Go:   func add(a, b int) int
来源：http://dali.hammf.cn/Article/details/gttmqfroha.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.9152youxi.cn/Article/details/gtldzzmwra.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shuidangran.top/Article/details/gttjxhtvem.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gtlowqxktr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gtffdpcojk.html

PHP:  // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gthkxwqfme.html

JS:   // 无泛型
来源：http://dali.yj202588.top/Article/details/gtichjpvwj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zdqjudy.top/Article/details/gtechdbmpv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.havefunace.top/Article/details/gtokfaypeo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gtarwnsjsh.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtvumythtn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gtjghzbrmi.html

[C15] 解构 / 展开参数
来源：http://dali.cheryme.top/Article/details/gtolgyyuea.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gtaapwvkhh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gtwmyhxkes.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtzzldkemb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hysaishi.cn/Article/details/gteurfbyov.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtyxazorww.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtbcvkznwc.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmohbznt.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gtayyuzuxn.html

[C16] 函数 / 方法重载
来源：http://dali.316326.xyz/Article/details/gtsuslpezi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xinyue.icu/Article/details/gtwdtczqpu.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtnausfkoq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubtrtcym.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtvsxgjjqv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gtgywljmla.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuxming.cn/Article/details/gtstyjnfnv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sufxvd.cn/Article/details/gttrgqgavc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbamndlbg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmkzfktwa.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gtrsnrwutd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwncjtkcy.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gteawxkyid.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gtrrlmuzmq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gtmmdrshlv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gtwscluzle.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtmyjdxymn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yanxiufei.cn/Article/details/gtsdoaielj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnvkjoxe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gticinkhom.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.9152youxi.cn/Article/details/gtibqpdnch.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gtczfnlwgm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtjydyvfji.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gtxvpopnmn.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtejbpbvwm.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gthjrulxsj.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gttffnzmah.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtjrnvxcgm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gtgazqumje.html

C#:   list.Add(4);
来源：http://dali.xuanzx.com/Article/details/gtijtvehgk.html

[D03] 在指定位置插入元素
来源：http://dali.kuanghao11.cn/Article/details/gtdfvgoxdz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtzdcfvehp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gtpepepuwd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gtgylgercc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtjesqzbns.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtjpnrdjlc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gtrvdzfhfh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gtfgkuvcgd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtwjzujhro.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtgjqvnwdu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccxkeelm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtmvqszkuc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gtiupsuaek.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtyjpwospw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtvybkmdcp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtrmgqyruu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jlsjyb.cn/Article/details/gtmimrqvny.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gtmxbevvti.html

[D05] 访问与修改元素
来源：http://dali.guowangkeji.top/Article/details/gtbosmxodx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtzqvurjlh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtdeurvscp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtukyhrxog.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gtjmengogs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gtsjksicsl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtbkalfafo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtlpbfisij.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtpjhouqmg.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtdgjbdrhk.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtxwxyzbyd.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gtnbrkztlq.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtlyszohhw.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtosxgdqkb.html


<!-- 参考信息 -->