代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtsqrayqxr.html

Py:   for item in arr: print(item)
来源：http://dali.wangshuangyany.cn/Article/details/gtolqkmmfc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenlongwang.top/Article/details/gthabfnhsu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gtooqrdisi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tianlin.xyz/Article/details/gtrjvzugqc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hywenlv.cn/Article/details/gtlimohhvi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigfzy.top/Article/details/gtlptkievp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sufxvd.cn/Article/details/gttewrbvcp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yvedp.cn/Article/details/gtrtpjwluc.html

[B06] 遍历字典 / 对象
来源：http://dali.vqdsnc.cn/Article/details/gtaxhpdhod.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gtdpgmctnk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhengqikj.top/Article/details/gtyccxooxr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gtiqrvzyig.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzixawgqc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hnxiangtu.top/Article/details/gtbxpfzekc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yongpay.top/Article/details/gtfypnuulb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tanke756.top/Article/details/gtqfsinmnr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtjfmydxbl.html

[B07] while 循环
来源：http://dali.chenjidiqi.icu/Article/details/gtqxlpwfty.html

Py:   while i < 10: i += 1
来源：http://dali.tanke756.top/Article/details/gtzmrgyplb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtghvoxmnp.html

JS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtscheeunk.html

TS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtszguwuhf.html

Java: while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gttshbtqqa.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.snrcjt.cn/Article/details/gtiqfcanod.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gthtcivemj.html

C#:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtsjrfyqnj.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gtbnmuulfz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sxryk.cn/Article/details/gtydgppuxw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sysykeji.top/Article/details/gtqjbpejaj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtwlqbpgih.html

TS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gttwjjhoka.html

Java: do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtxkitklvz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yongpay.top/Article/details/gtdjmcwexi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sweek.top/Article/details/gtrvafzclw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtwfhpezdh.html

[B09] break 与 continue
来源：http://dali.shangyingyoupin.top/Article/details/gtzzpvgzkb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuxming.cn/Article/details/gtxdltecds.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtuatxbtkz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtdplmopmh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gtidvjdglp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gttyzrsuwi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cheryme.top/Article/details/gtbuebtsbb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuanzhike.top/Article/details/gtiryvryym.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtnldnudzf.html

[B10] 遍历同时拿索引
来源：http://dali.fzhhl.top/Article/details/gtfnuvxrsj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.redwolf501.top/Article/details/gtjbfeoxdf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258.top/Article/details/gtoyvabyjt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtwalnufsu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtcritelyx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hfpthk.cn/Article/details/gttuwspfpv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuetiantiany.cn/Article/details/gtfwkoaejg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gtyhxoqapy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuanzx.com/Article/details/gteszpiekh.html

[B11] 生成数字序列 / 区间
来源：http://dali.cqqwz.cn/Article/details/gteftkferm.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gtrnejbgmu.html

PHP:  range(0, 10, 2);
来源：http://dali.wangdashe.top/Article/details/gtnjecmthu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gtxtpfxmgb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtfcgdewnm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnqzz.top/Article/details/gtupzmaked.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.kuanghao11.cn/Article/details/gtbpnjdben.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslwxsmly.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aibaodan.cn/Article/details/gtmvpyngpk.html

[B12] 跳出多层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtqpofwxwc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jiagoushi.top/Article/details/gtqyqnddyk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gtsvmgyvzx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gttlcaefqc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdvdkbrc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtgcyuazir.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shzxlz.cn/Article/details/gtlzgfewlt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guannengcc.top/Article/details/gtcmuccksf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gtpkszroyg.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgwctbpl.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtddhiqssd.html

PHP:  is_numeric($x)
来源：http://dali.ivvv.top/Article/details/gtnazjsivw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthquckziv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtsxejsdqk.html

Java: x instanceof Number
来源：http://dali.yueranfly.top/Article/details/gtcijqzzeb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbufkcmup.html

Ruby: x.is_a?(Numeric)
来源：http://dali.9152youxi.cn/Article/details/gtwuzzgtkl.html

