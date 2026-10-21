代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuanzhike.top/Article/details/gtntxzgcsb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtkgvmfrws.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtrgwthnwk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtcxniaooc.html

Java: do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtfgvxdvkf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cdnleiting.top/Article/details/gtqjtmdvtj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jianghu66.top/Article/details/gtefxywzsw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtzfupbdoz.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gtpulyvdpf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.bjfxy.top/Article/details/gtoecswltc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtfobtwedo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtttsiajuf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtsbpnfchg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtpmumbmal.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tianlin.xyz/Article/details/gtvxuupmzn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gotoacloud.top/Article/details/gtsyuzvrio.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtqrwpaffw.html

[B10] 遍历同时拿索引
来源：http://dali.cqqwz.cn/Article/details/gtlpuiohon.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.9152youxi.cn/Article/details/gtelcsidij.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gtiuntrpbe.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gtloskvsfc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtjyevfiqm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gtwiuzxmtw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.c1oappe.top/Article/details/gtqsaskmxa.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.birdmap.top/Article/details/gtpccoghhq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gtqhbzvvas.html

[B11] 生成数字序列 / 区间
来源：http://dali.0kj1m.cn/Article/details/gtvslcpbym.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gtgpweoilm.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gtrfhrkbnh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gtnupukikd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtrvotyfhb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sufxvd.cn/Article/details/gtxzrhmyda.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxuanxn.top/Article/details/gtefxjtwsh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cdnleiting.top/Article/details/gtmnxgaurr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gogol.net.cn/Article/details/gtaywjqbva.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gtpbidezuf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yanxiufei.cn/Article/details/gtulshzdnm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jianghu66.top/Article/details/gtqclxburj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsdxryej.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtedlfnibn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gtbuhvsvqs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.pycfn.com/Article/details/gtwjwlaawm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gtukzvolby.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daria6918.cn/Article/details/gtbfjcuyly.html

[B13] 判断是否为数字
来源：http://dali.hywenlv.cn/Article/details/gtevdeedwh.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gtfqjcfneu.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gtmzxzkrtp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gtazsjssdv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtlzrnddee.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gtciapvnqy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yangfankeji.com/Article/details/gtfqdbzffv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.kuanghao11.cn/Article/details/gtzjimmqud.html

C#:   x is int or double or decimal
来源：http://dali.zhixingplan.top/Article/details/gtrcqrdvpv.html

[B14] 判断值是否在集合内
来源：http://dali.svipenyu.cn/Article/details/gtasflyphw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiypwdaej.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gtyhydgwug.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gtxuhgcivt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gtekuxymzp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtddnyypar.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gtrrpeutzn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtnckpwrow.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtlgkqizql.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gtugyaejnx.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gtmxrcfuir.html

PHP:  $a && $b || !$c
来源：http://dali.havefunace.top/Article/details/gtabqbuheo.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpluolqjg.html

TS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtsqfchgxo.html

Java: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtrtyulnfb.html

Go:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtmqbpshrr.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtjdrlbeen.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkmvadsd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenlongwang.top/Article/details/gtvylihxrk.html

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gtyfvclysd.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gtppjsxbvo.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtrpmubqop.html

TS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gtxffrhyoa.html

Java: if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gtdkbsedpo.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gtecczfnsw.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gtmhivnnjg.html

C#:   if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtrviaotuw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdxlwuoku.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gtojzzguyz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdaqzktes.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtteplmccw.html

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gtbthefpgc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtlxtcaplr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtybvcryvu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtsixftsxm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtiqbjkmso.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258888.top/Article/details/gtxpvskhjq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtcwgixcdx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtkgnitpxl.html

[C02] 默认参数
来源：http://dali.birdmap.top/Article/details/gtlkyzeoeh.html

Py:   def greet(name="World"): return name
来源：http://dali.cqqwz.cn/Article/details/gtcxvmfkns.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.andypj.xyz/Article/details/gttkpblrrl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtrotkmhos.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gteiehwlul.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pycfn.com/Article/details/gtebhxlxus.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphndmuch.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gtsebabjlc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtmhodcstj.html

[C03] 可变参数
来源：http://dali.dianchejie.cn/Article/details/gthefzrykh.html

Py:   def total(*args): return sum(args)
来源：http://dali.sweek.top/Article/details/gtstrjmecu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gtxwvophfo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxrnxkynq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtkpclfwhp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gthtqoilgz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gtjlpzfoiz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daria6918.cn/Article/details/gtylvsfqea.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gtarevpxvt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shzxlz.cn/Article/details/gtvokqjpub.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gtxpnkttjc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkpenmki.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtslpxsaiz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gtjqbcmafj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgufenzy.top/Article/details/gtirkxycru.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfvepzqh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtnadnhqgh.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtgbgqqnax.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gtagxvtdmh.html

Py:   return a, b
来源：http://dali.jianghu66.top/Article/details/gtamvptxux.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpohkiqpf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gttfdeesrn.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gtwgdghvxk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gtlxetatez.html

Go:   return a, b
来源：http://dali.xylfe.cn/Article/details/gtkxnnorrl.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gterwvwrhb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gtvwmxkdzs.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gtzvzpfkvk.html

Py:   square = lambda x: x * x
来源：http://dali.jiagoushi.top/Article/details/gtvsvnseyk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.andypj.xyz/Article/details/gthtowmrnp.html

