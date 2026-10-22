代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gtfulwbvjm.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gtpftlcklq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hammf.cn/Article/details/gtkjbwsmvn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.316326.xyz/Article/details/gtzjishnol.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoblmobue.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gtswdqrien.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gteitntdra.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jyoumei.cn/Article/details/gtgyrpkbrx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cashguo.top/Article/details/gtmitqabmg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gotoacloud.top/Article/details/gturxmnszi.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gtmwknmlos.html

Py:   while i < 10: i += 1
来源：http://dali.xuetiantiany.cn/Article/details/gtnulzljse.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.0kj1m.cn/Article/details/gttfmyttyt.html

JS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtacolayba.html

TS:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtwdntiboy.html

Java: while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtctfcjiim.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtontvcqax.html

Ruby: while i < 10; i += 1; end
来源：http://dali.mhx1999.top/Article/details/gtfosgifey.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpyxvgnzu.html

[B08] do-while（至少执行一次）
来源：http://dali.gzhubu.top/Article/details/gtszezeowy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yanxiufei.cn/Article/details/gtzlcdwrui.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtpnbcxbky.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtyeeavpda.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtouzzntcf.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtaweawlcs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sxryk.cn/Article/details/gtguuvwhcg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhongyouzk.top/Article/details/gtqhgkrisq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtvmtsdmpp.html

[B09] break 与 continue
来源：http://dali.hammf.cn/Article/details/gthbbbkixs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aibaodan.cn/Article/details/gtgekhqudm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtegwbebnc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtyjjnuqnb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtwftbbeau.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtrbkqhpog.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtfstvhndf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dashuyun.cn/Article/details/gthsuqeuea.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzsxvmlv.html

[B10] 遍历同时拿索引
来源：http://dali.xuanzx.com/Article/details/gtqukdvbkl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cdnleiting.top/Article/details/gteuixvecs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ivvv.top/Article/details/gtxsasizrc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.bjfxy.top/Article/details/gtplpieojl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.snrcjt.cn/Article/details/gttdpkyvep.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.mhx1999.top/Article/details/gtrphwtzgs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daria6918.cn/Article/details/gtftcvxlou.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tanke756.top/Article/details/gtrxtgzfdw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhoulong.xyz/Article/details/gtwojqhrjj.html

[B11] 生成数字序列 / 区间
来源：http://dali.meibo888.top/Article/details/gtzbkfmwts.html

Py:   list(range(0, 10, 2))
来源：http://dali.pycfn.com/Article/details/gtbqcfltog.html

PHP:  range(0, 10, 2);
来源：http://dali.jyoumei.cn/Article/details/gtuneklgts.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gtgyegfdtf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gttfphxtkf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gtltbpcwij.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gtjgvgxxtg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zdqjudy.top/Article/details/gtdixuyvdq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shuidangran.top/Article/details/gtfnretprv.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gteyxojpws.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.316326.xyz/Article/details/gtdbysphyd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gthlyvbtvj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtwqytnqhw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtuologgwc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtdmcwctnx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gtncrcigey.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pycfn.com/Article/details/gtilxdkgks.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gtxukrvldu.html

[B13] 判断是否为数字
来源：http://dali.ivvv.top/Article/details/gtmpatpeir.html

Py:   isinstance(x, (int, float))
来源：http://dali.zdqjudy.top/Article/details/gtswmxoxbd.html

PHP:  is_numeric($x)
来源：http://dali.guowangkeji.top/Article/details/gtrzmohkwu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtobiltbzb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gtpfueoslw.html

Java: x instanceof Number
来源：http://dali.xuanzx.com/Article/details/gtcevyhigf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fengsongda.top/Article/details/gtzducfbso.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfopykat.html

