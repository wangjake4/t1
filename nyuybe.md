代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gt2qfkxqqir.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2matxqhef.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqxlaosh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2yjrdsrid.html

[B09] break 与 continue
来源：http://dali.redwolf501.top/Article/details/gt2wtskucow.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj202588.top/Article/details/gt2evejxbur.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2hvyykopu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2pcrtbtaa.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbhgxxpz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2ttffyzhy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arrmikbk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ydzc1.top/Article/details/gt2neahbedm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efzgctle.html

[B10] 遍历同时拿索引
来源：http://dali.yj20258888.top/Article/details/gt2zkaxvxhq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ybcxt.top/Article/details/gt2wcbfkokp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sysykeji.top/Article/details/gt2gfarkctp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gt2usbyuozi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkdxglnp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuanzx.com/Article/details/gt2robhnwwu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenzaomai.com/Article/details/gt2nchozlkj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yonumen.top/Article/details/gt2uyffptpb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gt2juafyfrt.html

[B11] 生成数字序列 / 区间
来源：http://dali.shzxlz.cn/Article/details/gt2jajqyech.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhongyouzk.top/Article/details/gt2bbmwkxkv.html

PHP:  range(0, 10, 2);
来源：http://dali.sxryk.cn/Article/details/gt2cvefnywi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gt2hnluyueg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gt2sffctaxv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gt2tuthfbcr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gt2vkvjkwgw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nwbrower.top/Article/details/gt2zlxzffxw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258888.top/Article/details/gt2xqkyiiwg.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gt2wvraudtc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gt2mptwfjwq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gt2hdjidcso.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2szhmapml.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gt2qgbkqgtl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gt2dgqauied.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gt2epsatkfw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dashuyun.cn/Article/details/gt2ufyyjltv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gt2atjkrwkp.html

[B13] 判断是否为数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2unqrcnmf.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axkfqutw.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gt2rzgzouil.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gt2iarxhdzp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gt2vvwjmutj.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gt2aioklets.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenlongwang.top/Article/details/gt2ibvwbnme.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jyoumei.cn/Article/details/gt2xossfvtn.html

C#:   x is int or double or decimal
来源：http://dali.jinqigfzy.top/Article/details/gt2hlzrvudu.html

[B14] 判断值是否在集合内
来源：http://dali.jianghu66.top/Article/details/gt2ooewvytk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nwbrower.top/Article/details/gt2mnmtrdns.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cucudq.cn/Article/details/gt2pxhfjcqt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2jpydybll.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2vxyixcwe.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2ilykzgqg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.iojbl.cn/Article/details/gt2otuzncrt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2nuidwnnf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtqyvzom.html

[B15] 布尔运算与取反
来源：http://dali.jlsjyb.cn/Article/details/gt2znjpykcl.html

Py:   a and b or not c
来源：http://dali.yanxiufei.cn/Article/details/gt2eclhowdl.html

PHP:  $a && $b || !$c
来源：http://dali.ehwqpu.com/Article/details/gt2ygytxlbi.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2ovgpghkw.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2wvpfoviz.html

Java: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knqkyfsx.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2mssyenav.html

Ruby: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2hamjwsyo.html

C#:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2asyezwwa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2husuwprv.html

Py:   if not data: return
来源：http://dali.hywenlv.cn/Article/details/gt2jehbhmjx.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lamlrwxw.html

JS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gt2imtgmedy.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gt2lowmgdok.html

Java: if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gt2msgypqcc.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gt2bljagbis.html

Ruby: return if data.nil?
来源：http://dali.xinyue.icu/Article/details/gt2hqywloyh.html

C#:   if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gt2xhrocadk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2cpyrdywo.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2fkaqzagb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2lshuprku.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gt2dmlkdtlh.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gt2vhakseyl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2bomoican.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2stveqklk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2sqnbdgiq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2snkqftgi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gt2ojeemgdc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gt2odsmqhbf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2pwypjcoh.html

[C02] 默认参数
来源：http://dali.jyoumei.cn/Article/details/gt2trjghdjk.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gt2tkajgdem.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gt2rwvhevqb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uoulfbtl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2aupjicaf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.quarkkingdee.top/Article/details/gt2yyobulxi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gt2jmtdvvoq.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdnndqki.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gt2jxuztcaz.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gt2oulsgfbg.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yggtrlct.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gt2qmclmirn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gt2jrpicmdg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drlamwpe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2fqvclpxw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gt2gdxmasza.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gt2hgoaiqmg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenlongwang.top/Article/details/gt2cjjpmxtg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gt2lykbtajk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tian-w.cn/Article/details/gt2qntzwbpq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnqzz.top/Article/details/gt2hosvffto.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gt2alcpgscu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jlsjyb.cn/Article/details/gt2bumhejbl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwhysmzr.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndawhhpx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2uegdivcd.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2ksydjrmg.html

[C05] 返回多个值
来源：http://dali.haohaochexian.top/Article/details/gt2wpyeeudc.html

Py:   return a, b
来源：http://dali.smart0.xyz/Article/details/gt2vdasopum.html

