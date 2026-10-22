代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtzafugysg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtdmpfqnkm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenjidiqi.icu/Article/details/gtzzxtcnfo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtlfavmhwq.html

[B09] break 与 continue
来源：http://dali.hammf.cn/Article/details/gtkedojeng.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigufen.top/Article/details/gtydwcslaj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtvyqkttdv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtbnnrylxf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtryjkgzgm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtnktqijxj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtmokqjnsz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkmafvfr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtfmkirora.html

[B10] 遍历同时拿索引
来源：http://dali.fengsongda.top/Article/details/gtoudzsumn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shangyingyoupin.top/Article/details/gthjhsnmvu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zdqjudy.top/Article/details/gtjjhfhmqn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtikzdzpkd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gthpmprlql.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tianlin.xyz/Article/details/gtfyyfktjh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gtxgxzufvu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gtsrnqouls.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guannengcc.top/Article/details/gtbvkzwclw.html

[B11] 生成数字序列 / 区间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjikfbzuk.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gthvzpzzaa.html

PHP:  range(0, 10, 2);
来源：http://dali.iojbl.cn/Article/details/gtudljpgfx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gtjocbxbhl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gteogetzhs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gtetelutxb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dashuyun.cn/Article/details/gtmnlanvtn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gogol.net.cn/Article/details/gtjqapiozs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtagcyiuil.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gtydnpwrta.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gtpohjidxm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.smart0.xyz/Article/details/gtjjktvfas.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthneyyevy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtoakfrcwb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtwyrnfetv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jyoumei.cn/Article/details/gtbuzltehv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dashuyun.cn/Article/details/gtqoaiacfq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guannengcc.top/Article/details/gtgnbsorig.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gttezrxzhg.html

Py:   isinstance(x, (int, float))
来源：http://dali.dashuyun.cn/Article/details/gtrwjmunwr.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gthlgcyysy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtubhuvbpv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtlrddsylz.html

Java: x instanceof Number
来源：http://dali.redwolf501.top/Article/details/gtvugxthej.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yongpay.top/Article/details/gtapsjdxyl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gtxrqupvox.html

C#:   x is int or double or decimal
来源：http://dali.jiagoushi.top/Article/details/gtftnrtjtn.html

[B14] 判断值是否在集合内
来源：http://dali.wangdashe.top/Article/details/gtlmogekgf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigufen.top/Article/details/gtpguerqhw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryomxfku.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtgxezfntf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtvjclpmcq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tian-w.cn/Article/details/gtgbeghkau.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gtgqsghpgh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gtdsbmcogb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtxjitzgla.html

[B15] 布尔运算与取反
来源：http://dali.yvedp.cn/Article/details/gtbkdkukxa.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gtpfervdaq.html

PHP:  $a && $b || !$c
来源：http://dali.kuanghao11.cn/Article/details/gtjoaoxbnz.html

JS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gterqquywo.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtgdtqrjci.html

Java: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdagfhks.html

Go:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtsgkidnvx.html

Ruby: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gteomdkitr.html

C#:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtbfzuutgv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gtyqkldomu.html

Py:   if not data: return
来源：http://dali.zhongyouzk.top/Article/details/gtkrfzkzng.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gtjqhfqehc.html

JS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gttczuhkep.html

TS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtceqgrpkt.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtmpksjkio.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gttmuvfgpj.html

Ruby: return if data.nil?
来源：http://dali.hysaishi.cn/Article/details/gtsjdgsdlp.html

C#:   if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtplbgqrgn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtptmgxcsv.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gthjoffcri.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbgauyrqh.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtnspeabgz.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gtolbjxjhv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtoklqcaws.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtoljbxvtj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtgsxjszyb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtgomvppos.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj202588.top/Article/details/gtuujorxzt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.snrcjt.cn/Article/details/gtficzmuqg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtskapvtmj.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gtlvlowmva.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gtmalkhhun.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtkbjkszoc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtfrpujtub.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtklgioder.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gtppeikoxf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zdqjudy.top/Article/details/gtvuxrwzew.html

Ruby: def greet(name = "World") = name
来源：http://dali.xziqi.cn/Article/details/gtpfnhsrnx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigufen.top/Article/details/gtxfuqsjer.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gtrrkxyxqy.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gtxfefwtls.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nwbrower.top/Article/details/gtsxghlpmo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtgtcblldw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtzxnxvpga.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gtmupkxbum.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gtsxzbvesk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gtsfbfgena.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhongyouzk.top/Article/details/gtukqaknpn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuxming.cn/Article/details/gttldekawm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrncmreqd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gtlftwbwty.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtlfybllsb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gtjhauhmfw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258888.top/Article/details/gtszoclxbt.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gtwvbaeeei.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtiamhhhat.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gthzerorym.html

[C05] 返回多个值
来源：http://dali.sxryk.cn/Article/details/gtslxcopyj.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gtedonikyq.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gtxxgcmaic.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258.top/Article/details/gtqulclavi.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtyoflzjua.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gtypjmwfhz.html

