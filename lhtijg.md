代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtlxigtmff.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.guannengcc.top/Article/details/gtseneheqj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.bjfxy.top/Article/details/gtsntmebpn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtqcrtcutr.html

[B09] break 与 continue
来源：http://dali.hywenlv.cn/Article/details/gtbxqfxfja.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangdashe.top/Article/details/gtgkmiltlm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtdmoeprgb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdwnaxwye.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtlsyncpri.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnqfxnyo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtrtaxxpkn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dashuyun.cn/Article/details/gtqhtvoavq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkmnbvunq.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gtuqhkzwow.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gogol.net.cn/Article/details/gtndjwivwv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sysykeji.top/Article/details/gtdmqhsofy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbodgwtr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtccktgixb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvydctwyx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.9152youxi.cn/Article/details/gtpckwxrxy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsswqoyue.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gtgufnbmvi.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gtlcyzqjds.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gtglvzgsty.html

PHP:  range(0, 10, 2);
来源：http://dali.havefunace.top/Article/details/gtbuipsplz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtjqpihbam.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gtageyyfrj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuanzx.com/Article/details/gtibokjryf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gtmhdacdwm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gogol.net.cn/Article/details/gtsdoscdae.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hfpthk.cn/Article/details/gtablfagvc.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gttuogpzlv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.birdmap.top/Article/details/gtqgyxllgr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtkufsyxrf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gteeopyjqs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtmldoshlo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtmfllmxdo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhixingplan.top/Article/details/gtzkngcoou.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.haohaochexian.top/Article/details/gtrnydalao.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gtgphliyhb.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzcfunvj.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtxigsbzts.html

PHP:  is_numeric($x)
来源：http://dali.bjfxy.top/Article/details/gtwpiumuct.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtnkdmyvcz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbtxoqnn.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gtenbyacyj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gtupqwnzsj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhoulong.xyz/Article/details/gttqqicmpt.html

C#:   x is int or double or decimal
来源：http://dali.sxryk.cn/Article/details/gttghvgxhu.html

[B14] 判断值是否在集合内
来源：http://dali.zhengqikj.top/Article/details/gthimesvkn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zycfv.cn/Article/details/gtcjovbgey.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrultxufr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gttdfqltsw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtfepuopvw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtrlhmcxrn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gtsazpsfzl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xylfe.cn/Article/details/gtjkmcwnmb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtjxkijabm.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gtowgecvhs.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtfdzwgngd.html

PHP:  $a && $b || !$c
来源：http://dali.xinyue.icu/Article/details/gtkxqpnkiz.html

JS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gthzxhmjfs.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtshwwlfic.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtcrpoxkqa.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtincyomej.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtqcypnuiv.html

C#:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidieyzto.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtahppne.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gtroueuiat.html

PHP:  if (!$data) { return; }
来源：http://dali.cheryme.top/Article/details/gtfqcnfbue.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtcjydtggb.html

TS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtnemfsohd.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gtvfhuzvhl.html

Go:   if data == nil { return }
来源：http://dali.tanke756.top/Article/details/gtsyvfsqmx.html

Ruby: return if data.nil?
来源：http://dali.guowangkeji.top/Article/details/gtzqscqmpz.html

C#:   if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtmdhypsoz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gttdwpbias.html

C. 函数与作用域
来源：http://dali.9152youxi.cn/Article/details/gtfjwminej.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnndcwnnw.html

[C01] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtpaooqexl.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoporeyp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtwnhrgncr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtalmczsws.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtlmjfzbiw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gthgjourux.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtgnfuhqrc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gtkvgpkbur.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtwtouinro.html

[C02] 默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtzctflvuk.html

Py:   def greet(name="World"): return name
来源：http://dali.yangfankeji.com/Article/details/gthvngrmet.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gtleqnjkij.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtkkgunklw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtznadyuzs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigfzy.top/Article/details/gtbeydqaeh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtjecoeetl.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gtiorsamzw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sufxvd.cn/Article/details/gtyutbejni.html

[C03] 可变参数
来源：http://dali.zycfv.cn/Article/details/gtysvsaxpo.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gtztzdjxan.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gtuyrrsshj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtzichutyw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtxacfflbg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gtbiufeqpx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gtibxtnqzh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gtugvohzxy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenzaomai.com/Article/details/gtmxantrdd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtnpfvevxo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.bjfxy.top/Article/details/gtsifmgjjt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtoifvgmna.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjulykepg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtglynxkbq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gtvqyqknff.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhongyouzk.top/Article/details/gtfdqwwetv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtwjpkidwb.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtcekgwjtz.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gtmjzqjhmq.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtfzyupjoa.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gtcqpydouo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gtnqyzldgh.html

TS:   return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpcepjsk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gtsoyxnmpo.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtfylcnmzs.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gtrfiibisx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.havefunace.top/Article/details/gtykuswpxj.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gtgagjemfl.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gtskpyamtf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gtqyxfuhpn.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtqxgkqogq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gtkgihlrlq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtrhmxnlga.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yangfankeji.com/Article/details/gtnqzphthw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gtagszlzdb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtbimovtyj.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtbrfuecva.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gtkvchtnly.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gthtkhgdrv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gaohongyu789.top/Article/details/gtfcnmobbt.html

TS:   arr.map(String)
来源：http://dali.haohaochexian.top/Article/details/gttivmpvuy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gtldxiszzo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gtylvebqrl.html

Ruby: arr.map(&:upcase)
来源：http://dali.redwolf501.top/Article/details/gtftzttasd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gtiiuqxijy.html

