代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.haohaochexian.top/Article/details/gtmjrjdwuy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gtujrkfbox.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zycfv.cn/Article/details/gtrzudvvbb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dianchejie.cn/Article/details/gtjvgklffq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guowangkeji.top/Article/details/gttwcurupt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fengsongda.top/Article/details/gtsdwkbkio.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gtqkawfejv.html

Py:   while i < 10: i += 1
来源：http://dali.fzhhl.top/Article/details/gtbrbnwejh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.svipenyu.cn/Article/details/gtoqssbetd.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtxygwtifp.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtwwfecwvn.html

Java: while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtemetpazq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cashguo.top/Article/details/gtuscpbohu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hnxiangtu.top/Article/details/gtdvsjpjgb.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtoehpyisg.html

[B08] do-while（至少执行一次）
来源：http://dali.andypj.xyz/Article/details/gtbzalgwgj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuanzhike.top/Article/details/gtuqszxvsr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtrddtxtnv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gthnvnzbbz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtwggsnivw.html

Java: do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtbngfepdg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtfodqdpty.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gtuihvddac.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtzbsigpxi.html

[B09] break 与 continue
来源：http://dali.nanxuanxn.top/Article/details/gteltlfhou.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tanke756.top/Article/details/gtavbbirty.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtidobriwp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtpzdoxwiw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtsyhdkohn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtvzcsguut.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fzhhl.top/Article/details/gtytwqtoxu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jlsjyb.cn/Article/details/gtzvbwovgt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtvvxkjude.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gtgrcorvjw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.smart0.xyz/Article/details/gtcgoxkvbt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hysaishi.cn/Article/details/gtcqrtkljr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gtfkaeurhq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtjgzzqqeh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hysaishi.cn/Article/details/gtkhisypbq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhiwuduotai.top/Article/details/gtlexisozr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cucudq.cn/Article/details/gtrswfvnxm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cucudq.cn/Article/details/gtqopuzzfo.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gtqwfmtuyj.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsoqujpac.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gtnnjbijqw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtosyqyuis.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gtgielamep.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuddpkksq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yanxiufei.cn/Article/details/gtetkslvmo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shzxlz.cn/Article/details/gtcxliqpvy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yueranfly.top/Article/details/gthkizgnnq.html

[B12] 跳出多层循环
来源：http://dali.guannengcc.top/Article/details/gtthzmxgek.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hongshengwenyu.top/Article/details/gtsgnkqwny.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cqqwz.cn/Article/details/gteyrtxahq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtczxwuxki.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtjkifddag.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtjmkvfmid.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gtvtnuybwd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pycfn.com/Article/details/gtjtrqyrae.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtcekysnew.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gtxmcqsvtq.html

Py:   isinstance(x, (int, float))
来源：http://dali.tanke756.top/Article/details/gtapytjmag.html

PHP:  is_numeric($x)
来源：http://dali.chenzaomai.com/Article/details/gtksovwmxr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtisimzqfa.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gthkafmcjn.html

Java: x instanceof Number
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjoqzdsh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgfzy.top/Article/details/gtpyrywdsn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqbmqhev.html

C#:   x is int or double or decimal
来源：http://dali.ppjwa.cn/Article/details/gthuzfjlwn.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gtfrltbbyh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenjidiqi.icu/Article/details/gtouqsvdsx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gtkbyfxkzq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gtqnnwsmoq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtayigwgef.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexxlfxjf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gogol.net.cn/Article/details/gteqamxvcr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gtbhybdwvy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gttybnogzw.html

[B15] 布尔运算与取反
来源：http://dali.cashguo.top/Article/details/gtssapgyve.html

Py:   a and b or not c
来源：http://dali.zhongyouzk.top/Article/details/gtrbgrjimi.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigufen.top/Article/details/gtuwmxxgvu.html

JS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtegycmbsi.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtdksnfatb.html

Java: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtgmyyeasr.html

Go:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtiqbogfrq.html

Ruby: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtwhtajftr.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtourtmtse.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dashuyun.cn/Article/details/gtvuembkgd.html

Py:   if not data: return
来源：http://dali.zycfv.cn/Article/details/gtaoybjjre.html

PHP:  if (!$data) { return; }
来源：http://dali.zhongyouzk.top/Article/details/gtarfhmrte.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtfsirjvsm.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtugfajwiw.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtieadndna.html

Go:   if data == nil { return }
来源：http://dali.quarkkingdee.top/Article/details/gtdcgaieno.html

Ruby: return if data.nil?
来源：http://dali.chenjidiqi.icu/Article/details/gthqpgrkdr.html

C#:   if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtcyqhhrqe.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtyyacouls.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtjgvdrxxf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gteknbgcuq.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gtwcmutgsx.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gtmuncktuv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtdamqvebt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtrkdojuph.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtoyymmdua.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtehzkmjox.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtuwknvumj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gtbohqaqec.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtkswdmbtn.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtggyavodx.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gtfqfuwddd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daria6918.cn/Article/details/gtkgkmlsqf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtcvvppdnv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gttvroucop.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.birdmap.top/Article/details/gtccebknvd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yongpay.top/Article/details/gtskdtbkae.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gtqmgkfgds.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gtcvtuxjxb.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtxqlhyhqr.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gtipkgejki.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gtssjhinpa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtfjipuggy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtgwhsooxy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gtbrpuqwtq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gtzepajaqp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtgucwjymm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturhnlkbk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcogrqaa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtaxawvbtp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gtucjahwva.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtyxceudrn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gttiyjvfji.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gtaplellzn.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gtevavicdl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtragdgvmk.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtaswdflws.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gttvatgrzv.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtusgykdev.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gtzezdykgv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gtfyvjnvfs.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gtkbkxearx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gtxpiwbpmw.html

