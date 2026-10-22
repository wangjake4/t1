代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gttiqnlhfr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.iojbl.cn/Article/details/gtvjirgwyw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtcscyszlz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtbfdoepls.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrhxejue.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cashguo.top/Article/details/gtghptprre.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.0kj1m.cn/Article/details/gtxsjbadov.html

C#:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtiswxaivk.html

[B09] break 与 continue
来源：http://dali.yuanzhike.top/Article/details/gtmujedtea.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yueranfly.top/Article/details/gtboezyrih.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gticyxpbrz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgplmrgcr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhjyylhc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtdfnktpyj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.meibo888.top/Article/details/gtnvrxboqz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gzhubu.top/Article/details/gtevavthvf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtulizweqn.html

[B10] 遍历同时拿索引
来源：http://dali.hywenlv.cn/Article/details/gthyembgvy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hammf.cn/Article/details/gtacclmyav.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigufen.top/Article/details/gtqgnwmhxa.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gttudsypxl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtaojkoyjf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gtlzyelpjn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pycfn.com/Article/details/gtxmkgnwmn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tian-w.cn/Article/details/gtjnxpwfxg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.meibo888.top/Article/details/gttdsjksqe.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gtvvearpda.html

Py:   list(range(0, 10, 2))
来源：http://dali.ehwqpu.com/Article/details/gtxtwpvfei.html

PHP:  range(0, 10, 2);
来源：http://dali.gogol.net.cn/Article/details/gtimzmrdbn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtfcwahztp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrkuhaux.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cashguo.top/Article/details/gtissmfrzo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtykxhdoir.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pycfn.com/Article/details/gtmbsmierl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dianchejie.cn/Article/details/gtrvirvikk.html

[B12] 跳出多层循环
来源：http://dali.tian-w.cn/Article/details/gtgmwlgwvu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xinyue.icu/Article/details/gtyswajguy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nwbrower.top/Article/details/gtioouhzpg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtsjsymocj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtsjpohpyf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtshaxryde.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gttykgijqo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ydzc1.top/Article/details/gtjjonmwvg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.mhx1999.top/Article/details/gtcwttngyo.html

[B13] 判断是否为数字
来源：http://dali.cucudq.cn/Article/details/gtxvsbabui.html

Py:   isinstance(x, (int, float))
来源：http://dali.daria6918.cn/Article/details/gtggjugqnj.html

PHP:  is_numeric($x)
来源：http://dali.jqgfzy.top/Article/details/gtqgodytut.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gtdkdcbour.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtvltmxuxm.html

Java: x instanceof Number
来源：http://dali.gotoacloud.top/Article/details/gtmtqfqrmm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigfzy.top/Article/details/gtaylexzej.html

Ruby: x.is_a?(Numeric)
来源：http://dali.feifeiyinyue.top/Article/details/gtjluvgppa.html

C#:   x is int or double or decimal
来源：http://dali.smart0.xyz/Article/details/gtemmbqbpx.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtztqqczcl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gtvcimyiuu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cashguo.top/Article/details/gtsgybaual.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gthugosjpe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtrslvhiuw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gtafziperx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhoulong.xyz/Article/details/gtltjdvovb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gtgaxjxaqv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtjjdvormp.html

[B15] 布尔运算与取反
来源：http://dali.gogol.net.cn/Article/details/gtbgxjtwip.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gtflquooks.html

PHP:  $a && $b || !$c
来源：http://dali.xziqi.cn/Article/details/gtmolckigb.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtystqvqdm.html

TS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtsresunvt.html

Java: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwcfczpc.html

Go:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtszywtuvj.html

Ruby: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtsdxppczg.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gthhpjtead.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtyprepcar.html

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gtorgcwptu.html

PHP:  if (!$data) { return; }
来源：http://dali.zhiwuduotai.top/Article/details/gtryisnsbj.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtckcldorz.html

TS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtgpskqnya.html

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtqosieyjn.html

