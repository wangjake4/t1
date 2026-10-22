代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2qxwsnpxm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dashuyun.cn/Article/details/gt2gsgjpoxp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xziqi.cn/Article/details/gt2fttsjbmh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2wfsaatix.html

[B09] break 与 continue
来源：http://dali.jinqigufen.top/Article/details/gt2aexbckba.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.haohaochexian.top/Article/details/gt2pxlqudsf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2bxuawuok.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2jyegynqu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2hpxeafcd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gt2gwfliynv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gt2ywopazmq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxinkj.top/Article/details/gt2hwpihazr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2rgqmuvfe.html

[B10] 遍历同时拿索引
来源：http://dali.wangdashe.top/Article/details/gt2hgwepqvt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gt2znbgkvua.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cucudq.cn/Article/details/gt2ywqtuxhc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gt2uhbghthe.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gt2gwfbfdqo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hywenlv.cn/Article/details/gt2kpudqwaj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlyhwrxu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zycfv.cn/Article/details/gt2wofcscbz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hysaishi.cn/Article/details/gt2lqpkribs.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigfzy.top/Article/details/gt2tuavpxdb.html

Py:   list(range(0, 10, 2))
来源：http://dali.guowangkeji.top/Article/details/gt2zsixzexe.html

PHP:  range(0, 10, 2);
来源：http://dali.shuidangran.top/Article/details/gt2recxxcnm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gt2fypwbleh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2acrdenpi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hammf.cn/Article/details/gt2wvzxfjhe.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpcfeeax.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gt2lcfiyddx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gt2tlidmlja.html

[B12] 跳出多层循环
来源：http://dali.jqgfzy.top/Article/details/gt2aevofikl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gt2pygktohr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gt2tcpqraui.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gt2vgjorboh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2ncjgvtej.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gt2zzsjusij.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2phiucrsi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yonumen.top/Article/details/gt2xxmxasri.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gogol.net.cn/Article/details/gt2fnccbjib.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrxleuuy.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigfzy.top/Article/details/gt2ghzhqyjr.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gt2mltfxitb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gt2lprlgqaf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gt2ploevxxk.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gt2xhawprkk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gt2ybieeqjk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.0kj1m.cn/Article/details/gt2bbribubb.html

C#:   x is int or double or decimal
来源：http://dali.svipenyu.cn/Article/details/gt2xpkjiupy.html

[B14] 判断值是否在集合内
来源：http://dali.yanxiufei.cn/Article/details/gt2hmzkxxqp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sufxvd.cn/Article/details/gt2ikmhakbg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ydzc1.top/Article/details/gt2kzkuyjdl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2hxcqzkrk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvhlukul.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2apomudnv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2sayruxmw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.smart0.xyz/Article/details/gt2jytootgv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2ohubdwnw.html

[B15] 布尔运算与取反
来源：http://dali.xuanzx.com/Article/details/gt2zfoeevfy.html

Py:   a and b or not c
来源：http://dali.yj20258.top/Article/details/gt2dklnizle.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gt2bycdfmia.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2ecgfvqru.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsukjvo.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2amlmkgjz.html

Go:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2zodnbfkr.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2slgnemqa.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2tdyhonrk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tianlin.xyz/Article/details/gt2zrtwhjvn.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gt2xjzgqiap.html

PHP:  if (!$data) { return; }
来源：http://dali.jianghu66.top/Article/details/gt2uknyjqqz.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gt2otrertkd.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2dbnrlfid.html

Java: if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gt2nvlwflch.html

Go:   if data == nil { return }
来源：http://dali.jlsjyb.cn/Article/details/gt2ihaljana.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gt2uogvheom.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2qnxyhque.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2npjswwqx.html

