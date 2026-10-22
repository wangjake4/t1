代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdkwgxdhg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gtcoqpedwm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.quarkkingdee.top/Article/details/gtvlmdpolh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xinyue.icu/Article/details/gtzogicohx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangdashe.top/Article/details/gtpkrsrvyg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.kuanghao11.cn/Article/details/gtngomwzcw.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gtwursqgfv.html

Py:   while i < 10: i += 1
来源：http://dali.haohaochexian.top/Article/details/gtdmkhiwvb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtjdegaiud.html

JS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtgprmbwea.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtakjyjcju.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxvruqhy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigufen.top/Article/details/gtsxqvxfid.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guannengcc.top/Article/details/gtjbggxoaw.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtipvpccxl.html

[B08] do-while（至少执行一次）
来源：http://dali.cdnleiting.top/Article/details/gtgmudwkgf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shuidangran.top/Article/details/gtdohitcxv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtliccqrkd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtomezlxhb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtrrrklznb.html

Java: do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtojsurxso.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gtuwxcjpsj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yangfankeji.com/Article/details/gtbuuvalnx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtnnhcmbeo.html

[B09] break 与 continue
来源：http://dali.9152youxi.cn/Article/details/gtvftuocsp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pycfn.com/Article/details/gtkozdwefl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtzcxegrgu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtazrapnwf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoirzlsan.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvfzvyyhv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gtyqfeowin.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hywenlv.cn/Article/details/gtirmvdret.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtonovbujw.html

[B10] 遍历同时拿索引
来源：http://dali.fengsongda.top/Article/details/gtvuwfyeun.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ehwqpu.com/Article/details/gthnzwifbm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkamshtyy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtqtlowade.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtketonemv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuxming.cn/Article/details/gtrtaxvqbh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yanxiufei.cn/Article/details/gtsfauyiyz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fengsongda.top/Article/details/gthbxfcfwd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gtaazqteag.html

[B11] 生成数字序列 / 区间
来源：http://dali.shzxlz.cn/Article/details/gtstuhkrdb.html

Py:   list(range(0, 10, 2))
来源：http://dali.cqqwz.cn/Article/details/gtjkyfbmgu.html

PHP:  range(0, 10, 2);
来源：http://dali.bjfxy.top/Article/details/gtduhhfwek.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtfhjvhbgt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gtupmtcoge.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtbfvyrsrf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yueranfly.top/Article/details/gtgowojhxu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zdqjudy.top/Article/details/gtnoioitrm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gtsbtlresn.html

[B12] 跳出多层循环
来源：http://dali.quarkkingdee.top/Article/details/gtjjnzimpy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcnhzbmt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhiwuduotai.top/Article/details/gtqoogoifc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtislnqxsz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtzkhnzbob.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gttylsnilc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfjxlzpg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtstgbuisq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.haohaochexian.top/Article/details/gtiiwqlqdp.html

[B13] 判断是否为数字
来源：http://dali.shuidangran.top/Article/details/gtxzclgipa.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtoigzsgac.html

PHP:  is_numeric($x)
来源：http://dali.smart0.xyz/Article/details/gtirfbrrrc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwjimuny.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtwzipnvmu.html

Java: x instanceof Number
来源：http://dali.redwolf501.top/Article/details/gteqajiqoi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtwkekuhvw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gtsybjcssw.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gtzjnbowhu.html

[B14] 判断值是否在集合内
来源：http://dali.shuidangran.top/Article/details/gtylwjkbdw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gtsoetmngx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.9152youxi.cn/Article/details/gtrnjkwdns.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtxyyomjbm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtxbdzqdfs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtegmeslkj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tianlin.xyz/Article/details/gtxflcjeni.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtchcrrclu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtlqzgcfky.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gtyexaahit.html

Py:   a and b or not c
来源：http://dali.zhixingplan.top/Article/details/gtpuhrwues.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gtpqbpfmqr.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtqxtiytwh.html

TS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtrkwkwkec.html

Java: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtvqwgmrfc.html

Go:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtmuvcsjff.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbwjizoe.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtddaddkpe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gthitggbzp.html

