代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guannengcc.top/Article/details/gtyolazqoq.html

JS:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfdgqzxan.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtzvkqdxql.html

Java: while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gthiaapfow.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gotoacloud.top/Article/details/gtiqybujox.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigufen.top/Article/details/gtnxxkbefq.html

C#:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtltmxplpi.html

[B08] do-while（至少执行一次）
来源：http://dali.jiagoushi.top/Article/details/gtbptjoxye.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gogol.net.cn/Article/details/gthpojuqyp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sxryk.cn/Article/details/gtktuiwdwc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gttfmergmw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtyivkxcpc.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtzqrazwdf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuanzhike.top/Article/details/gtwfqmqior.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangshuangyany.cn/Article/details/gtqzhnctpd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gttcukybou.html

[B09] break 与 continue
来源：http://dali.daria6918.cn/Article/details/gtkqplcpkl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shuidangran.top/Article/details/gtfdsovitu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtowtqxdhj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtpdyvahgp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gthqjnqcir.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtysltlkqe.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuanzhike.top/Article/details/gtkffaixmg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hfpthk.cn/Article/details/gttfwtsmei.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtepalkjbm.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxuvplza.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cashguo.top/Article/details/gtgwkryaex.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtggurbcmv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtcctlpqzf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsjkhmcz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jiagoushi.top/Article/details/gtxkfwwykl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteyllwua.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenlongwang.top/Article/details/gtjuoxcvik.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gtwqkwbjtt.html

[B11] 生成数字序列 / 区间
来源：http://dali.aibaodan.cn/Article/details/gtfpthvewk.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgfzy.top/Article/details/gtgnqedwca.html