JS:   const square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gtdmqtwfiy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtpkjqnvil.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtbidvubbr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenzaomai.com/Article/details/gtcplnurbe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtbfttflsm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtophkfgmz.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigufen.top/Article/details/gthlhiyydd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.snrcjt.cn/Article/details/gtyqzsnjwx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gtizggfkfz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtcwmypjmn.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gtpslemdiz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gtwgbpogcg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gtiwjnwcvy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gttrpglzai.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gtwjliyplk.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gtrpotostj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gaohongyu789.top/Article/details/gtbaqgamtp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zdqjudy.top/Article/details/gtsadzxtzu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtqnvtbtvo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtqgxslbcv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gtdkzcpryo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nwbrower.top/Article/details/gtqgpcmbvz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gtdsrxyofi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtpkczeoid.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gthunwgvts.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtrvtrpazp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtddpashwc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gthrplamgi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gthubehxkx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtyeagrafa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fengsongda.top/Article/details/gtutddcjpp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikqzgpjd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pycfn.com/Article/details/gthcyhtpjc.html

[C10] 变量作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezyvevef.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtvfdrdlva.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gttjfvqljd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxwwhtaw.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtammdvvsa.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gtacpbbzej.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gttwymmtdq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwbhwssn.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gtxidlgfen.html

[C11] 模块导入与导出
来源：http://dali.gaohongyu789.top/Article/details/gtkaabtazi.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gtpfwfdesh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jiagoushi.top/Article/details/gtsbsyhamb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gtdthwedpw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yonumen.top/Article/details/gtqpwnsszi.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gtsuqnrctn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gtibzamvvr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtdtgzxcuw.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gtmrglwjbl.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gtypmkdldo.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gtftqmligu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gtbkpsnerz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gthzittyav.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtpyozcbqh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nwbrower.top/Article/details/gtwfqoffuj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gtthtwbyxg.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gtlardyfqq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtgpdglsuu.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gthvvdkufv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtmuzajlvw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gttsvbphxp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yanxiufei.cn/Article/details/gtaxccnjik.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gthhmffyli.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gthzuazpyq.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gtwocysyxq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gtziqnhbfe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtoljnbcxi.html

[C14] 泛型函数
来源：http://dali.xziqi.cn/Article/details/gttyvayjst.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tian-w.cn/Article/details/gtybxqdyxk.html

PHP:  // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtzrnpfyrz.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gtmrzhzdeg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gtxxjhwlix.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtkuzpgxqg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gttegvxend.html

Ruby: # 无泛型
来源：http://dali.ydzc1.top/Article/details/gtibkjyksu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gtytwlokmz.html

[C15] 解构 / 展开参数
来源：http://dali.guowangkeji.top/Article/details/gtzgpejcku.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pengpengdd.cyou/Article/details/gtcumpkqyi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gtvjnqfeem.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gtewjviokc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gtplscsqmy.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gtcmnuvitn.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gtvjcixefn.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gtxlgkcjct.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtjttjimnr.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gtmijdkdxb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gtwcqkrauc.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gtfzrnqfpz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gtbmpsqgzq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gtqbdtyzlv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gtaopgjfjf.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gtqgxgldxd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gtlbepyikw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtcnavhwbm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcbxobeii.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlluwnfng.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtetciosoz.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtmlbwevjw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gtxvqufzcp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daria6918.cn/Article/details/gteirbltvo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gtqstokdwa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gtjlaptjni.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gtzlqgswwo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtmjtvezlc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gtdarlqnwd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gtzqxklspo.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gtcwsoptir.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yangfankeji.com/Article/details/gtyurgqlee.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenlongwang.top/Article/details/gtcyykqmqj.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtcfhypwrz.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtxlyvsmdz.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gtkennyxgo.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gtelcytgkr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtavfcyyrb.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gtferdzidv.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gtmvmogkmj.html

Py:   arr.insert(0, 0)
来源：http://dali.bjfxy.top/Article/details/gtomqorenf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gtnyswywce.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gtntpdyskr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gtqdqbpvjd.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtczpxzlnx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gtytnlntiw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xylfe.cn/Article/details/gtsoulaayd.html

C#:   list.Insert(0, 0);
来源：http://dali.316326.xyz/Article/details/gticmqgnct.html

[D04] 删除元素
来源：http://dali.sweek.top/Article/details/gtxjvcamhv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gtwggqcolc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.316326.xyz/Article/details/gtlsheraba.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gtyhzmraaq.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gtlpevuujn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gtsumtelxt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gtstuaeiia.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtovrwamyw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtpioegoge.html

[D05] 访问与修改元素
来源：http://dali.wangshuangyany.cn/Article/details/gtuzoavbav.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gterjcztlc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gthejcfqhr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtxamfmyan.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gtypneqhmj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gtpfoxltop.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtzygduuvw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtvarubmyv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtzpfwacvi.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gthqkligbx.html

Py:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtphzivdjs.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtixyexgvo.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtpyercqmp.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtysodbuvc.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gttfolgmxe.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtuxcivnzr.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gtpqljqihl.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gtxxwxzpci.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gtyautbtaj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gtqvhjexvj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gtsbtbcyyp.html

JS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtorckdnwv.html

TS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtlijpxpnk.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtfvsikwxo.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtmbluhcak.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gthqpzootk.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtupxspegy.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtfndxouso.html

Py:   a + b;  a.extend(b)
来源：http://dali.yanxiufei.cn/Article/details/gtoobjqegg.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gtqowgldqh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gtequyicrm.html

TS:   [...a, ...b];
来源：http://dali.zhengqikj.top/Article/details/gtxltkrdyz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlleveef.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gtwxwcbddo.html


<!-- 参考信息 -->