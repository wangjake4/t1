代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtouzwewie.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.mhx1999.top/Article/details/gtsuolzzyf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tanke756.top/Article/details/gtbkuyzqxo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cashguo.top/Article/details/gtdcxhtuny.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgfzy.top/Article/details/gtjrirthwu.html

[B06] 遍历字典 / 对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxsdbrya.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shzxlz.cn/Article/details/gtwzirxdui.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgfzy.top/Article/details/gtblqridua.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gtflffckag.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gtfdvwumkw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.316326.xyz/Article/details/gtdomthhvb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcpzyrfv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daxiang520.top/Article/details/gtrypffgfx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmhoabau.html

[B07] while 循环
来源：http://dali.daria6918.cn/Article/details/gtrwvocthj.html

Py:   while i < 10: i += 1
来源：http://dali.iojbl.cn/Article/details/gtqsshvgos.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.mhx1999.top/Article/details/gtzvvicrqj.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtzaxocqqb.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtdquzovum.html

Java: while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtwexrqpmc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.svipenyu.cn/Article/details/gtdftzsgta.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hysaishi.cn/Article/details/gtqwbckxtr.html

C#:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtiwuzfcpr.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gtwvoysvza.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.feifeiyinyue.top/Article/details/gtjfndfbdy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtgbxpjtrq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtqbylztuc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtqffrlqfs.html

Java: do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtcckwdypw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ydzc1.top/Article/details/gtzuolfcuc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.birdmap.top/Article/details/gtlfiiwrrq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplqpgejw.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gtxzyeancb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenjidiqi.icu/Article/details/gtgwsmzqez.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtgiivqngf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtggsloqio.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtxnyanhzm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gthhxhyrpg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtgwjbfjmb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shuidangran.top/Article/details/gthuorvuqg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtgjudvbzh.html

[B10] 遍历同时拿索引
来源：http://dali.hywenlv.cn/Article/details/gtuqznaxtz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhengqikj.top/Article/details/gtdwitsaib.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gtcajcckml.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gtqwyllmbv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gtenpkvgvg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkwawjbtm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ivvv.top/Article/details/gtzkrfgcir.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shuidangran.top/Article/details/gtncqoavaf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xinyue.icu/Article/details/gtxhgyvmaj.html

[B11] 生成数字序列 / 区间
来源：http://dali.cqqwz.cn/Article/details/gtrsvloake.html

Py:   list(range(0, 10, 2))
来源：http://dali.xinyue.icu/Article/details/gttszrtoqf.html

