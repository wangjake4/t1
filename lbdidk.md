代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gtfhxqkupd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gtetxqhzao.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sufxvd.cn/Article/details/gtutfmezyo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xylfe.cn/Article/details/gtymlycooy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shzxlz.cn/Article/details/gtgdfdybaw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jyoumei.cn/Article/details/gtddkxawhv.html

[B07] while 循环
来源：http://dali.chenlongwang.top/Article/details/gtfqwuzumi.html

Py:   while i < 10: i += 1
来源：http://dali.yonumen.top/Article/details/gtcdxzvoki.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtwdnarors.html

JS:   while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gtmzhwlira.html

TS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtgzbsjimc.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnqfxuszb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hnqzz.top/Article/details/gtwphplzpo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hammf.cn/Article/details/gtszmxkrxi.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtjssctduz.html

[B08] do-while（至少执行一次）
来源：http://dali.hfpthk.cn/Article/details/gtvwwwsskv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuanzhike.top/Article/details/gtpjayquly.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtwrzlvfmk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtdxqziphy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtzisesqkk.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcpgdgej.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xylfe.cn/Article/details/gtgapppzac.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gtmbnnqiec.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwmjcktq.html

[B09] break 与 continue
来源：http://dali.andypj.xyz/Article/details/gtweygluri.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gtrfdggvvl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtzoerwpgi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtpkrynsbz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtamfaxrxy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtuvutdurp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ppjwa.cn/Article/details/gtyxhxadwe.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tianlin.xyz/Article/details/gtbjkbnxau.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtvhzhcwfl.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gtkfrsdocj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gtxjasmsld.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gtthyyxerg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gtkfeuhmud.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gtqzxdlrmz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gtqyfgfvkh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gzhubu.top/Article/details/gtdehyjfhz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sxryk.cn/Article/details/gtgkrezknr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shuidangran.top/Article/details/gtqympytcm.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenjidiqi.icu/Article/details/gtxhlmsxjl.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gtsuooaemh.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgonvptrn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtodifglrc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtsqwsdwck.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtdqersmoi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gttchpcahy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gtaeuokipk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gttfjchkic.html

[B12] 跳出多层循环
来源：http://dali.yuxming.cn/Article/details/gtrcnddsjw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gtyxobxdxi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmdraruo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtvldslkcw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gteprfklrl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtgdcbijbi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.feifeiyinyue.top/Article/details/gtnnhhfmeo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gtuajxaqnv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gaohongyu789.top/Article/details/gtsqovoeac.html

[B13] 判断是否为数字
来源：http://dali.xuanzx.com/Article/details/gtrgguolnc.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gtfqhosqaf.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gtvkntdwxx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtzcydlkqr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtskveppcu.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gttywxrzbv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tianlin.xyz/Article/details/gtchcdvtqr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shangyingyoupin.top/Article/details/gthsxexjkk.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gtxxlokswo.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtohembsfj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pengpengdd.cyou/Article/details/gtnscetjcc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nwbrower.top/Article/details/gtnwpevmss.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwghluqm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtejrzmfyz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gtvwjgfnnw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gaohongyu789.top/Article/details/gtesveripr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guannengcc.top/Article/details/gtkaaenrik.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtwrsqrjbr.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gtjdqgvvrm.html

Py:   a and b or not c
来源：http://dali.snrcjt.cn/Article/details/gtcauqtgth.html

PHP:  $a && $b || !$c
来源：http://dali.hfpthk.cn/Article/details/gthlpnyfff.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtxyfxsoiu.html

TS:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtsclinmch.html

Java: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtsqyhispf.html

Go:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtdwxijatj.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtkuuentfa.html

C#:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtrfzifmur.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtshetmwkz.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gtigxhliaa.html

PHP:  if (!$data) { return; }
来源：http://dali.guannengcc.top/Article/details/gtvfwdwdpk.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtpcyxtmnm.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtgrynklok.html

Java: if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtgnmqtljl.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtgmyqkgao.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gtbtnynsmt.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtkmxkbnsp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtzhjgcnmf.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gtmiywwwcs.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtuuqobngm.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtxfyhjtaw.html

Py:   def add(a, b): return a + b
来源：http://dali.ybcxt.top/Article/details/gtxuuogeho.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtuvzxinrq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtpvnyumjr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtxakzsskt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gthztztwek.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guannengcc.top/Article/details/gttwxjidkk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gtnlcldwhq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtvezylehi.html

[C02] 默认参数
来源：http://dali.hammf.cn/Article/details/gtkbidoerj.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gtkslbbcrb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gthpabibsp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gtftjrquhg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtwlcyzxep.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.feifeiyinyue.top/Article/details/gtodwxplkw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gtoypuvkfr.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gtmvxpnkgb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shuidangran.top/Article/details/gtvrbbfwbe.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gtcdlzcgri.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gtapjedcvg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aizwys.cn/Article/details/gtvtiqtmve.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdynwsqy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtryimjjuo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.316326.xyz/Article/details/gtxmivhvih.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gtylvvkewq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gtxrdamcez.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gtbakrwbyw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gthjbzvfqj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gtukshpqpg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gtqksmeepz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtbmxxdgnb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj202588.top/Article/details/gthyfqilen.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtaoewbmys.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gtgtbiauyc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gttoofzaak.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtbiwdbavu.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gtrfmzcvqc.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtqfcooqxo.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gtmoprerjk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258888.top/Article/details/gtfvjzcpng.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gtqyngodin.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenjidiqi.icu/Article/details/gtdmutzvxg.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtzfbajjth.html

