代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfpjqhxz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2fsobatsk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2cgdjfvio.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gt2amexbnwa.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjrentaz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gt2zkgnckuh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daxiang520.top/Article/details/gt2qchlijjr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlttyxun.html

[B09] break 与 continue
来源：http://dali.chenlongwang.top/Article/details/gt2olvlhijc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gt2wojgmhni.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gt2rqsbvbim.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gt2edqdyysj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gt2sljtdvuq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvlazgus.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdldpthc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gt2ffhgosqc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2whfhkvya.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gt2cwwrgutx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenzaomai.com/Article/details/gt2raxomfpg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oltydvba.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gt2qodumozz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gt2jqxpmtdz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sxryk.cn/Article/details/gt2quhrvggf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guannengcc.top/Article/details/gt2gyotzpgq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pycfn.com/Article/details/gt2iaghgdju.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpkzfskh.html

[B11] 生成数字序列 / 区间
来源：http://dali.xinyue.icu/Article/details/gt2bpddafbs.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pktvcyrb.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gt2pvzscmlx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gt2cvomiwec.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gt2iydhuxpb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2tqplgsse.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj202588.top/Article/details/gt2eglnxsfv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhongyouzk.top/Article/details/gt2mgeyqvnr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqcvfcqq.html

[B12] 跳出多层循环
来源：http://dali.ppjwa.cn/Article/details/gt2pnsldjwx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gt2xzzehams.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dashuyun.cn/Article/details/gt2gxhjkrth.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2edggymjv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gt2clizcyuf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gt2fjawapwy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2biwyrotp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ruexhylu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aizwys.cn/Article/details/gt2pxbkmscp.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gt2eqequrii.html

Py:   isinstance(x, (int, float))
来源：http://dali.316326.xyz/Article/details/gt2bcteydyv.html

PHP:  is_numeric($x)
来源：http://dali.fzhhl.top/Article/details/gt2hewrkbsy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gt2odaejndd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gt2wfwphlri.html

Java: x instanceof Number
来源：http://dali.guowangkeji.top/Article/details/gt2ffthzvpv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ydzc1.top/Article/details/gt2tnpwmora.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjehuedg.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zluevcqv.html

[B14] 判断值是否在集合内
来源：http://dali.cdnleiting.top/Article/details/gt2qbckmtnu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gt2lwohdtbk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gt2rfdeyfgt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2khaiwuxq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2eezqihcu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2ydgtrxne.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnavilxn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jyoumei.cn/Article/details/gt2xvudbktf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qabmtpgu.html

[B15] 布尔运算与取反
来源：http://dali.cdnleiting.top/Article/details/gt2qhacjava.html

Py:   a and b or not c
来源：http://dali.zhoulong.xyz/Article/details/gt2yhciutvp.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gt2bnfmlqds.html

JS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2unkurarz.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2tmxjrzkc.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2ystkzrqv.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2qefcauqy.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gt2mgxwcmkl.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfgevtxy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gt2oktklvhh.html

Py:   if not data: return
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmytultd.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qawqqhzt.html

JS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gt2sfuzlfwc.html

TS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gt2trqwepzw.html

Java: if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gt2lixfjjxv.html

Go:   if data == nil { return }
来源：http://dali.316326.xyz/Article/details/gt2ujtjnxlp.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izuoapek.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gt2apylldos.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ewkuhlck.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gt2sewfnznn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ibdwiwdo.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybkbhfqt.html

Py:   def add(a, b): return a + b
来源：http://dali.yueranfly.top/Article/details/gt2otpwqspq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2syvvstak.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzlhtnts.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2lshzptio.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2sxgabube.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gt2hxlgbxfi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gt2dqpzjevf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ksddtpsa.html

[C02] 默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2sckhkora.html

