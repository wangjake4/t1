代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sxryk.cn/Article/details/gtmornngsz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxuanxn.top/Article/details/gtxssnmymr.html

C#:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtomphvbgf.html

[B08] do-while（至少执行一次）
来源：http://dali.ehwqpu.com/Article/details/gtjwvxwdyo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.haohaochexian.top/Article/details/gtyzxjrdas.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtpkdneqsx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsjksknf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtzeiaeusb.html

Java: do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtguuoeejl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gtsbsdvhpj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwibigbe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtmavmnfxo.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gtykwefnhd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzbyrjwx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtgwzjrdmk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtsrtbrrxw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtkawvjled.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtwrtcmnmg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sweek.top/Article/details/gtfxuhaivl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gtiurjahib.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtmmdvssqy.html

[B10] 遍历同时拿索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzxpcxit.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtrgykgfcc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gtrgkvnphs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqeqlnijm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cucudq.cn/Article/details/gtkalhnksi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gtfybxtwna.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gtdhehubzs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.9152youxi.cn/Article/details/gtkoaaphyy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cqqwz.cn/Article/details/gtczdfzhyr.html

[B11] 生成数字序列 / 区间
来源：http://dali.cdnleiting.top/Article/details/gtqfovtddp.html

Py:   list(range(0, 10, 2))
来源：http://dali.svipenyu.cn/Article/details/gtjzqarxbx.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gtbtbqpctu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gtewgrtirx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtmttbicmm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ppjwa.cn/Article/details/gtecxftzqu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gtylnvxldz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jyoumei.cn/Article/details/gthwfdzlgn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gogol.net.cn/Article/details/gtffqynckt.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqrtnqlp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenlongwang.top/Article/details/gtzsrspxrb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zycfv.cn/Article/details/gtkjyvgiow.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gturibmltu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtbagiupqa.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gtjqjexmqw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gtbloljcvw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtmmepzcdk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.haohaochexian.top/Article/details/gtwxgvfylw.html

[B13] 判断是否为数字
来源：http://dali.ydzc1.top/Article/details/gtmgxsllda.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlzrogsd.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gtxdzwmttw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gttknnidwq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gttnnlllzl.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gtmrcabyqe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gtmutsuogr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yongpay.top/Article/details/gtuczcxwel.html

C#:   x is int or double or decimal
来源：http://dali.zhiwuduotai.top/Article/details/gtxrsmuquf.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gtoyabuezq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ydzc1.top/Article/details/gtwoijybyz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenlongwang.top/Article/details/gtozokxnws.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gttcojkcpl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtybbenbxd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtropqjpqu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.kuanghao11.cn/Article/details/gtcdypxudh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gtendzjlbm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtpnrxgqnt.html

[B15] 布尔运算与取反
来源：http://dali.feifeiyinyue.top/Article/details/gtnhxehogg.html

Py:   a and b or not c
来源：http://dali.iojbl.cn/Article/details/gtqwstdnxh.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gtuijevyyn.html

JS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtmubicoyd.html

TS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtyroxbccq.html

Java: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtosolhjxd.html

Go:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gthpcbiyek.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtctirmrci.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtilxjeyil.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtncmervnn.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gtwviprjzj.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gtwpiapbom.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtomvqctig.html

TS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtzakscunp.html

Java: if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtfxeadbpe.html

Go:   if data == nil { return }
来源：http://dali.jiagoushi.top/Article/details/gtsrgoinpm.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gtcxcceoue.html

C#:   if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtxapvcbvh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtwkzzltsc.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gtnyqogoet.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtogtjzski.html

[C01] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gttksqzhab.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gtusngdbym.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtiuwljqen.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtktwtpdzc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtephaiteg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbknwrhou.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtsippxouv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.mhx1999.top/Article/details/gtjiltijgw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtivqejqbz.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtjgqduduw.html

Py:   def greet(name="World"): return name
来源：http://dali.nwbrower.top/Article/details/gthyjkdpjx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.iojbl.cn/Article/details/gthzdtwjrd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtvkhicxrv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtdoonbdzi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gteqelufxs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fengsongda.top/Article/details/gtepcjqmot.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gtmdiykgjp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gtpdrnpnvb.html

[C03] 可变参数
来源：http://dali.hongshengwenyu.top/Article/details/gtjxgeyjzy.html

Py:   def total(*args): return sum(args)
来源：http://dali.bjfxy.top/Article/details/gtmvffuaei.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xinyue.icu/Article/details/gtjstwhrkl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gthavxjzdv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtjtvtivhp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gotoacloud.top/Article/details/gtnuqjmkpd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gtszxgtuss.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gtywmusaqt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gaohongyu789.top/Article/details/gtqowioteb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gtacchoiaz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jianghu66.top/Article/details/gtdqrclkig.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtcfmellnc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtlqepymkg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gtvsrsxbqi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenzaomai.com/Article/details/gtywylqgsm.html

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gtajvasmhz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtdtzaqsts.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtmntkzjjx.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gtysuqyzfv.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtwzgsuojj.html

PHP:  return [$a, $b];
来源：http://dali.dashuyun.cn/Article/details/gtmtmdluss.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtvxlssico.html

TS:   return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzkcxnpy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangdashe.top/Article/details/gtgpqxvzel.html

