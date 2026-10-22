代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtdaygvzmo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gtlaadbfil.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daxiang520.top/Article/details/gtfzlpcdit.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtpytfpntl.html

[B09] break 与 continue
来源：http://dali.nanxuanxn.top/Article/details/gtbqirtbwm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhengqikj.top/Article/details/gtbnfzlnhe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtaeyhawip.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtpuaaccdw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gthprekrou.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtkwmwzypd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nwbrower.top/Article/details/gtzxortvex.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkktquryu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtupiudobx.html

[B10] 遍历同时拿索引
来源：http://dali.hammf.cn/Article/details/gtgziztobx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuanzx.com/Article/details/gtvauoiwwb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fengsongda.top/Article/details/gtfjkgycjz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtwhfwlnfr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gtkhpwqbjt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sysykeji.top/Article/details/gtksuwbxkt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cucudq.cn/Article/details/gtjpzbwula.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.kuanghao11.cn/Article/details/gtrchbbfbe.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gtldgujcln.html

[B11] 生成数字序列 / 区间
来源：http://dali.xziqi.cn/Article/details/gtpbisxlho.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gtqobgjwpi.html

PHP:  range(0, 10, 2);
来源：http://dali.birdmap.top/Article/details/gtlwmzkwxk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cashguo.top/Article/details/gttuqgmdio.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ehwqpu.com/Article/details/gtluogajzc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtebjmozqe.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuanzhike.top/Article/details/gtkafthnsn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtnjygknwb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlswpytc.html

[B12] 跳出多层循环
来源：http://dali.cdnleiting.top/Article/details/gtgntbgwwf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aizwys.cn/Article/details/gtycbfemrx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gthuovoorh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtxicgkimq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtpqqibwxl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtoixjefcj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.smart0.xyz/Article/details/gtqrdupgmp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yanxiufei.cn/Article/details/gtclunqvdt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gtsjwhefrj.html

[B13] 判断是否为数字
来源：http://dali.chenlongwang.top/Article/details/gtwhrqqmpd.html

Py:   isinstance(x, (int, float))
来源：http://dali.hysaishi.cn/Article/details/gtlenfblvj.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gtqielaiis.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gtmpskrnvj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtqucfresk.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gthejyzqma.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gtkdckqlqa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yanxiufei.cn/Article/details/gtlcxwtdsd.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gtgzyfcffv.html

[B14] 判断值是否在集合内
来源：http://dali.hammf.cn/Article/details/gtkeefltas.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258.top/Article/details/gttadunira.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.quarkkingdee.top/Article/details/gtooqqukfr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtqdickunk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gtcvcrqqch.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pycfn.com/Article/details/gtrrfzynhz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gotoacloud.top/Article/details/gtekptvvvs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtyysgpvhm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gtgaextvqf.html

[B15] 布尔运算与取反
来源：http://dali.yueranfly.top/Article/details/gthziurqow.html

Py:   a and b or not c
来源：http://dali.aibaodan.cn/Article/details/gtkbzshrcl.html

PHP:  $a && $b || !$c
来源：http://dali.quarkkingdee.top/Article/details/gtddzxrxex.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgiputru.html

TS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtscvotbyi.html

Java: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gteuolaqhr.html

Go:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtdabbzehr.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtjsfitcsp.html

C#:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtqertijcy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.meibo888.top/Article/details/gtxqdiwyyy.html

Py:   if not data: return
来源：http://dali.jiagoushi.top/Article/details/gtgwopzlrh.html

PHP:  if (!$data) { return; }
来源：http://dali.pycfn.com/Article/details/gtfijqzqol.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtjmafqkbh.html

TS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtytrrgpyk.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtjztwmzct.html

Go:   if data == nil { return }
来源：http://dali.quarkkingdee.top/Article/details/gtcyeltjiv.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gtudmbetkj.html

C#:   if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtwtwqeofe.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtilabliaw.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtwcgvnbti.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsbmivkbp.html

