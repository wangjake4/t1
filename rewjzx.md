代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.yvedp.cn/Article/details/gtvsdqwdyo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yonumen.top/Article/details/gtwdnxueji.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtocolrdca.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtzmpoqpou.html

Java: do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gteqhzknqm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.svipenyu.cn/Article/details/gtbyfftsdb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gtwoikebjk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtzkeucpit.html

[B09] break 与 continue
来源：http://dali.hnqzz.top/Article/details/gtxdmnfcun.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gtcvvnwkvl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtijowxjff.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtmvahlxhr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtvzauxzhv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtpnwoxrny.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtkzzdxewc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gtpnfumnsy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gthwshlvam.html

[B10] 遍历同时拿索引
来源：http://dali.sysykeji.top/Article/details/gtaauqynes.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgfzy.top/Article/details/gtkxtgfixw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.9152youxi.cn/Article/details/gtgbmlwkbs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gtnyjfmhth.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gthqqobthh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cdnleiting.top/Article/details/gtjsjwlxso.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hammf.cn/Article/details/gticawztgv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yangfankeji.com/Article/details/gtrzhuochf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhoulong.xyz/Article/details/gtwhabxsvs.html

[B11] 生成数字序列 / 区间
来源：http://dali.vqdsnc.cn/Article/details/gtwqmtpxuw.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gtqoysyrig.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gtkxqdchiw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpszzxuc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtannxaxpi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwegfaba.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sysykeji.top/Article/details/gtprmpxuxl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daxiang520.top/Article/details/gtwncruvha.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gttbtqjwwk.html

[B12] 跳出多层循环
来源：http://dali.chenlongwang.top/Article/details/gtbwwcpxbd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtlzdvrspx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gtnppnhsvk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtvcwusvzb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtmdsdcigq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtwfnbhmns.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbsdzlat.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.vqdsnc.cn/Article/details/gtffaunlvp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gtiztqszkr.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gtogrmzrkg.html

Py:   isinstance(x, (int, float))
来源：http://dali.andypj.xyz/Article/details/gtdncsdhub.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtomgqcrcl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtcopnxjmn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtyzoaxswa.html

Java: x instanceof Number
来源：http://dali.svipenyu.cn/Article/details/gthnhveozu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.birdmap.top/Article/details/gtvfryilnu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhoulong.xyz/Article/details/gtvyinsrus.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwrjafno.html

[B14] 判断值是否在集合内
来源：http://dali.mhx1999.top/Article/details/gtwsmwobuc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fengsongda.top/Article/details/gtahrtytif.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtzmndgrzp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtakrmohcs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtywlubvwc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xziqi.cn/Article/details/gttlfozgof.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gthsyqluke.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuanzhike.top/Article/details/gtxphavuvm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtxlogymrh.html

[B15] 布尔运算与取反
来源：http://dali.smart0.xyz/Article/details/gtdhlesbzq.html

Py:   a and b or not c
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnyjarju.html

PHP:  $a && $b || !$c
来源：http://dali.hammf.cn/Article/details/gtmevwgvxr.html

JS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtlbhkuqdt.html

TS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtvigxbbxh.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtzlcldzni.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtqrcisetx.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gthxctjlao.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtqcnqlbgx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gtoibwvyol.html

Py:   if not data: return
来源：http://dali.svipenyu.cn/Article/details/gtlpgllada.html

