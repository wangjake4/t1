代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gtxzklaalw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnxiangtu.top/Article/details/gtxfkwxyja.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sysykeji.top/Article/details/gtiyhljvea.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daxiang520.top/Article/details/gtoyyadvqj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxuanxn.top/Article/details/gtteoppdjy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenzaomai.com/Article/details/gtlwezfkdb.html

[B07] while 循环
来源：http://dali.9152youxi.cn/Article/details/gtntlvadne.html

Py:   while i < 10: i += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtonnpsmth.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtpskcvyyd.html

JS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtuloxthdk.html

TS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtfofzqzpf.html

Java: while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtkupvynvg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258.top/Article/details/gtizttisoi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aibaodan.cn/Article/details/gtckgifxjo.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtjymtxves.html

[B08] do-while（至少执行一次）
来源：http://dali.yj202588.top/Article/details/gtjhbvzsuc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daxiang520.top/Article/details/gtpshogulp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.9152youxi.cn/Article/details/gthgccmhet.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtsvxpghwt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtiqgysede.html

Java: do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gthlbxbglc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnqzz.top/Article/details/gtyzhmjrlw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgfzy.top/Article/details/gtbnfbciqp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtvnohjgxp.html

[B09] break 与 continue
来源：http://dali.svipenyu.cn/Article/details/gtoyydrczu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guannengcc.top/Article/details/gtcvkmssbo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtbcuxbymo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtbgepsurc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtfhcufole.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtvzilgczo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gtbkuijldg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.smart0.xyz/Article/details/gtkyaluuwk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtlwjliwrt.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gtlzvuqozo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.svipenyu.cn/Article/details/gtmtfwnwzq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jianghu66.top/Article/details/gtklqkbtqv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtsicqosnb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtolclnlto.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gtuvfhskja.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258888.top/Article/details/gtnfvtzrwi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gtekbgsxps.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtjdememkc.html

[B11] 生成数字序列 / 区间
来源：http://dali.hywenlv.cn/Article/details/gtzmprhsnu.html

