代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuanzhike.top/Article/details/gthqsogwms.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangdashe.top/Article/details/gteadaaopg.html

[B07] while 循环
来源：http://dali.nwbrower.top/Article/details/gtlnvyturz.html

Py:   while i < 10: i += 1
来源：http://dali.fzhhl.top/Article/details/gtpmqkqpza.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.andypj.xyz/Article/details/gtgzcpzhxm.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtnqyjadys.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpnsjlec.html

Java: while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtkfsysxnk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.mhx1999.top/Article/details/gtdfjjwsmb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cheryme.top/Article/details/gthljjppac.html

C#:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtkdvqabpb.html

[B08] do-while（至少执行一次）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiygvwkdf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuxming.cn/Article/details/gtudxpxpdl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtjltyxzsg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtxkjgejot.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtttfaiwgc.html

Java: do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtymvelqdl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cashguo.top/Article/details/gtsarsitbt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xylfe.cn/Article/details/gtvyycsxns.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtqahphsls.html

[B09] break 与 continue
来源：http://dali.ppjwa.cn/Article/details/gtiskhdgxj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ybcxt.top/Article/details/gtzloyavvj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtwepwayiv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gtmncuhoik.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtendcbcwh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtztjvzywu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsymqefwe.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.snrcjt.cn/Article/details/gtpykqpldc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtftxhhwnw.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gtwqzpdbjw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gtybvxohnh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gtwztqztpo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gtvyapdjri.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gtgaofoztr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fengsongda.top/Article/details/gtpxqsskrr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sysykeji.top/Article/details/gtfpufsxof.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gtiqqjutvh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkfciplpx.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gtplnozfyj.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gtuhkjelyr.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gtvueddjrq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtszvlikui.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtdtseiiaf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xinyue.icu/Article/details/gtuqcpwteu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ehwqpu.com/Article/details/gtmzridido.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhoulong.xyz/Article/details/gtruklyxue.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gthnnkbpyc.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gtnkjwrvty.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgufenzy.top/Article/details/gtdfkrlewb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gtgtxvljcm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtsgowdsxc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gtfxcukptx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtevqfhqio.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gtresgodpa.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtniiflttb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gtcweahfgf.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyklaleei.html

Py:   isinstance(x, (int, float))
来源：http://dali.xinyue.icu/Article/details/gtjtffirvf.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtfprxdgel.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfiyaefc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtvofdqtcy.html

Java: x instanceof Number
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgrkarwq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cheryme.top/Article/details/gtkkhgzmgm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhixingplan.top/Article/details/gtqzimcwym.html

C#:   x is int or double or decimal
来源：http://dali.jianghu66.top/Article/details/gtsgjppsod.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gtavswvguh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ivvv.top/Article/details/gtvkfajkri.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gtqanmthya.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtgahzzprr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtvejwqhaz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zycfv.cn/Article/details/gtsfldugyi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtikrayzus.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtxonuibww.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gttioenjjz.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyarfxrp.html

Py:   a and b or not c
来源：http://dali.cdnleiting.top/Article/details/gttoneqmyy.html

PHP:  $a && $b || !$c
来源：http://dali.ybcxt.top/Article/details/gtaeuwtezs.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtncrlpvfn.html

TS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtikjxvssv.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtkqpktjsj.html

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtbrfgrlwf.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtydapqmpc.html

C#:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtwtxnrdiu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aizwys.cn/Article/details/gtsqdigmvk.html

Py:   if not data: return
来源：http://dali.wangshuangyany.cn/Article/details/gtirmwalxq.html

PHP:  if (!$data) { return; }
来源：http://dali.9152youxi.cn/Article/details/gtsqqpcvai.html

JS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gtxlgrnpav.html

TS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gtzeyhockn.html

Java: if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gttkaiupek.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gtyseyrxry.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gtzsiurquk.html

C#:   if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtbsparwfy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtohclvxal.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gtrvzqfwzn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtulpxszry.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtuwnsquon.html

Py:   def add(a, b): return a + b
来源：http://dali.zycfv.cn/Article/details/gtmuwmvhdb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtrknkwpcg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtaejwcfoa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtevleibuy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtysfjlkjd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtjqmejies.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gtsvjrqhqi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtdhoyolhq.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gtexvwglbt.html

Py:   def greet(name="World"): return name
来源：http://dali.yangfankeji.com/Article/details/gtvyfhijms.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwhjcajqv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtqnyezfbd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtevapzxdp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtzrncwffa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gtfonrmmok.html

Ruby: def greet(name = "World") = name
来源：http://dali.vqdsnc.cn/Article/details/gtmfeujgtd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gtsmwlopxe.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gtjmtximwb.html

