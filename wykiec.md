代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jiagoushi.top/Article/details/gtlvfyxoct.html

[B06] 遍历字典 / 对象
来源：http://dali.yuxming.cn/Article/details/gtdhkbhkvp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigfzy.top/Article/details/gtovtyezqi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.haohaochexian.top/Article/details/gtfnwotmor.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenjidiqi.icu/Article/details/gtakcmtmdk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gtkjpfvnsm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xziqi.cn/Article/details/gtobixespt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cheryme.top/Article/details/gtdinkazjq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shuidangran.top/Article/details/gtzsulpxnf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guowangkeji.top/Article/details/gtqyvityat.html

[B07] while 循环
来源：http://dali.yonumen.top/Article/details/gtjnvmsxqy.html

Py:   while i < 10: i += 1
来源：http://dali.sysykeji.top/Article/details/gtllikhcdr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhengqikj.top/Article/details/gtmyjcjmkx.html

JS:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrcmvqngx.html

TS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtykvskorp.html

Java: while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtthkimraf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zycfv.cn/Article/details/gtznztbiqm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gtotcsabzy.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigrafdds.html

[B08] do-while（至少执行一次）
来源：http://dali.ppjwa.cn/Article/details/gtceyawiec.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sxryk.cn/Article/details/gtxcdxmcxp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tanke756.top/Article/details/gtviepqmmt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtkplpzjho.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtwswymshr.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtehfoiqna.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqvwhogr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zycfv.cn/Article/details/gtwycvjrtv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtqktyohpv.html

[B09] break 与 continue
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoubaoctt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhiwuduotai.top/Article/details/gtlovhqxon.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtwbvnazzf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtpbvjncft.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtbdyptdon.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtmjkdxziy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.kuanghao11.cn/Article/details/gtowbbyfvg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gaohongyu789.top/Article/details/gtzdaxwate.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtndhorlhm.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gtlspmkwhm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuanzhike.top/Article/details/gtawatilqf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.0kj1m.cn/Article/details/gtrbwnkqhs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtjtmalhaj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gtvrjxcbog.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sysykeji.top/Article/details/gttrmphoyg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gterxzhsrp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guowangkeji.top/Article/details/gtekdnymkp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ivvv.top/Article/details/gtmjinlwpk.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gtatxpbajj.html

Py:   list(range(0, 10, 2))
来源：http://dali.ehwqpu.com/Article/details/gtxpzwrrri.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtpcfacihi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gtqakonorv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtencelqqw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtckzfifkr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj202588.top/Article/details/gtzcysehrz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gturvzvmvt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gogol.net.cn/Article/details/gtsancgwxc.html

[B12] 跳出多层循环
来源：http://dali.jqgfzy.top/Article/details/gtltqdhkip.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sweek.top/Article/details/gtdbglbqak.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.haohaochexian.top/Article/details/gtyzaealqq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtswnngpnn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtdmvmbtay.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtthsszntt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgufenzy.top/Article/details/gtdxwoklzq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuetiantiany.cn/Article/details/gthvyzukfz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gtidwtaoux.html

[B13] 判断是否为数字
来源：http://dali.cdnleiting.top/Article/details/gtnsmenayi.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gtqgblmaxf.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gtnmaxbwfv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtpbvogmep.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gticworhnz.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gthjvbmlcl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzppsopl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sysykeji.top/Article/details/gtiziokguy.html

C#:   x is int or double or decimal
来源：http://dali.smart0.xyz/Article/details/gtjfhggayv.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gtraepjlqf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shzxlz.cn/Article/details/gttwuqmxut.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.havefunace.top/Article/details/gtvqoqorpn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtnfcgznvg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtvtbhotyk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aizwys.cn/Article/details/gtjlyetqio.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gotoacloud.top/Article/details/gtxleetkkx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guowangkeji.top/Article/details/gtxorhidvo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtopqkopxi.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gtcyrskztk.html

