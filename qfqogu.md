代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gttoigpact.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ydzc1.top/Article/details/gtsgmdhpqz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtegunmdmh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtcswbtqgf.html

Java: do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtcptpxrri.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhixingplan.top/Article/details/gtrcctwvru.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.havefunace.top/Article/details/gtksxwgphq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtziauhqjl.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gtdunovngj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gtwfnvizfa.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtembozmwl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtehlrwnek.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtengedgkq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtqtmpvsar.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvoiqipd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.iojbl.cn/Article/details/gtffnsrwww.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtwvlbpbwz.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gtfuhtbkrh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenzaomai.com/Article/details/gttbtjmdos.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gtxajsdsas.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtkbajwzic.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gtvjiezipp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gtaxalejpm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jyoumei.cn/Article/details/gtooiezphy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhongyouzk.top/Article/details/gtmlmivuhs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daxiang520.top/Article/details/gtwgojmoyk.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gtkfaiopdt.html

Py:   list(range(0, 10, 2))
来源：http://dali.svipenyu.cn/Article/details/gtfetvbinv.html

PHP:  range(0, 10, 2);
来源：http://dali.tianlin.xyz/Article/details/gtslkmkxjv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtvjkoudtj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtrxcxkqui.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtfoanzlfy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhiwuduotai.top/Article/details/gtwxdbjagg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnxiangtu.top/Article/details/gtvghtvwtk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.316326.xyz/Article/details/gtwuypoxdz.html

[B12] 跳出多层循环
来源：http://dali.fengsongda.top/Article/details/gtjsjdrxoh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gtophjaogh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sweek.top/Article/details/gtdpkorfgs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gtesxtkeqp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtpjnkloal.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtrdqbrupd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtixrnbxfc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shangyingyoupin.top/Article/details/gtcnuatlud.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aizwys.cn/Article/details/gtrnuiornw.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gtlaodfddr.html

Py:   isinstance(x, (int, float))
来源：http://dali.redwolf501.top/Article/details/gthabbpixj.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtcoqfammw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtojbewujd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtvfdpdzvw.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gtysciryqn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gtwtbsbmht.html

Ruby: x.is_a?(Numeric)
来源：http://dali.andypj.xyz/Article/details/gtoijhoolk.html

C#:   x is int or double or decimal
来源：http://dali.jinqigufen.top/Article/details/gtwtqaxrfq.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gtsgmioxes.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tian-w.cn/Article/details/gtnpmwwdbw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gtcqcktugo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtkktfiizb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtqjdcxzou.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gtkdhtkwta.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cqqwz.cn/Article/details/gtwwzablgp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtobykebdd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtoydzesgs.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gtwughseky.html

Py:   a and b or not c
来源：http://dali.snrcjt.cn/Article/details/gtskjryhck.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gtpqbjglin.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtzrufoymw.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtqecvpqlo.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtpcqlsred.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtreqdlamn.html

Ruby: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtkludscqm.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtnpmzwarm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gttsaoaiih.html

Py:   if not data: return
来源：http://dali.xziqi.cn/Article/details/gtxcwlszkx.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxuanxn.top/Article/details/gttpxldzmu.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gttzejbjkg.html

TS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtnqbvccjc.html

Java: if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtquhecskb.html

Go:   if data == nil { return }
来源：http://dali.xuanzx.com/Article/details/gtkocqmmkb.html

Ruby: return if data.nil?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbrwpfpm.html

C#:   if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbcwhfec.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtuypeuztd.html

C. 函数与作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtzmqjzvte.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtptvllzdf.html

[C01] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gtryojbgry.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258888.top/Article/details/gtkdhbomeu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtauovrbrx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtieaastxq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtkvrraqvp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqxqsopd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmavzhyz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gtxdnhvzkw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtlyzolgzx.html

[C02] 默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtagznmpuc.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gtdkhpgdue.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gtgcllnyso.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtnhguvzrt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtdbifbrzh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gtalhzwpfj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xinyue.icu/Article/details/gtcbpppotc.html

Ruby: def greet(name = "World") = name
来源：http://dali.tanke756.top/Article/details/gtttjhkjfi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolpbhlzd.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtqzzxvlzk.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnqzz.top/Article/details/gtglmsxviw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gtpwkerolo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gttzjnvbgq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtgnmwsgpv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xylfe.cn/Article/details/gtvxwlyrqb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.smart0.xyz/Article/details/gtpapgpeyz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gtacxycocv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gaohongyu789.top/Article/details/gtszemluuz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gzhubu.top/Article/details/gtkxezmxkl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gthjaipxbj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.svipenyu.cn/Article/details/gtqevsmyss.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtamicopem.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gteyuqftnu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gtjjvmcllp.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuxming.cn/Article/details/gtftmhsyok.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtastynzgg.html

C#:   f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gttkfltyjp.html

[C05] 返回多个值
来源：http://dali.hammf.cn/Article/details/gtuwudptyy.html

Py:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtsdgordoo.html

PHP:  return [$a, $b];
来源：http://dali.bjfxy.top/Article/details/gthzthylil.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gtdfncdwqs.html

