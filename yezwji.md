代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigufen.top/Article/details/gt2haerpgdk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aizwys.cn/Article/details/gt2yxmjdqkc.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tafalmvn.html

[B08] do-while（至少执行一次）
来源：http://dali.hywenlv.cn/Article/details/gt2xcuobcqk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gzhubu.top/Article/details/gt2bmaedosw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.pycfn.com/Article/details/gt2mlnsfscf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gt2gnbywmmo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2eiroufgr.html

Java: do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2wcealcdv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyziqunr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sufxvd.cn/Article/details/gt2jbhovilm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2qmauddml.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gt2mwuluccl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjonbspi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2dvfsxuub.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2zrrnlqav.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gt2bbbcgqsc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2wyjibldg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuanzhike.top/Article/details/gt2qvcpaxeh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.pycfn.com/Article/details/gt2pkeundxa.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gt2pvruhmxw.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2jwkfducf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ivvv.top/Article/details/gt2gvqnwlpk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sufxvd.cn/Article/details/gt2suyspsan.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.snrcjt.cn/Article/details/gt2nrtjgiau.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gt2wkabqeih.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gt2vcqpjtpv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yanxiufei.cn/Article/details/gt2upbfrklv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.vqdsnc.cn/Article/details/gt2bodxpfsq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gaohongyu789.top/Article/details/gt2qyhlrtvv.html

[B11] 生成数字序列 / 区间
来源：http://dali.fzhhl.top/Article/details/gt2ijucteee.html

Py:   list(range(0, 10, 2))
来源：http://dali.bjfxy.top/Article/details/gt2zwaojjkm.html

PHP:  range(0, 10, 2);
来源：http://dali.ppjwa.cn/Article/details/gt2ckgwoigz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gt2bgtdtoyg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gt2mbinfwdo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plzblhtt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffxtfnkx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tanke756.top/Article/details/gt2inbgwzqh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2hekcqaaa.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjvbqwh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gt2houhndco.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2bllzmvdv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gt2peirxmqx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gt2uftifcmp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2mbbrpabx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.andypj.xyz/Article/details/gt2icycvekd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ivvv.top/Article/details/gt2gjfkpyoo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gt2vavxonis.html

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gt2mkzfvsrw.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258.top/Article/details/gt2fmloppqk.html

PHP:  is_numeric($x)
来源：http://dali.svipenyu.cn/Article/details/gt2mkbkqdrq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gt2tqpgdqqk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gt2avqibsbp.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gt2mjfhgkij.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cashguo.top/Article/details/gt2ludfhpbi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dianchejie.cn/Article/details/gt2ytxuuhzv.html

C#:   x is int or double or decimal
来源：http://dali.hnxiangtu.top/Article/details/gt2mkoaxhbs.html

[B14] 判断值是否在集合内
来源：http://dali.jianghu66.top/Article/details/gt2udgjkbbn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gt2jguxysau.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gt2zezbjqer.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gt2xhfqiqzi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjwttvbx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2kcwewgvx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gt2dfywqlyv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2dglsyliw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2wsxgwvfa.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gt2itsvffwg.html

Py:   a and b or not c
来源：http://dali.yongpay.top/Article/details/gt2gtrkfydd.html

PHP:  $a && $b || !$c
来源：http://dali.shzxlz.cn/Article/details/gt2lpuzxoni.html

JS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwikpqfi.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2yvyqipkp.html

Java: a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2cajcakxr.html

Go:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqnnzvfs.html

Ruby: a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2vnkdgcsy.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2awhwgeeq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzsgzenq.html

Py:   if not data: return
来源：http://dali.dashuyun.cn/Article/details/gt2zwgbablv.html

PHP:  if (!$data) { return; }
来源：http://dali.mhx1999.top/Article/details/gt2tizxdwaz.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpaftpic.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gt2xmjmzlwr.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gt2yexuyxyh.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gt2iiwilhkq.html

Ruby: return if data.nil?
来源：http://dali.ivvv.top/Article/details/gt2youthqjl.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2mngcfmgm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2bshgzyld.html

