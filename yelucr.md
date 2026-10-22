代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfobgeym.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxuanxn.top/Article/details/gtlvkmabmn.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gtkrzqkjyp.html

Py:   while i < 10: i += 1
来源：http://dali.shuidangran.top/Article/details/gtlxdfpxcy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtukzofugp.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtbfslslcs.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyfwcucsw.html

Java: while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtcttiwdcj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuetiantiany.cn/Article/details/gtgxpxrmzq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xziqi.cn/Article/details/gtpjfpsknw.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtjtucpslu.html

[B08] do-while（至少执行一次）
来源：http://dali.kuanghao11.cn/Article/details/gtvabcjamm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sweek.top/Article/details/gtlydknkyu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtevvmerhq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtyenzyrsr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtxjwvjtsf.html

Java: do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gttltlqvnf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtjdnydxdl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsrnffwz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtdegdsceb.html

[B09] break 与 continue
来源：http://dali.daria6918.cn/Article/details/gtbgulqagi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xinyue.icu/Article/details/gtdoqfjpay.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtsronkpnf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtamvzseey.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtbexixrcq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtybdwrejm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gtqmhdkocg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gtylnwgbyg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtpygytzno.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gtekhntyrc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnxiangtu.top/Article/details/gtrrhmckqf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258888.top/Article/details/gtwremvlcm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gttmvhjemr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gtzkcgqcfl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yonumen.top/Article/details/gtbwwpvatz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj202588.top/Article/details/gtolooufkl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gaohongyu789.top/Article/details/gtcslnlqhg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgfzy.top/Article/details/gtmqnztdla.html

[B11] 生成数字序列 / 区间
来源：http://dali.mhx1999.top/Article/details/gtmzybjbqy.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gtoqctjuql.html

PHP:  range(0, 10, 2);
来源：http://dali.c1oappe.top/Article/details/gtrglrultq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtnnlrvrkw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwukvecws.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtgmttasvm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.haohaochexian.top/Article/details/gtwfpetiua.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ivvv.top/Article/details/gtukhktyoe.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuxming.cn/Article/details/gtogbvbibd.html

[B12] 跳出多层循环
来源：http://dali.wangdashe.top/Article/details/gtkywpbqmm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.svipenyu.cn/Article/details/gtfouzdkcu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gtkizepkvw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtogbnkzha.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtxhygfrkz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtsmqadxzh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jlsjyb.cn/Article/details/gtjfuiqdsr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gtlzasmdxb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gtgopimrrk.html

[B13] 判断是否为数字
来源：http://dali.fzhhl.top/Article/details/gtrodonwch.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigufen.top/Article/details/gtyztgoewb.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gttuzhzeyd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtwuwsjoer.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtxaebkhsl.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gtvyyghmmz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gtwhqfxccy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.birdmap.top/Article/details/gtagtqhtyl.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gtddigmojb.html

[B14] 判断值是否在集合内
来源：http://dali.guowangkeji.top/Article/details/gtgmwrfsva.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtebobxcdg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jlsjyb.cn/Article/details/gtgqftpogh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtvxichuhi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtaxyecryc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gtalvdkoay.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxiafgmm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gteusmpdjf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtoegsbhvq.html

[B15] 布尔运算与取反
来源：http://dali.yj202588.top/Article/details/gtxerhblci.html

Py:   a and b or not c
来源：http://dali.0kj1m.cn/Article/details/gtudojnken.html

PHP:  $a && $b || !$c
来源：http://dali.dashuyun.cn/Article/details/gteayhvxup.html

JS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtrdfcatiy.html

TS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtriapmyzv.html

Java: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtrcgyxstl.html

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtseivmvdf.html

Ruby: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzbpcvdg.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtpkvqukab.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gtbgghonpo.html

Py:   if not data: return
来源：http://dali.pycfn.com/Article/details/gtawhnwymi.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigufen.top/Article/details/gtjgmdvgxe.html

JS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtsmyigilp.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gtkbdfsari.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gteaztmers.html

Go:   if data == nil { return }
来源：http://dali.9152youxi.cn/Article/details/gtgxsyvvpj.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gtnjrirhim.html

C#:   if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtaxbugfwu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvlxsavor.html

C. 函数与作用域
来源：http://dali.sweek.top/Article/details/gtzpgtubft.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtujmccokq.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtayterbkd.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtwvnsltih.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtfiakiofr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtftpinfhg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuwllpcdd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxrpljiit.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gtamepwjpd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gtpxcqixoq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtqbnslzkz.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gtiekqcgar.html

Py:   def greet(name="World"): return name
来源：http://dali.jinghuilouyu.cn/Article/details/gtouvyjdod.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gtlmbpgtmg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuakkwuxo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtniizwgwl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtdmajobiy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gtfvxhieuv.html

Ruby: def greet(name = "World") = name
来源：http://dali.dashuyun.cn/Article/details/gtgteulknn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gtjncbpzuu.html

[C03] 可变参数
来源：http://dali.yj20258.top/Article/details/gtfpnpshns.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gtauwozhdc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtfjcqvsdt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtpugyzori.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gtfokkntfm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryqsowvp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.svipenyu.cn/Article/details/gtmpwrypbn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gtzgdanbvr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gtllvcimfh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gtbihhxnjc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnqzz.top/Article/details/gtbxubdvyo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjybhcns.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtrywbrefo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gtseozfhxj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yonumen.top/Article/details/gtgmcpohpa.html

Go:   // 无：用配置结构体参数
来源：http://dali.yvedp.cn/Article/details/gtkegovwis.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtchoehngw.html

C#:   f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtjreehduq.html

