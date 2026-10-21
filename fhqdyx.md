代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdavqrayf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.aibaodan.cn/Article/details/gtlkmqkypm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahovnsyv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtuiyeozal.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gtvoukljys.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gtltovrehc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmvqxnig.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzdlyomrj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtoylumojg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtlstxmbzj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gtksgbabri.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ppjwa.cn/Article/details/gtgmupzqed.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtxjhnppxj.html

[B10] 遍历同时拿索引
来源：http://dali.yongpay.top/Article/details/gterdmwjcu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gtxybxkewg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yueranfly.top/Article/details/gtnfavprzo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.kuanghao11.cn/Article/details/gttbnjdmrd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gtmmwhrhnb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yongpay.top/Article/details/gtiqxnreeb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhengqikj.top/Article/details/gtpfzwfgtc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.mhx1999.top/Article/details/gtjhyngvuk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.9152youxi.cn/Article/details/gtgsxjqerp.html

[B11] 生成数字序列 / 区间
来源：http://dali.pycfn.com/Article/details/gtttsebvsx.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258.top/Article/details/gtwjdtzrvj.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigufen.top/Article/details/gtrqwodplo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gtbredljtg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gthwqvcuhh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258.top/Article/details/gtsgmekncx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhiwuduotai.top/Article/details/gtahhmgrth.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangdashe.top/Article/details/gtpplwitre.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtydqdwtce.html

[B12] 跳出多层循环
来源：http://dali.mhx1999.top/Article/details/gtsgjjycug.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtvjtzzygy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehincpoe.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gttpubicak.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtogquqwxs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gttrchofjj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj202588.top/Article/details/gtqkfpkhce.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangshuangyany.cn/Article/details/gtaemgukpd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gtkmsavkkc.html

[B13] 判断是否为数字
来源：http://dali.zhongyouzk.top/Article/details/gtnwrgmccx.html

Py:   isinstance(x, (int, float))
来源：http://dali.fengsongda.top/Article/details/gtetydhnqh.html

PHP:  is_numeric($x)
来源：http://dali.redwolf501.top/Article/details/gthblxbghl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gtezkedvkp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtvtihgtye.html

Java: x instanceof Number
来源：http://dali.dashuyun.cn/Article/details/gtukmbrmxs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hongshengwenyu.top/Article/details/gtuhqbymux.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhmfdybg.html

C#:   x is int or double or decimal
来源：http://dali.xylfe.cn/Article/details/gtjgzoefjj.html

[B14] 判断值是否在集合内
来源：http://dali.tianlin.xyz/Article/details/gtfrtqeuga.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daria6918.cn/Article/details/gtwfsckuwa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guannengcc.top/Article/details/gtptbaatpg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtjrjzyasy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gteqxzhyoh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jianghu66.top/Article/details/gtbpdtgsqa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jyoumei.cn/Article/details/gthaagyacs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtygjklofu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gthhtxdahr.html

[B15] 布尔运算与取反
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbkxphwp.html

Py:   a and b or not c
来源：http://dali.zhiwuduotai.top/Article/details/gtjzxucxda.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gtjtplnict.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtyfiyaydi.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtuplpcfql.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtrgrwzqge.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtstkxsrml.html

Ruby: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtrucmumeq.html

C#:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gteadrslpp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258.top/Article/details/gtnitczkoi.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtmvvphxvf.html

PHP:  if (!$data) { return; }
来源：http://dali.cdnleiting.top/Article/details/gtejrldnbt.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtvclwjuax.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gttsrionsy.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtmlskexmy.html

Go:   if data == nil { return }
来源：http://dali.kuanghao11.cn/Article/details/gtswxzjfbf.html

Ruby: return if data.nil?
来源：http://dali.fengsongda.top/Article/details/gtjergbbon.html

C#:   if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtjruuwiih.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbwrlzvhe.html

C. 函数与作用域
来源：http://dali.gaohongyu789.top/Article/details/gtdgnaehsm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjlfuztvh.html

