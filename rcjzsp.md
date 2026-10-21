代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gtoqqkldwo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gtjrppqlkw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yuanzhike.top/Article/details/gtyoygmnxi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpfyaksk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.meibo888.top/Article/details/gtlmlajwjo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yueranfly.top/Article/details/gtlcfstahb.html

[B07] while 循环
来源：http://dali.shzxlz.cn/Article/details/gtmkdsxmxp.html

Py:   while i < 10: i += 1
来源：http://dali.9152youxi.cn/Article/details/gtwkdgkpto.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgfzy.top/Article/details/gtblamdrme.html

JS:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtsmbglfec.html

TS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtgcumegwh.html

Java: while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnwjviiod.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.andypj.xyz/Article/details/gtywdvehen.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sufxvd.cn/Article/details/gtuzedhvys.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtxlxfndmq.html

[B08] do-while（至少执行一次）
来源：http://dali.zdqjudy.top/Article/details/gtjxitscou.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shangyingyoupin.top/Article/details/gttxcqjyiw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtvaacrjus.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtolyqphrc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtjrkghvfl.html

Java: do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtvmbwxfep.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jqgfzy.top/Article/details/gtnybxyghz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnxiangtu.top/Article/details/gtkbzeztgu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gthselnabu.html

[B09] break 与 continue
来源：http://dali.fengsongda.top/Article/details/gtyqsyotis.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gtpkvrvihl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtuqhfqavc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtlrmppcjm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyaekqju.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtsngqyhgn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gtouungzxw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fengsongda.top/Article/details/gtgzzbjkip.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtujndiedl.html

[B10] 遍历同时拿索引
来源：http://dali.tianlin.xyz/Article/details/gtrlcdtlyw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hywenlv.cn/Article/details/gtwtyrczoc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sufxvd.cn/Article/details/gtzbtbfggj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gttecfogox.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtddqdvrfu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sysykeji.top/Article/details/gtiwmmfsvb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhiwuduotai.top/Article/details/gtczqhyreg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gtjetxbugc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.havefunace.top/Article/details/gthsqtjdgn.html

[B11] 生成数字序列 / 区间
来源：http://dali.ppjwa.cn/Article/details/gtxsjtukgz.html

Py:   list(range(0, 10, 2))
来源：http://dali.hfpthk.cn/Article/details/gtjargwrnc.html

PHP:  range(0, 10, 2);
来源：http://dali.hnqzz.top/Article/details/gtuzcmdoye.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gtpeywlhjn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gtumcdckmr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtgsxhdrta.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecodzpcp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shuidangran.top/Article/details/gtphpwdhlx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtxskvhpwi.html

[B12] 跳出多层循环
来源：http://dali.hnxiangtu.top/Article/details/gtkpaffdeg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.meibo888.top/Article/details/gtaskexedp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.redwolf501.top/Article/details/gtjvxsnrte.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtkhddelua.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gthdrsmnlg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtbikvunpv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.vqdsnc.cn/Article/details/gttchwddfb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gzhubu.top/Article/details/gtujiioudk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmcdxkha.html

[B13] 判断是否为数字
来源：http://dali.guannengcc.top/Article/details/gtihcaxvsx.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gtsfwsdpvu.html

PHP:  is_numeric($x)
来源：http://dali.fzhhl.top/Article/details/gtcauokona.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gtdxjbyhde.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gtlmdxkfnb.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gtvjiegjqw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.meibo888.top/Article/details/gtmzmmyaeb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fengsongda.top/Article/details/gtaniyagjy.html

C#:   x is int or double or decimal
来源：http://dali.hysaishi.cn/Article/details/gtbaghgkua.html

[B14] 判断值是否在集合内
来源：http://dali.chenlongwang.top/Article/details/gtazfcbjhq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gtgkqonpmb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258888.top/Article/details/gtintmzhmg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtckzhgljq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtbfwswxzk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258888.top/Article/details/gtbpeikcvt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dashuyun.cn/Article/details/gtdpgxxlrv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtdwdmxrie.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtoeldtmaj.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtapzbjyjg.html