Py:   list(range(0, 10, 2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtordgqaws.html

PHP:  range(0, 10, 2);
来源：http://dali.daxiang520.top/Article/details/gtbigffmvf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gtwmdorigq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gtehaqnngb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtgjdstthh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hywenlv.cn/Article/details/gtwdciwspo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuxming.cn/Article/details/gtbxnbwlex.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jyoumei.cn/Article/details/gtakiimvfz.html

[B12] 跳出多层循环
来源：http://dali.redwolf501.top/Article/details/gtsisfxsan.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.meibo888.top/Article/details/gtmowmlijy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yueranfly.top/Article/details/gtobbwsxxb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtvtwurgve.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtjzcvivbv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtqhktbdjk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tianlin.xyz/Article/details/gtmvagdwlb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gtcbqamsvs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gtbomdwjec.html

[B13] 判断是否为数字
来源：http://dali.hongshengwenyu.top/Article/details/gtrrknslex.html

Py:   isinstance(x, (int, float))
来源：http://dali.jlsjyb.cn/Article/details/gttkdfxyyf.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtvysmnyyw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gttqweifsw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtixsnjrdu.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwvyzgel.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gttutribsr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.havefunace.top/Article/details/gtdiasdjvp.html

C#:   x is int or double or decimal
来源：http://dali.c1oappe.top/Article/details/gtgoutqvye.html

[B14] 判断值是否在集合内
来源：http://dali.nanxuanxn.top/Article/details/gtukrlfgku.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gtclsslgxe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gtrofjriks.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtlzpsjlgr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gtpjymkfnu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gtckgnzmfu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jiagoushi.top/Article/details/gteyjbhhxs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtttenwvcp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvonlcvt.html

[B15] 布尔运算与取反
来源：http://dali.yueranfly.top/Article/details/gtcmvdyreh.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbmuivtf.html

PHP:  $a && $b || !$c
来源：http://dali.daria6918.cn/Article/details/gtbeqaijfn.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtxifalqul.html

TS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtceebmhfo.html

Java: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtpvraizxw.html

Go:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtnxvfbdgm.html

Ruby: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtkdmqwqls.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtrhrekggi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gtgdskqykb.html

Py:   if not data: return
来源：http://dali.tanke756.top/Article/details/gtuxetwoor.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gtxkvfkput.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtqqjzrrac.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtqrdfmrlj.html

Java: if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtbixsqufg.html

Go:   if data == nil { return }
来源：http://dali.jqgfzy.top/Article/details/gtwiakcpuu.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gtkkivnwrw.html

C#:   if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gtdechknux.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthufbxikt.html

C. 函数与作用域
来源：http://dali.zhongyouzk.top/Article/details/gtuguywpre.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtptpnqusw.html

[C01] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtywhdwmsy.html

Py:   def add(a, b): return a + b
来源：http://dali.0kj1m.cn/Article/details/gtzikdkjeg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtqjxotzpo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtiirkuufs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdzfiaamj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtxjzsukoh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtnbosnwoi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gtckdnndon.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtsqanjdbs.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijfqdnee.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gtvmizvfqr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gtwqtuyxny.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtlchovzyr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtcolfyzle.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmmjsyra.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtoguvnkjo.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gtvjwhdzjb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjeenwzz.html

[C03] 可变参数
来源：http://dali.yuanzhike.top/Article/details/gtxbidjvnl.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gtdawctzsz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gtvavkwfou.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gtbamvvkqf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtrutzcien.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.mhx1999.top/Article/details/gtgrniuhmm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gtnrjgrsfw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.vqdsnc.cn/Article/details/gthitzlxmc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtgccqfzbb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gtgouydxiv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.andypj.xyz/Article/details/gtxosqrnzu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gtzsczzwrk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtpjqlhaql.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gtxwtsogjt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlavffygy.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenlongwang.top/Article/details/gtmdwaihgm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtbecnrxfp.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfpoonne.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gtvjnhkypi.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtmiwnaohf.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gtjogwpflo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtfqieusur.html

TS:   return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gtyghdvmxm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gtnssvodin.html

Go:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gtpykwgbds.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtiqfvrizn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogewnvnd.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gtqlkyodqi.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gtqbfyqhty.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gtjployqmu.html

JS:   const square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtebkvlwdx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtxmfmpwji.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.smart0.xyz/Article/details/gtcbzfklzp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gtiovrwydx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sysykeji.top/Article/details/gtfzedzujw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtzhzbyjrs.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gtefbvrzso.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jlsjyb.cn/Article/details/gtvuxhrgwg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtyoaxfhcu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ybcxt.top/Article/details/gtkkutiiqe.html

TS:   arr.map(String)
来源：http://dali.zhoulong.xyz/Article/details/gtmeanxhns.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtkinqxqlx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gtkzdszuhd.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gtozcnuyko.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigfzy.top/Article/details/gtiatvbrex.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gtsetmozxq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gtqxgllzmu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gtyknahljf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtbtzgksle.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtgyltismo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtrhugnmwl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtqauvuyod.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtcpshrwvv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtqdptlxps.html

[C09] 递归
来源：http://dali.pengpengdd.cyou/Article/details/gtvekroqoy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtvfceqely.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtvqvnufcl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtfqnmpjcf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtmytsncqn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtozjpopni.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gttpeiggcw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmurxynxh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtdsmvwdlg.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gtvagmukyj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hammf.cn/Article/details/gtviuwgakj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gtxkdfaiym.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gtfznirrju.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gtavhrfelv.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gtkbjrdrtm.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtppqrzsly.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauwxdvyy.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtnkxavvuc.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gtcwwhelsy.html

Py:   from module import func
来源：http://dali.xuanzx.com/Article/details/gtkshxapzq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gtehvesdpw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gtybxjumzc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnxiangtu.top/Article/details/gtzlhbjfys.html

Java: import java.util.List;
来源：http://dali.daria6918.cn/Article/details/gtznjwplzd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtawtosgrf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zycfv.cn/Article/details/gtwhphyjlp.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtcfendavq.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gtwxrucjal.html

Py:   (lambda: print("run"))()
来源：http://dali.jyoumei.cn/Article/details/gtcciifykk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuanzx.com/Article/details/gtvgvzvuyo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtrqusxjqk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtjdwpcntb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gtjfpzpkzq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtknuzwpsi.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtxryjggsr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbueltuz.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gtttmdhxaq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gtrshpxgmz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gttiuxboss.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gttcrapppn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtcvdrrpcv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtkcvnrvkv.html

Go:   func add(a, b int) int
来源：http://dali.yj20258888.top/Article/details/gttzdamfag.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gtlofntmxh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gtktpsdata.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gtedtzojyx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gtktvgryhh.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtbewwhgyn.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtvsiatiqs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gtijyzaoue.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtozusheeg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gtgddbyzbe.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtxfrhczcb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gtoiuaeqxt.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gtbmvgydxq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gtooaohhoi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gtaxvtazgk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtdwfyixps.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gtfsxqmkyy.html

Java: // 无解构
来源：http://dali.zycfv.cn/Article/details/gtilturxnp.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gtmtasigke.html

Ruby: a, b = pair
来源：http://dali.cheryme.top/Article/details/gtfgyreiqn.html

C#:   var (a, b) = pair;
来源：http://dali.zhoulong.xyz/Article/details/gtuhpzunau.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gtxhisrmyz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sufxvd.cn/Article/details/gttfyyeyet.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gtfsyiupnd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gtguuugsyo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gtnhhfqqja.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtbhqgpyyw.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gtwdaoxxcv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gtecomgjbb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gtboltgzlm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrhqtuvxw.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqlrraha.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtngvzxbor.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gtfhdeqcug.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gtbxjtuyla.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtdmybrcdw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtsrntwvoj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gtnzyoxhgk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtwgnsppkx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtrsscyhiu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gtitqlblrv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gtgmmcqmtj.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtueusoyoc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gtokeynbyu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtxbphalve.html

JS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtyopafipx.html

TS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gteklenisq.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gtgpgbgrgn.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gttggnxxei.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gtempwetgi.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gtyelozkjg.html

[D03] 在指定位置插入元素
来源：http://dali.cdnleiting.top/Article/details/gtoumkjsql.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gtupiypgwe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hammf.cn/Article/details/gthvfpddsh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gtgkyrisbp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gttovmaepy.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtkeabhiwm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zycfv.cn/Article/details/gtoqjhjszo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsekvjomp.html

C#:   list.Insert(0, 0);
来源：http://dali.316326.xyz/Article/details/gtjmadofqr.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtyxaeaeut.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gtypgudlia.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtsmguzvfb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtooexhhkr.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gthjmznfss.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwzylhye.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gtmaaejtta.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gtacncgcdo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cqqwz.cn/Article/details/gtkpbbfdrd.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gtxxeojetw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtnenbrqtp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtajhdqoky.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtzkqffpfj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.vqdsnc.cn/Article/details/gtmouxhuwi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gtdubdkwun.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtcvabeziw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtribhbpmb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtpdrtszqy.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtmbjhnnsb.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtkzoyywcq.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gtecntufgu.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtpfyamomd.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtapkwkgix.html

Java: list.size();
来源：http://dali.ppjwa.cn/Article/details/gtryntdkik.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtantdpswm.html

Ruby: arr.length; arr.size
来源：http://dali.fengsongda.top/Article/details/gtpoblcejv.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gtoxlyxqxk.html


<!-- 参考信息 -->