PHP:  range(0, 10, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtupycyvrt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqenozec.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtpcrzxgir.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtiesmpddl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jyoumei.cn/Article/details/gtvrunajkx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyhzlkag.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pycfn.com/Article/details/gtzlpxsfgh.html

[B12] 跳出多层循环
来源：http://dali.sufxvd.cn/Article/details/gtduciwyjg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdralxfbw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ehwqpu.com/Article/details/gtqawlscdg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtpnxltpxv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtqiqboyld.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtjpklbwzo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdigtkjsq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jyoumei.cn/Article/details/gtbuqsqjke.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gogol.net.cn/Article/details/gtzphpokjb.html

[B13] 判断是否为数字
来源：http://dali.cqqwz.cn/Article/details/gtruntsxof.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwdsatpe.html

PHP:  is_numeric($x)
来源：http://dali.vqdsnc.cn/Article/details/gtbulqvygq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gtogqcrqlg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtckkcnziv.html

Java: x instanceof Number
来源：http://dali.zhixingplan.top/Article/details/gtilpkfzwg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gtxvnlohmz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgcajahl.html

C#:   x is int or double or decimal
来源：http://dali.svipenyu.cn/Article/details/gthisnsscm.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtxocrssri.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gtdtrxexzq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shangyingyoupin.top/Article/details/gtutrytcqz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtluhcndpu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtbjomlyzk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtfayteqsd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fengsongda.top/Article/details/gtuhyukhwg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtlwzpdwdq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtlwdxginp.html

[B15] 布尔运算与取反
来源：http://dali.shzxlz.cn/Article/details/gtiuottlcc.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtyssfawcr.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gttvedyeqz.html

JS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtouwjzwfq.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtmsoiseqf.html

Java: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtrneqzprh.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmrxmkmt.html

Ruby: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtniighwjm.html

C#:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtgasthyyr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tian-w.cn/Article/details/gtwjfjzydt.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtqlxtfwbt.html

PHP:  if (!$data) { return; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpvuoehzj.html

JS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtaqcupaih.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtodgmuhqd.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtfeksciss.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gtfwjhpezp.html

Ruby: return if data.nil?
来源：http://dali.jqgufenzy.top/Article/details/gtdooymhzi.html

C#:   if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtmnwjoijg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcdojrhhp.html

C. 函数与作用域
来源：http://dali.tanke756.top/Article/details/gtvxncupnv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwadwoaeg.html

[C01] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gttsawamem.html

Py:   def add(a, b): return a + b
来源：http://dali.cheryme.top/Article/details/gtndkzkklx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoxjsbjhp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtgbbojzek.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtsryfkuyq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtbiuvoyzr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtzduuygah.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gtgxpzqzbj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtikemktwz.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gtnacsoanx.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gtquittdfu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gtoybzxlzp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gteqkdmufq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtghopgxen.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.iojbl.cn/Article/details/gtdckoasbc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daxiang520.top/Article/details/gtsjmyweck.html

Ruby: def greet(name = "World") = name
来源：http://dali.aibaodan.cn/Article/details/gthsmmwcna.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shangyingyoupin.top/Article/details/gturmjgkac.html

[C03] 可变参数
来源：http://dali.yuxming.cn/Article/details/gtqiivhpom.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj202588.top/Article/details/gtubuqvkxg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gtdcnzcjxm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtljhdxvmz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gtawytrpka.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gtvalxnrup.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gtfttasbhv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gtusdgjdom.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenzaomai.com/Article/details/gtzjosltvs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shzxlz.cn/Article/details/gtmfdpnsnn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cashguo.top/Article/details/gtpbnkcedh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gtuawwgyrj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtgvkpslie.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtfddompst.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gtumiolgcu.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqakojvf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtvyjwyqno.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtorijazaf.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gtcwagmqgl.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtpwwabstz.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gtkewpbqsm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.havefunace.top/Article/details/gtumadfncz.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtdmdfjdqx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkhxsvpu.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gtwrejacoa.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gtklgvekew.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jlsjyb.cn/Article/details/gtgzismuba.html

[C06] 匿名函数 / lambda
来源：http://dali.hnqzz.top/Article/details/gtzbwtrppn.html

Py:   square = lambda x: x * x
来源：http://dali.andypj.xyz/Article/details/gtilmzckyv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gtafrfghez.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtpwaaplxb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.iojbl.cn/Article/details/gtdouzidem.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtkkorffja.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtfmbsfnqw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xziqi.cn/Article/details/gteisgjnmu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtdfgkwwam.html

[C07] 把函数作为参数传入
来源：http://dali.zhongyouzk.top/Article/details/gtykoeemgx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gtysjaxpew.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuanzx.com/Article/details/gtetrhvyew.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gtcprawltx.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gtgwgnlexd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gtsclvwcem.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.iojbl.cn/Article/details/gtwyoibvzk.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gtixaozxok.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnxiangtu.top/Article/details/gthbpdjduy.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gtulsopebc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gtdppxnern.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hammf.cn/Article/details/gtiinjpyoh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtvvgeqori.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtttgmopxe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gtctlpijkc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yueranfly.top/Article/details/gtnrsqcxje.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigufen.top/Article/details/gtjjxbcqxl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtglscfxqz.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhvsiukc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtucffetet.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtmlexpsrh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gtocbpajbp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtifkgnqro.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258.top/Article/details/gtffsxmklh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fzhhl.top/Article/details/gtcyiyoxqd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gteoxisufw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gtpcbxcwrt.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gtbjcixlpc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.havefunace.top/Article/details/gtdrenlmdh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gttznlqlzd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtedgqalbv.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gtpcslsiri.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gtucvahpze.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gtfyjxomzi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gtuzihunmc.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtidkxxzrj.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gtsoezvwog.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gtuezihfam.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigfzy.top/Article/details/gtdtmhbxqr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gtutqhljqh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gtqtpugoyf.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtmkartwiu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xinyue.icu/Article/details/gtbeckhthh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gtaeqbhicy.html

C#:   using System.Text;
来源：http://dali.yanxiufei.cn/Article/details/gtlavzlwai.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtfhuicyby.html

Py:   (lambda: print("run"))()
来源：http://dali.yvedp.cn/Article/details/gtyvbxubxw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gtnuuidoep.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtwrsemqvy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtwqtustxm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gtqyqtdvyw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258.top/Article/details/gtvadtzimk.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gtwteyikyp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sysykeji.top/Article/details/gtvknjcejg.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gtcwzpdmtd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtpruwzbsl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtgbztymcu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenjidiqi.icu/Article/details/gtyanchpzc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtsmrlwrbb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtaengpnde.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gtzcbctbri.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gtkpcrzyep.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtirglxrle.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtaixifzch.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gtjvsaundq.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtdfehfavs.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtogmdjegd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjskergao.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gtydzzydud.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gtujpjfgvo.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gthkzuquvd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinghuilouyu.cn/Article/details/gtaddkqkud.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gtuzhqlqao.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gtdfphfvgr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gtxktwiogi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtnqjpyfyk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtlfbpsxqr.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtyrkvvhft.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtumfjwfjf.html

Ruby: a, b = pair
来源：http://dali.hnqzz.top/Article/details/gtqniumnqi.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gttcczqasz.html

[C16] 函数 / 方法重载
来源：http://dali.zhoulong.xyz/Article/details/gtxntnddtp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gtofyxeefg.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gtpewvliyl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gteuodpqpn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gtfqtfmnmo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gtczzcsowt.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gtlhkjusiu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gthaavchtc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gttsfhnmjq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbuotnonh.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtgnzsfqmk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtavowkqfn.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtgvxfpkuj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gthmdvpdbb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jianghu66.top/Article/details/gtamxcqnjm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gtikpjftbv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtwedtozkh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gtpdapsoaf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtqtbodfsj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gtwgfajdbn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtecaqiwvi.html

[D02] 追加元素到末尾
来源：http://dali.xinyue.icu/Article/details/gtourwrlgi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gtszzyiwpo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtozckvrtp.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gteapwtlcp.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtjldcvowg.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtmvnjslzf.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtfnnlgnwy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gtnaroszug.html

C#:   list.Add(4);
来源：http://dali.gotoacloud.top/Article/details/gtaqajbqdv.html

[D03] 在指定位置插入元素
来源：http://dali.tanke756.top/Article/details/gtcrhakord.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gtgvhzrtwg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gtojjzspjj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gtjhenlwfp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gtaqurcffs.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuauujjbj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtpwldwkgz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangtech.top/Article/details/gttnooivav.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtgvrknkay.html

[D04] 删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtemzmec.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gtutbzezbg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gtsrloudun.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gtgvqkjgcn.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtisrasmxq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gtbsulvztw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtjumcgrpw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jyoumei.cn/Article/details/gtxmpxdocf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gtlalpmtxs.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtggwkosco.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtflnyeukg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtnwdcjfka.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtmzumpylz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gtlpqvdsky.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aizwys.cn/Article/details/gtdaazlvvg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtewgznhcx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtlfbkaqyo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtgtznypnz.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gturvtsotz.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtvlrrgsqg.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtvvpuutls.html

JS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtwmkgecvq.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtwglxnigj.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gtlevtjzhl.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtgivxslsf.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtpgpzlnrk.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gtsacqqjhl.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gtkyxvmdol.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gtbdquxydg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtshqdebcc.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtziffeyhs.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtslzicubr.html

Java: list.subList(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtrneqkylu.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gtdxcwnkor.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gtnttpoeci.html


<!-- 参考信息 -->