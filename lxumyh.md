代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hongshengwenyu.top/Article/details/gtqgundxay.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ydzc1.top/Article/details/gtpyixzegj.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtypcluwyh.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gtqlqvtlep.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gtpaxstbgi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtyjbczilm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtgqzhibvm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtjqjazdpt.html

Java: do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtlqutirbe.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtniimapjy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gtrpmsigey.html

C#:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtuhulgprj.html

[B09] break 与 continue
来源：http://dali.meibo888.top/Article/details/gtcwyyakjx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj202588.top/Article/details/gtvkuzuanx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtukkecgsz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtltlbdpmx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gttxuzwkgt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtykwjkdzz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gtrbbnjcyf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shuidangran.top/Article/details/gtnkhcosmd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxnsefcuf.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gtkeuuwaoi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tianlin.xyz/Article/details/gtgofmxfss.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sufxvd.cn/Article/details/gtzywygzec.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gtgagergpy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtqfuvkxfy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gtednhwuey.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxuanxn.top/Article/details/gtxksvtxyw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tanke756.top/Article/details/gtwhqalbfd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tian-w.cn/Article/details/gtuyziaapt.html

[B11] 生成数字序列 / 区间
来源：http://dali.hongshengwenyu.top/Article/details/gtakgtgzch.html

Py:   list(range(0, 10, 2))
来源：http://dali.ydzc1.top/Article/details/gtfzbjxelj.html

PHP:  range(0, 10, 2);
来源：http://dali.316326.xyz/Article/details/gtmtghlhwo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.9152youxi.cn/Article/details/gtgohfuput.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulwrccxx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtplawwvrm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangshuangyany.cn/Article/details/gtojqbnfhq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnqzz.top/Article/details/gtfmbnzsbs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guowangkeji.top/Article/details/gtbqeusgua.html

[B12] 跳出多层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtqyrmzhir.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gtejorgmoj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gtrqkhzdml.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtbeisntib.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gthwjrbufl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtqqpcwnci.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yangfankeji.com/Article/details/gtnadvesjk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gtqyqgtcpq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gtbctzvhvq.html

[B13] 判断是否为数字
来源：http://dali.nanxinkj.top/Article/details/gtnrvvitsy.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gtcjnuwouw.html

PHP:  is_numeric($x)
来源：http://dali.ydzc1.top/Article/details/gttkikmtoq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gttwdqcmau.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gtmuhhgown.html

Java: x instanceof Number
来源：http://dali.yj202588.top/Article/details/gtlfnrvgfj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgufenzy.top/Article/details/gtapwlmcfa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tianlin.xyz/Article/details/gtlinpwlxt.html

C#:   x is int or double or decimal
来源：http://dali.zhongyouzk.top/Article/details/gtlvbcouhb.html

[B14] 判断值是否在集合内
来源：http://dali.birdmap.top/Article/details/gtqkvwlqzt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yangfankeji.com/Article/details/gttzlydvzk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangshuangyany.cn/Article/details/gtxxwjzwjc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gttqvklpzz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtanyilusn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtmcadigyn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fzhhl.top/Article/details/gtmwtufyai.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtxpsiwjgm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtmabzmkzl.html

[B15] 布尔运算与取反
来源：http://dali.yj202588.top/Article/details/gttwiztpjz.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gtofwsuuco.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreqfowzl.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtxmjbeydt.html

TS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gttcikyxar.html

Java: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtzjkpozsv.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtjampitgw.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtpwyogfcg.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtimwofwiu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ppjwa.cn/Article/details/gtuwmsejom.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtvehaktej.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gtofapaqkc.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaqfgqpi.html

TS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gtbcdbtzap.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtlpxdcryj.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gtgqwqrqlc.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gttrusfxii.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtbmuylmzr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtznngmmwv.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtrzaxpjdo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqusdbeky.html

[C01] 定义函数
来源：http://dali.yuxming.cn/Article/details/gttzypmylj.html

Py:   def add(a, b): return a + b
来源：http://dali.yuanzhike.top/Article/details/gtiegxewuj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gthynobyjf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gthjtdyyll.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcewjytpe.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtpacefxnj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gtswpyudgt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenzaomai.com/Article/details/gtkqareknv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtdqdsgofm.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gtwquohhsk.html

Py:   def greet(name="World"): return name
来源：http://dali.zhoulong.xyz/Article/details/gtssbvfqvw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtoeyuoqvs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtdfuwtwgf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtbpeftepn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gtzxhlmtbo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pycfn.com/Article/details/gtlphefcxu.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gtyomzwlxu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gtwtrlhfrk.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gtclpcjfha.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgzfyhki.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.havefunace.top/Article/details/gtokgybvfv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtgwvgtdlv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtjaahuweu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gzhubu.top/Article/details/gtzaoypgvy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gtbagerrrq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gtijxebsnb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gtnaribocx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gtlaoqyyvu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtnllkqwiz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gtdgviksoj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtemkabgar.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gtxboivvsy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gthecjdqdv.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtkpampqjo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtaqsotxah.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtkqngwwfn.html

[C05] 返回多个值
来源：http://dali.vqdsnc.cn/Article/details/gtixqlbzqv.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gthfbguukm.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gthqazguhz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtssolufgm.html

