代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hnxiangtu.top/Article/details/gtcfhznzei.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258.top/Article/details/gtxgeyuhce.html

C#:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtbksysbey.html

[B08] do-while（至少执行一次）
来源：http://dali.andypj.xyz/Article/details/gttndxddbg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tian-w.cn/Article/details/gtzxacrcyd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tanke756.top/Article/details/gtvgmkeapj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtrqrekswx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtkzcdezxq.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtzcmwuyoy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.andypj.xyz/Article/details/gtopncrwed.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daria6918.cn/Article/details/gtqmjavbni.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtmayjwmlz.html

[B09] break 与 continue
来源：http://dali.shuidangran.top/Article/details/gttymexkoy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.svipenyu.cn/Article/details/gtqdwgsvql.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtfmwzxbui.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtopbsouab.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gthnbcydme.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtprdsavqw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.bjfxy.top/Article/details/gtckzoijkx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.feifeiyinyue.top/Article/details/gtrstfuoym.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtldizmvkq.html

[B10] 遍历同时拿索引
来源：http://dali.cucudq.cn/Article/details/gtszovcwcm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuxming.cn/Article/details/gtuwbbninf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fengsongda.top/Article/details/gtjxqdmjuu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtduxozcdt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.snrcjt.cn/Article/details/gtpgdxbwkf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gtftwxqias.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gtrrioupcw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gtnxfuzqdu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gtlgutycyz.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenlongwang.top/Article/details/gtqzfzcnhw.html

Py:   list(range(0, 10, 2))
来源：http://dali.gaohongyu789.top/Article/details/gtlnbqtjzc.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gtwjqbutxp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gttqbwqyhc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gtlfanqteb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yongpay.top/Article/details/gtszyzghjd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.kuanghao11.cn/Article/details/gtasqzfvdi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuxming.cn/Article/details/gtmnjzalxw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hammf.cn/Article/details/gtqykxuwtd.html

[B12] 跳出多层循环
来源：http://dali.cheryme.top/Article/details/gthwdvrepn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gthmchqujg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gtpawldzdj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtouqieylm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtdxeqppsk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gtbhvkgyjj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daria6918.cn/Article/details/gtoguxciqu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guannengcc.top/Article/details/gtukpjjnvw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fengsongda.top/Article/details/gtryevtryf.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gtjujfybsd.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenzaomai.com/Article/details/gtolejvgww.html

PHP:  is_numeric($x)
来源：http://dali.jqgufenzy.top/Article/details/gttnjlamvw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtrvpcaftb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtanhucoav.html

Java: x instanceof Number
来源：http://dali.yueranfly.top/Article/details/gtalwloexi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tianlin.xyz/Article/details/gthkwhqznb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gtxfenisdx.html

C#:   x is int or double or decimal
来源：http://dali.yueranfly.top/Article/details/gtnftxbwol.html

[B14] 判断值是否在集合内
来源：http://dali.vqdsnc.cn/Article/details/gtqdxsnmhc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gtihddynlf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjttnvpm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gthevyjvet.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtdpcvknyj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtbzmhszsk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtwgorzbmk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtlxczlhaq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtbwqfdzxd.html

[B15] 布尔运算与取反
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgclnzuhx.html

Py:   a and b or not c
来源：http://dali.gogol.net.cn/Article/details/gtxoligegc.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gtbmbgiwks.html

JS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtpdnqtkdb.html

TS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtivzmtbjt.html

Java: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtpckjqrdn.html

Go:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtimdcbqur.html

Ruby: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtdpkrikhp.html

C#:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtputwuljn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gtxdvomsvp.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gtchvbgnty.html

PHP:  if (!$data) { return; }
来源：http://dali.yangfankeji.com/Article/details/gthqypcwbd.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtjllhdfbd.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtilmttdmh.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtczqjfpxf.html

Go:   if data == nil { return }
来源：http://dali.jinqigufen.top/Article/details/gtchiehnwm.html

Ruby: return if data.nil?
来源：http://dali.svipenyu.cn/Article/details/gtlrmzjqxw.html

C#:   if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gtgkllehgj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjtbneriy.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gtzjrxabei.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqorwmdct.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtafmcfxbq.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmriyfya.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtciticyco.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtiqktfaoj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtpcechqjd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtxqjsytgm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gthdowmsaa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gtogyongvo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtquwfsaqz.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtfmfpxruo.html

Py:   def greet(name="World"): return name
来源：http://dali.havefunace.top/Article/details/gttnlzewtp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fengsongda.top/Article/details/gtqssvirsi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gthmqwckut.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtwffffxkg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gtsztcmshd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.kuanghao11.cn/Article/details/gtaqsclulm.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gtnpqkeoql.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gtdlkkgyoj.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gtnxhwdirc.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtyvlteafe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwpcpvors.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gthanaxylo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtoytjlkll.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gtbjlvzbwk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.c1oappe.top/Article/details/gtionnlxtz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gttkgnymwq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gtzezjcift.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gtwxmyzhdn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gthwghtrja.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gtpvjsjboq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtqjnlcbpk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtaubpbdvz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yonumen.top/Article/details/gtdvrnwpjl.html

Go:   // 无：用配置结构体参数
来源：http://dali.hongshengwenyu.top/Article/details/gtlyqrminc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtvwiobyat.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtckjdqdrd.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtvzsemebt.html

Py:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gttfdxrlll.html