C. 函数与作用域
来源：http://dali.daria6918.cn/Article/details/gt2hcdmmpuf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2exgmvbxj.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gt2haaazslj.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cygmvoer.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gt2ikisszva.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2vvlzlcgc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2llaoqdbt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2wkqkdhef.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.havefunace.top/Article/details/gt2fdwlaxbe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenlongwang.top/Article/details/gt2wrzjtobn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2thbtcvdz.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gt2iuazowgb.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gt2ytftlmff.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gt2anfapsqp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gt2ddvlihoh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2upfutchx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gt2svkvjcyv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzjdmuni.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuanzhike.top/Article/details/gt2spscucki.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cashguo.top/Article/details/gt2jsqrbblt.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gt2stxutpvr.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenzaomai.com/Article/details/gt2ayufxtbl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gt2bfkhkowk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gt2xwyozlob.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gt2hmafkyod.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gt2bxnclxys.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gt2ozjbweov.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gt2cbjgqmzi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gt2nlvzewaq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gt2iblkynas.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ydzc1.top/Article/details/gt2mlkjitdu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sweek.top/Article/details/gt2tttukhym.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gt2ijhhuivw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gt2vcncouaq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzxqujue.html

Go:   // 无：用配置结构体参数
来源：http://dali.sufxvd.cn/Article/details/gt2lpmfyfjt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2ipilddzg.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gt2fhuuaruc.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gt2ciysksee.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2almccozm.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gt2ogvcbtfu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2glntigxq.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oerfqtqu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guowangkeji.top/Article/details/gt2bfblgxlx.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2iinkaowv.html

Ruby: return a, b
来源：http://dali.xylfe.cn/Article/details/gt2eyohprbj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gt2vyrjbcox.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwzirxis.html

Py:   square = lambda x: x * x
来源：http://dali.nanxinkj.top/Article/details/gt2kohokzdm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gt2efgskpss.html

JS:   const square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2uofnwuhu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2swpocwjf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gt2ouqmufcd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gt2grariwpy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yonumen.top/Article/details/gt2qhakmvkv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gt2zyiafpcg.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gt2crogbnjw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gt2vpdowwea.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2cphxsreg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gt2axvadsrn.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gt2jquqkbbv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2skzirwcg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gt2gvyntfgz.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gt2xozxvaui.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ginjmlor.html

[C08] 闭包
来源：http://dali.hammf.cn/Article/details/gt2houeolbl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gt2fvhtgydd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gt2rihbzmgd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gt2yckhrnku.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gt2kavqegrd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gt2rdrnymnm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xylfe.cn/Article/details/gt2iszcfvoo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gt2vejlywkt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gt2wysvtmfg.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gt2cpvwjzbf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gt2zqiiexes.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gt2mtfhgkqv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gt2ipywofva.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gt2xtnhttrd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gt2zqkdwunx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gt2mzovvecl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gt2sujosojz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gt2fttbwivi.html

[C10] 变量作用域
来源：http://dali.birdmap.top/Article/details/gt2pdbgghnh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gt2ppopqyrv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gt2tgasisld.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2itusfjtt.html

TS:   同 JS
来源：http://dali.ydzc1.top/Article/details/gt2qocwzasl.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gt2nlbspeve.html

Go:   花括号块级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2yggydgci.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gt2nzyyxdph.html

C#:   块级作用域
来源：http://dali.xziqi.cn/Article/details/gt2apmqggtb.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gt2fwdsrcwz.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gt2xwgiawdt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tian-w.cn/Article/details/gt2llbaswfw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gt2zgvioqoo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gt2twsdxnru.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gt2vmdqmokc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ybcxt.top/Article/details/gt2fddmefiw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ehwqpu.com/Article/details/gt2obefchcz.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gt2sbpxolut.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2meqtzpqd.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gt2jlluqhdd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gt2xohhvkwv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2rtkxaepf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gt2rhuszebd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gt2rifawevm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gt2ynppipvx.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfhgwcdk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2fhlqmoij.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gt2otwfigmw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gzhubu.top/Article/details/gt2jslqyikd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2ujwbshis.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gt2yojdaace.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2htghibea.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2fvcimuwc.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gt2pvtsafgd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gt2enjerxjp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wobisuwg.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gt2cxjqrzvg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cucudq.cn/Article/details/gt2ykxgdnrc.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifvgblwp.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gt2gkysbdst.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daxiang520.top/Article/details/gt2ilxjrgxd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gt2gdmjckmt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gt2pjqvsavd.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnbfoide.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gt2cmeynfgg.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gt2qmvwdjdr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gt2xdueeojg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gt2pwryrcgb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ldurwpqa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cucudq.cn/Article/details/gt2qcbgksmt.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2snrvxyod.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2wpspebmy.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gt2rvrexilc.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gt2mrcarnuz.html

