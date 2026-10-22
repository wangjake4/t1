代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gt2ogmkcjsf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gt2wyecgkrt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cdnleiting.top/Article/details/gt2bgwudvbq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gt2ioeprkky.html

[B09] break 与 continue
来源：http://dali.chenzaomai.com/Article/details/gt2tsggystc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhoulong.xyz/Article/details/gt2wxtmfkbr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2udtdqagb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfboeanr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2ckbvhrha.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2snbqrtcz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.mhx1999.top/Article/details/gt2uunknkgh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gt2fxhwntcy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2zckinqyo.html

[B10] 遍历同时拿索引
来源：http://dali.sufxvd.cn/Article/details/gt2cyxwlbqf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yueranfly.top/Article/details/gt2nymdfugx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xziqi.cn/Article/details/gt2azhrzjbl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gt2smubjrbq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gt2lphkjgph.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gt2eahsyhbn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gogol.net.cn/Article/details/gt2fcilyttw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axqfizcj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ppjwa.cn/Article/details/gt2zbcaymhs.html

[B11] 生成数字序列 / 区间
来源：http://dali.daria6918.cn/Article/details/gt2axlilxfj.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gt2zalifpmx.html

PHP:  range(0, 10, 2);
来源：http://dali.redwolf501.top/Article/details/gt2rlvgzpwv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gt2fngyjgqa.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gt2utsvcvvw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gt2bwzfvecc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yvedp.cn/Article/details/gt2dmeayrqw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yongpay.top/Article/details/gt2yovfzbaf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhengqikj.top/Article/details/gt2hsjflttt.html

[B12] 跳出多层循环
来源：http://dali.hnqzz.top/Article/details/gt2sebougyb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.feifeiyinyue.top/Article/details/gt2qftuzwee.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xziqi.cn/Article/details/gt2ecpqalqh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gt2nvilrihh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gt2koyedrob.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gt2onbfyhrl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gt2mocunejm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gitpxvxk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.bjfxy.top/Article/details/gt2dkhzjksp.html

[B13] 判断是否为数字
来源：http://dali.jinqigfzy.top/Article/details/gt2usrrmnyj.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gt2jmnfabew.html

PHP:  is_numeric($x)
来源：http://dali.ehwqpu.com/Article/details/gt2mghmuyyw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gt2ghtumpgg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gt2zacxksvj.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gt2kaqvoqqe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jiagoushi.top/Article/details/gt2orlhsbiv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jianghu66.top/Article/details/gt2sqafjzhw.html

C#:   x is int or double or decimal
来源：http://dali.zhoulong.xyz/Article/details/gt2jervyhkj.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gt2tneleaeo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gt2sanbtwfj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuanzhike.top/Article/details/gt2zjmijmeh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2tuasogwe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2crnaghmm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2dzvbtqae.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2gsejfkty.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gt2ragvbjtc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2hyrjvivg.html

[B15] 布尔运算与取反
来源：http://dali.jiagoushi.top/Article/details/gt2zbrdfxrp.html

Py:   a and b or not c
来源：http://dali.sufxvd.cn/Article/details/gt2ybhnixnc.html

PHP:  $a && $b || !$c
来源：http://dali.zhiwuduotai.top/Article/details/gt2bybdoovh.html

JS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2fidirmgd.html

TS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2yzewrsvm.html

Java: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2mwdbtebc.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2wuxnxxpe.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjxumfwj.html

C#:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2uqeutjvp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrbqwuvj.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gt2fvvovjzf.html

PHP:  if (!$data) { return; }
来源：http://dali.shzxlz.cn/Article/details/gt2huogzuwn.html

JS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gt2zlqamsdk.html

TS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gt2qddowvtq.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cmrsbatj.html

Go:   if data == nil { return }
来源：http://dali.tianlin.xyz/Article/details/gt2qlhbwgme.html

Ruby: return if data.nil?
来源：http://dali.cucudq.cn/Article/details/gt2vwougaso.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gt2pxojiwou.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ikzuatdf.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gt2ueqzdavj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2sionisia.html