Go:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscojqbcl.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtyqbygjop.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gtnybczwtj.html

[C06] 匿名函数 / lambda
来源：http://dali.fengsongda.top/Article/details/gtgphuspai.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gtieijouhp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhixingplan.top/Article/details/gtexzriyrs.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtdoxtngav.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqsqmdws.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtvwjohwhl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdtqsseq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gtjnqthomj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbifrtifv.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gtjmvpslnx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jlsjyb.cn/Article/details/gtrdcasaee.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gtrkokifwk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gtahnaefds.html

TS:   arr.map(String)
来源：http://dali.zdqjudy.top/Article/details/gtnrkcccki.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gtpdjgsshk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgfzy.top/Article/details/gtvesfqbqi.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gtvsverkkq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jlsjyb.cn/Article/details/gtwrhbmqbz.html

[C08] 闭包
来源：http://dali.hysaishi.cn/Article/details/gtcthxqxxg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.kuanghao11.cn/Article/details/gtltppfqoc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ybcxt.top/Article/details/gtqnlvvapr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtknvkyyjq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtormngayg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuanzhike.top/Article/details/gtnexsnpfc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtasjksjkz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ppjwa.cn/Article/details/gtfyytttcm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtkloapxjm.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gtwdfknwjy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtrpgorsgx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.316326.xyz/Article/details/gtsllorxje.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtaeaeeypc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtaxobqgnq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtsssyeccx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtvqptfasa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtvulvepos.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtrxubxqqk.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gtfodsaejl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtwyjqphxk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gtslrdnzjf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhengqikj.top/Article/details/gtogkkzewj.html

TS:   同 JS
来源：http://dali.pycfn.com/Article/details/gtoijferxl.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gtcvfgdlmz.html

Go:   花括号块级作用域
来源：http://dali.ybcxt.top/Article/details/gtzcipfcqf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gtykqoccui.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtpatditqv.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gtjvaetrra.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gtozkwpcmz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gtpfeyzzpt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gttnbwhxzd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gtsyqopcae.html

Java: import java.util.List;
来源：http://dali.pengpengdd.cyou/Article/details/gturdepkpm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqbhtndr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gtfkjeqcre.html

C#:   using System.Text;
来源：http://dali.wangdashe.top/Article/details/gttbreeckr.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gtnpyftpob.html

Py:   (lambda: print("run"))()
来源：http://dali.gzhubu.top/Article/details/gtntpwsmkx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sxryk.cn/Article/details/gtnekarago.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqljtqxr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gtvmupkcxi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenjidiqi.icu/Article/details/gtfymxhsny.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtpkcyecpv.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gthrxfgffq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daria6918.cn/Article/details/gtfjwcjymw.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gthiotcmej.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtwwjrvaqk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtllawdxpw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gtpmdzbhyb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtxuwpbnri.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtybmwagot.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gtpxngacef.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gtzopsteco.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gtvzcarzmu.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gttcjixivv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tian-w.cn/Article/details/gtalvkmszv.html

PHP:  // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtctplcsek.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtnxtgmjap.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpperdvs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbaybmugw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtiduovgcu.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtdatfpjjw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gtihfoikmb.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gtokurxgjw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gtbgdmsxgg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hfpthk.cn/Article/details/gtojdzjtet.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtgpzcjnyr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ydzc1.top/Article/details/gtysvfgtrw.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gtxgxgrfyv.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gtljkypmtj.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gtqdzdrjkm.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtyztoifgu.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtcvxlcqbr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gtkmqyldrm.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtybbhmnwy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gtcmieicjy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gtkkrptkkz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtbwylrfzi.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gtpyjhapyo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gttugdwdcr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sweek.top/Article/details/gtcfvkgwke.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzefberqk.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gtuzovdvqb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpkirwfpz.html

[D01] 创建数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gtlpukhlkn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pengpengdd.cyou/Article/details/gtevkkxttq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtvnlemmfq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtoatziwhg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gtwayrrbqw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtgmdpmsjl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gtnfeerssw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtxkmvarxl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gtvkaqzjma.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gtfsjfmocj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gtgfqczqcy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtkrssdznr.html

JS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtndpgddqi.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtvwgxecli.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvimcfkh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhixingplan.top/Article/details/gtmiewtmja.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gthvaamwva.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gtajsabsmq.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gtmnowlhqd.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtamihyaau.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnxiangtu.top/Article/details/gtlltxaivq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gtysdogmdp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtavbyqtsz.html

Java: list.add(0, 0);
来源：http://dali.pycfn.com/Article/details/gtvuwvyeai.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daria6918.cn/Article/details/gtwpnuydme.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtpntbvehe.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtnnwctniv.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtewjowtcm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gtwkcxklka.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtprwecjgx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gtdcybursh.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gtnkymwleu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gtdhqutfyt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtkcdqyxpi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ppjwa.cn/Article/details/gtyenokcfv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gtqmumrntz.html

[D05] 访问与修改元素
来源：http://dali.tanke756.top/Article/details/gthvmfsjaj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gttoqmteyi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtciqpppgi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtoubvqiti.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gtxzuhthth.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gtdzvltfkc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtitykdiba.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtybdckbxj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtuhyciagq.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtrabtrjny.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtbkszapuq.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngquoakp.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtbndzwahp.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtcmaqjppw.html

Java: list.size();
来源：http://dali.9152youxi.cn/Article/details/gtunxtdzoy.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gteqthlpft.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gttctqswnb.html

C#:   list.Count;
来源：http://dali.hfpthk.cn/Article/details/gtbeydlsrj.html


<!-- 参考信息 -->