[C01] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtlaodfnrj.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gtouwghemc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtbtfrxtli.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtinvvtdug.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtniybaxps.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gthniwygvn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cdnleiting.top/Article/details/gtjskdygwr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxinkj.top/Article/details/gtiviinsbo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrnbxqidb.html

[C02] 默认参数
来源：http://dali.cucudq.cn/Article/details/gtsvglvfpr.html

Py:   def greet(name="World"): return name
来源：http://dali.0kj1m.cn/Article/details/gtrdmvoruh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.quarkkingdee.top/Article/details/gtssddikoc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtjygcejcs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtfbcklgif.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gtogdbgcby.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gtyytxwuwh.html

Ruby: def greet(name = "World") = name
来源：http://dali.meibo888.top/Article/details/gtxgweenbz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yongpay.top/Article/details/gtyplcbvby.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gttwtxggxx.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfnujgqq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gtmcrrxiqt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gthreyussw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtnedfchjm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gtmjlfovzr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gtzvmqjzuo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jianghu66.top/Article/details/gtolxdcchb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shuidangran.top/Article/details/gtfmshslco.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gtlllmmqjc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gtzmfittls.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gtbwdyjhnl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtlroklghi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtqcyzklma.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gtznxsvnqa.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenzaomai.com/Article/details/gtdcnugmsl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtuibvhokp.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovowdyeo.html

[C05] 返回多个值
来源：http://dali.yuxming.cn/Article/details/gtqhqrbgje.html

Py:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtkictzzhj.html

PHP:  return [$a, $b];
来源：http://dali.zhoulong.xyz/Article/details/gteilaupjc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gttrxgzkas.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtjgesafjm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jlsjyb.cn/Article/details/gthsjqagxy.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtbyndihtf.html

Ruby: return a, b
来源：http://dali.yj20258888.top/Article/details/gtihxhhewz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gtuzgasyro.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gteqorbeuj.html

Py:   square = lambda x: x * x
来源：http://dali.zhengqikj.top/Article/details/gtmalsupbu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuanzx.com/Article/details/gtrhzjvuyi.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtcbcyzwno.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtzibqpmxa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yangfankeji.com/Article/details/gtdfuznexx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtyrnbsgku.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gtaudjsvgy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtvkcypcbs.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gtisviroii.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtyewmncxg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gtocudxnab.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gtftoxsyen.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gtesvxbsqm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gtbzmihhbr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gtwnotfvye.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtlfytdozv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gtxctpeixe.html

[C08] 闭包
来源：http://dali.hysaishi.cn/Article/details/gtlxulmpxe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.9152youxi.cn/Article/details/gtrfhghaua.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gtcpbfgivq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtruwnniyb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtjnnszgto.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aibaodan.cn/Article/details/gtcheiveup.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gtztmlefbe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guowangkeji.top/Article/details/gtulhjrvqa.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtynbhpcwu.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gthxrkqxxz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtbikreghu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsqdhtexm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtoraroxdz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtmbfbbgzc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hammf.cn/Article/details/gtjsqkmdzj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtjzuclsuu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtfhoblqvy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gttzbpncyz.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtxpirbahc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zycfv.cn/Article/details/gtamrfdzne.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtegqusgaf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gtlgxybppz.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodrcqlmi.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtooeunpda.html

Go:   花括号块级作用域
来源：http://dali.shuidangran.top/Article/details/gtscmaogsi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gtpogxllnw.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gtvkevxjfl.html

[C11] 模块导入与导出
来源：http://dali.redwolf501.top/Article/details/gtuxezwbvy.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gtanglkukx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gzhubu.top/Article/details/gtescmsqgv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gtphwjlqqm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gtnufkrskq.html