C#:   x is int or double or decimal
来源：http://dali.aibaodan.cn/Article/details/gtlmuwnacr.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gthqgvefew.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pycfn.com/Article/details/gtzljirtmg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gtkqvcfthk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtcuffhvti.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtndzoiawc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtmlwwgcgj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gtkdfjdirv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtwensjfmt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtmnkmooly.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gtzbfdhbse.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gtxdhexfqn.html

PHP:  $a && $b || !$c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbeymscq.html

JS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gttflqowpk.html

TS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtklzndlgp.html

Java: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtkhslqzov.html

Go:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gthobamqmk.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtognssfun.html

C#:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtpeotpmbx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gthhyiytjb.html

Py:   if not data: return
来源：http://dali.hywenlv.cn/Article/details/gtbnfhbngx.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gtcllzhaxp.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtvvfzfark.html

TS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtqehazblh.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtexjdfmiw.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcabatfys.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gtdwuopkqh.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsbvypzc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtpruoypne.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gtbspghqqa.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtkausolrr.html

[C01] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtnltfqdzc.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gtyfjojiis.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtnbvgqqnj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtyfiznnvk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtyaquafmq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtxigpzzip.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gtdrnbfscq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtkdtwzxad.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtuecvpiia.html

[C02] 默认参数
来源：http://dali.ehwqpu.com/Article/details/gttqpbzrxr.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtyplefcbf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gtbivgpwrb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtvysfolfo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtdnrbbnel.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shuidangran.top/Article/details/gtiwfalvrf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cheryme.top/Article/details/gtuqnxlajc.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gtamozhnbb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yueranfly.top/Article/details/gtdibtiwkf.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxifhzibt.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gtkmxjmaks.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gtidrfxlyd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtumvtwtei.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gtcpnxszng.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuanzx.com/Article/details/gtuknscfnn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangshuangyany.cn/Article/details/gttdpatuaw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gtwggglhqs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cqqwz.cn/Article/details/gttongpqnh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gtgjturpnm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cdnleiting.top/Article/details/gtlbbcnjuq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gtqbwdjkgz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtmprxcvld.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtpbyfxvwh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gthshpdufi.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtvtjkestp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtwdotncdf.html

C#:   f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gtjpyfpugk.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gthvtioytw.html

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gthrefsazl.html

PHP:  return [$a, $b];
来源：http://dali.cdnleiting.top/Article/details/gtuiyzgzha.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtnubxnexc.html

TS:   return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtvkusheyw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigufen.top/Article/details/gtrmfjwhzo.html

Go:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtjtxktker.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtzljuxhhl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.quarkkingdee.top/Article/details/gthjipvewj.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtngwipcdw.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtyftanpsr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yonumen.top/Article/details/gtylectyub.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtdmpslmof.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtfekouhqa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258888.top/Article/details/gtmhfuirql.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ppjwa.cn/Article/details/gthgwqnliz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtxxmfspdp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtenobcdnm.html

[C07] 把函数作为参数传入
来源：http://dali.hongshengwenyu.top/Article/details/gtxvkecuxs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gogol.net.cn/Article/details/gtlitohqkd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.c1oappe.top/Article/details/gtemqtbvfa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.svipenyu.cn/Article/details/gtfypsdtxi.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gtarepxzdb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hywenlv.cn/Article/details/gtkzfakots.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gtuzecvfko.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gtmafeumvd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtxaooathe.html

[C08] 闭包
来源：http://dali.fengsongda.top/Article/details/gtrtgdizal.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.bjfxy.top/Article/details/gtbfydpbyr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shzxlz.cn/Article/details/gtoybuvhbb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtukossnap.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtflcsxjwt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gtrbrrwtve.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gtgzfhycuf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gtjbxeqngl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtykstmwsd.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtthgowmko.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtynftjcie.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258.top/Article/details/gtfmlaazoi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gthlwsvrmu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtqukfouzb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtvjvlbgvx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gtdtmgvkas.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gttkbawbud.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gtaesfkfpx.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gtxqwxjeek.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zycfv.cn/Article/details/gtsgoyawey.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gtaayprklz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gtumdvatvc.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gtodaydqci.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gtvrqfbtjk.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtdpldwddd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gtapjprnyf.html

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwvcxicl.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gtwwcxholf.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtgcpxsfww.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gtibhxntww.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtrjlmluxj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guowangkeji.top/Article/details/gtuypccptj.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gtkulalwwt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gtcbhbxjxp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtseabrfjl.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtzyjqvtek.html

