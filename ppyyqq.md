代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxuanxn.top/Article/details/gtmyksrfnt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cheryme.top/Article/details/gtitbylmbs.html

[B07] while 循环
来源：http://dali.fengsongda.top/Article/details/gtzcmrutiu.html

Py:   while i < 10: i += 1
来源：http://dali.gzhubu.top/Article/details/gtmanyevfv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yvedp.cn/Article/details/gtckfxluiz.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gttbwrvfiw.html

TS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtryzanzpu.html

Java: while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtdyvokgsg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ivvv.top/Article/details/gtllzgpmuu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cheryme.top/Article/details/gtgqfqnvkl.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtwaldfxgx.html

[B08] do-while（至少执行一次）
来源：http://dali.sxryk.cn/Article/details/gtauobylwy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gtsumnaooj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jianghu66.top/Article/details/gtnybkkgpu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtcnkqlwcz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtzosfleho.html

Java: do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtnctcepiq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gtfggwbxya.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.bjfxy.top/Article/details/gtghcqvdmy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtivthxdog.html

[B09] break 与 continue
来源：http://dali.chenjidiqi.icu/Article/details/gttsrpihum.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.andypj.xyz/Article/details/gtularrxmb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtxjtdnkns.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gttdpfxqwa.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtfkrnicqc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtjkbftdfx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daria6918.cn/Article/details/gtqjlyflup.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yvedp.cn/Article/details/gtkdgzgzns.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtsjrzsnyc.html

[B10] 遍历同时拿索引
来源：http://dali.0kj1m.cn/Article/details/gturkhuczw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yongpay.top/Article/details/gtauemcgez.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nwbrower.top/Article/details/gtonfncrsi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtpltgmdwh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtcvwjpnkb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yonumen.top/Article/details/gtylyfgzrp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gtwybppxed.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xylfe.cn/Article/details/gtfpdzfexb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gtfljjxaso.html

[B11] 生成数字序列 / 区间
来源：http://dali.gzhubu.top/Article/details/gthjxdhtor.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gtawjgmfaw.html