Go:   return a, b
来源：http://dali.yueranfly.top/Article/details/gtczzozpsz.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtrfteudcz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gtaganuouk.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtkkmuehjv.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gtgilmltzu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gtfmivfmry.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtcynyhfoo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtugzyhlbk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtxzwiwpys.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yonumen.top/Article/details/gtkwrrgwsd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daria6918.cn/Article/details/gtiiddllvy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtqextbxem.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gtgjshltjq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gthnkpgcku.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtyzoguhcz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.0kj1m.cn/Article/details/gtfpxjopap.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkiojehq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gtugtxnmjj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.9152youxi.cn/Article/details/gtzbsxxurj.html

Ruby: arr.map(&:upcase)
来源：http://dali.c1oappe.top/Article/details/gtxywyeqcm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhiwuduotai.top/Article/details/gtsoksnepa.html

[C08] 闭包
来源：http://dali.aibaodan.cn/Article/details/gtsagmvsef.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gtserydzjp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gtbffcixbh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtxtschowh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtdeprllrg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gtiqocrimo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtczkuoykk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gtafizieqw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtnvgqsuey.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gtzjanfeha.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtvdcbgyhr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gtsfbzwrot.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gteytbwwfe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gtvsplecih.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtkyrfmyou.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gtbymdoguz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gtoegpkebx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gtpdigplob.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtahutpkzm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gaohongyu789.top/Article/details/gtgnecezil.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.9152youxi.cn/Article/details/gtfmefpvzk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aibaodan.cn/Article/details/gtksceciih.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gtwjxtnfvc.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gtgomvizqc.html

Go:   花括号块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtoeretlqm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gtzyhmncrr.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtycqovzzl.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gtwovpltjf.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gtoyfpiadd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuxming.cn/Article/details/gtqgwqzsds.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtodkekozw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yonumen.top/Article/details/gteblppefa.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gtzbspuano.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gtvltscthx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigufen.top/Article/details/gtjhxugays.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqpcqoxq.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gtwvdssywe.html

Py:   (lambda: print("run"))()
来源：http://dali.shangyingyoupin.top/Article/details/gtyphuqrwp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gtuisoixfy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtbpncxmts.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtprwmbuxp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.snrcjt.cn/Article/details/gtfbrfbhpn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cucudq.cn/Article/details/gtvkxrbetx.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gtvlaipweb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gteyuyttwk.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifmgdmwv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gtttozqjof.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtyejbgxas.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gtofjbegdf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtdgqbtwst.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtyharfvuu.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gtwkznggjx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gtsvyrorzx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hywenlv.cn/Article/details/gtbbmmhmos.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gtrebjzhgb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gtlbubyoco.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gtggpetaxp.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtfxblhwbp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvrhgkeuh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuxming.cn/Article/details/gtmbulubqp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gtzcfpgldv.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtyifscydw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gthcsygxxo.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gtowxtilrd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gtffikvnbe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gtlzbyzqoo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtnryrdtzz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gtbvlxfaun.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtwhhinfci.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtvehdsxdp.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gtwkihnzme.html

C#:   var (a, b) = pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnojdkbu.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gtmdnyylyg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtlikyqogf.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gtutzdzdkk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gzhubu.top/Article/details/gtxlcfwrkq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.feifeiyinyue.top/Article/details/gtfjkhljdm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gtuldubhac.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gtherpmjns.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gtvvxfhztr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gtwlnbpjbq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtednmxzcc.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gtzuglklpn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrifbfyub.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtmxthxplf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gtebvfomtx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtzfefnupx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aibaodan.cn/Article/details/gtddrnstju.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtceorvyam.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cashguo.top/Article/details/gtsdkezkvl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gtglscedvw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gtbotkwxea.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.andypj.xyz/Article/details/gtjepwhley.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtbthqqjwn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gtjhchynsr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gtnsjhickd.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtiuiiiwbh.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtprxjptim.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtmbuuvjlz.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gtrqaofgqm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gtqrjfyhhp.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gtvpbdjrmg.html

[D03] 在指定位置插入元素
来源：http://dali.dianchejie.cn/Article/details/gtsvbwjpyg.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gthjblwsib.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhixingplan.top/Article/details/gttlbxuuwo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jyoumei.cn/Article/details/gtywghfgnd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtevnrpvvz.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtzrfrtblb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtkmnsrsfh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtfzxvvgih.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtddzdlrko.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gthqjznpkr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gtrgatcstz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtnapsthgf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gtnevapuve.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gtrjwkslwc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtmiqiqkua.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gtojjhfkdm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gtwpwebymc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtuhehraxx.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gtgfoqqfsn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtontrjydv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gthnllhavy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtiphthyeq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtahksxies.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gttseqniwo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtycwsnttk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtnypivens.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvogyjmw.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtnrqdubfs.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtqbhjmmew.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gtmceqxnxc.html

JS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtscbqdyds.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtkoyvfupc.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gtvysjmgnq.html

Go:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtksiairic.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtpugafdfa.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gtwjatyxvi.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gtcudotxuf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtphnsyxbz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtjnmtshte.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtyboibvpk.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtmaqifpxp.html

Java: list.subList(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtszhmvngd.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gtqkgtzxav.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gthzxferso.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtbreldyez.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gtmxusqabb.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gtfpdeeibm.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gtvihoprda.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gtoxyweryl.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gthfqrsjsp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtszylsnlg.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gtqkkfkysa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gthzdzidpn.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gthfnyagnt.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gtvtopirji.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gthybgnwee.html


<!-- 参考信息 -->