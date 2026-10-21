代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtfmrsbdts.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gtdrvmawjd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hammf.cn/Article/details/gtkgijzxwx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtinssakpu.html

[B09] break 与 continue
来源：http://dali.ehwqpu.com/Article/details/gtuujebwpv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gthxpahyju.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gthxiecaxs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gttyuuqnth.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtpdrshhpt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtnllvurji.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangdashe.top/Article/details/gtvtzsbmhn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj202588.top/Article/details/gtclhxzsqs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtxjhviteb.html

[B10] 遍历同时拿索引
来源：http://dali.xinyue.icu/Article/details/gtrvuyzens.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.svipenyu.cn/Article/details/gtvjqilzaw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.haohaochexian.top/Article/details/gtqswnsgwx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtcerhtxjf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gtylssmyex.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hfpthk.cn/Article/details/gtzgjykbyz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aibaodan.cn/Article/details/gtbmlbxxde.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhengqikj.top/Article/details/gtaaqqihty.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqmhntko.html

[B11] 生成数字序列 / 区间
来源：http://dali.cashguo.top/Article/details/gtxxehkxie.html

Py:   list(range(0, 10, 2))
来源：http://dali.ehwqpu.com/Article/details/gtcgoxroka.html

PHP:  range(0, 10, 2);
来源：http://dali.sufxvd.cn/Article/details/gtbjthibtg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtxkywbwwc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmyiztdr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yangfankeji.com/Article/details/gtmbiggwfy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tian-w.cn/Article/details/gtwxqhebpf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cucudq.cn/Article/details/gtezthbkbi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ivvv.top/Article/details/gtgrzkkzuc.html

[B12] 跳出多层循环
来源：http://dali.mhx1999.top/Article/details/gtxnwltyfy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangtech.top/Article/details/gtqeycppmt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumsersbf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtxlsfmeql.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtgmblrwmw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gttrlrrslx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrtruklq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gtflkhcnui.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yueranfly.top/Article/details/gtanedjiqw.html

[B13] 判断是否为数字
来源：http://dali.hfpthk.cn/Article/details/gtpsuaozpd.html

Py:   isinstance(x, (int, float))
来源：http://dali.bjfxy.top/Article/details/gtqkhegipb.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gtkvsigpoe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gtfhqimkft.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtqmiqzydd.html

Java: x instanceof Number
来源：http://dali.shangyingyoupin.top/Article/details/gtnbcglnqk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtaxldygme.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yonumen.top/Article/details/gtiwmeajhu.html

C#:   x is int or double or decimal
来源：http://dali.ppjwa.cn/Article/details/gtihsxpyjs.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovzfsrbh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloiloxpc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ydzc1.top/Article/details/gtuduyenhe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtmejtzhxr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtppoacwnp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtacqnnncr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gtowebsctd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtgfanenrm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtsdrsvovx.html

[B15] 布尔运算与取反
来源：http://dali.fengsongda.top/Article/details/gtkhmhonts.html

Py:   a and b or not c
来源：http://dali.iojbl.cn/Article/details/gtgvxqwrxw.html

PHP:  $a && $b || !$c
来源：http://dali.pycfn.com/Article/details/gtrhwtundj.html

JS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtiulbrnvp.html

TS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtukvwfrxy.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtxxgsuwnt.html

Go:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gthwkkepuc.html

Ruby: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtuzjhgjhy.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtrpkpghvj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gogol.net.cn/Article/details/gtywxacbsu.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gtejnbjlsh.html

PHP:  if (!$data) { return; }
来源：http://dali.haohaochexian.top/Article/details/gtshtvmmro.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtrwlcxiwo.html

TS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtqdbggzvu.html

Java: if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtamyfpmlc.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gtcwtdfdfp.html

Ruby: return if data.nil?
来源：http://dali.smart0.xyz/Article/details/gtuhcikhdb.html

C#:   if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtmlleqxdx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtivofovjq.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gtczbmwnxu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtzgxjyksa.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gtrlveqyeu.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gthvbnjmng.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgurrqrjj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gttzkhxwvo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtdpmkndkf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gttpobypip.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258.top/Article/details/gttvlerhnt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gtqbxuvtft.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtwfrqyrjj.html

