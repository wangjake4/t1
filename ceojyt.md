代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gtdftotmfs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gtfaytynxb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hammf.cn/Article/details/gthcodlcvm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shzxlz.cn/Article/details/gtnqwrxfiy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xinyue.icu/Article/details/gtsjwthdbe.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gteapzzxen.html

[B07] while 循环
来源：http://dali.sufxvd.cn/Article/details/gtfqvkbfvh.html

Py:   while i < 10: i += 1
来源：http://dali.yonumen.top/Article/details/gtobrhvsac.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dianchejie.cn/Article/details/gtvzvhopfj.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtphzpwlph.html

TS:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gttszwlqps.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtoluoddvl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgufenzy.top/Article/details/gtxgebpmuf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tian-w.cn/Article/details/gttymztjob.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpaphhhkr.html

[B08] do-while（至少执行一次）
来源：http://dali.quarkkingdee.top/Article/details/gtccipfnlz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gtlrdjzjdq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sxryk.cn/Article/details/gtxvswyknl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtvxgcdkga.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtkkgmliqu.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtiwumzfue.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gtkitlmjlg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.haohaochexian.top/Article/details/gtlouoxgkg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtejapcvkn.html

[B09] break 与 continue
来源：http://dali.jyoumei.cn/Article/details/gtlzxqmpid.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiazpdpv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtsmvtvjsw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtqoghumil.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtfzvpdenu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtqglxbeng.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xylfe.cn/Article/details/gtbcotxhla.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gtqpomdgld.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtyovpoflx.html

[B10] 遍历同时拿索引
来源：http://dali.daria6918.cn/Article/details/gtpdrdcvgx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gttlaqgeam.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjuyoswpc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtkqdzeuoo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gtkbdfpxhj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangdashe.top/Article/details/gtoqbetfir.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gotoacloud.top/Article/details/gtcbyhgytd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtwkwnzkrx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhoulong.xyz/Article/details/gtgrzfuivw.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuetiantiany.cn/Article/details/gtorbzbkeh.html

Py:   list(range(0, 10, 2))
来源：http://dali.yonumen.top/Article/details/gtupztptek.html

PHP:  range(0, 10, 2);
来源：http://dali.redwolf501.top/Article/details/gtdaaftwze.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtmndevrtf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gtkndossjp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasfwqvde.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hywenlv.cn/Article/details/gtfgfkjinr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gtqbnkoeul.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuxming.cn/Article/details/gtwfekqglm.html

[B12] 跳出多层循环
来源：http://dali.yangfankeji.com/Article/details/gtqsjaeipj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cucudq.cn/Article/details/gtbllkjyti.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.andypj.xyz/Article/details/gtqzymlpin.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtdowxqgoq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtainkyrek.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtftmoklab.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gtvzipezzw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gtflhmfbfa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinghuilouyu.cn/Article/details/gtvykuvwpk.html

[B13] 判断是否为数字
来源：http://dali.smart0.xyz/Article/details/gtwrizgxpz.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtsoqfqykc.html

