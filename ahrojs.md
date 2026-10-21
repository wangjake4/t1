代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xylfe.cn/Article/details/gtgztsjxdz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ppjwa.cn/Article/details/gtvbiuipdz.html

C#:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtkwcnxrzq.html

[B08] do-while（至少执行一次）
来源：http://dali.hammf.cn/Article/details/gtbmokrzdo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.guowangkeji.top/Article/details/gtanryapwm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtrlxbsknt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtrfdqfbvu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtzsxizhgn.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtcoezdiix.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtngyruijh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigufen.top/Article/details/gtukntksgy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtftdmvedp.html

[B09] break 与 continue
来源：http://dali.gogol.net.cn/Article/details/gtnvdzmuqu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cheryme.top/Article/details/gthtytjzop.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtzgzautzb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtipnjlhln.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjjtkfxtk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtzweezoth.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gtwiijdiuk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gtcxjprctt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtiklhwfnd.html

[B10] 遍历同时拿索引
来源：http://dali.jyoumei.cn/Article/details/gtwqriwgvk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tianlin.xyz/Article/details/gttchhzkem.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gtjqcdiemp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gttkqtbhtz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtowtaishz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gtfwuixzhs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigfzy.top/Article/details/gtglxygmyc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.bjfxy.top/Article/details/gtyvjzkfhq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jiagoushi.top/Article/details/gtdrtfewfk.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgpjoxaa.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhoulong.xyz/Article/details/gtcvgchrqr.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtweonmhpf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gtbspbrlfq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtttwjbinl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jiagoushi.top/Article/details/gtubjjwyod.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.kuanghao11.cn/Article/details/gtceopkxrs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cqqwz.cn/Article/details/gtzxrazmcy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gtnpsrhvxy.html

[B12] 跳出多层循环
来源：http://dali.cashguo.top/Article/details/gtqcslanyr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gtzhvmczzh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gthytprlml.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtpmiioatw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtcdubxugx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtcintqhic.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ybcxt.top/Article/details/gtjakbiscv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gtlfqemexx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hysaishi.cn/Article/details/gttfdcgzcv.html

[B13] 判断是否为数字
来源：http://dali.havefunace.top/Article/details/gtabjqauff.html

Py:   isinstance(x, (int, float))
来源：http://dali.gotoacloud.top/Article/details/gtapdyrtik.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gtpllkenzc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gtenebvtcd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtmjvlzpdj.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gtakxznrdq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tian-w.cn/Article/details/gtgstfqwsb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tianlin.xyz/Article/details/gttqdtywsq.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gtkksirokr.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtogueowkc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigufen.top/Article/details/gtfyonqpwj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.smart0.xyz/Article/details/gtfzaqvoni.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtwzxnxtps.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtouvlsfyi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtrffcvwdm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gotoacloud.top/Article/details/gtdduszquj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtprpoicwm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnmzdupz.html

[B15] 布尔运算与取反
来源：http://dali.chenjidiqi.icu/Article/details/gtdoomcyzs.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gtxoxdkjvi.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtphyfodfc.html

JS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtrejcnlou.html

TS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtdjlprtmc.html

Java: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtwrhlfnml.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gteiowiumz.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtamzdkbyr.html

C#:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtarkscuxc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtfxveuvvh.html

Py:   if not data: return
来源：http://dali.pycfn.com/Article/details/gtbwkvsgpr.html

PHP:  if (!$data) { return; }
来源：http://dali.hnxiangtu.top/Article/details/gtkylqvspa.html

JS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gtgoogggin.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtrkllfhdp.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtjihocpbj.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gthhgmqruk.html

Ruby: return if data.nil?
来源：http://dali.birdmap.top/Article/details/gtybahxhsx.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gtwjmxghfv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzscvuoni.html

C. 函数与作用域
来源：http://dali.shzxlz.cn/Article/details/gtweixhrqb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtlpjywnby.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtovomuyrj.html

Py:   def add(a, b): return a + b
来源：http://dali.guowangkeji.top/Article/details/gthcqmxrqq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtfoqjlmlb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtppoqsbrl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtbobgckxn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtoeifdjox.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gtkxvqwdgb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtukbsnsus.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtvcqdsgzy.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gtmiiyriab.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfyzomip.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ydzc1.top/Article/details/gtitxckclv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gttrqrlvfs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtkqwidnye.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtwoisojog.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.quarkkingdee.top/Article/details/gtziifshho.html

Ruby: def greet(name = "World") = name
来源：http://dali.316326.xyz/Article/details/gthhszijys.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tanke756.top/Article/details/gtgnbkmilp.html

[C03] 可变参数
来源：http://dali.hongshengwenyu.top/Article/details/gtkoqgsicr.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gthbtveqex.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gtyksfyxhu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtzijuhram.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtdhxncndo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.9152youxi.cn/Article/details/gtctsmcqcn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gtqwdwhbvt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gtrdtghrol.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.birdmap.top/Article/details/gtkxvxwicu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.kuanghao11.cn/Article/details/gtxhovhwbo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yueranfly.top/Article/details/gtvvllimyj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gtdaetfupq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtpkwhfntj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guowangkeji.top/Article/details/gtmuwuphff.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnqzz.top/Article/details/gtgoxwwoun.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gtwfctgevi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gthvxocnxk.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtelfwftos.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gtlcdyegtz.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtvgywjvfy.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gtszjvcpft.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.iojbl.cn/Article/details/gttrliyybk.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gtvpefwecb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gtapmocqkk.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtehkmnofg.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gtnacfbxgo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gttlibbcoj.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtuwxztqmd.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gtwrpuniqe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.bjfxy.top/Article/details/gtuumnxott.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtgptutefk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtblljctqq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdygthvbe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gteleacicb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gtxddzotmy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gttprtghvr.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahhkiisa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtamehbuab.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gthhhmduvi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtwsmuopoz.html

