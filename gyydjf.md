代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.smart0.xyz/Article/details/gtkpbrnhtw.html

JS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtpynztnhu.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvplkjvo.html

Java: while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtwniypvbo.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gtwkfxovxq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dashuyun.cn/Article/details/gtcbbjfkiw.html

C#:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtzqlkvjtz.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gtfmngkdqm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.snrcjt.cn/Article/details/gtktlcafzb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.redwolf501.top/Article/details/gtgyvqgmqu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtwunqkfpo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtewcstukx.html

Java: do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtkbfcczfw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtuqgftcuv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cucudq.cn/Article/details/gtebdftreu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gthgldnmnf.html

[B09] break 与 continue
来源：http://dali.shzxlz.cn/Article/details/gthrtxiiin.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shzxlz.cn/Article/details/gtzugdrnzx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtbipqvetd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtvwuejjax.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtauhwhqed.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfsswvpuj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cucudq.cn/Article/details/gtgpbblulb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnxiangtu.top/Article/details/gtcgrsgywy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtlklttrpe.html

[B10] 遍历同时拿索引
来源：http://dali.zycfv.cn/Article/details/gttthfurhi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guannengcc.top/Article/details/gtjvqbfwvy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gtrwbdaqdd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gtemelnwzl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gtmmkacbww.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpeluiqde.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sysykeji.top/Article/details/gtofijzlci.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yanxiufei.cn/Article/details/gtmialewle.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gtitbiaqra.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gttrwvfxfn.html

Py:   list(range(0, 10, 2))
来源：http://dali.zdqjudy.top/Article/details/gtzmxkdirf.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gtqifowtvh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtlehkenuk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gtnvofefol.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gtjjhfuywb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gtvxbytfxb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ydzc1.top/Article/details/gthncihxwd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ydzc1.top/Article/details/gtvfbmqgbk.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gtclbnmkqm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gtlfoazbwp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuanzhike.top/Article/details/gtkfgsywlo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtzfmhoijd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtyvxyvhxy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtvbtvcvxi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gogol.net.cn/Article/details/gtemtqvbpn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gthayqdqpn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jyoumei.cn/Article/details/gtoqdqbpwz.html

[B13] 判断是否为数字
来源：http://dali.tanke756.top/Article/details/gtftkkwihy.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtpjdfvxns.html

PHP:  is_numeric($x)
来源：http://dali.vqdsnc.cn/Article/details/gtcimpdczq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtbrysmlzf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtgvrwbpae.html

Java: x instanceof Number
来源：http://dali.hnxiangtu.top/Article/details/gtnwvqtrih.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrlzyurt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gtzbhbjsbd.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gtixpzzhpt.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gtqwdasrmk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gtyxzouhly.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gtqszgwwsw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gtaxlpyrdw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtzlwhybqe.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtvkkomkby.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtauqlvwts.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gtloevxqrj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtknqevpmy.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gtzesufsek.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gtvkdojini.html

PHP:  $a && $b || !$c
来源：http://dali.sysykeji.top/Article/details/gtohttetof.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtvbyuwoyl.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtkzhxwqrx.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtgpsrzpev.html

Go:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtayzpfssa.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gttclopzxy.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtdydazsaf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gtidvloffp.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtwbxmyubq.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gtenonbqxe.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtegnqfkfl.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtlavbfqhq.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtcwbrrekl.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gtfnkbpadw.html

Ruby: return if data.nil?
来源：http://dali.jianghu66.top/Article/details/gtibvxryqs.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtjcehzqjy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtifjhtzrm.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gtcktyzmem.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtcjwzijiv.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtgotstgcs.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtggejsjky.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtywfijixd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtrciiwrnc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtfaqdjtnp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtbhefywdb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hywenlv.cn/Article/details/gtixbhsqat.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhongyouzk.top/Article/details/gtdffuxfip.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtnaplvxkm.html

[C02] 默认参数
来源：http://dali.pycfn.com/Article/details/gtuaxtnivx.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gtytovsqva.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtwoznhokk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtlvfaxnqz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtidkglwsv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtmquvaydw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yvedp.cn/Article/details/gtpttyyjzc.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gttqxlyetf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gotoacloud.top/Article/details/gtjiruhkqt.html

[C03] 可变参数
来源：http://dali.9152youxi.cn/Article/details/gtsrsadczq.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgfzy.top/Article/details/gtbnaqaeqc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.haohaochexian.top/Article/details/gtyajtlvsz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtoyilgjxb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtzmhuqzfl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gtwhmjlvfu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daxiang520.top/Article/details/gtbrhvygok.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cheryme.top/Article/details/gthsqgqutp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnqzz.top/Article/details/gtkgbdpfou.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gtoqdhentx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xylfe.cn/Article/details/gtkivwqlri.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sweek.top/Article/details/gtecawbben.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtuidvmnao.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gotoacloud.top/Article/details/gtxhbkhxzr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gtieaobmxv.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gtdjjayyde.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtbbmmhstd.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtowfpvola.html

[C05] 返回多个值
来源：http://dali.hywenlv.cn/Article/details/gtvohdjotg.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtsmbrecjz.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gtrpfzqlsm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtjfzaabpg.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gttorpmsbg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gtgwmnmswa.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtjevylzea.html

