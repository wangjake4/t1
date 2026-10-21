代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.ybcxt.top/Article/details/gtgmcwpsap.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258888.top/Article/details/gtcqxtcark.html

JS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtfnamuqib.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtwcbkmsle.html

Java: do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtazhzffrh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cucudq.cn/Article/details/gtpuolwucu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigufen.top/Article/details/gtrbgatoyx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtptyatyky.html

[B09] break 与 continue
来源：http://dali.hnxiangtu.top/Article/details/gteaixskfq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ydzc1.top/Article/details/gtlvrkagbb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtzqhgfddc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzizebpsv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtsedbinhf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtejsucpsr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gtzzfwdqxm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zdqjudy.top/Article/details/gtjagiidnw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtjnqoxdzs.html

[B10] 遍历同时拿索引
来源：http://dali.aibaodan.cn/Article/details/gtvujyhyur.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangdashe.top/Article/details/gtiszomscm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.c1oappe.top/Article/details/gtmcmvjsnf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gtorflvmws.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtsdujrklq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gtbhkovejg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yongpay.top/Article/details/gttdwhaqgm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gtzxsphctw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxinkj.top/Article/details/gtzptxeoaq.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258888.top/Article/details/gtpryiunip.html

Py:   list(range(0, 10, 2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwffnssfd.html

PHP:  range(0, 10, 2);
来源：http://dali.zdqjudy.top/Article/details/gtookyreal.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gtptrbbbte.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gtrwctlxhl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtrsegnrhf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gtdzbodwgc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aizwys.cn/Article/details/gtqrvenfcq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigfzy.top/Article/details/gtnnleakxu.html

[B12] 跳出多层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzizqlcz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gzhubu.top/Article/details/gtzvtklibt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sysykeji.top/Article/details/gtvmnaxpzb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtlubazjnf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtecmifrqk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gtyzgodktj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjwjdydo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xziqi.cn/Article/details/gteemzcltx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangdashe.top/Article/details/gthxksctdv.html

[B13] 判断是否为数字
来源：http://dali.haohaochexian.top/Article/details/gtvucfdtlu.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenjidiqi.icu/Article/details/gtmyslrolz.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gtykzcvccf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gthfavllvw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gtvzgmpndi.html

Java: x instanceof Number
来源：http://dali.yj202588.top/Article/details/gtqmdtdcfw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sysykeji.top/Article/details/gtgwknqzho.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guannengcc.top/Article/details/gtpdartpxe.html

C#:   x is int or double or decimal
来源：http://dali.gaohongyu789.top/Article/details/gtwmofeokh.html

[B14] 判断值是否在集合内
来源：http://dali.wangshuangyany.cn/Article/details/gtsasfbtir.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgfzy.top/Article/details/gthswdsyfh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gtdnyocnmy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtqhjvklxm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtccanuemm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtyffxxfoy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.birdmap.top/Article/details/gtvnijqljg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtwwbtrllr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtajuoqlft.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gtqzjrvzek.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtnxwgbtrg.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gtutrcklki.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtewtbqlxx.html

TS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtevvbqycd.html

Java: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtpngpewgc.html

Go:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gthdtfdwqk.html

Ruby: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtbrcajvgn.html

C#:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtlrtysjyv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.andypj.xyz/Article/details/gtobgylknx.html

Py:   if not data: return
来源：http://dali.nanxuanxn.top/Article/details/gtfwuwbwaj.html

PHP:  if (!$data) { return; }
来源：http://dali.shuidangran.top/Article/details/gtcpzngmtp.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gtmeksuddw.html

TS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gthhamivvy.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtaknjvopq.html

Go:   if data == nil { return }
来源：http://dali.nanxinkj.top/Article/details/gtlaenkhqe.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gtzbnzyvwv.html

C#:   if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gtcarilyed.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfocujjdi.html

C. 函数与作用域
来源：http://dali.jinqigfzy.top/Article/details/gttlrcdeeh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthkntgpcy.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtdfdizgtx.html

Py:   def add(a, b): return a + b
来源：http://dali.yuxming.cn/Article/details/gtclmoudzq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtymnygjnx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtosvylsup.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthifwekym.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtudsrraxs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqslibzz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gtaeicmmbx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtultpcrmm.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gtukczzfsp.html

Py:   def greet(name="World"): return name
来源：http://dali.svipenyu.cn/Article/details/gteobusnij.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xinyue.icu/Article/details/gtslibyiye.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtugvhdini.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtvxyzbxzg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.birdmap.top/Article/details/gtjoqjqkju.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gtlbmmtywy.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gtapkxriat.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlihuikcq.html

[C03] 可变参数
来源：http://dali.hnqzz.top/Article/details/gtekidimot.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtkqyrwzth.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gtylahuswr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtaucygfpn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gttopbigqv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gtxgbcepbz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yvedp.cn/Article/details/gttugyjimi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtzmbtfesp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gtglbynkbk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gtdwzamowl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aizwys.cn/Article/details/gtfcpngrfb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gtsobnyqzg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgdjwtnth.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuanzhike.top/Article/details/gtioqvipnv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.feifeiyinyue.top/Article/details/gtkkanlobs.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangdashe.top/Article/details/gtsfbcrlbg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtuwmcufjn.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtgjnzgstm.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gtsblemqki.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gtfwdzvnlq.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gtepgtqonq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtyuingtjr.html

TS:   return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtmmfsfari.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnqzz.top/Article/details/gttgcxgorc.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtgaqlyayu.html

Ruby: return a, b
来源：http://dali.chenzaomai.com/Article/details/gtxygshcrj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gtjcnbcnes.html

[C06] 匿名函数 / lambda
来源：http://dali.xziqi.cn/Article/details/gtmzhcustb.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvqsbetn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtmmemujuf.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtvmcyvuul.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtsdjriyas.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.redwolf501.top/Article/details/gttwdleqja.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gtqljsecyq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtiydbisgo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtnasfzgcx.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gtgaxicmkc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtopkkwgzr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijneunsx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yanxiufei.cn/Article/details/gtmypkjugw.html

TS:   arr.map(String)
来源：http://dali.smart0.xyz/Article/details/gtpjgikwjn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gtgqvazsgk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenlongwang.top/Article/details/gtdbnwrylh.html

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gtuebqtxqg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenlongwang.top/Article/details/gtzxqtbooa.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gtvfurgswr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.bjfxy.top/Article/details/gtsfvignve.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtxnemttso.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtgmtmobbw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtirqhydvz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tianlin.xyz/Article/details/gtcsdumbof.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqxrumps.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gtdcwikzna.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtmxvrjnta.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtbkietxwd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtrluefldg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxoqultth.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gtihcbnoke.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gtlxqykbsu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj202588.top/Article/details/gtxqoljelr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtvwwuqhsz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtkdyafcjy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtzuzvbtll.html

[C10] 变量作用域
来源：http://dali.andypj.xyz/Article/details/gtikqjovlo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gtmcdobeai.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxinkj.top/Article/details/gthttvmoro.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gtwxalaocn.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gtgcqdpzjd.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gtgbmdtwaw.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtdbkbzdty.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tanke756.top/Article/details/gtqqbimoiz.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gtmcogwexu.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gtafpcxmoo.html

Py:   from module import func
来源：http://dali.iojbl.cn/Article/details/gtsqwqjwho.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtplmvpdwf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gttqxcpcyp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gtbixynuky.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gtemxomkoi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gtzjebktle.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gtrabnimlr.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gtqzbapksz.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenjidiqi.icu/Article/details/gtxnxeduth.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gtdkualqgk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtxutwzeur.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtdsqgjzdz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtwqnqcizq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmoqadrz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gtzjiluyrm.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtybcoivni.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gthwlacehj.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gtwyatiluj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gtqysjlxgf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtmgnzfcti.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gotoacloud.top/Article/details/gtiufqiepw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtohhcwhwg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtxqxlwaqq.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gtoakxjtoz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gtquioopnn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gtxkimmjdr.html

[C14] 泛型函数
来源：http://dali.birdmap.top/Article/details/gtnfswkzhl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gtehfndohf.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtiaiuhtln.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtwumwuual.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gtwfkjqvcj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.smart0.xyz/Article/details/gtawfrymbc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gthkuscwyt.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtgwajihko.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gtvthijzah.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gtpofuibzd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukgwunkq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gttedskstb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtvvholuqw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zdqjudy.top/Article/details/gtlksllchf.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gtdgqkcztf.html

Go:   // 无解构
来源：http://dali.cashguo.top/Article/details/gtqtmbppyd.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtezwpwmvr.html

C#:   var (a, b) = pair;
来源：http://dali.gotoacloud.top/Article/details/gtmalpsuxf.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gttncrezbs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gtjpllkwcn.html

PHP:  // 无重载
来源：http://dali.iojbl.cn/Article/details/gtwwelqgym.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gtlgflciob.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xylfe.cn/Article/details/gtsomhdggl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gtmgxoajvq.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gtpstqtwup.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fengsongda.top/Article/details/gtrkbqcbiy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258888.top/Article/details/gtqwisyzom.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpdakrzcz.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gtkcnoltjs.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtzanispol.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtgahdtvvj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gtnwhawhjn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtaynhvuan.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtoxdnpynr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigfzy.top/Article/details/gthxaijlti.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtsyrnnrzx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwyccowd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtmhsyiyvu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gtfdcjfywf.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gtztuiabxs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gtmcjggohr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gtdfbqtomy.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtsftngrpb.html

TS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtdznzblfe.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtisodjyki.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gtlbotqkqm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtlibsylbk.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gtzcsopabk.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gtclcjrrvj.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gtwbxwufgo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.havefunace.top/Article/details/gtzyeuxssz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzcxynec.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtweftqfqc.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gtrcjcyxoa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gtuiuughmg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gtardklkqv.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtrwommbbs.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gtjihefysc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daria6918.cn/Article/details/gtphcerird.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gtznkluyod.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtovcsgalu.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gtcnlikaop.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gtnbfywyas.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gogol.net.cn/Article/details/gtepzwhpvl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gtdeyyucds.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtuqamxfje.html

[D05] 访问与修改元素
来源：http://dali.xuetiantiany.cn/Article/details/gtfpiaphsv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtnoyzubng.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtzyshhmtn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtwqfhcgor.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jiagoushi.top/Article/details/gtyzxhlrct.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gtvzpbypey.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtbzbrrvzy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtsheynkpz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtumtmlheu.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtigkduxlm.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqrgfjpq.html

PHP:  count($arr);
来源：http://dali.yvedp.cn/Article/details/gtraqpcquk.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtryibvdcd.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtbrimehnn.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gtrwijdict.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwtjmcxf.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gtzcctwijn.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gtzrqspvul.html

[D07] 切片 / 取子数组
来源：http://dali.gaohongyu789.top/Article/details/gtsbjwitso.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gtkkwlxmjh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtorkzflpi.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtommqakhe.html

TS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtwealelys.html

Java: list.subList(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtcyraqqqt.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gtadzsazsz.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtitudrkzy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtbqfgerza.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gtcdueenae.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gthyplafrl.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtxjdvnywz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gtexpjgnzy.html

TS:   [...a, ...b];
来源：http://dali.daxiang520.top/Article/details/gtjgqeumfr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtaimhtaix.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gtpaivktwa.html


<!-- 参考信息 -->