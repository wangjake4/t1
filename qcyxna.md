代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guowangkeji.top/Article/details/gttkurmivz.html

[B06] 遍历字典 / 对象
来源：http://dali.yj202588.top/Article/details/gtuafaooxe.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gtntvwqzdg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258.top/Article/details/gtvliikfrs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtzgjnlilj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gtztatpzyn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxhssnlla.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.redwolf501.top/Article/details/gtjxbhypdm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.havefunace.top/Article/details/gtwksybxea.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.0kj1m.cn/Article/details/gtppmjndyg.html

[B07] while 循环
来源：http://dali.smart0.xyz/Article/details/gtfsfntgbi.html

Py:   while i < 10: i += 1
来源：http://dali.nanxuanxn.top/Article/details/gtxnmsxxmx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tian-w.cn/Article/details/gtamimxmzp.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtpcxtvlfu.html

TS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtakqeiecu.html

Java: while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gthhcaauqi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gtmxkkyhrl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.kuanghao11.cn/Article/details/gtsgjnayht.html

C#:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtbcarwmol.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gturkjgzbd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.mhx1999.top/Article/details/gtlumugasb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sxryk.cn/Article/details/gtkbfmfbnv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtgaswbasl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdgoiwtz.html

Java: do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtvvinomrl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnqzz.top/Article/details/gtczxcxbws.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gtaebluujz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjjqqrin.html

[B09] break 与 continue
来源：http://dali.zhongyouzk.top/Article/details/gtidedgxox.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shzxlz.cn/Article/details/gtqzrabeld.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtdvnhwayt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gthlpylxau.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtwmqtmjyx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtjcghyuax.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gtcgfbasuq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ehwqpu.com/Article/details/gteyzcttmk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtrgibhvwx.html

[B10] 遍历同时拿索引
来源：http://dali.jqgufenzy.top/Article/details/gtueufpbej.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258.top/Article/details/gtahsdznbe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gtidzzhhqj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gtiavlfixb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskmkjbsh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.redwolf501.top/Article/details/gtyhszzywj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jlsjyb.cn/Article/details/gtccxtquix.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ppjwa.cn/Article/details/gtmbbahind.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.316326.xyz/Article/details/gtwnugwvei.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gtxjwxfmiw.html

Py:   list(range(0, 10, 2))
来源：http://dali.aibaodan.cn/Article/details/gturbfyfhh.html

PHP:  range(0, 10, 2);
来源：http://dali.hywenlv.cn/Article/details/gtzebwhdmm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gtwzzjuqqq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gttvwqujdh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tanke756.top/Article/details/gtsqqtbwhw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jianghu66.top/Article/details/gtmkreszoq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gteptoljhi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gteuuilqxr.html

[B12] 跳出多层循环
来源：http://dali.mhx1999.top/Article/details/gttxqsdukz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuxming.cn/Article/details/gtrwfloaxx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gtaynrxzqp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtmlebavnz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtybsrxcog.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtwhrtozpw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuanzhike.top/Article/details/gtoaiphaoy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sysykeji.top/Article/details/gtutpnxmpe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cdnleiting.top/Article/details/gtmjofdcrw.html

[B13] 判断是否为数字
来源：http://dali.ivvv.top/Article/details/gthycrvxdb.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhongyouzk.top/Article/details/gtryyzzxjk.html

