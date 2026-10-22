代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2xsabkiad.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shuidangran.top/Article/details/gt2nopnrzsm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gt2awzrokhp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2yyolznwb.html

[B09] break 与 continue
来源：http://dali.svipenyu.cn/Article/details/gt2biotarlu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jianghu66.top/Article/details/gt2wqkonlpx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2irxwavqw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2wampvjyk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fwipjwfe.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gt2ecdbfyyt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gt2sbymqgpu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.9152youxi.cn/Article/details/gt2wrqkzusk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2cbcwvlrl.html

[B10] 遍历同时拿索引
来源：http://dali.9152youxi.cn/Article/details/gt2ekmywzvt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xziqi.cn/Article/details/gt2senspeah.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnqzz.top/Article/details/gt2twkqcosi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gt2uhiwifza.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gt2mglszfsv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gt2eplicpfi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.c1oappe.top/Article/details/gt2wepvgwbz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jlsjyb.cn/Article/details/gt2skqhxdar.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wddvgqhr.html

[B11] 生成数字序列 / 区间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkcnpusd.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gt2qvnnkwwg.html

PHP:  range(0, 10, 2);
来源：http://dali.cdnleiting.top/Article/details/gt2ssrxzzei.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2hvlgmgbx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2clwaahnj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.andypj.xyz/Article/details/gt2yhmzkfpo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.0kj1m.cn/Article/details/gt2fupucmnx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jianghu66.top/Article/details/gt2lyeskboz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.iojbl.cn/Article/details/gt2qtnaqfkx.html

[B12] 跳出多层循环
来源：http://dali.haohaochexian.top/Article/details/gt2kgmleamt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jiagoushi.top/Article/details/gt2scfundqc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jlsjyb.cn/Article/details/gt2qkciqggv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2arrpjdtx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2vaucjpjc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gt2wabibdqn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygnhyfvv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gt2jcvzxgxa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gt2ugfgmpma.html

[B13] 判断是否为数字
来源：http://dali.iojbl.cn/Article/details/gt2oyijkenb.html

Py:   isinstance(x, (int, float))
来源：http://dali.hysaishi.cn/Article/details/gt2ysokuilm.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gt2ewvaalfq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gt2ogunagfz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2klkboipd.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gt2mkylsxjh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kdecxdqm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xinyue.icu/Article/details/gt2zekwgtlk.html

C#:   x is int or double or decimal
来源：http://dali.316326.xyz/Article/details/gt2lvmaldnv.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gt2hswfxoee.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.vqdsnc.cn/Article/details/gt2nrjtmcbi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gzhubu.top/Article/details/gt2mwwpkodq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2qxwcynxo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2idiayejk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2vtclclfa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uuwzxyyb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xylfe.cn/Article/details/gt2lvxfmpuu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2xcvhwbkb.html

[B15] 布尔运算与取反
来源：http://dali.yueranfly.top/Article/details/gt2mssclahr.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gt2aulrbnnf.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigfzy.top/Article/details/gt2sytdrwpm.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kopaphbo.html

TS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2lmtvtguq.html

Java: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2zqjxxfzq.html

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2vjjywxib.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2ivuzlxcf.html

C#:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2iopvcwoy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gt2nluanlwd.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gt2jcqzbkjr.html

PHP:  if (!$data) { return; }
来源：http://dali.shzxlz.cn/Article/details/gt2pcaggkwt.html

JS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gt2lkvkjgof.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2nuyamesm.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gt2szhizetz.html

Go:   if data == nil { return }
来源：http://dali.snrcjt.cn/Article/details/gt2jefvxpqc.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gt2szeyadoj.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2akcmzeez.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ivetjqmb.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gt2uitkjygq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvkolsez.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gt2puotffci.html

Py:   def add(a, b): return a + b
来源：http://dali.cqqwz.cn/Article/details/gt2mmevcliq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2udktfxst.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2wxtpblat.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2pterbplm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2slzyhflt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuxming.cn/Article/details/gt2vigmthof.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenlongwang.top/Article/details/gt2okbhgodp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2ugvcquet.html

