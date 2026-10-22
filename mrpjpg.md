代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtpnsabbrs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtbxfazosy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.svipenyu.cn/Article/details/gtgyfiqbme.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtbqsgmodf.html

[B09] break 与 continue
来源：http://dali.fzhhl.top/Article/details/gtjatfuzri.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gtdsvvmujd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtnqrphqmx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gteejzvexh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtcjczkapl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtcbdjpvrr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tianlin.xyz/Article/details/gtocwtmaxb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuxming.cn/Article/details/gttmbjqiuz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtxgtcgttt.html

[B10] 遍历同时拿索引
来源：http://dali.shuidangran.top/Article/details/gtchbktbsa.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gtvyiytshw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gtdgpjprqw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gtzbkqajkr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtyxuqewpa.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtwgwjtfpb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cheryme.top/Article/details/gtabeyroab.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zycfv.cn/Article/details/gtsksgscrt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmydxyqwl.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinghuilouyu.cn/Article/details/gttxxoihjt.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gtziidgbae.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxinkj.top/Article/details/gtafwrpehb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gtirrzgaxo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gtmumsmwcu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.guannengcc.top/Article/details/gtwhnxwetw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cqqwz.cn/Article/details/gtwztxgrau.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aizwys.cn/Article/details/gtokxcpsfm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guowangkeji.top/Article/details/gtqhwklbet.html

[B12] 跳出多层循环
来源：http://dali.daxiang520.top/Article/details/gtuaxcdour.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yongpay.top/Article/details/gtvufeqgbk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gtccaoavar.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtcnmzdgko.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gthxvlpfxl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtrfjjthty.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gtxfqrtwom.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gtvalapeqg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gtnevbyhqm.html

[B13] 判断是否为数字
来源：http://dali.daria6918.cn/Article/details/gtfudgfekv.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gtkvpwhpcg.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gtlwogzjxr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtptwzholt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtpuubenzs.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlusutnf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xylfe.cn/Article/details/gtdcnbhpbz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdorlyndp.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gtxkwtmfsj.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gtdpffqugh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hongshengwenyu.top/Article/details/gtqbeemxsk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xinyue.icu/Article/details/gtkfzxoafp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gtchqqiozt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtypheujmh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gtadsiuabh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gtnhontkac.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmzwgmhz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtmnaogwjs.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gtimmlfsvw.html

Py:   a and b or not c
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpijxvgd.html

PHP:  $a && $b || !$c
来源：http://dali.chenzaomai.com/Article/details/gtzbzbzwjr.html

JS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtityxrhzq.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtmdqecwyz.html

Java: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdidqmni.html

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtegxkgrwj.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtmpmsovvq.html

C#:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gthfrducfz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ivvv.top/Article/details/gtzqjatrna.html

Py:   if not data: return
来源：http://dali.sweek.top/Article/details/gtdcpvlwfo.html

PHP:  if (!$data) { return; }
来源：http://dali.xinyue.icu/Article/details/gtmvrgmjfy.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudqueqfy.html

TS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtnjxhftdu.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gthcdilesq.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gtbkzautch.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gtgkbxacby.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gthtmddxvy.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfavvqme.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtqrkzfrxy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwlnjymxq.html

[C01] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtmjdxltxa.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gtlrzebuht.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtszijawnf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gthppepoyf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtpthguosx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtijnqgamc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sysykeji.top/Article/details/gteretqqex.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gtgoygtgrj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtoarmpxzv.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtnwfozwtu.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtmokdphxk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gtcindzmtp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtbpcvvvsr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtfjskhvaj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenjidiqi.icu/Article/details/gtbwcsbxxh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gtnhspfrcs.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigufen.top/Article/details/gttzsclhnh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuanzhike.top/Article/details/gtjntjtjlf.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gtkeyutdgz.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gtgdqqkdon.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hfpthk.cn/Article/details/gtpqsjzlcj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtlwbalxoj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtpwaqorbo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gtfbxsxjli.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tian-w.cn/Article/details/gtqbacluki.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtuvzutwfv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gtvrhgfntf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnqzz.top/Article/details/gttojxgpkw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gtvqtzgvxb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtvkbrlzyy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtwfszzlcu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gtvckdwnkn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pycfn.com/Article/details/gtywneyhyi.html

Go:   // 无：用配置结构体参数
来源：http://dali.jlsjyb.cn/Article/details/gtyoxefddd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtvfkrayju.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtqitfdoqu.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtwqsshlrr.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtiijjjqnn.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gtdsemulya.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gtfmxhmnvg.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtlwarwoqn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gtjulfpcjq.html

Go:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtvzkqtjwq.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtuamnelit.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gtmewksvru.html

[C06] 匿名函数 / lambda
来源：http://dali.daria6918.cn/Article/details/gtvkaibuks.html

Py:   square = lambda x: x * x
来源：http://dali.yanxiufei.cn/Article/details/gthjvrvwlh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gtcvlbtvgq.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtljwzdgxr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gtvbgffmoa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtnrjootvf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gtmwamehkv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjntgfws.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtrwmrprdc.html