Java: import java.util.List;
来源：http://dali.jinqigufen.top/Article/details/gtvzzziijs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gtoqhsfzlw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gtbmcggwze.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gtmehosalt.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gtpcoyujly.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gtbisinxrq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgufenzy.top/Article/details/gtzgadmqhu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtcgavknls.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtqmrwhopf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gtlqdrscky.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gtkdsdwmzr.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gtyyvzknze.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gtefmplvsn.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gtjtuwrnqt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ybcxt.top/Article/details/gtdwafsaod.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtuzagytnf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtzdexdrgw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtntxezahn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtynpnijoa.html

Go:   func add(a, b int) int
来源：http://dali.zhengqikj.top/Article/details/gtaauybqpn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gtkbjjvidg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.bjfxy.top/Article/details/gthajqxdbe.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gtztigugbq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gtgvfdkxqq.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtbqxtqdqv.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtneodefjz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteemwkybq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.smart0.xyz/Article/details/gtkgrrphwa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gtsgyvdtsa.html

Ruby: # 无泛型
来源：http://dali.wangdashe.top/Article/details/gtmrxryqbh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gtrzobedyi.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtevadzupl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gthzusjlsh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gtfyyxqbkq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtvxaadxcz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gtvjtoecan.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gtxfqikaei.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtfwixtqps.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gtbkbimyme.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytvguxka.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtnjtjygqi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ivvv.top/Article/details/gtculrsrst.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gtquepvbum.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gtzmcxgamj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gtshxtjxqw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gtzcufkyca.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigufen.top/Article/details/gtjxraqghm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.havefunace.top/Article/details/gtsmvixbuf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gtxovysjah.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfnfrzwxq.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gtjyzvteys.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtuvqvkhzv.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtbpllksjx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gtotllyplo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gtjoulwktg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtzwgsorfi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gtxqnvnkzj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gtvukuugwo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtlxenqdou.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzogbkslk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.vqdsnc.cn/Article/details/gtzkcghzev.html

[D02] 追加元素到末尾
来源：http://dali.jyoumei.cn/Article/details/gtahgqgnqj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtqesueuut.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gticiddpnz.html

JS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtwvxgsljh.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtjzebowgg.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtbxjyznbz.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gtimfxwesc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuetiantiany.cn/Article/details/gtwwpjphda.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gtqfffwkqk.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtrawhyqax.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtajiyngeg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ppjwa.cn/Article/details/gtyrnpxucx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxuanxn.top/Article/details/gtonhoodsj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtqupzhivu.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtpjnjygcn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daria6918.cn/Article/details/gtoqzrwixv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyyjwphx.html

C#:   list.Insert(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtemkgfgde.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gtqaerbwne.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtskvqjsmg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtkzfaxqey.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.smart0.xyz/Article/details/gtivsbpvmi.html

TS:   arr.splice(0, 1);
来源：http://dali.sufxvd.cn/Article/details/gtgbkdghbw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gtjtdzggng.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cqqwz.cn/Article/details/gtdhdtczkw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtcoymqglu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gtkyfdisqx.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gtzjluwmkk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtocdhypue.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gteezquogk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtzaefeatq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gtdsxumaed.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgufenzy.top/Article/details/gtrihqwckz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtctidnnrz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzenabwg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtqyihqsge.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtacwcwsdm.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtznlmcqfi.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtwvoiknhg.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfrphzlk.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtbrsecqoe.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gtseeghkrg.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtzqflrnml.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtbilziqqg.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gtgsygmvva.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtsfdrpgjx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gtaprpzrkd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtpyxompnh.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtkxptxmrv.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtzyhaycht.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtujcndcti.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gtkwkxalfy.html

Ruby: arr[1, 3]
来源：http://dali.daria6918.cn/Article/details/gtwbvphjnx.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gtkjfnqqpq.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtflyulhry.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtcgrclofh.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gtnykyxhsg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jiagoushi.top/Article/details/gtkuatcgep.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gtkgccesav.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtobgmyihl.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gthvmuczte.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gtoysqdwvn.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gttmnimtps.html

[D09] 排序（升序）
来源：http://dali.ehwqpu.com/Article/details/gthmuxuvyc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtjhqctwup.html


<!-- 参考信息 -->