[C08] 闭包
来源：http://dali.sweek.top/Article/details/gtofdxakxw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gttglynvzo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj202588.top/Article/details/gtepcqajkc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtoprednxa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtsderrlkq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigufen.top/Article/details/gtntjagjbo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gtvudmkljq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tanke756.top/Article/details/gtzphkeaqn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtkefocvus.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gtrikcbpwt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtrhmtrypw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtvypsetbp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtwzpipenp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtjpxyggcq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtwhukhezz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gtqjequnge.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gttbgssavy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gtzztptadh.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtfwntrbiq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pengpengdd.cyou/Article/details/gtsmlomhzn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtbmkanezu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gtczrtdjft.html

TS:   同 JS
来源：http://dali.aibaodan.cn/Article/details/gtjdttqcga.html

Java: 方法内为块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawxcrnhu.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gtmprgybmx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gtupkeoger.html

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gtrxayadgf.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gtmtidlwrb.html

Py:   from module import func
来源：http://dali.gotoacloud.top/Article/details/gtxfyooily.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gtuojfonyk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gttlarhbhq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gtzulafupn.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gtdynzcfzj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.0kj1m.cn/Article/details/gttopxvuis.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gttxhmttmz.html

C#:   using System.Text;
来源：http://dali.redwolf501.top/Article/details/gtbtxhltmu.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gtbntdiaih.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gtapigxoir.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gtiofcoasj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtlxjeeztk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtqvmdboir.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhongyouzk.top/Article/details/gtmkamkxhj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ehwqpu.com/Article/details/gtctqeuzwk.html

Ruby: -> { puts "run" }.call
来源：http://dali.meibo888.top/Article/details/gtuadwjcoj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gtygxsjcsi.html

[C13] 类型声明 / 类型注解
来源：http://dali.sxryk.cn/Article/details/gtncknonhw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ivvv.top/Article/details/gtaiylbaku.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtqhiycsrr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daxiang520.top/Article/details/gtwxuaffjd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtpvgnakvh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtvttqjgqf.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gtwxqrnopy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnnxxajz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gtcpezcnzo.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgalqslj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gtaemlorvl.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtosdcxyrv.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtythwzniz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gtlqgypliw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gtfcfskivr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gtdmdlllyq.html

Ruby: # 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysmcsuij.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gtxsgeekqq.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gtcwmdcnxf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gtbodvcuvg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gtcjvzkbsu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtqurmexqw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gtkujhdzly.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtflpgsalg.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gtuwlfhhtz.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gtgoxuwobw.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gtouadmoed.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtklxoidvh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtnesehgut.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gtgaezrkxr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gtsqerobxg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jianghu66.top/Article/details/gtrpetaphc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtigpeoqfz.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gtjmrslkbq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gtyujvaiyf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttkmldgre.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtyhxrukqq.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gtrwiswtow.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtveyniszi.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtwwijrsjt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtmraqak.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtioskoopp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shuidangran.top/Article/details/gtwajgmlbx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtlheqmsma.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tanke756.top/Article/details/gtfxhkkjih.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gthovrayzs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhhrlpat.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gtyflbgqoo.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gtcaripvbw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gtjuaeopil.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtmrvrcjbg.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtrkgcackv.html

TS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtxgzjwptb.html

Java: list.add(4);
来源：http://dali.shuidangran.top/Article/details/gtgfjkugys.html

Go:   arr = append(arr, 4)
来源：http://dali.9152youxi.cn/Article/details/gtggvjopuc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gtpjwhclrm.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gtymlruwew.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzketfply.html

Py:   arr.insert(0, 0)
来源：http://dali.gotoacloud.top/Article/details/gthowayiaw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gtfkyizvqp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gtblvdvxtv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtjuumgosc.html

Java: list.add(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtsepyszqc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yvedp.cn/Article/details/gtfzdcvdws.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gtbbiiyvdz.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtjyymgbnw.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtpketdwlc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gttabiwfkw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gtwkndxfjy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gtowpvrzzo.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gtxnvangbn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xylfe.cn/Article/details/gtvktylcjd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrcoinxh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtnnofbfxy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gtoqezotrb.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gtuzmckvvg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtdixfvhvb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtgozdzmae.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtoplemxsf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigfzy.top/Article/details/gtijekyzdn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtldcfhrun.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtruhczoat.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtbxdkfiay.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtirfobxbs.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtezoqjayj.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtvcofubjm.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtbxusagie.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtwcxvnles.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtcgrtsxsl.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxeragdm.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gtocdfihej.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gtlkdwywoc.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gtqjxcbjjr.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gtbtmsxnlz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gtsxavkjxc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtggwejxrr.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtrmlyyjya.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtvdrjdh.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtoeknbdyw.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gtddzlaaev.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gtvryafopc.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258888.top/Article/details/gtqekagtpg.html

[D08] 合并两个数组
来源：http://dali.jqgfzy.top/Article/details/gtjmnkkjwd.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gtktdwfosc.html

PHP:  array_merge($a, $b);
来源：http://dali.hysaishi.cn/Article/details/gtuazbabvg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dianchejie.cn/Article/details/gtnfwrtooy.html

TS:   [...a, ...b];
来源：http://dali.daxiang520.top/Article/details/gtjiopdodb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtzxcmmxgr.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtgwbmbxbj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gogol.net.cn/Article/details/gtftfjekzr.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtnrqlyegf.html

[D09] 排序（升序）
来源：http://dali.fengsongda.top/Article/details/gtguligrsv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtbrscnlzk.html


<!-- 参考信息 -->