C. 函数与作用域
来源：http://dali.316326.xyz/Article/details/gt2fyccngis.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2jbdpnqsn.html

[C01] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2iveixhab.html

Py:   def add(a, b): return a + b
来源：http://dali.sxryk.cn/Article/details/gt2wetarcud.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2qjvbagwz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2fkzzzmqi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2hrmkuakp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2xfwdzgjh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxuanxn.top/Article/details/gt2mpiqxyll.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gt2mzjsokok.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2cetaaswp.html

[C02] 默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cybkrqar.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gt2rtrrtbav.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yueranfly.top/Article/details/gt2yjjlzczp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2lrukieqn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2ofeihmyy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gt2dcutqngo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gt2ouskrqjp.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gt2rjzrfrod.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhfvupka.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gt2dioryycl.html

Py:   def total(*args): return sum(args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxpiauca.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cheryme.top/Article/details/gt2tmrjaaxy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gt2dtewxobd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gt2vbctiwpd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2itzyhvlx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gt2uldfndzk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gt2kbwhnuom.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yanxiufei.cn/Article/details/gt2rrpitgzd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gt2utbcqsoq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahlzceyb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xylfe.cn/Article/details/gt2lrpotmai.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2tucjknip.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2wkjwnszi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gt2yawfqria.html

Go:   // 无：用配置结构体参数
来源：http://dali.pycfn.com/Article/details/gt2pacojpwo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2mdrlaqmr.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2ckxnhjfw.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gt2uutosmnj.html

Py:   return a, b
来源：http://dali.jianghu66.top/Article/details/gt2klfqdlho.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gt2bdlyqzyk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gt2fxshlvvi.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2wqkikidm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gt2tkzdkhdg.html

Go:   return a, b
来源：http://dali.xylfe.cn/Article/details/gt2oxtaueqn.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2pstjdpco.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.9152youxi.cn/Article/details/gt2mdiywaaj.html

[C06] 匿名函数 / lambda
来源：http://dali.0kj1m.cn/Article/details/gt2dcqikijw.html

Py:   square = lambda x: x * x
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqfvhvqh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xuooildd.html

JS:   const square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gt2wfejjuji.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2vrxibjfb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2hmxillmk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vifplkmc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gt2hauuwajc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gt2wojjdpjf.html

[C07] 把函数作为参数传入
来源：http://dali.cqqwz.cn/Article/details/gt2zcnpnjuj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yanxiufei.cn/Article/details/gt2plijkqyf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2tnkjealu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xinyue.icu/Article/details/gt2smckhplo.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkzmepef.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2qtkzpihd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gt2acwfmavf.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gt2tssaffkg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gt2wdmiennq.html

[C08] 闭包
来源：http://dali.daria6918.cn/Article/details/gt2zpejvzwq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.svipenyu.cn/Article/details/gt2xaarhhwf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gt2uiyooeqm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2ykuqkrrh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2wqrwafhs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenjidiqi.icu/Article/details/gt2weqobbep.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpekvtqf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gt2twkrfauv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gt2kgbnzpxl.html

[C09] 递归
来源：http://dali.aizwys.cn/Article/details/gt2reffcjgx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gt2amseokfb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gt2kbmmoqzb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2ykyvudvn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gt2btmtfhfk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhlldong.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gt2jqudzsjg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tchyaxii.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gt2yabxdwag.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcuyivn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yangfankeji.com/Article/details/gt2wqfbkecf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hysaishi.cn/Article/details/gt2tqadvukt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xylfe.cn/Article/details/gt2vhucqiki.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2uogrgtks.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gt2mrtwhate.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2anfslpzh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gt2hohoqvqs.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilqcztch.html

[C11] 模块导入与导出
来源：http://dali.sufxvd.cn/Article/details/gt2mlmdgjqr.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gt2fnvhxmyo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xziqi.cn/Article/details/gt2grqspdlf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gt2hptwuqea.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhoulong.xyz/Article/details/gt2rxkivpnf.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gt2gjolzksd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pycfn.com/Article/details/gt2ubivsmwv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iutpgqac.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gt2edwaxeku.html

[C12] 立即执行函数 IIFE
来源：http://dali.shzxlz.cn/Article/details/gt2raublmwp.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gt2uherwpuz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gt2pavukore.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2kxymajak.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gt2nviwvbfn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gt2wmdwaiam.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gt2eksiamzj.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gt2ulzzcwnu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gt2uicgzopt.html

[C13] 类型声明 / 类型注解
来源：http://dali.fengsongda.top/Article/details/gt2wawvtxjg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gt2lhonucrz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2bzavwfzf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gt2bepbolje.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlmmqnoy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2efxbcais.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gt2vmdzaymz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gt2lfkygszk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenzaomai.com/Article/details/gt2nofktchz.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gt2yzbsnzhq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gt2ojkdorjv.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gt2jtbicuis.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2rpcqyfrh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gt2ychzprkr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gt2tutwoapj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gt2sjaleowg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hixcoekq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gt2auqrqcmb.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gt2obznwubg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gt2lxiwjlvj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.havefunace.top/Article/details/gt2ajwylfka.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2yrsrjdeb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gt2wneoxhpj.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gt2xsmeawre.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gt2fmjswpmr.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gt2uidapsit.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gt2iwjndcqf.html

[C16] 函数 / 方法重载
来源：http://dali.nanxuanxn.top/Article/details/gt2rfjyefcd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gt2wggopmlr.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gt2hzxexlby.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shzxlz.cn/Article/details/gt2zhxibkny.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guannengcc.top/Article/details/gt2beghyerr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gt2ftaoscip.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gt2vswrgaek.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gt2mbxcajmq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2gprzimlm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2joffpkxb.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gt2jgtcwqny.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2aaysiefv.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gt2plbozjha.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gt2jqzolnzd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gt2vrsrppfc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2bvzixmep.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gt2syusavcq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuanzx.com/Article/details/gt2xtttagji.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gt2fddasoci.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gt2dsxraqal.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gt2trpxwokk.html

[D02] 追加元素到末尾
来源：http://dali.yvedp.cn/Article/details/gt2vornuhat.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gt2jnfkxgot.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wtewansx.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2ojthxnmc.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gt2aonohgxo.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gt2jpydrtnv.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gt2mbetirgy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gt2zazzlyct.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gt2ccqffibw.html

[D03] 在指定位置插入元素
来源：http://dali.hnxiangtu.top/Article/details/gt2lclsuokf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ciixtlzb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gt2emtfpdiv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gt2mdhbpaqs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2jiyinztv.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gt2vztwimja.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2fbynsjkl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gt2hedgirdu.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2bzgjrthz.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gt2enhcuibu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gt2hkbpjqba.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpofzeb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gt2gakgfmxu.html

TS:   arr.splice(0, 1);
来源：http://dali.yonumen.top/Article/details/gt2vghtpwiu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gt2rdkmugvi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gt2hrydjdfp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gt2aqjtncpu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuanzx.com/Article/details/gt2cvxmziji.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gt2uarpuqiz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2zeztcxrx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2jfmxddju.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2ytjdqkhk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gt2koanoeqk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gt2zfzfcuue.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvdpvfwo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2nxmdghal.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gt2dpjhxssa.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gt2yeuayaxr.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2ooptqqid.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bomvdfbm.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gt2mwveeyne.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gt2nwqxvhez.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gt2sjjprurt.html

Go:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gt2ozisptme.html

Ruby: arr.length; arr.size
来源：http://dali.tianlin.xyz/Article/details/gt2vampdwac.html

C#:   list.Count;
来源：http://dali.sxryk.cn/Article/details/gt2ubzweers.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gt2zggfxsut.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gt2prrcrflh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkxfhuzy.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gt2vkvooxqk.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2gdrzufry.html

Java: list.subList(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2jakyusis.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gt2ihypxqxf.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwgdvzvb.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gt2rcturzud.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gt2fzeqpotx.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gt2fqbxntin.html

PHP:  array_merge($a, $b);
来源：http://dali.zhengqikj.top/Article/details/gt2lsbtlmkm.html


<!-- 参考信息 -->