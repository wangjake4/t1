代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenjidiqi.icu/Article/details/gtlgrmwyzh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jyoumei.cn/Article/details/gttycxgqna.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtjhedptbx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtnodzoyof.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtfjxzheib.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.andypj.xyz/Article/details/gtrslfbuur.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.svipenyu.cn/Article/details/gtavywwdou.html

C#:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtctoyvyoz.html

[B09] break 与 continue
来源：http://dali.shangyingyoupin.top/Article/details/gtablauraz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgfzy.top/Article/details/gtrenpvylg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtbhxkhklb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtgjsootsr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gttmhpygqu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcsevgjx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gtcmesvbqb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tianlin.xyz/Article/details/gtzilqucpg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtmvcsurym.html

[B10] 遍历同时拿索引
来源：http://dali.yuxming.cn/Article/details/gtfszkucej.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gtpngmlnfa.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gtxbblspqk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtsgpdtfbi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gtfbshkwup.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuanzx.com/Article/details/gtnszcdqca.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gtsnsdwebo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cheryme.top/Article/details/gtkqcwskpz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gtxwefslzc.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gtyyxvjbdp.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgfzy.top/Article/details/gtecstsvmi.html

PHP:  range(0, 10, 2);
来源：http://dali.yuxming.cn/Article/details/gtojthnucm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gtzhchldoo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlprtxemo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cashguo.top/Article/details/gtebpgmxem.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xylfe.cn/Article/details/gtkqeuinzb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.c1oappe.top/Article/details/gthakjrpwo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.mhx1999.top/Article/details/gtyvzebxbf.html

[B12] 跳出多层循环
来源：http://dali.xziqi.cn/Article/details/gtblnxwltl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shzxlz.cn/Article/details/gtgpgwqhkx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuxming.cn/Article/details/gtwhxdgibu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtokpxjvqa.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gthnfnqxfm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtqdeazoep.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhongyouzk.top/Article/details/gtlawomifj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hammf.cn/Article/details/gthqnlobxt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonzlsqbl.html

[B13] 判断是否为数字
来源：http://dali.yuxming.cn/Article/details/gtuudqznhf.html

Py:   isinstance(x, (int, float))
来源：http://dali.sweek.top/Article/details/gtznyfxxyj.html

PHP:  is_numeric($x)
来源：http://dali.redwolf501.top/Article/details/gthjsvsmrn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gtxnkgysrl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gtdwqjumfi.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gtcedseqib.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gttbezbvpn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gtectoujyu.html

C#:   x is int or double or decimal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzhmlkle.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gtznairxmm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yanxiufei.cn/Article/details/gtdgukcdeo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hysaishi.cn/Article/details/gtokxzjbkg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtbxqaiswe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtusyvmpgy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gtlsbhwcwq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258888.top/Article/details/gtosggqcrx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtutidomtt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtgjxqcmbk.html

[B15] 布尔运算与取反
来源：http://dali.zhiwuduotai.top/Article/details/gtktezazlc.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gtubptenuj.html

PHP:  $a && $b || !$c
来源：http://dali.xylfe.cn/Article/details/gtihonigty.html

JS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtomgjvsch.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtdunowfnl.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtdbifdbwg.html

Go:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gthidyfzxu.html

Ruby: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtkbgfhawv.html

C#:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtzflijzqw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtftepewec.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gtjnhnixqh.html

PHP:  if (!$data) { return; }
来源：http://dali.gzhubu.top/Article/details/gtrebbppmd.html

JS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtdmbonuos.html

TS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtkmqcbkwv.html

Java: if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtzuyddqux.html