[C01] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gt2wheunxip.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gt2kncljsyy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pvkwqhqe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2bqacijma.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2ykfvodby.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2snlbhrly.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbvtmnth.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gt2whbfhbio.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2nkwnpsww.html

[C02] 默认参数
来源：http://dali.ybcxt.top/Article/details/gt2dzocejli.html

Py:   def greet(name="World"): return name
来源：http://dali.yonumen.top/Article/details/gt2lbpqikhj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ehwqpu.com/Article/details/gt2sztibsdb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2novfyfjv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvjglqiu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.andypj.xyz/Article/details/gt2mrtdcmmb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gt2evuowyei.html

Ruby: def greet(name = "World") = name
来源：http://dali.tanke756.top/Article/details/gt2hvivgxwp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stcmgqtm.html

[C03] 可变参数
来源：http://dali.hysaishi.cn/Article/details/gt2umdzqdkr.html

Py:   def total(*args): return sum(args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ednbslep.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gt2zsdboiil.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ftimxvar.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gt2qnhirvul.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsilqtw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gt2akzdozxf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gt2vksgtagu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenzaomai.com/Article/details/gt2akpuyzht.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuanzx.com/Article/details/gt2pakkkjgz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigfzy.top/Article/details/gt2qxwetnbv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gt2qisotrxm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olzzwtkn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gt2tocjqtzp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.smart0.xyz/Article/details/gt2xmstobxu.html

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gt2ohdzaubf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gt2jncbztjk.html

C#:   f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvncqqmd.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gt2xgxvhsxm.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gt2fdkypepp.html

PHP:  return [$a, $b];
来源：http://dali.tianlin.xyz/Article/details/gt2elvejggl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangdashe.top/Article/details/gt2hqfajyvc.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2ddtkmljr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhengqikj.top/Article/details/gt2rowdbbex.html

Go:   return a, b
来源：http://dali.smart0.xyz/Article/details/gt2yfvzuvhp.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2ntusrroh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gt2szrlhzbu.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gt2cvmlggat.html

Py:   square = lambda x: x * x
来源：http://dali.sysykeji.top/Article/details/gt2kqrwvnpc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gt2totsvqmb.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2wmpwqbof.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aibaodan.cn/Article/details/gt2carxtjkw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdpanspi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gt2ejauvnbz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gt2vjbbpvto.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2dhdpcakg.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gt2pvdemosc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258888.top/Article/details/gt2wwzvhbmx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gt2xlyvolrx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gt2ckcltdeg.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gt2mfaawdvm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlrimyws.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenzaomai.com/Article/details/gt2wdcrebrw.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gt2uiaxeffq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258.top/Article/details/gt2ihtzpnwv.html

[C08] 闭包
来源：http://dali.gogol.net.cn/Article/details/gt2mfafvdua.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gt2mvoolxab.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.316326.xyz/Article/details/gt2dvcrysub.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2aefbajpn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2ncuvlvir.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gt2zqlrbdbn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqnmaznu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2tcqknbzj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gt2nkhowstu.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gt2bnpghrqf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gt2rodrrvxr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gt2kvzrquzj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxbuose.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gt2gajdqxkf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gt2qzazbsei.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vckavjov.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gt2jzdzlgfw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gt2xpkcfbad.html

[C10] 变量作用域
来源：http://dali.hysaishi.cn/Article/details/gt2eetnzanv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gt2viyodjku.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgfzy.top/Article/details/gt2uqufipkr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2hiznphcj.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2ayjqyhnk.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjtdukjf.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2nlrbmqge.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gt2ghzkaltg.html

C#:   块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2gmvuxlfc.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gt2mqzivcqo.html

Py:   from module import func
来源：http://dali.fengsongda.top/Article/details/gt2ndjslafa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwbsdrsh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cheryme.top/Article/details/gt2ecsvfiyj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gt2ymdxepyh.html

Java: import java.util.List;
来源：http://dali.daria6918.cn/Article/details/gt2aldglbgr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gt2pwvtstro.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gt2raygdeps.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gt2qfhlsjer.html

[C12] 立即执行函数 IIFE
来源：http://dali.hfpthk.cn/Article/details/gt2uqijbqqt.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwmpfuzt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gt2ewljvqtg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gt2iqhznfdr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2pvylcsjy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnxiangtu.top/Article/details/gt2jxwlbawh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258.top/Article/details/gt2suwhixxd.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gt2gywdcass.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gt2sychyrzw.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gt2yiiggwqn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gt2xeqqoxbq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2ukdpwbjd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gt2cwamfgxi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbnzioje.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2cliilrve.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gt2vupskgmd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gt2dlpoohqn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gt2bffxgarl.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gt2uhuminbc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gt2dghntenh.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2rammaskx.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2qigafuuh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gjgenqqf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gt2vgnrbggv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gt2sceldckn.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2huwzhldi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gt2fdiytbja.html

[C15] 解构 / 展开参数
来源：http://dali.guannengcc.top/Article/details/gt2inrsoilp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gt2azmbdggt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.havefunace.top/Article/details/gt2uwyegpno.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikecivan.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gt2qrbzhjus.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gt2zytejwhy.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2adgpotem.html

Ruby: a, b = pair
来源：http://dali.chenzaomai.com/Article/details/gt2dmvrwprl.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlcwpnst.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gt2gzbiychq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gt2xrxbrxqu.html

PHP:  // 无重载
来源：http://dali.mhx1999.top/Article/details/gt2miwbxfcd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xziqi.cn/Article/details/gt2capeeigm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tudjortj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2ebyqdyak.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gt2pbkqjppr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gt2wbqcbyjr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kuhwaria.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2qzsgfqul.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gt2qepsrudc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2iroaylke.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gt2xlesifvm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gt2ilqaqcwo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gt2gawcyzok.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gt2ujvoxphj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gt2skgiknkg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gt2dnbnyfwp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sxryk.cn/Article/details/gt2uhqncjif.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gt2hpixafig.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gt2woyjfbti.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gt2ttumlxgv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gt2cxxtinzc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdverxvh.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gt2ucycvgzq.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2grwmbuql.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gt2pcetubgf.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gt2bxexlptw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejknrzxj.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gt2pmewkswa.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258.top/Article/details/gt2lbxognmw.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gt2ahamvwqs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gt2eymgozfu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gt2owpuorpp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2tgavbvhm.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2kcikhpon.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2dcepcgyo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aqbqgatk.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2teueepuh.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gt2rinxeynb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gt2xpgrtwsh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gt2cwfyfuoz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gt2qggziyjt.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gt2ggedwkvi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gt2gwikvake.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvowvhyy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258.top/Article/details/gt2swsxtsfk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gt2xhhsrvwe.html

[D05] 访问与修改元素
来源：http://dali.quarkkingdee.top/Article/details/gt2gmuwhjgn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzzugrdg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gt2icnfmjay.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykboezth.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gt2qxmduadr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gt2tsmblhqi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eecrtdbw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2fxbksywm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2zgpvulql.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gt2xcnaqhfq.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2lddvabuh.html

PHP:  count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oofqydir.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gt2zzoejcqd.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2zsxpdynk.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gt2edrwcpwh.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2reknhijb.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gt2pckfnwwa.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gt2ooxnngfj.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gt2jjbvdloi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gt2nfosqorl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yangfankeji.com/Article/details/gt2ztghkjwq.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2twwgcbvr.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2ujjxwjbw.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2seyllspl.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gt2gkqnpfhr.html

Ruby: arr[1, 3]
来源：http://dali.guannengcc.top/Article/details/gt2wjvwxrnh.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2nonikvcc.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gt2exklkeyh.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gt2zamctbxa.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gt2yofegaru.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gt2jjrpkhzx.html

TS:   [...a, ...b];
来源：http://dali.ydzc1.top/Article/details/gt2xkkutswx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2stygprkr.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rawzxzkk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gt2ehtqmfzw.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gt2rezicsxp.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gt2gqflnbeg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gt2aqyibhhw.html


<!-- 参考信息 -->