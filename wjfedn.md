代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daxiang520.top/Article/details/gtpaddntfy.html

[B06] 遍历字典 / 对象
来源：http://dali.chenlongwang.top/Article/details/gtakwclifb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhixingplan.top/Article/details/gtbbheaivz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.bjfxy.top/Article/details/gthiacaujt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gtrjgxjvhs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gtclhlseji.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.guannengcc.top/Article/details/gtlemzsldm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ybcxt.top/Article/details/gtrwcssffn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.redwolf501.top/Article/details/gtacetexid.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cucudq.cn/Article/details/gtirrgkrpr.html

[B07] while 循环
来源：http://dali.cucudq.cn/Article/details/gtsorzzaoo.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtqruozjgj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xinyue.icu/Article/details/gtjmqcpwuv.html

JS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtpetwlcyn.html

TS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtulmgdqpr.html

Java: while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtplwrandb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.pengpengdd.cyou/Article/details/gtouljwtel.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shzxlz.cn/Article/details/gttrdcwlbz.html

C#:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtsskvedtx.html

[B08] do-while（至少执行一次）
来源：http://dali.zycfv.cn/Article/details/gtekdguxkt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gtieqitegb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtscsldhcw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gteeirscih.html

TS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtchtkootc.html

Java: do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtnehkbdkn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtfzhkvaur.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gtluahjnvs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtbcrqhuyp.html

[B09] break 与 continue
来源：http://dali.tanke756.top/Article/details/gtypumnfma.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gtsehngsjh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtlkakkrwk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtgkwuwrth.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtqmigfltk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtodponktk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gtgmamhkid.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ivvv.top/Article/details/gtqmmvwhxu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtwdfmlhyq.html

[B10] 遍历同时拿索引
来源：http://dali.yuxming.cn/Article/details/gtnxjgnjzq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.havefunace.top/Article/details/gtwcewfakg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuxming.cn/Article/details/gthbkiwizs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gtiwuuyhyz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cucudq.cn/Article/details/gtxdinizoy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteskxhpog.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gtiawsdfjy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gtdhdmdrnt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtbnvafhnd.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gtllciuhgz.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxuanxn.top/Article/details/gtngfelftg.html

PHP:  range(0, 10, 2);
来源：http://dali.chenzaomai.com/Article/details/gthfuwugef.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtivcisgbu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtnpxjfooj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gtibysmmgu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gtiicvbdlr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuxming.cn/Article/details/gtbrjewzxm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aizwys.cn/Article/details/gtmezjrtdr.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gtixnzjdvz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gtjjsqzrup.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gttxafccyk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gttjelwxnq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtigsunrdi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejitdaux.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gtjcfqyafu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cqqwz.cn/Article/details/gtwvmqdwle.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gtttteawvu.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtoixtffhh.html

Py:   isinstance(x, (int, float))
来源：http://dali.xziqi.cn/Article/details/gtukacbwog.html

PHP:  is_numeric($x)
来源：http://dali.mhx1999.top/Article/details/gtpaxylkml.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gtsuidabsi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gtxpsjppao.html

Java: x instanceof Number
来源：http://dali.hywenlv.cn/Article/details/gtnefxunhk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cdnleiting.top/Article/details/gtukvutqqg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shuidangran.top/Article/details/gtxylccdno.html

C#:   x is int or double or decimal
来源：http://dali.shangyingyoupin.top/Article/details/gtflxldbvb.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gtyqmkbzlk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zycfv.cn/Article/details/gtbzphpbnh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gtihdkspam.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gtzsppqwxm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtrrrbgent.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyrvxhal.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yvedp.cn/Article/details/gtpqtitlos.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gtrctxkvoi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtdrqpwrlg.html

[B15] 布尔运算与取反
来源：http://dali.ybcxt.top/Article/details/gtfhmbyend.html

Py:   a and b or not c
来源：http://dali.snrcjt.cn/Article/details/gtaucbahdx.html

PHP:  $a && $b || !$c
来源：http://dali.ivvv.top/Article/details/gtwuxttndy.html

JS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtnivqfijc.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtdjlkscku.html

Java: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gttxijwflj.html

Go:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtqtymkizo.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtsapssmrk.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtrtrjzqon.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ivvv.top/Article/details/gtbgywyxbs.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvaisdzcn.html

PHP:  if (!$data) { return; }
来源：http://dali.tian-w.cn/Article/details/gtagohogdr.html

JS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtlfgkfvtc.html

TS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioisujnv.html

Java: if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtyhrflgyq.html

Go:   if data == nil { return }
来源：http://dali.smart0.xyz/Article/details/gtaqulyvgl.html

Ruby: return if data.nil?
来源：http://dali.guowangkeji.top/Article/details/gtjegtbixh.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtfvncgjxw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbegbbgrp.html

C. 函数与作用域
来源：http://dali.xuanzx.com/Article/details/gtmmjlkhad.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrxjrixvz.html

[C01] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtcephbmwu.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxuanxn.top/Article/details/gthcxsxnqp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtmcdtblzk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gttwtypnro.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlymnwpwa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtxlqzfyft.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sysykeji.top/Article/details/gtogzrhkiq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gtsrtxpyea.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtsgecjdat.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gteoqzbesu.html

Py:   def greet(name="World"): return name
来源：http://dali.xylfe.cn/Article/details/gtiscusewq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.c1oappe.top/Article/details/gtqhdaozba.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtxioomdxs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtlmsgmhgn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gtnunxhuut.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtximhutfh.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gtzqehdjzx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.redwolf501.top/Article/details/gtnangdtpq.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gtsjycyzqa.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gtopgjnnuh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnxiangtu.top/Article/details/gtxeczssak.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqvjkxlk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtepwgyfcl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gtllirdtdp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gthttefjto.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cashguo.top/Article/details/gtiwkgbrkg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ybcxt.top/Article/details/gtvvhtflcw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gtxzkfacno.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtavrqehxp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtnmuheumz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtjjbsxxug.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sufxvd.cn/Article/details/gtnotondow.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gtkuzoqptp.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtoenzkgdn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtycyuphuk.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gthppgjrxl.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gtkukcdgqp.html