TS:   arr.map(String)
来源：http://dali.yuanzhike.top/Article/details/gtulezjbgy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gtuuwkzosg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gtiqinqmje.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gtjqpoaqpb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gtvkbkazeu.html

[C08] 闭包
来源：http://dali.yuxming.cn/Article/details/gtmewssyok.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtjxxaicua.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gtoectigat.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtxffutfih.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtlcqpbtte.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cheryme.top/Article/details/gttblknnwo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.kuanghao11.cn/Article/details/gtyrsfkvcz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gterehitdi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvhgdzqgw.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtqymiczfb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtchvsykwl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtpobewskn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtandkslxu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtegqgivsu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ivvv.top/Article/details/gtbfypuguj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gtxaklgkws.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtsvygopyn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gtubesmske.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gtybpnztbk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhongyouzk.top/Article/details/gtnzgwywev.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gthlfjcjxs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtufijibns.html

TS:   同 JS
来源：http://dali.dashuyun.cn/Article/details/gtypobpvaj.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gtolkroqiy.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gtnwgtwhfp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.kuanghao11.cn/Article/details/gtpkpvczgt.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gtilniisyi.html

[C11] 模块导入与导出
来源：http://dali.9152youxi.cn/Article/details/gtbdguwxlk.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gtswfnoyzj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofgpjtej.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtoerksvwu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtljrbkcaf.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmyuwoxc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtpqtoypst.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gtfdpxsdzl.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gtkbhhpcqd.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gtpwcteckq.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gtimzmbkxg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gttgbochvc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtpquknzzh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtagnkgaoc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gtulaevfvp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.9152youxi.cn/Article/details/gtanjnkvgk.html

Ruby: -> { puts "run" }.call
来源：http://dali.sxryk.cn/Article/details/gtwpaikqws.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.9152youxi.cn/Article/details/gthmpdglry.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgufenzy.top/Article/details/gtuvlyjyzx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gttcsisiae.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtemwkflqr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gtwcvlpptn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gteoyqibmv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtbmanuroz.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gtucjohwwq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gtsacoqygh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtzebqozxu.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gtktlkoqfo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gtfgerdceg.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtibchkndw.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtwapdowue.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtltiydwpp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gtvmnzyhqq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtbwjcwsin.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gtdjqeipmc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gtthfpxcvt.html

[C15] 解构 / 展开参数
来源：http://dali.wangdashe.top/Article/details/gtotmdkzif.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yonumen.top/Article/details/gtysgehwgh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gtbetwyqcm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtxtbexryp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gthwgwuhss.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtgypscwne.html

Go:   // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtkoloikuw.html

Ruby: a, b = pair
来源：http://dali.jiagoushi.top/Article/details/gtjpshndax.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gtdfkzqooa.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gtbioyqrjs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gtqopeogsj.html

PHP:  // 无重载
来源：http://dali.zdqjudy.top/Article/details/gtwucorlfs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtenqslbgf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmyckfxd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gtdbgvmusr.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gtxwksymrt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gtqennnzxa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gtdodcmmex.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbgqhsjwt.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gtztedtwfa.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthdfvhxnk.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtybtqrhkx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgufenzy.top/Article/details/gtyjvrcguc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gticppezje.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aibaodan.cn/Article/details/gtifzaszkz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gtnxhqeyep.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gthqujocis.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gtgewnevlk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gthevhjbzo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gtljzwaoke.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtlfwmenas.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gtxkbwwwch.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gtdwlhgvsn.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtxkyeyyna.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtehxesimo.html

Java: list.add(4);
来源：http://dali.chenzaomai.com/Article/details/gtatvtjffq.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gtvwrpukhq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtavowdzof.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gtctwgnxaz.html

[D03] 在指定位置插入元素
来源：http://dali.ehwqpu.com/Article/details/gtkbskgrxt.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtxumkypoq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ppjwa.cn/Article/details/gtmdtzjyqi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtkgdstznl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.meibo888.top/Article/details/gtbxqcplpp.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtsrtksvrr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtylofllxq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gotoacloud.top/Article/details/gtsgwhpevx.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtoubakkpl.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtrmkxwbqy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gtnwmhamkj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gtvgzjdwzi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gtuttgsayu.html

TS:   arr.splice(0, 1);
来源：http://dali.jianghu66.top/Article/details/gtjvylzksi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtnlhvvcdi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gtoboaxccl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtnezxirpq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gtykhxugko.html

[D05] 访问与修改元素
来源：http://dali.chenzaomai.com/Article/details/gtxcbyuepu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtjbnmyeii.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtmkdnjdak.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtbswdjjpk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gtjwevxkdp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtiwvcdiur.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtodpfqahs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtzbvqchog.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtvmprtzfy.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtsctgemnk.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtjtxtnytt.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gtvowgdgkx.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtgaznscdm.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtwchpxkys.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzbrgkvq.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gttneznido.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtuxejstfu.html

C#:   list.Count;
来源：http://dali.feifeiyinyue.top/Article/details/gtpmasxxuq.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gtaeqdvbnh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtrvvbuxvv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gtzryrylry.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtxhcnmixt.html

TS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtuvmokelb.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtonbqfhkf.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gtxhhrnwun.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gttgqpngci.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gtsqfutlkt.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gtbgvmfbxj.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtrdedoocp.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gtnossbuwn.html


<!-- 参考信息 -->