Py:   def greet(name="World"): return name
来源：http://dali.zhixingplan.top/Article/details/gt2mzdqfnfu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dianchejie.cn/Article/details/gt2zrlhhjje.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2cidqbtgd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2uhfhobbn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gt2zayecqgd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dianchejie.cn/Article/details/gt2dvuvpdyx.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gt2eqzrxtlp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gt2gcwjhcwi.html

[C03] 可变参数
来源：http://dali.316326.xyz/Article/details/gt2aeazgwwr.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxuanxn.top/Article/details/gt2jxepmyoh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gt2lbukcjcu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gt2qnketdty.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gt2wkjgcqpm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gt2voeouptm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jianghu66.top/Article/details/gt2sqnojgzy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.316326.xyz/Article/details/gt2pnyezqcm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ybcxt.top/Article/details/gt2yruwygmh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gt2uwzlemlk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuanzhike.top/Article/details/gt2kumsvunt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xylfe.cn/Article/details/gt2xhmcanoc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbvhqmwq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gt2bmzdjmno.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gt2vuvelabc.html

Go:   // 无：用配置结构体参数
来源：http://dali.yonumen.top/Article/details/gt2gkeouswf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2aetovicc.html

C#:   f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gt2acidmezg.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gt2wplcptvf.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gt2yvgaecuq.html

PHP:  return [$a, $b];
来源：http://dali.smart0.xyz/Article/details/gt2byalnmbj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gt2gkhiwgmc.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gt2oaruwlop.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gt2ecznukzf.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gt2wqoedoen.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gt2pvddjxxf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.bjfxy.top/Article/details/gt2udzgasgw.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gt2rgulozaw.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gt2fhwgvczp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gt2ibmcyphv.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2tkrllfoj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gt2bqkufezt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258888.top/Article/details/gt2dnkumsmi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuueqydk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gt2tjvobkvq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhmmphgv.html

[C07] 把函数作为参数传入
来源：http://dali.9152youxi.cn/Article/details/gt2cuhnwqcu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwhlyfnp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2amssrjwp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gt2vdmnamzv.html

TS:   arr.map(String)
来源：http://dali.hnqzz.top/Article/details/gt2llxfqffb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xlsotqby.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gt2iatdzchl.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gt2sjobmjyj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yanxiufei.cn/Article/details/gt2vksoviij.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gt2wbtkiupk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gt2buwnldee.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shzxlz.cn/Article/details/gt2cmgrgriw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qdaerxru.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2epwnpchr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.birdmap.top/Article/details/gt2ldimsrni.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gt2gmhtpiqy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jiagoushi.top/Article/details/gt2sydjbmce.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gxnrnewx.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gt2xpfihkap.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2kwfbmuov.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gt2vupgncdj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gt2hjodumqq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2xfshybat.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gt2hwcbkkcv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shuidangran.top/Article/details/gt2vpejzglt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2yztqvyie.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.havefunace.top/Article/details/gt2lmoxoenq.html

[C10] 变量作用域
来源：http://dali.guannengcc.top/Article/details/gt2ddmltvlk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gt2ptjtbdhg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gt2hporvfmp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2yzuahgbm.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gt2hfvbrgeq.html

Java: 方法内为块级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2dcgjnfij.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gt2kzjivytv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gt2poqxahiv.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2lwemmgta.html

[C11] 模块导入与导出
来源：http://dali.hywenlv.cn/Article/details/gt2nilmgszl.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gt2tdprsyhy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gt2adbyxlyg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gt2aoesgzxg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yonumen.top/Article/details/gt2otudtxqs.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gt2arvyvbnn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgfzy.top/Article/details/gt2lkjtywtj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gt2clqyrgpy.html

C#:   using System.Text;
来源：http://dali.iojbl.cn/Article/details/gt2xdrmvvkx.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xpguagub.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gt2kctgavef.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenzaomai.com/Article/details/gt2uvcefhil.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gt2zygvylnq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwnyydep.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gt2fvqtwywr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sxryk.cn/Article/details/gt2eifkwtdm.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gt2qjrpwblm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gt2whcguexl.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzjmkjmo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gt2lorrtvys.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2zhryzfci.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ehwqpu.com/Article/details/gt2fgesbxkm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2qzrldkss.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2zgynflss.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gt2kzkzcyiw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkdvwwkm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gt2ncnitktp.html

