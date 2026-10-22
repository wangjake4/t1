代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yappgtmz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdegqgkw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shuidangran.top/Article/details/gt2tfvkrlnh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hfpthk.cn/Article/details/gt2wtoxticp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.svipenyu.cn/Article/details/gt2nxnoenmq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ieehtzpk.html

[B07] while 循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzcrrbkq.html

Py:   while i < 10: i += 1
来源：http://dali.snrcjt.cn/Article/details/gt2tieihsqt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ivvv.top/Article/details/gt2cbmovhrw.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmevamc.html

TS:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gt2wchdmkjq.html

Java: while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gt2hevarefr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xylfe.cn/Article/details/gt2djkdbwlr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tianlin.xyz/Article/details/gt2hngcafxh.html

C#:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gt2dtpiihnn.html

[B08] do-while（至少执行一次）
来源：http://dali.gzhubu.top/Article/details/gt2kyiigbfx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ehwqpu.com/Article/details/gt2ryycbtza.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hammf.cn/Article/details/gt2xvevgmtq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gt2jznrgend.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkhpbgzu.html

Java: do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gt2sfmpkwnc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cheryme.top/Article/details/gt2vyruqjdt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guowangkeji.top/Article/details/gt2jwdfucqo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2mhzuhyuo.html

[B09] break 与 continue
来源：http://dali.zhixingplan.top/Article/details/gt2pcmwzxws.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gogol.net.cn/Article/details/gt2airzvlao.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gt2jxdkdfuf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2jcumluie.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xehnehrz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2ufjoiljy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhengqikj.top/Article/details/gt2ekahgjsz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gt2vbhcgstc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fuwlxdbu.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gt2dcyjzcut.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hammf.cn/Article/details/gt2btemcyws.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hfpthk.cn/Article/details/gt2tpscchfx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhauwino.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbiqenks.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yueranfly.top/Article/details/gt2nnnzcdga.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fengsongda.top/Article/details/gt2dgsiwpsq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yonumen.top/Article/details/gt2czizgydz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tanke756.top/Article/details/gt2jtsndtme.html

[B11] 生成数字序列 / 区间
来源：http://dali.zycfv.cn/Article/details/gt2uctlsbkl.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258.top/Article/details/gt2shbsaroz.html

