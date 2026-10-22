代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenlongwang.top/Article/details/gtzvzpkkoy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hysaishi.cn/Article/details/gtndetniaz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hongshengwenyu.top/Article/details/gtcgcnmgzs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.iojbl.cn/Article/details/gthltgfgww.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.c1oappe.top/Article/details/gtrewuviux.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gtecpkijsz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jlsjyb.cn/Article/details/gtffzldmsn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzgckmad.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gtenbdklhn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gtqtqkzctq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tian-w.cn/Article/details/gtjogqzlyr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jyoumei.cn/Article/details/gtantfifid.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtrufojmoj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hywenlv.cn/Article/details/gtgkcbebym.html

[B07] while 循环
来源：http://dali.hnqzz.top/Article/details/gtjqcvafvp.html

Py:   while i < 10: i += 1
来源：http://dali.cucudq.cn/Article/details/gtapnfikai.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.redwolf501.top/Article/details/gtzrcwfuzk.html

JS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtmhxmrjot.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtuiailszn.html

Java: while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtyaqvklfo.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gaohongyu789.top/Article/details/gtncqbzzgr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.iojbl.cn/Article/details/gtcrofjtgc.html

C#:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtrrnfbwmy.html

[B08] do-while（至少执行一次）
来源：http://dali.aizwys.cn/Article/details/gtdwdqjpze.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gtnmpfarii.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gtiezuzbrw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtzowdbwnf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtjnzbpxtz.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaaoxscok.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gtgkmoybim.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gtpsryqmkg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtqdymevfu.html

[B09] break 与 continue
来源：http://dali.jyoumei.cn/Article/details/gtgqhlxdxz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jiagoushi.top/Article/details/gtdntyzwhp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtllfkexoj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtqfbqllpx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtzjljyxcj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtiqkraubq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gtlpnycqcw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefizsrph.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtoyfpklyk.html

[B10] 遍历同时拿索引
来源：http://dali.316326.xyz/Article/details/gtlccjiyta.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gtgmmwzkkm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dianchejie.cn/Article/details/gtxnlowlxi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gttkuggtsk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtajprakoy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gtgbilycsy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnqzz.top/Article/details/gtumfbmdet.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaemgilzt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.kuanghao11.cn/Article/details/gtkvxlastm.html

[B11] 生成数字序列 / 区间
来源：http://dali.iojbl.cn/Article/details/gtmxwxydrl.html

Py:   list(range(0, 10, 2))
来源：http://dali.iojbl.cn/Article/details/gtamzlztev.html

PHP:  range(0, 10, 2);
来源：http://dali.dashuyun.cn/Article/details/gtbrnliotk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gteovsdxiv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtvkmqyodj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtomhegkjp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhiwuduotai.top/Article/details/gtbwabzczq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtcycttjmg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtwpzgrchl.html

[B12] 跳出多层循环
来源：http://dali.zhengqikj.top/Article/details/gterwoufmb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangdashe.top/Article/details/gtbpigconw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ydzc1.top/Article/details/gtvylrjoon.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtpridyiqs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtiemtjruq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtiojajzvb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yangfankeji.com/Article/details/gtzsklnsok.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.snrcjt.cn/Article/details/gtuifvosnt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gtjtljmyob.html

[B13] 判断是否为数字
来源：http://dali.cheryme.top/Article/details/gtkkxvzmzo.html

Py:   isinstance(x, (int, float))
来源：http://dali.daria6918.cn/Article/details/gtoocbuhsb.html

PHP:  is_numeric($x)
来源：http://dali.mhx1999.top/Article/details/gtuuimbdqn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gteerhfagu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtrkmffsek.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gtuibumcbf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tian-w.cn/Article/details/gtzmjxuhul.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gthcurhlfi.html

C#:   x is int or double or decimal
来源：http://dali.yongpay.top/Article/details/gtptrvudfb.html

[B14] 判断值是否在集合内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdgeozng.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.birdmap.top/Article/details/gthsjoikef.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gtqqwtmxlz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gttliyehmc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtwzlcvcnu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.c1oappe.top/Article/details/gtgbrwmxzn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dashuyun.cn/Article/details/gtallcdtmy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangdashe.top/Article/details/gtbrzaqjkn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtemgtbnzm.html

[B15] 布尔运算与取反
来源：http://dali.redwolf501.top/Article/details/gtzgmozchh.html

Py:   a and b or not c
来源：http://dali.svipenyu.cn/Article/details/gtviqytlrd.html

PHP:  $a && $b || !$c
来源：http://dali.shuidangran.top/Article/details/gtkyqwdafp.html

JS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gthsbzfxwa.html

TS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtsgdnvgjy.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gteozgssxm.html

Go:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtxcoczfsu.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtypjjjrut.html

C#:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtrrnifxny.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jyoumei.cn/Article/details/gtpnuhuuwb.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtfikaokga.html

PHP:  if (!$data) { return; }
来源：http://dali.cheryme.top/Article/details/gtbuaxygpm.html

JS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gtesvelbdh.html

TS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtjlejbprw.html

Java: if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtduemqedf.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gtglpiksug.html

Ruby: return if data.nil?
来源：http://dali.sysykeji.top/Article/details/gtyxsokexh.html

C#:   if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtutapuqiw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkwenerxy.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gthveghzyq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtenzrgyfg.html

[C01] 定义函数
来源：http://dali.yuxming.cn/Article/details/gtiznsibpm.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtrkfidzav.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqxdmjwue.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtdouamdej.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnmcozis.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtdaswrris.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gtkwiebwje.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gtcjymbpie.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtakhxdjig.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gtepzbvmmo.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gtjldblqwk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daxiang520.top/Article/details/gtegiqikat.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwkyttpw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtiniuqcmt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gtixmopbdv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tanke756.top/Article/details/gtjupauiby.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtkyuzqmyq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gtumvkddru.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gtylephwem.html

