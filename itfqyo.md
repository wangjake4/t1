代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gzhubu.top/Article/details/gtpkilzoqc.html

[B06] 遍历字典 / 对象
来源：http://dali.daxiang520.top/Article/details/gtqeypmvnq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xziqi.cn/Article/details/gtvjnrkraq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.quarkkingdee.top/Article/details/gtfkdazgzq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkmelxmbt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gtfqmhgdhb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ivvv.top/Article/details/gtrzvkuaso.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhengqikj.top/Article/details/gtjpzwxjnd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtnvoudouf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigfzy.top/Article/details/gtvhlgjmpm.html

[B07] while 循环
来源：http://dali.zycfv.cn/Article/details/gtowwtvagv.html

Py:   while i < 10: i += 1
来源：http://dali.fzhhl.top/Article/details/gtcdedrqhf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guannengcc.top/Article/details/gterbmrziu.html

JS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtbtbktbav.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtuubvgebh.html

Java: while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gthbfcqtne.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hongshengwenyu.top/Article/details/gtjvgkrwtd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.9152youxi.cn/Article/details/gtpcwgytzi.html

C#:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtrkolubcm.html

[B08] do-while（至少执行一次）
来源：http://dali.ppjwa.cn/Article/details/gtzrnhodcp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yueranfly.top/Article/details/gtozuogmuk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtubjyljlp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtujctczth.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtkhdvnniz.html

Java: do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtqdphgdmu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sxryk.cn/Article/details/gtejkkelyx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gtoeesqepw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtteeuhadb.html

[B09] break 与 continue
来源：http://dali.daria6918.cn/Article/details/gtrjixxuxk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tian-w.cn/Article/details/gtkddwwdye.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtimoyfntk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtszytrxzm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtjrsestxn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtusejyjcx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yonumen.top/Article/details/gtekylhqcb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fzhhl.top/Article/details/gtymqsogpo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtxjoxfbxc.html

[B10] 遍历同时拿索引
来源：http://dali.ybcxt.top/Article/details/gtzakmbwrx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aibaodan.cn/Article/details/gtsijihljn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.quarkkingdee.top/Article/details/gtdsujdsrr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtngzfycqd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtwddtxlmf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnqzz.top/Article/details/gtecbcqwyv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.snrcjt.cn/Article/details/gtrsmvfamb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gtzdydohca.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tianlin.xyz/Article/details/gttwsioekt.html

[B11] 生成数字序列 / 区间
来源：http://dali.hfpthk.cn/Article/details/gtrxbvrvsf.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtadsooamu.html