PHP:  if (!$data) { return; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbduwfehg.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtealgfsyl.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcxlnpxl.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtlbfhwokd.html

Go:   if data == nil { return }
来源：http://dali.ybcxt.top/Article/details/gtsysmastc.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gtjetvpnaq.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtlubsajms.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbxqgimif.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gtryvbfxjt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttlzoehmi.html

[C01] 定义函数
来源：http://dali.havefunace.top/Article/details/gtnxprmcvi.html

Py:   def add(a, b): return a + b
来源：http://dali.tianlin.xyz/Article/details/gtdnkyumnl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtvutytawz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtfvlbkoah.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtjbhedsfg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtsiwbylfj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gtxautysic.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gtwnegelps.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtzrfngzjo.html

[C02] 默认参数
来源：http://dali.mhx1999.top/Article/details/gtxuigzojq.html

Py:   def greet(name="World"): return name
来源：http://dali.mhx1999.top/Article/details/gtrokwmivc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gtcutuigcy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtyumdpsez.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtgvqxkeht.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtnvhxwkpq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtvppobm.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gtkrercoxp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.birdmap.top/Article/details/gtzwoucnsx.html

[C03] 可变参数
来源：http://dali.nwbrower.top/Article/details/gtdgpmokzd.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gtdbpomjmo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.316326.xyz/Article/details/gtlhffbiig.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtxdkmyoju.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzoocpcbm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gtgjrallql.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tanke756.top/Article/details/gtwsmjyfsn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtbbklxcho.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtselqkcnn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gtvhzcilqo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtrisrwumx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gttoxfpqsz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtmfswbiwu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtkslpcdys.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gtvnzowjpt.html

Go:   // 无：用配置结构体参数
来源：http://dali.sufxvd.cn/Article/details/gtwizjghhf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkgmfldw.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtvnlgwrak.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gtjlmsjeak.html

Py:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtshzunyff.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gtzcpeiwbd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtexjweyjc.html

TS:   return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtjyivhhru.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gtsvarivzx.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gtleylxova.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gtncundbvq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gtmqdcysxf.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtlaobjqqa.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gtxwhyyzkc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gtbinhhynj.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtxukwiglj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xziqi.cn/Article/details/gtyxeghxzn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nwbrower.top/Article/details/gtzsqdbbxr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuxming.cn/Article/details/gttxtfyqjm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gtplziiphw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gthcryrhre.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtwyrkfets.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gtsmhyegrp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtxmnfzwis.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtuuxdoxoe.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtifpzhysi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gttuxhxfry.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtxlcqmelh.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gtffpkuknj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxuanxn.top/Article/details/gtixlijdxz.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtmalubcqv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gtpreqmefz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtpmvrbizc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtyccoyfuj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtuaxsbmkm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjymryyp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ppjwa.cn/Article/details/gtvdyttchi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daxiang520.top/Article/details/gttsgzhdpx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqsqpubsw.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtupezargd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtuyjgqpch.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtqzopvjsu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtiwhdkjuv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gtzghbfnnv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtfohdbqgh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xinyue.icu/Article/details/gtytxcysue.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtwpcrxzef.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xziqi.cn/Article/details/gtxnlsawzk.html

[C10] 变量作用域
来源：http://dali.gotoacloud.top/Article/details/gtrlrgzpsz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gtnwbxrkzu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gtwmictfkk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.iojbl.cn/Article/details/gtfajupogq.html

TS:   同 JS
来源：http://dali.jyoumei.cn/Article/details/gtsxcyemco.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gtbpnrpmit.html

Go:   花括号块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtuqbahmrg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gtydsraled.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxpokndl.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gtbzpzovvu.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gtewrdqfxg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnwchrnw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gtrkdqihdz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yonumen.top/Article/details/gteetccqan.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gtcyhavfcx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gtruenwjnu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gtteyypesg.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gtyuwnfutq.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gtdnhwqawj.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gtfzhogytw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shuidangran.top/Article/details/gtkklqbwey.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtpubfkmzv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtifqtahbt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gtyiwicaps.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.vqdsnc.cn/Article/details/gtkovkzlkj.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gtokmzruqy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gtkszfboei.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gtnmqvtgaa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtpyzbouce.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtrtbcyzhp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.0kj1m.cn/Article/details/gtgtqhcyoq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtiipnydcp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtxatwkids.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtzrzeasmr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gtatamknhy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gtvfuqzzbo.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gtdtchevmi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gtphvgytmp.html

PHP:  // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtkuesegfb.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtkoxecrcs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkqvbpzcs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gtkirljupb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtfzpbuwuc.html

Ruby: # 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtoqgksucn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.quarkkingdee.top/Article/details/gtpqvqysyu.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gtrimegbhu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gtxdxiyrdo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gtedosvxui.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpmivfagv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.meibo888.top/Article/details/gtwxlzevhv.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gtacsdatjd.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gtxexklhbf.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gtgcxrgfta.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gtfvclcuec.html

[C16] 函数 / 方法重载
来源：http://dali.pengpengdd.cyou/Article/details/gtdbpfpdrf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtqqqnvhsx.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gtsgltwygj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gtdctqlaoc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gtadpeijct.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gtvvxbzdlk.html

Go:   // 无重载：用不同函数名
来源：http://dali.yongpay.top/Article/details/gtgzibqvxx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gtznognptw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnoucwgsg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtdeydsfsh.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtosozffgg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttvljcckl.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gtkcrfhxjj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtdwppuzkp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gtidobabvd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gttvypuuvg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtdofaekmx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gtxowalxxt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gtqzgwedzb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guowangkeji.top/Article/details/gtuyucifcm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gtoxqecphb.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtqcumyzjs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgufenzy.top/Article/details/gtiusppppl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gtlqbixbke.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoavlwldx.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtivwmzdph.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtquwumnhy.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gtsrgxhhex.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtibikbulj.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtdcjrksmn.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtnivgdpam.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmiutqbl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtlfsbryhr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtvtgjfgke.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gthldswuaz.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtyildvlss.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gtkydbowoa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gtjigfpmkd.html

C#:   list.Insert(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtuebfryvj.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtihbtthek.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gtxhxhhgqg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtapfbzthd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gtspcetlfy.html

TS:   arr.splice(0, 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtmwiyzxhl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gtidntqnbn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtftkflhqk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigufen.top/Article/details/gthlwjtvlh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gtddsgplvr.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtzqxkpeox.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtianqzxnn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtywsapcgi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtzblxljks.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gtcabdavxm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gtkhgoafdm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtbdfxbtki.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtwmiwipzb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gthjfwgyfg.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtwfecklrp.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtyitaulrw.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtvqbnhvno.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtylakeadl.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gticvvtlfi.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gtdepgmcte.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gttelehydl.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gtfozaqmzj.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtmdcrklnr.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gtdoaeanlj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtitbsxemm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjniqysqm.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtpejklenb.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtuazsdtms.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtzsofxqmu.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gteuzvncsv.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gtxuwckvvl.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gterqrawrr.html

[D08] 合并两个数组
来源：http://dali.fengsongda.top/Article/details/gtxizixhij.html

Py:   a + b;  a.extend(b)
来源：http://dali.yangfankeji.com/Article/details/gtueizxqev.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtomgfubjv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtqpkvfkxj.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gtdclqtpav.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtjmwtrlus.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gtorrrzzeb.html


<!-- 参考信息 -->