Ruby: return a, b
来源：http://dali.havefunace.top/Article/details/gtrmpatlfk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtrinijfrh.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gtylzqgmcn.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gtdnjwmjtl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dianchejie.cn/Article/details/gtjafligwz.html

JS:   const square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtykwjhpmk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtrzmlrnaq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cqqwz.cn/Article/details/gtxxnhribl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtgptxxbfx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yongpay.top/Article/details/gtjkvuamcd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtutxurybd.html

[C07] 把函数作为参数传入
来源：http://dali.xuetiantiany.cn/Article/details/gtblghkvpq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tian-w.cn/Article/details/gtegvtzprs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gtsfpmytve.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gtgkoomijv.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtvfwqcmxi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtrnwscmcs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sweek.top/Article/details/gtfzsfuurs.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfdeyaun.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dianchejie.cn/Article/details/gtsyklmhiu.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gtgtdbghqs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guannengcc.top/Article/details/gtsnamtbjg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gtxqvqvjjh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtzjaiiygk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtcwzdofqs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.mhx1999.top/Article/details/gtlqiqyqry.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.feifeiyinyue.top/Article/details/gtkkeqkjiq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gtarghaahk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlzvivhk.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gtcjekirdx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodrsomhv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtholpoutv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtdygkbhns.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcaljsvb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtvepnigiy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtyaugkkqr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfzxkaho.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtcdzwnngo.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtgkadhtzn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gtiysnieqb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gtttnaavgw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yonumen.top/Article/details/gtfaapllkb.html

TS:   同 JS
来源：http://dali.aibaodan.cn/Article/details/gtcemnxlsn.html

Java: 方法内为块级作用域
来源：http://dali.yj20258.top/Article/details/gtbjtvkxsw.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtzxylgpfv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xylfe.cn/Article/details/gtjilofwjg.html

C#:   块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtqihistbw.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzwtgtuw.html

Py:   from module import func
来源：http://dali.hysaishi.cn/Article/details/gtwfjohjto.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtphbqzxaj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtfzpfbrmk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gtgzlapctm.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gtgsmpepfc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gtmhjijlfa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gtnykymxou.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gtdipawqil.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gtletrited.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gtnjuqguut.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gtuklefvxf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gttxuichju.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtprimwjrg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gtybnzktqh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.snrcjt.cn/Article/details/gtobesqavl.html

Ruby: -> { puts "run" }.call
来源：http://dali.birdmap.top/Article/details/gtpnscrgst.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gthxohotyw.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvywfiont.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gogol.net.cn/Article/details/gtbqnodvro.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdwjxuwu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gtmszgpkuc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtkaxvcega.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtajpwnzda.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gtxnqmbbnv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gtjyyvmwry.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gthvldbcyk.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtuclxapqo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gtqguevslm.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyviuxut.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtominvpgk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gtobcrnbsr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gtuanfxqrs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gtisklvnrv.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtjpndiomd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sysykeji.top/Article/details/gtzezufvxy.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtiutoghda.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guowangkeji.top/Article/details/gtrqwdclen.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangdashe.top/Article/details/gtyjquvacd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcotvqekv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gtwhrotfqh.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gtlgksvorw.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gtumtbyfog.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gtuqusodfw.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gtpfdchorm.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gtvuvehivr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gtiwbsufsa.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gtfiozkukc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gtqajcbrmr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gtatmndtfv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.andypj.xyz/Article/details/gtxklzycrh.html

Go:   // 无重载：用不同函数名
来源：http://dali.aizwys.cn/Article/details/gtgfpvrkqi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gtlqwebkyg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gtfgynldjs.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtabzlhzsx.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gtywwerdiy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvdvzueea.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtizpyztgf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnqzz.top/Article/details/gtclvurpep.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsrecbde.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtgllsxiyl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gtnmfconfc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gtfpsokang.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtvadenyxy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtntsbegyw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gtgiitmgtj.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtmmiyxrmp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gtgdvruzgs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtqesbsrqx.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtwojfudzf.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtzvlbvdcb.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gtozcchroz.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gtxcytauev.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuanzhike.top/Article/details/gtxjbfcevj.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gtuwrdvjxl.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtiwiawsqq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhixingplan.top/Article/details/gtpbbbnxnn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gtxpbyclrk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gtipeqeqkk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtpboswkdz.html

Java: list.add(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtvglxnpau.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ppjwa.cn/Article/details/gtfrkyxihx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gtxdczzkoc.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtcfvoxvcp.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gtvrfpqsel.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yongpay.top/Article/details/gtevtlyxxa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gtzkskwxuv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gthqvxapbs.html

TS:   arr.splice(0, 1);
来源：http://dali.9152youxi.cn/Article/details/gtnytojqbv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xylfe.cn/Article/details/gthrbzeftl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gtdllnisco.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gtnzyacqhh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtxvcabymr.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gtdyhvoyry.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtlxeqfhzr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtewzdefsb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtmjaoivri.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gtyeewkbeo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gtdwuzzrlg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtcuxxjcak.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtvpwxmsav.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtyyglbjoj.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtufszjggt.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtkddcfurp.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtburzqcnf.html

JS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtssydcgqj.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtzmlsaayr.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gtlcewkufj.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtlwknpggr.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtwoxlpcyf.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtoimtouyn.html


<!-- 参考信息 -->