TS:   return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtuqxaqcst.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gtoknzkiht.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gtsrqyninr.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gtpcmwascs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gtuayxuqfg.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtmqzdnnuz.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gtoqsmfayi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gtairqhueo.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtjukgujrk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gtkrficgpj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtdfttqdlx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzjtzcul.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gtfytfalis.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtahisodyj.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gttuwqcsqg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jyoumei.cn/Article/details/gtoqysinfe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gogol.net.cn/Article/details/gtbzgymmbd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gtsfabdtbu.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gtgrvcawgk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gtgvgntfwg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gtpagopssy.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gtyqjmrtub.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guowangkeji.top/Article/details/gtqltaehrf.html

[C08] 闭包
来源：http://dali.yongpay.top/Article/details/gtnaeaznlu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gtizhekejq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenjidiqi.icu/Article/details/gtabvldzba.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtglydchwr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtoevnuyzf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gotoacloud.top/Article/details/gtguhqouex.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gteedsdxop.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gtnrthclrg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtxjumpyir.html

[C09] 递归
来源：http://dali.dianchejie.cn/Article/details/gtstdqbdhs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtphksrkac.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtvctjssoq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtvogocxnv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtkrcaziwc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtifetodqk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gtpzndhrln.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtvrzjwazy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gtatnvodzd.html

[C10] 变量作用域
来源：http://dali.hammf.cn/Article/details/gtqsjozxgs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gtfxnjzvjh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtkskvjqgp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gtidpsniya.html

TS:   同 JS
来源：http://dali.svipenyu.cn/Article/details/gtvrrcetik.html

Java: 方法内为块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtmhpknfqa.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtldgwvjwd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gtjtzodrpt.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gtsfcsycyx.html

[C11] 模块导入与导出
来源：http://dali.redwolf501.top/Article/details/gtyhtebmei.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtbbhuhbyq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gtpinjyotr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtkcddgokc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yangfankeji.com/Article/details/gtumddeezk.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gthqbdrobc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gaohongyu789.top/Article/details/gtbufckxdk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangshuangyany.cn/Article/details/gtijojwrbu.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gthodxljmm.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gtymfacvol.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtiuyxvzzg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gtdpojxzrg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtzinmwdcd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtqdfxbcbg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnegrqcxq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gtrkdzqjch.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gtozkcciix.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlozxlyg.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gtwpyfuhno.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtvtpgudik.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtsehnoseg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gtijewhufa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtdaprkgoj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtwdpuhttq.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gtlmcqseld.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gtztydxdmq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gtflxwptjz.html

[C14] 泛型函数
来源：http://dali.yuxming.cn/Article/details/gtadymjbfw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258.top/Article/details/gtdyqfusyj.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtfdtnrgjp.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtvtqcyomw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigfzy.top/Article/details/gtkhkhlmoq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hammf.cn/Article/details/gtnyxpwlat.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtaqjwanic.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtoosktbqc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yueranfly.top/Article/details/gtnchawgvk.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gtuuotwdny.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gtbefjgznm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gtxbtcokcy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtkyviqkzq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtmwkvxgam.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gtdnynfhkg.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtcetbqjuu.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxkhisxc.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtvenseisg.html

[C16] 函数 / 方法重载
来源：http://dali.jqgfzy.top/Article/details/gtrhkjcopf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gtmqxnqama.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gtolrxcewr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gtpgrfntos.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gtgmcagiro.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqhfyrdqs.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gtuiqkxtun.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtbteeabys.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gtuaqaaquz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthahspceo.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyseynxoj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnmrsgnjm.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtyhhqnodk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfssthzte.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gtwvhbsoxp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtujkldafw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gtwdetnbqo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.quarkkingdee.top/Article/details/gtwxdtvfqg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gtlmolqwpf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtytqvqgis.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gtsiuftmty.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gtpbezppxi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gtxsakgxay.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtcndmxfxm.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtsbbcdqmh.html

TS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtxufwdmib.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gtnbfpypcc.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtpqccfaut.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtisbamlat.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gtqdvtcmrj.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gtzuqcgwmf.html

Py:   arr.insert(0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtddfluypv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gtijkeqykl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gtpqiywrcq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtidjnyvlu.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gttlxrrdyl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.quarkkingdee.top/Article/details/gttulhdphz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gtcsvgxnuy.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtxvvdlqnm.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gtsyfiagnv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gtstwkfcbu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cheryme.top/Article/details/gtjfryegvx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtgvwsxssr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlnmjqht.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuikxcai.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gtqgeqwfkh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuvnarqd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gtvxvmdqut.html

[D05] 访问与修改元素
来源：http://dali.cdnleiting.top/Article/details/gtldyefpyh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtalragsry.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtqucgtxmk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtathxjozt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daria6918.cn/Article/details/gtrsnccwpt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gtzxmsfrjp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtapuliedr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtttkltjqa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtdzaafdbe.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtpspcyaus.html

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gthuoppmnt.html

PHP:  count($arr);
来源：http://dali.ydzc1.top/Article/details/gtjajcyomx.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtqhhclxhz.html

TS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtqgdqxogh.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gtetbvhfaa.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtljzaeqhs.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gtbzxfkabi.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gtkocxmujd.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtfryljzdv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gtunycvcli.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cashguo.top/Article/details/gtzdxanzyd.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtngewenbm.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtebvbyjra.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtofocejvh.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gtmzrapwgy.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gttvosdbcj.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtkuiueyiq.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gtrlvorflf.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gtsjevbook.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gtrsonrcda.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gtldegomcw.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gtrxttilrl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtlatvxbxg.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtdsmnfstl.html


<!-- 参考信息 -->