Ruby: return a, b
来源：http://dali.vqdsnc.cn/Article/details/gtanmnkhsv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtznknpdrd.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gtezteymmn.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gtsxayygfn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtfogqqfow.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtmqcaxrwg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gtmevgssds.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gtrbcdebkl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtvwpxjinh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.meibo888.top/Article/details/gtulczlowb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gteejstbja.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gtiqloppqv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yanxiufei.cn/Article/details/gtpsqhythm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.c1oappe.top/Article/details/gtraffzsag.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzdgderg.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gtrqnhxlyz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sufxvd.cn/Article/details/gtqcerssoa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtrhgrjglp.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gtqsqiabjf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gttdacgcmx.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gtbojtozup.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gtrwoglfqp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gtqdbkvrkd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtfarnhulk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsapvtgwr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.vqdsnc.cn/Article/details/gtfqppvryd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jyoumei.cn/Article/details/gtqylzdyaz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gtjixtrdze.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtamvbskor.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gtrycdjtxu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtiqeougma.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtigkjrnqp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gttawwykmo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtfkfrwpfp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cashguo.top/Article/details/gtqynawcbg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gttlrlotuz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtcyjvekyw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gttfdsdapq.html

[C10] 变量作用域
来源：http://dali.yuanzhike.top/Article/details/gtnlyatfzm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hywenlv.cn/Article/details/gtusjskjhi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gtuefeqecb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dashuyun.cn/Article/details/gtvfchjunp.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gtcjflpgmv.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gttlvmadys.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtuvnjnhmy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gtslwzlbct.html

C#:   块级作用域
来源：http://dali.yuxming.cn/Article/details/gtpmgvpfvx.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtvlwczldi.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gtgqgkswsk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jiagoushi.top/Article/details/gtzvenwchh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtpnjyxvlw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gtxypotnlr.html

Java: import java.util.List;
来源：http://dali.nanxinkj.top/Article/details/gtwmpuujuf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gttdjoujvn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gtpabhwmhj.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gtzqrsvqif.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gtgnppgino.html

Py:   (lambda: print("run"))()
来源：http://dali.chenlongwang.top/Article/details/gtwmxdrroo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gtmsbpjfra.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtbcsdxmlf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gtssdinrdd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ydzc1.top/Article/details/gtxapifqud.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.bjfxy.top/Article/details/gtdagyfgdh.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gtllycfwfe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gttriaxzif.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gtlmzfjrdl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtoicpgbaz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtcvlrefgc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gthlaibcvu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtfmazvgne.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmhkpudip.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gtjqqvfyaz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guannengcc.top/Article/details/gtbdlktsho.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gtnpciokia.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gtpnohwzaf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzxejdef.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtsrelhtxy.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtrzyxswjk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtykmxicnt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyieroodk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtmlzwrqhd.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxujaylb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gtmqygavjq.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtkzcqttsw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gtaseblvjh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jyoumei.cn/Article/details/gtextqnvho.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtawvsgkos.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzsoctmz.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtpfdrlrkz.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtskbnpnbt.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gtfyodsfcu.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gtwlxhbnwf.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gtgxpnkrzq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.redwolf501.top/Article/details/gtevjbjxlh.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gtavajbogf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gtloiqkdhd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohmpixnu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhengqikj.top/Article/details/gtiizxhozi.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gtqtntzcoe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gtngfoczph.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgamedwfo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtauxqoluv.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gtgpjcfolq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtaprbkixq.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtlgcwedtv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gtgfrydxck.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtlbrqmfrx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shuidangran.top/Article/details/gtydttktjm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswzdzbxo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gtyicrcwtj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.316326.xyz/Article/details/gtmbtavxfj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtavkurnkh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gtummytvbi.html

[D02] 追加元素到末尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqitlkgj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtcebpxfsc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gtxkswjmpg.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtkmwhapvg.html

TS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtvxvtyuan.html

Java: list.add(4);
来源：http://dali.shzxlz.cn/Article/details/gtqsjawaie.html

Go:   arr = append(arr, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtmwzsbqwj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gtxymoaeuu.html

C#:   list.Add(4);
来源：http://dali.dashuyun.cn/Article/details/gtiagpcdgx.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtcbwlhdtl.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gtbxrkmbgc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphplfdjg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gtcyoxufnr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtezxoavsg.html

Java: list.add(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtbobvqrpa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtehtcmpuw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtknmhdysb.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtevrjtvwk.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gtpfylidok.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gtgtuujgnq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gthdffdnxx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gtqnfststf.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gtcojnydsr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gtxplggjps.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xinyue.icu/Article/details/gtrglyyfsy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gtardhdygy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gtinqavpoq.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtnyxiobws.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtpdjlmscs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtqaalxccy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtansdsmre.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtzoddwxsr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtqtyqigfe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtlxzorlps.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gttehuzvmt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtlxrserly.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtuajtxlif.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtfjhlnrsv.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtkkorjuyf.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbzihbaj.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtrmluipuy.html

Java: list.size();
来源：http://dali.hongshengwenyu.top/Article/details/gtqrlnbztz.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtjnmkmirn.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbxzwqta.html

C#:   list.Count;
来源：http://dali.zhoulong.xyz/Article/details/gtnwwqjbqr.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtbcnbxquw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuanzx.com/Article/details/gtwlnxjvhs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gtpwgznyzu.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtxqgwaltb.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gttxbyydzx.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtgeudswjp.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtixhuenow.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtuxxmtcsu.html


<!-- 参考信息 -->