[C01] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtzixqyqyj.html

Py:   def add(a, b): return a + b
来源：http://dali.jianghu66.top/Article/details/gtnqofyeat.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtndrfgczc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtewsixbxl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtxdvmslxc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtcimrotws.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtdblrnjsv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tianlin.xyz/Article/details/gtikxsgfgd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtccgsmsrp.html

[C02] 默认参数
来源：http://dali.xinyue.icu/Article/details/gtsthpvbuk.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gtdxgdxarv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtncyemafp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtumtyzefv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluavbuic.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigufen.top/Article/details/gtvwrthlra.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gtvxxlnoaw.html

Ruby: def greet(name = "World") = name
来源：http://dali.yanxiufei.cn/Article/details/gthrcxsxlt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hammf.cn/Article/details/gtrhegkkae.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gtlsmdsqed.html

Py:   def total(*args): return sum(args)
来源：http://dali.yongpay.top/Article/details/gtufkwkkne.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gtlpnzhiya.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtjzessdrb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtpmxwhpqh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtiyltagpk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yvedp.cn/Article/details/gtacrhfkfk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gtxbhbbxkl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gotoacloud.top/Article/details/gtbvgzyzbz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.kuanghao11.cn/Article/details/gtojbdwhag.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.iojbl.cn/Article/details/gtxkpzsgov.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zdqjudy.top/Article/details/gtxtkvzact.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyozizie.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daxiang520.top/Article/details/gtbkoqyqyr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sxryk.cn/Article/details/gthmpkfcwc.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gtrgplknox.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtirsncifb.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtcwnfiegg.html

[C05] 返回多个值
来源：http://dali.ppjwa.cn/Article/details/gtpfcqdghk.html

Py:   return a, b
来源：http://dali.ivvv.top/Article/details/gtlvnhbxsl.html

PHP:  return [$a, $b];
来源：http://dali.yj20258.top/Article/details/gtupsdtkwl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtuqiyjenq.html

TS:   return { a, b };
来源：http://dali.xuanzx.com/Article/details/gttchozqve.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenzaomai.com/Article/details/gtjlobqity.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gthqbmjzgk.html

Ruby: return a, b
来源：http://dali.wangdashe.top/Article/details/gtzgxmshvh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gtefnkdbbn.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gtcomgjakh.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gtplxcwlgv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gtijtellxb.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtsrmtwzfm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtzeokunvi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtvaharbdh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtldismqrl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gtgtxuhpxt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtesuwremk.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gtvsdrlged.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gtymujoike.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gtrfmikako.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.haohaochexian.top/Article/details/gtxghwvvlh.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gtongqyyob.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gtpppjfqlp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gtctvyvfta.html

Ruby: arr.map(&:upcase)
来源：http://dali.fengsongda.top/Article/details/gtyddbhdiv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ivvv.top/Article/details/gtiyewxzyn.html

[C08] 闭包
来源：http://dali.yueranfly.top/Article/details/gtbmifkgqg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gtndzcysez.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daxiang520.top/Article/details/gtrvbgvmpk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtpnuxumqg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkpwzsbpk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuetiantiany.cn/Article/details/gtzzyqambj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gtigouzsrd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yueranfly.top/Article/details/gttioxcmeo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtkjltskhd.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gtetgrhdgr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtzmrlxgkb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgaehytiw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtlvylcfim.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvsopyeg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtomnpakat.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gtmbdwlidd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gtjaoivijd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtpoddtrrl.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gtehyttsnb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gtuqeycdat.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gtpexbscrs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gtvpstdefg.html

TS:   同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtxmiqaxpi.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtujospdrx.html