Go:   if data == nil { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkarqowhd.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gtjdqlwnhn.html

C#:   if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gtuhgtegaj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwzhomesy.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtvudactsk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtskwhkfsy.html

[C01] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtpdvzqibv.html

Py:   def add(a, b): return a + b
来源：http://dali.chenlongwang.top/Article/details/gtlfirvttm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtrnyomfbe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtferuwhkn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gttzhvzyzd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtwohdhiog.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gtpkypgiqu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yanxiufei.cn/Article/details/gtilbgxicv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtuevacazg.html

[C02] 默认参数
来源：http://dali.mhx1999.top/Article/details/gtuvrqvqbr.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gtkdrnkbjx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gtekmkzoqa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gtpchqnopd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtayfltsgm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gtyqegwfov.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxynyixvj.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gtvibaawqb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtnhwkvxat.html

[C03] 可变参数
来源：http://dali.xuetiantiany.cn/Article/details/gtgcuupthr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthngnkynp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtsomsunee.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtckjzpzxq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gtslshomur.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gtmwywbzii.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tian-w.cn/Article/details/gtbiyalbtf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gteonzhwao.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.0kj1m.cn/Article/details/gtmozgsefq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gtttgfckhb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuanzhike.top/Article/details/gtqqqozeyx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtgdmnhpvx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtlspwzfbd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daxiang520.top/Article/details/gtwpsvgbmo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gtexifupzu.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuejeuhax.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtoknbzhiv.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtoytplkaf.html

[C05] 返回多个值
来源：http://dali.ydzc1.top/Article/details/gtmcerahlc.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gttccanllq.html

PHP:  return [$a, $b];
来源：http://dali.pycfn.com/Article/details/gtdnwvyepo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gtvrbaqrcj.html

TS:   return { a, b };
来源：http://dali.yonumen.top/Article/details/gtuatveolo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xziqi.cn/Article/details/gtijdtulgm.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtbpkidtho.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtherxgzpt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gtkbxcayda.html

[C06] 匿名函数 / lambda
来源：http://dali.gaohongyu789.top/Article/details/gtytgwuadl.html

Py:   square = lambda x: x * x
来源：http://dali.feifeiyinyue.top/Article/details/gtaxxeukar.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtuqjaaimf.html

JS:   const square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gtalwypzaa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtxxdmsikn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.c1oappe.top/Article/details/gtgifkvxyi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.andypj.xyz/Article/details/gtleipqkko.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtvlevkxky.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtkebajgmh.html

[C07] 把函数作为参数传入
来源：http://dali.sysykeji.top/Article/details/gtbxfjflrj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtougjbefn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhixingplan.top/Article/details/gtzicygxce.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gtdqmmfuig.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gtqimulogk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ppjwa.cn/Article/details/gtrojqmmxq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwdchzew.html

Ruby: arr.map(&:upcase)
来源：http://dali.bjfxy.top/Article/details/gtmzcqurbi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gtrdnlqcow.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gtkweinaat.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gtbjnpnpiq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aibaodan.cn/Article/details/gtjweusbvq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtovcrvwya.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtfibpkedk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.redwolf501.top/Article/details/gtrjujhsgr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhengqikj.top/Article/details/gtfjgogrwd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zdqjudy.top/Article/details/gtimlweoln.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtmsqwsmki.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gtetcgzvrt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtspesrxua.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtphyzqoyx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gtzdiuueje.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtmtxpilrr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtxirnvbiz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gtkpkezldp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtkqexyhut.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gthcuqvrwx.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtjmqiszen.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gtsmqcqrnk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.9152youxi.cn/Article/details/gtyyuheayu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shuidangran.top/Article/details/gtiunuvrnt.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtxtxwxlci.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtfvtmesxr.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gteavlmcnv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gtbhuupifc.html

C#:   块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtmlctohce.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gtahsmkwku.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gtxrxisucg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gtvoegjten.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtjkkcifdx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gtmuixuxrd.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gthfqfgdam.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fengsongda.top/Article/details/gtewgoqggz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gtvvxbsaic.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gtpcpkxcol.html

[C12] 立即执行函数 IIFE
来源：http://dali.cdnleiting.top/Article/details/gtxpyusyfb.html

Py:   (lambda: print("run"))()
来源：http://dali.gaohongyu789.top/Article/details/gtnxkqmaxc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gtrlqkhyjx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtnextssdh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtcqgwvznb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gtilcnreuc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigfzy.top/Article/details/gtoxdpttet.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gttujjjjak.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gtijvehrze.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtiwwzklrk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shuidangran.top/Article/details/gtenwovhhh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtvbfzmlfy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtpfdivcge.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxmobchmr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtvfqpqqsv.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gtgoithivy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gtpwasafjo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daria6918.cn/Article/details/gtgawmeilb.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gtebtriric.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gtdpzcqodh.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtwjmygxsb.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gthasxltoi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gtshjoipdp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gtqdnmtqii.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtwhvjzgzh.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtpiobgqyv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cashguo.top/Article/details/gtrtrvgzhr.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gtnbonwguo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gtjqfiedzn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.c1oappe.top/Article/details/gtrniqxoxp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtzzffozaw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtnbmjzrqb.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtnroykuca.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gtxpxqvsvy.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtxxbpmaxv.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtfbyzbmnr.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gtyjlriafn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdyoevjg.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtgorymhua.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gthjunbeow.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.0kj1m.cn/Article/details/gtnaiwsjzq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gtjnfhquca.html

Go:   // 无重载：用不同函数名
来源：http://dali.gaohongyu789.top/Article/details/gtwkpjowol.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gtmwgmrwny.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewyglqnk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcbiaspeq.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gtvjpmrjgg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtomqsnkrs.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtwodptzdr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gthervsnuw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gtzseolite.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtsaebwndr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gtwxyixrta.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gtofrhdfwj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gtwjtaalnf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gtwfwcsfzx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtauezuveo.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzruzequ.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gtvbdrrbcd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.redwolf501.top/Article/details/gtxgwhpwcc.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtnwdipoij.html

TS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gtmuieiiyd.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoctyllk.html

Go:   arr = append(arr, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtoaozalyt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tanke756.top/Article/details/gtqhgsuooj.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlijnkqdy.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gtwjgbguar.html

Py:   arr.insert(0, 0)
来源：http://dali.c1oappe.top/Article/details/gtosstxkik.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sysykeji.top/Article/details/gtfoxfhxrh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gtrijpgafa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtsreklfmd.html

Java: list.add(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqegewsjc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gtpwrkijfg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gtkinhwwrd.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtkqamdhfw.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtatgswrel.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenlongwang.top/Article/details/gtconlrpcd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtcixwvvgp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gtwgtbguji.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtgzwunofx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gtmadfjwmp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gtxpjegbvy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gtoebejtlf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyervrcyv.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gtlbjulbcm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtdxxepuru.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gttpkvbryz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtekaqueze.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdbolyox.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gthbxyvppg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtbtufcnii.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtptzmybta.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtlligcage.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtarksmbjj.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtpelqrzib.html

PHP:  count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtbflxvteg.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtiuwfibsa.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtdawdwsqx.html

Java: list.size();
来源：http://dali.sufxvd.cn/Article/details/gtqodrfayj.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtfollzlgr.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gtblgslehd.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtfanmduxf.html

[D07] 切片 / 取子数组
来源：http://dali.9152youxi.cn/Article/details/gtjxqkjsrj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gtrxsykhre.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtxiijywym.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbhizuwk.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzgudtzx.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gtsybblcec.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gtkqrzlhlr.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gtinrbnoop.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtmhfvqjgy.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gtvfhjhpuf.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gtodqenkyk.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gteuilprxw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtlyrkhfso.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gtyzvrimjz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gtkarhttav.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gtssdijeuc.html


<!-- 参考信息 -->