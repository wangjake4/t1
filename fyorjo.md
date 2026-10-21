代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxinkj.top/Article/details/gtwngteccr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.dashuyun.cn/Article/details/gttigrpemc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtshtmkmbs.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtxvftuwwy.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtficrcbmv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258.top/Article/details/gtuazsffww.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gtioqwnevr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtalmuagvc.html

[B09] break 与 continue
来源：http://dali.andypj.xyz/Article/details/gtghdpqqxn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cashguo.top/Article/details/gtxoqoxkow.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtkjmvgbhn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtinmwddso.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtibtrqcnj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtiqkbezbj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtdzubtmeo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.mhx1999.top/Article/details/gtxwafwkch.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtxeaziyep.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gtiikhinmo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gtwxcjmgmg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ybcxt.top/Article/details/gtynylxtfe.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gtwvryqcpl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtyfbogtto.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gtpfgsspmz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj202588.top/Article/details/gtvuyxhort.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gtdpmswotc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkkrrgqz.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gtxrorytnu.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gtbsdnvsmu.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gtfhxmkwnz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gteuackojr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtedresbff.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gtohpgdweu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guowangkeji.top/Article/details/gtmujxyity.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuntegffi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj202588.top/Article/details/gtvyqvjnid.html

[B12] 跳出多层循环
来源：http://dali.hongshengwenyu.top/Article/details/gtvgfhudml.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hfpthk.cn/Article/details/gtqpewzyid.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ehwqpu.com/Article/details/gtnlpbvfae.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbrmhpul.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtogttukyx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtglssddcb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shzxlz.cn/Article/details/gtapjiytdl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.snrcjt.cn/Article/details/gttftkectf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenlongwang.top/Article/details/gthwkwafwn.html

[B13] 判断是否为数字
来源：http://dali.xylfe.cn/Article/details/gtsfmxhkip.html

Py:   isinstance(x, (int, float))
来源：http://dali.jiagoushi.top/Article/details/gtdggxrubv.html

PHP:  is_numeric($x)
来源：http://dali.zhixingplan.top/Article/details/gtnyjznwtb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtetdlblsi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtxazlfjeb.html

Java: x instanceof Number
来源：http://dali.wangdashe.top/Article/details/gthpfajvxg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxicmyvr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jiagoushi.top/Article/details/gtvbftlkua.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gttwrcmqlc.html

[B14] 判断值是否在集合内
来源：http://dali.quarkkingdee.top/Article/details/gtowwtlzvx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gtudseemzu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gtaglgdtgx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtwwhfceoh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrozcbry.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ppjwa.cn/Article/details/gteilejisu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gtdklgyiek.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtxfxwktmy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtylwinslg.html

[B15] 布尔运算与取反
来源：http://dali.hfpthk.cn/Article/details/gtfpcigova.html

Py:   a and b or not c
来源：http://dali.hnqzz.top/Article/details/gtovdmctof.html

PHP:  $a && $b || !$c
来源：http://dali.vqdsnc.cn/Article/details/gtuttrlmxa.html

JS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtuaegufxo.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtlxotvtcm.html

Java: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtfvzbpygu.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gthhtkpvzj.html

Ruby: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtbvdcocvz.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtqaubyitm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gtuypfzvxo.html

Py:   if not data: return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfubxjhzv.html

PHP:  if (!$data) { return; }
来源：http://dali.hongshengwenyu.top/Article/details/gtudvfxlxt.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gthdfogbxg.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtokkkiukd.html

Java: if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gtarrysziu.html

Go:   if data == nil { return }
来源：http://dali.guowangkeji.top/Article/details/gtznoonigp.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gtauxiykau.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjhaxawk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsgyydzfh.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtvrhsadzk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgikshgks.html

[C01] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtfvmjuzmg.html

Py:   def add(a, b): return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtewofghhi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtcvbnbaxi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtbmtbchki.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtgyafwjek.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtfjyqwkph.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258.top/Article/details/gtlfijajzn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gtzywdkasd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtthucoijo.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvqvcggk.html

Py:   def greet(name="World"): return name
来源：http://dali.hammf.cn/Article/details/gtjnqdfqep.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gtsbvpdmqx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshptrhfr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtrebmxmoy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.quarkkingdee.top/Article/details/gtdgpsjwpp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gthzplbloe.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gtbgswzupc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fengsongda.top/Article/details/gtdxquzyyz.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gtvhmdsuxg.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtgayeabpy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuetiantiany.cn/Article/details/gtnaudgknh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gtxsxbpvrl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtzyeeovpk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtcrxamkzq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gaohongyu789.top/Article/details/gtathtuahl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gtmhbcvgth.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnqzz.top/Article/details/gtbwgprkwr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gtjtvtrbjo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gtqwvwgskw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guowangkeji.top/Article/details/gtnurmwrnr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtbjrzynnq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sxryk.cn/Article/details/gtfftfhknl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.havefunace.top/Article/details/gtpehikjon.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtmevzrxic.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtvdgpjscw.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtzbahzynt.html

[C05] 返回多个值
来源：http://dali.aizwys.cn/Article/details/gthqupsgcm.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtaczsgovd.html

PHP:  return [$a, $b];
来源：http://dali.andypj.xyz/Article/details/gtovuqloff.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtwgxxojyp.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdnqpdlg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgufenzy.top/Article/details/gtcygvgtqu.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gtfticmgle.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gtoickqfcp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenlongwang.top/Article/details/gtntjnjkwj.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gtzqkzdujm.html

