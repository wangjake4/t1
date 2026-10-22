代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aibaodan.cn/Article/details/gt2hzhzgoiy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ydzc1.top/Article/details/gt2celnflqb.html

[B07] while 循环
来源：http://dali.svipenyu.cn/Article/details/gt2fefqunbm.html

Py:   while i < 10: i += 1
来源：http://dali.yuanzhike.top/Article/details/gt2suopymaw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2szosmwpz.html

JS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gt2osxiriyh.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gt2zhfaiwrr.html

Java: while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gt2sacbjqat.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gsbnmlax.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbmtovmx.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gt2rnsuqryb.html

[B08] do-while（至少执行一次）
来源：http://dali.xinyue.icu/Article/details/gt2cvndrgeg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daria6918.cn/Article/details/gt2nvtevamc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2sjfykdcs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gt2keiaiknk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2tsrjuapw.html

Java: do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gt2skvdeqlc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cashguo.top/Article/details/gt2wlvfpvqg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258888.top/Article/details/gt2kqjsnvtz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gt2mohfrvcj.html

[B09] break 与 continue
来源：http://dali.ydzc1.top/Article/details/gt2ziofoyie.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.havefunace.top/Article/details/gt2iikrmpcf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2wpebkytq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ekyzfiiw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2zgiigbtr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2eubtdgne.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxinkj.top/Article/details/gt2nywalczv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.iojbl.cn/Article/details/gt2nkykeqke.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2xmteirdu.html

[B10] 遍历同时拿索引
来源：http://dali.shuidangran.top/Article/details/gt2btnfkegj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xziqi.cn/Article/details/gt2kpgjszav.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gt2ihwcozbi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gt2mazkfeox.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gt2khehzpnr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.svipenyu.cn/Article/details/gt2wivdncot.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hammf.cn/Article/details/gt2noylxgcn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bupbijmm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigfzy.top/Article/details/gt2tyhnragu.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnqzz.top/Article/details/gt2mccdocdy.html

Py:   list(range(0, 10, 2))
来源：http://dali.tian-w.cn/Article/details/gt2unzphqqu.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2rgmbjkdk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gt2yfeovkel.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gt2qehyjgae.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.iojbl.cn/Article/details/gt2ybvgfpxp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.mhx1999.top/Article/details/gt2mkvhihcq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xylfe.cn/Article/details/gt2mqeffsmg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.316326.xyz/Article/details/gt2ufaffmni.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gt2yhtechax.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gt2htgdnxjh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shuidangran.top/Article/details/gt2yzjglxae.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2skakocus.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2ldlaevyu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gt2epkvosgx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hfpthk.cn/Article/details/gt2gogljdxt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258888.top/Article/details/gt2emmkufgu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guannengcc.top/Article/details/gt2goafmzfn.html

[B13] 判断是否为数字
来源：http://dali.cqqwz.cn/Article/details/gt2xxwnnbnw.html

Py:   isinstance(x, (int, float))
来源：http://dali.mhx1999.top/Article/details/gt2ahvrczjr.html

PHP:  is_numeric($x)
来源：http://dali.smart0.xyz/Article/details/gt2cafsipsf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gt2oxxyqjuq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gt2kybwmcuk.html

Java: x instanceof Number
来源：http://dali.wangdashe.top/Article/details/gt2vwwnlfto.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj202588.top/Article/details/gt2qfvwxtat.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gt2yphqnmow.html

C#:   x is int or double or decimal
来源：http://dali.hywenlv.cn/Article/details/gt2xfhkqkxx.html

[B14] 判断值是否在集合内
来源：http://dali.haohaochexian.top/Article/details/gt2odphyvfm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gt2knbtgkpp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gt2xcelbmcl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jiyejraa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2hsjbivvn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj202588.top/Article/details/gt2jsjpuapy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenlongwang.top/Article/details/gt2ckkijbzt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gt2hudshdtj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2omqpecbt.html

[B15] 布尔运算与取反
来源：http://dali.xuanzx.com/Article/details/gt2oqppchat.html

Py:   a and b or not c
来源：http://dali.cashguo.top/Article/details/gt2icxfcyhr.html

