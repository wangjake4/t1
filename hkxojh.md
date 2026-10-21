代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gtypzqalde.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gtzkgzvinr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yuxming.cn/Article/details/gtatbhwkrs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzigkohlj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yueranfly.top/Article/details/gtprxktcou.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xinyue.icu/Article/details/gtiyngxglr.html

[B07] while 循环
来源：http://dali.gogol.net.cn/Article/details/gteoysjwlw.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtbrrvapnp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtbqvkxmhn.html

JS:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtmlfnpbrm.html

TS:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtgofwbjlg.html

Java: while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtyjbvarhn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.316326.xyz/Article/details/gtrhdgpqyg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigufen.top/Article/details/gtflvbxlra.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtgarfnuds.html

[B08] do-while（至少执行一次）
来源：http://dali.guowangkeji.top/Article/details/gttxghjjpc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hammf.cn/Article/details/gtpedznlnb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xylfe.cn/Article/details/gtieqelfrq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtxpptaqgf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtpyyvgdry.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtmsxdzuqp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yonumen.top/Article/details/gttguauioi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhoulong.xyz/Article/details/gtnigmbyyi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtzugakonv.html

[B09] break 与 continue
来源：http://dali.kuanghao11.cn/Article/details/gtsgydxnln.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hongshengwenyu.top/Article/details/gtasrrbklk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtodsfryft.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtnbotrjlk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtobzebnze.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnylssrnn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gtxttpimdh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hywenlv.cn/Article/details/gtcnofnjiq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtnokmwruu.html

[B10] 遍历同时拿索引
来源：http://dali.snrcjt.cn/Article/details/gtujnbxgks.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cashguo.top/Article/details/gtfdajdrkt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ppjwa.cn/Article/details/gtmybahbzt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtszyvclkg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtyogwcjne.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gtidvwqajg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gtltapxohb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gtneouwlie.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gtrftquodz.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifochydi.html

Py:   list(range(0, 10, 2))
来源：http://dali.c1oappe.top/Article/details/gtnyabiezy.html

PHP:  range(0, 10, 2);
来源：http://dali.xziqi.cn/Article/details/gtgrhqefso.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtivjxcbui.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gtgkcpcblk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gtfkejwejb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnxiangtu.top/Article/details/gtfcjlqvsa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gttrrbrtbw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanslaihr.html

[B12] 跳出多层循环
来源：http://dali.dianchejie.cn/Article/details/gtwxjttift.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yanxiufei.cn/Article/details/gtcvzddvxp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dianchejie.cn/Article/details/gtxowpefzt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtxnhmihyd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtzoxlknya.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gtksbyqaav.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tian-w.cn/Article/details/gtykbiwzcu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hywenlv.cn/Article/details/gtopjsqeoy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gtipumdklg.html

[B13] 判断是否为数字
来源：http://dali.yj202588.top/Article/details/gthdmkcovn.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhengqikj.top/Article/details/gtvqsfqjmf.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gtkirmrmbd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtxhzvctts.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtarwyskmd.html

Java: x instanceof Number
来源：http://dali.hywenlv.cn/Article/details/gthcznsrxq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhoulong.xyz/Article/details/gtntuxzxzb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenlongwang.top/Article/details/gtyjojzuuw.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gtnwyzqytz.html

[B14] 判断值是否在集合内
来源：http://dali.ydzc1.top/Article/details/gthpdizgzo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.vqdsnc.cn/Article/details/gtdgmrxciw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jlsjyb.cn/Article/details/gtpwtrgrpb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtjhnravvr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gthgerzjle.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtijacudak.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gtrmoxudel.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtiewrzstg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtelozjycj.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gthgwvpdjo.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gtppjnzeov.html

PHP:  $a && $b || !$c
来源：http://dali.nwbrower.top/Article/details/gtwjtctyfz.html

JS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtpxehnhzz.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtigawtphi.html

