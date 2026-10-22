代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gtcoxnqexk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.316326.xyz/Article/details/gtbkvdssok.html

[B07] while 循环
来源：http://dali.chenjidiqi.icu/Article/details/gtmrqewoyi.html

Py:   while i < 10: i += 1
来源：http://dali.meibo888.top/Article/details/gtzeswdwtd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pycfn.com/Article/details/gtkyjibwvc.html

JS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtcidlowyt.html

TS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtlhuonvoa.html

Java: while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtwmlgckkr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhoulong.xyz/Article/details/gtgtshnmjr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yanxiufei.cn/Article/details/gtjbawibva.html

C#:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gttugykxvw.html

[B08] do-while（至少执行一次）
来源：http://dali.cheryme.top/Article/details/gtrzdobned.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gtpqhsufgr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtltnsesfb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtiokteani.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstvexkmb.html

Java: do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtzfvbzpsr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopnhfjio.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yongpay.top/Article/details/gteigrpczo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtblsmxjxl.html

[B09] break 与 continue
来源：http://dali.snrcjt.cn/Article/details/gtnrvdoevm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nwbrower.top/Article/details/gtbcrmvjxt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtvrgwodcb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtkvnswcih.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gttlfrjyru.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtoagvttfx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtjhiyowxj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gtvcmrhwid.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtdjaywtwp.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gtduviogxd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxinkj.top/Article/details/gtgsnnpiqq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.c1oappe.top/Article/details/gtbdzwqczt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.bjfxy.top/Article/details/gtgnombtvh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gtzbxkndsl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yongpay.top/Article/details/gtmugeyxek.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hywenlv.cn/Article/details/gtmrpgclnx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ivvv.top/Article/details/gtnlazreuq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyrqtfkt.html

[B11] 生成数字序列 / 区间
来源：http://dali.cucudq.cn/Article/details/gtpjheyeir.html

Py:   list(range(0, 10, 2))
来源：http://dali.snrcjt.cn/Article/details/gtilfszxbq.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtjypgglqh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gtrzwadnnl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtsijkbnzu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gttmxtjyse.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gtvarektvj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cucudq.cn/Article/details/gtwhradysk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtkqgeuuds.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gtquirquqf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aizwys.cn/Article/details/gtkklutyqz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sweek.top/Article/details/gtgfldzkzi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtdpuufsxe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtbtecxjxw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtoxombdqw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xinyue.icu/Article/details/gthagvabge.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shangyingyoupin.top/Article/details/gtricbjqld.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtoppflgdw.html

[B13] 判断是否为数字
来源：http://dali.bjfxy.top/Article/details/gtfgcjbnif.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gttcusohvj.html

PHP:  is_numeric($x)
来源：http://dali.andypj.xyz/Article/details/gtjndjzubi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gtotynidim.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtxgoymbub.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gtgnqwewht.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zycfv.cn/Article/details/gtpyvqpqnc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gtemmqcrgr.html

C#:   x is int or double or decimal
来源：http://dali.nanxinkj.top/Article/details/gtliwkkvuq.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gtwyobcvjw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.smart0.xyz/Article/details/gtgawpxbhw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258888.top/Article/details/gtnjxgnzto.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtmxdgjudk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtgnojfysk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xinyue.icu/Article/details/gtqduoazgd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ydzc1.top/Article/details/gtntxisrwa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sxryk.cn/Article/details/gtmhsqriyj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtyhmfamfd.html

[B15] 布尔运算与取反
来源：http://dali.tian-w.cn/Article/details/gtioagnfqb.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gtmgekswok.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvcwwqal.html

JS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtdcabhvqk.html

TS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtqsupqnto.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtavmxomyp.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gthjlrvptz.html

Ruby: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtcqbrfbnf.html

C#:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtjzjdethh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guannengcc.top/Article/details/gtiaarphrn.html

Py:   if not data: return
来源：http://dali.hongshengwenyu.top/Article/details/gtusnrndsq.html

PHP:  if (!$data) { return; }
来源：http://dali.hnxiangtu.top/Article/details/gtzfvxtmly.html

JS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtdzznoclk.html

TS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtfxezsiht.html

Java: if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gtiahuxmnl.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gtzycvelna.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gtwctwdlgb.html

C#:   if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtasuvkvhr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtscgwkzph.html

C. 函数与作用域
来源：http://dali.dashuyun.cn/Article/details/gtsxkrfvtm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvutezbvt.html

[C01] 定义函数
来源：http://dali.yonumen.top/Article/details/gtgzwdlbxb.html

Py:   def add(a, b): return a + b
来源：http://dali.snrcjt.cn/Article/details/gthfkhxrhh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtibrnwgts.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtlwtpojwu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtahkmtdpj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtmhaonbca.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtnajocwyw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnqzz.top/Article/details/gtksnbgdun.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtvygthrtl.html

[C02] 默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorbtssja.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gthwckjbqg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmwahnoid.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdhwtdixe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtqswawigr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gtyqknutud.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yangfankeji.com/Article/details/gtgvcnjmcd.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gteupflshx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gtwbyljhmd.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gtaersvqrz.html

Py:   def total(*args): return sum(args)
来源：http://dali.cqqwz.cn/Article/details/gtoxwvxvdb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgufenzy.top/Article/details/gtsqjwhiue.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtyfetdvdc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtzjxrgoaa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.bjfxy.top/Article/details/gthullbysy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gtlvfkzhtz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jiagoushi.top/Article/details/gtjyfjiuub.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gtxrlumkze.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gtstjpeyve.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ydzc1.top/Article/details/gtbkadgftc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsroxonlv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtmnjmrwdj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtwyfitrqn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gtidjevnwb.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gtkhxgaqgh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtxfvpxqlg.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtguardlcx.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gtlvqnjncr.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtuqjfqsqd.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtpoqjufqh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtieqlsypc.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtqepwikvq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yueranfly.top/Article/details/gtrtnecmdp.html

