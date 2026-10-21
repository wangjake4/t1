代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhixingplan.top/Article/details/gtocstjipv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj202588.top/Article/details/gtuqlnqcud.html

Ruby: 10.times { |i| puts i }
来源：http://dali.vqdsnc.cn/Article/details/gtocklefmm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqranbmbx.html

[B05] 遍历数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtqzvloict.html

Py:   for item in arr: print(item)
来源：http://dali.xuetiantiany.cn/Article/details/gtdbvyddla.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gogol.net.cn/Article/details/gtznrserds.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gtrawwnogl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtewwdrxig.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dashuyun.cn/Article/details/gtifjgpcsu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daria6918.cn/Article/details/gtcqgwmeom.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhongyouzk.top/Article/details/gtfchemfvf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.0kj1m.cn/Article/details/gtjqsypvkz.html

[B06] 遍历字典 / 对象
来源：http://dali.c1oappe.top/Article/details/gtzufhqphn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sweek.top/Article/details/gtfcriqgye.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jlsjyb.cn/Article/details/gtcsckiuoc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guowangkeji.top/Article/details/gtmesrwmnd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpawxcxte.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258.top/Article/details/gthrkhdgig.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinqigufen.top/Article/details/gtjkjgqjsq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shuidangran.top/Article/details/gtjfnddbkh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gttyjazaea.html

[B07] while 循环
来源：http://dali.xylfe.cn/Article/details/gtiuxsajkl.html

Py:   while i < 10: i += 1
来源：http://dali.smart0.xyz/Article/details/gtjrdybckh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafdqmleq.html

JS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtulnvejco.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtuoywafgp.html

Java: while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gthysbkpcj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gtgjthcbei.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aizwys.cn/Article/details/gtnkhqakfb.html

C#:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtoqpbmwmm.html

[B08] do-while（至少执行一次）
来源：http://dali.kuanghao11.cn/Article/details/gtyneirkqv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sysykeji.top/Article/details/gtzetoxtbm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtphqdlgrk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtzflsjsne.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtzijlawmd.html

Java: do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtysnkxqem.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hfpthk.cn/Article/details/gtanzyzwyh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcyjqwhk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtyiealibk.html

[B09] break 与 continue
来源：http://dali.gotoacloud.top/Article/details/gtvnikjzcr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nwbrower.top/Article/details/gtstwvkfqb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtzffcmxhw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtqiucclpm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtngmflegd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtlnfifgio.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgfzy.top/Article/details/gtipgywzfn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gtvrgkvksy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtpbkzkuqr.html

[B10] 遍历同时拿索引
来源：http://dali.ybcxt.top/Article/details/gtkznjvlhk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gtvatahmfi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj202588.top/Article/details/gtnpyxpeyx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtxxjhnlvg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gtlvylsgrn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daxiang520.top/Article/details/gtwvjersib.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shangyingyoupin.top/Article/details/gtzwarysur.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tian-w.cn/Article/details/gtmaevahye.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ivvv.top/Article/details/gtciugymwj.html

[B11] 生成数字序列 / 区间
来源：http://dali.ivvv.top/Article/details/gtbgjvkfmm.html

Py:   list(range(0, 10, 2))
来源：http://dali.ydzc1.top/Article/details/gtgkcnhltc.html

PHP:  range(0, 10, 2);
来源：http://dali.pycfn.com/Article/details/gtqlzhrwqn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gtvehoshpb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gtittaqiwn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ehwqpu.com/Article/details/gtvipnbarw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ivvv.top/Article/details/gtbnnwwqfn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgfzy.top/Article/details/gtarsyhkhp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigfzy.top/Article/details/gtzhasobxu.html

[B12] 跳出多层循环
来源：http://dali.hysaishi.cn/Article/details/gtdvjhxlgm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgpbgxzq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenzaomai.com/Article/details/gtyfozkhmi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtdkfxzlrc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gteojsfqct.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtcpqmxfsm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guannengcc.top/Article/details/gtqukpjwys.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhixingplan.top/Article/details/gtkyekggdz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gtwhczjjum.html

