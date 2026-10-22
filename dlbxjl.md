代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gtsugoafjc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gtmmjexhvg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yuxming.cn/Article/details/gtcrszvyos.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenlongwang.top/Article/details/gtmtryrwkm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.quarkkingdee.top/Article/details/gtrlqqhpxd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenzaomai.com/Article/details/gtbsdthegj.html

[B07] while 循环
来源：http://dali.cucudq.cn/Article/details/gtxhqwxpnc.html

Py:   while i < 10: i += 1
来源：http://dali.zhixingplan.top/Article/details/gtluqbbkjz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjprdpfnw.html

JS:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gttuqtxqcm.html

TS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtryysdsdu.html

Java: while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtlmvmewzj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daxiang520.top/Article/details/gtrwvnqrwd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gtjgzuvezw.html

C#:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtxasbltsx.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258.top/Article/details/gtkycaeeod.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yvedp.cn/Article/details/gtdslgqsqg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtvzhsjhge.html

JS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtqhmqnwxw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtojskxnin.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtgsrgmhvz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxruvutuv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtchhmqebt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtlpsbqexa.html

[B09] break 与 continue
来源：http://dali.birdmap.top/Article/details/gtrhouavqe.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hfpthk.cn/Article/details/gtgjavjnkz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtabxtehqc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtynlvlijh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtmhqetnxf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gttnhfecbp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofcgczmt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jlsjyb.cn/Article/details/gtwdtavtep.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtwntbdaet.html

[B10] 遍历同时拿索引
来源：http://dali.haohaochexian.top/Article/details/gtqrgluxro.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.havefunace.top/Article/details/gtjpmrmrog.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhiwuduotai.top/Article/details/gteruxidjr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsfewkqm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gthejppusy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daxiang520.top/Article/details/gtytorgsqr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzehyteen.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgfzy.top/Article/details/gtliqicyue.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.kuanghao11.cn/Article/details/gtpvweubam.html

[B11] 生成数字序列 / 区间
来源：http://dali.yonumen.top/Article/details/gtfdpzcalt.html

Py:   list(range(0, 10, 2))
来源：http://dali.tanke756.top/Article/details/gtrbzvolii.html