TS:   return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gtvvveulta.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gtthreaqim.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtuymprlay.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtcxjdupxu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gtezoyjdea.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gtmciwsqrv.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gthhntfrmz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gtjtpvlpuv.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtyupijhvg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gtatbmwqte.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gtkqbykjgo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gtxumjwabg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xinyue.icu/Article/details/gtesdhwjbu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtkagqwhno.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtrdnhmjml.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gtvqlkfahm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuanzx.com/Article/details/gtgifkxhfy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gtifgzwukd.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gtvablopek.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gtxmyoplqx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gtqlqrnjkv.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gtqxdpcmdb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gtcatjxraf.html

[C08] 闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtasmrtpcs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcitoity.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtxtwsmjax.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtbgzwvvve.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtoholmtes.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gtimrsnixj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xylfe.cn/Article/details/gtsetimgjb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenzaomai.com/Article/details/gtbazwxtlk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtgnxwcspd.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gtxnugoada.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtxtcgjijl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtaibtirxx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtwccsmdff.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtsdivozts.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdhjuuyph.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigfzy.top/Article/details/gtazrmamwn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtalanqgbd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigfzy.top/Article/details/gtlxjioljt.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gtmrzjcmxx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gtvfwadmzn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangshuangyany.cn/Article/details/gteufshufb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gtstabuudj.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxzwcrqi.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gtqekwogfo.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtwlnznntx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gtkiqwjgqu.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtjyyymsed.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gtyyhycbwu.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gthobkewys.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gtpxqiufbm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtjgzzvyjb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gtdtvgffkk.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gthiasaxjx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gtahdaprss.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gtsbhjurni.html

C#:   using System.Text;
来源：http://dali.birdmap.top/Article/details/gtdqkhioxv.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gttzjepqkh.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gtmgxztzfa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtuylpwuvn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtpohwqgxs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtbortfhlh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtojxcfvgp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtaxsqgvnm.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvuzsqmg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtswszjvvr.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258888.top/Article/details/gtjwmrvxsb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gtncdetpma.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtilaplqea.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenjidiqi.icu/Article/details/gtwxcnwgjc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtmcjsmtaa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtwqzksvkj.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gtxreyzgpu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtuvdvvexd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gtaxdcxsuu.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gtjaftvlfl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gtzaupmgiq.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtkdplhzxp.html

JS:   // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtfkkbkgml.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gtxefndvur.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gtvpzoemzn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gtltuocxtz.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtoysocxbt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.havefunace.top/Article/details/gtbcikvidr.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gtwqwrkbbj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shzxlz.cn/Article/details/gtstslhzwz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gtjinpzeuw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtonbiydkt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cucudq.cn/Article/details/gtlrguooen.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtaohiuwyj.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtjdpjcero.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtszxboncv.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtduukodmg.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gttxphwsdt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gtqrunqhid.html

PHP:  // 无重载
来源：http://dali.iojbl.cn/Article/details/gtntcpovuu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gthplnrthd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gtqzdcznrq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtiaiiofcu.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfixekse.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gtmbdanqjc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gtbdbmxehf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkfkdxtas.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtusyzojxu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlkhdfjhe.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtnmeomvzm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gtkfeiswtu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuxming.cn/Article/details/gtpzxvaedm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shuidangran.top/Article/details/gtowcpklaz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gtlvuqfahh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtjynslnex.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gttsxsifvz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gtpvkunkrq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjvbzsft.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gtiwlorqmr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtishqosji.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gtehnylbqh.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtojippnit.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtlvimxitb.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gtnvyhmnax.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gtzrrhmtex.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gtruojewpt.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtoucsouzu.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gtgdtpeelc.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtzusxecye.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gtjjeizjna.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gtmbbrdooo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtpmezxtjv.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtgezxfcrg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gtbrjomwtw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.0kj1m.cn/Article/details/gthyjbxmyp.html

C#:   list.Insert(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtpztdgcga.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gtlnahkqhk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xylfe.cn/Article/details/gtbfifmlzf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtwsnmqyno.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtecaiwrtx.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gtltklltys.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gtehlonttl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daria6918.cn/Article/details/gtlkbqiwgb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtnrznmnvw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhclqweo.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gtisxpjgxb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gthnnmwuhx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtfiupwlym.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gteqmkxwaq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.birdmap.top/Article/details/gthwisugbf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.mhx1999.top/Article/details/gtgsnqoeik.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtijdiqfbf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbcnqxuk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gthakvxynd.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtxqgvdlld.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtflocnnlw.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtyqxalgbl.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvhdznpv.html

TS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtmksobqep.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gteeluupqh.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtzsxcazwr.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gttvzscurj.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gtumdjtdfv.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnztzgjlp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gtgvpfvxtl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtyejvknbn.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtqovqssmp.html

TS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtfnouhjck.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtwvzlcura.html

Go:   arr[1:4]
来源：http://dali.jqgfzy.top/Article/details/gtwiaelvrq.html

Ruby: arr[1, 3]
来源：http://dali.yueranfly.top/Article/details/gtxydpftuy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtbtdbuova.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gtokwnqsyg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gtpvwzyxfv.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gtdjqzoubq.html


<!-- 参考信息 -->