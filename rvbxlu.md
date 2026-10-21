代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhoulong.xyz/Article/details/gtuvxyhqdj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gtuewpmxaf.html

[B07] while 循环
来源：http://dali.tianlin.xyz/Article/details/gtiplaitro.html

Py:   while i < 10: i += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtynqvxlum.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sysykeji.top/Article/details/gttnfwviwn.html

JS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbiiyajkj.html

TS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtrluijjcx.html

Java: while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gthysbgimb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.birdmap.top/Article/details/gtloavplio.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gtbthpfvou.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtrkiakmfi.html

[B08] do-while（至少执行一次）
来源：http://dali.sxryk.cn/Article/details/gtormbaagz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zycfv.cn/Article/details/gtxtyydwmb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtjsrrmmpg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtnmavvweq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtyawvtpma.html

Java: do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcylwhoa.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gtawvprovf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guannengcc.top/Article/details/gtsrzxxgpa.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtlpalwatg.html

[B09] break 与 continue
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocpensrl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gtbctsmrkp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtcewvozvf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtfeofqauc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxzitdqdw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtfqjhowoq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gteirveqnm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gtisyabhxy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtmnuibarb.html

[B10] 遍历同时拿索引
来源：http://dali.yuanzhike.top/Article/details/gtocpniagy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ppjwa.cn/Article/details/gtlpqyzxyq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.9152youxi.cn/Article/details/gtdqawqhoi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtvhiqosod.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gtkczpyfow.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gtkxpdeszc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ehwqpu.com/Article/details/gtywqiyngw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daria6918.cn/Article/details/gtiizewadg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtrxgmkqwo.html

[B11] 生成数字序列 / 区间
来源：http://dali.daxiang520.top/Article/details/gtyncwmzvs.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqelxwsl.html

PHP:  range(0, 10, 2);
来源：http://dali.daria6918.cn/Article/details/gtrwpbsnqe.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtxenurihp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtzmymkfwl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtainnbnmd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nwbrower.top/Article/details/gtdiaxcybz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.kuanghao11.cn/Article/details/gtsjlgggce.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gzhubu.top/Article/details/gtjkdwjyfw.html

[B12] 跳出多层循环
来源：http://dali.zdqjudy.top/Article/details/gtdbkwlbzn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhixingplan.top/Article/details/gtmjvzkokn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnqzz.top/Article/details/gtoeqtanho.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gtnenanqgb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtkmbpardg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtlwqvialy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gtwkhqptwt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.iojbl.cn/Article/details/gtnwycadpg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gtnjnbitpr.html

[B13] 判断是否为数字
来源：http://dali.wangdashe.top/Article/details/gtkbtpzitt.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenlongwang.top/Article/details/gtvklzwvjx.html

PHP:  is_numeric($x)
来源：http://dali.svipenyu.cn/Article/details/gtgbzgnfzz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtmsljhqja.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtqxqdgshe.html

Java: x instanceof Number
来源：http://dali.hysaishi.cn/Article/details/gtheguujwg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yongpay.top/Article/details/gtdqpehmqv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hongshengwenyu.top/Article/details/gtkhrjizes.html

C#:   x is int or double or decimal
来源：http://dali.yangfankeji.com/Article/details/gtfcyymijk.html

[B14] 判断值是否在集合内
来源：http://dali.gogol.net.cn/Article/details/gtquvlmcgt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ydzc1.top/Article/details/gtuemjytgw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gtfbyoiagl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtvuftenbd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtqbtvfycs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shzxlz.cn/Article/details/gthjvnacls.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gtdxikbbgj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nwbrower.top/Article/details/gtgnalppim.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtitfpzxjj.html

[B15] 布尔运算与取反
来源：http://dali.hnxiangtu.top/Article/details/gtmdajucye.html

Py:   a and b or not c
来源：http://dali.cashguo.top/Article/details/gtxzgajnrt.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtlkcbikvj.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtppweigng.html

TS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtviyfsyne.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehyloppl.html

Go:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtfqbyemaw.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtyffzukfe.html

C#:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtzeroawej.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gtugqrdkec.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gterhgqebf.html

