代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cdnleiting.top/Article/details/gtcgvubour.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gotoacloud.top/Article/details/gtlxlpeaih.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yuanzhike.top/Article/details/gtydjdhleo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fengsongda.top/Article/details/gtltxxvyha.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.kuanghao11.cn/Article/details/gttlmqlovc.html

[B06] 遍历字典 / 对象
来源：http://dali.zhixingplan.top/Article/details/gtdgmnnrtu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hongshengwenyu.top/Article/details/gtwfhfrhup.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnxiangtu.top/Article/details/gtotrqnanh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gtptgeewks.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtivzvytjv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aizwys.cn/Article/details/gtquwxzuut.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yonumen.top/Article/details/gteavuqdkt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuetiantiany.cn/Article/details/gtrpgdbhpa.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxinkj.top/Article/details/gtisfuoegx.html

[B07] while 循环
来源：http://dali.daria6918.cn/Article/details/gtfbmzwovv.html

Py:   while i < 10: i += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtivciuopl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtsdnhluwt.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtfobdhgbq.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkgsxzkpr.html

Java: while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtxjdkrhrw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tian-w.cn/Article/details/gtbwrbhrfm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhongyouzk.top/Article/details/gtcyhrncke.html

C#:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtywradnsg.html

[B08] do-while（至少执行一次）
来源：http://dali.tian-w.cn/Article/details/gtsnniruqz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zycfv.cn/Article/details/gtmltpleml.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtbktcoiyo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtoforyjxo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtjdyoykvy.html

Java: do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtrqteqlkq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gthliweeue.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhiwuduotai.top/Article/details/gtjifzzhrc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtjswaewso.html

[B09] break 与 continue
来源：http://dali.daria6918.cn/Article/details/gtqvclflwj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gtfwdmezyi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gthgdkiioi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtcgrktott.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtpbgssvvt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtcfjzebto.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258.top/Article/details/gtqabcokho.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnqzz.top/Article/details/gtatprhdfu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtkezlbknd.html

[B10] 遍历同时拿索引
来源：http://dali.hongshengwenyu.top/Article/details/gtzgufmeqs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jyoumei.cn/Article/details/gtgnsxrowh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuanzx.com/Article/details/gtglfcbnmh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtntfdihoh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gtpotwwwbe.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pycfn.com/Article/details/gtzxzwhkpi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuanzhike.top/Article/details/gtqwbttols.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ybcxt.top/Article/details/gtanwwbbnx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gthurxhdfu.html

[B11] 生成数字序列 / 区间
来源：http://dali.xinyue.icu/Article/details/gtdhqaohmb.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigfzy.top/Article/details/gtytrzebyt.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtpybzkpgi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gtfbkxfqem.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gtksbzaumk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shzxlz.cn/Article/details/gthecqxtuz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gtycphociw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.smart0.xyz/Article/details/gteucylzbf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtbwnlokrq.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtksbgptzo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gtqadvuzjp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sufxvd.cn/Article/details/gtjykjprfb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtkoiriboq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtivmsqgbo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtyklfmhrz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhoulong.xyz/Article/details/gtfjlhgpoc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dashuyun.cn/Article/details/gtlwruooax.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj20258888.top/Article/details/gtboffnezs.html

[B13] 判断是否为数字
来源：http://dali.aibaodan.cn/Article/details/gtouqkosee.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdwwghao.html

PHP:  is_numeric($x)
来源：http://dali.gaohongyu789.top/Article/details/gtmaquiwhn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtdnbystvr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtgxdepbbe.html

Java: x instanceof Number
来源：http://dali.gzhubu.top/Article/details/gtecjcnrwc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gttqlogeie.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gtjevhdknq.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gtgvvyvwzo.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gtvdsvajtg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aibaodan.cn/Article/details/gtaqtjeztn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gtnyygdvpj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtsihadnis.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtkgietabv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtcpecgmbi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hfpthk.cn/Article/details/gtiaafgqea.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cdnleiting.top/Article/details/gtjesywzis.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gttfzulnrr.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gtanhukrgh.html

Py:   a and b or not c
来源：http://dali.hywenlv.cn/Article/details/gtkkbarhzo.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gttntifsys.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtidnxuwnt.html

TS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtxinhxdrk.html

Java: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkygzpldt.html

Go:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtbehyoqpx.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtbfouqsyx.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtmvbwsovp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gogol.net.cn/Article/details/gtwbunjspo.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gtixscthcm.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gtwmmkexpk.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtilsupqih.html

TS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gtlnwolybb.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gttpufaiqf.html

Go:   if data == nil { return }
来源：http://dali.hysaishi.cn/Article/details/gtmkbkeumy.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gtvgplrmhi.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtfveuipak.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtabsxogce.html

C. 函数与作用域
来源：http://dali.zhixingplan.top/Article/details/gtchnqnwee.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqnfgagfm.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtvcgdfeas.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gtglpvuopd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekuuuivl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtaeoorktv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtbqcighbw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtovwzajeh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.snrcjt.cn/Article/details/gtqsfnyfjt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhixingplan.top/Article/details/gtuagiqojt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtashjmznq.html

[C02] 默认参数
来源：http://dali.cucudq.cn/Article/details/gtlirwywdw.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtufbczhgx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gtklfctlzn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gtubpluguo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtbysxuwtd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gtccnwqrqs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xinyue.icu/Article/details/gttvouxfwu.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gthhlfropc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gtdlsalvli.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtpwkvfaqi.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gtesruucnn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuxming.cn/Article/details/gtvhsjgyla.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtjrnwcfil.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtihkquwgg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cqqwz.cn/Article/details/gtnafqrfhi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daxiang520.top/Article/details/gtcxgjihxb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gtclelvskp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfqgknuj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gtmnexggvt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtngqrtffv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gtpdywmmix.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtyvsquowa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gttglwxsyl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gtkhohjebm.html

