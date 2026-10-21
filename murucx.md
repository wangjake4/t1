代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hfpthk.cn/Article/details/gtuknqsxjz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.quarkkingdee.top/Article/details/gtdvyxhkck.html

[B07] while 循环
来源：http://dali.ybcxt.top/Article/details/gtaiqbdjgk.html

Py:   while i < 10: i += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtnchtxgyj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shuidangran.top/Article/details/gtfgtjnfxx.html

JS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtteptnrsy.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkprbkigq.html

Java: while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtuhrhtwbw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gtmfckdceq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.iojbl.cn/Article/details/gtodcrskix.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtbnlertfz.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gtkxvikmqu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shzxlz.cn/Article/details/gtgjprtkgf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.mhx1999.top/Article/details/gtemriadly.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtatmulend.html

TS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtmowvkyij.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtltdglbkq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzadrvjb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gaohongyu789.top/Article/details/gtwguopwwx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtspezvfky.html

[B09] break 与 continue
来源：http://dali.yvedp.cn/Article/details/gtnriugghx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.haohaochexian.top/Article/details/gtcgynibay.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtjztpbrra.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpobapvov.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gthfcpqxef.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtynwwpppg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jianghu66.top/Article/details/gtafjmbdmg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhiwuduotai.top/Article/details/gtiejogong.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtmlqbftbg.html

[B10] 遍历同时拿索引
来源：http://dali.shzxlz.cn/Article/details/gtgkmyjify.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtqbdhrwru.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gtkjfzvnqm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtopjvyjrh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuhscyfx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xinyue.icu/Article/details/gtjuhkbpxu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ydzc1.top/Article/details/gtmcklkwks.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gtyqmzjfxl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhongyouzk.top/Article/details/gthlotvhdr.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfteygito.html

Py:   list(range(0, 10, 2))
来源：http://dali.nwbrower.top/Article/details/gtbiapkrdc.html

PHP:  range(0, 10, 2);
来源：http://dali.chenlongwang.top/Article/details/gtgweghmjd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ehwqpu.com/Article/details/gtnexuudsd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtfaqdztwa.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jianghu66.top/Article/details/gtoshbrbdx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tanke756.top/Article/details/gtmqtpqyub.html

Ruby: (0...10).step(2).to_a
来源：http://dali.snrcjt.cn/Article/details/gtwjixlhho.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shuidangran.top/Article/details/gtrzilenos.html

[B12] 跳出多层循环
来源：http://dali.sufxvd.cn/Article/details/gtlyperklp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenlongwang.top/Article/details/gttwhjpvog.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gtphrijkwm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynifooqi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtebuvyzyl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtefnsfxnr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gtyyvczenm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.haohaochexian.top/Article/details/gtiwfnvoid.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gtbhsxaurk.html

[B13] 判断是否为数字
来源：http://dali.yonumen.top/Article/details/gtzxiugsxj.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gtlihkromc.html

PHP:  is_numeric($x)
来源：http://dali.c1oappe.top/Article/details/gtpobmyygi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gthrzwknwh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtktmtsbtu.html

Java: x instanceof Number
来源：http://dali.shanyushiyangkeji.top/Article/details/gteubhdnsu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gtybquvvmo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shzxlz.cn/Article/details/gtpvvldnao.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtdxtbinns.html

[B14] 判断值是否在集合内
来源：http://dali.yuxming.cn/Article/details/gtkrlctzcs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ehwqpu.com/Article/details/gtzodqtarn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xziqi.cn/Article/details/gtusnutazb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtgoczjoin.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtggbqdecu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtnutmypsl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jyoumei.cn/Article/details/gtvcjdehau.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.meibo888.top/Article/details/gtqyimhskn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gttcsahzfv.html

[B15] 布尔运算与取反
来源：http://dali.guannengcc.top/Article/details/gtdhwhkagb.html