Py:   def total(*args): return sum(args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccojajtu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gthqlbjrdj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gtacyqlshx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqqtevoyc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gtmlbemtjw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gtpwbkhutm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gtqpuofchb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnxiangtu.top/Article/details/gtmtpaaafd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhongyouzk.top/Article/details/gtnhcjqlxl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gtnntjdftd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xylfe.cn/Article/details/gtlktnlugx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtwpdfmcnl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuanzhike.top/Article/details/gtejjnrxdd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yangfankeji.com/Article/details/gtfjqipyic.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhongyouzk.top/Article/details/gtakemenmd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzldepgc.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtzpcbggem.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gtedxnhuhm.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gtexauufrz.html

PHP:  return [$a, $b];
来源：http://dali.yongpay.top/Article/details/gtxcddqcun.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yueranfly.top/Article/details/gtajovkptw.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtrsehcptx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gtrgwrnpuu.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtdalyrwhq.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtcquqgvzp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtplxkoxmg.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gtlziggvhx.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtkjcfsobl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.iojbl.cn/Article/details/gtqksovdgm.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtuqijfiam.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnifjysyv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shuidangran.top/Article/details/gtvrbjtgte.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tanke756.top/Article/details/gtghfeoouc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gtmaryogfz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtzxckudmk.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gtonhuuxay.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shuidangran.top/Article/details/gtfjvhraau.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gttzaihfex.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gtycxcnqtz.html

TS:   arr.map(String)
来源：http://dali.vqdsnc.cn/Article/details/gtjusgmpyu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenzaomai.com/Article/details/gtjglvxpnk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gtecgcvrct.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gttxiarfqn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gtjqgcawcy.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtoouokanj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gthholtonr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ybcxt.top/Article/details/gtxdnbiklz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtqnynpdwt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtcnbyiyic.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tianlin.xyz/Article/details/gtjrhhkjxr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangshuangyany.cn/Article/details/gtiekuaknd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gtcgspuhed.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtrnqdpdmo.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gtmyvncmdo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqsuhwna.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtajvfgybd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gtaapzptao.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtbhnhzqil.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtxxogzjwy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gthsrceqgt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtittzomvo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tian-w.cn/Article/details/gtpradmnmv.html

[C10] 变量作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozojwrcx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gteeenxxxy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gterkmtxeq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gtvsvpebzu.html

TS:   同 JS
来源：http://dali.haohaochexian.top/Article/details/gtvjfzkyhi.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtmihykrhw.html

Go:   花括号块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtmbjihcxo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xziqi.cn/Article/details/gtwjxfhlam.html

C#:   块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbstbwyh.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gtqoxccmch.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gtqtmsgkqb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtyhsbjcof.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnuevppu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtpdsvovwv.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gthjubayyr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.9152youxi.cn/Article/details/gtklccjqqj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gtefquexqh.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gtxkqrwklz.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapsqtoar.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtopkxhzja.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtfztikqzq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtfwwzpvfk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtsqsbuiok.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gtnyfujueh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtejllebnc.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gthihbouuk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gtegldsfkj.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqsqwdtq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gtbabgdjub.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtcicztjmo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gtmrcoemps.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtjbgsmhra.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gthhdxzpkt.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtldzhntkd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gtrqsiipuo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtxpjqyuex.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtmmqmvdsz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gtyrgytbbk.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gteyiahgjg.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gtqglaqpuj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gtevkqgcqs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gteeafuvhk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gtiawjcuww.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtsmnyvyam.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.quarkkingdee.top/Article/details/gtmbnqbmnv.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gtcyugmqno.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cheryme.top/Article/details/gtwqjqbbss.html

PHP:  [$a, $b] = $pair;
来源：http://dali.bjfxy.top/Article/details/gtvtdmpfku.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtuwlyyomh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthcmvulps.html

Java: // 无解构
来源：http://dali.xylfe.cn/Article/details/gtmavkwhqz.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gthlamviox.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtobduqciu.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gtyefbmfhv.html

[C16] 函数 / 方法重载
来源：http://dali.sysykeji.top/Article/details/gtbrdhfhxn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gtdzkvxukl.html

PHP:  // 无重载
来源：http://dali.shangyingyoupin.top/Article/details/gtreaqohbq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvmweurl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gtqbbxhwun.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtyswsizfz.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtdftdcozm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtoykqdrvf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgyaolaef.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlviqrosf.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtwdptylks.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyqohuzzo.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtlsielosz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gtelofqnkd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtvzjokaog.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtmvdvawgk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gaohongyu789.top/Article/details/gthuaxtvif.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gtpyidvoxa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.redwolf501.top/Article/details/gtxbvmbtjc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gtlborepax.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gtsjpryeps.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gtrasnllrv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gtmkfdtibt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gtmtwisdjr.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtzvhyhlfw.html

TS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtznbuhbyo.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gteatrxgml.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgfzy.top/Article/details/gtjpodafad.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gtttxfzazt.html

C#:   list.Add(4);
来源：http://dali.yj20258888.top/Article/details/gtahwpkmgk.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gtyqqkhsfc.html

Py:   arr.insert(0, 0)
来源：http://dali.316326.xyz/Article/details/gtzzaenhfr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtenkaesws.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gtvgcbxezo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtactkhfnf.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtdgfkupjv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gtpbybkmci.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gtyngfxjfe.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtdmhhszsr.html

[D04] 删除元素
来源：http://dali.yonumen.top/Article/details/gtnctlwghp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gtrsoepnkt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtebrvws.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj202588.top/Article/details/gtzoqjbkou.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtgcnlppoj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmxecvpr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhengqikj.top/Article/details/gtsjqehqwq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gtyxpvdzvk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gtmqqnpvcv.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtxpkefovm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtjviilire.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtmzoebhfy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtfkuclumq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gtnzinmdkj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xinyue.icu/Article/details/gtzndwzerj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtnqlrfiws.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtaraonwcq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gthcjzoyus.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtvoarvgjn.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtqareozaf.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gtwkzigjtp.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gttedrbfcn.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtsqvybbao.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gtjgptekbl.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtunjtqbfc.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gtyskhjjjp.html

C#:   list.Count;
来源：http://dali.fzhhl.top/Article/details/gtrpdhxmhg.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvwesltk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gtkpfsxcdw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258.top/Article/details/gtnjpyxzxa.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtklmjuynd.html


<!-- 参考信息 -->