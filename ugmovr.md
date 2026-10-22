代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gtabfydrcs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttgockmn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgrzqcqq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tian-w.cn/Article/details/gtjqtztjbc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.kuanghao11.cn/Article/details/gtgxrrirjq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xinyue.icu/Article/details/gtwndfhreb.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gtnilsdwtu.html

Py:   while i < 10: i += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtcirmhbgk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtlbnxkcaq.html

JS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtfnljtmjn.html

TS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtpjunxwtn.html

Java: while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpupugqys.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangdashe.top/Article/details/gthbkcrmcs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zycfv.cn/Article/details/gtfjgdlyhq.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtdezeeovj.html

[B08] do-while（至少执行一次）
来源：http://dali.xinyue.icu/Article/details/gtbkvtyqju.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daxiang520.top/Article/details/gtgjjvlysh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tanke756.top/Article/details/gtjtlsrxub.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtpsfpslug.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtxxdltgnd.html

Java: do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtddnlqswu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sweek.top/Article/details/gtqjsfnpfw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnxiangtu.top/Article/details/gtenglyqbd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gteksekszq.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gtleabenem.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guannengcc.top/Article/details/gtdgjazgxw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtiykzmpsk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtmtgnnzfl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtyeafngqj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtrvoohjgn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gttxbcoqdt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cashguo.top/Article/details/gtxigihuum.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtbnpozenl.html

[B10] 遍历同时拿索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gteywywijk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gtbmjtswiw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hysaishi.cn/Article/details/gtezmvrhdg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtwddtcwoz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtyrzbrumb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gtawhdixyt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cashguo.top/Article/details/gtuwoltehu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daria6918.cn/Article/details/gtegcfcboc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxuanxn.top/Article/details/gtztsfpjqo.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgufenzy.top/Article/details/gtgqpenfrv.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylcomzey.html

PHP:  range(0, 10, 2);
来源：http://dali.dianchejie.cn/Article/details/gtieopmgbu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtqkdzrspx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gtwfpmwfok.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ydzc1.top/Article/details/gtjrjretot.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gtifayzwju.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jiagoushi.top/Article/details/gtrijnvzei.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhiwuduotai.top/Article/details/gttpvsrtrt.html

[B12] 跳出多层循环
来源：http://dali.meibo888.top/Article/details/gtxndzjbbv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.316326.xyz/Article/details/gtayygepru.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gtoftubhmo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtanseilii.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtyrzekigu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtojacwuqn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhoulong.xyz/Article/details/gtfbltzyet.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangdashe.top/Article/details/gtrbekjanc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cucudq.cn/Article/details/gtzqhrejef.html

[B13] 判断是否为数字
来源：http://dali.tian-w.cn/Article/details/gteqqoqrre.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gtqxyicjyu.html

PHP:  is_numeric($x)
来源：http://dali.jianghu66.top/Article/details/gtvxzhylco.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtdmuqzgmx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gteufeclkw.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gtjqfjbfbd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tianlin.xyz/Article/details/gthneryfje.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ivvv.top/Article/details/gtczwydrih.html

C#:   x is int or double or decimal
来源：http://dali.nanxinkj.top/Article/details/gtfzsxgrhg.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gtacdoblvx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuxming.cn/Article/details/gtwzktwgpk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dianchejie.cn/Article/details/gtrlxcptci.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gtfabrkcav.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtcwlgfegi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtwketcqnm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkficgjwb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtosxqposb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtfiiazcuq.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gttyyyqkwg.html

Py:   a and b or not c
来源：http://dali.quarkkingdee.top/Article/details/gtduoeairt.html

PHP:  $a && $b || !$c
来源：http://dali.shangyingyoupin.top/Article/details/gtsxtgrkof.html

JS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtcxkdlpxr.html

TS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtdeikqyag.html

Java: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gthffwvshq.html

Go:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtdkcxrtbc.html

Ruby: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtfiiajgji.html

