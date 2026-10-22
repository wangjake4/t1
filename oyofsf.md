代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cashguo.top/Article/details/gtaoydlikt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nwbrower.top/Article/details/gtdawtczce.html

[B07] while 循环
来源：http://dali.hywenlv.cn/Article/details/gtkeyrrqbp.html

Py:   while i < 10: i += 1
来源：http://dali.dashuyun.cn/Article/details/gtcpsmuooa.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtbnybdgpy.html

JS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtrvqljgll.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gthjpooajd.html

Java: while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtneavydzb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuetiantiany.cn/Article/details/gtfcppmtcg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gotoacloud.top/Article/details/gtfpwidedb.html

C#:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtfxfbrfjd.html

[B08] do-while（至少执行一次）
来源：http://dali.shangyingyoupin.top/Article/details/gtbitthaup.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gtdhvxkwgq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xziqi.cn/Article/details/gtoezcaghi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtjjglszti.html

TS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtdasgdpph.html

Java: do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtywdxtyqt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.aizwys.cn/Article/details/gtnfblagcn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.redwolf501.top/Article/details/gtdzvyfhbu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtghlxaruj.html

[B09] break 与 continue
来源：http://dali.jinqigufen.top/Article/details/gterrkmuea.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shangyingyoupin.top/Article/details/gtuqmphzxp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtctbsceps.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gteroccfcl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtwfnogxrn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtetmoxili.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gtoonlqsdd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgfzy.top/Article/details/gtowwuycjc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtfyjiiqbz.html

[B10] 遍历同时拿索引
来源：http://dali.havefunace.top/Article/details/gthxzjuclw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gtqlilaebf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guannengcc.top/Article/details/gtbmzstlcj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtdecdxukx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtczaqzfgm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nwbrower.top/Article/details/gtjgkgzmur.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuanzhike.top/Article/details/gtvbgquucx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gtpkxdcwrz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zycfv.cn/Article/details/gtplingtzj.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gtpssnfoof.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gtvdajsaji.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgufenzy.top/Article/details/gtjbtmndpq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtxexdqpap.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtdemvciex.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtualugits.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpkzldac.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gtcjesoaag.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gtymyaegff.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gteeiwnxbd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfafafzpi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daria6918.cn/Article/details/gtpdhjsxfb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtejywnpsf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtkhzesxoz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtataznwav.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.mhx1999.top/Article/details/gtuvylaomn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hfpthk.cn/Article/details/gtbxuhunlh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxuanxn.top/Article/details/gtgbyvstbb.html

[B13] 判断是否为数字
来源：http://dali.redwolf501.top/Article/details/gtljzlivac.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gtzpdwkqkz.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtcomxiscq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtucwqehon.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gtedsrtwqm.html

Java: x instanceof Number
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwldcied.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gtgkyeiaqs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.mhx1999.top/Article/details/gtyzqzukhn.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gtudmnavrs.html

[B14] 判断值是否在集合内
来源：http://dali.meibo888.top/Article/details/gtpfvrzins.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gthwsvaagv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zdqjudy.top/Article/details/gtfnbvsrmz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtevafsmlg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtimgqqudv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sweek.top/Article/details/gtrbrvvuob.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xylfe.cn/Article/details/gtrwhycfnh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sysykeji.top/Article/details/gtbkxvirnt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtiypfhqut.html

[B15] 布尔运算与取反
来源：http://dali.kuanghao11.cn/Article/details/gtdszeeoty.html

Py:   a and b or not c
来源：http://dali.gotoacloud.top/Article/details/gttffykozo.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gtkqrxvfeb.html

JS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtiuwoonin.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtcubwvbwn.html

Java: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtbkwtptpe.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtrfdnlpiz.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtwwnxehvq.html

C#:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtgltxvmja.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtullqncxn.html

Py:   if not data: return
来源：http://dali.cashguo.top/Article/details/gtjrlfoyix.html

PHP:  if (!$data) { return; }
来源：http://dali.andypj.xyz/Article/details/gtgiyyjqmt.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gttbcuutbt.html

TS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtzjctmfeg.html

Java: if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gthrwlagrd.html

Go:   if data == nil { return }
来源：http://dali.ydzc1.top/Article/details/gtgmgzsuhe.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gtfvmgvmkd.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtauvnjnlj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnlnvcrsf.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivyoonjx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgvhmkktv.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtiyocwokp.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gteokqlaon.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtchaxubbr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gthrgoyiva.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtnbnwtxnj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtthmdqsdf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbajsylkd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gtkobstbuy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtffdpyalx.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgjusfiq.html

Py:   def greet(name="World"): return name
来源：http://dali.yvedp.cn/Article/details/gthhpkxuvy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gtunkixubu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtbdhbfnxv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtcgyuimbe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gtaemtqrez.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuanzhike.top/Article/details/gtrwmvmefa.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gtdsozkvuk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gtqkyzfmtl.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gtkejwclsa.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgufenzy.top/Article/details/gtqsghkhwx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gtjfofkatz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gtdifmnmio.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtmratkyju.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtyfyuqnoy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gtwyxddtzk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gtqwreqevz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sweek.top/Article/details/gtyzrlzarq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gthcqdlmjo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gtekcocrmm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gteuyjbuxe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtrdlqclhw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnqzz.top/Article/details/gtjmrsemnm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gtuslgeuno.html

Go:   // 无：用配置结构体参数
来源：http://dali.yonumen.top/Article/details/gtvjbxizcv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtmusabpjq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtjnlhppvk.html