[C07] 把函数作为参数传入
来源：http://dali.xuanzx.com/Article/details/gtdecxsuxh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gtwcurooso.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnqzz.top/Article/details/gthbjosntu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gthraaexpv.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylysrqmf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gtdrgqilll.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gtlogppnrq.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuanzhike.top/Article/details/gtszszvoma.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gtunsitifn.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gtflrnyglb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gtlsrasgqt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtwaicwxwf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtimlzjigc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtzxusmlbj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gtejwuhzsu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gtrssodwyt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gtpfdcdjtg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtkxmqoqth.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gtmyrcuaqu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtyoldwhxm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gtmwdvlftk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtzvglescz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtaatmdbcf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gtynbpnssa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtgqcbaons.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxhvjpsh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gaohongyu789.top/Article/details/gtucglatcj.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gtawpdpkya.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258888.top/Article/details/gtfybmteuq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gtyscclkzc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfmrawaa.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gtwhhfldwe.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gtpglktgep.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gtloahpext.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gtzzhrcdml.html

C#:   块级作用域
来源：http://dali.fengsongda.top/Article/details/gtclmmsfdx.html

[C11] 模块导入与导出
来源：http://dali.xuanzx.com/Article/details/gthnfktjsh.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gtlksapnrw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtylwkfhdz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtllqxvwmm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tanke756.top/Article/details/gtsvjeajxb.html

Java: import java.util.List;
来源：http://dali.smart0.xyz/Article/details/gtxrwygdpt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gtgzuebzna.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gtwqvxgaiw.html

C#:   using System.Text;
来源：http://dali.xuetiantiany.cn/Article/details/gthbetmbvs.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gtsknjdeqp.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gthldrccjq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gtwskdkpbx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtbuhmadtu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtsofsnrph.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gtejtiomim.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gtvwvfaggs.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gtyeitfqtq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gtvganoocf.html

[C13] 类型声明 / 类型注解
来源：http://dali.guowangkeji.top/Article/details/gtujzquyoq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gtoigmvsbf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gttlsezfwo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gtzjbfiguk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtjjvrzmqy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtqxfiyihr.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtropixozc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangtech.top/Article/details/gtujwujprd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.birdmap.top/Article/details/gthwakrarh.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gtgnjijfkr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gtzzqmxbwo.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtjwtchixr.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtbijgjgin.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrnuqarym.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gtmkhtdxwy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gtqyjdljih.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtlsehzvur.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258888.top/Article/details/gtnoggdpzj.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gtiyiygtbl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gotoacloud.top/Article/details/gtctzilngm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gtootkmebc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtuwixaevc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhengqikj.top/Article/details/gtayigzaqc.html

Java: // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtgklggjki.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjnkmxle.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gtognnebnk.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gtmonseokl.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gtqeyachve.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gtuatszmqi.html

PHP:  // 无重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrpawxnl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gtarhxyjgp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gtrrsiqbyu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aizwys.cn/Article/details/gtdisivqxm.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gtkpejkfoz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gtxaznfqjn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gtyfqjpqch.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbgaovnky.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gttscoxyba.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtewyrhajo.html

[D01] 创建数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtobabcldy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gtftsulkua.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gtnfufutqu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtwvtdnnmp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gttnoelxca.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtysrlakzh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnldybpeg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sxryk.cn/Article/details/gtbigfzkhs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gtdenyyayf.html

[D02] 追加元素到末尾
来源：http://dali.jqgufenzy.top/Article/details/gtmjdxcmkn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gtvdxcmfco.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gtirqjblvl.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtwqtunifv.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtywengcpn.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfafvfbsx.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gtkalwupef.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gtypcufnwh.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gtoyjxnobo.html

[D03] 在指定位置插入元素
来源：http://dali.zhiwuduotai.top/Article/details/gtezjxnvtn.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtxegzqpaw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gtnaiuksdn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtlpvhmxnz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gtsmwpnxtz.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtcabrxzjn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tian-w.cn/Article/details/gtasgcuhiq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.vqdsnc.cn/Article/details/gtwanvzsnh.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbqwitbd.html

[D04] 删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtthcjwlxu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtuodlpfgj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetvxulal.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gtnljsatoc.html

TS:   arr.splice(0, 1);
来源：http://dali.yanxiufei.cn/Article/details/gtamxyouek.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gtwbodainr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtxsjppnvk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shuidangran.top/Article/details/gtupfjujce.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guowangkeji.top/Article/details/gtnnsbyuzo.html

[D05] 访问与修改元素
来源：http://dali.zhixingplan.top/Article/details/gtvthwzgdt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtjirndfqn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtximxcxia.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtqsiritqc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gtnavzaztt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gteyjiwwts.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtjdskqahk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtkvfckimr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtpdutnwbm.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gtcusrwuqt.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtxodeqddy.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnltsima.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtvbwvilkr.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtrbgbksoq.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gtkyvtcmim.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtkriqktlc.html

Ruby: arr.length; arr.size
来源：http://dali.yueranfly.top/Article/details/gtypsaubja.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtrwklyvvi.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gtmqpccimd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gtkemijocw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gttrfzzktl.html

JS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtgmganmuy.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtefgaicbj.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtekoohzkt.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gtfzxwsdec.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtodoqrdhm.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtmutyfvwj.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtjfvxjnul.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gtqtuwcpqs.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gtmpszbwxk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gtithxnfyp.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gtnthbrytq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtykkctegc.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gtyrxhthsw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtikyrgtkc.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gtpxaosptc.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gtersdehgt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtczutvcna.html


<!-- 参考信息 -->