PHP:  is_numeric($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipiziceh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtfqdkozva.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtxdozdsxc.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gtwgqkhzra.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sysykeji.top/Article/details/gtutquparb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ehwqpu.com/Article/details/gtdispdhox.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gtmrbsjfsy.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gtfxjxoufm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.c1oappe.top/Article/details/gtbfridtdu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ydzc1.top/Article/details/gtivhzbckp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtocxahrua.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtphxvjkig.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.bjfxy.top/Article/details/gteikcunqs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gtzbodutxz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtevaqevak.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtynkfdmmo.html

[B15] 布尔运算与取反
来源：http://dali.jianghu66.top/Article/details/gtmysxvshz.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gtdxtavelx.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gtvocbyjgl.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtmnamerpg.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtjmfpezgx.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gtldlbmzjs.html

Go:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtupmhynyb.html

Ruby: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gttganbhhq.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtpemgqauk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.wangdashe.top/Article/details/gtetzvznte.html

Py:   if not data: return
来源：http://dali.jyoumei.cn/Article/details/gtwzwnfttw.html

PHP:  if (!$data) { return; }
来源：http://dali.havefunace.top/Article/details/gthbijecvf.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtiwdwnrtu.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gtyrhxrawj.html

Java: if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gtoglrlpxl.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtvbhtdqbj.html

Ruby: return if data.nil?
来源：http://dali.hnqzz.top/Article/details/gtezmzbjqa.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gtpdbgvalh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtegsrylmb.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtlolxnuow.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkqiktusl.html

[C01] 定义函数
来源：http://dali.yueranfly.top/Article/details/gtfhjafdqb.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtcltkgezv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtovfqxlxq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtcksdzysp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtfpmlqass.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtyppkdiac.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtjghyeiri.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cucudq.cn/Article/details/gtrcqnalnh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gthdhorelr.html

[C02] 默认参数
来源：http://dali.daxiang520.top/Article/details/gtgqzhozaw.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gtejyqsyco.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdmgoqmim.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtyuthvfzj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqapysxun.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigufen.top/Article/details/gtunoiposs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gtebbpcetw.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gtvofbshah.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gtpfbobjdh.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gtwjhreqjf.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqmyaggx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gtsegdddzv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmavbiqpn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gtrajmkzau.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gtsqoagkvp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gttvotetvr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtizhvodzk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gtcdtqicvr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztrvzily.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ydzc1.top/Article/details/gtpgktbmjl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtdyxsvznk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtcgfklsgc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtzgetobjw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.316326.xyz/Article/details/gttjrgujpq.html

Go:   // 无：用配置结构体参数
来源：http://dali.meibo888.top/Article/details/gtkqlzfcyo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtettzjppg.html

C#:   f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtldgfmuuf.html

[C05] 返回多个值
来源：http://dali.ydzc1.top/Article/details/gtzokfnktz.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gtkcjuoebw.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtiwxypjud.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtwgchnekn.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtdiaiwglg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gtyqyxsoob.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtiflvljwb.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtdwzwjtsa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.meibo888.top/Article/details/gtigfxytsh.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gtgpkopwmb.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtzhpelife.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizsyeags.html

JS:   const square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtfbahmkrn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtjdcpvixs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtvspmegte.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gtecfgcfxu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmbasmlh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gtqzymxdta.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gtzmeeaaqa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gtjzthhysy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtejiqsigb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nwbrower.top/Article/details/gtponhaqcs.html

TS:   arr.map(String)
来源：http://dali.vqdsnc.cn/Article/details/gttssyaxmr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.svipenyu.cn/Article/details/gtewnlhsfg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gtskqufmtn.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gtgdqxzzew.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dianchejie.cn/Article/details/gtkxtzspoz.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gtpmajrwck.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gtnrjmezab.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jiagoushi.top/Article/details/gtamvpxfqq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gteyifejod.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtsulubxdl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jyoumei.cn/Article/details/gtecacclkx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gteigufgeq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtljuqgpxi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtpyaysklt.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gtjajlppnp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtgudjqwvu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpfriiie.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtybsihsnn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtgjaanorj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtucjytyqp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtscehhcfs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtrkknhupo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.birdmap.top/Article/details/gtwnxgedef.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtegpgxbbt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gtkdhxhyqk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gtvhbtaext.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ppjwa.cn/Article/details/gtqgcdpfmx.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzwomdgu.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gtxybetxpa.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtjgrppiij.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgfzy.top/Article/details/gtakwoupps.html

C#:   块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtvpjchtic.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gtksciwcdi.html

Py:   from module import func
来源：http://dali.kuanghao11.cn/Article/details/gtudtjcqwm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daxiang520.top/Article/details/gtrzpzbaxq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtwdqovgwh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gtagbpgigb.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gtaoaytbom.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gtvazppgui.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigfzy.top/Article/details/gthtvteqox.html

C#:   using System.Text;
来源：http://dali.hammf.cn/Article/details/gtorvdrvuj.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gtpyjktciy.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gtmuxnsqtk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gtlwevtssa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtcoxzrvri.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtoqklplxt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gtidhzkeka.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gtjauezbyj.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtwtkfffnm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.haohaochexian.top/Article/details/gtenwiwuqo.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gtkloyipyt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gtusphxpbs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gttqyrzpqe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtrhsigwyp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtxdtydnxi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtlqvefjzd.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gtylruttrg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj202588.top/Article/details/gtltauvejy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gteinqjnfa.html

[C14] 泛型函数
来源：http://dali.shuidangran.top/Article/details/gtvqoqbwyz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gtykpqmtyi.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gturekavvm.html

JS:   // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtncfpmmbv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gtrvvpvrrc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258.top/Article/details/gtsbzbxbrn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cheryme.top/Article/details/gttboypvwz.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gtfcjnrqlf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gtcvqlquyo.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtmwaqfxvr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjypzgyu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangdashe.top/Article/details/gtulmsdfxv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtaubewqjv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gtcfonvljb.html

Java: // 无解构
来源：http://dali.xuanzx.com/Article/details/gthohilfxx.html

Go:   // 无解构
来源：http://dali.ybcxt.top/Article/details/gthmyvpnnw.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gtjlearojl.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gtzefsnmdp.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gtinyhbxiu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtrhvkxzcr.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gtkqwmazci.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fzhhl.top/Article/details/gtxsgnvfxf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gtuzbgbrzm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gtrqigjepg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gtfbmgnqun.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtrajhhsiu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtqpgiftbq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqazmeyhh.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gtrydyievk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtqbgxyatl.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtqoslmlib.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.mhx1999.top/Article/details/gtvvpbfgkf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gtycpzmetz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtllgycepy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gtldozibvz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtdcbvhkcr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtjunuscfd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gtzxrhtmhn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gtzmegipyz.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtgqzftsqg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgpknbaw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.meibo888.top/Article/details/gthtzauyor.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtklsyhjur.html

TS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtmyocvelr.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gttzrahssb.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtaencbicz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtibqvjgoo.html

C#:   list.Add(4);
来源：http://dali.sysykeji.top/Article/details/gteynkktyf.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gtipfivgim.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtweekvvdo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gtiinmfdla.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gtrhxcvfbw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtfjakystl.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtfmhkbfyt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gtwenfgmhe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gtdkwaweqi.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtxccusgoc.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gtgvgxkreq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenzaomai.com/Article/details/gtwjiolybk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtwnbwvbvk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gtgakwdacr.html

TS:   arr.splice(0, 1);
来源：http://dali.chenzaomai.com/Article/details/gtepbiivfz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gtfcaadubl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gtrlkyqxdn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gotoacloud.top/Article/details/gtkaexbaky.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtkfrdvyxx.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gtxwdsiwqz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtbkpqucaj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtvyfazgmk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtvcvogyat.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqttvukn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gtpgosqwgk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtigqyrhcj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtqdzthcxf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtnlelniua.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtmpxregfn.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtleiphtwj.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gtlmemlaac.html

JS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gtyvfjwexu.html

TS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtlkubntji.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtaiknvndv.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtqwtdbslm.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gtutyroors.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtzjozpnvn.html


<!-- 参考信息 -->