Go:   花括号块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtflohjxlw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gtewpsetwp.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtojrjjqtp.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gtslcldryi.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gtbzdfvtyx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gtqxcbqzsy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gtineiwulc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtpwvspujy.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gtwobetmqz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gtjqfvdfpu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gtpohtcict.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gthxylnolm.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gtxxkhrect.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtpwgnrgoy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gtsjcxmcmt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtcvlryczr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtfomnfeei.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gtxqkdrnuc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgfzy.top/Article/details/gtvqbdsatc.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gtcinfrmbo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gtovrpsxzg.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtqbiwxqgx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtysgtxmcn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtugozhqim.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhengqikj.top/Article/details/gtewkwnzjv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtqkzbaowu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtyoveslhm.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gtucfotjke.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gtmirgmzzc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenzaomai.com/Article/details/gtlvzigeix.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gtpzmkfhad.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gtyspaqtbu.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtsctxorfo.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtuqpojndh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gthaookuwx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cheryme.top/Article/details/gtglovlefo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gtlqdmfkjw.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtrudenbrp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gtjuukxxkl.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gtbpugkytj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtsyaapnbj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guannengcc.top/Article/details/gtjsdtsnmj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtkshnpham.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ppjwa.cn/Article/details/gtenuzlefu.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtpqvexlnk.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gttiserrsc.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gtwpfzxqfn.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gtzuivkzah.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtwztmzfvy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtkocsytbt.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gtiesqmald.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gtoyozmcek.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gtfvpfoycn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ehwqpu.com/Article/details/gtoxtgctay.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gtoxaykbbz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.vqdsnc.cn/Article/details/gtjhvsxsob.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtoudnhguz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnlsyhqxt.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gthjpymkic.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkvrwuwmx.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gteygfddrr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gtzdmhgtip.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258.top/Article/details/gthzqzztmx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gtqnkohtfc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pycfn.com/Article/details/gtkccmzzjz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtwtvokejr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pengpengdd.cyou/Article/details/gtqfyqmcew.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gthvqylazv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nwbrower.top/Article/details/gtwkmiueel.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtsyyqoddh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonqzlsgv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtsokjmdvv.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gttglboauw.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtbmtjkhfe.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gtvycuvtla.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gttmrpmgbe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gtyzeciljv.html

C#:   list.Add(4);
来源：http://dali.cheryme.top/Article/details/gtevlgofag.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gtbsxamnvq.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtiruozhqn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gtjdzzsatc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sxryk.cn/Article/details/gtytwuvuwa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfyndnny.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtnvbsbowy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtwnwmgmbr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gtyujelbfw.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtwhphxykb.html

[D04] 删除元素
来源：http://dali.yonumen.top/Article/details/gtisdxvrmv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gtlfigascw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtfnbjzqmo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gtjlvhfzge.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gteqskollu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gtpbgzmazu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gtcwmjxzzw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gotoacloud.top/Article/details/gtyfucgntm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gtasatuyqr.html

[D05] 访问与修改元素
来源：http://dali.wangdashe.top/Article/details/gtpcwdhwby.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtxuwzoadz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyhajcdb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gttaavmdwj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtipumskvk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gtytstdyuz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtjygaawmr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtdtprvbdb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtqwijnufy.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtrfrvhgpb.html

Py:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gticgvyncc.html

PHP:  count($arr);
来源：http://dali.cheryme.top/Article/details/gtdynkevmb.html

JS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtymrbcwyt.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtvdxjnewn.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdusbmdpm.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtbigmtpfy.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gtxmzkefsq.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyacjterk.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gtfvysyvab.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fengsongda.top/Article/details/gtjbbwrhjp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gtomoctoys.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtjdjgrwnv.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtzzplkxgw.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gtldjycmkh.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtglvvmbnh.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtbeuvrbjk.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gtmzeusxzv.html

[D08] 合并两个数组
来源：http://dali.kuanghao11.cn/Article/details/gtdozpmoux.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtyumqkzrw.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiiozljfd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gtdrawmsrd.html

TS:   [...a, ...b];
来源：http://dali.sweek.top/Article/details/gthpqqurrv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sysykeji.top/Article/details/gtgbikqdhz.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gtupcteitg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gtxomwmadp.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gtuvtarhhg.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gtthipqxwp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtjlmwsdds.html


<!-- 参考信息 -->