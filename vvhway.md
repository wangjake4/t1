代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xinyue.icu/Article/details/gtvynzwdpf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuetiantiany.cn/Article/details/gtcxtczndt.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtytjzmycb.html

[B08] do-while（至少执行一次）
来源：http://dali.tanke756.top/Article/details/gteqgpecoa.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.0kj1m.cn/Article/details/gtfarpqgwp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtepitndba.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtiedysibv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvssnqqua.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxrfoxew.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gtwvnexjyb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cdnleiting.top/Article/details/gtcykqmcfq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gteycabtbg.html

[B09] break 与 continue
来源：http://dali.svipenyu.cn/Article/details/gtvhwvymeg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yonumen.top/Article/details/gtxmafzzne.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtxyffvykq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvkjnyqtg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gthhedjbgl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfcrzduz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gtjsdtlszy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.feifeiyinyue.top/Article/details/gtwydbpgku.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtpvsvsnlw.html

[B10] 遍历同时拿索引
来源：http://dali.yj202588.top/Article/details/gtpncwdqvm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gtakwxiqwg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlarlkrma.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gtidnhxlrh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtjetvengh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gtyabefpsy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yanxiufei.cn/Article/details/gtuvodhpve.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjrrocyo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gtloqmvncy.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuetiantiany.cn/Article/details/gtkftxvevd.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gtjhebtavb.html

PHP:  range(0, 10, 2);
来源：http://dali.316326.xyz/Article/details/gtkbihdzaa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtsdvdtkls.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtmgirozxh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gteydmbjrz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jianghu66.top/Article/details/gtsxvourut.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gtmmvlcwhs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.bjfxy.top/Article/details/gtminkdlmv.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gtmlhywmqi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gtjzbdqand.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.mhx1999.top/Article/details/gttyyzqnvu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtwodbtcll.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtdjyyqkqe.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtagfgngch.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.feifeiyinyue.top/Article/details/gtmrumqmya.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hfpthk.cn/Article/details/gtkidovljc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gtmrunkjto.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhdpspci.html

Py:   isinstance(x, (int, float))
来源：http://dali.yonumen.top/Article/details/gtibvrblko.html

PHP:  is_numeric($x)
来源：http://dali.c1oappe.top/Article/details/gtppxklorn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtcdluztxf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gtknegnbcs.html

Java: x instanceof Number
来源：http://dali.yanxiufei.cn/Article/details/gtnarfgyky.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daria6918.cn/Article/details/gthpmaiqld.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gtpzsmbrta.html

C#:   x is int or double or decimal
来源：http://dali.9152youxi.cn/Article/details/gttkrmfvdm.html

[B14] 判断值是否在集合内
来源：http://dali.pycfn.com/Article/details/gtkanyzwao.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gtohtzixvu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtiwgnoilb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gttmqhwphh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtyocrrjuk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtzgxlmucl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtdpjmuzhz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tian-w.cn/Article/details/gtqsdjnedw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtccbotrqw.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gtnhlonafj.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gtbcyrbkgq.html

PHP:  $a && $b || !$c
来源：http://dali.hongshengwenyu.top/Article/details/gtlpyzorwa.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtezzgzgep.html

TS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtmwzbdsnk.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtcbdtmkym.html

Go:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtnhshntkr.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtmtyxzblb.html

C#:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtrnimkrug.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gtqkafuewo.html

Py:   if not data: return
来源：http://dali.tanke756.top/Article/details/gtuefbgtht.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gtgpponfoo.html

JS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtzcahakwg.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtufetcngo.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtoctnlbxm.html

Go:   if data == nil { return }
来源：http://dali.pycfn.com/Article/details/gtklcekzcv.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkjahhoz.html

C#:   if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtynylcqda.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtsuiegghc.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gttwwujrqe.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxsrjmrk.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtktmqxvru.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gtcgnheaby.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtkaqazmbp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtzacixkhm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtfbndrnss.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gttgrzryme.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gtdlxround.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yonumen.top/Article/details/gtqvpukzsr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtzhxvidnf.html

[C02] 默认参数
来源：http://dali.yj202588.top/Article/details/gtrqybxukh.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtjupomorc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticgqukvh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtwnyuctye.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtrmnftkrz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yueranfly.top/Article/details/gtckoalpij.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtjuxgjphs.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gtvaqpeobv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gtgmejsezu.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gtkkytabun.html

Py:   def total(*args): return sum(args)
来源：http://dali.sweek.top/Article/details/gtovpjbbve.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yueranfly.top/Article/details/gtzupezzfa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtbaatxcty.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtryanbwkx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysuausyo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.feifeiyinyue.top/Article/details/gtmiridtmo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gttdxcsyfm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shuidangran.top/Article/details/gtedrdzodd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnksnotpp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gtextjtxcq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gtbtzadssv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtmgwpsqym.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tanke756.top/Article/details/gtrzgipbyh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gtiztyvzqx.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gtupoticoy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtkhkjkiwg.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtmjdpejpa.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gtpdfwburo.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtcraurhmo.html

PHP:  return [$a, $b];
来源：http://dali.cashguo.top/Article/details/gtnwrfgfio.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hammf.cn/Article/details/gtvrwqjana.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtdvbpxhzy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hfpthk.cn/Article/details/gtlehkodof.html

Go:   return a, b
来源：http://dali.jianghu66.top/Article/details/gtymfeafsp.html

Ruby: return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtvpbhxuma.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gtmzgbriax.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gtxlvsbceo.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gtoazyekda.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudgaeyfd.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtxyafrukq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gthdmpzrcs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtyulykmnn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.andypj.xyz/Article/details/gtaptatkue.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gthojnxprw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gthqnwaibm.html

