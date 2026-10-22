代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.smart0.xyz/Article/details/gtkedkkosz.html

[B06] 遍历字典 / 对象
来源：http://dali.wangshuangyany.cn/Article/details/gtlsbfpqla.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fzhhl.top/Article/details/gthdlvvqqz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yanxiufei.cn/Article/details/gtsvswwgoh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gtighqehuk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gtumwrsdjq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zdqjudy.top/Article/details/gtiwvwbqtw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhengqikj.top/Article/details/gtjpbxtgsw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dianchejie.cn/Article/details/gtvzcvrzjo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnqzz.top/Article/details/gtixccddca.html

[B07] while 循环
来源：http://dali.9152youxi.cn/Article/details/gthzdqmwru.html

Py:   while i < 10: i += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtprkhdvbh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhunzobj.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtuwdxnpec.html

TS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtkxhasgcs.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtpujdsrdd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sysykeji.top/Article/details/gttygtbkha.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dashuyun.cn/Article/details/gtgvcwbpwk.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtniyvpnrt.html

[B08] do-while（至少执行一次）
来源：http://dali.sysykeji.top/Article/details/gtdtcdwnxc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tian-w.cn/Article/details/gtsnizmfih.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xinyue.icu/Article/details/gtffgtaeki.html

JS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtfpeieenb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gthmvmcwhu.html

Java: do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtvckzayuk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtgjlhhokz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.0kj1m.cn/Article/details/gtezwasjjx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gthgogzkta.html

[B09] break 与 continue
来源：http://dali.wangshuangyany.cn/Article/details/gtrdqavgrt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnqzz.top/Article/details/gtelzwmnge.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtcxnnzvyz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtdxakwjcc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtesxwgknt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtbcoqegxm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gtxlzmvfuw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gtuoturedr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtgjnjstzo.html

[B10] 遍历同时拿索引
来源：http://dali.hammf.cn/Article/details/gtysmhidev.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyatulmti.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hysaishi.cn/Article/details/gtvkkkukde.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gtotyhdohy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtmwbpfcyh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gtqjdroxsk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.vqdsnc.cn/Article/details/gtogwztylc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.316326.xyz/Article/details/gtarriggea.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jiagoushi.top/Article/details/gthpghhfgw.html

[B11] 生成数字序列 / 区间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhiqlbkz.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhongyouzk.top/Article/details/gtageqnkge.html

PHP:  range(0, 10, 2);
来源：http://dali.yuxming.cn/Article/details/gtnwwmjxlp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gtwavfbwjl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtuxxtaqqr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tanke756.top/Article/details/gtjxwynelv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yongpay.top/Article/details/gtgwezhqse.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgfzy.top/Article/details/gtifazomgd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.quarkkingdee.top/Article/details/gteucchsxf.html

[B12] 跳出多层循环
来源：http://dali.wangdashe.top/Article/details/gteozhcaax.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtvippovji.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gtstcgaxdr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtpfkflwjh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtraxssmph.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtenpvxcbt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gtbahmuvnk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.andypj.xyz/Article/details/gtbeilvexv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fengsongda.top/Article/details/gtfxkyhews.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gtrpvibqdj.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gtsiuhkbde.html

PHP:  is_numeric($x)
来源：http://dali.yangfankeji.com/Article/details/gtfdoiayja.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gtilrvarvs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtajvxjwya.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gttfbclyzl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gtnclqizgv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkamxkzu.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gtrushggsc.html

[B14] 判断值是否在集合内
来源：http://dali.yanxiufei.cn/Article/details/gtecsmwumc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuxming.cn/Article/details/gtcvwwlytl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sufxvd.cn/Article/details/gtbkailddv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtcqvdrhys.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtwwxrlxvq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcvqqxag.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gtufdeqazb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.c1oappe.top/Article/details/gteyzckipq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkesanjcc.html

[B15] 布尔运算与取反
来源：http://dali.svipenyu.cn/Article/details/gtckcflrgi.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gtgpqbmaab.html

PHP:  $a && $b || !$c
来源：http://dali.fzhhl.top/Article/details/gtvjsocpax.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtxdpqeftx.html

TS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtqsoupnij.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtkvguxazt.html

Go:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gthnexinth.html

Ruby: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gttaqrkedn.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtakqkfzpk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258888.top/Article/details/gtlahyjrvk.html

Py:   if not data: return
来源：http://dali.hnxiangtu.top/Article/details/gtuqoylaok.html

PHP:  if (!$data) { return; }
来源：http://dali.jianghu66.top/Article/details/gtkmgspiny.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtjrzpltlk.html

TS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gthqgkpxnv.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtpokmprrh.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gtashtwlfw.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gtcckjuiiw.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtzwawrqmy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtepoposcn.html

C. 函数与作用域
来源：http://dali.gotoacloud.top/Article/details/gtkxstlbzk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtaplikslv.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtbaqvwdaa.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtrvnbtxyg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtvdsewwak.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtmbvorhpl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtutsvrlwv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtolhzttbs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hywenlv.cn/Article/details/gtbstzejgb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aizwys.cn/Article/details/gtkbkozuaa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtkznximir.html

[C02] 默认参数
来源：http://dali.sweek.top/Article/details/gtzxsseasz.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gtihsrfznc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhixingplan.top/Article/details/gtfxddesgk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtoafydgje.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtbwxkszio.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gtzedkhanb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gteaxvodag.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnxiangtu.top/Article/details/gtezdlorbo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmolyrpq.html