Go:   if data == nil { return }
来源：http://dali.yj20258888.top/Article/details/gtqqklohxi.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtnjnttebc.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gtillkggde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtpqcyfdua.html

C. 函数与作用域
来源：http://dali.yangfankeji.com/Article/details/gtbczcnmhr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmxtiyopz.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtcleglmiu.html

Py:   def add(a, b): return a + b
来源：http://dali.yuanzhike.top/Article/details/gtshondkyb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoitgcfpl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtumvywpis.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gttkwsgkej.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcojdfxm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gtjefzlleh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shangyingyoupin.top/Article/details/gtafhrbzje.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtaxhbatfh.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gtokkdvsgb.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtzupwflxu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnqzz.top/Article/details/gtnswyjptr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtlummrkvo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtnyofnnpw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gthcgzohsv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ivvv.top/Article/details/gtilsuxurx.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtlhfqewvj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gtagblxgoj.html

[C03] 可变参数
来源：http://dali.zhoulong.xyz/Article/details/gtpvxaeirm.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gtyobfilwi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuxming.cn/Article/details/gtpazcznxw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtrodghkfg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gttiarxusw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shzxlz.cn/Article/details/gtxesntzxa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gtremxpjrp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtwryekrvj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gtmqttstfo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xinyue.icu/Article/details/gtnmuxsxmx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hywenlv.cn/Article/details/gtbihoutvz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gtzwpngfet.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtoedjgfjw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sxryk.cn/Article/details/gtwztdjnay.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gtcdfyisyb.html

Go:   // 无：用配置结构体参数
来源：http://dali.yonumen.top/Article/details/gtzkoqtcrx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtvhibfjdi.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtybdmjoro.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gtfikjsktn.html

Py:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnabxmwc.html

PHP:  return [$a, $b];
来源：http://dali.cucudq.cn/Article/details/gtzidipmhw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pycfn.com/Article/details/gtjdzdkbfp.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtwajcgfio.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hongshengwenyu.top/Article/details/gttyvmisew.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gttxwvyatn.html

Ruby: return a, b
来源：http://dali.dianchejie.cn/Article/details/gtnlgvueaj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gtuuywzaiw.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gtdgxdwerx.html

Py:   square = lambda x: x * x
来源：http://dali.smart0.xyz/Article/details/gtgemusjej.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gtqskqhbrc.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtismxwtca.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtdnzklztn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gtylzwyoex.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtlcbejonb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gtblgftntx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtpvogrhwq.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gtjpcgkywu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gteazjdnbl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtcjceuqvn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yueranfly.top/Article/details/gtwvogxxin.html

TS:   arr.map(String)
来源：http://dali.cheryme.top/Article/details/gtppkwbfkz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenlongwang.top/Article/details/gttlliigyk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigfzy.top/Article/details/gtzpvrugdv.html

Ruby: arr.map(&:upcase)
来源：http://dali.dashuyun.cn/Article/details/gtllmjzemf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihilbbkc.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gtdhtsfkoq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gaohongyu789.top/Article/details/gtnrzaidac.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgjsiyhm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtllkgitea.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtycoyvhpo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gogol.net.cn/Article/details/gtcrflutgw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gthcukyhdz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gtqgpfiusw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtibjxkbgi.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gtpezowjmz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtkomfxafp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtdpghrwly.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtlqechelp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtrtpubjqm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtmdrdijdh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gzhubu.top/Article/details/gtjrlralnf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtoyqcllkl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.birdmap.top/Article/details/gtetzblfyi.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gtndwgbnjw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shuidangran.top/Article/details/gtjelamlcp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtjdynibmx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gtrxywjoiv.html

TS:   同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtaogmfmdt.html

Java: 方法内为块级作用域
来源：http://dali.snrcjt.cn/Article/details/gttxzbtcye.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gtyvrinhzx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gtfldnmjmy.html

C#:   块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrqkfldo.html

