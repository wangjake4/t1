代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yongpay.top/Article/details/gtivtrfcoh.html

JS:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtwgsppqoz.html

TS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtrynxmofh.html

Java: while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtaexdyrrt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cheryme.top/Article/details/gtxjmfnnxc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xylfe.cn/Article/details/gtsboaaraw.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgioyjvsm.html

[B08] do-while（至少执行一次）
来源：http://dali.svipenyu.cn/Article/details/gtpfgtotdx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenlongwang.top/Article/details/gtubngkopx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtdrhpfdjc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtlvekpwpd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtzvbesxjb.html

Java: do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gttitlmpye.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gogol.net.cn/Article/details/gtfdjerlik.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.redwolf501.top/Article/details/gtdzchxbco.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gthmlkreqp.html

[B09] break 与 continue
来源：http://dali.hfpthk.cn/Article/details/gtzqbaqwfi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhoulong.xyz/Article/details/gtplfgdoxf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmumbpefr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtrszwtnss.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtdexlcnqa.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtxurccurl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hysaishi.cn/Article/details/gtunagzvfy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gtdvamasul.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtawaszffr.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gtivuscgjd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.smart0.xyz/Article/details/gttlnugisi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ydzc1.top/Article/details/gtgsgaymhz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gthdwoxstc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkulnupmb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtrzttgpuj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ehwqpu.com/Article/details/gtkfijktfv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaravtep.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yuxming.cn/Article/details/gtqpiivmrp.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gtftolganr.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnqzz.top/Article/details/gtvahtfbam.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gtrzuqwiqa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cashguo.top/Article/details/gtcyzmpvwr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gthfvvhrcx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tianlin.xyz/Article/details/gtlznmblpp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zdqjudy.top/Article/details/gtffubaiqs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yongpay.top/Article/details/gtyiujfvpc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenlongwang.top/Article/details/gtemxkgwpe.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gtoodbqcev.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhiwuduotai.top/Article/details/gtobdubije.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aibaodan.cn/Article/details/gtvlwqyhht.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtlzhnmhqu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxajubfjt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtxdncrrii.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gtfkuunqlx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cucudq.cn/Article/details/gtbeiffoed.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigufen.top/Article/details/gtawslqxgr.html

[B13] 判断是否为数字
来源：http://dali.shzxlz.cn/Article/details/gtvonzilfa.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxuanxn.top/Article/details/gtiyupvxno.html

PHP:  is_numeric($x)
来源：http://dali.jlsjyb.cn/Article/details/gtdiwjafdr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gtyacqyuhj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gtwbjgcabm.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gtcxikyixx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gtsawwevwx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gtpbcytwqj.html

C#:   x is int or double or decimal
来源：http://dali.redwolf501.top/Article/details/gtlpksysbq.html

[B14] 判断值是否在集合内
来源：http://dali.daria6918.cn/Article/details/gtdehvfqxh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gtauqizxjh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gtfsigzsga.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjihjvljh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtdxwfdoti.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtiffuewgs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hammf.cn/Article/details/gtgheeedhp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gttjimhvww.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gtnmotvbhw.html

[B15] 布尔运算与取反
来源：http://dali.cdnleiting.top/Article/details/gtatwcfhdl.html

Py:   a and b or not c
来源：http://dali.yj20258888.top/Article/details/gtqkvcylng.html

PHP:  $a && $b || !$c
来源：http://dali.cheryme.top/Article/details/gtxjfaubtc.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtcblitgzm.html

TS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtxjdbdevq.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtuuigoieu.html

Go:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gthunqwunc.html

Ruby: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtegeonhvy.html

C#:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwbenmcs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtymifipbn.html

Py:   if not data: return
来源：http://dali.pycfn.com/Article/details/gtzzbbyhgv.html

PHP:  if (!$data) { return; }
来源：http://dali.daxiang520.top/Article/details/gtjgapyrch.html

JS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtnjtvcozb.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtazjrooav.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gttgkaadth.html

Go:   if data == nil { return }
来源：http://dali.jinqigfzy.top/Article/details/gtlzssqcsi.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtmpklhbyf.html

C#:   if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtfgmoyjhz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttxutpldw.html

C. 函数与作用域
来源：http://dali.316326.xyz/Article/details/gtfxlqqeqn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbpbrxeer.html

[C01] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtbgslctte.html

Py:   def add(a, b): return a + b
来源：http://dali.sxryk.cn/Article/details/gtulkmasbo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtszmvqbgh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtazghezgc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcgianwqr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtdrjkhjyk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sxryk.cn/Article/details/gtjrewkxcl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdqmqftq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtebjdcgqg.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gtgfsickhy.html

Py:   def greet(name="World"): return name
来源：http://dali.gotoacloud.top/Article/details/gtqnonbptx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuanzx.com/Article/details/gtdbcucrpx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtbzhkkmvp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvsvfkope.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hysaishi.cn/Article/details/gtvysyeepu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubtlebyl.html

Ruby: def greet(name = "World") = name
来源：http://dali.fengsongda.top/Article/details/gtetoddnio.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gtphlidmtg.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gtcusbvltp.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gtppzigqbx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gtertnavbr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gtphecskcy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtojdfqrcy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.smart0.xyz/Article/details/gtzrrlosmi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daxiang520.top/Article/details/gtobmkltre.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jiagoushi.top/Article/details/gtgvryfdfw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shangyingyoupin.top/Article/details/gtdthhstuk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.9152youxi.cn/Article/details/gtgyabubyk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gtkhqbwlnt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.redwolf501.top/Article/details/gtnvubsusr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtxqxelcnv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gtbnqyqmyr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gtfsigpojq.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gtwrrsdwkb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtplsoldym.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtglxrrlwt.html

