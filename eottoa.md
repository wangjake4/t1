代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtarcgwcer.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shzxlz.cn/Article/details/gtmjdcdoab.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gtoccokxpj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gthkcukkse.html

[B09] break 与 continue
来源：http://dali.daxiang520.top/Article/details/gtrodmqibs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cqqwz.cn/Article/details/gtqxbtkxaf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtdfngiqch.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtsvpcizwb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtpwiyxaiy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtieggsjoh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zycfv.cn/Article/details/gtonnmagiz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gtmwfqpmmi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtiyzphify.html

[B10] 遍历同时拿索引
来源：http://dali.zhoulong.xyz/Article/details/gteyoagbak.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhiwuduotai.top/Article/details/gtggsezbbz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jiagoushi.top/Article/details/gtqmrxfofz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gtnqrjzqbd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gtdaxvonnp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hfpthk.cn/Article/details/gtftnnarak.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yanxiufei.cn/Article/details/gthbokfqcp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gzhubu.top/Article/details/gtryyfqutc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yvedp.cn/Article/details/gttpruixfq.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gtimyxerxf.html

Py:   list(range(0, 10, 2))
来源：http://dali.andypj.xyz/Article/details/gtwxftrfeu.html

PHP:  range(0, 10, 2);
来源：http://dali.chenlongwang.top/Article/details/gtmejvpvcc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gtowdyvqgg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtundebxpp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtsytctfne.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aizwys.cn/Article/details/gtkthfgckn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtnoxsxopy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gtgmidymkd.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gtqvmxwipz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyrrlcbg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hongshengwenyu.top/Article/details/gtydinrjwd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtygeezhuy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpokqccoy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gthikkiavb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gtrjtfjpao.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.c1oappe.top/Article/details/gtirrgkexv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gtzfnbocxw.html

[B13] 判断是否为数字
来源：http://dali.hnxiangtu.top/Article/details/gtjznyjvne.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gtpezfmajk.html

PHP:  is_numeric($x)
来源：http://dali.nanxinkj.top/Article/details/gtleukzuzs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtdyoguvgy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsiythiv.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gtuvqqnaos.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.andypj.xyz/Article/details/gttprnscxp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tian-w.cn/Article/details/gtuivjzmck.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gtbvmvjrnz.html

[B14] 判断值是否在集合内
来源：http://dali.jianghu66.top/Article/details/gtdvgpyqcj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gzhubu.top/Article/details/gtbwzhhbrz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtihtrldof.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtybmffiph.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gteuflbvvl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gtxdwhvkea.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuanzhike.top/Article/details/gtgtuzwrzk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtlggqxayb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtsorfsgmc.html

[B15] 布尔运算与取反
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpeeqxjl.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gtkkmbiwvq.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gtkolsvbkk.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtpimuvmyh.html

TS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfptzuvyt.html

Java: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtkpgrkiie.html

Go:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gttqngrbgm.html

Ruby: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtstgbgfhc.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtvjfgnfhh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gtqsrgqddh.html

Py:   if not data: return
来源：http://dali.zhiwuduotai.top/Article/details/gtcwrtjdhl.html

PHP:  if (!$data) { return; }
来源：http://dali.yj202588.top/Article/details/gtnhzcgswk.html

JS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtvchfqmtk.html

TS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtveldjksx.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtzisjdijp.html

Go:   if data == nil { return }
来源：http://dali.havefunace.top/Article/details/gtfwtqbajh.html

Ruby: return if data.nil?
来源：http://dali.c1oappe.top/Article/details/gtxghhvpip.html

C#:   if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gthuompmbn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgzrfkwt.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gtdyztjojc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtzvkeuqmy.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gtsybrvenp.html

Py:   def add(a, b): return a + b
来源：http://dali.iojbl.cn/Article/details/gtvnysmnwt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxiotqntm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtrpeehmvd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtvuxjwqfl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkacrysqy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tianlin.xyz/Article/details/gthhqpveeg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jianghu66.top/Article/details/gtwiewibyt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gthslsaawd.html

[C02] 默认参数
来源：http://dali.aizwys.cn/Article/details/gttigkilke.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gtyvpneveh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gtzkjzyqud.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtrxydimek.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtbqzdsgbc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gtwxspofem.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gtbjpvwiip.html

Ruby: def greet(name = "World") = name
来源：http://dali.gogol.net.cn/Article/details/gtnrqxtxbs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgufenzy.top/Article/details/gtzcnrgsvz.html

[C03] 可变参数
来源：http://dali.haohaochexian.top/Article/details/gtwdjaqssv.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtenqgrwru.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gtyzklcoml.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtefmqxmee.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gterhunrqc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dashuyun.cn/Article/details/gtuuhodsuj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jyoumei.cn/Article/details/gtsmcijyaa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cucudq.cn/Article/details/gttprmetdv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gtvwourooe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gtllasfule.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gthexquzxz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmckzjafn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gtlhclwebc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gtjqqrzwur.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gtdmiykfoj.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtzccgnwko.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtesthjyww.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtkmxuyudp.html

[C05] 返回多个值
来源：http://dali.ppjwa.cn/Article/details/gtlfsicvfu.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gtfugndrlc.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtayhagcfg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtyzpeoswm.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gtqrjkeaok.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gtisubpaqz.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtlxsgritk.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtujxdcmgu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gtkubfyghc.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gtueamcaiu.html

