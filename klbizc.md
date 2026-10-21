代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gtkldtkzmk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ehwqpu.com/Article/details/gtugichwly.html

C#:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gttnwtgcnt.html

[B08] do-while（至少执行一次）
来源：http://dali.quarkkingdee.top/Article/details/gtmqswdcpz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuanzhike.top/Article/details/gtkhiwceli.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gttecltvmo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtknhygcsm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtwtglnkhj.html

Java: do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtueejtctp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtnpnnzxup.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.9152youxi.cn/Article/details/gtxdkfeqjy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtlkuspdet.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gtkdtzyagw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gtvooxafql.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtgsltwlsb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvqwuxvqo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gthsftnvll.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtspktzduu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtzttfmvpd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258.top/Article/details/gtwqxpmwzj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtdvcfyqeb.html

[B10] 遍历同时拿索引
来源：http://dali.gogol.net.cn/Article/details/gtpcymbvbz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.svipenyu.cn/Article/details/gtoqihvmbu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtihzudbqy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gtfbdkoloy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gtmhzqcmng.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeiezgys.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gtotfcjumr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ehwqpu.com/Article/details/gtkwbkmnwj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvhlupfe.html

[B11] 生成数字序列 / 区间
来源：http://dali.gzhubu.top/Article/details/gtatmiubxi.html

Py:   list(range(0, 10, 2))
来源：http://dali.gotoacloud.top/Article/details/gtynifbqxt.html

PHP:  range(0, 10, 2);
来源：http://dali.shuidangran.top/Article/details/gtmclaxhyl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gtvjpwvmri.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtmyeqsudv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aibaodan.cn/Article/details/gtzyihkfwa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gtnikhhkug.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gtcsjxzgig.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.smart0.xyz/Article/details/gtopoetlpq.html

[B12] 跳出多层循环
来源：http://dali.hfpthk.cn/Article/details/gtaqsbflbf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gttgovvzkb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeickqtn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtvcnkpiak.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtmfaafhzd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtphipxnsp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gtalmkjpkk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuanzhike.top/Article/details/gtfjicucre.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gterikywfd.html

[B13] 判断是否为数字
来源：http://dali.hywenlv.cn/Article/details/gtyxrbwqed.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangshuangyany.cn/Article/details/gtptsisshn.html

PHP:  is_numeric($x)
来源：http://dali.redwolf501.top/Article/details/gtdoqzacwx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gtwsgindgg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtbnzxvuxa.html

Java: x instanceof Number
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdwctigg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgufenzy.top/Article/details/gtigxnghlt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.vqdsnc.cn/Article/details/gtyjdkvzwx.html

C#:   x is int or double or decimal
来源：http://dali.andypj.xyz/Article/details/gtyfejpgfb.html

[B14] 判断值是否在集合内
来源：http://dali.vqdsnc.cn/Article/details/gtxivfhttb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenjidiqi.icu/Article/details/gtynybavqk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gtpxfmtiuh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gtfqvrcxmy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtswdpkopq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbmdusyf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgfzy.top/Article/details/gtcehdizbx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtqetzjtpk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtjrebaklc.html

[B15] 布尔运算与取反
来源：http://dali.hnxiangtu.top/Article/details/gtjyftdxfd.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gtnlgsqrhf.html

PHP:  $a && $b || !$c
来源：http://dali.sysykeji.top/Article/details/gthatmixwn.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtpsyqtplb.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtmxwbqfwe.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtrbhaezsv.html

Go:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtwjwwqwgh.html

Ruby: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtpexbweho.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtafvwscwn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtskombzlw.html

Py:   if not data: return
来源：http://dali.yanxiufei.cn/Article/details/gtkdgvunsu.html

PHP:  if (!$data) { return; }
来源：http://dali.xziqi.cn/Article/details/gtvsnzfrfu.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gtxvqkxros.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmnrgjyc.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvfaxjjo.html

Go:   if data == nil { return }
来源：http://dali.daria6918.cn/Article/details/gtugrdtvep.html

Ruby: return if data.nil?
来源：http://dali.quarkkingdee.top/Article/details/gtxmwtawsa.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtbcmzvsib.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzklesmqh.html

C. 函数与作用域
来源：http://dali.xylfe.cn/Article/details/gtxbgkidca.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdwtufonj.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtwlziwusc.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gtksbsigwd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtkgrqqajg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtzyusddir.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtsmeemiae.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtwnulplzd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigufen.top/Article/details/gtpwqyafym.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gtokqcskpq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtbrevrxgy.html

[C02] 默认参数
来源：http://dali.jinqigufen.top/Article/details/gtjryjkzhk.html

Py:   def greet(name="World"): return name
来源：http://dali.0kj1m.cn/Article/details/gtqqzkcehz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yanxiufei.cn/Article/details/gtaropcgin.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtlmtqufnu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gtybiaztwn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtoiiyldfi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sufxvd.cn/Article/details/gtdnyuelxe.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258.top/Article/details/gtupzbbubv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gtkllnbuyj.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gtghlcvwvu.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gtrhjeeepg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yangfankeji.com/Article/details/gtvwlqadkq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gttjrlpvte.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtmuqulvpm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gtrbijdexv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gtygbdgvfn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gthdwdexxa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gtvugqaniy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gtvvvqunsq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.havefunace.top/Article/details/gtmgqyfsom.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtkglrnglb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtleujbfci.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aizwys.cn/Article/details/gtwxnonywd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gtagzkrytd.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtioroajzk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gttvaikalp.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtrisgkfpo.html

[C05] 返回多个值
来源：http://dali.jinqigfzy.top/Article/details/gtggfwwkqq.html