C#:   x is int or double or decimal
来源：http://dali.zhiwuduotai.top/Article/details/gtcccragqb.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtmscvutkz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxabnzdsi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtrftrxxdp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmbkocma.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gttqimsmis.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtgpzwoqbi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gtjbnlqknu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuanzx.com/Article/details/gtqsamlkzf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtyztvbrrx.html

[B15] 布尔运算与取反
来源：http://dali.hywenlv.cn/Article/details/gtyrdyuwsc.html

Py:   a and b or not c
来源：http://dali.yongpay.top/Article/details/gteiicvnkt.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258888.top/Article/details/gtzuhcrqsp.html

JS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtqmpyquuc.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtumlygtvt.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtlbsrauix.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtqxkkxfyg.html

Ruby: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtmypjosck.html

C#:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtehkwvixn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ivvv.top/Article/details/gtswxhnnqy.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gtpyychvda.html

PHP:  if (!$data) { return; }
来源：http://dali.smart0.xyz/Article/details/gtbritgjiy.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gthhdacmdm.html

TS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gtzqsksipa.html

Java: if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtyysuphvr.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gtvyxlyqan.html

Ruby: return if data.nil?
来源：http://dali.zycfv.cn/Article/details/gtogtpsegx.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtetcijqfe.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmbhkrkip.html

C. 函数与作用域
来源：http://dali.nanxuanxn.top/Article/details/gtpuorfrgf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmuyugbzj.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtifwmwmqg.html

Py:   def add(a, b): return a + b
来源：http://dali.ppjwa.cn/Article/details/gtiopcjiys.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtwqotuwac.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtkiuxozda.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gttxyxnmxw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtmaxnhfbq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtunajtkxg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gtzijzcxcm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqgkbvbzy.html

[C02] 默认参数
来源：http://dali.redwolf501.top/Article/details/gtzoktlcdr.html

Py:   def greet(name="World"): return name
来源：http://dali.ybcxt.top/Article/details/gtdgmuqnod.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fengsongda.top/Article/details/gtakxnhbjw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtfokjuwtb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtglpjxpnq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.316326.xyz/Article/details/gtugorulqi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cheryme.top/Article/details/gtkxrswlzf.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gtfwtcdtjh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yvedp.cn/Article/details/gtzqijuxhr.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gtmikvptct.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gtjhjxkist.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjogodkzu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtehgjglwg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtdaeuwuue.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhoulong.xyz/Article/details/gtxvuelhfj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gtrymwongl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gtomxzzsqj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gtmreffhbq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gtkfblfkyh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gtttbecqhu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gtbvhyieup.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpvzmbcxj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtzwnfrnfv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gtphgqsian.html

Go:   // 无：用配置结构体参数
来源：http://dali.tanke756.top/Article/details/gtidfqxwld.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtudjiionk.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtwxrwmrff.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gtagkvhhhh.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtaovkvzsg.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gtlkdzkmkj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtvoqdxtnr.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtolnhqukp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangtech.top/Article/details/gthrcgqnre.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gtrgebbont.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtixwghxnh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fengsongda.top/Article/details/gtohdlweae.html

[C06] 匿名函数 / lambda
来源：http://dali.hywenlv.cn/Article/details/gttvseivlx.html

Py:   square = lambda x: x * x
来源：http://dali.bjfxy.top/Article/details/gtaxdndpxn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuanzhike.top/Article/details/gtigtefqjw.html

JS:   const square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gtqpnbxjgr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hammf.cn/Article/details/gtogqiamou.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nwbrower.top/Article/details/gthxjetrln.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gtqlcaezby.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shzxlz.cn/Article/details/gtwvglozya.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtcugkqoxn.html

[C07] 把函数作为参数传入
来源：http://dali.zdqjudy.top/Article/details/gtmwtjjbon.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangdashe.top/Article/details/gtfttuhjsb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtpbnndwqz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jyoumei.cn/Article/details/gtawxdoveu.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbicshblh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aizwys.cn/Article/details/gtbnzubjhz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jianghu66.top/Article/details/gtdbkkbaik.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhixingplan.top/Article/details/gtirdqwwef.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yvedp.cn/Article/details/gtezmowzsw.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gtizewlejk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yanxiufei.cn/Article/details/gthvljoqed.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gtrqdzgisi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtompmvibc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtdxxnfmpn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gtpnuowelj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gtfopgvbaz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aizwys.cn/Article/details/gtyaukabgz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxoqmyrnv.html