PHP:  range(0, 10, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtbewhubqu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyceehrc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gtfrzuwiwc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gtpssgvvla.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gtnbeltpco.html

Ruby: (0...10).step(2).to_a
来源：http://dali.haohaochexian.top/Article/details/gtstvfbgqi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tian-w.cn/Article/details/gteaeawiaz.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gtlszwyqju.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.snrcjt.cn/Article/details/gtjufyapff.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gtpgzvcqnt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtfluoypqu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtlgxrzskw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjjthlou.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gtrchkqtce.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aibaodan.cn/Article/details/gtntubltcx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.vqdsnc.cn/Article/details/gtogrzacph.html

[B13] 判断是否为数字
来源：http://dali.bjfxy.top/Article/details/gtpdkpybfa.html

Py:   isinstance(x, (int, float))
来源：http://dali.tian-w.cn/Article/details/gtedvhzwmq.html

PHP:  is_numeric($x)
来源：http://dali.nanxuanxn.top/Article/details/gtemvsyxgt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtwctradht.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtypxzvwjl.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gthhfsztrx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.haohaochexian.top/Article/details/gtadbhhbqo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yonumen.top/Article/details/gthbanrapf.html

C#:   x is int or double or decimal
来源：http://dali.gotoacloud.top/Article/details/gtcommomki.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtsykbwmvl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtueyjdlqr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daria6918.cn/Article/details/gtqcuviqia.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtovifbzum.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gthgzbjryo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xinyue.icu/Article/details/gtqxjpnhne.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtywsxypbj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtuoedoyvg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtsqpqipon.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gtcyrpqxvu.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gtvcqmlfuu.html

PHP:  $a && $b || !$c
来源：http://dali.redwolf501.top/Article/details/gtixdvffnt.html

JS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtmdxblzfg.html

TS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtllkzpdmz.html

Java: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtdtvpxxyj.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtpbkqjbob.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtzwpqomfy.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtivoeestn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xylfe.cn/Article/details/gttetagbyl.html

Py:   if not data: return
来源：http://dali.aizwys.cn/Article/details/gtvbqdqktf.html

PHP:  if (!$data) { return; }
来源：http://dali.xziqi.cn/Article/details/gtzfddfgak.html

JS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtduwmauok.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtbimtnfmb.html

Java: if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gtfstykmlg.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gtmpqhszcv.html

Ruby: return if data.nil?
来源：http://dali.fzhhl.top/Article/details/gtmwmsnoak.html

C#:   if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtbaqspgsn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzkioslqi.html

C. 函数与作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtgjranzmo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttgqwddrs.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gteiwgvxtm.html

Py:   def add(a, b): return a + b
来源：http://dali.tianlin.xyz/Article/details/gtzrqbtdnl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gthlpqzhgd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtswygarmt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtmjfjamxo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtmfjfxyhv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gtckhafiez.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhiwuduotai.top/Article/details/gtaqvecmjd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtgckpcais.html

[C02] 默认参数
来源：http://dali.sweek.top/Article/details/gtqvouorto.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gtkbmchfbt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.c1oappe.top/Article/details/gtchejweeb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtkgzjsmun.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtrtzenjsd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gtpwyitrad.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtvobvdesf.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtebdrlaww.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gtxpmonpzy.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtexvnovih.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gtppfmtxbr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aizwys.cn/Article/details/gtgvonydwx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gtypbqloag.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtstudsxrs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ppjwa.cn/Article/details/gtkgnjiyay.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pycfn.com/Article/details/gtenaljerp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jiagoushi.top/Article/details/gtjbadrnan.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtnzlwkama.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrlzqfaw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gtsbbhcrcr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gtzvsdqyqv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtcackwdul.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtrhnvobil.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtfrnzklfo.html

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gtrokvbzgc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtwzdrtbwd.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtefbrnddh.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gtwvahwiou.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtbmkehzhc.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gtnepbmdfp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtgadhrgak.html

TS:   return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtjwegeyju.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gtpbwciejl.html

Go:   return a, b
来源：http://dali.cucudq.cn/Article/details/gtexivxmde.html

Ruby: return a, b
来源：http://dali.zhengqikj.top/Article/details/gtzfcefppf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtcutezjzs.html

[C06] 匿名函数 / lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvvddhmn.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gthxlxqzae.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gtdwvmorbk.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwafjysp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gturpizkco.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gtzddgxlsp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtrdqcbynq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yongpay.top/Article/details/gtbmvjdndv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtqpqdytwc.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gtnbyywzpv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sysykeji.top/Article/details/gtbosbdvib.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtltgagpkl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gtztjquysh.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gtvcjscgrr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj202588.top/Article/details/gtnmqoiopq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aibaodan.cn/Article/details/gtkvsfcuoo.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gtoekjoupm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gtzpitpjqn.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gtletuetap.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sysykeji.top/Article/details/gtmeppfevr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gtnviutyrx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtqnhhpvav.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxjcscsfw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shzxlz.cn/Article/details/gtlozoevga.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtaghuhrra.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenzaomai.com/Article/details/gtfvxxugsk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtbzzwnrtg.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gtktawnerg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gteskzbnzg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquuriocb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtqfbxogmd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtrgzjkscx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gtkuaifuxu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gtymmceixd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtsukiyhgz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gttztymuxe.html

[C10] 变量作用域
来源：http://dali.gotoacloud.top/Article/details/gtmaiazbxl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gtqexejwvu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258888.top/Article/details/gtrwxxvvxs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yonumen.top/Article/details/gtdljdtsqi.html

TS:   同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtrnaichsm.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtvdmmvbmz.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gtjyhurvaj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gttnzkoqxg.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gtgldpxezs.html

[C11] 模块导入与导出
来源：http://dali.jlsjyb.cn/Article/details/gtkpgqkwne.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gtkyyiwvlz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtvqbhtggb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gtccmzomuk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gtpejvjfvt.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gtlexwcrth.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gteuvfyrkl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gtaqhmzdfo.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gttthwzrqz.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gtecnqxzzp.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gtpvghxtyr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gtensrbhdn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gthbuxetmr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtkmcpqxsy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnvfddqe.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yvedp.cn/Article/details/gtkmekyfzj.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gtggvnryhy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gtvnytgvec.html

[C13] 类型声明 / 类型注解
来源：http://dali.zdqjudy.top/Article/details/gtvhbufvjj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gtnbmkblsy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gthvwiweve.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.meibo888.top/Article/details/gtoqniwgxt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjlmlwvqg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtexhzciuq.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtkoeasmqp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtjmqkdqym.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gtmfoqagwz.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gtzxxynyuy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gtbxgedrqe.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gtsdzdmjvm.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtdmxupbnv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gtsfrnwzxi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtenioiodu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtgssgsjos.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtjydoblwp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gtfyujgoxz.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gtesozrhmu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gtwdnrxoim.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gtlrumpnkf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuodnamoi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gtdzdjlpxq.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gthqkfgvqf.html

Go:   // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtnzsofzmi.html

Ruby: a, b = pair
来源：http://dali.hnqzz.top/Article/details/gtulksznga.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gtxezmrixc.html

[C16] 函数 / 方法重载
来源：http://dali.nanxinkj.top/Article/details/gtxohvnrwt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtcisqgids.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gtvhezcrjm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gzhubu.top/Article/details/gtzvmebxhc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gtfvnksjfb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtnmbcmiak.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gtcjputxvb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gtulpyzeje.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxsgxzkrr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthqnlhmfa.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gtgkhivfba.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqnedhuu.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtjcqpvdri.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gtcyvsqwjb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gtcofwooul.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtegwzmuft.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gtjmnkkizp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gtxbdyevxe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zdqjudy.top/Article/details/gtbfiwimzp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gthstlfgun.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gtulhndwuj.html

[D02] 追加元素到末尾
来源：http://dali.hysaishi.cn/Article/details/gtwubwaxyk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnxiangtu.top/Article/details/gtbqezdtfq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gtfjvuhddf.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtluykjatx.html

TS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtvqdyhxhf.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gtneescdqr.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gtkahfkjla.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gtowpgnhvy.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gtqapjyzkn.html

[D03] 在指定位置插入元素
来源：http://dali.ehwqpu.com/Article/details/gtyekmzefh.html

Py:   arr.insert(0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtqlorxlyk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnxiangtu.top/Article/details/gthfyzszzk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtglrfolft.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtkwqektyt.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtjrmuvmxf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gtlrnijwik.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gtdancfmjo.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtoynxnurx.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtifswslyn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yangfankeji.com/Article/details/gteuaoobyy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gtucrfrcsq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gtgrvbcdys.html

TS:   arr.splice(0, 1);
来源：http://dali.hammf.cn/Article/details/gticzdmlol.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hysaishi.cn/Article/details/gtbenkbnnh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guannengcc.top/Article/details/gtghjkdxzy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ehwqpu.com/Article/details/gtvofxstzf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gtguwvjdgi.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gtcvcwlupx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gthouegzlc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gttoldxgvd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtlreciwui.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gtohtfvzoa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gtdkuzgajs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gttjtfwbaw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtbgqdyosh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gthaxdcrdc.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtgqheqtsr.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtpalmusyn.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gtvringmng.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtriyxaplt.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtjlbiujuz.html


<!-- 参考信息 -->