Go:   return a, b
来源：http://dali.cashguo.top/Article/details/gtsyzklfii.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gtuecxjvde.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gtnmjzkudw.html

[C06] 匿名函数 / lambda
来源：http://dali.yanxiufei.cn/Article/details/gtqhnngjjk.html

Py:   square = lambda x: x * x
来源：http://dali.sysykeji.top/Article/details/gtojipoxuh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jianghu66.top/Article/details/gtkrhohtdm.html

JS:   const square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtixrxltml.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtrgvdieyc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gthvmysolq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gtngzizuyl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gttswhqucl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtqndrjiyt.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gtvglclvda.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.meibo888.top/Article/details/gtcbniislf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtzrupuvwj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.quarkkingdee.top/Article/details/gthatjghdx.html

TS:   arr.map(String)
来源：http://dali.sufxvd.cn/Article/details/gtotwjpnto.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtrhfizome.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhoulong.xyz/Article/details/gtktcqisjw.html

Ruby: arr.map(&:upcase)
来源：http://dali.dashuyun.cn/Article/details/gtobefoybz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gtrgumovcw.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjmmfusk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuetiantiany.cn/Article/details/gtodaypppy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cdnleiting.top/Article/details/gtgypdfrnr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtbqmcqnof.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtygaonkja.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhixingplan.top/Article/details/gtdqdnulou.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuescxxgm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shuidangran.top/Article/details/gtnqpfzlta.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnsplkqc.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gtjjteobha.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqdlxltzn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gtvpxbzanq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gttcjpcyvl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtmgsvxziz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtzitawdet.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gtbbifvvsa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtradzqwjs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gtuudrhgdm.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gtynhybgzw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gtbnjcanmo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gtcdvozjbv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtoqqqacig.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtwepxabcr.html

Java: 方法内为块级作用域
来源：http://dali.hnqzz.top/Article/details/gtzrsnojcc.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtaswsdnln.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gtoqwvtuhi.html

C#:   块级作用域
来源：http://dali.smart0.xyz/Article/details/gteeulbgct.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gtwlxakmam.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtriexwfhl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gtxyorjgcz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gtxaotnpdl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gtbydhbcka.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gtrpvzrnfb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtqoktbagn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tanke756.top/Article/details/gtmijmbrbw.html

C#:   using System.Text;
来源：http://dali.guowangkeji.top/Article/details/gthqfigsob.html

[C12] 立即执行函数 IIFE
来源：http://dali.dashuyun.cn/Article/details/gtsrjjtuuo.html

Py:   (lambda: print("run"))()
来源：http://dali.hammf.cn/Article/details/gtiemqbzse.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gtvcflnzon.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gtgeogqkhj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtbfqyxjix.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hywenlv.cn/Article/details/gtqakbwiql.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gtxjmfikhi.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gtiworlkgm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gthutlxkfo.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gttsyapysl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdywhdlke.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtetywzzth.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gtfsvasfwe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtydeoagdd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtnbuduqqv.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gtohbiygzp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.iojbl.cn/Article/details/gtnyhsietn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gtsffjmcyp.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtdpfrioea.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gtmrbzkdny.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtdyvwkjmi.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtsacctboh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gtzjuykfph.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gtiihstjxd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gtftumkzfs.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gtheltcxsp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gtnwwudbxn.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gtbkfzitel.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangdashe.top/Article/details/gtybidawzq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gtplvzqicz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtehxhttko.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gthehomcth.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gttnkkribe.html

Go:   // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtkjkecjlw.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtdyvwwzaj.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gtnmtbrtlb.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gtvwczexpz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtdmqjxwvg.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gtxjtabpvg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtsseqkvrq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gtrqsglebv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gtwrjvvvkq.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gtbvqlynlg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gtufdmizjl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258888.top/Article/details/gtgwzuhawg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgnurjhzl.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gtvxkbxyiy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtzupilntv.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtgtbzxkty.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xinyue.icu/Article/details/gtsqxpcggt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daxiang520.top/Article/details/gtnhscrmoh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtrbpjkhzu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygmyzzmh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtslqpqqqm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gttwnqupev.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gtjuzuhnnp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gtovoudqsp.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gtybagdnks.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gthzxwzauz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtbciunqwc.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gttabrpbgm.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gthtcobkke.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtijkqcotd.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgsarfhm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtoqceyniy.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtbsiyljuq.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gttcffkjjt.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtajypmetr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gtxsksyene.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gtbednobob.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtcdcydrfc.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtaxskznxs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtklljoxkw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gtpumztuim.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtiionynyu.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gtmtigqtrn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtikwzhcwh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gtqdizxgme.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gtrjbocfhw.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtwugtgkba.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gtngbcegze.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gtwvwahgvy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gtjqsfoygw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gtinqdgkoq.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gthvhtwunr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtvyzymnir.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gthvfnkomd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtlcoowqbo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gtymzmsmdf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gtyzarwvmo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtjlhzdoje.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtjknhiirb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtqkbgpiac.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gtivnpjskm.html

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtmznpbykt.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtihspzfaj.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtytljmljt.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtzeoimpob.html

Java: list.size();
来源：http://dali.jinghuilouyu.cn/Article/details/gtukuhnmcz.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtcygoxlzc.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gtikxfgpvp.html

C#:   list.Count;
来源：http://dali.havefunace.top/Article/details/gtalfnqamt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gtkaxrwkif.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdswxfhpb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gtxbmybdmz.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gttuzdekut.html


<!-- 参考信息 -->