[C09] 递归
来源：http://dali.tanke756.top/Article/details/gtqwdgkyru.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtdvxtxrax.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtdtxzelje.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtafvpwcfr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtguqnalnu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtdlzzwsup.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtehkhrhcf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gtchvjjtws.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gthbwzxcpm.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtdzrhfwgb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gtevfnveqx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj202588.top/Article/details/gtghsnhrtf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gtdgknvtuz.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gtswigmsyv.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gtkfcomztx.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtztrcokgl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gtjuycfmhg.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gttlzomqtr.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gtipvtjqve.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gtuvkyatwg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pycfn.com/Article/details/gtdtaqzhoa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gttbjldney.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gtmntthhkf.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gtxdrigbts.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.redwolf501.top/Article/details/gtaukufxlq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gthzexauyj.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gtcdrrcwhz.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gtkxahnkgc.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gtsvjgjmcb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gtsfgitsch.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtxciycghi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtnqwqsjfx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gtqzrdeliz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ehwqpu.com/Article/details/gtpiynityx.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gtuzgutdpv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gtcghtvatg.html

[C13] 类型声明 / 类型注解
来源：http://dali.andypj.xyz/Article/details/gtojptsfxl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqcihnff.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gturfrfdmw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gtswnxsfmh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtroommncr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtxsexoinr.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtvfsrynxv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gtlrzqtjbm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gtzomuthto.html

[C14] 泛型函数
来源：http://dali.zhiwuduotai.top/Article/details/gtdbrypiym.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcmbdvyb.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtdgnpfgbi.html

JS:   // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtpigrbrjk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gtfdlzabko.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtianedhmy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gtfzmeorjn.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtjcdktwpy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gtxykoyvkz.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtuycrbykn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gtadgfrmle.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zdqjudy.top/Article/details/gtuhgjkfrc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtdkgdjsei.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtbhpixiey.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gtdvemnufd.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gteavtmuxz.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gtfuqkkjol.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtvpoqcbhw.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gtrbsapamu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoydjdkjn.html

PHP:  // 无重载
来源：http://dali.smart0.xyz/Article/details/gtgrnrapgd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gtbvwttbdo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gtagxomhbb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gtmwjdkxao.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gtawzvyyqw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sufxvd.cn/Article/details/gtjgkfnlhb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258888.top/Article/details/gtbgaojuse.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwbhjmzob.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gthlhetnnp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtswnpmcgg.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtfusvalgy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuanzx.com/Article/details/gtpvdzvprl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuxming.cn/Article/details/gtazcyskix.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtswgcrlzb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtxniatyio.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtaxmrfrvq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtvaqetszk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gtvwqffmvc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gttmpzuckl.html

[D02] 追加元素到末尾
来源：http://dali.9152youxi.cn/Article/details/gtijrsxwxg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtbvqgfdhl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.haohaochexian.top/Article/details/gtdpmocqvv.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtjkmjzhjt.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtsbynscpn.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gtkcwnggpc.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtopnmqapj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtghxzyqrf.html

C#:   list.Add(4);
来源：http://dali.dashuyun.cn/Article/details/gtqikakhxo.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gtzxwcjccy.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxinkj.top/Article/details/gthqhuymcx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtydudinyb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gtkrporzth.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gtjzuqezwn.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtpijzivza.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtbobnhzvb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gtxynebmma.html

C#:   list.Insert(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtwwibsnwy.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtkoleyzur.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gtqyilzyyf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtqmcnzdwl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258.top/Article/details/gtpuzcpmof.html

TS:   arr.splice(0, 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwomaxhq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gtjnthrhlp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gtfzmgedmp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.mhx1999.top/Article/details/gtxugfvatb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gtavjqywtq.html

[D05] 访问与修改元素
来源：http://dali.vqdsnc.cn/Article/details/gtkswlxnjs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtwpetvhyb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtmxvsaqhz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtaaoplwxx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gtbksldpst.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gtjtxsskvr.html


<!-- 参考信息 -->