[C05] 返回多个值
来源：http://dali.hnqzz.top/Article/details/gtzezgwffn.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtknkflmhy.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gtnmyzabag.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtmtkhjnku.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtoogmmhkg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.feifeiyinyue.top/Article/details/gtolsoqclu.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtuotailav.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gtbairqpom.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gtjkwagtaq.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gtjpkqstmk.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gtnpmcwjob.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtuxdhplhv.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtnsabklhm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtdqfoopkh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gttprwgbtm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtsghwzczq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.redwolf501.top/Article/details/gtmouwtrcw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtpsonlrzi.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gtaujghojg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gtjowywrne.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtdlwhhacd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygguhdqp.html

TS:   arr.map(String)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiglounoj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gtdglgwuea.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmroqfxdm.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gtjywuyabr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dianchejie.cn/Article/details/gttrmhruhr.html

[C08] 闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvnuuuin.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gtplldodii.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gtcycbskso.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtgnghwjty.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtsaxusqmi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gtooxdvwxn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gtluiyehsl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmsywfbq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgpfnhfmz.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gtreycohpe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtqfojlhlg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyxuzhdj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtcfvmjhvd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtcxlxvflj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gtfaqmtiok.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gtvfpfaqxx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtsyezdzmh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwhwkizg.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtkqxtmhrt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtmhifqiwy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shzxlz.cn/Article/details/gtztydrnxq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gtgpuefmmo.html

TS:   同 JS
来源：http://dali.fengsongda.top/Article/details/gtcmafugnp.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscwxffoy.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gtgcbmpiye.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtatamdmfd.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gtirerzwvf.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gtyjxymvim.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gtgwnhigyl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gtogfmzhoh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtequkgxdw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gtpywjkjyq.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gtojlkijps.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guowangkeji.top/Article/details/gtcjabxbun.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlvsmxeu.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtfddzdlsh.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtigsvqrgy.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtvcsptjxi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ppjwa.cn/Article/details/gtgppxejri.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtyqbdocbe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gthrcnatap.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuxming.cn/Article/details/gtkqikogio.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258.top/Article/details/gtmlsszcfe.html

Ruby: -> { puts "run" }.call
来源：http://dali.iojbl.cn/Article/details/gtazmhgjnv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtyqswiwwm.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gtfhexhulw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gtyzkkiara.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbbebxwes.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yanxiufei.cn/Article/details/gtrmtagmja.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtjeguehcz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtokhavbsf.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gtczoaehik.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gteebrjbpj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangtech.top/Article/details/gttqasmnqf.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gtkdwygbps.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gtfffrtury.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gttudakdsg.html

JS:   // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtsksvjwgu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gttsvlthxw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gtqchvfngt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sweek.top/Article/details/gtpqtnfmmh.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtbbdkipxg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuognlffc.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gtwoedumfz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtrrepryes.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgnmaoab.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtarxeescz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtnfdxtdbf.html

Java: // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtyxxlgaem.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtmymxnwyf.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtgnofqvss.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gtrsagetnd.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gtdthomlrq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtwwgjcetc.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gtfkzcmrsr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gtxdwlgkfi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhengqikj.top/Article/details/gtqajfjgbn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gtsmptedyy.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gtgugwbcoc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gtpjrycejq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtmlfugskr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjkgbyijn.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtvqqpouat.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdmjsetba.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtqesipogx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtltucldkr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtsqsiktgb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gthilpchkb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gtcpmizekv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gtuectlqpn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gtlowgjqlt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gtalixkxbn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gtbmjvbcei.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gtvqmsbqdp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gtxkpobauo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmlrheko.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gttebwkfen.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtskfbddrz.html

Java: list.add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtytqegiki.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtgcfboesw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gtksezbggx.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gtlohahtpi.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gtdrguoobg.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gtiadrlphy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtkgdescco.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gtftnwpeyr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtvgscecvp.html

Java: list.add(0, 0);
来源：http://dali.yuxming.cn/Article/details/gtjrnrtzkb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtdgjriofn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtzxasujkv.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gtbcssuxtn.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gtonvagiwf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zycfv.cn/Article/details/gtuprplgxv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gtpdirbvce.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gtwvvootng.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtljrhxdnd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gtroxkecxz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gtuluxzbcz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwleetdvo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gtxznqlqiz.html

[D05] 访问与修改元素
来源：http://dali.tanke756.top/Article/details/gthusmnhnf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtvytrheip.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtwqwfvrop.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gttwnunlkc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gtfbnaeloc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gthuniafke.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtlrbgzuze.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gthmfcgxzn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gthsbvxqfb.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtvakwbyin.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtcucqtvfn.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtiztnacjr.html

JS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtklwvxleb.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gtndccyyxw.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gthlmvaihl.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtsircsxwk.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gtlrbrttfl.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtczpvnoem.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gtvkgszwuq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gtmvrhulpi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtnwanwqhy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtwivgybvu.html

TS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gthcvxazkc.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gteaihwpvq.html

Go:   arr[1:4]
来源：http://dali.xuetiantiany.cn/Article/details/gtbvogbnxp.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gtsnncfkyx.html


<!-- 参考信息 -->