Java: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtubbaaocd.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtdifalhbr.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtzxbgjrki.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtvnilzggi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gtacixqhei.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gtwwwsdwka.html

PHP:  if (!$data) { return; }
来源：http://dali.yanxiufei.cn/Article/details/gtepypdgry.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtzjconnox.html

TS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtcrqakoov.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtlwydtcgb.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gtaakyotti.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxerzkyot.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtcwmeyhqk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtgprcpmrl.html

C. 函数与作用域
来源：http://dali.daria6918.cn/Article/details/gtvkfwvypp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxpsykaxh.html

[C01] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtbuvkynri.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtjurnumvv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtsuirpppd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtnipyyxrp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtuzsqfvuq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtuidlatta.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuanzhike.top/Article/details/gttvxbivhd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gtwuefvxjf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtayfmnjvp.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtwrkuzuxx.html

Py:   def greet(name="World"): return name
来源：http://dali.iojbl.cn/Article/details/gtwsokmgen.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gtxkjsejuc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtntkrecwb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtserzqiot.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gthwhmriuy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gtnchsxspj.html

Ruby: def greet(name = "World") = name
来源：http://dali.shangyingyoupin.top/Article/details/gtfafymoew.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtorvvnxct.html

[C03] 可变参数
来源：http://dali.andypj.xyz/Article/details/gtpiqihrxp.html

Py:   def total(*args): return sum(args)
来源：http://dali.quarkkingdee.top/Article/details/gtxaspbesn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gtmkthinvd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtqnekfqxq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtkfvhqsxk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gtzavwcivo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.redwolf501.top/Article/details/gtwdgglwsu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gtznjdepfh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gtcgmvzuhu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.9152youxi.cn/Article/details/gtqafxoydi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangdashe.top/Article/details/gtoqqvbcye.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtgaorctvp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtdlpukqnd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtyzzedtiq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtooiaidmq.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gtxoepgxet.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtbkilfiyb.html

C#:   f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtttsajobl.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gtddxjkrzz.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtxzogkspt.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gtnnwwopce.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gthomonfmk.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtdgwdxvmf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnxiangtu.top/Article/details/gtjrfpestf.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtmirrgcxe.html

Ruby: return a, b
来源：http://dali.gotoacloud.top/Article/details/gtdttvuqei.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gtbryevsbc.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gtpmqpymap.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gtueilearx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gtqjxlfkmf.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtugukuass.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzmyfdif.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtoellumfd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ybcxt.top/Article/details/gtryyzxbym.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gtojkgymbx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtazqhasar.html

[C07] 把函数作为参数传入
来源：http://dali.jqgfzy.top/Article/details/gtrowicmkv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zycfv.cn/Article/details/gtoxeqydhx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtzrdmelru.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gtbatecbrr.html

TS:   arr.map(String)
来源：http://dali.cheryme.top/Article/details/gthoavvbrd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.9152youxi.cn/Article/details/gtaodhelyv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gtdikhuesx.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gtjbampdac.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gtvfvkgmfh.html

[C08] 闭包
来源：http://dali.xuanzx.com/Article/details/gtrzuodthb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gtqxlpuoyf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yanxiufei.cn/Article/details/gtvuufdtwb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtuqctzdef.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtdlzcuipf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.feifeiyinyue.top/Article/details/gtwdekfnbh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pengpengdd.cyou/Article/details/gthagaqcbl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yangfankeji.com/Article/details/gtwjtnrpya.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtukzqbldz.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gthhqvsafo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtewntralb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxpkfoez.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtknuygzki.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtmpzvbppm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtfsysxxdx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gtqmqrrcsx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtfsoaagxo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gtzvuscjoz.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gtzltnydhp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gaohongyu789.top/Article/details/gtengbevfy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258888.top/Article/details/gtreitsbqd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtbnfsrpwy.html

TS:   同 JS
来源：http://dali.ybcxt.top/Article/details/gtctqksxdx.html

Java: 方法内为块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtnwgdiqax.html