[C07] 把函数作为参数传入
来源：http://dali.sweek.top/Article/details/gtsqtwblke.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gtcnnxlezo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtxujpzscq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gtkgedbmgp.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gtzqoccbyl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gtymvpcjrm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gtsuocyyas.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gtcswnlnju.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gtwiuloytt.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtffjhtaal.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gtoujdkxgj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dashuyun.cn/Article/details/gtaofahicz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjumzlwqd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtxwnigery.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtkmfnblur.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gttfozzilb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gthcqxcgva.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtcdxkylrx.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtwlwptrfq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtlmmrinvh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.smart0.xyz/Article/details/gttzilxwgt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtjottbtwa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gtvgfmkhuv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyxqzxed.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyarhstuj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtoaubdiqj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenjidiqi.icu/Article/details/gttcjkpbce.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gtyiasozdx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gtdazcrlsr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gtjwdnolps.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gttexttrnm.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gtmkkddgbr.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtxtenquun.html

Go:   花括号块级作用域
来源：http://dali.sxryk.cn/Article/details/gtqoqwimjx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gtrvczkkdv.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtgozcsnnu.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gtnalenjqf.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gtkdibjgdu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhengqikj.top/Article/details/gtzufvelbb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzoozopl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gthrzxamqd.html

Java: import java.util.List;
来源：http://dali.jqgufenzy.top/Article/details/gtoashgyya.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gtkglpfrax.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hammf.cn/Article/details/gttagzvqtf.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gtvvhkajry.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gthoqbvkxu.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gtlgftpkii.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gtplumoygy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtchgxxbqa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gthabcpgvm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gtguzbgdix.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gtsfipxrok.html

Ruby: -> { puts "run" }.call
来源：http://dali.guowangkeji.top/Article/details/gtzvvszmff.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtmnnuheoh.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gteyafkpeh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtrccjkwxb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtugtthhqf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenlongwang.top/Article/details/gtpzynxbvm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtxhhnirjf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtbwbvbphe.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gttwemuczq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj202588.top/Article/details/gtvytgdnwu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gtsrsfzlkw.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gtrnyqqtog.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gtlelnarfh.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gthngyvuun.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtzhndyaey.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnqzz.top/Article/details/gtfrjcahdz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaohgfvnt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gthrbgmcbk.html

Ruby: # 无泛型
来源：http://dali.hammf.cn/Article/details/gtjwzsxyrb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ybcxt.top/Article/details/gtuheaagpo.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gtskeneuqp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.andypj.xyz/Article/details/gtumkyiugs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwpactgm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtpuimgxil.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlhozrbek.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gtbulvtpsn.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtegdnwgkq.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtvbvpyvsl.html

C#:   var (a, b) = pair;
来源：http://dali.gotoacloud.top/Article/details/gtxkasmiks.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gtxwtrwbzf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigfzy.top/Article/details/gtdkzgehwy.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtsojxuovt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gtfcgcbyqh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gtpmxgxcdn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqfjzinu.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gtitthkxlg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtrxidxdzm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtalatmsmo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsgcruyfi.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gtqriswcrc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrfnxbmsg.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtjndjqciq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gtntzyqzdo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gtmadedyui.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtsstdvnbs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gtitukedpa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dashuyun.cn/Article/details/gthfdxmdgs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gteqdasjcw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gteggdfhnk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.iojbl.cn/Article/details/gtamyhuuvv.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gtphxcbhlz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gtlvfgyjsz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gthhnmyfpg.html

JS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtvsnqlrpk.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtgpghcqgt.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gtogjihjxu.html

Go:   arr = append(arr, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtxmzuxout.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gtpwqsqeik.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gtlvpsajzp.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubxdppre.html

Py:   arr.insert(0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtoobdtgbl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gtuwiotavi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtydpaixka.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtthycplzy.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtasumfbcx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gtodjpaddq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gttjdbammv.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtkttsrhhq.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gtpfcezldm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gtyqcudyjd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jyoumei.cn/Article/details/gtatahcbob.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gtgkjhahls.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gtflrrpuhi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gtwqokatez.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkdirzuj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gtwjyrugev.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gtnyasyzde.html

[D05] 访问与修改元素
来源：http://dali.guowangkeji.top/Article/details/gtrsgajeji.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gteyexleuk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtgkrjvnfm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtmwpdlbre.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.smart0.xyz/Article/details/gtxpdnqiha.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ydzc1.top/Article/details/gtmoasbvmu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtkmlwadle.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtomcefxqf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtxufbidtc.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtwnpsefqs.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtbfjxvylk.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gtjaxneapr.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjduqetji.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtmoiyioed.html

Java: list.size();
来源：http://dali.ybcxt.top/Article/details/gtwaocrzxr.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtlqjvwpmi.html

Ruby: arr.length; arr.size
来源：http://dali.jyoumei.cn/Article/details/gtqqblyojp.html

C#:   list.Count;
来源：http://dali.yonumen.top/Article/details/gtejlqcdzu.html

[D07] 切片 / 取子数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagyfiacm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenjidiqi.icu/Article/details/gtaomluwcw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gtolfqpcoc.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtijzhuogz.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtpetklccn.html

Java: list.subList(1, 4);
来源：http://dali.pycfn.com/Article/details/gtuegszald.html

Go:   arr[1:4]
来源：http://dali.havefunace.top/Article/details/gthuxexxwh.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gtuxetalvp.html

C#:   list.GetRange(1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtkftcdxez.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gtxpwrehvz.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gtprdzelmv.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtdzxgwwmz.html


<!-- 参考信息 -->