PHP:  range(0, 10, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2zgszaeuy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gt2cevhnhpn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gt2olrebpim.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cqqwz.cn/Article/details/gt2juihvkky.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gt2igpudcve.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cucudq.cn/Article/details/gt2grzyggsc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258888.top/Article/details/gt2vqyrwgbn.html

[B12] 跳出多层循环
来源：http://dali.hnqzz.top/Article/details/gt2nbpaitdz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shuidangran.top/Article/details/gt2trczqvqx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yongpay.top/Article/details/gt2aajzllps.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gt2ormvtzrd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2bnxctvhb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gt2ngsfarkw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuanzhike.top/Article/details/gt2obydrfwo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gt2jeymheur.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gt2purhxbke.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gt2twnyfkqa.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhengqikj.top/Article/details/gt2wvepvqww.html

PHP:  is_numeric($x)
来源：http://dali.svipenyu.cn/Article/details/gt2ovlrvwby.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gt2mhsjritn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gt2fjvnedup.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gt2mfgnaaxx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hfpthk.cn/Article/details/gt2gjztruud.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigfzy.top/Article/details/gt2otilyzvq.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gt2nhvxsneg.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gt2llfhrxwo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gt2akfpcewx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gt2qmethlwi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gt2qcduqzgi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2foiuravr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xylfe.cn/Article/details/gt2hurtiybz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gogol.net.cn/Article/details/gt2zkknuask.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gt2bstuvdfx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2wpgnlrgu.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gt2wzbrbaao.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gt2otofnawp.html

PHP:  $a && $b || !$c
来源：http://dali.aibaodan.cn/Article/details/gt2nlcodoci.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2cqaiqksf.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2zhmqcouw.html

Java: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2xwzbqyoy.html

Go:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2hhccjitd.html

Ruby: a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2bnletwtk.html

C#:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2bowyfhea.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.316326.xyz/Article/details/gt2hsofvdoh.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfuzbxgs.html

PHP:  if (!$data) { return; }
来源：http://dali.9152youxi.cn/Article/details/gt2yeoopyjs.html

JS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gt2kljbsppr.html

TS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gt2ilqaudcf.html

Java: if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gt2yzmodqsy.html

Go:   if data == nil { return }
来源：http://dali.yj202588.top/Article/details/gt2vmobvkdy.html

Ruby: return if data.nil?
来源：http://dali.zycfv.cn/Article/details/gt2ktbayjvz.html

C#:   if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gt2lqqyvded.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2bebwajtt.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gt2egappzpo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2vhorkubx.html

[C01] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdccbznk.html

Py:   def add(a, b): return a + b
来源：http://dali.yj202588.top/Article/details/gt2rkehkfzq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2banlsmpy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2kmlfkgdj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbrnxxez.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2xzhclhki.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsckjvdi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gt2ajwwyvmp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2ijlubnls.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gt2goqgahmg.html

Py:   def greet(name="World"): return name
来源：http://dali.gotoacloud.top/Article/details/gt2yevlowbz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258888.top/Article/details/gt2tbqlqugw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2kbxqbpxg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gt2eyfcenel.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj202588.top/Article/details/gt2jhliajrc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuanzhike.top/Article/details/gt2vblinzkv.html

Ruby: def greet(name = "World") = name
来源：http://dali.guowangkeji.top/Article/details/gt2nenrwjzc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gt2tmfzhsoa.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gt2pquxdcin.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gt2jnqdrkex.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gt2bjlfpbqv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gt2uhhdifaa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gt2wqftsbtj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gaenvhvp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wojzbxep.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gt2lydiatqb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xylfe.cn/Article/details/gt2knzvybxg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuxming.cn/Article/details/gt2quagzwlz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnhywrtz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cucudq.cn/Article/details/gt2uvyzgzyn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2boxvsnvz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gt2wsiggymy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gt2niscuzgi.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gt2yyjcqerm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gt2ueltdnfn.html

C#:   f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gt2eqwqelmw.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gt2wvscapix.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gt2vcyrkour.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gt2vmfsnvwh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gt2rrngddef.html

TS:   return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gt2buqnikdu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gt2vlthzdpc.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gt2fdrynchd.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gt2lptppwlj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsuzxtyr.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybvafcim.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gt2dobugqee.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gt2cmgyvdma.html

JS:   const square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2jlcgnwpn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gt2gxszcmxl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gt2rynosrel.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bivpshjz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxinkj.top/Article/details/gt2oawcrsml.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2uwxwulli.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gt2tlwtqjqn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gt2wyumhyin.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2ctkwozwl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gt2uyqgzyov.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gt2fzokligp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gt2jdbgctji.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.havefunace.top/Article/details/gt2vrnmhvur.html

Ruby: arr.map(&:upcase)
来源：http://dali.kuanghao11.cn/Article/details/gt2imrcezor.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gt2qwvgrizz.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gt2yxrnenvb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gt2noydltip.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gt2vdszzozp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zlzxxfaj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcodsvym.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.birdmap.top/Article/details/gt2qfgewrva.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gt2kzenabao.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gt2ydipbtrh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2cxlvqzfb.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hquhcesu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gt2cafpflnw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2ddqbnamv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gt2uaxubqwb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jiavrugz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gt2mhsbhvwc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqklowtk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gt2bwzbynqy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sufxvd.cn/Article/details/gt2lbwtuzzk.html

[C10] 变量作用域
来源：http://dali.guowangkeji.top/Article/details/gt2tjzcjswp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.kuanghao11.cn/Article/details/gt2pvisiurh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gt2svehfcvy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gt2swskuzwn.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2lxsnnqvh.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2qirhccuq.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2nuxvbulu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gt2vkpdkzec.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2nvvzcoqx.html

[C11] 模块导入与导出
来源：http://dali.0kj1m.cn/Article/details/gt2nlgmttlw.html

Py:   from module import func
来源：http://dali.mhx1999.top/Article/details/gt2nvzkqubz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gt2qlsablhy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gt2yqqkvnij.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gt2mjvwbkxg.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gt2lllqeegp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xziqi.cn/Article/details/gt2xarjzeyw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258888.top/Article/details/gt2ooydelgf.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndlggnjn.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gt2czmtrrnz.html

Py:   (lambda: print("run"))()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ugaohhmh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gt2bvnnhmnp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gt2kcamhvrr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gt2tsqfhfhf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.c1oappe.top/Article/details/gt2qekqrfsx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gt2irblkmtk.html

Ruby: -> { puts "run" }.call
来源：http://dali.kuanghao11.cn/Article/details/gt2uraewoan.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daria6918.cn/Article/details/gt2zhjkomzw.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuanzx.com/Article/details/gt2hxhhktky.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.svipenyu.cn/Article/details/gt2gwprysre.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2ddsvnurj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gt2oyqvixvw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rwcvhkon.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2dvehvrpj.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gt2xzvkglnh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gt2nqvhpvwy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhengqikj.top/Article/details/gt2qnnwlduc.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uunmirkm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gt2tqrlkptd.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2sobckttp.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gt2svwyktwy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hnoflgql.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gt2gxqwkbem.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gt2uwejilfe.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gt2ijjgtvip.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dianchejie.cn/Article/details/gt2pndxbkkz.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gt2uscaakpc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gt2xoetazsu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gt2taactypx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gt2hugknstv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gt2orvhcrse.html

Java: // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gt2jxdmyiix.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2ybozhjhs.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gt2twxudelr.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gt2itxfbrei.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gt2gqqgaoen.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yvedp.cn/Article/details/gt2ffzlrbgx.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gt2nroaktrb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gt2pxomjnep.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gt2vxpwcgvq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2evlvjfxy.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gt2zfxjjqxf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gt2bwvuglol.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gt2jkurzcoc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojcsaqvk.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gt2pgcscjqy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2mmmhlzcl.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gt2nkaelzgp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hongshengwenyu.top/Article/details/gt2cfaochhi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gt2ommdxlik.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdmaqleb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfituusz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gt2ikynevfp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gt2wwwhvcme.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gt2xchcwsvm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ydzc1.top/Article/details/gt2rhtdzfsh.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gt2awfqwkxd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guannengcc.top/Article/details/gt2kdxtotne.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gt2eowhoegz.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gt2anjjmcjf.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gt2mjgyddll.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gt2ssurkzzu.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gt2tbjtqqpk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gt2xzxmcyxs.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gt2swkqdfqc.html

[D03] 在指定位置插入元素
来源：http://dali.tian-w.cn/Article/details/gt2vbzvyjbq.html

Py:   arr.insert(0, 0)
来源：http://dali.xziqi.cn/Article/details/gt2fpifopqj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gt2pmuheynl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gzhubu.top/Article/details/gt2qyzucqcy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2fhqphdry.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2aacmkdzo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2ojwxcnqj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cqqwz.cn/Article/details/gt2akegfvhg.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gt2tejolcjy.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gt2dplrkrgc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gt2vddkimpd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gt2poseegqa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gt2kcfbahbp.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gt2efoztvnm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gt2aunjkzju.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gt2rhuqqrhm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gt2pjqcirvs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gt2lvelfyyo.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gt2swxpnijd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gt2xsiympen.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gt2alxnangn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gt2bgannnav.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipdiyddb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfcnutuv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzflcefh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2nobvygst.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gt2xmskgeod.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2xmjgarrt.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2wrbkmjjh.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2sthqxwlp.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gt2gdcovphi.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gt2uzcefulk.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gt2snmvvxjz.html

Go:   len(arr)
来源：http://dali.yongpay.top/Article/details/gt2jsbozeqc.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gt2rkwgcaxg.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gt2oxzsgwbm.html


<!-- 参考信息 -->