[C16] 函数 / 方法重载
来源：http://dali.xinyue.icu/Article/details/gt2utcrrzgk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangshuangyany.cn/Article/details/gt2ljrdffoo.html

PHP:  // 无重载
来源：http://dali.hongshengwenyu.top/Article/details/gt2csxjkhfg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gt2kmdkjfnr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gt2uzmrnsme.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gt2beljsqnh.html

Go:   // 无重载：用不同函数名
来源：http://dali.iojbl.cn/Article/details/gt2gmbbuqkp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.kuanghao11.cn/Article/details/gt2gmvnuhnh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guannengcc.top/Article/details/gt2vaaavvxy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2gzkwpdyh.html

D. 数组 / 列表 / 集合
来源：http://dali.zdqjudy.top/Article/details/gt2ahlvahqc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2agsmmftc.html

[D01] 创建数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gt2xqomomay.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guowangkeji.top/Article/details/gt2wosellfi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2gcfyckwh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gt2bbxdxyap.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gt2etohmwhc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gt2zoilyeaw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gt2bshudvda.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gt2hurmqpkk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.andypj.xyz/Article/details/gt2fftqjfkz.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gt2bobayabv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cqqwz.cn/Article/details/gt2jsohhpuj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gt2gdogddpb.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gt2vycwkzpt.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gt2kncavpwt.html

Java: list.add(4);
来源：http://dali.ivvv.top/Article/details/gt2wbtiibgo.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gt2xvtinokn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gt2fylbzkwc.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2huibtglh.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gt2flcvfftz.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2tanbqufg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sysykeji.top/Article/details/gt2mudwkafx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gt2zhygntep.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2rysqaklr.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2qnlrvnla.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gt2weedullo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gt2twibphqt.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2mdjarfji.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2buyubwtb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gt2lqmdqlkg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gt2zhxxrhrk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yvedp.cn/Article/details/gt2qglzjrdg.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gt2axfgicsg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gt2hmbziyss.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqmjqfff.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnojiqfg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gt2fcxmsyon.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gt2bhlrycad.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvyxrfnf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2kahwazlw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2flpnleuy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gt2zauhudyc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gizwdgco.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2vahwhbzf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdfsdzcy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2phjgawkk.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuiftybs.html

Py:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gt2odvlgwyh.html

PHP:  count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2kvzpknay.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gt2bjjevgxp.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2dgzdheee.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gt2phnuafab.html

Go:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2okweroko.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gt2obkeezeb.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gt2jwwjsdeq.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gt2gfepzxof.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjdbjxhz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tygsuqiq.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2eescvgmg.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2qzdtglik.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gt2kuogseon.html

Go:   arr[1:4]
来源：http://dali.aibaodan.cn/Article/details/gt2kswhyulj.html

Ruby: arr[1, 3]
来源：http://dali.yueranfly.top/Article/details/gt2atmyonod.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgmettq.html

[D08] 合并两个数组
来源：http://dali.meibo888.top/Article/details/gt2uunnszhr.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obetorbz.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gt2vzeppddi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gt2izvhkiqm.html

TS:   [...a, ...b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2vhcqmmmu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2pyrukocn.html

Go:   append(a, b...)
来源：http://dali.hysaishi.cn/Article/details/gt2jnghrruq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gt2kquldiqe.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2vwfzqici.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gt2nftyhlkm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2ntebnizr.html


<!-- 参考信息 -->