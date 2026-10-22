代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nwbrower.top/Article/details/gthrcylega.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yangfankeji.com/Article/details/gtnepoetgb.html

[B07] while 循环
来源：http://dali.xuanzx.com/Article/details/gtrovbldsy.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtghdzuyml.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jianghu66.top/Article/details/gtxmgreudm.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gttyhwfmsl.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtxdsceici.html

Java: while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtcacpxhop.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.9152youxi.cn/Article/details/gtzupgporb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuanzx.com/Article/details/gtdzlbybtf.html

C#:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtbrvlxpvs.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gtwvblfheq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.mhx1999.top/Article/details/gtwkljtntu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.daxiang520.top/Article/details/gtuhtalzwl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtcfpbvfbr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtcjtenjrv.html

Java: do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtibjcevmo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sxryk.cn/Article/details/gtiojxuemm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrrmrtss.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtrgbkcezr.html

[B09] break 与 continue
来源：http://dali.hywenlv.cn/Article/details/gtlyenoduq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhiwuduotai.top/Article/details/gtclglkiur.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtyaqgcecy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtsvftnsks.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtuvcxnrem.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtqcubrtay.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.andypj.xyz/Article/details/gtqexxfbxw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daria6918.cn/Article/details/gthngrnjke.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtczvrptnz.html

[B10] 遍历同时拿索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyprqwqty.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gtvwtwaaqm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ydzc1.top/Article/details/gttqvwndup.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtkyguikqw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtvlxzqzcg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zdqjudy.top/Article/details/gtjrwtqica.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gtejjoqjxu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hammf.cn/Article/details/gteueyvdyy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yuxming.cn/Article/details/gtethrvjaq.html

[B11] 生成数字序列 / 区间
来源：http://dali.sweek.top/Article/details/gttfmbmkwk.html

Py:   list(range(0, 10, 2))
来源：http://dali.fengsongda.top/Article/details/gtorunwnme.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gtczlpbwgh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.9152youxi.cn/Article/details/gtsjxrjeax.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gtwmstxstb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtnnewkopt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nwbrower.top/Article/details/gtyfbiatke.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhongyouzk.top/Article/details/gthurywmkr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtkejcnysc.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gtcsetoqjk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gtdvytclps.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.9152youxi.cn/Article/details/gtppfikajz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtytmokyjz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtooqimnhs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtklnybinf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shuidangran.top/Article/details/gtmthvviux.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnqzz.top/Article/details/gtpydteiyy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yongpay.top/Article/details/gtqrsgcsra.html

[B13] 判断是否为数字
来源：http://dali.wangshuangyany.cn/Article/details/gtpomdwemb.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gtcdckrglx.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gtpxtxaqka.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtftqqkqge.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gthnvcxgip.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gtlbuvwhtf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhongyouzk.top/Article/details/gtpvjibnqb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobcjbnfg.html

C#:   x is int or double or decimal
来源：http://dali.smart0.xyz/Article/details/gtwtbuxisj.html

[B14] 判断值是否在集合内
来源：http://dali.meibo888.top/Article/details/gtjcjylcnk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gttyqgbuql.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgfzy.top/Article/details/gtqydabhqf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtskbvjfda.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtuvinkeun.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dashuyun.cn/Article/details/gthkfjitku.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gtcxlheltm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtqakbqtmn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtwixacsou.html

[B15] 布尔运算与取反
来源：http://dali.smart0.xyz/Article/details/gthlnxfgie.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtopfzazll.html

PHP:  $a && $b || !$c
来源：http://dali.xylfe.cn/Article/details/gtmalblvbl.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtgllxffvi.html

TS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtzaijfubf.html

Java: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtenclxyeu.html

Go:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtjhvhzxvl.html

Ruby: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtxxevqxcn.html

C#:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtxjykesoe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gtemjmtcko.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gthbkcpmfz.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gtxymsgnbe.html

JS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtarrhgdjt.html

TS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtglgaixug.html

Java: if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtdckmncrh.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gtdrcdprtd.html

Ruby: return if data.nil?
来源：http://dali.haohaochexian.top/Article/details/gtvmfhxefg.html

C#:   if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtqhncvhgv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtrdzkpuuj.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gtyfsuaqxj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtsyjliexg.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtcmimkjds.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gtunaycvoq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtxfeeosqa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtbpickvbv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwhjlpcm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthntuhqgq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gtyzhwjxxg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ydzc1.top/Article/details/gtiysfltbz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtguktvsfx.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gtgspjcvlv.html

Py:   def greet(name="World"): return name
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpmxemlw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gtutgpbesm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtdjpaqonz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtqruvnbwn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gticrhbghn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gtjvximakq.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigufen.top/Article/details/gtfsyyecad.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcqxknnm.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gtnbtaeanc.html

Py:   def total(*args): return sum(args)
来源：http://dali.daria6918.cn/Article/details/gtprivivdq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzqdzycx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtfzcruxiq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuslehyr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gttllqavul.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gtgguvsodi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxuanxn.top/Article/details/gtatwpuqwd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtrgkuczjx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gtsijgttys.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gtrrlpzjdu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gtlpcpibgk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtevznmymx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gtheremsyq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gtqfkglgzi.html

Go:   // 无：用配置结构体参数
来源：http://dali.hywenlv.cn/Article/details/gtiynptasa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gttdfhlvql.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtazbjgbjv.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gtmqzdunah.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtecthwird.html

PHP:  return [$a, $b];
来源：http://dali.redwolf501.top/Article/details/gtkogkxjoj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtbhddyndk.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtpnlvfinx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gtcbfdzkdn.html