Py:   if not data: return
来源：http://dali.316326.xyz/Article/details/gtycalztmj.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gtmyzxvgvl.html

JS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtfoqteqfe.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtluknqodt.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtkrenfcwe.html

Go:   if data == nil { return }
来源：http://dali.ivvv.top/Article/details/gtihnoqeve.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gttszpumkc.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gthxzzdygn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvmedkgcj.html

C. 函数与作用域
来源：http://dali.sweek.top/Article/details/gtvtmychxr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtirojhgll.html

[C01] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtyuarrktu.html

Py:   def add(a, b): return a + b
来源：http://dali.ybcxt.top/Article/details/gtfessldzz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrofeqnzs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtsmzzlyre.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxbtttak.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtrswrhvjz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gtuadymyue.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shzxlz.cn/Article/details/gtlteqbwzc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaslbfaq.html

[C02] 默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtcxpsbcel.html

Py:   def greet(name="World"): return name
来源：http://dali.hysaishi.cn/Article/details/gtjgloajna.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtsypbsxzg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtjzcbunsn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gthrfmyjyv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gtcnhzpxkb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenjidiqi.icu/Article/details/gtgmumhbmj.html

Ruby: def greet(name = "World") = name
来源：http://dali.xziqi.cn/Article/details/gtoxbpkfze.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gtabrquxyl.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtsjudaxtx.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gtfsljqnga.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cdnleiting.top/Article/details/gtbpxwlcfd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtaoimpuys.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtqcrdjjnl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgqayifm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gtpnyhiete.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtjoisoece.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gtqvbhtqkb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tanke756.top/Article/details/gtcsdzvfsw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gtsskwpsny.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gtrptdzohh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtgxvzqpnx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxinkj.top/Article/details/gtwvhmnaoe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gtehhrdjib.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gthiwmlmqo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtfxlkskqt.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtykzfteyo.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gttpzudbfr.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtkkghfbus.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gthxsbkfds.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtiozeckrj.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtdqmrmito.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gtedeahigc.html

Go:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtcunitway.html

Ruby: return a, b
来源：http://dali.tian-w.cn/Article/details/gtaufhxoya.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuvvlugo.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtmsqmjumf.html

Py:   square = lambda x: x * x
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgvbrker.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtzanrphus.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtaueitlhw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gtsrqlmtek.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhongyouzk.top/Article/details/gthlzbpyul.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gotoacloud.top/Article/details/gtcygjbzpz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtydckouzp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtvhsfgkcl.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtbpnrlhkz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daxiang520.top/Article/details/gtfcsnujpg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nwbrower.top/Article/details/gtamgwogmg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shzxlz.cn/Article/details/gtlefphgog.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjalfscq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gtqugzaosd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gzhubu.top/Article/details/gtytxxfivs.html

Ruby: arr.map(&:upcase)
来源：http://dali.0kj1m.cn/Article/details/gtkwtkcvuw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuxming.cn/Article/details/gtzpsmuzrb.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gteyryveby.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.iojbl.cn/Article/details/gtrcjisean.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gtmydfryus.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtlmdkavye.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtiuqbzmii.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ppjwa.cn/Article/details/gtbckvastp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtewyrlxwr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gtopencfqm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtfmdxrrjn.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnguutve.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtdnkbabfm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtepqjhged.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrmhblgs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtggfvbrpx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkberogsy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cdnleiting.top/Article/details/gtppgxlvtm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtnechhucc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnqzz.top/Article/details/gtzbkwezbb.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gtwcqyzdfc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gtckarvjdg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gtoxgyhala.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gtcyufjhqe.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gtygrbqjqy.html

Java: 方法内为块级作用域
来源：http://dali.yvedp.cn/Article/details/gtbkfuujqw.html

Go:   花括号块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtsobfacrn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.vqdsnc.cn/Article/details/gttvrvygmn.html

C#:   块级作用域
来源：http://dali.smart0.xyz/Article/details/gtxpflzvnh.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gtzdvgbard.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtpenrsgsh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gtdaatrude.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtwtplkxfs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtemerhdkx.html