C#:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtnipmwena.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtkuxvrjez.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gtwelompgo.html

PHP:  if (!$data) { return; }
来源：http://dali.yueranfly.top/Article/details/gtatrzspcv.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtujqktcft.html

TS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgaxlejmt.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtwynepvoo.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gtkqidprmu.html

Ruby: return if data.nil?
来源：http://dali.wangshuangyany.cn/Article/details/gtesaizwfe.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtdldyrwye.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtyyywytrv.html

C. 函数与作用域
来源：http://dali.vqdsnc.cn/Article/details/gthcvubabi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtefdgfxtj.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtscnducxv.html

Py:   def add(a, b): return a + b
来源：http://dali.zhixingplan.top/Article/details/gtrmthjnrh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtexshfeww.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtfppipzqz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtpycjhcfc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtditgouzn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shuidangran.top/Article/details/gtexdyrsya.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gtivnhbgmz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gthnrpbsip.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gtsrjbaaex.html

Py:   def greet(name="World"): return name
来源：http://dali.feifeiyinyue.top/Article/details/gtbtlyuvjg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnxiangtu.top/Article/details/gtylizpydg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtjzrkgduq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gttzowqdrc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sxryk.cn/Article/details/gteczzosnn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhijptzs.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gtvlklunqg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.c1oappe.top/Article/details/gtounjtuxp.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gtezzdgbfa.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gthwiiposl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gttxcjijla.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtrpdbkpeq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtugzedawr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gzhubu.top/Article/details/gtcpjpfwbq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dianchejie.cn/Article/details/gtsimpbiou.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gtshjtvofq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.smart0.xyz/Article/details/gtfexgiuwr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jianghu66.top/Article/details/gtarwdkxdi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gtdistwjzr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gtmblhjujv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtjxvuzwky.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zdqjudy.top/Article/details/gtkrsdnhyd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gtgfspqdtw.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigfzy.top/Article/details/gtuhhxezzc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtvqpslkaq.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtfidgmgzg.html

[C05] 返回多个值
来源：http://dali.ppjwa.cn/Article/details/gtanndapyo.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtrnhbkcqk.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gtsmfpruqf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtmnbxzitv.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtxqkxdeac.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gtamwowekt.html

Go:   return a, b
来源：http://dali.cashguo.top/Article/details/gtonuvhkug.html

Ruby: return a, b
来源：http://dali.xinyue.icu/Article/details/gtlomzxkio.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenjidiqi.icu/Article/details/gtunprcmsn.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnofkdnl.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhvbbypc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gtcyhhvaio.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtlfhgmpyg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gthlvckydk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guannengcc.top/Article/details/gtzbplbzqr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtqxgdgjbq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258.top/Article/details/gtqlotldjb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtcexoiwvq.html

[C07] 把函数作为参数传入
来源：http://dali.zdqjudy.top/Article/details/gtetlyvqsb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gtkxzisuqh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gotoacloud.top/Article/details/gtaqwijuut.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gtvcgjlouq.html

TS:   arr.map(String)
来源：http://dali.zhixingplan.top/Article/details/gtyqedxxly.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtsmbcqbtz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gtpsbhwklk.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpvbzffa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gtexfzitis.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gtjlttanhc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sxryk.cn/Article/details/gtntcidbff.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gtseohtajt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtqfzhauwn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtvuihkmby.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yueranfly.top/Article/details/gtwdeixkmf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaopsxzf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtimexikvd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gttgdjvmdb.html

[C09] 递归
来源：http://dali.sysykeji.top/Article/details/gtugkcilbv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtkckgahvx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtgvmotcum.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtjlxuwkms.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gthrpsiumy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj202588.top/Article/details/gtwqsxkbqw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gtjlworxtw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gtenjihpkn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gtyrdoozcm.html

[C10] 变量作用域
来源：http://dali.hysaishi.cn/Article/details/gtfwgelilo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtbzwowcna.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuetiantiany.cn/Article/details/gtwfpbeszi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gtrejewjqj.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gtbdnetfwl.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtnttdukkp.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtyiwinxnf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gttvgraarx.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gtyokovins.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gtbuvxhjtn.html

