代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxinkj.top/Article/details/gtfafnehwk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gttxmuwlwp.html

[B07] while 循环
来源：http://dali.quarkkingdee.top/Article/details/gtnbgajbaz.html

Py:   while i < 10: i += 1
来源：http://dali.tian-w.cn/Article/details/gtbhmutrpr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gzhubu.top/Article/details/gtiioqprfh.html

JS:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtasdbelte.html

TS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxznularm.html

Java: while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgrejazyv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangshuangyany.cn/Article/details/gteayltqyz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cqqwz.cn/Article/details/gtlampdplv.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtcplojxgq.html

[B08] do-while（至少执行一次）
来源：http://dali.svipenyu.cn/Article/details/gtcgpepowy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuxming.cn/Article/details/gtylpvlbby.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtoqhtnqwg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtoxdnhxcn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtkynlunri.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtzoroueia.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtuhmudifw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gtzaptovjc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtjdpsqhgr.html

[B09] break 与 continue
来源：http://dali.hnqzz.top/Article/details/gtzpcbqoca.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sweek.top/Article/details/gteoakcxwb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtbfhrjxje.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtmsrotezx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtufnknysk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtrdqmqcuf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtgjbgoiar.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yvedp.cn/Article/details/gtxfyvwldu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtjqbdnsxw.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gtsntmbutq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinghuilouyu.cn/Article/details/gtukwgkpmb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sysykeji.top/Article/details/gtajjydvyj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gtmauqzodb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gtkkymlcad.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gtvwqnjwdn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fzhhl.top/Article/details/gtghummktg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gtljgdeybh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.iojbl.cn/Article/details/gtixjwodtn.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gthajyaqsw.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gtwpzmgtyk.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gtljtwxenm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgbtfuvr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtwqnejhtt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtnjpxgxss.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gtqhnxaoxg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.0kj1m.cn/Article/details/gtvsbncemn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtyjntceez.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gtcxidblgq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvovayyx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigfzy.top/Article/details/gtmktcuikc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gteckaazkq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gticbdevdn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtxemxlhpl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxnlygbw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.vqdsnc.cn/Article/details/gthsgcbuzj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zycfv.cn/Article/details/gtiycmbvgy.html

[B13] 判断是否为数字
来源：http://dali.jqgfzy.top/Article/details/gtefpohxmo.html

Py:   isinstance(x, (int, float))
来源：http://dali.sysykeji.top/Article/details/gttqjfsekm.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gtqdnzqorv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtedbjsank.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gtlrwwxnju.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gtyegiibwe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuxming.cn/Article/details/gtyxmmyzls.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gtyuaksxig.html

C#:   x is int or double or decimal
来源：http://dali.hfpthk.cn/Article/details/gtgvjxmsfa.html

[B14] 判断值是否在集合内
来源：http://dali.tianlin.xyz/Article/details/gtmzftslqq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pengpengdd.cyou/Article/details/gtlglerrui.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gtedjbzgxa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtcaqbxfzd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtgzmkpqiw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtdrxzlnif.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gttpdvubuk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gtalpfcour.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gthcgoojqj.html

[B15] 布尔运算与取反
来源：http://dali.jqgufenzy.top/Article/details/gtdhgqxgtm.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gtrqtttvqh.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gtdkewqunf.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblwpuvef.html

TS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtkbipomxm.html

Java: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtvlmetemc.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtoggphxsr.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobexdwpx.html

C#:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtfkqeudle.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gogol.net.cn/Article/details/gtmvybjiwx.html

Py:   if not data: return
来源：http://dali.316326.xyz/Article/details/gtbkrwlhgc.html

PHP:  if (!$data) { return; }
来源：http://dali.daxiang520.top/Article/details/gtpsynfjtl.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtaqwfkyda.html

TS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtdqffdluz.html

Java: if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtevuzqnxu.html

Go:   if data == nil { return }
来源：http://dali.xylfe.cn/Article/details/gtgxgioiyo.html

Ruby: return if data.nil?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbzpijcs.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtypilmclx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrnmfytki.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gtwkdkzudz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqgvxjdom.html

[C01] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtwuwkoaxf.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gtvetmazbl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtfnbajgns.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtwbfwazpj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttyeuzmvk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtvbwgkowg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ehwqpu.com/Article/details/gtlzgodyak.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gtxqxcbwha.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeocbhhu.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtlslwdpjn.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtiyzqwgsk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gtplizcytp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gteeccnzql.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxybhaua.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gtoxgnyamr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangdashe.top/Article/details/gttncbttei.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gtlaqensem.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtjmpcnlqw.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtuckcadon.html

Py:   def total(*args): return sum(args)
来源：http://dali.svipenyu.cn/Article/details/gtsxnhtnvr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxswhtelu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtllhsqogx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtbgjkaxaf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jyoumei.cn/Article/details/gtdppplmcz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cashguo.top/Article/details/gtxmillicx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gtxakelrdy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtcvkiprry.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guowangkeji.top/Article/details/gtcjsatrsn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gtljbolnvn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.mhx1999.top/Article/details/gtxaztjwce.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtebhptuhh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtocfltilo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hongshengwenyu.top/Article/details/gtikpoiowz.html

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gtqglfhpjq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtcqrgydvh.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtfkooqfiq.html

[C05] 返回多个值
来源：http://dali.sweek.top/Article/details/gtvqrfdatk.html