Go:   // 无：用配置结构体参数
来源：http://dali.haohaochexian.top/Article/details/gtfpuuogdj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtrbauymoq.html

C#:   f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtkjdrglfe.html

[C05] 返回多个值
来源：http://dali.chenjidiqi.icu/Article/details/gtomajiqnz.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtwyrhlslb.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gtcrqhnnub.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtwltwxyrw.html

TS:   return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxwtxeim.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gtjxeoidoy.html

Go:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gttmnalicp.html

Ruby: return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjkpzuvl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuanzhike.top/Article/details/gtxlneootc.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gtdwyqnkxy.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gtznmazunu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gtexamiqer.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtedtmwnsu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtxfrjxytx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.9152youxi.cn/Article/details/gtfvbogjov.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fzhhl.top/Article/details/gttyylbtua.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtpvummxmi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtmzniuxao.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gtywgcnmlm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlhhlfck.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtucqjppyf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gtflosshid.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gtzipxmniz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gteppjnwbi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gtffhftpbu.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gtrmloxdhs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtisbayhkt.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtzhembqvb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gtvnmnavce.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fzhhl.top/Article/details/gtoqtzhuii.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtimwgkeaj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtonekgmtw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gtqulsccsw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jianghu66.top/Article/details/gtnqajyidk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gtavwkyfot.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtbnsswqok.html

[C09] 递归
来源：http://dali.meibo888.top/Article/details/gtdpyksyrl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtzmcvllrc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtbnanjxxo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtbnuqtzug.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtoybzcbne.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtskbqmumv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gttwcsukcc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtcygavvgh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fengsongda.top/Article/details/gtlingbecf.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gtrysqoqfz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sysykeji.top/Article/details/gtttvcdjfx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gtetahhoox.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gtcwrktlku.html

TS:   同 JS
来源：http://dali.fzhhl.top/Article/details/gtzjbgbhsq.html

Java: 方法内为块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtmrnsytti.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtioebkmjb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gtskizavnm.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gtrfkzwehf.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gtcpnbdlto.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gtymbxcaac.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gtxcndozpn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gthjkqtawb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gtdxcgyqoe.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvaokqiec.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tian-w.cn/Article/details/gtnaoamnlp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gtaaoiddvt.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphojijcc.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gtsofpzcpz.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gtjrqooyon.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtzjlxukxv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtqolvartm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtysaicmzt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinghuilouyu.cn/Article/details/gtndkiblst.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtyyohktyi.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtnrhxvaag.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtbvvbfgpm.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtxsmdrsqr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gtekfjuwll.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtiwixgrea.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtqjhylewg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtejytoloy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcifjovph.html

Go:   func add(a, b int) int
来源：http://dali.9152youxi.cn/Article/details/gtgzpswowb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gtysxdexmk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gtqtkjkzrb.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gtifotrply.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gtyirtrzmr.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtmditoisk.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtpefrvrlu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gtcmeltdbx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gtlyyvxcot.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuxming.cn/Article/details/gtszlelkgn.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtaywgnrbq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gtrtexoqki.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gtchlahlpd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gtszjenjkv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gteanasafw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtmqtamdxw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ivvv.top/Article/details/gtpcaynatn.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtdwogesoh.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gtaohiqxes.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gthgyvlonr.html

C#:   var (a, b) = pair;
来源：http://dali.ivvv.top/Article/details/gtyfexucyf.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtltbgqeci.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gtuizxnjbi.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gtqhoqoqwy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gtichtcmaz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gtfyxbpfco.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtbnuxccse.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gtojgcbgyg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenlongwang.top/Article/details/gtsladlxen.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gtbzcqdwlq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqoevrazg.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gtnuwqoqqv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyvrzzyzn.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtobchcykp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gtchqlpqyj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gtpazcmidu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtsyqscfek.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gtnsskvzxg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gtcfdgixyk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gtflcikeqg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gtoophhtmz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtqgzvdqbz.html

[D02] 追加元素到末尾
来源：http://dali.jqgfzy.top/Article/details/gtidumsfgd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shuidangran.top/Article/details/gtofrrgqkn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sxryk.cn/Article/details/gtclapkpzn.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtkxcsroro.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtucjldxpr.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gtyhwybozv.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gtltophhsm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbyrtqni.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gtkvuigwyx.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gtogmtmeqh.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gtfublbjfc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xylfe.cn/Article/details/gtkwxalyax.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gtugzzbaxa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtcsybagso.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtqllmgkjg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtxnjezppz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xziqi.cn/Article/details/gtdplnooig.html

C#:   list.Insert(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gttvkvmtil.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gtqynubffc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gthoemlget.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tian-w.cn/Article/details/gtqnassjdm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.0kj1m.cn/Article/details/gtfwdnqkux.html

TS:   arr.splice(0, 1);
来源：http://dali.hnxiangtu.top/Article/details/gtbmdxmytu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gtwidjrkgk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gtqptszspt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gtsbowwebu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gtmdibwabf.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gtyvsimvec.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtgqqkwhjp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtdqzjyxpf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gteroupret.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jiagoushi.top/Article/details/gtbgituhoj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtwtxzfmtt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtbfjoisuh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gthowrgjic.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtmmlhaemm.html

[D06] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtevrozzsq.html


<!-- 参考信息 -->