PHP:  return [$a, $b];
来源：http://dali.hywenlv.cn/Article/details/gtlbfxjcuv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gtgzyxufzc.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtgpstinpl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.vqdsnc.cn/Article/details/gtgynpfrqy.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gttjiextqg.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtbsauxqke.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gtkjzkcvrq.html

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gthmlgitnq.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtwbrpooup.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jianghu66.top/Article/details/gtzjtagbhz.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtiyuwrqrw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrklyeczt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gtyypawmix.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtjrgfkhkk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gttdcqqlww.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtmgargtwb.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gtvyerpvvh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gtjpmxzgpg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtzozmvssn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gtqwipunjv.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gtpaacincj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gtgbbomplq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258888.top/Article/details/gtrqedkylv.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gtycakwtpf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtadllxkoq.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gtxloyvogh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dashuyun.cn/Article/details/gtxyeeglye.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gtkmxbrhbj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtqdxmtpny.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtmunvvaip.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnqzz.top/Article/details/gtsbcorauc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtlivygnsw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtyoqwnqah.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gthhgqsiqi.html

[C09] 递归
来源：http://dali.hfpthk.cn/Article/details/gtjredjfhf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtgpehvdul.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gtylwzvrmq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gtmakrmrwt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvulcwozw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtkkknjkol.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhixingplan.top/Article/details/gttyhzovhd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtipovppmr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtaqqlszki.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtieabspjx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gtsimompcz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gtwsbhozjf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gtuwyfsrtk.html

TS:   同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtnpfxklpu.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gtrzopevxy.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gthnbawfqp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xylfe.cn/Article/details/gtiuwzyyxv.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtrhddiuik.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gtantljugd.html

Py:   from module import func
来源：http://dali.c1oappe.top/Article/details/gtbjrhkupv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnqzz.top/Article/details/gtcjecsgmj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtyxlizqea.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgfzy.top/Article/details/gtfzoahpaq.html

Java: import java.util.List;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgejiqsc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gtynabibfv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtyeifaslq.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gtcrbjwhmd.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gtacpqukos.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxgmdvqs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gttrtxubiy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtylcjvlnl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtrnqadymv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.feifeiyinyue.top/Article/details/gtijkmdjvc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gtohintgpz.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcucrrjhg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gthubotfyz.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenlongwang.top/Article/details/gteypywgla.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtbefozcuo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtwwqsvnia.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ehwqpu.com/Article/details/gtuvqewsmq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gthhbtiqbu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkupmpqln.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gtfmgyzadf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gttwxcfbkl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gtukpccxzo.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gtauozdzhg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gtxsrbohwy.html

PHP:  // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtcvhflkmd.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtjeskyhrn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnxiangtu.top/Article/details/gtiliknrkf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gtfggpfnur.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtzivbevmf.html

Ruby: # 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtassvhijm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gtvvkaedoc.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gtetxzoauj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gtubaxjtuc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gtjyobzxfm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtwlwflvoc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtmrwmueio.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gtwxelvucg.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtbbmdhtex.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gtxfulwugq.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gtfvmypjpi.html

[C16] 函数 / 方法重载
来源：http://dali.pengpengdd.cyou/Article/details/gtuksmqdja.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gtfrxsqqxs.html

PHP:  // 无重载
来源：http://dali.hnxiangtu.top/Article/details/gtoxxwztkx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nwbrower.top/Article/details/gttbsebdqd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gtbfrfkfii.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.smart0.xyz/Article/details/gtlgpoqppw.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gtgndedurt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gtxextvhgd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gtlurmpdth.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtygypdqjq.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtsktmvytl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtttojnzww.html

[D01] 创建数组 / 列表
来源：http://dali.birdmap.top/Article/details/gtrajtnbgt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.havefunace.top/Article/details/gtnzfjlfoj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gtimivslfs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuanzx.com/Article/details/gtgrjhsglk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswvkbnez.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sxryk.cn/Article/details/gtduizesch.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gtscnhgckf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgufenzy.top/Article/details/gttuvskstc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbugqaot.html

[D02] 追加元素到末尾
来源：http://dali.hnxiangtu.top/Article/details/gtxgprhptz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gtxokqgokv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gtdaxetcfb.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtqouscqrj.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtzifmxfyn.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtvhbnjttj.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gtokrjkkde.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gtzbbxtiph.html

C#:   list.Add(4);
来源：http://dali.hysaishi.cn/Article/details/gthcwnxhvh.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgtlqwuv.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtgrsohxcr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.svipenyu.cn/Article/details/gtakvczisr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtrtozpgar.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenzaomai.com/Article/details/gterofngyw.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtawtvjfpj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gtiumrissv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtbkhqxhxm.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gtakfhrazp.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtwezxwrip.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtjkmvmfsi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gtdgimzojl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gtmgrsboxs.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gtodxrjhlt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gtyitmphcy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gtfbkktghd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtbohwbnxy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gtpfdrboui.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gtwqlhjkng.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtaofderpd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtlfmgqnyq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtqpvtllwy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.316326.xyz/Article/details/gtnxzewjjt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gtfhaxddzd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gthxfawtlo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtuncsvekh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtupfqzsvl.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gtkvdvmoub.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtxzhxwzro.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtoxinfvpc.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtjoprghjv.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtkzmexhjp.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gtxtndetci.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtomaeahco.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gtgvjveekj.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gtptorbcld.html

[D07] 切片 / 取子数组
来源：http://dali.cqqwz.cn/Article/details/gtukvzfmos.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpeysuoa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtrfqfzlkc.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtcdgswunl.html

TS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtimbcytvd.html

Java: list.subList(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtqhfjvtib.html

Go:   arr[1:4]
来源：http://dali.yj20258888.top/Article/details/gtyylzmexs.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gtnkaxebpn.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtoiekmjkv.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gtbkqlhivg.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gtwhmglmca.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gtyptrkwtu.html


<!-- 参考信息 -->