Java: import java.util.List;
来源：http://dali.zycfv.cn/Article/details/gtipxwymrv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ybcxt.top/Article/details/gtedklznhe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gtvcdfeflk.html

C#:   using System.Text;
来源：http://dali.zhoulong.xyz/Article/details/gtfvlzbwsa.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gtztblmoea.html

Py:   (lambda: print("run"))()
来源：http://dali.redwolf501.top/Article/details/gtaanpnvkb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hywenlv.cn/Article/details/gtbzjnrayq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gtgizxzfnp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtguipewqu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtykadkkdl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhoulong.xyz/Article/details/gtbdztwpdg.html

Ruby: -> { puts "run" }.call
来源：http://dali.0kj1m.cn/Article/details/gtntrykopi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gtvmpnahcn.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtfixlpztt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.redwolf501.top/Article/details/gthnsazyrc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtzsecsxsb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtwluemlve.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtypqxppdt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtiqvkkvdi.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gtskabdmap.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangshuangyany.cn/Article/details/gtzzqsetjk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtdsufdeal.html

[C14] 泛型函数
来源：http://dali.wangdashe.top/Article/details/gtswdhxxml.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtribzolrj.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gtycnonvjg.html

JS:   // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtgbvszsxz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gtdfociact.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtynuwarxp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gtrngzykpb.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtuwchewbz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqopudzj.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gtdtuejssd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gtvjifrlfs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gtgdaogcqn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtiktvqnlh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gtxhyacgsa.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtwlsxvojn.html

Go:   // 无解构
来源：http://dali.0kj1m.cn/Article/details/gtvorqmoej.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gtcsotjkhu.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtmbuopgjw.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtwhddbklt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.vqdsnc.cn/Article/details/gtcxmfnkfh.html

PHP:  // 无重载
来源：http://dali.iojbl.cn/Article/details/gtfyhxxori.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gtzjhvsfmu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gtssjpqpxf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gtrzisregv.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gttoscpnrx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gtnmlbruwu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jyoumei.cn/Article/details/gtbmqsjlyl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqtnxikew.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gtbfhmwccu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdcvnppsz.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtapefdsat.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuanzx.com/Article/details/gtaqthbwsk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtbizvjlwp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtalqamtgj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gtotrjlnnr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sweek.top/Article/details/gtxendsgfy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gtigulougt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtemvyaknm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guowangkeji.top/Article/details/gtpsgpveyu.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gttmltuktk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tanke756.top/Article/details/gtascyqosj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.redwolf501.top/Article/details/gtqglmzwte.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtboaykhbc.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtjtggjbid.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtiakbfbbh.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtfdbqwcqz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cdnleiting.top/Article/details/gtmjniptip.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gtmyxpehnr.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtxbgmtjlg.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gtohwhghyw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gtcilaosyz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ehwqpu.com/Article/details/gtqjzxoaxb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daxiang520.top/Article/details/gtvvdokvgj.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gthkiyqdfi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtrkeghcir.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gtdebvtpwz.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtclgshojp.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gtjhesgmqf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ydzc1.top/Article/details/gtwpdjfryb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nwbrower.top/Article/details/gtgqjaxtng.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gthjicxbnv.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gtpcnnityx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gthkslpwkh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtfnfyjktf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gtwdiaobhw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuetiantiany.cn/Article/details/gtodkiqnra.html

[D05] 访问与修改元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteokgnjfs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyqwpykf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtgekvpqzr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtjtushchh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtgqjhtwno.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbykncdg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gthgytovht.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtwajosjlw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtahujwgpb.html

[D06] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtgttovqec.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtpalkikfg.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gtjzwpwjiq.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtgljnpoug.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtjifbnxjm.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gtjkgunomw.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtfrlvllfo.html

Ruby: arr.length; arr.size
来源：http://dali.yueranfly.top/Article/details/gtccgbverg.html

C#:   list.Count;
来源：http://dali.fengsongda.top/Article/details/gtjadcjwcw.html


<!-- 参考信息 -->