Py:   a and b or not c
来源：http://dali.hfpthk.cn/Article/details/gtlwvripkr.html

PHP:  $a && $b || !$c
来源：http://dali.hongshengwenyu.top/Article/details/gttiywurtb.html

JS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtfolvvsfh.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtnbedeijp.html

Java: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtqxmpxscz.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtipqbjrhc.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtxwepzvdg.html

C#:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtbqvsywqm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gtdnrbadnh.html

Py:   if not data: return
来源：http://dali.jinqigufen.top/Article/details/gtrzhtwmgg.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gtoavkaefa.html

JS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmoosqzfh.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtuthbufip.html

Java: if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gtlihpfptz.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gtwmmpaqnt.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gtsmyomlyr.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtbrfexhyl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxzmqvlwk.html

C. 函数与作用域
来源：http://dali.ppjwa.cn/Article/details/gtxclqkqhd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtazpufcum.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtoscgpjpa.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gtaqpnhxrr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtzjhjpgqi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtorlorahc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtxgnxbgts.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gttelfzccy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gtnsvlcnrr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.bjfxy.top/Article/details/gtcuvswmvd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gterdwghoo.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gtkapibbbl.html

Py:   def greet(name="World"): return name
来源：http://dali.pycfn.com/Article/details/gtzhxikpme.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tianlin.xyz/Article/details/gtqoofyhuj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtcubapcjl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtbblgybxr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gtysijdkqj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangshuangyany.cn/Article/details/gtwdwsegdg.html

Ruby: def greet(name = "World") = name
来源：http://dali.xziqi.cn/Article/details/gtbjwslilp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gtbupgqjis.html

[C03] 可变参数
来源：http://dali.cucudq.cn/Article/details/gtwlggqbqd.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gtckmpjhdw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gtdvyrsoil.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtjwcbhwhf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtrdmzilai.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fengsongda.top/Article/details/gtlrmxruqb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cdnleiting.top/Article/details/gtvtxfvwqz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shuidangran.top/Article/details/gtldjkbhcc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakijfkrt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hysaishi.cn/Article/details/gtecpxdlhr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gtutmbszwr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gtifqdwlcc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gthbpqpgqd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dianchejie.cn/Article/details/gtioanjxlq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.redwolf501.top/Article/details/gtxonfrygk.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gtygvjjrbg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtqullpcti.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtbhceichk.html

[C05] 返回多个值
来源：http://dali.nanxuanxn.top/Article/details/gtlbowxncm.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtoumldvxo.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gtjpuyxpii.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoqhstjt.html

TS:   return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtijbeiznr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnxiangtu.top/Article/details/gtcaemngeo.html

Go:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtqnpaozok.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzmfkybs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gtseulgbje.html

[C06] 匿名函数 / lambda
来源：http://dali.jyoumei.cn/Article/details/gtsivldevy.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gtsrpscxgt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.andypj.xyz/Article/details/gtocpbpsss.html

JS:   const square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtywcsszud.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gttspcueeq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtvstqijkv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gtzhlsmbni.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jyoumei.cn/Article/details/gtaqctnujx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtkebitkrv.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gtrhtonccs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtbysrmrga.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtfnmuxqnu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqpewzwk.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssapzbfo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jianghu66.top/Article/details/gttzzxquti.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gthmfanoyo.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtbifjzjxs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cqqwz.cn/Article/details/gtyejrwvri.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtruucicxc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtmrtjuquh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gtbhpiygmz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtsbzdyqur.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtitzgxazt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dianchejie.cn/Article/details/gtajyragni.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cucudq.cn/Article/details/gtigibcitr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenjidiqi.icu/Article/details/gttngsydgd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gttkkddtci.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gtdxoxuoea.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtycyvngmq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtxyyzbsnq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtpixahojp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtbppxyymo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtqypdxjou.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gtdaovwgxi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtcfcgxiqf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcofclyru.html