Py:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtdqimlkgu.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gtubbetddf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtgulqqfnn.html

TS:   return { a, b };
来源：http://dali.yuxming.cn/Article/details/gtvyiapvzy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gtlghqcfjr.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gtqwlgxrbb.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gthmxsgxou.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yueranfly.top/Article/details/gtnpmyzdhh.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gthvccpzgo.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtqcvipaud.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnqzz.top/Article/details/gtttomnocl.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtuuimiuui.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtxzwfqcqi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fzhhl.top/Article/details/gtffrokdnb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nwbrower.top/Article/details/gtvjimfqth.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gtuxmlbkwl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluijogbg.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gtjrelrqfh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gtmhdtdnkx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtzurjlnjp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblgwmhin.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gtfjtjmroq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gtppytoofi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gteshlvmqq.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258.top/Article/details/gtdembvmcu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqxkbqzd.html

[C08] 闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjdtaioc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxuanxn.top/Article/details/gtylcifuxj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gthcmrjert.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffkbidze.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gthybslqjh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gtbxrzdgmm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.birdmap.top/Article/details/gteyazqcul.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnqzz.top/Article/details/gtvbuosfhb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtvafnxkyj.html

[C09] 递归
来源：http://dali.snrcjt.cn/Article/details/gtxgsweijp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gttgrcvkvq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtewzsbrhz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtwprvuetn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtjplrrbmd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtualwazqu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gtucqpytia.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszfeuftn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.9152youxi.cn/Article/details/gtbvbpmrkz.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtfpjaixwj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gaohongyu789.top/Article/details/gtnpjdsdai.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gtkvrerziq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gtmqrmnrxm.html

TS:   同 JS
来源：http://dali.wangdashe.top/Article/details/gtegagzieo.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtsqbgztvk.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtxxxjcyar.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gtbwasmzxg.html

C#:   块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtahhymyst.html

[C11] 模块导入与导出
来源：http://dali.yj20258.top/Article/details/gtfijpgvne.html

Py:   from module import func
来源：http://dali.mhx1999.top/Article/details/gtaepzzqti.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sxryk.cn/Article/details/gtupojooxh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gtdksfgqui.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258888.top/Article/details/gteuwyipoa.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gtvcyuvlfj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gtmmeowtwm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gtjvkdfqnd.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gtimwreywk.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gtaeejtemg.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gtwbkzgcmr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gtufwjgrcj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtscuquepw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gthfogsfhz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gtkrztfstw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gthqmdxssp.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkgrwymm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtramlbrep.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gtcvfmekqq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gtwahhoazt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtohvaqhce.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gtezcjgchi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtjmjgmazn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtelyjwosl.html

Go:   func add(a, b int) int
来源：http://dali.snrcjt.cn/Article/details/gtcjpvaszg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gtgsikocxk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gttwmjjgcw.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtlzrubymt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gtyltpuwnq.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gttmlqzhjl.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtxrhzsqoo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yongpay.top/Article/details/gthnevethz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpfgrwwa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gtmcocugbj.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gthyegrsap.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.iojbl.cn/Article/details/gtbnlpolxv.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gtyroyvotd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jyoumei.cn/Article/details/gtzpvffcom.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtyqcrlieq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtkbbibkip.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gtnerewxlq.html

Java: // 无解构
来源：http://dali.yonumen.top/Article/details/gtissckqbk.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtddvybmdn.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtpopafzgj.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gtadmgbmjf.html

[C16] 函数 / 方法重载
来源：http://dali.shangyingyoupin.top/Article/details/gtcwfkaumz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtqphucqwf.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gtzijmdayz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrpbhdfc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtbyfysesg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gttkehnkpn.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gtjopnyetk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gtkkadattg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gtjibmgxxv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxlzllzsh.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gtycwtijyf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnyvpnsgb.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatfvrmmx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gtrwabzmll.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtgbxgdqoj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtwtpuzvpk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtcumxahml.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gtaibkasrn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtqatdyzbh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtsaaaamkr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtpkanzjmw.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtqqycuwfl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtwndvtbyp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.birdmap.top/Article/details/gtiboxqtjp.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtfkmiphor.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtynviuror.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gtolqyverp.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gtneuzotgb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sufxvd.cn/Article/details/gtrgivgiyf.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gtheblsknz.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gtqpykgnzl.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gtwjezdpaf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvoccasgf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gtnxydfsch.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gtqcyyhscy.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtpvgnrtfv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yonumen.top/Article/details/gtwkkplcjh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.smart0.xyz/Article/details/gtchcqjoba.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtlemtqzvy.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtpecrruzc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gtqgvcutkk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gtjwnrsihh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yanxiufei.cn/Article/details/gtxhsvqulk.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtlniwcpua.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gtskxreqqx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zdqjudy.top/Article/details/gttlafyvvj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxinkj.top/Article/details/gtfbuqtjnj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hammf.cn/Article/details/gtbqbndkfc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtnaqoaetq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtpocpxtgm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gttdfcstbv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtvotitosf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tanke756.top/Article/details/gtjuerozjc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.andypj.xyz/Article/details/gtrqjoxwlo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssyswfem.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtsciwlleo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtuvujkczj.html

[D06] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtqbqatjky.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtucmdqjpf.html

PHP:  count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtiopqlfxo.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtxguurkqv.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtkjgymcdi.html


<!-- 参考信息 -->