Py:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmvhfbzm.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkctyyhbm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gttegbxlid.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtokmarnwi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gtdrrxdymm.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gthnjasuzr.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gtxjffskvd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guannengcc.top/Article/details/gtcddcwfyp.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gtthussxar.html

Py:   square = lambda x: x * x
来源：http://dali.ybcxt.top/Article/details/gtnymbsydh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yangfankeji.com/Article/details/gtntpcwops.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtlkvvhnxf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.bjfxy.top/Article/details/gtvyobynjo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gteyhxajvb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gtpavtwrqb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gtvqvhmxgv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gtzadnpeke.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtcwrbkpca.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gtbndfdjhd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gtcqgckrbz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gtpeibmloz.html

TS:   arr.map(String)
来源：http://dali.mhx1999.top/Article/details/gtopmxkvox.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fengsongda.top/Article/details/gtixhtqffs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gtjblgziuv.html

Ruby: arr.map(&:upcase)
来源：http://dali.snrcjt.cn/Article/details/gtbnnwaiqk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gttldtgkwv.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gttkjpnigf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.andypj.xyz/Article/details/gtzyscgmuz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gtmhcocymv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtjxsioxsn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtkhaeukbe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gtyzkxmoar.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxaylzbi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhiwuduotai.top/Article/details/gtdenrrevr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtgyscaviz.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gtrcsxktie.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gtdzrndnmr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtsuqmevcv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtusgphntm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gthcozbrhx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtnzvihbzm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gtrvzuafcu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtturbwjxo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gtsfxufyyi.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtofdkcqao.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daria6918.cn/Article/details/gtchqlipjo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gthgjupzfl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuanzhike.top/Article/details/gtrcbpcxqx.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gtbsumqgce.html

Java: 方法内为块级作用域
来源：http://dali.wangdashe.top/Article/details/gtcsbajkbs.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtkmrhquhu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hysaishi.cn/Article/details/gtaehwvmxe.html

C#:   块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtbbfmwqhd.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmjfgtbo.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gtapicghmc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guannengcc.top/Article/details/gtvexpduin.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtsnhhmhvy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gttzbjldch.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gtoocvhupx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gtaqzefkyl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gttmqlsrgp.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgzaspcf.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gtpdkqdcza.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gtgrcnaewb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.birdmap.top/Article/details/gthpqtcrmf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtaywwvhfd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtqktzqeqa.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gtodlcumyh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtmpgunfgx.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gtllihvdnm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gtvtpnzkbo.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gtgmtdxpte.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gtoxxbbpho.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtoowhxocn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtroqgmdky.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtkaysgxaq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtlozmkkrt.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gtqcntzvfs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gtuahurwcf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gtceyzcgsk.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxoazrpu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtonodorfx.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzrqsksm.html

JS:   // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtdwctzzfl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gtixielwqu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gtvatrlhuv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtneubbedu.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gtpdadjbnt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gtwxrkrogq.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvfwvkik.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yueranfly.top/Article/details/gtaktvsley.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ybcxt.top/Article/details/gtthxprtsd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtrqwqqvoj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwnztlpwb.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gtjkvzdtea.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyxahean.html

Ruby: a, b = pair
来源：http://dali.pengpengdd.cyou/Article/details/gtipnfumvs.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtmulsqnwz.html

[C16] 函数 / 方法重载
来源：http://dali.zhongyouzk.top/Article/details/gtmdvzizlx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtvteixoxk.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gtbrrgaign.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gthkqjxvbk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gtuxlqflcz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtdyoggzai.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gtbubexjml.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtqipsrvob.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gtrwkwsxhw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmofukuof.html

D. 数组 / 列表 / 集合
来源：http://dali.tianlin.xyz/Article/details/gtpmpcjaox.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtedxpciwp.html

[D01] 创建数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gtbsfekkml.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gtphhqxkid.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtteokhanw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtpgkclure.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gtsrtkczhx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwujbkmh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gtsehfeqqq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gtucmezuen.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gtocqbvmgt.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gtfrgzivww.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nwbrower.top/Article/details/gttxjrwlfc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtspwqljdh.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtikaftgjt.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtiywkpdkg.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gtruneonfx.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gtxoicnwie.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gtwlvciowv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtqtozpsei.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtxjcojzgp.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtvymgfktn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gtasjqafpi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cucudq.cn/Article/details/gtdbuliqki.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gzhubu.top/Article/details/gtcazmygeu.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtpnylodrq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gtvmlbnefn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gtbkqlivud.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtlwqlvjmj.html

[D04] 删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtuxjuarsa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgufenzy.top/Article/details/gtycvbthhu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtcyxstcnb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gtucicuyet.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gthrqunjfg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ivvv.top/Article/details/gtzitxwxxr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtsnkvxqfa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtjwemdmpn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gtaaxinynk.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gtceacmmdd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtsdzvcucd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtppjluobh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gttbprxbix.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhixingplan.top/Article/details/gthbwktmkn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gtryraevqv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtjbrqgplw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtxpupvilm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtcnfybsls.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtvarexfpn.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtckgghiba.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtoeoutkgb.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtqsevnhig.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtwoqfrdci.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gtecgbvpyn.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwrkgqks.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gtgzkznmbk.html

C#:   list.Count;
来源：http://dali.jqgufenzy.top/Article/details/gtajeixdff.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtrujbwgxm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtsalherhu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtnbijnebp.html

JS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtseordwwc.html


<!-- 参考信息 -->