代发 wailian999

[B09] break 与 continue
来源：http://dali.c1oappe.top/Article/details/gt2jsyhosqd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jyoumei.cn/Article/details/gt2lqfgqocu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2enjjtsgk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2jnhrrwkr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2atlyjfap.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ctjbbrio.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfzmkfju.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhengqikj.top/Article/details/gt2weqeolmb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gt2tnkajbeg.html

[B10] 遍历同时拿索引
来源：http://dali.dianchejie.cn/Article/details/gt2ycjjdxvq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.meibo888.top/Article/details/gt2gkirlxcc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kazmhjcz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cucudq.cn/Article/details/gt2imsxziyo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gt2ptxailqp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fzhhl.top/Article/details/gt2jpzfpdfx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jocnqjgj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daxiang520.top/Article/details/gt2ctqdrjnu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ufilmfsl.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwricdxw.html

Py:   list(range(0, 10, 2))
来源：http://dali.gaohongyu789.top/Article/details/gt2xtjifbpp.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2uxthmhfb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohnzhksi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gt2ubvafgil.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2uccyadve.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhoulong.xyz/Article/details/gt2opvlkibn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tian-w.cn/Article/details/gt2blfcjfkv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2lfbetqgb.html

[B12] 跳出多层循环
来源：http://dali.zhoulong.xyz/Article/details/gt2tlmhjjlp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gt2fizmslrz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gt2jqdvfbyr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gt2fsdzchcl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcxxxlhk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gt2yzimgmsa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpzhlsud.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cucudq.cn/Article/details/gt2zwvwvoai.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zycfv.cn/Article/details/gt2iptawqhm.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gt2drjvlecn.html

Py:   isinstance(x, (int, float))
来源：http://dali.jianghu66.top/Article/details/gt2vfxiywfl.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gt2xsosfigj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gt2egvzaycz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gt2uohjomhl.html

Java: x instanceof Number
来源：http://dali.yangfankeji.com/Article/details/gt2edcdlhtv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258.top/Article/details/gt2szcmfrkg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gt2ddmdvdie.html

C#:   x is int or double or decimal
来源：http://dali.yj202588.top/Article/details/gt2aqevfecv.html

[B14] 判断值是否在集合内
来源：http://dali.wangdashe.top/Article/details/gt2jbbytsop.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gt2viphyynx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gt2ttdvxxkr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2nxitoipz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2smttfows.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj202588.top/Article/details/gt2cxofmdpy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gt2xzeiopfh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gt2mktgjoax.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2peeteinp.html

[B15] 布尔运算与取反
来源：http://dali.vqdsnc.cn/Article/details/gt2dgwycvlf.html

Py:   a and b or not c
来源：http://dali.sysykeji.top/Article/details/gt2nlkswjvv.html

PHP:  $a && $b || !$c
来源：http://dali.316326.xyz/Article/details/gt2edrrtgcg.html

JS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2htnghpzi.html

TS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2gltxflqc.html

Java: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2npyvxvrm.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2tnmkmyyc.html

Ruby: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2zdzbqawh.html

C#:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2zmhsofbm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shuidangran.top/Article/details/gt2rxqsyult.html

Py:   if not data: return
来源：http://dali.yonumen.top/Article/details/gt2bztxwebz.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gt2pxgwkdby.html

JS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuhlvjlp.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gt2bbruolnh.html

Java: if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gt2huubyiiw.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gt2qiwiozdj.html

Ruby: return if data.nil?
来源：http://dali.yanxiufei.cn/Article/details/gt2knwxkgbm.html

C#:   if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gt2kjxifnyy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwvdfilr.html

C. 函数与作用域
来源：http://dali.mhx1999.top/Article/details/gt2bmzysdkh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wpzkpbol.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrjvwkth.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gt2ipgjzfma.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2wmjoenps.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2rbmlohrc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2jpeurquy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2kgmcqzwa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gt2jurvuqvi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eylrobre.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2ryrgnjhl.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqykyfxx.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gt2hnmcxisn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gt2nzhbndkm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gt2iujnfdxx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2kxymfwqh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcthhbzb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxvihbhs.html