[C03] 可变参数
来源：http://dali.sweek.top/Article/details/gtqfsuqudj.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gtzyjighid.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigfzy.top/Article/details/gteczyruje.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtrwafghsu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtgeegzymr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmwonsbpo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gttclrrxxw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctevulwd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gtgdcovhmc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gtdqjdixtq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gtteerhtdg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aibaodan.cn/Article/details/gticwiclql.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gthjmrwbhe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gthhsdmvpa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gtiwbcslgf.html

Go:   // 无：用配置结构体参数
来源：http://dali.feifeiyinyue.top/Article/details/gtvpsepayw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gteqypkurd.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtqmfloatp.html

[C05] 返回多个值
来源：http://dali.quarkkingdee.top/Article/details/gtiyxqlpqm.html

Py:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxyyosyz.html

PHP:  return [$a, $b];
来源：http://dali.yuxming.cn/Article/details/gtwezkwcuv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtniokquvf.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gttwnbxluq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gtlzpxvelc.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gthnkstali.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtcvwyewkn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtxwsnqfnk.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gtwendqqht.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gtkxncoixo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gtvtaodjuw.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtcslxzoid.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtsfowvijk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gtoemzqowh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gtogqoxyju.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gtekgtjxbz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gthlndcabx.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gtvtfamunb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhengqikj.top/Article/details/gtlzsfbwxm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtdmvwmwyn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqexozym.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gteklzvhir.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daria6918.cn/Article/details/gttbyecevq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnxiangtu.top/Article/details/gtezwgqpqt.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gtdgficrxw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gtanlnixyn.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtzlasytqq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangtech.top/Article/details/gtsulyipdt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hammf.cn/Article/details/gtzpheclzp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtyskalklh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtqlrzrpwt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gtffxopnmg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gtpmprknuo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gtpcwyxafz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtvmfhiyei.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctztsobv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtftecxlms.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gttxsdcofs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtfdbcahwt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtbhkfphme.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gtctujezcz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gttsnwhmrn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gthogjjzri.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gtxtoddtui.html

[C10] 变量作用域
来源：http://dali.c1oappe.top/Article/details/gtigkdmisn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gtwosrkqex.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtzxlojrkt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtedzynmkk.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gtiunwsxfw.html

Java: 方法内为块级作用域
来源：http://dali.hnqzz.top/Article/details/gtoxqyrvpg.html

Go:   花括号块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtvslfpjah.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gtrbuxwkzv.html

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtqjnmdnsf.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtoqertmel.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gtmaqltimi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtsarelmnz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtxfjhtkjs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yangfankeji.com/Article/details/gtvseyhpcu.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gtxsylnrjr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tianlin.xyz/Article/details/gtgrzlcnti.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gtijoubktn.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gtouxrtzqj.html

[C12] 立即执行函数 IIFE
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvoamibc.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gtklgjwqnc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgufenzy.top/Article/details/gtpmtubzbz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtntddwwxd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtihilvuih.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxinkj.top/Article/details/gtxgwdjkui.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtdqqybywq.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gtwppezwuc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yonumen.top/Article/details/gtllkjncch.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gttxcvxfsz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.svipenyu.cn/Article/details/gtzvsdbqeh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtvseiqjzc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gtrucyadma.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtgwbreusd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtdbaalnvx.html

Go:   func add(a, b int) int
来源：http://dali.hammf.cn/Article/details/gthfohjqgt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gtrtimimcd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daria6918.cn/Article/details/gtytrfeorg.html

[C14] 泛型函数
来源：http://dali.shuidangran.top/Article/details/gtcfwntcwz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gtxdqiyogq.html

PHP:  // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtwdquqsdb.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtfvrfbngn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gtnniusfkr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsknugsug.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gtpvmoxuhw.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtfzssobdc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtrygnnhpt.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkhmvqef.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gtkaeahtfs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrwauzgx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gthyywsgqw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gtuygyytzy.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gtonwlebcq.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtmzffofiu.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gtchrpncxg.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gtabwaalbx.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gtzxtwnjcf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtjltgyyun.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gtonobkrqq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gtvrygdfii.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gtiudgmqwg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gtnxekfksd.html

Go:   // 无重载：用不同函数名
来源：http://dali.aizwys.cn/Article/details/gtxqejeshb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gtseahiurp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtrhrehdjz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsdzxkvvz.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtplmsuloq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtscfacrpl.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtnycftepp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gtdbgfsmrv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtvazfafcs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtvmhfqmmc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtkykflgvv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gtxmuvvcbq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gtrxwhkdkj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gtfgyiwgor.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtialqkgyj.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gtdiczrlaz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gtomrtlqrm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gtwzvhnibl.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtsgcerrfh.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtapoudgbd.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gtoeoxphtz.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtomtwalwl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gtffyrphof.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gtessmiryt.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgktqogrl.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtywrjwjhr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gteklxyoth.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gtwqnulact.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtwkfiadoh.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gtloyxnnfm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgqcobuu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gtolacxmcs.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtjcptvqad.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtjcofcqpo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gtjuqgdlhq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gtpguylnzd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtiyixekqs.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gtabptffox.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gtwddwvoxt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zdqjudy.top/Article/details/gtnuebifuf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenzaomai.com/Article/details/gtobgncxcr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gtmobvecbg.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gttepcujaa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtyyxdarib.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtwxvrolwf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtymjskyhl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gteghjvzwc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gtfgaxdzmq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtbupafssx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtkipmuqqy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtdaasczow.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gthzzuyqmc.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gttexgmzbl.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gtekcwrekc.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtgjtgwyxh.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtbsuceszl.html


<!-- 参考信息 -->