[C10] 变量作用域
来源：http://dali.yvedp.cn/Article/details/gtfpqiylxi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258888.top/Article/details/gtjjgjcbcm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtxdoybgyr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gtwibblxnt.html

TS:   同 JS
来源：http://dali.yj20258888.top/Article/details/gtapvtwvhg.html

Java: 方法内为块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtmkrjfatt.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtyynqqawg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gtjeyasssd.html

C#:   块级作用域
来源：http://dali.nwbrower.top/Article/details/gtwvwzpvyr.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gtgsmkbthp.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gtxmgcwbyw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjomwcvrr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtwgrbthwr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugrvrwty.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtmqktlpgd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj202588.top/Article/details/gtsulaldya.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gtyxotnllm.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gtcmxxcope.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gtyddmzgli.html

Py:   (lambda: print("run"))()
来源：http://dali.yueranfly.top/Article/details/gtpbseumzi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shuidangran.top/Article/details/gtvnpmfxzy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtgwjrfbjw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtktsbyvnp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gtesladkhm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtthjhhpdx.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gtmowpjbiv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigufen.top/Article/details/gtahwzcsxt.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gtymdztqrg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gtvxzlxyig.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtxxdmxaru.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtpiiapvkp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gthhlcowns.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtmrnwlxur.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gtdvfsjxvq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gtmsymjsxo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gtfqahexew.html

[C14] 泛型函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvndlkgf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtgmyxxtrt.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtzexljnyq.html

JS:   // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtirrxnvmw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnubymftn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cheryme.top/Article/details/gtsxonnkwb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jiagoushi.top/Article/details/gtqmmchepi.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtloxamigs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gttdvacicr.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gtkemhktux.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gtairchsjh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtwnyondzr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtmpxzrqgj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gtfymipzbm.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtifsdpqdo.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gtdukmsnuh.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gtmmcljhlm.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtxnujgehd.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gtltefceul.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtfyficfkw.html

PHP:  // 无重载
来源：http://dali.bjfxy.top/Article/details/gtnlqszwcf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.quarkkingdee.top/Article/details/gtyoflqitd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtjihgborv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fengsongda.top/Article/details/gthvvzfecj.html

Go:   // 无重载：用不同函数名
来源：http://dali.mhx1999.top/Article/details/gtmbvckvki.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gteertlzxz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtawbuenyw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtuwwllbww.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gtbxjshkkn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtejxcgmpr.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gtybgpttyd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtlqqduihe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtzuedjiiq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtnnbqwwec.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gtnutgorrm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gtingftebm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gtpokgtvbj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gthajkkvfa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtcuigtmtl.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gtwozncaha.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gtrknizcrl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqjifszu.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtbqssremu.html

TS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtnvqkrxma.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gtsuyjyhge.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gtgqiowmnr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gtakmcrgiy.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gtpyuxsupb.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gtznceuite.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtsjdsvbdx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtyrjquyyk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gtfphnoaei.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtzlxbjcwl.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtzbxlnzil.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gtwrfzuiax.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gtpvungjkd.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtrxmwdkwj.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtnsezhonw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gtxyleeqev.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtwwfvgjbo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtqtegwwtx.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtjueujqmz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gtrvxaiyoi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gtwhcscrml.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrntlmtt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtnbdtmebo.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gtostfzehz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtlzobgalz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtuezudrah.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtaasddply.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gtvxkhiipk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gtfsekjleb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtyhgukjtc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtzwkhccqh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtibzkdxwl.html

[D06] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtmtetibsq.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtrzgptswt.html

PHP:  count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtimrbbyzr.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtgkqfhjto.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtfeoakgon.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtkghjskai.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtwphibvke.html

Ruby: arr.length; arr.size
来源：http://dali.xuanzx.com/Article/details/gtkvfxpilu.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gtygzwuxth.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gtdyaijzei.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gtfuouqzxn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xinyue.icu/Article/details/gtdpzhyzzk.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtsctwfmst.html


<!-- 参考信息 -->