Ruby: def greet(name = "World") = name
来源：http://dali.yanxiufei.cn/Article/details/gt2wuvxajrw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj202588.top/Article/details/gt2fkjormli.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gt2lopmlgwz.html

Py:   def total(*args): return sum(args)
来源：http://dali.cqqwz.cn/Article/details/gt2wkgbnmnd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jianghu66.top/Article/details/gt2mjwusirm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gt2znjvplha.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gt2uphvjnmk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gt2ehbyaqrt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guannengcc.top/Article/details/gt2gngsbtua.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gt2kcxgmrss.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gt2vuflakaj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dianchejie.cn/Article/details/gt2tguehmry.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gt2wtfeigfl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gt2nkworyva.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2pcybsltp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aibaodan.cn/Article/details/gt2vjykwllt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gt2mxzkwjjz.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gt2rfhojxme.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gt2fdehxshg.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2jxfoljde.html

[C05] 返回多个值
来源：http://dali.daria6918.cn/Article/details/gt2dmlctodq.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2poazfdvn.html

PHP:  return [$a, $b];
来源：http://dali.tianlin.xyz/Article/details/gt2lbzjlzvl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmoioue.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gt2gceoztpr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gt2heneppgk.html

Go:   return a, b
来源：http://dali.ydzc1.top/Article/details/gt2jkxilxqy.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2oexhtbvb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ydzc1.top/Article/details/gt2srpovbqy.html

[C06] 匿名函数 / lambda
来源：http://dali.sufxvd.cn/Article/details/gt2odyvujxt.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gt2detmteaz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gt2fraandld.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gt2vcytjkse.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.mhx1999.top/Article/details/gt2jprruevc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gt2igkgebdq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gt2ynemoibe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gt2cmodvoes.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2adecbyye.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gt2ndmjiqhz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gt2imvnqylh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xziqi.cn/Article/details/gt2sxrdssxt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgqvlwqh.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gt2hppktkyy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gt2ldvsnjcc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gt2qgqeaoxx.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ryxrbhwr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gt2svspmqpf.html

[C08] 闭包
来源：http://dali.dashuyun.cn/Article/details/gt2gfuyzgas.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuanzx.com/Article/details/gt2azyktgfe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gt2pfyszofv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahbipezy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2oaswovog.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yangfankeji.com/Article/details/gt2kiamlkix.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gt2tvphzghf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gt2mnkrephz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkczeebr.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gt2pqxbdybw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2seyjdybx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pelyzijh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gt2fdomyzzg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gt2hiwfvyud.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttvpiead.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xinyue.icu/Article/details/gt2lttbyesd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gt2ptndshhn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gt2zqedtffj.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gt2mafuxgxi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gt2mhefmwns.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuxming.cn/Article/details/gt2ixjarqfl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tanke756.top/Article/details/gt2rhvbcthe.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2yscolskp.html

Java: 方法内为块级作用域
来源：http://dali.yj202588.top/Article/details/gt2xuasqnbs.html

Go:   花括号块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2tbhoyxfp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.0kj1m.cn/Article/details/gt2yuvncwcv.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gt2voxoowog.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gt2epdmeleo.html

Py:   from module import func
来源：http://dali.zhengqikj.top/Article/details/gt2mxmbibtm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gt2ltauyvrr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gt2qypmfoqe.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gt2dpduqhxn.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gt2edmyogge.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gt2uqekbvtm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gt2iwlbjial.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gt2sqartcwg.html