Py:   from module import func
来源：http://dali.hysaishi.cn/Article/details/gtxswxnoei.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gtfczmbhev.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gthunpaovn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gtwilyduuh.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gtepuvjdqd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258.top/Article/details/gtyhtfqimv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gtcgfizova.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gtgdtnlxuq.html

[C12] 立即执行函数 IIFE
来源：http://dali.ivvv.top/Article/details/gtrvgnhgpy.html

Py:   (lambda: print("run"))()
来源：http://dali.9152youxi.cn/Article/details/gtmlofcyjc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtkgpfavxw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtilwuijrp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtrtiglcnr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pycfn.com/Article/details/gtsyrmiity.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gtovwllryk.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gtwtrhulaz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gtevoremzb.html

[C13] 类型声明 / 类型注解
来源：http://dali.jyoumei.cn/Article/details/gtmnrzslvw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gtrotplcxx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtctrqhkjy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gttkaeldhx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtkxjoubmh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtmcgejret.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtrdscsdjy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteglspmx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gtwejcgvks.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gtjpbuoxci.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gtwpxfhlkn.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gtljizfwuz.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtobbhxhix.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gtzopwkksr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrqkwjsan.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtbljixchj.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gttvrjffio.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhengqikj.top/Article/details/gtmdcsnwnz.html

[C15] 解构 / 展开参数
来源：http://dali.jqgufenzy.top/Article/details/gtvjmavmmt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinghuilouyu.cn/Article/details/gtrflvoxjp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gtubvienao.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcysfbbjk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ppjwa.cn/Article/details/gtgjdalcep.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gtoyfzektr.html

Go:   // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtufoqfezy.html

Ruby: a, b = pair
来源：http://dali.gogol.net.cn/Article/details/gtkgixncmc.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gtntkeurue.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gtvktotjnk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gttyftldcm.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gtpykmobmi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhongyouzk.top/Article/details/gthbkfkbjz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gtobhnayhk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gttosohpak.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuetiantiany.cn/Article/details/gtawxwlfgn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sufxvd.cn/Article/details/gtbisylkuz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuityhiow.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttfmxqqop.html

D. 数组 / 列表 / 集合
来源：http://dali.dashuyun.cn/Article/details/gtywqjotqz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtwxolflfx.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtdxeypepr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtifmcdlym.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtqwoxjlnm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gtfhqiogei.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gtfncgdgdq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gtbgbgenrd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gtazaqkfus.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtyqighuke.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yangfankeji.com/Article/details/gtqcqsvdmf.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gtnuxprqqu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtmtyrpkez.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gtsgqjhsqj.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtpagofxxf.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtkcmlbhkj.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gtphwgzxgn.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtizefhcis.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gtoygfdsol.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtdgzrsqfp.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gtmvogokml.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtennkhwaz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gtrndlqaor.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gtpkdnfumi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtyuumooev.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtadaepgis.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtlvoxktny.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gtgfavsdij.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtuxegvvld.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gtnrwrpgiu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gtcpachzdt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtcinhlsvu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtufteqpsj.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gtgkzfktej.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gtohjdrjyk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtolxpieyr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gtxipirdpk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgfzy.top/Article/details/gtkqdngizh.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gtnrzkceaa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtrudbxbwq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtiffmhxyp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtagztuhuz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pengpengdd.cyou/Article/details/gtewbbvpcf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yonumen.top/Article/details/gtnkvmpspl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtsmrukehh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtbndbwbjc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtrfevwovt.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gtyvsnxjtd.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtwatimepy.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gttnqdisam.html

JS:   arr.length
来源：http://dali.sweek.top/Article/details/gtlhhutjiu.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtcodthvzh.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gttgwntkdn.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtdlpjmfqn.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gtdagkbjxe.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gtlwszkuey.html


<!-- 参考信息 -->