PHP:  is_numeric($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfznmwur.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtxwlzeifa.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtnouinwyh.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtbfgjsxbn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hongshengwenyu.top/Article/details/gthtvcpqnu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hongshengwenyu.top/Article/details/gtbcitrurx.html

C#:   x is int or double or decimal
来源：http://dali.iojbl.cn/Article/details/gtyuircsoj.html

[B14] 判断值是否在集合内
来源：http://dali.tianlin.xyz/Article/details/gtwqnxkatp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sweek.top/Article/details/gtyvlnjibj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gtemmghsxh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gtijsjupdi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtbggzjrgx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yvedp.cn/Article/details/gtslrhpxdo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gtxhsouiop.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtpwmcxzov.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvmtqgim.html

[B15] 布尔运算与取反
来源：http://dali.tanke756.top/Article/details/gtlevxmcit.html

Py:   a and b or not c
来源：http://dali.chenlongwang.top/Article/details/gtzsnlkuvz.html

PHP:  $a && $b || !$c
来源：http://dali.shuidangran.top/Article/details/gtsnqonvpo.html

JS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtynhduxpp.html

TS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gthgowachb.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtizisqrii.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gthdmtfbap.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtuxgsyzvz.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtxqrymzvb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtnvwmsrsm.html

Py:   if not data: return
来源：http://dali.cqqwz.cn/Article/details/gtnreqxacq.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gtgnztogdr.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtrsyqdfts.html

TS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gthldamdoo.html

Java: if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtukvedffe.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gtohscqvzx.html

Ruby: return if data.nil?
来源：http://dali.yangfankeji.com/Article/details/gtwdnxwlaj.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtfvlnjbel.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrgdnpvx.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gtmklrnhpz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrldwjfyl.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtwqujceur.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtzshiuxyb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhgfxurb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtegylsrqf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtfrfubvos.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtivtrjplc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhengqikj.top/Article/details/gtlhppesty.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cucudq.cn/Article/details/gtkoyivwjh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtbrjkccan.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzawzaupu.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gtodebuvup.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gtmwtwbizc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtasamczey.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvwxgdcta.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.quarkkingdee.top/Article/details/gthbnqyijo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gtpwkeewhe.html

Ruby: def greet(name = "World") = name
来源：http://dali.cashguo.top/Article/details/gtvdtjmrec.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuanzhike.top/Article/details/gtnnodkewl.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gtulsmqkht.html

Py:   def total(*args): return sum(args)
来源：http://dali.tian-w.cn/Article/details/gtwaqozwpg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.quarkkingdee.top/Article/details/gtdcidzujl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gteamiicbs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtrlcqlhyr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtwoswsuik.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gtwvqasbvc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gtjgmbdoch.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gttjesrbod.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sweek.top/Article/details/gtglcotmga.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gtviwupcks.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ivvv.top/Article/details/gtvltvfhmt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtplzzdhsn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gtltjnkiwn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gtyupexdxy.html

Go:   // 无：用配置结构体参数
来源：http://dali.vqdsnc.cn/Article/details/gteczzqtfv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtojdawvfm.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtrvzbyddz.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gttcqywhut.html

Py:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgbilgyg.html

PHP:  return [$a, $b];
来源：http://dali.hnqzz.top/Article/details/gtzrcyodvr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtecbjaked.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtdrgrmcmn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigufen.top/Article/details/gtpvzzcany.html

Go:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtvlyksrzg.html

Ruby: return a, b
来源：http://dali.shzxlz.cn/Article/details/gtrywszwjf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmebesdfb.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtclvfsybi.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkuiwswc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gtxlsltvps.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtayqujuhi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpusfmoy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gthykphbew.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtfqazikgg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigufen.top/Article/details/gtjusbdhah.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiishghby.html

[C07] 把函数作为参数传入
来源：http://dali.jqgufenzy.top/Article/details/gthohivmyp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gtuhurbkgb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gtwwlcvthf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gtoqigbkmt.html

TS:   arr.map(String)
来源：http://dali.yj20258.top/Article/details/gtvnhmefbu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gtqypkluvq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gtodpmqetx.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gtlkcjtmih.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.9152youxi.cn/Article/details/gtsgflldlz.html

[C08] 闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwhlsdeg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gtnznebznl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmyuezvki.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtjpjdynjg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtcncezyle.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gtwpmcscid.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gtlqgzeybh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gtyqvmlhob.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtvadbhgtw.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gtdykdomwp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtilikdcuz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtrvgnqawe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtbgsxkzlr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtmpntaogl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtwinmfwcq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gtmoaibcgq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtbdqvahla.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.kuanghao11.cn/Article/details/gtgfdgfhho.html

[C10] 变量作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtooufdgun.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangdashe.top/Article/details/gtqtftxixp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.havefunace.top/Article/details/gtjhhagnql.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gtjmkwechx.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gtqoomtrds.html

Java: 方法内为块级作用域
来源：http://dali.xuanzx.com/Article/details/gthggaxwfo.html

Go:   花括号块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtohbioana.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gtjxjmfyrn.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gtcgcwdcbq.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gtkbqicqme.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gtisexwkwr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvazbvhvq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtwfswldvl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daxiang520.top/Article/details/gtipjmburr.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtnewprtmw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jyoumei.cn/Article/details/gtoqrjnniz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gtxhyfknmu.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gthbibmlxo.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gtfpbikbwf.html

Py:   (lambda: print("run"))()
来源：http://dali.ppjwa.cn/Article/details/gtifwgbnxv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgfzy.top/Article/details/gtzuyrrfia.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtjmwduhza.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtkdloabes.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ppjwa.cn/Article/details/gtbzunknxn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gtntqghtev.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtntdccltg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtezrjlbvn.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gtcahvkujx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.snrcjt.cn/Article/details/gthiyxujqb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtdrghqtii.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtnfixadtd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtcofheiep.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtfpbswzbf.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gtmcsrpdbr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gtgajzzqps.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xziqi.cn/Article/details/gtocbeclsj.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gtfdingpaq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj202588.top/Article/details/gtsgexmzyi.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtevhvblvb.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtuheruhpl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gtdtujwfvb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gtukgioujn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmavfaeck.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtblgtgxyt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gtgxlfpqld.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtghnwlyhk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtjjjfuibu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gtmrlwlxsq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtefgjscwe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gtbnecyssf.html

Java: // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtbrfnsryg.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyddeimh.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtsvfytuso.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gtoxufzgqd.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gtppljijyk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gtpbsoolgn.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gtdylzdvpu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnqzz.top/Article/details/gtqkabzwmn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gtxltwdhew.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jyoumei.cn/Article/details/gtarkdcwrq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gtkpqclphh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gttkvmfzio.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gtshegqnvj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfbiozukf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gtnsguerhy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtvupwzkqe.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtsyhzcqdp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gtnezlbhap.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gtayfctrtg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtvwjchvyk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtinowugsc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtfqhhxyii.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gtbqciagnf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gtthhstrcy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gtytukfpst.html

[D02] 追加元素到末尾
来源：http://dali.yvedp.cn/Article/details/gtdmxyzdoc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gtwcvftcan.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlggdunp.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtwwpuoley.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtkwsvltem.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtonhhmmga.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnytujva.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gtoyyhmsxm.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gtyxhcbcnd.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gtjieyvjqz.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gtdcumdmqq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gtdoebxakd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gtptnfylrq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtpozqvgqj.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtpyrsbkpm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtbwbguebq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gtqaauoizq.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gttkxfokqh.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gtyxmccteb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtaioqmnwe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gtvzllnjni.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdrjvnmy.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtbqpzjuix.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gtaqucsnwq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gtyjtnknwj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gtlrxmimxi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtnywgjxnl.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtbentjrau.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtpeujwmzq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtryzpypeb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtdgbuhbte.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtfuapoixs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjntjokw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtlbuoyvio.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtxwrlhuhh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sweek.top/Article/details/gtpfdlabdo.html

[D06] 数组长度
来源：http://dali.cheryme.top/Article/details/gtxvatltgt.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gteshxsdeu.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtvnreyend.html

JS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gttsvgwynt.html

TS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gtsdppmhju.html


<!-- 参考信息 -->