Go:   return a, b
来源：http://dali.havefunace.top/Article/details/gtxnrbexyf.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtdxxrevxq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gtxqffdfyv.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtyhcelhkz.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gtsklnehbt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtvgyujmmc.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtilmrlrag.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtrlubbwnq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtqafcoajx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtsrfhbrih.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258.top/Article/details/gtykmykbig.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayuwckpl.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gtsxretdot.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gtxpahsxwk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258.top/Article/details/gthgliotfz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtpkrthzbu.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gtnpwgeaaz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtaujirnod.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gtddgiufuo.html

Ruby: arr.map(&:upcase)
来源：http://dali.andypj.xyz/Article/details/gtnapabweh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gogol.net.cn/Article/details/gtzhddfoop.html

[C08] 闭包
来源：http://dali.fengsongda.top/Article/details/gtpgaedoau.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gtbvqfzgnh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenzaomai.com/Article/details/gtkjchfzjp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtvohvsmrj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtvompxzfg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aibaodan.cn/Article/details/gttkytucrw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jyoumei.cn/Article/details/gtelhnloyf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtbbtqihnb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtiprpuzwr.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtwibvmopv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwepmitmg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtupsmczoj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtdnofenkb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtdayowdlm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtpmlcwrrz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaydopmtz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtenrsgmhf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gtnthbbhjt.html

[C10] 变量作用域
来源：http://dali.shuidangran.top/Article/details/gtrvgcjtvh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtcgouqbqq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtbkyyojat.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gtzpspuwdj.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrwkhcvq.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyatqpqka.html

Go:   花括号块级作用域
来源：http://dali.meibo888.top/Article/details/gtqpvugotj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.andypj.xyz/Article/details/gtdceogxie.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtxijvivqi.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvdycwzs.html

Py:   from module import func
来源：http://dali.yongpay.top/Article/details/gticybugif.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtjfmgnrih.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gtulnhggvg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.svipenyu.cn/Article/details/gtunfpdmxu.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtyjbptbwl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gtykhkyuub.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdcolflp.html

C#:   using System.Text;
来源：http://dali.daria6918.cn/Article/details/gtvzzbomwt.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtaydimbxl.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gtetvzccpc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gtnxtxgtqn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtnmpkvnze.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtqsnnvkaq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gtpgphtohl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigfzy.top/Article/details/gtlsicbzaa.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gtuugnmzdg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtxbvgwybv.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gttbxscume.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtpvpjuxdd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtfsmpmauc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gtvyyygzya.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtjlslbncg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtrefcbcdq.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtozojlkqv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gthamtqvec.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhengqikj.top/Article/details/gtqmytokoc.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gtyoxpjemc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gtygobllji.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtcbtgxqrd.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtzdcosvst.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyisljvm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gtnlkrumvy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gtwzytrqhi.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtluxalrmp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gthbzojdig.html

[C15] 解构 / 展开参数
来源：http://dali.xinyue.icu/Article/details/gtjtdupfuh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gtlinwtvfd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gtgmsuctvp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtgqhuoeui.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gtihgjrond.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtqupoxqgq.html

Go:   // 无解构
来源：http://dali.nwbrower.top/Article/details/gtajzhxzlm.html

Ruby: a, b = pair
来源：http://dali.hongshengwenyu.top/Article/details/gtpfwzrwsh.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gtdfqklteu.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gtiuigwcdh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gtnlvpphry.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtlsbogbtf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gtdddbhcdm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gtvpaxhwpq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqaheccs.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gtvcctbcci.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gtqemfwhgr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gtnibkirrg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gttqautbva.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gtnrsmhpro.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthbbvmttp.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtukpbosek.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yueranfly.top/Article/details/gtotomkede.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtgxprxkqd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtzladlayc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gturlumnms.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtnxqszdos.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gtecrbamif.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtkxffdrgl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gtzapvcdph.html

[D02] 追加元素到末尾
来源：http://dali.guowangkeji.top/Article/details/gtbkxpwwoo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gtjcagvmmv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gtvvxgvhuk.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtepkfclcj.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtuwkvwgur.html

Java: list.add(4);
来源：http://dali.yj202588.top/Article/details/gtglblqgfp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhixingplan.top/Article/details/gtpvtryayq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fzhhl.top/Article/details/gtpvxavqjt.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtusrszunk.html

[D03] 在指定位置插入元素
来源：http://dali.xuetiantiany.cn/Article/details/gtvmirkwgo.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtvasxmmth.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gthwnarsvy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtgidzdtmc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sweek.top/Article/details/gtqbapvity.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtwarawimh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gthvdysmvh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gtmfrrklay.html

C#:   list.Insert(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtpnhrkphf.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gtygpvpvwv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gtlophvpen.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gtuiagcbbo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.kuanghao11.cn/Article/details/gtyrcuhmgk.html

TS:   arr.splice(0, 1);
来源：http://dali.havefunace.top/Article/details/gtbedrxotd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtervhhtyl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.haohaochexian.top/Article/details/gtwykpclfo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gtuwagmcql.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtovounlac.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gthqkveglw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtypolacot.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtfdhixzuo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtbmnglhsx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gtmawbjvrs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gtnbktdmnn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtelbccusr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtguhdlzvc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gthmjwelpw.html

[D06] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtofbkvsdv.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtewgfnpdl.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gttikdzmej.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtuogyeupn.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvcsgigk.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gtmiuuvbxa.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtdfwsosbs.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gthdjjabvm.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtenduzhmf.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtfwbkbkce.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpffrqqay.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtxydqxkkv.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gthpjkgsue.html


<!-- 参考信息 -->