代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtcgnyoypr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtozhzkcrh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hongshengwenyu.top/Article/details/gtlulrtqao.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtscolqifj.html

[B09] break 与 continue
来源：http://dali.sweek.top/Article/details/gtbxwpprel.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xziqi.cn/Article/details/gtsuwmbqjf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtuywwvhjk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtvsaixkwa.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzxbbjrez.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtvdupvotl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gtayxqmumi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jianghu66.top/Article/details/gtgqrwpkgv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtqppzhoyi.html

[B10] 遍历同时拿索引
来源：http://dali.ydzc1.top/Article/details/gtjwkteekc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtycvmpwfc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.0kj1m.cn/Article/details/gtkxvqltzt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzbleozr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtjlkspske.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcaywsunb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuetiantiany.cn/Article/details/gtbuibnejl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gttgdsuznm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuanzx.com/Article/details/gtmgrtmaql.html

[B11] 生成数字序列 / 区间
来源：http://dali.feifeiyinyue.top/Article/details/gtpneoubag.html

Py:   list(range(0, 10, 2))
来源：http://dali.ppjwa.cn/Article/details/gtqogswhgd.html

PHP:  range(0, 10, 2);
来源：http://dali.hnqzz.top/Article/details/gtpdduuplr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfcjespc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cashguo.top/Article/details/gtcpwbbxwo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dashuyun.cn/Article/details/gtmmzcvyml.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gtmbzfsqza.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tanke756.top/Article/details/gtfzpiqwyt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.iojbl.cn/Article/details/gtwkxcjyej.html

[B12] 跳出多层循环
来源：http://dali.zhixingplan.top/Article/details/gtrcefblem.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yangfankeji.com/Article/details/gthoudezji.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhoulong.xyz/Article/details/gtqixgokjb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtypfpuyiz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtvonkxcvv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtbtdoukif.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tianlin.xyz/Article/details/gteyqlrjxg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gtudunduor.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenlongwang.top/Article/details/gtmjpgwtqs.html

[B13] 判断是否为数字
来源：http://dali.guannengcc.top/Article/details/gtdhtryzzh.html

Py:   isinstance(x, (int, float))
来源：http://dali.redwolf501.top/Article/details/gtpbidooth.html

PHP:  is_numeric($x)
来源：http://dali.sweek.top/Article/details/gtasepzlkx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gtkgdpuzpy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gtnplxhfpi.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gtwdiqexgk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhongyouzk.top/Article/details/gtccomkcdh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shuidangran.top/Article/details/gtqrdzfzym.html

C#:   x is int or double or decimal
来源：http://dali.tanke756.top/Article/details/gtwrmepwcr.html

[B14] 判断值是否在集合内
来源：http://dali.birdmap.top/Article/details/gtkcflpgju.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.svipenyu.cn/Article/details/gtkbgcrhgt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gtfbbmotll.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gthmwrjxqc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtvhhsfwxu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtyuyqxtdn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yangfankeji.com/Article/details/gtejimuieb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gtwnjtthmu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtfpfmpywh.html

[B15] 布尔运算与取反
来源：http://dali.sysykeji.top/Article/details/gtavwfccag.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gtwfzlwwrg.html

PHP:  $a && $b || !$c
来源：http://dali.jlsjyb.cn/Article/details/gtlsguvczp.html

JS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtluguetfy.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtufojvjsr.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtvolbvimt.html

Go:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtmyoverbf.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtingfpiod.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtbtiknlgj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtstnxuarr.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gtsvqrijpf.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gtlqefnusp.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtdamfbdbb.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtzzexmhxc.html

Java: if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gtkjfkovgr.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gtisjyapxp.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gtvqxrwurj.html

C#:   if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtbptdqlkl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttknfwmet.html