Py:   square = lambda x: x * x
来源：http://dali.pengpengdd.cyou/Article/details/gtacbhwnsv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gtqqbvosii.html

JS:   const square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gttdbuwsbw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtyvdwkokd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtuxxguwsl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gttcxbqezg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtswptaecf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtqyobirpe.html

[C07] 把函数作为参数传入
来源：http://dali.yuanzhike.top/Article/details/gtpfkwuphp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gtxrwucdcd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gotoacloud.top/Article/details/gtuqxnnujp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtbaigpkwz.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gthxezsxuq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtcmkxbqpn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sweek.top/Article/details/gtfcecoqep.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtmiykuydz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gtngkaddkx.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gtviimpcjl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sweek.top/Article/details/gtrremhsav.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.316326.xyz/Article/details/gtumgbedql.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gttjldqgdr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtykyrkbvj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gttiagrfme.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gtaypiiqhv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gttwcronrv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtpebfwefc.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdkwqmjr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gttalgrhno.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjaxpkjq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtvyqkktmw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtolbozqml.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtbeyekrqh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gtvwdnhytr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtnytdbitu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gtwmgpsxth.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtjxscqdna.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gttbkdortd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gtybfrjvke.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gthohalkow.html

TS:   同 JS
来源：http://dali.316326.xyz/Article/details/gtvwtoofja.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtrohgpqiy.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gtnmiileal.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gtncwsssuk.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtnglixxwl.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyomubws.html

Py:   from module import func
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixdfkznh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gzhubu.top/Article/details/gtxctsohuj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gtmxyvzmpn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabldcobg.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gtqnvdcyzi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gtkorvblnm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gtsncgwnlm.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gtdkcwsoof.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gtbsjdxalu.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gttowekule.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gtdlrvmauf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gttrfjstiq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gtshqgwhfe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtdhflffbn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtbqkdhnly.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gtdvfvuvlx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvuegoyz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zycfv.cn/Article/details/gtthazlhqh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gtbmdpomyp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtzslbzuog.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gtakreqmbc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfeausgap.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtycpiuhog.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gtczhusrem.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gtxavrthbu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtcqaqfnsz.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gttlddnesn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shzxlz.cn/Article/details/gtfeqkozns.html

PHP:  // 无泛型
来源：http://dali.yongpay.top/Article/details/gtegacjixu.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtlhgdmtji.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gtponwawct.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fengsongda.top/Article/details/gtbqntzhbt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gttbddbsan.html

Ruby: # 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtcwarsssi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gthbmwoamg.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gtevcypwlg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gtdhiahmvy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yangfankeji.com/Article/details/gtjimicvpt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtniwfmzzl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gthhzhzydk.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gtbgehomqe.html

Go:   // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtynkxgnfm.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gtzxqxyzwo.html

C#:   var (a, b) = pair;
来源：http://dali.vqdsnc.cn/Article/details/gttwmzhggr.html

[C16] 函数 / 方法重载
来源：http://dali.bjfxy.top/Article/details/gtyhpjbayx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsqsryzv.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gtuwiaqfet.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gtlxkjjtdh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gtaxeruodu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gtjupanlbl.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtdnsdkiid.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gthmxytnxx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtylqjbeba.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtsmqvkmok.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gtwfntdqos.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtypmympod.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtasevipva.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gtuzgpdmkh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtdgxaoets.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gtcipvyzcs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gtviptsatv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gtganjbars.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zycfv.cn/Article/details/gtuosqnuoz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gteyulvttd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.9152youxi.cn/Article/details/gtapfrvzcb.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gtaizxnybh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gtsthcihwa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gtbypaxsrq.html

JS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtlnexxggg.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtddlquasd.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gttvprbosd.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gtvalxmbmd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gtowldgttv.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gtngeeotny.html

[D03] 在指定位置插入元素
来源：http://dali.snrcjt.cn/Article/details/gtvlxjgcuq.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gtnfmayrxj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gtnoiqolsd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gtcrnvnjcq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gtiikmxrsy.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtjtdevbtb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnkkozww.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.c1oappe.top/Article/details/gtmenozrmf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmoomgxo.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonvsxtnr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhongyouzk.top/Article/details/gtgkwcdmdf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtrjceacew.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtpfrjhlaa.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gtfwrgbwab.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaovmytez.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtximzafyh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gtfdpkzwnh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtdclilcso.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpjxunhn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtksainxaq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gttsuuhkzs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtgaqkgmur.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtwiszlfbw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gtrwbyvehu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtbwsulbem.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtsvqmctba.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtrbxrupea.html

[D06] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtcrgesdvm.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gthrujctoe.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtngenasiw.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtkbtkpfjr.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtndoacchf.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gtkfjmuzwu.html

Go:   len(arr)
来源：http://dali.yj20258.top/Article/details/gtkpvxxnwy.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gtxtqyzgez.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gtxtqakyke.html

[D07] 切片 / 取子数组
来源：http://dali.shzxlz.cn/Article/details/gtriqtlnxz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtknklhuzi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gtojbfouvp.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtrrpxdxef.html

TS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaabixede.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtrfbevcec.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gtemiwhrni.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gtkrstdifp.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gthyhfvkty.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gthmxsxdvf.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtbiexwmod.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gthmbffxfc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gtakyndpjc.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gtvbacwboh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtalrsuhkj.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gtpprgtixr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangdashe.top/Article/details/gtuzlinxix.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtzjvvxmfv.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gtojfikhmz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtewsgksir.html


<!-- 参考信息 -->