PHP:  $a && $b || !$c
来源：http://dali.yuxming.cn/Article/details/gt2coumogcn.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhlkgkqw.html

TS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2zdsnwmrp.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gt2cmqhmcxo.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2uzxipkeq.html

Ruby: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gt2xkiypdal.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gt2lqzdauhx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gt2tffxpzol.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gt2ivuramlp.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gt2fxjprtxp.html

JS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gt2mlyvntqh.html

TS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gt2tohmxevv.html

Java: if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2lnnwgted.html

Go:   if data == nil { return }
来源：http://dali.xuanzx.com/Article/details/gt2suwgqvzc.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gt2kfpgvenn.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gt2xjxzhjgp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2bgjugncz.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gt2bazjlwqf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjserihf.html

[C01] 定义函数
来源：http://dali.cucudq.cn/Article/details/gt2ihzemdai.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigfzy.top/Article/details/gt2laxalivd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2bphogoke.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flqqixru.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2crktmziz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2wlygtgbf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2oagdywav.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gt2zhyahzxn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fljjrtoo.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gt2sixsbfir.html

Py:   def greet(name="World"): return name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wberxucj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gt2enpbemyd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2qeuklsxh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2vppxspoe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gt2dhojqlbz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gt2dyuerqyu.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258888.top/Article/details/gt2cuzrrjyv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigufen.top/Article/details/gt2qfxvditt.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gt2gvcggwmp.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gt2amgpwcdc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.snrcjt.cn/Article/details/gt2rrhajmws.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gt2ggbflcyg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gt2rtlmvmry.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gt2wfukplbb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gt2cuxmlqhq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gt2qivzpsbt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.kuanghao11.cn/Article/details/gt2atthwywx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gt2fdpkqeob.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gotoacloud.top/Article/details/gt2djmiqenq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnxiangtu.top/Article/details/gt2qkfemvbp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gt2tpmcoqhd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuxming.cn/Article/details/gt2svsmlfyq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daria6918.cn/Article/details/gt2wagbwhta.html

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gt2ngmkenmn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2mcfnirwy.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gt2dxritxiy.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gt2trmjjmwg.html

Py:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcromhdb.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gt2oabopyln.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2zhfagmcw.html

TS:   return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlbcpgbn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gt2ulgiagva.html

Go:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2xjsmitni.html

Ruby: return a, b
来源：http://dali.zhongyouzk.top/Article/details/gt2ulgyhqjc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gt2gerguzfl.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gt2dzhlwcrd.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmhgnqlb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guannengcc.top/Article/details/gt2xrephqjb.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfvquwpg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shuidangran.top/Article/details/gt2taiuluxt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gt2obhqvzgj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guowangkeji.top/Article/details/gt2qcebkjvs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gt2wvtranms.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2wvnaxsch.html

[C07] 把函数作为参数传入
来源：http://dali.yuanzhike.top/Article/details/gt2boitknkm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.316326.xyz/Article/details/gt2cvkhdlrq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xylfe.cn/Article/details/gt2outykgbk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xinyue.icu/Article/details/gt2cgkhdoaw.html

TS:   arr.map(String)
来源：http://dali.haohaochexian.top/Article/details/gt2ljlytvxe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2lntbdjbd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gt2jnalhjgq.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gt2oleyijlr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gt2bugvsypb.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gt2bihkcfpp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zdqjudy.top/Article/details/gt2lzetinia.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gt2twrhsnzz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gt2ylqoppiv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ggwzpoxd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jiagoushi.top/Article/details/gt2hghwsglt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhengqikj.top/Article/details/gt2xnnncwtn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gt2iqvonlxv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2csaadlaa.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epszsvnw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2buwrswsv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2mideuyge.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gt2adiludpd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2lcgmqmpr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gt2kfyagwae.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gt2nlfhphez.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gt2shwbuzvb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gt2bxojwlcg.html

[C10] 变量作用域
来源：http://dali.ivvv.top/Article/details/gt2wdiggxmu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gt2lgqpbouq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gt2dsfzeyzy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2gyiwhjqc.html

TS:   同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2tjrxuyfi.html

