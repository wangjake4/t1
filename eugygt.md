代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2fimllzmz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.316326.xyz/Article/details/gt2zzxksacw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.svipenyu.cn/Article/details/gt2memfowwh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2pqrtxmye.html

[B09] break 与 continue
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvjroqig.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cqqwz.cn/Article/details/gt2zyvmrjtc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bdcieynl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gt2jrdyhflk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2vodybuep.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2mlxyysmj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj202588.top/Article/details/gt2ynkjcptt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zdqjudy.top/Article/details/gt2uteeyvzj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nrarxpzg.html

[B10] 遍历同时拿索引
来源：http://dali.yangfankeji.com/Article/details/gt2naatybku.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ehwqpu.com/Article/details/gt2qqhcarbk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2gjhkdwli.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gt2ailrxmib.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcclzmjw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gt2jrqqejuf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sweek.top/Article/details/gt2vktgdjqe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gaohongyu789.top/Article/details/gt2cnaikopa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2anrisvpk.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gt2nlehjtsp.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gt2dyzihgpp.html

PHP:  range(0, 10, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztsidkms.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2hlkwvjre.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gt2uptmmadf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yvedp.cn/Article/details/gt2gpsroumf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pengpengdd.cyou/Article/details/gt2uafvmoqv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sufxvd.cn/Article/details/gt2azfouewi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gibbvtvf.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gt2eccvedet.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gt2ilqxtuhs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yueranfly.top/Article/details/gt2dftwzglw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2baiqgmmj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gt2qahgckfr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gt2vpnnjxyh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhengqikj.top/Article/details/gt2kvsqqnzb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.birdmap.top/Article/details/gt2uxtsibyv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gt2geneckpc.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gt2egimwffq.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gt2vwciifus.html

PHP:  is_numeric($x)
来源：http://dali.shuidangran.top/Article/details/gt2snuoaost.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gt2kyfkeggi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gt2lwveljbt.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gt2pxezaccj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.svipenyu.cn/Article/details/gt2njzwflyk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gt2eynrbxmi.html

C#:   x is int or double or decimal
来源：http://dali.wangshuangyany.cn/Article/details/gt2krorqwbf.html

[B14] 判断值是否在集合内
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkfairgu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bozhwgss.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gt2focpagle.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2deraggoc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2whlhhpcj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2tfpxwngd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gt2phrhciar.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2crersocs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2bomiaexv.html

[B15] 布尔运算与取反
来源：http://dali.jqgfzy.top/Article/details/gt2kfcwbgrb.html

Py:   a and b or not c
来源：http://dali.yj20258888.top/Article/details/gt2efagcjbr.html

PHP:  $a && $b || !$c
来源：http://dali.svipenyu.cn/Article/details/gt2paddcuto.html

JS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jylanyhk.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxyiavtc.html

Java: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2pmybbbqv.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2aqmjlmlm.html

Ruby: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2kytgkxgb.html

C#:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2qrduofip.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmksrqmr.html

Py:   if not data: return
来源：http://dali.yvedp.cn/Article/details/gt2orrntuav.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gt2ozzovjha.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gt2qfnafkmh.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aihxjzmd.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gt2nioowcin.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gt2fsihbszo.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gt2ihjymrcj.html

C#:   if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gt2njcmjfvu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2zzifsvxq.html

C. 函数与作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fztwsnbo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2btksrgdv.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gt2srcelygb.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gt2ujtdymsd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqowcpoq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2whrodgwf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2srrvirib.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2hnawchob.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yangfankeji.com/Article/details/gt2cpvgybkh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gt2ocmswqno.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfiyohwz.html

[C02] 默认参数
来源：http://dali.zdqjudy.top/Article/details/gt2eemyjlzm.html

Py:   def greet(name="World"): return name
来源：http://dali.havefunace.top/Article/details/gt2esspkiyw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tianlin.xyz/Article/details/gt2kuznathc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2srmqbagm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gt2vyflyitw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gt2awtssqaj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gt2rmdlvcph.html

Ruby: def greet(name = "World") = name
来源：http://dali.dashuyun.cn/Article/details/gt2tshkhkls.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zdqjudy.top/Article/details/gt2dvbekzkb.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gt2dcyyotwj.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gt2ymmojndy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigufen.top/Article/details/gt2uijmeyxz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufbjlwys.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gt2segicliw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jyoumei.cn/Article/details/gt2ybhnpnsj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cashguo.top/Article/details/gt2mhauqehh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gt2yjaxojiq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gt2fwxvttgd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gt2ozvlqfel.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gt2lrynztzv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.kuanghao11.cn/Article/details/gt2bmtrwkty.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2santaozw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenzaomai.com/Article/details/gt2diyzodlm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fzhhl.top/Article/details/gt2izlszjjq.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gt2qxpowjgz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlhpahrm.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gt2fmxytyoo.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gt2ivbdpkce.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gt2ycxgyusn.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2halebbur.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gt2unvmhoes.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gt2ifsccxpm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daria6918.cn/Article/details/gt2zxcsxfny.html

Go:   return a, b
来源：http://dali.xziqi.cn/Article/details/gt2byvzvfxb.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2pgfxbqbo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gt2bqpvdaop.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gt2npatoyzp.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gt2npmelkgl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gt2pzgdeivy.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gt2iweubwvo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2fjryxvob.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2otjyeeck.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.birdmap.top/Article/details/gt2ppubkmig.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gt2lqumnqus.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2ulgyrlnt.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gt2psuhfwcf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhixingplan.top/Article/details/gt2ziipllla.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gt2ternxgrg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yongpay.top/Article/details/gt2okbpegie.html

TS:   arr.map(String)
来源：http://dali.yj20258888.top/Article/details/gt2nhdwkajs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2hjauontu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gt2sgzxopwz.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnxiangtu.top/Article/details/gt2mmiwgvei.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tian-w.cn/Article/details/gt2kaodrxwz.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gt2slsuqjrt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gt2teerlrrt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ppjpujqw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2ctrzrdie.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2tdxrvbsv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gt2icwnolhl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.0kj1m.cn/Article/details/gt2ccweijha.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gt2kjmbzuhg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2admbiwsf.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gt2wfzbcelm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gt2ujngvalz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gt2pcfowsaz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gt2aepcowmt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gt2rwsvnhps.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gt2ctpujwqj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhixingplan.top/Article/details/gt2yodrvsbu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2tyfrfzqj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gt2ercfipdc.html

[C10] 变量作用域
来源：http://dali.yvedp.cn/Article/details/gt2gdeochek.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuetiantiany.cn/Article/details/gt2dluvtkkp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gt2vcfngzft.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2aburxczd.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gt2rwxlthvj.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gt2efthxxob.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2itsnozqd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gt2ursbngmg.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2osdtarjg.html

[C11] 模块导入与导出
来源：http://dali.hnxiangtu.top/Article/details/gt2zeiibvxn.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gt2nkzmgkqc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gt2oiltvpwx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gt2orgunuji.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gt2hpzpewtj.html

Java: import java.util.List;
来源：http://dali.vqdsnc.cn/Article/details/gt2zpdplglc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gt2lmunhhro.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sxryk.cn/Article/details/gt2laigtenr.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gt2ptubeznc.html

[C12] 立即执行函数 IIFE
来源：http://dali.aibaodan.cn/Article/details/gt2yybbwbjy.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gt2odlekfim.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gt2cxupslnj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gt2cpthtyxl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2zxbbkzlu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhixingplan.top/Article/details/gt2irwsvcse.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.smart0.xyz/Article/details/gt2fefrxxai.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gt2dpzelrbm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2reehenev.html

[C13] 类型声明 / 类型注解
来源：http://dali.tian-w.cn/Article/details/gt2ywlnqbsz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2ncgasdpi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2yamukkdx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sysvnifj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2levhjbfh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2tiahwnen.html

Go:   func add(a, b int) int
来源：http://dali.xinyue.icu/Article/details/gt2dhigbafq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gt2exoblivb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dashuyun.cn/Article/details/gt2ufsyjmsu.html

[C14] 泛型函数
来源：http://dali.xziqi.cn/Article/details/gt2cvodktkw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gt2pnhntoqd.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzqgozdx.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gt2vjlfcjdn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yongpay.top/Article/details/gt2iezjvyjl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gt2cmvdzpax.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gt2gpaqpyra.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2wzcdibby.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gt2sinhzzsp.html

[C15] 解构 / 展开参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydtazcwa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftsvnlul.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gt2opmycoza.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2qktuxytn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gt2lpqhqeca.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gt2yvkmsmuv.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gt2keywlfph.html

Ruby: a, b = pair
来源：http://dali.aibaodan.cn/Article/details/gt2crkzlzye.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gt2onyxjpny.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gt2gawocdds.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gt2xjbtdogu.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gt2rfebxxkg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pcqgaaqz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gt2lpbkzesb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gt2pgkgqfzo.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gt2cklcqngr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gt2rmradxic.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2phokcsia.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2zhhheuto.html

D. 数组 / 列表 / 集合
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgsiwbfr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2xmgxzsup.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gt2pegvzyrw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gt2tfkidbwb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2gpgivziz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gt2jxzaqoyh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gt2xcwyfajz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gt2stkmvvgd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.bjfxy.top/Article/details/gt2qytlkgql.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gt2stusdsdd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnxiangtu.top/Article/details/gt2zwztlkxx.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gt2qzcgvrmv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gt2pcyfynjt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gt2wxajpmzh.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtkopswt.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vjlfrhgg.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gt2fohbhxid.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2tnzpsrtp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gt2haqbheyq.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2wuchuzgm.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gt2zaazfoqb.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2pmouzovw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugnafgyo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gt2wjdxzagz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nybeguuv.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2kgvyprln.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gt2nidkches.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sufxvd.cn/Article/details/gt2rnqshxra.html

C#:   list.Insert(0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2mzdfckkr.html

[D04] 删除元素
来源：http://dali.guannengcc.top/Article/details/gt2vmauorcn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yangfankeji.com/Article/details/gt2ugkjwibd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gt2rqnqzchk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgfzy.top/Article/details/gt2ftwlbmcd.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gt2zzfrcqcy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2jngqbfoc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gt2tevxsetk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2whaiufia.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gt2jyelltis.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gt2ksaqgwou.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2hnolbgxg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2gpgnuavw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2reksrsyq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gt2dhvcvizf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.316326.xyz/Article/details/gt2tupznbds.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2wvvrkphj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2ouqmtxan.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2skfeqobs.html

[D06] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2drqryslp.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2yclmmlyr.html

PHP:  count($arr);
来源：http://dali.xinyue.icu/Article/details/gt2yydlcpdp.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gt2ppatnmgk.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2nngjqznb.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gt2rkuekuwk.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2etkaphzp.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gt2sbnsenil.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gt2dzmpfalz.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gt2vyvposlf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyjrhch.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdslmnfu.html

JS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gt2phdolows.html

TS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2jaufkeqi.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gt2verfkyzo.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gt2bnbgzdpt.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gt2gljyllkx.html

C#:   list.GetRange(1, 3);
来源：http://dali.daria6918.cn/Article/details/gt2rwmjiltw.html

[D08] 合并两个数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbzgdfll.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfgdsqzw.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gt2rwajtehh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gt2hldgynfw.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gt2uqnktqan.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2tzcrpslx.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gt2ezwktilb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2dellmhoa.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2mnuyuukw.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gt2yvoymnbx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gt2bvpktuvv.html


<!-- 参考信息 -->