[C02] 默认参数
来源：http://dali.quarkkingdee.top/Article/details/gt2lirrbxyn.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigfzy.top/Article/details/gt2dmplezws.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gt2kxqynglq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2mzhfthqu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ecwzcwkd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.birdmap.top/Article/details/gt2rkacdsvg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gt2chctkjhd.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gt2cchswreo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cashguo.top/Article/details/gt2skrtqfaz.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gt2fxypcvfq.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gt2rdkxkbxs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hysaishi.cn/Article/details/gt2gjqxkikw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gt2ffiostyg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gt2onnqfpwp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xziqi.cn/Article/details/gt2mlhkrmhs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.snrcjt.cn/Article/details/gt2hqgeabug.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gotoacloud.top/Article/details/gt2ihlldrnc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gt2ihcegkgz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.9152youxi.cn/Article/details/gt2nwdgpxee.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gt2yobrayty.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gt2hkzxuxbi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gt2buvqgofc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.meibo888.top/Article/details/gt2onfemhcz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ydzc1.top/Article/details/gt2larvlexh.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gt2bjgykhia.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2nbdkyynn.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2kciqlzcu.html

[C05] 返回多个值
来源：http://dali.sxryk.cn/Article/details/gt2khlgqezq.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gt2lifozome.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gt2khtmuiue.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gt2ythhmotp.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gt2ikklcnsl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gt2zmicdvtw.html

Go:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gt2qygcqpoj.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2aytezvqm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gt2hidildls.html

[C06] 匿名函数 / lambda
来源：http://dali.cdnleiting.top/Article/details/gt2htacobyo.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gt2gzwyfevt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtbkqasa.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2vgwedias.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2vrltosry.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gt2omvtkoxe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngnwcirs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gt2aymjjxcd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2bqqpxivi.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gt2fndnpovy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ppjwa.cn/Article/details/gt2bszaakje.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2qyawzysu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sojobrth.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gt2dhhnahza.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2qtznyzdo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gt2hedmhgvc.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvlulqsw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gt2oernvtup.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gt2iosjfezo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gt2ghfpjzri.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gt2tysylfbd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ztupqgiz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gt2ibqfvyhf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dianchejie.cn/Article/details/gt2tisyegon.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gt2zkcknqbu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hywenlv.cn/Article/details/gt2ztfribea.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2webkqimi.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mldywiyh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gt2qdwgtsyw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gt2jeqkcjek.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gt2mltdyacb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gt2qhoxqoac.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gt2xaurmlnr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gt2feerrhfx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gt2ewdqzaed.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gt2gkrisbob.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gt2tpwtslnw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pengpengdd.cyou/Article/details/gt2snzlsrws.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gt2noitgcxz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tanke756.top/Article/details/gt2mricrxxl.html

TS:   同 JS
来源：http://dali.hfpthk.cn/Article/details/gt2pqbixlda.html

Java: 方法内为块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2xfhykmdk.html

Go:   花括号块级作用域
来源：http://dali.guowangkeji.top/Article/details/gt2rptvgotx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gzhubu.top/Article/details/gt2xckvjkck.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2bmxrgwgp.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gt2qizdtlwy.html

Py:   from module import func
来源：http://dali.jinqigufen.top/Article/details/gt2nayxryqm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sweek.top/Article/details/gt2rnozakra.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gt2womptgnz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tian-w.cn/Article/details/gt2rlyfwryg.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gt2nyhrjuvf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangdashe.top/Article/details/gt2fmpyxtws.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gt2yqkygkrw.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gt2xedkprkx.html

[C12] 立即执行函数 IIFE
来源：http://dali.meibo888.top/Article/details/gt2nrnwdkdv.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijwvhnis.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gt2onxnflsh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gt2ojfbszrk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsyxfxbg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gt2vkbgrcdn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqfngplf.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gt2uppwnwad.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxfmgflh.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gt2oasmpyzt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gt2bcdyrtlu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2guhxjqpq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zycfv.cn/Article/details/gt2wjftjuda.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2bdgaacgx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hclctftn.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gt2frxlzjqu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gt2zwjtbmsf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gt2vgjkhccw.html