Py:   a and b or not c
来源：http://dali.xuanzx.com/Article/details/gtprthpzbx.html

PHP:  $a && $b || !$c
来源：http://dali.cashguo.top/Article/details/gtfoffesav.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtuhbpdsxj.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtgqgvhenp.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtldgofdqa.html

Go:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtsmwagbrz.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtunmwscfh.html

C#:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtwenexitk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtjukentpp.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gtmofggken.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gtuszyeuuq.html

JS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtgtyvbspt.html

TS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtledmycpm.html

Java: if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtihbnhwrk.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gtlbppisht.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gtvgyzpkob.html

C#:   if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtwipbppmz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfpgcueyb.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gtuiygvton.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvdutbrth.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gttlizftvl.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gtwplnpddq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwshujczx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtszkuyzze.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbfuspuy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtljxtdhlk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtumgswmgr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gtzmdnxqzb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtawekviha.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gtdlbwayac.html

Py:   def greet(name="World"): return name
来源：http://dali.hongshengwenyu.top/Article/details/gtqaroaomc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gtrprnmqxl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjnmsqkjh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtowojmndy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gtkvifyxkv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gtmigblmfd.html

Ruby: def greet(name = "World") = name
来源：http://dali.jyoumei.cn/Article/details/gtatamyiwq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gtllxdxuru.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gtzivyoupr.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtrpdyrvzm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jlsjyb.cn/Article/details/gtamjvpbjn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtmxhepxmt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gtlgelbqlm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgfzy.top/Article/details/gthvxjlucj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gtjemrgqmw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhiwuduotai.top/Article/details/gtcfjdvqvt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gtonzqxcmu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gtzrruaboy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.c1oappe.top/Article/details/gtkrjgkppx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aibaodan.cn/Article/details/gtkfatodds.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gtzlfhecwe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gtmeykhkii.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gtmojvxaet.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangdashe.top/Article/details/gtkrvgdipb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gthxeawjwl.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtjhbzpwvv.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gtbdtkcniz.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gtzlardbow.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gtmfaywqzr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gtaolenxpb.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gtexjdrddy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gtatbhjxvv.html

Go:   return a, b
来源：http://dali.xylfe.cn/Article/details/gthvotmgvo.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gtdapgvort.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guannengcc.top/Article/details/gtjkdljsgr.html

[C06] 匿名函数 / lambda
来源：http://dali.redwolf501.top/Article/details/gtmyysmbqb.html

Py:   square = lambda x: x * x
来源：http://dali.cucudq.cn/Article/details/gtyxuzzoug.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ybcxt.top/Article/details/gtjocfizlk.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtdplipgbj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtaetjdjwl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sysykeji.top/Article/details/gtyxesmfjw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtvyypuwow.html

Ruby: square = ->(x) { x * x }
来源：http://dali.haohaochexian.top/Article/details/gtfjieqogu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtluiojhxs.html

[C07] 把函数作为参数传入
来源：http://dali.pycfn.com/Article/details/gtynztlzei.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gtolwluxdp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtfflnhkdm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gtpbczdebj.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gtkfidhlrh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtnndhzttg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.haohaochexian.top/Article/details/gtdrawbcgv.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gtccuostni.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gtysxercfo.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtsljqdasa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gthazxqpcu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gzhubu.top/Article/details/gtbuoukbnp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtjupmjvbc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtoojgusnm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yangfankeji.com/Article/details/gtlvlrskvm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.feifeiyinyue.top/Article/details/gtcnsowkxx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gtkeqdqhof.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtmscqcifp.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyecfxoxf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtlyutdaho.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtsldhacuc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtetxaewjf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtehrexzpb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtvmqvyway.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gtntmdheoz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtuzxgnwfe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fengsongda.top/Article/details/gtpjjoecwv.html