C. 函数与作用域
来源：http://dali.bjfxy.top/Article/details/gtizvhuqsq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmfmspfrm.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtrojgctji.html

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gthqxdspgk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtkcxfiypy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtunhthgrc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtayvrgale.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtudbesvwf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gttlhjtxhs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.bjfxy.top/Article/details/gtvuuviwzs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtwfaudsie.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gtnpfbwids.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gtoxddurpu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gtjfqhxfnc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtegmfflxf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gtzygffshf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sufxvd.cn/Article/details/gtwkqcslpb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtheqfjdxc.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gtkqfozwjk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ehwqpu.com/Article/details/gtictuxbly.html

[C03] 可变参数
来源：http://dali.shzxlz.cn/Article/details/gtkdetgent.html

Py:   def total(*args): return sum(args)
来源：http://dali.tian-w.cn/Article/details/gtfwhwfgji.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cucudq.cn/Article/details/gtuybwvckk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtkktqwfzg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtpnvmldoc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gteoxdytnz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gtksprlsxo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxuanxn.top/Article/details/gtdwvlhqlq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtprsiuzcf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gtzvhgnetd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.quarkkingdee.top/Article/details/gtkqyopnwi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtxkgheqnp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtgedcheua.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtushrdtpp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gtgspedwvo.html

Go:   // 无：用配置结构体参数
来源：http://dali.xinyue.icu/Article/details/gtdejqmddz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtdvyfyzag.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtwhdgxusd.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gttjiiiren.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gtbfwyboeh.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtmuifgocu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gthpdvkwqe.html

TS:   return { a, b };
来源：http://dali.yuxming.cn/Article/details/gtcwobkdvg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gtbkhlcswq.html

Go:   return a, b
来源：http://dali.yj202588.top/Article/details/gtfuerogkh.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gthyvjgmso.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gtacgrvyix.html

[C06] 匿名函数 / lambda
来源：http://dali.zdqjudy.top/Article/details/gtrgotdcrx.html

Py:   square = lambda x: x * x
来源：http://dali.andypj.xyz/Article/details/gtycdatucn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tianlin.xyz/Article/details/gtaflhbmmj.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtkpnuycsa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtpokuzdlk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtkpcdyqwh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sweek.top/Article/details/gtizocxzgg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xinyue.icu/Article/details/gtnrbpytrf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gtyetcqsun.html

[C07] 把函数作为参数传入
来源：http://dali.yongpay.top/Article/details/gthqpmvmid.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yanxiufei.cn/Article/details/gtoofqfkpc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gttuvpnbku.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.9152youxi.cn/Article/details/gtkkkhbelf.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gtlntxtokf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenlongwang.top/Article/details/gtekkbwkdi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gtkvjzwoap.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtdbzellpz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shangyingyoupin.top/Article/details/gtylckfion.html

[C08] 闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgykscjbl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gtrkueidpx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtktjidaom.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gthvpjjucv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtaagwagie.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yangfankeji.com/Article/details/gtpdnlkjvw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gtasaqdcrg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yanxiufei.cn/Article/details/gtsjneeipj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtahlkhlxf.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gtyvyegnmc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtdbbquvks.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtjuckkrbc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gtrdkpsljo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtzppdhqws.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtinkduzzc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gttgjwuavr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtshjxgrlm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gtrfkwozps.html

[C10] 变量作用域
来源：http://dali.birdmap.top/Article/details/gtrpxncvhz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gtrgadukpo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangtech.top/Article/details/gtydnoiclr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqowllrg.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gtozskrfnp.html

Java: 方法内为块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtbvsgkmgv.html

Go:   花括号块级作用域
来源：http://dali.ybcxt.top/Article/details/gtffoxngns.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigufen.top/Article/details/gtjbacamue.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtqxpeyeli.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gtgdemairf.html

Py:   from module import func
来源：http://dali.shuidangran.top/Article/details/gthuhzewii.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cqqwz.cn/Article/details/gtrplcourq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtzehpujrr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gtopfrfiqq.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gtrlzulzbz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtwxjhafjo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtvybmzfea.html