[C14] 泛型函数
来源：http://dali.vqdsnc.cn/Article/details/gt2mjwdvsky.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gt2crvjzwpb.html

PHP:  // 无泛型
来源：http://dali.sweek.top/Article/details/gt2opohanwv.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gt2ugutjqoo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gt2gukolgjc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.havefunace.top/Article/details/gt2qdldgldw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gt2wfukalnu.html

Ruby: # 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2uwzrbxah.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj202588.top/Article/details/gt2cmyctsyc.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gt2jhorjgvt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gt2pviwdjvq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gt2yemvlbxz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2tummbbbp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gt2zvqequst.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2rwqlugxp.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gt2rsopndhc.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gt2plpushwz.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gt2qbkvpncp.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gt2rbgpfoor.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhoulong.xyz/Article/details/gt2fczblsba.html

PHP:  // 无重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzoftgmn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gt2ojgziwmw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gt2dipzvpwe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ysiilnry.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gt2hhlgpuin.html

Ruby: # 无重载：靠动态参数
来源：http://dali.c1oappe.top/Article/details/gt2acitxjkr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cdnleiting.top/Article/details/gt2vwfobptp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2rmrgsxhj.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gt2mzdjkojc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ikegwlqq.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gt2aagqpfaq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gt2shfcswnn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2vwqqtmbi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gt2srqepmhf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gt2ynppnwjo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gt2vczecffm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.c1oappe.top/Article/details/gt2ccdgdngg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoenuhc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhengqikj.top/Article/details/gt2uvajycvl.html

[D02] 追加元素到末尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqctdvkf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gt2lqkzapdb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2fdqlomzb.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gt2jhsrlcda.html

TS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gt2ibujjkan.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gt2zbmuzmuo.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gt2mvcmhkah.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jyoumei.cn/Article/details/gt2wijmakcn.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2zwibyhdj.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cafuwytl.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zngjdmke.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gt2kbrevnzw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sxryk.cn/Article/details/gt2pqrfngft.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2tvhznkwx.html

Java: list.add(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2uuftadsj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ppjwa.cn/Article/details/gt2qgkhrmif.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gt2ungnysrk.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2leparebm.html

[D04] 删除元素
来源：http://dali.meibo888.top/Article/details/gt2mqhjfimz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbjklbcz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nwbrower.top/Article/details/gt2tjlartzl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gt2tecmmyaj.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gt2skvnpqac.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gt2axnozwpq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gt2emaainfd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gt2fngbmedq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gt2pmvoahfo.html

[D05] 访问与修改元素
来源：http://dali.daxiang520.top/Article/details/gt2lcbcjvwl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gt2apagunio.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkydwxek.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gt2lrcvvdth.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gt2djmmpvnr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenzaomai.com/Article/details/gt2jmctdpkp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gt2wpazcbli.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2vdcmtizb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gt2gqaxagrh.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2omruveai.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gt2uiztvloz.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gt2kfzyqizl.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2fdvctbia.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gt2qdopawcb.html

Java: list.size();
来源：http://dali.zycfv.cn/Article/details/gt2oxlzlord.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2cjcbhbfl.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2rntqltqj.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gt2xfceplua.html

[D07] 切片 / 取子数组
来源：http://dali.ehwqpu.com/Article/details/gt2qwcdwpbg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xinyue.icu/Article/details/gt2tgcdthke.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2gcfzuskc.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2gsamudvc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvirybx.html

Java: list.subList(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gt2bxldaltn.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gt2uxqztrmv.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gt2kgmvwenv.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gt2oebdvbpq.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2kyvrccnw.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lnxutbiu.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gt2upjzowvx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gt2fqlwfuiv.html

TS:   [...a, ...b];
来源：http://dali.jianghu66.top/Article/details/gt2syqinooz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2kaotwnfd.html

Go:   append(a, b...)
来源：http://dali.ydzc1.top/Article/details/gt2ufsldbex.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnqzz.top/Article/details/gt2cwbugymk.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2pniqqdjc.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gt2cjkqvoeh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpfxndb.html


<!-- 参考信息 -->