Go:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtlpftxkrt.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gtrnfymarn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258.top/Article/details/gtgphumegf.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gtmzlkkikh.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gtspjuyomf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtcqmgdjks.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtmbdoofrc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtqybhchlq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtdldnaaid.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gtiwwjesai.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgufenzy.top/Article/details/gthhlvuzfl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpvjrxmw.html

[C07] 把函数作为参数传入
来源：http://dali.guannengcc.top/Article/details/gtyxwufxqo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gtgdlxyfrz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtepecntyn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gtaccuczgl.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gtyhvxtrbp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.svipenyu.cn/Article/details/gtcvrivytr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gtrmdbxpoy.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtylktgtmc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gtogbvkdrz.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gtngrtwwdm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqmbqxxo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gtpyolbmdq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtpcxnnrgx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtjlfjubvl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtbachckhv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jyoumei.cn/Article/details/gtumzqwwre.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sufxvd.cn/Article/details/gtpbfgflbf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtxevukiii.html

[C09] 递归
来源：http://dali.daxiang520.top/Article/details/gtknhsmayr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtfxaszrtk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtcnelicgc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtotvcbtyl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtntqjufkr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzmyfyil.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gtqyggoflu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtxrwfqidn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gttogtshnm.html

[C10] 变量作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtxgsmejgw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yangfankeji.com/Article/details/gtmpqplqod.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.andypj.xyz/Article/details/gtnxcgqkqq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gtnitpredw.html

TS:   同 JS
来源：http://dali.haohaochexian.top/Article/details/gtnfvlcrgk.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtmcvzaexe.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gtlodoeycq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gtvohgkhbk.html

C#:   块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktohbayp.html

[C11] 模块导入与导出
来源：http://dali.zhoulong.xyz/Article/details/gtwamzbypq.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gtozdevdkz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.meibo888.top/Article/details/gtpmapcula.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.316326.xyz/Article/details/gtgqyactni.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jiagoushi.top/Article/details/gtopkknfhg.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gtqvvvennw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtozgkjkyv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gtazpsapdd.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gtmfdpiqov.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gtfafybvom.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtnfomtgfs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pycfn.com/Article/details/gtuwehiafb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtugmrmyuv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtmrdtlxlp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtvxxqbvnw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtnqgejtin.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtzoskgzdz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtgpmruiqq.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gtjxxghptn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gtkvtyrifj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwpbocqs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnxiangtu.top/Article/details/gtutxtqqgo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtrjewwtwt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtshjanhnm.html

Go:   func add(a, b int) int
来源：http://dali.yangfankeji.com/Article/details/gttyitjbhs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gtrhcjyuyw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpasbhjgv.html

[C14] 泛型函数
来源：http://dali.chenlongwang.top/Article/details/gtrlyxspfq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gtqnatalve.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtjhqfkabr.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtxrtcwlll.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gtschcpuhm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuanzx.com/Article/details/gtsmwqompk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gteqcsxpba.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gtugmoceik.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gtuaerfbbx.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gtckreujpo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pengpengdd.cyou/Article/details/gtemqiycat.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangdashe.top/Article/details/gtassjlpcw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtgfbrvqsx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gtqakdtodj.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gthastfnmf.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gtvkwbnmbw.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gtynuwjncu.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gtrldmzfsu.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gtnlsmajhw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gtenhnbmal.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gtuhtpudpt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gtcvwzrekn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtqgkeyhno.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ppjwa.cn/Article/details/gtszmqxlkk.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtyfkwrwwb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gtrqijdubu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gtywibavfu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxvyealy.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gtlcywcwis.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtpnohxygl.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtnrvabrtt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gtaczgzcly.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtzcpkdjjk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtihpifwfy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gtfccvdqgz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtrflntoau.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtqupocbiz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtwemvgyxd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtpbyiysrx.html

[D02] 追加元素到末尾
来源：http://dali.pengpengdd.cyou/Article/details/gtmpxziqhc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gteyiabfkw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sufxvd.cn/Article/details/gtlyhgcgth.html

JS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gttbtgaaee.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gttqskzqex.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gtzesoyjcq.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gtrvofwuub.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtrwyzqhqe.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gtchwyijpy.html

[D03] 在指定位置插入元素
来源：http://dali.dianchejie.cn/Article/details/gtllkmhmhq.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtgyfyfxdb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gtidtywpej.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtfryiowxn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gtobkzlbfv.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmyvepom.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtqqoarhlw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtdzxhqoyd.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtatbfbawk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtwlxucjik.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtvowspnqf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtnpqklgpg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gtmvblckmh.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gtnlhoifzz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnqzz.top/Article/details/gtohqkcate.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gthbhtnkfh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jiagoushi.top/Article/details/gtgnbhyfbs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gtdaqgkubc.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gtaueacxbd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtmnuakfpd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtcyovlgec.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtnwdtegls.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gtclcslkpv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gttovajopv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtirvvernl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtwiijeffv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtgyqnevsz.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtnjdcdrls.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtztujfhoj.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtqdgmcuqx.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtzqjzookc.html

TS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gtwsqbnynt.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gtewvdffsf.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gttfkylawr.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtvzqpiiaj.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gtohwxmmbm.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtjomvebbs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gtxybfqwsr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gtpbewkary.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtealibpod.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gteshdbpsm.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzjpadkh.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gtekzxapfp.html

Ruby: arr[1, 3]
来源：http://dali.jqgfzy.top/Article/details/gttykqihze.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcncmtcqu.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gtjvykgwtq.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtqxqanaip.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gtfihnkghc.html


<!-- 参考信息 -->