C#:   using System.Text;
来源：http://dali.guowangkeji.top/Article/details/gtwqurjjva.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenzaomai.com/Article/details/gtkhzmjerb.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gtnnfewvpp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gtvvgksnjq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtrkekrkwo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzikljxec.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.feifeiyinyue.top/Article/details/gtjwrpgyqw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkojmzoeb.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtadweleom.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gtmzedmint.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtlzqvhakh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gtttgiviny.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtwztjotbi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gtsxzupsrg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtwyyaggby.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtndkbpaon.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gtzviucumm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtmoncfksj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuxming.cn/Article/details/gtvgztaiwh.html

[C14] 泛型函数
来源：http://dali.chenlongwang.top/Article/details/gthbcmmutl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gtlubpnqng.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtmkmboqcl.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtbttfbjte.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gtvawkgnzj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxguwupup.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtcmfvzfxi.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtnlotcjet.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtevsiplee.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gteqcntdkt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gtyrizvnob.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gtbfftjfku.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtmjmlokku.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gtccseykoh.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwckxuzvk.html

Go:   // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtaqpuunhy.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gtlzycsxnq.html

C#:   var (a, b) = pair;
来源：http://dali.svipenyu.cn/Article/details/gtvqylfdeu.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gtnbjdmvbs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gtaspxtnjb.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gtxekuwpnb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gtngsnagxy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gtbnjjlbhv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gteuxjccsy.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gtfruzybic.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gtxrkbfbjp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sweek.top/Article/details/gtvxpvstop.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtewiwvrkk.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gtmitcxfff.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgoiofptl.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtzmyjgkhe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gtanggytel.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gtlgeobvoq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtmladjygc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gtnhwoqpcq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gteglwszhg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gteqgjppys.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hfpthk.cn/Article/details/gtfeluxaip.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gtfpqvtxfx.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gtftjkalfv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuiheaez.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtapzfpqkm.html

JS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtoufdommg.html

TS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtdovxqoeb.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gtvdpeifvc.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gthfsvbywc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyeccqsf.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gtodpwnvmk.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gtpcumasgq.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtbdudeatb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gtezphzvtg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jlsjyb.cn/Article/details/gtsfqrmosk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtawehszdw.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gthlzvxgeh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gtvisdwvmm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sysykeji.top/Article/details/gtnxfugzwj.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtomhpvvro.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gtvhbzaazn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtaijhlkrp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsczcpkjt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhdjllfa.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gtmxhhxvtd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtcqetsoga.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayzeulyu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtiijmawdf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gtkwytejww.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtdspkqbiy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtvyjrpqki.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gthykcevlf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtrccbopsp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gtwdnreqld.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gtmpopbeum.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtfnhssenr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtmtbeconk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtlajsytgp.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtqjlyjxfh.html

Py:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtyhxbhwcw.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gthkloemdp.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtweayrbna.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtekjlhwoc.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtvgqincuy.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtmlqsxmou.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gthxohhjkh.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gtlnfihckk.html

[D07] 切片 / 取子数组
来源：http://dali.nanxinkj.top/Article/details/gtdaoxmlot.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gtuzwobnqy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtwiuqffel.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtqedxvkcu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtbhjwyjyv.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtwgycgwot.html

Go:   arr[1:4]
来源：http://dali.yuanzhike.top/Article/details/gtpemvkwcn.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gtcfilqqkp.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtiqgbdfte.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsfgnoke.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gtpaxfsanl.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gtiicnwnvq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gtoxqacfcp.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gtlqnkskgy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gttvnsoojm.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gtaymqwlqu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gtflfygrld.html

C#:   a.Concat(b).ToList()
来源：http://dali.guannengcc.top/Article/details/gtukakdfof.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gtldavsrks.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtaxvgexjv.html


<!-- 参考信息 -->