PHP:  range(0, 10, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtsqnndtyw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtfcfmirqn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtagrynxai.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aibaodan.cn/Article/details/gtfleuwenq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gtxlblzzug.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuxming.cn/Article/details/gtilvmqzpg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jlsjyb.cn/Article/details/gtqrvvttar.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gtwujpeymz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtburqpopz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hysaishi.cn/Article/details/gtulnlxzjq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtrhenvncr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtobcpyqig.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtwlxyhkrm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gtuwbspkug.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhoulong.xyz/Article/details/gtryiglrtf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.birdmap.top/Article/details/gtrdolmleb.html

[B13] 判断是否为数字
来源：http://dali.bjfxy.top/Article/details/gthoutdyac.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtgyngazkf.html

PHP:  is_numeric($x)
来源：http://dali.zhixingplan.top/Article/details/gtdwbvteha.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtncmoiyzs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtvdwjysfk.html

Java: x instanceof Number
来源：http://dali.nanxuanxn.top/Article/details/gtlhkzibyy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zdqjudy.top/Article/details/gtmhwlledu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.iojbl.cn/Article/details/gttijllpgh.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gthuradvda.html

[B14] 判断值是否在集合内
来源：http://dali.zhixingplan.top/Article/details/gtwjzbfvmz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gotoacloud.top/Article/details/gtzihdcsfh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gtyfupypih.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtsjqekjdg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gttyvyvsmt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xinyue.icu/Article/details/gtaaljxrzq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gtjfxakaog.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gtecycpcfs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtxqedoihk.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gtpeffomyh.html

Py:   a and b or not c
来源：http://dali.hongshengwenyu.top/Article/details/gtdnfdrvva.html

PHP:  $a && $b || !$c
来源：http://dali.kuanghao11.cn/Article/details/gtjusppshe.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtuqntjdwk.html

TS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtjlbavzdo.html

Java: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtvzvqwfye.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtfzbpyqje.html

Ruby: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtgmxdzxwl.html

C#:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtjsijhojy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yongpay.top/Article/details/gtmwiyjaak.html

Py:   if not data: return
来源：http://dali.yvedp.cn/Article/details/gthjqgdzgj.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gtrjlajzbn.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtmmsetfim.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtmbzzoclw.html

Java: if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtiqzjswcx.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gtgxjvnnat.html

Ruby: return if data.nil?
来源：http://dali.aibaodan.cn/Article/details/gtnqfmmnzh.html

C#:   if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gtqjfbbgpe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrwedquml.html

C. 函数与作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtcngiirvs.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjopezahq.html

[C01] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtquwmtohr.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtrfjqtzpf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbledmszc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtzxwpqsqx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgccgkyhq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtjlrxkwpj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtjbszzifi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxzxriwn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtflqkecne.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gthhesolbs.html

Py:   def greet(name="World"): return name
来源：http://dali.havefunace.top/Article/details/gtzvepnsyj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sweek.top/Article/details/gtueprrlei.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtqqixmopm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gtycrpuxpk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gthlpghnke.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shangyingyoupin.top/Article/details/gtymfiqjxq.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gtwewhrior.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gtcshuyavb.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gtebhuvlzy.html

Py:   def total(*args): return sum(args)
来源：http://dali.jiagoushi.top/Article/details/gtbpbldfkq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gtwyxahqnw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtukgnhdwf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtoeiboqbo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtpvothbpo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gtkwzefwmr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shuidangran.top/Article/details/gtkeishgei.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dianchejie.cn/Article/details/gtzbrmdsoh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gtjemhncuo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gtzqmrszvb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gtjyzwdmje.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtinoirxvm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggxcggxc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangdashe.top/Article/details/gtaxvruaqv.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gttvraxylu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwpgtsyb.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsimuopbe.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtfhixqmbk.html

Py:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gthsdbyxci.html

PHP:  return [$a, $b];
来源：http://dali.chenlongwang.top/Article/details/gtfxrefssy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gttivvlmyu.html

TS:   return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gtitdpqrru.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtprnivsnf.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtwquzfvqz.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gtgagutdpb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gtuaskwhzl.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gtocppmsnp.html

Py:   square = lambda x: x * x
来源：http://dali.xuanzx.com/Article/details/gtufssuuid.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.smart0.xyz/Article/details/gttuqbqhxp.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtlnjyzjoc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gtrgqsgyvp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtwweamnqo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zycfv.cn/Article/details/gtbgojlcyc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dashuyun.cn/Article/details/gtjgjkhcba.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtacknzkdj.html

[C07] 把函数作为参数传入
来源：http://dali.yongpay.top/Article/details/gttafqbgbs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttopgznww.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsqefhnc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hywenlv.cn/Article/details/gtcjbwvnqv.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtfcbqudvp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gtjlrlkyug.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aizwys.cn/Article/details/gthjzensxf.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gtcqykggdd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gteeswvtff.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gterylkehi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.andypj.xyz/Article/details/gtlxrobokv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cheryme.top/Article/details/gtenskdcip.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtslluadex.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtqokuchrw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gaohongyu789.top/Article/details/gtuicfnyms.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.316326.xyz/Article/details/gtcwaxvvxl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sweek.top/Article/details/gtxupreiue.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtrgafjozi.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrphwtgos.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gtjpdeymih.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtiodwojpv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtcnirwpvi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtgrptnsxb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtvpbgnuav.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.bjfxy.top/Article/details/gtzewvglre.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtgvxvrsga.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gtyltrfhjq.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtcslrypeq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gthcktctep.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.andypj.xyz/Article/details/gtmqkgtpxv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hfpthk.cn/Article/details/gtvfdnxxlr.html

TS:   同 JS
来源：http://dali.guannengcc.top/Article/details/gtuuyszfsm.html

Java: 方法内为块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtuvugddzm.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvjpprex.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gtkjebsclk.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gtenmxiojd.html

[C11] 模块导入与导出
来源：http://dali.fengsongda.top/Article/details/gtthnkymio.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gthzmlrxnk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtamusopmb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gtdlhsvhlj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnxiangtu.top/Article/details/gtqkjcxhxm.html

Java: import java.util.List;
来源：http://dali.xinyue.icu/Article/details/gtseyjfwxt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gtjhqzvbsc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gtpcunmpkm.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsrgeoam.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gtxwknnnso.html

Py:   (lambda: print("run"))()
来源：http://dali.haohaochexian.top/Article/details/gtxxqnghxk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtmshhwzku.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtwnbwazwh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtuzlvruew.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gtvwhncsfm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gtgtsprjay.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtucfaldxu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gtxwswwgup.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gtrkqxpppx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtbndtkkxd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtcfvzszzr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gtxeskjucw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtohliwqrk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtbbjxbzru.html

Go:   func add(a, b int) int
来源：http://dali.cashguo.top/Article/details/gtsyiymqzn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gteiwzhhyl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jlsjyb.cn/Article/details/gtmupfyvmh.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gtddeqqffs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gtocbvqiyk.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gtlsrbbqpi.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtkxkinjdz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gtmzjhjsbb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gthtqkumsw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gtstkrpoke.html

Ruby: # 无泛型
来源：http://dali.c1oappe.top/Article/details/gtemojzxdb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gtgwibigfz.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gtmoanmsoq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangshuangyany.cn/Article/details/gtrqcqsspd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gtgfwriuya.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtwriuuiwt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gtxfgwpgua.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtglrnptuo.html

Go:   // 无解构
来源：http://dali.ydzc1.top/Article/details/gtelybumbv.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gtqfqzkjoj.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gtrijqjzry.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gtthtglkzl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gtxqxexvpg.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gtusvubnmq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnqzz.top/Article/details/gtcglfgwmp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gtbfhokejj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtejhcqtit.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenzaomai.com/Article/details/gtfbycgaby.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zycfv.cn/Article/details/gtutgryxoq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gtkvjjiyot.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtenzkevvt.html

D. 数组 / 列表 / 集合
来源：http://dali.yuxming.cn/Article/details/gtyxsssvah.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnqdvcvwb.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtsgevldgp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guannengcc.top/Article/details/gtghfcwqyq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.mhx1999.top/Article/details/gtzkfjtmfa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtnihytrfr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukpozeve.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.quarkkingdee.top/Article/details/gtrcoobdlu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gtwjdtflkh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtthptcpwi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gtzpeuvmjh.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gtnvdwyqkf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gtxlszbjlc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtinkcnqnb.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtbqlmhwcc.html

TS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtxbpxoruz.html

Java: list.add(4);
来源：http://dali.316326.xyz/Article/details/gtudsfufli.html

Go:   arr = append(arr, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtnngasbwh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtqammokwv.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gtpzpxigqc.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtbtdsruut.html

Py:   arr.insert(0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtkepltnsr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gttplvktab.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.smart0.xyz/Article/details/gtdfvzcyfm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhengqikj.top/Article/details/gticzmikdq.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtjslwgzei.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtjugbuzhc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gtgrchjdxx.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gtunlzpmpu.html

[D04] 删除元素
来源：http://dali.nwbrower.top/Article/details/gtjymhllpo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenzaomai.com/Article/details/gtrbarqwux.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.meibo888.top/Article/details/gtyelrialu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.mhx1999.top/Article/details/gtfuebjaad.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxinkj.top/Article/details/gtrwcotwav.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gthvltmmyb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gtzbleprwm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtlhjrhoxf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gteguglqqy.html

[D05] 访问与修改元素
来源：http://dali.meibo888.top/Article/details/gthlbntiiz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtkklhpqre.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtahvdxwgh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtdhdweipo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.quarkkingdee.top/Article/details/gtviyxacbx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gthtzqmubn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtujfomhkg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtfjdfbnxv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtjazzebgn.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtitetwzzu.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtodfumdix.html

PHP:  count($arr);
来源：http://dali.yueranfly.top/Article/details/gtzqgkbjmn.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtgnrywmzc.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtranawdvp.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gtucswscxh.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtryhlbtnk.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gtbojwswyf.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtpadyjurp.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtsmnqykfj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.quarkkingdee.top/Article/details/gtgbhhthki.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxkdkkdm.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtlbyjzfyy.html


<!-- 参考信息 -->