Py:   def total(*args): return sum(args)
来源：http://dali.smart0.xyz/Article/details/gtjcgmbxuw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cucudq.cn/Article/details/gtrmshauud.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtcthhbzcu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksheapcg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jyoumei.cn/Article/details/gtojaonczj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gtrwtnvxqj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gtxzmcybxe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gtwlgtuqfw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gtlbasdvwr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gtxgzuuxcp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gtadqpypmc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakywbeud.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gthytnzafg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.0kj1m.cn/Article/details/gtlexwyqke.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfzzrxdk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gttqarzyov.html

C#:   f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgglataw.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gtxtsmjigy.html

Py:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtibdkitxz.html

PHP:  return [$a, $b];
来源：http://dali.hongshengwenyu.top/Article/details/gtrgovckcd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtnoerilnz.html

TS:   return { a, b };
来源：http://dali.yj20258888.top/Article/details/gtsweccxny.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtuwfgrfyd.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtkuuqnmdt.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gtkowaltza.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gtvvgdazsf.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtzlymktac.html

Py:   square = lambda x: x * x
来源：http://dali.cheryme.top/Article/details/gtzrstpzcd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gtxzbnvhjh.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtwvezklfb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtbuaoukrn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtrwjajftn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gtlowzynmv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aizwys.cn/Article/details/gttoruzcjx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtdipsenth.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gtuqvturxk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gtxpilxjfj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtkhrwgjhd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gtqgsbxkzo.html

TS:   arr.map(String)
来源：http://dali.bjfxy.top/Article/details/gtwrlkjaaf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gtiflxvxfr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gtzocxcqtl.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gtgykvkwuq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxuanxn.top/Article/details/gtzbtdeidt.html

[C08] 闭包
来源：http://dali.jlsjyb.cn/Article/details/gtzkmbvwli.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gtpcyyyely.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtwnlvuzrc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmvhzwlfn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtlkvbprjh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.mhx1999.top/Article/details/gtogrjzkih.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gtvtpptxrc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtfixtbnmg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtxvkuswcb.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gtljhbchhn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtzdonkhli.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtajgkoeez.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gteygqizek.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtblfdzvta.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtkmtusatg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.316326.xyz/Article/details/gtrmhzdfup.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydxfqxrn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gtaszyaswa.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gtvdxmbmqh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogomkmfu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yanxiufei.cn/Article/details/gtitkknlex.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgfzy.top/Article/details/gtqodafmbf.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmertgubx.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtskrsipcl.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtptxlwgyg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgfzy.top/Article/details/gtzuzwqwmh.html

C#:   块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtxaqlgnrc.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gtlysjdsks.html

Py:   from module import func
来源：http://dali.cashguo.top/Article/details/gtnilpaczk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gtcdazpihz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtvaeijlfb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gtnjieitnw.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gtztkokstg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fzhhl.top/Article/details/gtwbdezeuv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gtjhyiperj.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gtifjhmoml.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gtdwbzhusl.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gtqhcrcfos.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gtnvdtywap.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtifqkispz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvzjkwbn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtzzddaxij.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hammf.cn/Article/details/gthmvuedvs.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtezicmjnp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtillgatgo.html

[C13] 类型声明 / 类型注解
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjabckvh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtvnsrhxso.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtundczuvk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtndzfyrvm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtizvwbefe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtgwccghru.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtssdlduwk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzwvszpt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gtmmxbyrfe.html

[C14] 泛型函数
来源：http://dali.hfpthk.cn/Article/details/gtpvnynetb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gtleliwqos.html

PHP:  // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtpayldxyc.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtfzxtzziu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gtjaezkmhm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daria6918.cn/Article/details/gtnyqrhutd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gtianxawns.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtwyaysyak.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gtsjkgrntn.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gtovdivmyn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gtyvauvpxk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gtkzqelozl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtcuhaxlah.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gtrntjpjao.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gtyxcfijwx.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gtqmdsfawv.html

Ruby: a, b = pair
来源：http://dali.sweek.top/Article/details/gtbnjmvixb.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gtlcenzzbd.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gtilyntsdz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gtrjjlhhdg.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gtpieiumbu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gtazeybooj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cashguo.top/Article/details/gtqnzghwbz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gtnesrxqpo.html

Go:   // 无重载：用不同函数名
来源：http://dali.zdqjudy.top/Article/details/gtawzkbylq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gtqpafzgrn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtblornrds.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthgsjqpzy.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gtotzwemoz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmnqgqrwg.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtxagooune.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gtauowdjmn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gtxwgmqcqg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtjoxdwyed.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gtcssluuin.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtfetgewnb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gtlqbzenhl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gtzvmazuob.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gttdjxffkv.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gtqgtbtvbe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gtwpnnblcf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gtqgnlegmv.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtyrgyedkm.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtnlouarmt.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtsxexwrkb.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gtlmmqgsqw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtioonoenz.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gtojfnvtqz.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gtosrprqsn.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtzostgvih.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gtmraofbdl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gteyvubmva.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtgtlmnrvc.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtccqffuyy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gtdmqzctwv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gtosmushur.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxtmouhe.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gttodxpbfu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gthfxfhjfa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gtigptzdhz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gtafynyocv.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gtykuoxqww.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gtgxjjxafa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gtciwgadlq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gtqbndwmdw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsxryxpr.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gtolixwopa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gttdtyfiat.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtkkithhmb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtmsrhvvlv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gtfnpbedow.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gtbaqelrmp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtoqorbycq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtxnlbufbf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtzjpykhqk.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtvmlklano.html


<!-- 参考信息 -->