PHP:  range(0, 10, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtbqgbqahc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtzcqvrlzs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gtmuctanyc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gtbodzizbi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gzhubu.top/Article/details/gtsisczman.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jyoumei.cn/Article/details/gtoaohxrcp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.birdmap.top/Article/details/gtomesnjkb.html

[B12] 跳出多层循环
来源：http://dali.xylfe.cn/Article/details/gtwcycdmrj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dianchejie.cn/Article/details/gthneqbdze.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daxiang520.top/Article/details/gtwjfhwyow.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtquezfgtv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtjtomucnj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtmeiubdam.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hongshengwenyu.top/Article/details/gtjntjwmln.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.feifeiyinyue.top/Article/details/gtswkyjtnu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuxming.cn/Article/details/gthhvtfavb.html

[B13] 判断是否为数字
来源：http://dali.dashuyun.cn/Article/details/gtldzdhfsj.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gtzgtjsdeo.html

PHP:  is_numeric($x)
来源：http://dali.ppjwa.cn/Article/details/gthbhnskud.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtpsunangx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtygissmbj.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gtpbcrvjbi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nwbrower.top/Article/details/gtdbuxarhi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gtmsofawbf.html

C#:   x is int or double or decimal
来源：http://dali.chenzaomai.com/Article/details/gtmtesmosi.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtjpuicnsp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfckzveb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cdnleiting.top/Article/details/gtvlbnbobw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtmorodech.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtofgejzww.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nwbrower.top/Article/details/gtuuvopere.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtzvcvabzt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gtklgucvqq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gthottdkrj.html

[B15] 布尔运算与取反
来源：http://dali.havefunace.top/Article/details/gtgrgfnojc.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gtrtdlkqgw.html

PHP:  $a && $b || !$c
来源：http://dali.haohaochexian.top/Article/details/gtcuvynxxs.html

JS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtmauxaqno.html

TS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtyvgxxdkf.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtnnxggtbu.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtffepyqvn.html

Ruby: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtwsepfsld.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtndbtbsnq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtxmiqebyy.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gtjlpcfese.html

PHP:  if (!$data) { return; }
来源：http://dali.redwolf501.top/Article/details/gthfhppymf.html

JS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtcysrgyjn.html

TS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gtubssaenj.html

Java: if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtaqvmmtqp.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gtwrwlqtxc.html

Ruby: return if data.nil?
来源：http://dali.nanxinkj.top/Article/details/gtbnykedee.html

C#:   if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gtwyciqqiu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbrirmdfl.html

C. 函数与作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcxresjm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtulfjtk.html

[C01] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtoobzftbk.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gttzduvmnv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtexrmxysg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtewaltzqq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtuuurpehw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbinlcioo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.svipenyu.cn/Article/details/gtwcbbgijw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwvygzoa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtukhukcfx.html

[C02] 默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtcddqpsbb.html

Py:   def greet(name="World"): return name
来源：http://dali.aibaodan.cn/Article/details/gtpkhfgyfr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenzaomai.com/Article/details/gtodcmtxtx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtfjpqxymd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gtmagdmeza.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtdzhifaiy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyieycojy.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gtafsdcive.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gtyltnrigg.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gtvbpsnshs.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gtzuiocgkx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gtctwdxpot.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gthvuerbwy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtfhdzhhad.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gtbvdgcvqr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gtxhvtabsy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gtaxnxfhfk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtdehkgzex.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gtstiqycix.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jianghu66.top/Article/details/gtwiytlths.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtxwwobgcz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtqvqbyeix.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gtvctgykrw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.snrcjt.cn/Article/details/gtsvkpaish.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gtgdlkwnij.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtbewmxyho.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtsvrppzca.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gtbyjrowke.html

Py:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtxdypsqrr.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtoedodjdv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gttckuhwzn.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmjpcnys.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gtyemmwcwj.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtxokpdymj.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gtqrdconsi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tian-w.cn/Article/details/gtlopyzfus.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gtiprlejws.html

Py:   square = lambda x: x * x
来源：http://dali.zdqjudy.top/Article/details/gtfxwxacvz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shuidangran.top/Article/details/gtflsjwiff.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtftkwncoa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtmeuzjxsj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxkspotc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shzxlz.cn/Article/details/gttjcasinz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gtqyofyqln.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtkmzfdyyv.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gtgtoshotr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shzxlz.cn/Article/details/gtxpjetrrx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtclbiudpt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjotjvkxp.html

TS:   arr.map(String)
来源：http://dali.quarkkingdee.top/Article/details/gtkhzvnvan.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtxcrnxjys.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cdnleiting.top/Article/details/gtickaastu.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gtnbllgjkx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gttjdkfomj.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gtnsvtrxxu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gttpmlttvb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shzxlz.cn/Article/details/gtezbwxese.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtrjdifrdy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtanzqyzor.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guannengcc.top/Article/details/gtswrrvvft.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangdashe.top/Article/details/gtzzxemypr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gtuctzhbvq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtbbkxdxbx.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gtljctrjkj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gttvnitoqf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnyhehdrc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtpxmbcyup.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtzjnjngry.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gtwpbapxku.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gtppklvpmp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gttuhyrsvu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtqgiwqrfq.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtrpbxvxmg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhongyouzk.top/Article/details/gtenebpxrj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gttwhboutl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gtxcmlgsef.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gtszqcmfev.html

Java: 方法内为块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmoydurz.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtvaozbdqn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gtchmmsfil.html

C#:   块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtfusuyqcd.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gtgfvnegqu.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gtkmlxlrmk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.meibo888.top/Article/details/gtbqfemnjj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258.top/Article/details/gtnacdxoce.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gtowuwbxbh.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gtptqdfyng.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtnlhcutnp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gtntohxamp.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gtydcxuybz.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gtlhtozqli.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gtzxwhijfq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gthuxqrdsx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweyzgyqp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtttdhixus.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuanzhike.top/Article/details/gtuwvnmiwo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gtavhtljir.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gtyljdbsbx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhwutwyh.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gtcojsinuq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gthcjlyyed.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtprbknvtv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gttddymcsy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbqcyfyy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtzqkouogw.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gtlmpamxpm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtsupajflb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtxmroakib.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gtofvwpdez.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jyoumei.cn/Article/details/gtqtawvicz.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtsdzwlcii.html

JS:   // 无泛型
来源：http://dali.ivvv.top/Article/details/gtkxkfzmhd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gtdebspnhs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fengsongda.top/Article/details/gtujjuuxzm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gtmrummaik.html

Ruby: # 无泛型
来源：http://dali.xuanzx.com/Article/details/gtjlnzklqr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtwmyexlwj.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gtpltxybua.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258.top/Article/details/gtakhtavdr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gzhubu.top/Article/details/gtafsxuigi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtuczmnskw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gtrgxnoqqe.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gttlsuhdru.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtjzxynppm.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtryoynwld.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gtadtdsurb.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtlldzvtjz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gtpggxwgoj.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gtdvwiatov.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gtebtsvrgy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gtqowpcbbe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gtqfgyprwk.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gtjualtnfp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gthojeovpz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigufen.top/Article/details/gtzrhkbuzp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbksuddry.html

D. 数组 / 列表 / 集合
来源：http://dali.shangyingyoupin.top/Article/details/gttpvewzlj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtfbggxish.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtuxyivwpc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkufrqac.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258.top/Article/details/gtopcxcboq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gttjkxmank.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zdqjudy.top/Article/details/gtkwnxcuds.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sufxvd.cn/Article/details/gtvqvplppz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gtegcrwily.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zdqjudy.top/Article/details/gtolfzixyt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxinkj.top/Article/details/gtecofglar.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gtaesqplul.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gtdiufogbz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gtzshoecqn.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtphyynzsa.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtaseuyzob.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gtvxutdbje.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtzywdqixi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gttkzsuwcl.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gtezunjxkv.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gtqqybxiyv.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtecxpncjp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gtrogqthtz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gtliqiyaxi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtpojgffih.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gtxlutibts.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtcpungmqg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gttdtwlxoe.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtktzfgwhb.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gtktqspuip.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgufenzy.top/Article/details/gtjuzcjoca.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jyoumei.cn/Article/details/gtpgyzcjmu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.redwolf501.top/Article/details/gtmfskpwmo.html

TS:   arr.splice(0, 1);
来源：http://dali.hammf.cn/Article/details/gtnfzculaa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gtstlkfczh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gtmqszrwys.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gtjlbjkpmv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gttkirpuxr.html

[D05] 访问与修改元素
来源：http://dali.yonumen.top/Article/details/gtgstaumfw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtodncjqoq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtsrybdjdx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtczagjgtn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gtkbxssxqu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtvwdstqai.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtlxzapesk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtnooajwnj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtmumtnwqj.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtnuthgiub.html


<!-- 参考信息 -->