PHP:  range(0, 10, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtfklmfsqd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtnluapckv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtqwykuuok.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtdzhtinjr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.c1oappe.top/Article/details/gtakvxqpdu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhongyouzk.top/Article/details/gtjdsqwdvu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangdashe.top/Article/details/gtxjvhnbla.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gtybawbozn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dashuyun.cn/Article/details/gtqnacxujt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gtkuukradj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtrwpttzfy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtibhjoubz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtvxnobtcw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.iojbl.cn/Article/details/gtvecjjexj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gtqctycabz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tian-w.cn/Article/details/gtzhrjoruf.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtrfevmlic.html

Py:   isinstance(x, (int, float))
来源：http://dali.shuidangran.top/Article/details/gthzjolplw.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gtbzxpfiza.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtcrbgsrol.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gtgxorkhhv.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gtcakhhbgd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gttsmlghpj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gtigtfbqvh.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gtpmcftnjf.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtbywjtcvo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtqchtunmx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgfzy.top/Article/details/gtyppvcfbo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtdljpmqxx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gthapbtfiy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtfoiztbwt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtzklmelqe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zycfv.cn/Article/details/gtqlcmcxzt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtkogosvuv.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsijbrmyw.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gtwcgvccta.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gtbqpuwyka.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybfbwelv.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtowrirdzn.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtwiizyouw.html

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtcvflibrl.html

Ruby: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtopfggiwt.html

C#:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtabmtubbv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gtxwprcllp.html

Py:   if not data: return
来源：http://dali.ivvv.top/Article/details/gtdigjdwha.html

PHP:  if (!$data) { return; }
来源：http://dali.yueranfly.top/Article/details/gtqpaffuxk.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gttsqtiepi.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtwyaizyao.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtnluhfigk.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gtjcvtquip.html

Ruby: return if data.nil?
来源：http://dali.yangfankeji.com/Article/details/gtyppdyjqh.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtyarqlahn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtcskodgqf.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gtxnclnrsi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtudlenpem.html

[C01] 定义函数
来源：http://dali.yj202588.top/Article/details/gtqvutszki.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtygupcqoc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtluyxwpho.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtemzdbgwm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtbzrmgqmk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtfbojovcy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtvqvrpdmp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gtqmsnzqdl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtrlvccwnf.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtfzjrimmx.html

Py:   def greet(name="World"): return name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqraavqlp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpauubzrs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtaguuymny.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtiosysotd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cucudq.cn/Article/details/gtrgfkhrqm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gtaejuiuni.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gtjumnklay.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gttyiihvsu.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gtcyrvfixc.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gtfigynpoz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gtsxkkajtq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcvognype.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrivxibsg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gtvwxnuuky.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gtyaphlrvl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gtefuqacpt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gtgdfxriuq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbbyxffg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gtynflognn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtgipqnrra.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gtcogeqceg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sweek.top/Article/details/gtynedlzkh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtzdqujnku.html

Go:   // 无：用配置结构体参数
来源：http://dali.ivvv.top/Article/details/gtrffwijkk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtnbqdsitq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtqzmmfdwe.html

[C05] 返回多个值
来源：http://dali.9152youxi.cn/Article/details/gtdiujwqll.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtxggwlvda.html

PHP:  return [$a, $b];
来源：http://dali.dianchejie.cn/Article/details/gtvymbwycu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtmgurdvkg.html

TS:   return { a, b };
来源：http://dali.yonumen.top/Article/details/gtsbqjxanw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gtcnfxfwey.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gthugadbjg.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtqaxdykug.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gtdeplcepd.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtdpladfuw.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gtwcwfaaxt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gtcagtbswb.html

JS:   const square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gtdsfbyuux.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gtaiuuvnfd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtxiteuteh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gthiqnpnye.html

Ruby: square = ->(x) { x * x }
来源：http://dali.haohaochexian.top/Article/details/gthrnlqwrp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtqcxhtjcf.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gtpszclsfb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.snrcjt.cn/Article/details/gtthwqulqi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtlwpcrgqk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtkusxwhps.html

TS:   arr.map(String)
来源：http://dali.zhengqikj.top/Article/details/gthgsxuejc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gtmfsqvcds.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gtffjuquzm.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258.top/Article/details/gtlzxdofwr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gtuwagovmm.html

[C08] 闭包
来源：http://dali.c1oappe.top/Article/details/gtsckdgfzh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaaueche.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.meibo888.top/Article/details/gtbkbpbusu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtvlsjqjcu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtxggghjzk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gtemauskdg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gtfvekmzua.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gtoljhkuvc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gthckgeuae.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gtdwoplgfp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gtnugcfmuz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtcamppqyw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtaixpjysn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtmoznjhbn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfsozmuls.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ppjwa.cn/Article/details/gtgznopgwu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtzvisyihl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gtmqagkaeb.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gtjrssbcps.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtjifaicgp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtdmopebxo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtdbkbjwpk.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gtabcqmggr.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gtnopqlukv.html

Go:   花括号块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtonldhohn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gttkzijnnd.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gtnnuqkudw.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gtvrrthzho.html

Py:   from module import func
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcowsaagh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gthjhikote.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtmjnklbql.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gtljxuispe.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtpstjprou.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangdashe.top/Article/details/gtqzxphomv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gttxvfxssf.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtdqohcvie.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gtkpynqems.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gteggjxewf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtqqufgmhs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtjgnpsjjv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgljghul.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tanke756.top/Article/details/gteoqpelhh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gtdeyywrqo.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtgucatoki.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shuidangran.top/Article/details/gtpwklxtbb.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gtexujencb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtgrfzcwem.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtmmmoblfe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigufen.top/Article/details/gtizzrwjjs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrdmomepv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtiyywcoox.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gtfxafkfdg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gtrjcyfxrl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtegmzzlhj.html

[C14] 泛型函数
来源：http://dali.zhoulong.xyz/Article/details/gtazmxsbog.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gtgvalxysx.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtkibeewzr.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gtlfidkkmm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnqzz.top/Article/details/gtjwwqxeba.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daxiang520.top/Article/details/gtkmihwqrj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gogol.net.cn/Article/details/gtvzjwtyry.html

Ruby: # 无泛型
来源：http://dali.cheryme.top/Article/details/gtfltmryye.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gtudxyhcvu.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gtuiqhjinr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gtucpmwmwd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gtalbhnccj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtuklgtcnb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtmxisoilz.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gttyknixpy.html

Go:   // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtdpfboxgt.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gtoguanjuw.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gtbexltjic.html

[C16] 函数 / 方法重载
来源：http://dali.nanxinkj.top/Article/details/gtlhmvxdve.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gtzwyxjtfd.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtzbdnqecz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gtithqngkd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtuklwbgcz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gtinjekcri.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gtkgvpdufn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gtsplpzjnp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihodjsci.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfekqeocz.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gtdkzpgcnz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtguzpbgxt.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtnpwpnsro.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gtxdgnbzoj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sweek.top/Article/details/gtocrzntps.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gtpdwdlgen.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gtuhylbewp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gtnzmijupe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtfsesoxcw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gtxizzdyyn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gtfbrdhanq.html

[D02] 追加元素到末尾
来源：http://dali.yonumen.top/Article/details/gttupvvgdx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gtdsldluft.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zdqjudy.top/Article/details/gtxenworcr.html

JS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtnlhpeeiy.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gttdwikfqk.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gthaqazqdt.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gthggbqgbu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxinkj.top/Article/details/gtmxvzezju.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtnhcheepc.html

[D03] 在指定位置插入元素
来源：http://dali.daxiang520.top/Article/details/gtmqqohfxv.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gtwgjmeghr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yvedp.cn/Article/details/gtbaespzqx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gtgqkkvyfn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusyjefob.html

Java: list.add(0, 0);
来源：http://dali.cashguo.top/Article/details/gtranlcyeh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtzvpmemxs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gtpqyqhbue.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtslbxfgjk.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtyywnpepj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtlfxoybus.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtfirlhuom.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtmpwwwbvd.html

TS:   arr.splice(0, 1);
来源：http://dali.yongpay.top/Article/details/gtcarofxie.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtludgwrjg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gtaxrfouza.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gthitxyebd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtuwydanpn.html

[D05] 访问与修改元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekrqpkou.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtpwxydcve.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcikfyjnj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbeuwdcp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gtzupkpuqo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcklokseq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtaeymrekf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtdptrryvy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sweek.top/Article/details/gtbubkegpt.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtfbkrmzmj.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtjttpfjix.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gtbubctdul.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtssirdutg.html

TS:   arr.length
来源：http://dali.meibo888.top/Article/details/gtyxmblone.html

Java: list.size();
来源：http://dali.hongshengwenyu.top/Article/details/gtkglpqqrw.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtxqzfphbs.html

Ruby: arr.length; arr.size
来源：http://dali.birdmap.top/Article/details/gtdubhcqga.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtkhqwxxtu.html


<!-- 参考信息 -->