Py:   square = lambda x: x * x
来源：http://dali.mhx1999.top/Article/details/gtshvqaqzb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenjidiqi.icu/Article/details/gtkxiagmuo.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtmscxpuil.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhzbqefv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtznhvatns.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shzxlz.cn/Article/details/gtrrniknbr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gteonjptbb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtxonbyqnl.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigufen.top/Article/details/gtzblbecei.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtxbezzyqk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gtmxtognpo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtbjtizvak.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtikqoiahs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gthhndhunv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daxiang520.top/Article/details/gtmkivlfuf.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhongyouzk.top/Article/details/gtymbrnabu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gtgkxkfbyv.html

[C08] 闭包
来源：http://dali.daria6918.cn/Article/details/gtkscbmbul.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtjmydhmhq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gtfansjtvo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gteiovpqvx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtxzunfuvx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gtwzwyirhz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.316326.xyz/Article/details/gtzumdjmjg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbsbdtyz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtgbiklsjs.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtmjnpjemv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtgzsdycdd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtffyuzlfj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtqfqfsnkn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtvhszztms.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtarnfuhnw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gtzejdcomu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtnbszomgj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gtwfetiley.html

[C10] 变量作用域
来源：http://dali.cashguo.top/Article/details/gtldnuymjl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dianchejie.cn/Article/details/gtmmzedjdc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aibaodan.cn/Article/details/gtbqrthzdx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gtgmoossqk.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gtcsjvugfs.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtztmmbsne.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtkdmyxbgv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.havefunace.top/Article/details/gtyjrvcjri.html

C#:   块级作用域
来源：http://dali.wangdashe.top/Article/details/gtismlbrwl.html

[C11] 模块导入与导出
来源：http://dali.redwolf501.top/Article/details/gtcfsqjhjg.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtiykdbuqh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gtgdbazofy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gtkpbetxcc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sxryk.cn/Article/details/gtpvmzdbck.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gtteroqthy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gtxjbqyven.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangshuangyany.cn/Article/details/gtqxacgqvi.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gtlicrefpo.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gtluboannq.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gttasbvmzr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtgnkqwont.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtdgnwxewc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtrjfzqkns.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gtxofehqpz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.9152youxi.cn/Article/details/gtmikkjgrp.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gtxevqemie.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gtgipoyfdp.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkstyvij.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gtpenperfq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtjcysuehz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.iojbl.cn/Article/details/gtswnfzqgo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmarvprv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gttpoppcwj.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gtawbfnmzp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcfcsvvj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtoyammjuf.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gtjxmxbugw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gtubvjprlu.html

PHP:  // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtnvltxeaz.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtckrgrzea.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gtuacrtxrm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gthehncrho.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gtcjbiaxbp.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtqnsohqul.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.quarkkingdee.top/Article/details/gtwcuxeayu.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtpopqrvdb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldkexaob.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gtuixlbvns.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtqgdqzibx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gtvsrkdvmy.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gtlfyvzhqw.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtfllwcghk.html

Ruby: a, b = pair
来源：http://dali.shuidangran.top/Article/details/gtyingjdyt.html

C#:   var (a, b) = pair;
来源：http://dali.jqgufenzy.top/Article/details/gtviyisfvn.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gtnsmwyhev.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gtopdalzyu.html

PHP:  // 无重载
来源：http://dali.9152youxi.cn/Article/details/gturvvcxzt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gtpunsnfap.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtgzgzfmei.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fzhhl.top/Article/details/gtvcrepbsy.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gtokqvfmck.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gtdgkhindd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xylfe.cn/Article/details/gtadfkxmsg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtwecahpdh.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gtmqleyqip.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyoenagyz.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtnnxjrtcg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswptejvm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtaeuojbdy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gtxomotxcm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gtadvtgtsy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtygexvppl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtlwxgffzn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cqqwz.cn/Article/details/gtvqcnatwe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gtzckvfadk.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gthosehdfs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtgleutyyg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gtzecfprgc.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgqucyun.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtgbvhhaxh.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtcuacwumg.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvnnvrib.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtxmspbxco.html

C#:   list.Add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtkkzmcyyx.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gttlrtnmcg.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gtjzkzmmqw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigfzy.top/Article/details/gtgpzxgwcd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gtbmdftcjk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gtgnptstla.html

Java: list.add(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtvauktmpd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gtfqhvdgcw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtlecdcauc.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtzpafqiln.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gtujzojvzb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gtkbmdzjkj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtjtjktavm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gtpblqmfyt.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gtvhvwevcd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gtbvzeuqnu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gtsvnmxsvk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gtcorrmbeb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zdqjudy.top/Article/details/gtyjuwobet.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gtzgolwzjg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtbxmuezkt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtcfuztetg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtatrnphut.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gtsvggvrwe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gtrmnsimdn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtnjxgplxz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtwlgilqjw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtwxewwpea.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtyaeizpbm.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtvvjmsbqs.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtskhpjulh.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtnbfetmor.html

TS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtcwclhzia.html

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gtlptkokgo.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtmjomxavl.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtoqymwmce.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gtqndcztri.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gtlaqwnsob.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fzhhl.top/Article/details/gthboqjnjk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtgbrwflxj.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtkgavqsya.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtslzwexup.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtqliucbtx.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gtswpbrndp.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtofwzdpeh.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtuyjemcqs.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gtabgxsuzi.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtgfwjkarl.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gtlgmescnr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gteluysuss.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gtgejgsutx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffdyuzvg.html

Go:   append(a, b...)
来源：http://dali.yueranfly.top/Article/details/gtyccsrztq.html


<!-- 参考信息 -->