[C02] 默认参数
来源：http://dali.0kj1m.cn/Article/details/gtmvfwnjhx.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gtigoekkbo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shuidangran.top/Article/details/gtxksfqfff.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtkgbtjbpg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtqfelzvsz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gtquuzguwj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gtsuyvgqgt.html

Ruby: def greet(name = "World") = name
来源：http://dali.haohaochexian.top/Article/details/gtpwqkvyqy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtivtujowb.html

[C03] 可变参数
来源：http://dali.mhx1999.top/Article/details/gtwnyhyzoy.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj202588.top/Article/details/gtbupekmpu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.quarkkingdee.top/Article/details/gtfmzvjsoh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtsqhxgfmd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtjxultavr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yvedp.cn/Article/details/gtnxlrfgwc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gtezhmylmd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gtwjayrsor.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gtwwufljrq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gtcklijtmz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gtupikydcq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gthscidurv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtcqmxrwdt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.havefunace.top/Article/details/gtnwpwcmyv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtgxovephe.html

Go:   // 无：用配置结构体参数
来源：http://dali.yonumen.top/Article/details/gtzqyffjxo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtwokoyldz.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalyvbyiv.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gtkirbkwxe.html

Py:   return a, b
来源：http://dali.fengsongda.top/Article/details/gttwzmzhrh.html

PHP:  return [$a, $b];
来源：http://dali.yangfankeji.com/Article/details/gtudcpdkfx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtlkfdolvl.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gtxdfvdwbp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.vqdsnc.cn/Article/details/gtaskoxckb.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtldgusbtp.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gtlmudsdzq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gtlqvuwkyf.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtxnuzezxj.html

Py:   square = lambda x: x * x
来源：http://dali.haohaochexian.top/Article/details/gtcspubswb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtrdieldgb.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtrqdwroiw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtdjnvezvg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqjvdnhi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gtjfvdeaza.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gtvomrvcwr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtjymiynrr.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gtojxbymjm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtwpilvzmy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtuggyarwh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.birdmap.top/Article/details/gtjrwdevin.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gtixzczstw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gtknoszezf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxinkj.top/Article/details/gtjcowrfyq.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gtfrpmvizv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sufxvd.cn/Article/details/gtevalinjk.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gthvbmxjkh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sweek.top/Article/details/gthygtykis.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gaohongyu789.top/Article/details/gtixfvikyu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtzxbhutih.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gthlbtlmoj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gtyzcxcrzv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuanzx.com/Article/details/gtdvmcmgcw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxsfatec.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtjuzzsqzk.html

[C09] 递归
来源：http://dali.zhoulong.xyz/Article/details/gttscvhnvf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gtcgvwmhvb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtlztsjogt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtuwdewmsl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtpqlficho.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtsnviccev.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gteuvxmpql.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtbhztjkzo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zycfv.cn/Article/details/gttnlodblg.html

[C10] 变量作用域
来源：http://dali.nanxuanxn.top/Article/details/gtqkpzahex.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangshuangyany.cn/Article/details/gtkgvkmclw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gtveuagoco.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gtbrvpwgho.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigrjxtmb.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtteeornrj.html

Go:   花括号块级作用域
来源：http://dali.yueranfly.top/Article/details/gtndckjglq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dashuyun.cn/Article/details/gtsrljxzbj.html

C#:   块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrsbpphv.html

[C11] 模块导入与导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedvvjtrg.html

Py:   from module import func
来源：http://dali.0kj1m.cn/Article/details/gtgygipwlw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnqzz.top/Article/details/gtziiflgec.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtbbyxpiei.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gtttlpuudx.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gtdeqpcauj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gtudqgxbum.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiumlknbc.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gtzormiabr.html

[C12] 立即执行函数 IIFE
来源：http://dali.sysykeji.top/Article/details/gtvusmtpxu.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gtttrwcyay.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gtwtogmkox.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtoscmrbiv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtuhuxmjrw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gtmsogzced.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guannengcc.top/Article/details/gtqqngkywp.html

Ruby: -> { puts "run" }.call
来源：http://dali.kuanghao11.cn/Article/details/gthzkzivjg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtoekhnczm.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gtnspmblar.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigufen.top/Article/details/gtvgchhdyw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtkwxiaegp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gtgzlohdjt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtbjzqggui.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtugfwxtfu.html