[C05] 返回多个值
来源：http://dali.sxryk.cn/Article/details/gtulfhzzxl.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtrzgsxwti.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gtkqsoxpxv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gtmkwteefv.html

TS:   return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtsegtnkxk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gttkddjfoh.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gtjvohiirh.html

Ruby: return a, b
来源：http://dali.havefunace.top/Article/details/gtxcfznptv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gtaxdgiqhl.html

[C06] 匿名函数 / lambda
来源：http://dali.xziqi.cn/Article/details/gtikxfbjgd.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gthiswrifu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtegawhajh.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtqmtebqvp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtcxsdifgh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gtjwimqcxb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gtxmmzowts.html

Ruby: square = ->(x) { x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtvwubgegt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvikmktzp.html

[C07] 把函数作为参数传入
来源：http://dali.sweek.top/Article/details/gtoqgclwjk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gtqwonqpgf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtaiskjmxy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hongshengwenyu.top/Article/details/gthppibaef.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtopomomdc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.9152youxi.cn/Article/details/gtaunmyogx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gtoyhacijn.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenlongwang.top/Article/details/gtrrkqbbhm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fengsongda.top/Article/details/gtvfswqbvj.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtqqeufrbs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgufenzy.top/Article/details/gtyzhgieac.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtwebhyvih.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtgmbbkcyt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtssddlwnt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gtsojvblsk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.havefunace.top/Article/details/gtaoljogzr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gtuhxzyqgz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtmeuakjvd.html

[C09] 递归
来源：http://dali.cqqwz.cn/Article/details/gtcunscfky.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtsaqosp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gtaznmcaru.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtsxayxldd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtupumzcsa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtzkuktzxc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gthmeaavej.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtcojmwten.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.bjfxy.top/Article/details/gtalziorxh.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtxtdxtytr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hammf.cn/Article/details/gttwwvycgt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjrpqidy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gtssxvmecy.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gtkypdnuki.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtwkveghxn.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtexjdsfed.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.kuanghao11.cn/Article/details/gtccnfeywy.html

C#:   块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtthayscpu.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gtannlpvvu.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtkhrhajer.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtalezhaad.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtziuvjrtc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtwtinmeqh.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gtdmklaynm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gtbfzgsvew.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gttmpbswdp.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtdlhlipqw.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gtrpkuobhb.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gtysjsgqsl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gtxxwodrgq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtbtcwvicn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtxzgrnxle.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gtradbwwcc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtyseebfae.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhixingplan.top/Article/details/gtjwxdekjc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtqbevcafd.html

[C13] 类型声明 / 类型注解
来源：http://dali.iojbl.cn/Article/details/gtweisjdhw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtjvucwnxe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gttxindlmo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gtcgsioksx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtdulouhst.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsuouuqv.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtkhfhydsq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gtejlxbcfk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gtowbzwvub.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gtulkvzoaf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cdnleiting.top/Article/details/gtbazbbczk.html

PHP:  // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtnhaksjwm.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtanorjpvf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gtxoivzfdb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gthynrqhho.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gtbxwmilxu.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gtpltrnsly.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtkvkwseta.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtfmpoaamy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtcsjxvwqp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gtvzpjboah.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtgetxemjp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cashguo.top/Article/details/gtjnidzphf.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtfylkpyxi.html

Go:   // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtbuukupob.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gtbamgidwq.html

C#:   var (a, b) = pair;
来源：http://dali.gogol.net.cn/Article/details/gtlfnyooej.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtmwqltali.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yvedp.cn/Article/details/gtbhnbjqtz.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtmnmyhbyg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtsesakiri.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gtgnlakjsq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtznmobtau.html

Go:   // 无重载：用不同函数名
来源：http://dali.ehwqpu.com/Article/details/gtldolqvri.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gtgjztthzg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ivvv.top/Article/details/gtqpitxjlm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtsuzicoxx.html

D. 数组 / 列表 / 集合
来源：http://dali.haohaochexian.top/Article/details/gtzohobegx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtaihevcnl.html

[D01] 创建数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gtpyckusza.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gtcwtehpfe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtihzkrtde.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gtnkzlanvd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gtteatjlho.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gtjmsnfzji.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzkensde.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhengqikj.top/Article/details/gtuulwejaf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gtjilyebaj.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtfowmeakm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gtuwhpsijj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlqyugtl.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtnhbbiizd.html

TS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtgblqzktl.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gtpzoehlux.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258.top/Article/details/gtbypeuiak.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gtnwzdqosp.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gtcoxredjx.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gtcgsywzrl.html

Py:   arr.insert(0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtxnwsnwhi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gaohongyu789.top/Article/details/gtjmduimsp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gttieanbvz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtewszvuyx.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtapcqcmnq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gtfcremrft.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gtgfwumura.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtrkfbbusj.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gttllehwph.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gttjbbjklu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvshfrxh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gtqvgtjykr.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gtdaxcspiz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gtlerfawue.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtbvtuzkmi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.mhx1999.top/Article/details/gtrababxfr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtxzrghrmw.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtaptmpejv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtkbiuktbc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtdefkzvkm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtzaybxath.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gtwkdowdoo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcguomxwv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtzlczkxcg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtilbmdurj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulvynadq.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtrxmatgcl.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtmjnbqbla.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gttlspqbot.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtkcqvnyzz.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtcrhxmitp.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gtlvrthfrk.html

Go:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbmecnub.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gtosgzuruq.html

C#:   list.Count;
来源：http://dali.smart0.xyz/Article/details/gtucxcsbza.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhprosyk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvbabvpp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtkmxyvjwi.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtfdebnzvg.html


<!-- 参考信息 -->