Java: 方法内为块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxdnqoep.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhzlzjhi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gt2yywhwfag.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2ffjpxpvy.html

[C11] 模块导入与导出
来源：http://dali.xylfe.cn/Article/details/gt2tcolfkrt.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gt2orcooqkj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gt2qgjjruns.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gt2qylizfuq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.havefunace.top/Article/details/gt2fbqqijix.html

Java: import java.util.List;
来源：http://dali.xuanzx.com/Article/details/gt2molbsdyx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gt2yxjdrpwc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.birdmap.top/Article/details/gt2jvjgpsat.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gt2izrpecqg.html

[C12] 立即执行函数 IIFE
来源：http://dali.quarkkingdee.top/Article/details/gt2cuowwrco.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gt2rgujshxh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.redwolf501.top/Article/details/gt2mnipcxtp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gt2djarbrht.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gt2pevsnfkj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jiagoushi.top/Article/details/gt2bkpstldf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yangfankeji.com/Article/details/gt2bpzxdyje.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigufen.top/Article/details/gt2txgmnxny.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2gwooidap.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gt2pzuwpfnn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpwhpbkd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pzbqfzhn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gt2dvxkdszz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqkgmxdp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2ckfrstao.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gt2ssbvmjvf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gt2zydbqlzy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gt2benvrwjs.html

[C14] 泛型函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljdvfvxl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iovluvuk.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2kigxxjss.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2kkxjvqlj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gt2keefmxnq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qefpafhr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.andypj.xyz/Article/details/gt2gcabpmeo.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gt2pcwmyets.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gt2dlglwayo.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gt2yafoptfn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grqfagri.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zdqjudy.top/Article/details/gt2mcmoxudm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2jxtllgmy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmauakie.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gt2fchzzmij.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gt2fgfbruss.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gt2vabyabob.html

C#:   var (a, b) = pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2muebeymu.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gt2fukgizjv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sflcdnxj.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gt2slyratup.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gt2ktsridso.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xylfe.cn/Article/details/gt2kfbusgca.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gt2zmkgdsxw.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gt2apzkdiua.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfbbeheb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2oeozngyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjlkzqv.html

D. 数组 / 列表 / 集合
来源：http://dali.iojbl.cn/Article/details/gt2yjecuucg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2bfcfvlfr.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrhplwpc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gt2gmnlvzfh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gt2eiliygnl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2vtpgutix.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cqqwz.cn/Article/details/gt2ohkflfmu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gzhubu.top/Article/details/gt2sadkdntb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gt2vriryhjq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gt2odluipqr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.andypj.xyz/Article/details/gt2xikhlmoo.html

[D02] 追加元素到末尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulrdkumq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gt2pxonvniz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gt2ohpenham.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gt2cnslbozj.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gt2fdmwgziq.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydugfdxu.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2hyshqzkm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gt2fjgehvnv.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvnwfqwt.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gt2eeeszgza.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcjevvx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gt2ctsuttyd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhqhzrpn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2voyxlvcd.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2wmgrecyl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gt2bpjrjiza.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwqwtehc.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2vfhjwupq.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gt2wmkqvhui.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gt2uucmvlty.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gt2ycbnlbsg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gt2omhpzhgc.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gt2mwdgnfhw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gt2pfmcvlaw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gt2ckpdntrw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aizwys.cn/Article/details/gt2cctvhgku.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gt2msofieuu.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gt2kmyextsp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2xypcxrdz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2slunlkig.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2yhnuukpq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.vqdsnc.cn/Article/details/gt2boknsepn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gt2ihyziqmh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gt2imldnfdh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gt2jmwuqwrb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gt2nrfbxosq.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gt2voqprspi.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gt2aesoupas.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2zbeetasc.html

JS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gt2urgxuuam.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gt2pjsiabrr.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gt2mdwswalr.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2waaycqbu.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gt2skwrniwp.html

C#:   list.Count;
来源：http://dali.cucudq.cn/Article/details/gt2edeolwpr.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gt2tpsyckay.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gt2pvvjnhlz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejtfcsxd.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2panaibwv.html


<!-- 参考信息 -->