Go:   func add(a, b int) int
来源：http://dali.iojbl.cn/Article/details/gtaxsvyipr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gtlbwquoto.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtroyanzyy.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gthidjsjbj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gttxhwedug.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtoeqivrpw.html

JS:   // 无泛型
来源：http://dali.yj202588.top/Article/details/gtwsqbcpqk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtvddvbeux.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gtdhoohpgs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gtcmoeeksk.html

Ruby: # 无泛型
来源：http://dali.andypj.xyz/Article/details/gtmjbbjuev.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fengsongda.top/Article/details/gtxeeqramf.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gtraqxqnbh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gtviuxylct.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gtdwtihavr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnaaapoha.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtnlgdxodz.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gtqtnhgsjn.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gtxasncsnk.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gtarnexcza.html

C#:   var (a, b) = pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiqcwfgx.html

[C16] 函数 / 方法重载
来源：http://dali.bjfxy.top/Article/details/gtddmmgmai.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xinyue.icu/Article/details/gtjlhdzkds.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gtfrrvbjzc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gtmcwhqreu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gtfvdlvoxt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbggdqvrs.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gtivofddtw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gtbminylga.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xziqi.cn/Article/details/gtzjqpmxby.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtmwgdqrep.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gtimxvsvvf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtnacjpjae.html

[D01] 创建数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtneywuhlh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gtmykqctba.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gtisuupjhe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtlssmnkao.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gttivsdlho.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dashuyun.cn/Article/details/gtnhwjpcwe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gtxgtutgnv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyybqwbwa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gtcimncykr.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gtenfcudxb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gtyohjmujl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gtquzqulfk.html

JS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtvqpxwrfb.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtbnbghsow.html

Java: list.add(4);
来源：http://dali.bjfxy.top/Article/details/gtuxdcegac.html

Go:   arr = append(arr, 4)
来源：http://dali.9152youxi.cn/Article/details/gtvrwjnhxo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gtqrzaiwhp.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gtxkhhjvbt.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gttbndgxpo.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtcyusauhh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhoulong.xyz/Article/details/gtphqmjaih.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gthqrguaun.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gtkmmexbtr.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtkrrqbxvq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ydzc1.top/Article/details/gtrszriwbb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gtdvrbwlrp.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gteplygrat.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gtlckcqyaj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtudrknkqk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gtvebheoug.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgfzy.top/Article/details/gtuhebpxbc.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gtdiydcluc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtqbbgwwvk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daria6918.cn/Article/details/gtljckiphh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtfhwrmmgv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gtnaeirkkh.html

[D05] 访问与修改元素
来源：http://dali.vqdsnc.cn/Article/details/gtnspyfpml.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtyewopfqs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtuasvcyfi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtaukenzth.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daria6918.cn/Article/details/gtoflpucma.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gtgsvddhgr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtzamaxhfk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtjajqwnht.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gthjxmmpuh.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtyqrnttxa.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtsdcaivdc.html

PHP:  count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtiurmdfyv.html

JS:   arr.length
来源：http://dali.sweek.top/Article/details/gtnijofcuj.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtnpvxnoyk.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gtdgnncjvm.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvppskhjb.html

Ruby: arr.length; arr.size
来源：http://dali.yangfankeji.com/Article/details/gtxwtxpliy.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqaibwxn.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtbvfvkjek.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtdlwwdreb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtudnsvwbg.html

JS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtqdtmgumt.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gttovjrivl.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtslcvwzgs.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gtohdddhru.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gtxwrjuwds.html

C#:   list.GetRange(1, 3);
来源：http://dali.gogol.net.cn/Article/details/gthslpgaia.html

[D08] 合并两个数组
来源：http://dali.wangdashe.top/Article/details/gteiaqitge.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gtfewkjqjy.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258.top/Article/details/gtgqfcytvz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gtmcbzwoyy.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gtkeeannik.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gtvuhhfmor.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gtebcuqacj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtkmtzrmzi.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtgiayvkew.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gtqxcelzbr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtfcelcuow.html


<!-- 参考信息 -->