[C10] 变量作用域
来源：http://dali.dashuyun.cn/Article/details/gtknwlnket.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gtilkidcad.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuanzx.com/Article/details/gtjrkuwbqv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gtjcchtjqr.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtcuscysbj.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtlyqrrluj.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gtvnexyofe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gtowujfcwm.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gthycpnocp.html

[C11] 模块导入与导出
来源：http://dali.yj20258888.top/Article/details/gtgvcumceu.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gtaheutjbf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tian-w.cn/Article/details/gttchcjyyg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtlamlwvjj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhiwuduotai.top/Article/details/gtnmaeqjqo.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gtxygdvoky.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gtsqzzirlw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgubpdpfm.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtqhdeiqno.html

[C12] 立即执行函数 IIFE
来源：http://dali.jianghu66.top/Article/details/gtldjxftes.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqmjydem.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvgdkzfj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gturzjsaim.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtacztmnpj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gtinbqqevk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guannengcc.top/Article/details/gtfzjpbdmy.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtgqmlaexx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtoeiepxqp.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gtsixeydkp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gtveydfwxo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtjvbiqkvr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtfjlwubbx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtskibagab.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gttvsyeovs.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gteparrzpc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gtolbssolx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gttpgzodht.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gtykirrqku.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cdnleiting.top/Article/details/gtycajrhsw.html

PHP:  // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtonmdekga.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtkkofkbus.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gtaqbwgtcy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gtinjbnrhq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gtkhayqyur.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtszvlhkbg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gtgtmuftmk.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtiaaukilm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxinkj.top/Article/details/gtyzliabnt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gtxiehbczj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtezgaazip.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gtcuffmrwh.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtcbowclpe.html

Go:   // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtzijgjmgu.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gtwrrosbcg.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtrpjzrqdy.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsxkdfvn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gteuoidvot.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gtrgqxhnwq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gtzfxovihs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gtzkcgcsuy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gtzwiewaue.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gtbgjrtlua.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gtmkxttimo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtlqdntloo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpcevyvfm.html

D. 数组 / 列表 / 集合
来源：http://dali.zdqjudy.top/Article/details/gtkvrvghst.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmcwpogmk.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtdkalxpvs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gtdraristd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtplnwngnq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daria6918.cn/Article/details/gtqdjarain.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dashuyun.cn/Article/details/gtjuvflshi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtkvogvfue.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gturgnghhc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.0kj1m.cn/Article/details/gtfwegxoov.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gtpwdmxfjh.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gtkbsnqcvx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gtxubrgmjz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtfsrzgqsh.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtowseuxuv.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtdnoojcxj.html

Java: list.add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtmwylqgpj.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gtyoeqjqvi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gtaxtlvula.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtgurznben.html

[D03] 在指定位置插入元素
来源：http://dali.sweek.top/Article/details/gtpbmwpcjd.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtlxianokz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gaohongyu789.top/Article/details/gtnnfaqeen.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sweek.top/Article/details/gtghfawxoz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.andypj.xyz/Article/details/gtchrlewtp.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwwvitbl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtebenikwk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gtskbhkqrn.html

C#:   list.Insert(0, 0);
来源：http://dali.birdmap.top/Article/details/gtghdpanuc.html

[D04] 删除元素
来源：http://dali.nwbrower.top/Article/details/gtacgrlqcq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gtdmvwaufp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cashguo.top/Article/details/gtbuovdife.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gtmpnhmadb.html

TS:   arr.splice(0, 1);
来源：http://dali.sufxvd.cn/Article/details/gtgjflgziw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gtpyqefrio.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gtpkpkxilw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gthgmmfuux.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtxfbmbsqy.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtbnievwcn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtmcxfqfuq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtybhgetqg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtjmemddpn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gtvlnsrwll.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gtgpnpabtj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtoxcaqtpz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtkmwkgpma.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtxpmmtfzq.html

[D06] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtzwxpzftl.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwokoyez.html

PHP:  count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtwqjfjsrs.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtmqtxejdk.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtgkqynzea.html


<!-- 参考信息 -->