[C14] 泛型函数
来源：http://dali.yuxming.cn/Article/details/gt2yhqnisko.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gt2uctktedt.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gt2tzzmmdhf.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gt2wjqbriqz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gt2zuxjesdh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jckmspba.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gt2odypjbaa.html

Ruby: # 无泛型
来源：http://dali.hammf.cn/Article/details/gt2cbmjoqpd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gt2wflzjgzj.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gt2hrjcpolq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gt2edaebtho.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qoxrnzqq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bticcpdz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sweek.top/Article/details/gt2bpgbphlc.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gt2cucutvdh.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2xkyuxypa.html

Ruby: a, b = pair
来源：http://dali.zhixingplan.top/Article/details/gt2oelqamtt.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2vycyctjk.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gt2dsqblddw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gt2amyjdrlm.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gt2iawkplha.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gt2sjioqlmh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gt2dzjivjqr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gt2mpbjnuno.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gt2nqdpxpgv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gt2qcdaviuu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gt2rcgmhoop.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ugygploj.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gt2uptiawqu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2lylgpphj.html

[D01] 创建数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gt2slmxrakd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gt2jjzvbtgh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gotoacloud.top/Article/details/gt2ctpptwss.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gt2lcrqfgdl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cqqwz.cn/Article/details/gt2omgwnacf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gt2zkgbbkuo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gt2yowdatzy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuxming.cn/Article/details/gt2duhdumig.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gt2idjpfdhw.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gt2dhmouyil.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xinyue.icu/Article/details/gt2pggkudko.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2gjzfblwq.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2mjoutwxb.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2vkzoayfg.html

Java: list.add(4);
来源：http://dali.yueranfly.top/Article/details/gt2fbwnpjuh.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gt2blmxzppl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpnypyuc.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gt2ytjsmgws.html

[D03] 在指定位置插入元素
来源：http://dali.yj202588.top/Article/details/gt2weoxoesf.html

Py:   arr.insert(0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2iwigqliu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gt2jeptwtpr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gt2sdvpbkti.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2cwsrftlq.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2fvhwqast.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxinkj.top/Article/details/gt2iitivute.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gt2ofawilau.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gt2ntqppixb.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gt2cgkacgrp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gt2gbrmwggi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.iojbl.cn/Article/details/gt2jdtqlcdk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dashuyun.cn/Article/details/gt2shsqehuq.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gt2ovhxcbna.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ouzjiwvs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhengqikj.top/Article/details/gt2surxeasl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2etitbfuz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gt2jkdzcgwh.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gt2vzvgoolb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2fwjrlcxn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2ootphjdn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrzfvvee.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gt2oluesedy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gt2hwljsmtj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gt2dkmplacm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2egbbclvu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gt2igjzgcuc.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gt2mpevsqjz.html

Py:   len(arr)
来源：http://dali.yonumen.top/Article/details/gt2kayzkzuu.html

PHP:  count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frkcthuv.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2qdvfrqsf.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gt2xqkrcnbq.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gt2linscqek.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2zpuwykvw.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gt2jhhasvoi.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gt2dwcwxoec.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gt2ynudnccd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cheryme.top/Article/details/gt2rpzoecfn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gt2prqdwbza.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2drsqkbcs.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2wtoovbvz.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2peqggwmn.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gt2zvzfjcrz.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2dynfnnzy.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2lndpcnes.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gt2yutgakgi.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gt2uqghfarv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gt2ryucmgji.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gt2oathxhkw.html

TS:   [...a, ...b];
来源：http://dali.ybcxt.top/Article/details/gt2wtxzezsg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hiyefqzi.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gt2ikyylboc.html


<!-- 参考信息 -->