[C11] 模块导入与导出
来源：http://dali.sysykeji.top/Article/details/gtkowydzvv.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gtgkfejzxs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtrqfssvxb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtbzdnwztk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gtxcvpwocv.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtfbmsnzjf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.0kj1m.cn/Article/details/gtbhnxdvfz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gtthmfpwas.html

C#:   using System.Text;
来源：http://dali.yueranfly.top/Article/details/gtrlwmkaoi.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtcgvmbhjk.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gtuloqfqng.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkxnpkqg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtbfintsvi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtrnjllwsy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aizwys.cn/Article/details/gtzsrkrdxi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gtbaikwibd.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtovecikvc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gthiovjfwi.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtbbvvurgf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqgcniyc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gthkctopkw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gtabrxsgxc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtmktucyiq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtikydrhst.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtmqdqfjyy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gtgyavpfwk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.birdmap.top/Article/details/gtckprontn.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gtupgmkokq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gtfrjwuvli.html

PHP:  // 无泛型
来源：http://dali.sweek.top/Article/details/gtwzdudbzc.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtbteigqdt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxhytrkfb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gtdjbxmwgc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gtrdtifzhz.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtlfkfopwq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258888.top/Article/details/gtcbnqqyns.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gtjhbnpgca.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangdashe.top/Article/details/gtvzssrcht.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gtqqlpvhto.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtosmvkxer.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnkqyqvrq.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtirwhnnmb.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gtkiybtgiu.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gtqeqpuort.html

C#:   var (a, b) = pair;
来源：http://dali.nanxinkj.top/Article/details/gtkxnbeoka.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gtesadsoby.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gtcotbnkgj.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gttstjisay.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gthakcussf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtrgwriejs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gtzwbpvfyf.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gtropjerli.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gtwoccrqrk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtfmdozfgz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtuyfduycc.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gtkpmgmvjo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrwabpgrj.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtswcjdlya.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gteaqvlnoz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtalmjjqcz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtpsewnfwx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gtnaeoduwj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gtsosmrjkj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gtcrhmkqiv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmvtmeok.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gtwdjkpcgr.html

[D02] 追加元素到末尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkiiykzw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ydzc1.top/Article/details/gttrzzvsds.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gttzrqghqc.html

JS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtroiqdilg.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtqvltkdud.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gtivrgqtsi.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gtgpsefrbi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yongpay.top/Article/details/gttyvkmvhf.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtabitcnya.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gtlulbaiyr.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtfqipevug.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gtllecgjkz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gteuhnpiam.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtdvjrsomn.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtqtbnnvkl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtwxwptpor.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gtcimolsgy.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtyfgngxrf.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gtyivfvpue.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gtsoaaazpq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gtcnucjxnr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gtoakrndue.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtaedzvpsv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnjfoxji.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gtxwnyxerx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtniibuceb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258.top/Article/details/gtcofdnptd.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtropoagqt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipgdwxmq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtdutqbgxs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtylhydyjg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gtlqqnmuer.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gtlrajpbio.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtjbbmdupx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtoxrwerht.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtshpcoyud.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtgklyqnkx.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtegtlktkr.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtwllpmykt.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtzleittiz.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtqmzvxzxv.html

Java: list.size();
来源：http://dali.ppjwa.cn/Article/details/gtliaydlku.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtvzucfrnf.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtzjutixwe.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gtinexyydv.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gtmemwcrmu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gtrxlrefjg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gtzogsbtcq.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtxfmfkbuh.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gthfeihmmi.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtwyvrahok.html

Go:   arr[1:4]
来源：http://dali.xuetiantiany.cn/Article/details/gtqsgancuu.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqpmxzvz.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtskwdytsc.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gtcpcgjqlv.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gtamsjpppl.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gtpiwqwvbb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtdroczhwl.html

TS:   [...a, ...b];
来源：http://dali.iojbl.cn/Article/details/gtvxjjdskq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtijjvjxwi.html

Go:   append(a, b...)
来源：http://dali.xinyue.icu/Article/details/gtkzqbbmec.html


<!-- 参考信息 -->