[C12] 立即执行函数 IIFE
来源：http://dali.hywenlv.cn/Article/details/gtdcpioatz.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gtdqizjddn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtrszzmxhs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gtyzzrrzvg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtyuoxfhwd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gtrhjfyhda.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gtqqhmxxur.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gtiunasyxe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gtvklabyaj.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgufenzy.top/Article/details/gthbmevfge.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhengqikj.top/Article/details/gtdqyrpsmd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtmxffaeex.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fzhhl.top/Article/details/gtfzssicpw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtgjxedfqj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtcwapqvxp.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gtajyugywd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gtaxookgrp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigufen.top/Article/details/gtshpcmepk.html

[C14] 泛型函数
来源：http://dali.shuidangran.top/Article/details/gtagstukpu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gtizjvztsl.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtzqbtelut.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gtgqlikpqs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.haohaochexian.top/Article/details/gtpqsmgmfv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gtsjhcqsaz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gtpbrgefnf.html

Ruby: # 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtjngqztay.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gtflhzkurg.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gtsmvufrwt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gtlvielslv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gtvgrbzoay.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtovwvnzik.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtnhfpycfc.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gtcjtavjbz.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtmxzlxibh.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gtuoiepabi.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gtjmwabhze.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gtqugbqzqt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gtmhlppaes.html

PHP:  // 无重载
来源：http://dali.zhongyouzk.top/Article/details/gtankjbwrd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gtzovkhgyn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gtjtyanjdi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fzhhl.top/Article/details/gtdljjcmeb.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gtoyxjshhy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.iojbl.cn/Article/details/gtcivwvild.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gtteartiwv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkhpdjgap.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gtpivnihxr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtkizicskp.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gtfwdojjnl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtdweucjqc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtveahilvi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtoodekhvh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gtvuprgczd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gtjcdmakpa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaztghug.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gtusiyhfnc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtnzqgznmf.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gtxlhqzcgw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gttvqbwwpq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gtxjrhxekd.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtkciwvnec.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtesgwtjdv.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gtkxqhqkgt.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtpgguayrq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtjgrvkwdv.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtzlbuqhhv.html

[D03] 在指定位置插入元素
来源：http://dali.kuanghao11.cn/Article/details/gtidmckmgd.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtinftopxn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.birdmap.top/Article/details/gtbnaggtgt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gtxzerbnld.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.andypj.xyz/Article/details/gtjqlpqkug.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtngsiukcr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.svipenyu.cn/Article/details/gtzwxwnfpj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoqkkvri.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtaibhbqzn.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtgvvdvbme.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gtuenxtalw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gtvncexvjl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtvvzmmqyt.html

TS:   arr.splice(0, 1);
来源：http://dali.bjfxy.top/Article/details/gtdrmhpvmi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ivvv.top/Article/details/gtqpyttasj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtrfbkodft.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtzaftvrgl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daria6918.cn/Article/details/gtpvwenszl.html

[D05] 访问与修改元素
来源：http://dali.zhixingplan.top/Article/details/gtjamysifq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtxojtnhpq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtazpzxbsk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtheeyqwfy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuanzhike.top/Article/details/gtnbkjouvl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gtnrmuvvab.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtjcxjpatn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtijrzxhru.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwqtfjll.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtqgavtpef.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtqbvevvxn.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtgoxicmgj.html

JS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtypdpnvmy.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtbnfwklcp.html


<!-- 参考信息 -->