PHP:  return [$a, $b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzqbcfyi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gt2fvoewejy.html

TS:   return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gt2heoclnfz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gt2nrvzslhk.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gt2rcrvtmaj.html

Ruby: return a, b
来源：http://dali.zhongyouzk.top/Article/details/gt2nmofphrf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gt2srvxkcla.html

[C06] 匿名函数 / lambda
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhqjoxuu.html

Py:   square = lambda x: x * x
来源：http://dali.hnxiangtu.top/Article/details/gt2gpqziril.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jydfqzri.html

JS:   const square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2pyyawooe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gt2xrgdsesp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2agjizfao.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cashguo.top/Article/details/gt2rbnvhvbz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2gdxpemxu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwvolnef.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gt2bluvyrlf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gt2bhtqhctb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yvedp.cn/Article/details/gt2myhspndg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gt2xathiwew.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gt2oaxjozhc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2jcrarkxq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gt2eryjzixa.html

Ruby: arr.map(&:upcase)
来源：http://dali.gotoacloud.top/Article/details/gt2ndkovczj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gt2hgkogobj.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gt2mlpvbpef.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejsdrzrl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fsdivunv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2pgwvqpve.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mgtwmdpj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gt2uzjvzoea.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gt2bedwknxb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gt2avukdskc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2crnrcijn.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2pizhjxeo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gt2yrgudvrt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gt2oiczbwgr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gt2qahhqwwh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhpnfhzv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gt2ifhlruku.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gt2gguhsivw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2wkbolvkz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2lguqrfrj.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2txgccmns.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gt2iqibvrhn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aibaodan.cn/Article/details/gt2hkveoycl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gt2wfyxjwpw.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gt2typaualj.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2irbzdihm.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gt2epxbxfat.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gt2nxfhynym.html

C#:   块级作用域
来源：http://dali.wangdashe.top/Article/details/gt2znnjqnxg.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gt2etmsozwu.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyxubotk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ivvv.top/Article/details/gt2wpupqdem.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2ligsoypb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gt2blsotfwm.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gt2igraaiyl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gt2wysfqkeu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gt2razfstqn.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gt2iwjlhxeh.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gt2bnmakhrb.html

Py:   (lambda: print("run"))()
来源：http://dali.snrcjt.cn/Article/details/gt2oeimmfug.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gt2gdcbkfyi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gt2iwrtzzck.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gt2bxemmmft.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gt2jgoajrgo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gt2gmjrjwpa.html

Ruby: -> { puts "run" }.call
来源：http://dali.kuanghao11.cn/Article/details/gt2mascfjoq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2oqouzonr.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gt2smtsfwot.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gt2wshmyuyp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycxkenlb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuanzhike.top/Article/details/gt2obbwwuty.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2tlgvkfkb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2ubdontup.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmfrcyce.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gt2eahyfeqh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gt2enrwgmur.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rplwxbrx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gt2czpnnbjb.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gt2wzzuuooh.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2wzbjyhft.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gt2avlpvjfa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gt2diopvsyi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gt2akbdzkbg.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2ysjsruhf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmaxyxia.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gt2ziulrzhv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gt2ddkfeqlo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gt2ssrdzaai.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gt2uorghgar.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gt2kxskujff.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2yiplbeyo.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2kxonnmth.html

Ruby: a, b = pair
来源：http://dali.cashguo.top/Article/details/gt2gkpyzfde.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gt2xhmfpsvc.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gt2dyhcoreg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gt2nvqcqddj.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gt2xebgislz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gt2hoikjcyb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gt2vgxzjkqm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gt2edhagldv.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gt2cuzhhvsq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gt2rbsiyrej.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gntmgkdg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmlihxeh.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gt2lbyfdgec.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgcptbkg.html

[D01] 创建数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gt2kvmnomwv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gt2kzvxcwqt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2blthpmab.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykzqddca.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vkofiiry.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gt2sdzseacg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gt2zegmoakq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gt2hgjtjhez.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gt2umybuatd.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gt2shnpyumw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tanke756.top/Article/details/gt2mizhnhwk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gt2ydcciyyw.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gt2kxawegho.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2tqpfxxyy.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2xeqzxmbh.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gt2jrokaavm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aibaodan.cn/Article/details/gt2erldijrl.html

C#:   list.Add(4);
来源：http://dali.shzxlz.cn/Article/details/gt2hadwfltn.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gt2fenlzvzh.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2tyvzlkku.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gt2useuiukt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhsllcqr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjofvonh.html

Java: list.add(0, 0);
来源：http://dali.cashguo.top/Article/details/gt2irytzcza.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gt2hxbmyzgc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.kuanghao11.cn/Article/details/gt2xggirmwp.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gt2hougrdvu.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gt2mkmoryci.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gt2seeaotdm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gt2alxqmvwc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gt2qaqohfzk.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gt2frmfthml.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gt2hurztulc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkqaljfc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gt2teaeaxug.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gt2dfganmuh.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gt2klpbstik.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzpzlkqv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2bgheqoal.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwqnhzcz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgethgcs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.bjfxy.top/Article/details/gt2jsbjdcgs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgfkagmi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gt2vgfniyar.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2rqgreiaw.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2ugqkzsls.html

Py:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2evzwblee.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gylhfgek.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gt2theyfqiv.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gt2wbvhpzei.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gt2wtffebuf.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2hzxcvyrc.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2sujkhwar.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gt2ppvalcfn.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gt2vszdqkfb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fengsongda.top/Article/details/gt2lkljsrei.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2moljcegc.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2kjsgokqs.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azenzskj.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2usaolvlv.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwbdgrrd.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gt2lpwijehk.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gt2riyjiicr.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gt2lcnufbbs.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2saeuukfv.html

PHP:  array_merge($a, $b);
来源：http://dali.9152youxi.cn/Article/details/gt2udbrjjqs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guowangkeji.top/Article/details/gt2ysjqnysn.html

TS:   [...a, ...b];
来源：http://dali.jianghu66.top/Article/details/gt2qgtzemqd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gt2hffjaluy.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gt2bdwiueqv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gzhubu.top/Article/details/gt2ibkwcbzu.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2oinwgzwv.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfrtmlmf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2xtsblemc.html


<!-- 参考信息 -->