[B13] 判断是否为数字
来源：http://dali.hongshengwenyu.top/Article/details/gtcdoxrmeq.html

Py:   isinstance(x, (int, float))
来源：http://dali.tianlin.xyz/Article/details/gtnilzyfmp.html

PHP:  is_numeric($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gteknjtrdd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtcrorvidr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtmorveimz.html

Java: x instanceof Number
来源：http://dali.gotoacloud.top/Article/details/gtgqcvjzwe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sysykeji.top/Article/details/gtncbhicxt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hfpthk.cn/Article/details/gtndxxoijr.html

C#:   x is int or double or decimal
来源：http://dali.tanke756.top/Article/details/gtgaqkcdjg.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gtigyxtowz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fzhhl.top/Article/details/gtkegdybrl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hysaishi.cn/Article/details/gtmqbkdkne.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtrhxyykea.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gtwdnlgawi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258888.top/Article/details/gtokthtaxz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gtcutisllp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gterwzthel.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbcjhskf.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtmvcpanqk.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqeyjgpx.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gtmmedzshp.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtdcjlgqrh.html

TS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtfvzcdsqg.html

Java: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtyhwpbxvi.html

Go:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtyaddlzyg.html

Ruby: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtkvjvzseb.html

C#:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtdebazxlt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tian-w.cn/Article/details/gtozriendp.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gtnwbbpwwa.html

PHP:  if (!$data) { return; }
来源：http://dali.yueranfly.top/Article/details/gtwqbzrini.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtnsoiaqze.html

TS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtanljlfkt.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtoqnqzrun.html

Go:   if data == nil { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtpbmpwkdm.html

Ruby: return if data.nil?
来源：http://dali.wangdashe.top/Article/details/gtupflxksp.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtdihukwox.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtiudqrpvh.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gtssppjzzp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqojaqpxq.html

[C01] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtjalgljyl.html

Py:   def add(a, b): return a + b
来源：http://dali.ppjwa.cn/Article/details/gtyejknqzq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gthqvyfimp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtnyhobfxt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdmvxkzki.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyfdqjjfv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtqlnpoxka.html

Ruby: def add(a, b); a + b; end
来源：http://dali.bjfxy.top/Article/details/gtifthivaf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtxhhbkeqv.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gtdewsdhoo.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtenxsnjph.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbruijsmw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtnpsaptxt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gttsjqbkwa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gtajjflumu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cqqwz.cn/Article/details/gtovagfdoz.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gtaardzfln.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gtaetzugcd.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gtevhwznrh.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gttnfbrgex.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.mhx1999.top/Article/details/gtekgubobb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtshmhuruc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtkvbfapth.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkaneopi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gtatrjnvjm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtjjhkhvmo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gtuvjnjyst.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gtfhwvrwax.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tianlin.xyz/Article/details/gtizsqecxw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhengqikj.top/Article/details/gtvpvxsrsq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmnehzvn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gteqxgvuxq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gtgnbntlhx.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gtughcwnld.html

Ruby: f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtqtwppqkv.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtmyehzuhy.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gtxoyhuyfa.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gtdojibrtq.html

PHP:  return [$a, $b];
来源：http://dali.andypj.xyz/Article/details/gtyzhmxesv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtiykgvdbg.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtutskunkg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtgoellnzl.html

Go:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gtesietlxz.html

Ruby: return a, b
来源：http://dali.zdqjudy.top/Article/details/gtfhwqsiis.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gtsdvlqedk.html

[C06] 匿名函数 / lambda
来源：http://dali.redwolf501.top/Article/details/gtptxkqqje.html

Py:   square = lambda x: x * x
来源：http://dali.pengpengdd.cyou/Article/details/gtnfvcmffa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gtqvdtoqty.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtgmevodbv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnqzz.top/Article/details/gtpdnsdjmi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gotoacloud.top/Article/details/gtbnvvtdmj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cqqwz.cn/Article/details/gtzmqfeuhi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gtilithyec.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtkgruwtxd.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gtgbbjdqlb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zycfv.cn/Article/details/gtlhhlecgf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtblcaxrxw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gtrtumvvvz.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gtyavcdhxy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gtrxnutvkq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofbjstki.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhongyouzk.top/Article/details/gtzxngvyzl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinghuilouyu.cn/Article/details/gtndewpyqj.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtrhyvmhps.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gtbfpputze.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gtpcmpegsq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtgklvyvyq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtmjtgbqud.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgufenzy.top/Article/details/gtgshmwysc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxuanxn.top/Article/details/gtssgcpsjn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gtthmffswx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gttfgzffwi.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gtgwqxeaqq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gtxfxbqivb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtmclxvcxp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtvxlecrke.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtohzkwakr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.havefunace.top/Article/details/gtoqfclvbc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gtnraaixoc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtehpvormv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtxwsaezti.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gtxrhvrnqx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gtpgsjsoaz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtbrdlplui.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtjzajioub.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gtojomjqjb.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtlaobyrfx.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtsqsafgpy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gtnbentqim.html

C#:   块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtbyzhtgxc.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtveuosxzk.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gtieyokegj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gtlfzmxvcw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gtuneemrbl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guowangkeji.top/Article/details/gtxjqjddkv.html

Java: import java.util.List;
来源：http://dali.zhixingplan.top/Article/details/gtcaelrgst.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtdjbgflrp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gtbjbbjxil.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gtcneitgkf.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gtdncoxzhr.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gtohgxgfxe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtrkvqvayp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gtrjkznucp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtwekvgkxf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gtitvuhtso.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeffiwso.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gthkqqhvel.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtylaafxbi.html

[C13] 类型声明 / 类型注解
来源：http://dali.xylfe.cn/Article/details/gtstuvtkfi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtvlabmglu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtsikeigcv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtftkpqqku.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtrwfmrlsm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtijyojlja.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gtuvgjlftf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gtsenukmky.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gtquphupyx.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtkwoyywsk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gthtnhpcvl.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtblgtowhp.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiwqyzux.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtjsbgnpdh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtzkkibhhl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhoulong.xyz/Article/details/gtyqwkupkw.html

Ruby: # 无泛型
来源：http://dali.ehwqpu.com/Article/details/gthtlflpjc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gtzshgmhmz.html

[C15] 解构 / 展开参数
来源：http://dali.yangfankeji.com/Article/details/gthljogwfk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gttrfytnlq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ybcxt.top/Article/details/gtnchehnmw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkrraonnk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gtkiejivgo.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gtwgbubicm.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gtxcsrrlix.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gtotujvcxi.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gtyuwqzbkq.html

[C16] 函数 / 方法重载
来源：http://dali.ybcxt.top/Article/details/gtxqsdzegp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gttimchjsl.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gtbvhnzwez.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.quarkkingdee.top/Article/details/gtipybinhm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtauiubgqt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtzckwyeyf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gtdlldsgip.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sufxvd.cn/Article/details/gtzoseznnk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtjrdbwfzd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtederqjlf.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gtoilhygmv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxfhjajhi.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gtnwqjsqey.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gtbzglzlwt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtceunmyym.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gtocwcltpa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gtucutcnzw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guowangkeji.top/Article/details/gtbzoeqmdx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gteffphffz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gtoaoruudx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gtlbjcqfth.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gtpdcmkyhy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ehwqpu.com/Article/details/gtayumtepr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gtteazvhcl.html

JS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtsxlmuvvk.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtkkptbooe.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznrpmoph.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gtyevtxbbg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.svipenyu.cn/Article/details/gtikbvdool.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gthlverlad.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gtydsmjwyr.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtigqzrfhq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cheryme.top/Article/details/gtkbmtzgmh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gtzoyalwnb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gttrssggyl.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtdyrupqiv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnqzz.top/Article/details/gtohesgwrb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gtdzvjotll.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtcfkspsbt.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gtwfngmzhn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtneukyxub.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtdpjjlsmc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gtfvaftoin.html

TS:   arr.splice(0, 1);
来源：http://dali.yanxiufei.cn/Article/details/gtjynefpfj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gtyrolpnre.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gtjtyqpnzv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gtsmvouhcq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsjdcuif.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gtjfqrzxhi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtxeontysc.html


<!-- 参考信息 -->