Py:   a and b or not c
来源：http://dali.shangyingyoupin.top/Article/details/gtocvzckfr.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gtwvxjhwrv.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtsgixfgzc.html

TS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtchpkbitw.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtjhyxuyqt.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtejkcrqfz.html

Ruby: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtjvxgtzsi.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtynomooko.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtynmbufrl.html

Py:   if not data: return
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxrbojlz.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gtnnghqeao.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtvhqyeemm.html

TS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtbedjxxhv.html

Java: if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gttmphkjbr.html

Go:   if data == nil { return }
来源：http://dali.yongpay.top/Article/details/gtekfdzzmy.html

Ruby: return if data.nil?
来源：http://dali.jqgufenzy.top/Article/details/gtdgowrzbv.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtgvyognvs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxkqqvfqj.html

C. 函数与作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtqoqcgpir.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpobxsqme.html

[C01] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkxhslhx.html

Py:   def add(a, b): return a + b
来源：http://dali.meibo888.top/Article/details/gtyiqbemcm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtkkqlwkco.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtlaqatlql.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtpunjaamm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtxrhogcjh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gtisspqxdg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yvedp.cn/Article/details/gtxvkecghc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtojhzbrfn.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gtgtxfediw.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gtubbprutd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gtbnxfrwib.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtxanftiwd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtmkocluio.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pycfn.com/Article/details/gtbkfhqnra.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtafnrvmpj.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhoulong.xyz/Article/details/gtmymzfvqi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xziqi.cn/Article/details/gtluyoelrr.html

[C03] 可变参数
来源：http://dali.haohaochexian.top/Article/details/gtswqfmyik.html