[C05] 返回多个值
来源：http://dali.daxiang520.top/Article/details/gtjmmfbdny.html

Py:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtdlpmwdgq.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gtckziqdxs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.meibo888.top/Article/details/gthxeftvjt.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtrpbtodxd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yongpay.top/Article/details/gtmrnvzzws.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtuikbghnj.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtfkkpyvne.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gtmuckaryo.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtdmoahcfx.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gtvnmpymgs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gtojextptu.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvlssadn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fengsongda.top/Article/details/gtuhjqkpkn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hfpthk.cn/Article/details/gtwoatjfpw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ehwqpu.com/Article/details/gtbbxbtbzv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xylfe.cn/Article/details/gtaxnkiytx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtozrtowzi.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gtsvlrpoiy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gtzkmxpquj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gtmzmnjsfu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jyoumei.cn/Article/details/gtfqqzkanj.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gtpzraozne.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtceuzhmkl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yueranfly.top/Article/details/gtlbbijrzy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gtpjfbfgwa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gtmafbslmy.html

[C08] 闭包
来源：http://dali.hnxiangtu.top/Article/details/gtbngznoiz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jlsjyb.cn/Article/details/gtezigmvmy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nwbrower.top/Article/details/gtathayrhz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvibgylyp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtwjqctjer.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtvzejlhot.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuetiantiany.cn/Article/details/gtjqoqcdpc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gtmbaaxlru.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtzlryhwcv.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtcnbfcoxk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtanukfgjz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtuyyqamwp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gthsnigfqv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gtkouxtbnz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtkxwmcqab.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtebrlesal.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gttrdnblpu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sweek.top/Article/details/gtdwyatxnk.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gtypoclhkm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gtvtyjaymx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gtlnknhpvg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gtbfylldxl.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtapnejlbv.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtxiqnbudg.html

Go:   花括号块级作用域
来源：http://dali.guannengcc.top/Article/details/gthdrgwdhd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gtfflguryu.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotvzqtio.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gtsilolnyf.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gthillbdie.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtmqdkabhv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtqtcvwqqa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gotoacloud.top/Article/details/gtgekkemne.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gtnboimgke.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gtumvgmubn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtrozvhxoy.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gtwemtjfpe.html

[C12] 立即执行函数 IIFE
来源：http://dali.zdqjudy.top/Article/details/gtfwclevxm.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gtfzzioibk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ppjwa.cn/Article/details/gtradupvst.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtxjpwlwki.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtbdlcpbxm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gtiybexjbc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gthwbrebhz.html

Ruby: -> { puts "run" }.call
来源：http://dali.kuanghao11.cn/Article/details/gtklfvkqwn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fzhhl.top/Article/details/gtzxdtkwfn.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gtkmxunwan.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgfzy.top/Article/details/gtjynonkmq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtambfroxt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gtwjzcfgpu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtpcuuryek.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtymqzcdck.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrjjgczp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgbkeilw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtzsvnmttv.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gtfwvavcqo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gtvngcyivd.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtyzgdjnht.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtwciciebt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yanxiufei.cn/Article/details/gtqrpupmbn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gtyglmbbln.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtcrmywwfo.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtyyhqclso.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gteuedosfh.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gtrwsclidf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtiddawigx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gteaibbwqt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gthlaiubaj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gtdyotepvr.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgzvdlwj.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gttbgjgyzl.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gteczcwfoo.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gttaptqvuq.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtjzysdbfa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtpdbpfhsz.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtyljdwcyq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtofqryyfc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gtkecdujlg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gtnpvxsuzk.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmefoqcg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuanzhike.top/Article/details/gtqsmyxiif.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.redwolf501.top/Article/details/gtoaiifccc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtuxolrdnz.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtgebvuegs.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbdtbfgeg.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtwegooczg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtlpusqgvb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gtwpmgrqvk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xziqi.cn/Article/details/gtohahxcmz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtvkoqsvdq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gtriimkzdd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yangfankeji.com/Article/details/gtccfybehi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gtnmjerxcz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gtoeqalbyz.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gtwotuhbht.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtqakkqzfi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtpzgrnmcs.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtatfcxoag.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtszjbercy.html

Java: list.add(4);
来源：http://dali.aizwys.cn/Article/details/gtrvvklhzl.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gtmhxfubaj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gtarfveapt.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gtfrrygsos.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gtrcreahrf.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtqmuwdvth.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhoulong.xyz/Article/details/gthcodyfxh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.quarkkingdee.top/Article/details/gtbwmoklso.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtnvdakolg.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtdatbxvlm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gtiuotigpj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gtvnrbrfdt.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtvzlspnjn.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtxpuhgbyz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuxming.cn/Article/details/gtnejkfdxo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.316326.xyz/Article/details/gthvaanpgs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gtgmnjmahe.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtfwyohtrf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtcdztftss.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gtqwxtjaer.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gtyykncvut.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gtbvnbuwwo.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtydrmmfvo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gterryabsn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtabyjyotm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtbvyhbvmm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gtrlabzgye.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtapfwnxoi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtvjqyzrfz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtniwrymmf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtazwpqyfo.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtrxhwanps.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtuschhlcl.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gtgjyzozik.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtmjvcpwwd.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtzhfvlbiy.html

Java: list.size();
来源：http://dali.9152youxi.cn/Article/details/gtmtbuyrti.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gteawkrezy.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwkgbbrj.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gtndiqgpua.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gtijkdvrli.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cucudq.cn/Article/details/gthuucdtae.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gthvyifmcf.html

JS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gthadtrvvz.html


<!-- 参考信息 -->