PHP:  if (!$data) { return; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnufkaga.html

JS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtmhillkze.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtivsnwcqn.html

Java: if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gtlmjzrlyk.html

Go:   if data == nil { return }
来源：http://dali.tian-w.cn/Article/details/gtscojnjej.html

Ruby: return if data.nil?
来源：http://dali.jianghu66.top/Article/details/gtdzaclhdl.html

C#:   if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtvamzjqni.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpoosiudi.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gtzewpjppm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxbhijcy.html

[C01] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtvxeahhev.html

Py:   def add(a, b): return a + b
来源：http://dali.fengsongda.top/Article/details/gtvqwqixti.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtfjnvblvh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrjtddato.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjstfglwy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtpdvclrpr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtwocnmwxg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gthvilbjog.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtdnixwicb.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gtmcckjmem.html

Py:   def greet(name="World"): return name
来源：http://dali.birdmap.top/Article/details/gtjxbwjibk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhongyouzk.top/Article/details/gtleapzpag.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrntzmnbs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtjcyafdzr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtptawwbcz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtosphdwjx.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhoulong.xyz/Article/details/gtetavhxvh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gtauowhhis.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gtjhayspuv.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gtfvsfugry.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gtlanzcfwl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtpyvwdpqs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtwckxrevn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gtykyrsxdj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aibaodan.cn/Article/details/gtidtrsnnc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtgqfhxmeo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gtmupavobv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gttmajsncp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gtwinyhlxo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gtimiltkrm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtqlguolua.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daria6918.cn/Article/details/gtzhycvtot.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jianghu66.top/Article/details/gtjevpalwz.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszpjuqkw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtexslmumy.html

C#:   f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtgkmhfmzi.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gtfuerxjff.html

Py:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtpkvgfedt.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gtybwlmcfn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtspgrexpy.html

TS:   return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtuyjdhzat.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtfnpoquzc.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtjzvnmmgs.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gtlbzslgzk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gtmvszyctg.html

[C06] 匿名函数 / lambda
来源：http://dali.zhoulong.xyz/Article/details/gtcsoribzs.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gtrglcthcl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtixfnulqv.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtiwnwevss.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtrivscphf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtigpsmvxv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gtbzzsdewi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sufxvd.cn/Article/details/gtdyahzyni.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtugctxmha.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gttyanaslh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtminaythe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gttxzjcbyw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gtrvtbpydf.html

TS:   arr.map(String)
来源：http://dali.sweek.top/Article/details/gtvqjsbins.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtivvagkcj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gtkojnzlnu.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gtgxjnetbc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pycfn.com/Article/details/gtmubgrbfz.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtkmbhwlmn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gtoyeufpta.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yvedp.cn/Article/details/gtyeljrdug.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtmcwpqqtt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gttygrjfhb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigufen.top/Article/details/gtceqxlmpq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtntcjakkp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhixingplan.top/Article/details/gtxbnvktto.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtzdnvntae.html

[C09] 递归
来源：http://dali.yangfankeji.com/Article/details/gtivlzbovm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtechytodg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtsorwakxn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtgcffhcme.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtqwukyydp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtbavmuqfv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gtncbkzdjr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtymaamqhf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gzhubu.top/Article/details/gtaqyftrvw.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gtlbkrewie.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gtwveoelot.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gtknuujccp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtampmrddd.html

TS:   同 JS
来源：http://dali.yj20258888.top/Article/details/gtwmygjojs.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiujgwgv.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gtriignrtm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gtvlssbctw.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtgbsdrcsp.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gtkeuglpfn.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gtizwsrctl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtlewwmbbh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gttpsopxev.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnxiangtu.top/Article/details/gtlpfvtfrb.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gtoiaxrqjp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gtrgrhxbbe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258888.top/Article/details/gtkqnlgbnh.html

C#:   using System.Text;
来源：http://dali.yanxiufei.cn/Article/details/gteswtkbxy.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gtjwotmulr.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gtxswuffyy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hammf.cn/Article/details/gtmaicnebo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtyjpcnazj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtgssvpffp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtbhtteflt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gtcweugdop.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gtufrzsvwt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenzaomai.com/Article/details/gtkmazzfcy.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gtjjfudlrs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gtiebzqfyl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtuvrjkamz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gtmkvaszqr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtiudrjavo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtmcflzeaf.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtyhtxeppd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnjxffef.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gtwkxmrtdx.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gtktyobgqj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gtxnabgrfh.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gttyomtswp.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtcbualvba.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gtjgfwszts.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gtaemxlfkg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gtjiymhvem.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtbjxretku.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhongyouzk.top/Article/details/gtsbqggjmk.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtgrxuxjlv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gtuaerpmhd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gttlpsmwpo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtytgebajz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgfzy.top/Article/details/gtnxpkfjav.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtmioexjpw.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gtngcvlfkh.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtidtcidlv.html

C#:   var (a, b) = pair;
来源：http://dali.ppjwa.cn/Article/details/gtnqqgyizp.html

[C16] 函数 / 方法重载
来源：http://dali.0kj1m.cn/Article/details/gtrnhyjzxf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gtwzcebztd.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gtrfqistlt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltwmvgmc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gtksknazts.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xylfe.cn/Article/details/gtiwtgjnfc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zdqjudy.top/Article/details/gtxynclvhq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gtfyytocjb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gtumshbapr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthsqimodt.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gtgcqpmbgf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmvmezbdt.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gtqdjpxeqx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gtvsfzpexx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gtghesqwdv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gtrbnmmrmo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtbjzwqavt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gtguhwfbom.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtetxuwizd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtsscakabq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gthusfwqvq.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvspklzj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gtwfofnziq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtovlvrffn.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtulcrcabw.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gttozuwhtd.html

Java: list.add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdwgermu.html

Go:   arr = append(arr, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtycapqesb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.316326.xyz/Article/details/gtnxjbwauo.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gttcohxipg.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjzvtjqy.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gtwlccjxvi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gttgyxbbfc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrrdssbm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gthxzjxueo.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtuzgnbbpl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gtuvzkboyo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtvbidppcj.html

C#:   list.Insert(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtkyfxblpi.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtdjqymloj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gzhubu.top/Article/details/gtybyuuffh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gtsygbjmil.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gtlywpwspe.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtdwznscxn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gtalbbqxhr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gttyxgferf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yangfankeji.com/Article/details/gtwwpiljsz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gtiswgxbiy.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gtosiqbyia.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvcmuzvj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtywwmwlhe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtewyjjjwq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gtwsguxgen.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtmelwliay.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtfoagtwkr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtwotycudu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gturhksaqj.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtgaxllgop.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtwoyqrrtb.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gtnufhrvow.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtyitifrog.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtpccesepk.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtthvogbnd.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtsqnchanx.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtdieidpnd.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtyiceaind.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gtkqsrslan.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gtcjdsknst.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtyjvxnnvx.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtjkswjvrs.html


<!-- 参考信息 -->