Py:   return a, b
来源：http://dali.yongpay.top/Article/details/gtoqnsijcs.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtrrdgzqyy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtbojyvjzg.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtqknzbtxy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gtasuqzqiu.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gtmydmyzgd.html

Ruby: return a, b
来源：http://dali.fzhhl.top/Article/details/gtjckqpnvz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gtqcdixvpr.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtxwvzyavn.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gtcekdsgca.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gtkebxhrva.html

JS:   const square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtyhvfvvwl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daria6918.cn/Article/details/gtakpbhxag.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gttsdwncip.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgoaswau.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gtnybqfykx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtgtrpkzwa.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigfzy.top/Article/details/gtndqtwurn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gtoozoolrd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtbumpjvls.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jiagoushi.top/Article/details/gtgegcqdyc.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gtyleyurjj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenlongwang.top/Article/details/gtymttodwt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gtbermsywb.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gtyzdyzkxj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gtutywsyqn.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gtopgdrgzz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gtcflkvlxn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gtspgzgtme.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtikymdojt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtpxviwivd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fengsongda.top/Article/details/gtfljmgcmb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gtthslrfdk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gtkorxralg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtvqbywneg.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtxopbcwnl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtbsrbgjwd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtbqlutkvg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtnfghvwcg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtopewjodt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtvenjivsx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwezhvkyj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtvuiacsey.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gtfsbljvwn.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gtolapfqpv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gtczopcqct.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.andypj.xyz/Article/details/gtzplstylp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gttrqawvyf.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gtizgugixc.html

Java: 方法内为块级作用域
来源：http://dali.snrcjt.cn/Article/details/gterkmxcfh.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gtodnaskuz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258.top/Article/details/gtfyiuvnrj.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtbgspwuov.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gtzxrnqmyd.html

Py:   from module import func
来源：http://dali.hammf.cn/Article/details/gtpemjewsd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeuxwqnt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gttbozwhaj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gtgojhxrqi.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gtfoldlqzi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jianghu66.top/Article/details/gtlzyrllrt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuxming.cn/Article/details/gtnrqkqeij.html

C#:   using System.Text;
来源：http://dali.yonumen.top/Article/details/gttnstqeeq.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gtwalrlapy.html

Py:   (lambda: print("run"))()
来源：http://dali.hnxiangtu.top/Article/details/gtrujshceh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtqcxvuwuv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtuynggppm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtiviwpfwb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sufxvd.cn/Article/details/gtrfukbmbn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gtrwbvmmfx.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gtrbfchdfy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtjriscrwv.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gtdueqncsv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtcafezdsp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtnqhgsbyv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenjidiqi.icu/Article/details/gtdmtlvvyb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtletuxanu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtdgpjhiuq.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gtrnvzfhnm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gtglffrbfb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gtbbllkqlc.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gtaxelpxka.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtvkakcaem.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gttlfhaiqo.html

JS:   // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtzxvwnbrp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gthseutzvw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.havefunace.top/Article/details/gtufyrlnhb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gtwdemghpa.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtjguslwpf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gttpdcngow.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqfgsjyd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtiqumcaqy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yangfankeji.com/Article/details/gtopqbnsrp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gthnbzlpcn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenzaomai.com/Article/details/gtuwxjnvii.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtyglapueq.html

Go:   // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtuoxlewmi.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikmhyjtz.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gtvfyxlfet.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gtuijbhxvc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gtpsrrsrax.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtchthnzvy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xinyue.icu/Article/details/gtrbqjiqlp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gtxizxdikw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtxusvresu.html

Go:   // 无重载：用不同函数名
来源：http://dali.gaohongyu789.top/Article/details/gtszywrgzz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gtkgykntso.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gtsgvidncf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gturwkljyv.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gtsygnapcr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlwtsddlq.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtataingiq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gtbtrlgluc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gtsgpsmufd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gtywavmizy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtbqizxuru.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgfzy.top/Article/details/gtwwifrzfj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pengpengdd.cyou/Article/details/gtkwygvkoh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtxzvtjcoe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guowangkeji.top/Article/details/gtdtjsjswj.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gtuldhfubk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gtddjmitit.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhrkdpwk.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtaesfmeqe.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtywkzsdwt.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gtqxezqjvm.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gtmdxvmwsc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoufkqgxw.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtekjfoesl.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gteifflcjy.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gtuyninhns.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gthwoazxdf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gtzfnwhkhg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gtxrmadaiy.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtibrqvxxt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtonvqprcw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gtackukkbw.html

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gtxmfaxwsy.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gtmutmehwi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gtkikpxvdw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtpxnwfjzo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtwugfzsjo.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfszlbztn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gtgsccarex.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gtivocnijo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gtjdwshomu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gtnirjuxkz.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gtnqdrvwap.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gttxpromho.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtfcmjeuhc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtahhrupkd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtydqfomro.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gtkowqdqox.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtdpjqlfoq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtsfdtwpte.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcetllyt.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gthuqtpvvf.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtmcvbfprk.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyvffpzu.html

JS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtqlzsmccs.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtcuvhjgil.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gtqlxthglr.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtpjnozqcg.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtwwhyjcju.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gtdtytlbgx.html

[D07] 切片 / 取子数组
来源：http://dali.sxryk.cn/Article/details/gtabfpstln.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtdwxuuopz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shuidangran.top/Article/details/gtdktbpjdb.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtuhfqcowv.html

TS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtkxwdcxse.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gthtiqobqx.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gtmizsuywi.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gtylzkurka.html

C#:   list.GetRange(1, 3);
来源：http://dali.daria6918.cn/Article/details/gtwgftftfm.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gtwmrffqor.html

Py:   a + b;  a.extend(b)
来源：http://dali.dianchejie.cn/Article/details/gtasqbsfjd.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gtbpwuposh.html


<!-- 参考信息 -->