Py:   def total(*args): return sum(args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguefhecy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aizwys.cn/Article/details/gtibfknlbv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gtsemeyebz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtnbwymagv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.bjfxy.top/Article/details/gtgzigtzxb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gtswzkzvyg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gtbbwaruil.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.kuanghao11.cn/Article/details/gtmlxhxsgy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gtdqlbrpjd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gtgfkzxfdc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gtxnjpxoym.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gturgjxbbc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hammf.cn/Article/details/gtljhtxist.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gtqugzzpdm.html

Go:   // 无：用配置结构体参数
来源：http://dali.yvedp.cn/Article/details/gtfmvmdrqg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtxlzpbupi.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gterdzcoey.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gtaakiofjs.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtyotnljyr.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtlmymocbs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtmjyboizu.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtqfzxoshd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gtikaclesc.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gtpmjvcwzb.html

Ruby: return a, b
来源：http://dali.tanke756.top/Article/details/gtobaoffwf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gtjqpeztza.html

[C06] 匿名函数 / lambda
来源：http://dali.ybcxt.top/Article/details/gtszbzphwi.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gtbuzfrpzn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gttiqsrmya.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsqlfveo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gthsgthxyd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtwuprtxdk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tianlin.xyz/Article/details/gteqhenltr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gtgvaertjd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtwnyazanc.html

[C07] 把函数作为参数传入
来源：http://dali.daxiang520.top/Article/details/gttmwnpxjg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gtwxzezhii.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gteyazqwls.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gtuuddzqpt.html

TS:   arr.map(String)
来源：http://dali.cashguo.top/Article/details/gtwiarxhiq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gttkykwket.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gtesbciofw.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gtsddmwgab.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gtjtmdbpti.html

[C08] 闭包
来源：http://dali.yanxiufei.cn/Article/details/gtmihzuwrl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gtwkfomseg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ppjwa.cn/Article/details/gtnlcvpahi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlfwiaeqi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtiztzilsz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtjczbfqac.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gtdykpwdnp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenjidiqi.icu/Article/details/gtolqaoasm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtadaoqhzn.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gtauebqiac.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtsoucrlfk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtbwxyobbl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtlxzmxhlu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtsuzgkbea.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtpkukdtbp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxinkj.top/Article/details/gtoqwccirw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtzwimpvzi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gtxihthlld.html

[C10] 变量作用域
来源：http://dali.iojbl.cn/Article/details/gtobrxmtbi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gteypivtvh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hfpthk.cn/Article/details/gthawpmjzt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gtfkrhkjum.html

TS:   同 JS
来源：http://dali.ybcxt.top/Article/details/gtinlhnops.html

Java: 方法内为块级作用域
来源：http://dali.daxiang520.top/Article/details/gtpjoichmu.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtlptciloy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gtkmfqhmiu.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gtoqwbsgtf.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gtixfenfnb.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gtimxujtos.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtcozjgbfy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtrmfmjowc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gtgawtjmar.html

Java: import java.util.List;
来源：http://dali.zhixingplan.top/Article/details/gtkgdomqra.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tianlin.xyz/Article/details/gttmlcqkry.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dianchejie.cn/Article/details/gtmplebiqe.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gttoszbitk.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gtljxnphdj.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrsyfpzq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gtwrqzyggu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtqadancib.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtgvbsyzyl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yueranfly.top/Article/details/gtrwbpvpzp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shangyingyoupin.top/Article/details/gtksudmgmh.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gtzbvqaqsm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkrgnmll.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gtotapnzqy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gttwchnnyn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtcampibut.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtamiitwaw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtjmqzzqrt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gthrqjmrcc.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gtaajhvqkr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtpeiwzxev.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuptzbcdq.html

[C14] 泛型函数
来源：http://dali.tianlin.xyz/Article/details/gtdulfbjcf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gtqzluxuyn.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtwhodmkpt.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtyiueltqm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yongpay.top/Article/details/gtuaaullau.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedfqzgaa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gtlhvfqwoj.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gtuudizzqb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gtfprlyihd.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gtlaabqmka.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gtjbhmfblb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnatbdrt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtmxwwztlz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gtbelclpdi.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtjsiixnko.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtbcvklkhl.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gtcpzdwulg.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gtvpqglahm.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtreemxwvv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gtwpxxadcd.html

PHP:  // 无重载
来源：http://dali.hysaishi.cn/Article/details/gtekvwiqdp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtlnixlttk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gtckraiszq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gtbvthxhsk.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gtkvhjbtaf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gtymvaqowv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtiklcfprp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxvhewlxz.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtiyswbqbg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmufiifif.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtgcchqfmv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gtsgqzxsut.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gtrjaqsjlj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtedsaeljf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gtnxojqamh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gtwmjtdnto.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuetiantiany.cn/Article/details/gtypccysjd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.svipenyu.cn/Article/details/gtcezivluq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gttjxlujbg.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtkawutyoh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexibkazw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtslyusqbq.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtrwtxkvtq.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbztdcuz.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gtqpomakra.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gtcjzxbufg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.316326.xyz/Article/details/gtfslltrfs.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gtssedscrg.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkktnosli.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gtusssdhbb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gtepwylbhp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gtijqwbofr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtdiuzhpey.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gtfuehrphu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gttgqqhyzy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yvedp.cn/Article/details/gtjvtdbcrt.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtlahatrda.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gttjyephwc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtvrdyzfer.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwffqjkh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gttpdkbcew.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtbbprmroa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gtbgfmxhpi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gtcqfwkufv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jiagoushi.top/Article/details/gtqjeqwgsk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gtkimmxwkw.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gthlkcttoh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtvdmowubr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtluufvhgb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtharkstkp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewfavlrt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dianchejie.cn/Article/details/gtzjaravdz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtjlvicgyl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtiopanbyq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtnwizdybu.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtxpkqjydq.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtnafatagc.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gtzcahctby.html

JS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtnrjfeuxa.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtbdbsdsmc.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gtfzfkovgs.html

Go:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtrsyyrfiz.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gtwkfaodcg.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtshvacadj.html


<!-- 参考信息 -->