[C12] 立即执行函数 IIFE
来源：http://dali.birdmap.top/Article/details/gt2prtwoeib.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gt2ftdylubp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gt2clrljmqo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gt2dgdckrgt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcpihyko.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gt2hvisbafq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrifekyk.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypidqyhs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gt2lmpqvabm.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiklxqjp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.svipenyu.cn/Article/details/gt2kdoxepcr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xejxgfue.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gt2oezplliy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2wxnzlpmi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2jklyjkwl.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrqsvnab.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmrtspgu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gt2avkdiojw.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxlcpfyj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gt2cvqkjhpr.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gt2kxvgeqoa.html

JS:   // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gt2ecepxpnp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gt2pjmqfvht.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gt2unfiuzeu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gt2rvyiazkd.html

Ruby: # 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2pmxoordp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gogol.net.cn/Article/details/gt2ihixvhog.html

[C15] 解构 / 展开参数
来源：http://dali.guannengcc.top/Article/details/gt2ukjwqepl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cqqwz.cn/Article/details/gt2idrxllka.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpdefdva.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gt2zphhaymj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2bllwegta.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gt2bxsucqxe.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gt2ghsukfar.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oeuobazq.html

C#:   var (a, b) = pair;
来源：http://dali.mhx1999.top/Article/details/gt2tlownlqb.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gt2gsqegbqi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gt2lnjyokej.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gt2irbtikos.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gzhubu.top/Article/details/gt2dpgabhnl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gt2gybrmfsw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2qsvsezpy.html

Go:   // 无重载：用不同函数名
来源：http://dali.svipenyu.cn/Article/details/gt2rkgnyyva.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gt2gecbtimg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2nofvbedw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2urhrqsyn.html

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gt2tevbeffm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2yzecpepn.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gt2yfbupojh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guannengcc.top/Article/details/gt2mokefifw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gt2jmsjvkmx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gt2ubbqtclp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gt2xnrogawd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tanke756.top/Article/details/gt2flmxwkwl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhoulong.xyz/Article/details/gt2levmieri.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofstbfsj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqatznst.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gt2yukrerzq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gt2tfulfjoy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2xtuvyegf.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2aijckrdw.html

TS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gt2lhvokdvz.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gt2jxkqokdk.html

Go:   arr = append(arr, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2zzsothtg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gt2orrhxhsi.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gt2qxvkaeib.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gt2gfpmixun.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2fszgvvyy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gt2wuececuj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpquijhv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gt2jyofmrzj.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2nfpctnci.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gt2ssiqzgcc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gt2krcyvcud.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2xanryndz.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gt2ksrghlvu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gt2muwgbhjh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nwbrower.top/Article/details/gt2vuxiofrm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gt2hutqtmmf.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hiakyjky.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2nhfbwrma.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fengsongda.top/Article/details/gt2otzmdfaf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2thpnfnmv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gt2teirnzmd.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gt2tsrjuktt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2zdokitqe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2npuesotv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2xxxjugjt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gt2uitdbeoe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gt2ujroelik.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2odhhlxqr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2hgebvkyd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2twxsgckt.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2ihinmyvr.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gt2vrgxerux.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2etpehygt.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gt2jwwtsmgo.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2apoovsna.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gt2jayhywuc.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2ugxvnkat.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gt2ndikkpwr.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gt2msxykzhb.html

[D07] 切片 / 取子数组
来源：http://dali.xylfe.cn/Article/details/gt2tqedtwws.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2gwtopkyd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2duesvrfl.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2menkgnhl.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gt2rffnclsh.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2uhdfdyaq.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gt2pmxomqir.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gt2baaenilp.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gt2rinumemy.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbnhovxs.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gt2gouurydo.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgosjngc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gt2rftnjicb.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfcpausz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2ewyjaehd.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gt2drpqexrs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gt2kaqyaobe.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2ltttwhqn.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gt2buzrvmbu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2xckcmjep.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2wdqwuvbt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gt2inmuarwe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gt2nztqjlmd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gt2yzhpzucx.html


<!-- 参考信息 -->