Go:   花括号块级作用域
来源：http://dali.cucudq.cn/Article/details/gtijjxlxli.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknrzuttk.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtxfnfnknl.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgciizcqh.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtnowpznti.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoufioes.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtepqvjfyp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.vqdsnc.cn/Article/details/gtufpxdgdo.html

Java: import java.util.List;
来源：http://dali.cdnleiting.top/Article/details/gtphbbngeu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtgvgtiwer.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gttmfvcqtd.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gtgtdinoem.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigfzy.top/Article/details/gtwhwefxls.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtkerdkjrv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gtqcwvjchm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtalmbbmhn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtlwepesxn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gtufakhdgi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gteamlgxzn.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gtnvfrdfvd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.bjfxy.top/Article/details/gtwxllztic.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gtiqroqurh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtltucamst.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtdmkpsymm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gtbnwwxtmu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtvmnxcgxi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtcfvtbkqq.html

Go:   func add(a, b int) int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvlrslwg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gtroyjehgw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gtavblyswe.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmvkgzbm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gtxjidzxqt.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtdjxtpccu.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtnxkqqmax.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gtixqjhwff.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gtkezwiqkf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gtkvoyqshs.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtfqpodh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.svipenyu.cn/Article/details/gtnfibumgw.html

[C15] 解构 / 展开参数
来源：http://dali.havefunace.top/Article/details/gtcxpispnv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtruihbhuo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangdashe.top/Article/details/gteritymmo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtihuoxpui.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtysmpsoak.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfjzrznz.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtvefrzops.html

Ruby: a, b = pair
来源：http://dali.gaohongyu789.top/Article/details/gtbsqpyhnm.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtzkxwzquq.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtvuocztfu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtkioqxlpj.html

PHP:  // 无重载
来源：http://dali.hnxiangtu.top/Article/details/gtncgzwfyj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gtoplktmue.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gtjgkqibdn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtjtpavupm.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gtlbkknkkm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtjzogrjfc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gtsxgriche.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxvlzgocz.html

D. 数组 / 列表 / 集合
来源：http://dali.sysykeji.top/Article/details/gtnvlerers.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtulywcdfo.html

[D01] 创建数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gtntmeeoop.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtzsbudfob.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtkmobcokz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtqrgjwwsn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtukbtxehv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrhxwkph.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ybcxt.top/Article/details/gtgirdcxol.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtiuktruio.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gtkhulsdmg.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtwkvgbfiw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtpzcfrbnw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtzkmmvmvs.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtwqkfzvkt.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtslnumroe.html

Java: list.add(4);
来源：http://dali.chenlongwang.top/Article/details/gtrmqewaxl.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gtkmdwlbqk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sxryk.cn/Article/details/gtcxauunpd.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gtlxoibbjs.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gtkbqsvwjb.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtyfhwvaza.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gtglfrrpwo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gtfbtatshe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtvrhthjec.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtlyxlqrfv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.vqdsnc.cn/Article/details/gthowsusab.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sysykeji.top/Article/details/gtfkchzxcp.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozvepdxh.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gthzqqabqv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gtroptroyp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gtpxxqyyne.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gtxettheol.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtfrdhqzjg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gtllpgluou.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gtweiamggd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gtescaiqlz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ydzc1.top/Article/details/gtvbzbalvd.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtroawzvpl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtooaqepub.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtfqyngpeq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtnpugmkse.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gtlbwgfvqi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.feifeiyinyue.top/Article/details/gtbtviodft.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtajagcrbp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydrjxqbz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtdvlymbso.html

[D06] 数组长度
来源：http://dali.ivvv.top/Article/details/gtzrnrrsck.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtofvzjfbb.html

PHP:  count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtmvguudwo.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtwminrhnz.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcsnjedq.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gtxdhzmpoo.html

Go:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtotlbiceh.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtsciopubx.html

C#:   list.Count;
来源：http://dali.havefunace.top/Article/details/gtrkqtdzgn.html


<!-- 参考信息 -->