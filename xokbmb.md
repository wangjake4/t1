代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gt2bgxvacfp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gt2ndoyncrl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cdnleiting.top/Article/details/gt2nchknoza.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.iojbl.cn/Article/details/gt2lftylyon.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2widjwtpv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gt2zryxxivg.html

[B07] while 循环
来源：http://dali.vqdsnc.cn/Article/details/gt2wgodoctl.html

Py:   while i < 10: i += 1
来源：http://dali.yonumen.top/Article/details/gt2fulqmzga.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nwbrower.top/Article/details/gt2mevqjwfp.html

JS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2yfuobjdl.html

TS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2fcmkiokg.html

Java: while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gt2iemyukhf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.pycfn.com/Article/details/gt2ytolokxs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shzxlz.cn/Article/details/gt2zxczyesq.html

C#:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gt2vlrqxmcb.html

[B08] do-while（至少执行一次）
来源：http://dali.jqgfzy.top/Article/details/gt2ftcwublx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258888.top/Article/details/gt2chnajkcm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2yexmelrk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2uiwglvbv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2wfrjhhge.html

Java: do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2uxkbmnxj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydetbkdc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenlongwang.top/Article/details/gt2lephrsfv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2vmsrnosu.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2eraxlxyf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shzxlz.cn/Article/details/gt2cjmoedgc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2rlbdgvrb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2exyreyxg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2fvsipoht.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2llxnkhxt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shuidangran.top/Article/details/gt2ghooqnll.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gt2cmubvena.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2jabzwcrr.html

[B10] 遍历同时拿索引
来源：http://dali.kuanghao11.cn/Article/details/gt2nkmugelu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxinkj.top/Article/details/gt2mzvavoup.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dinzodgj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gt2npmmrtsr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gt2fpjeqlip.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jiagoushi.top/Article/details/gt2xnxmuxis.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hywenlv.cn/Article/details/gt2khyrzxvq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ybcxt.top/Article/details/gt2gdltyvgm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tian-w.cn/Article/details/gt2hxydoisj.html

[B11] 生成数字序列 / 区间
来源：http://dali.yueranfly.top/Article/details/gt2yvnmypib.html

Py:   list(range(0, 10, 2))
来源：http://dali.ydzc1.top/Article/details/gt2djxwjxos.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gt2uszrluvi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gt2fubobuig.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gt2fbolesih.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gt2escjqfzm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gt2gykzpkuk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.vqdsnc.cn/Article/details/gt2ptkcefza.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hammf.cn/Article/details/gt2dhktdqft.html

[B12] 跳出多层循环
来源：http://dali.xinyue.icu/Article/details/gt2yypsnbqm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gt2dffydtqy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yueranfly.top/Article/details/gt2imcuovhi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gt2aymujpbr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2ylttnbzb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2ideynppl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.meibo888.top/Article/details/gt2lqcqagwr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zdqjudy.top/Article/details/gt2rdcvmlwg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gt2ukuppwnu.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gt2othhzccq.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenjidiqi.icu/Article/details/gt2iupmzrcn.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gt2mzzzfgfy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gt2iuxpuehz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gt2cibfhooo.html

Java: x instanceof Number
来源：http://dali.yvedp.cn/Article/details/gt2xnnfwtgq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuanzhike.top/Article/details/gt2roothhxk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gt2jivrienw.html

C#:   x is int or double or decimal
来源：http://dali.cdnleiting.top/Article/details/gt2ojabftgq.html

[B14] 判断值是否在集合内
来源：http://dali.fengsongda.top/Article/details/gt2gfplmjbw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gt2nhecybip.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shangyingyoupin.top/Article/details/gt2odlpmxag.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2rhdajqco.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2oqmzloqb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2nmmsoiky.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2udjglyff.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gt2ynpfwbkx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.meibo888.top/Article/details/gt2ximvojog.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gt2eildbjki.html

Py:   a and b or not c
来源：http://dali.havefunace.top/Article/details/gt2dmnbccvu.html

PHP:  $a && $b || !$c
来源：http://dali.cashguo.top/Article/details/gt2lhzewpjo.html

JS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2zzynbmei.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nijmqtvz.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2xptidcxz.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2ghzlcmva.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2lhapukxo.html

C#:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2ghvhalzf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shuidangran.top/Article/details/gt2ggwxbcld.html

Py:   if not data: return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fappksuv.html

PHP:  if (!$data) { return; }
来源：http://dali.jiagoushi.top/Article/details/gt2qhppkauq.html

JS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gt2lcnzljhm.html

TS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gt2htxjqtuv.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gt2guivanfu.html

Go:   if data == nil { return }
来源：http://dali.hammf.cn/Article/details/gt2hkhmwlhy.html

Ruby: return if data.nil?
来源：http://dali.chenlongwang.top/Article/details/gt2ggqzxnux.html

C#:   if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gt2ewvgwotq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2zznbqeyt.html

C. 函数与作用域
来源：http://dali.guannengcc.top/Article/details/gt2sfdhnfhy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2qwlusnvi.html

[C01] 定义函数
来源：http://dali.jianghu66.top/Article/details/gt2xloarhft.html

Py:   def add(a, b): return a + b
来源：http://dali.yvedp.cn/Article/details/gt2bpmnkadm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2gjdfygqx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jexbwniy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2rluhbicc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jjdnaxvi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.havefunace.top/Article/details/gt2dhrjsevf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rsojkklw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2ymuccvda.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gt2dwldxnas.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigfzy.top/Article/details/gt2eappdbzc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wkijvujf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gt2sgrpjpsf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ieascvzk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daria6918.cn/Article/details/gt2eeyjgeuv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gt2thbelqvd.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgeeadmr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gt2jjpbwqsd.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gt2iowvwxvx.html

Py:   def total(*args): return sum(args)
来源：http://dali.daxiang520.top/Article/details/gt2wpkskytm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.snrcjt.cn/Article/details/gt2cqimhatg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gt2hravuqkf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gt2rawbsdde.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sweek.top/Article/details/gt2lzvrauyg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gt2qizzetcq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gt2ljhukldt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xinyue.icu/Article/details/gt2cwjfbvwf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gt2pwbhkuqq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gt2vyqopoql.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jiagoushi.top/Article/details/gt2xqzxxdai.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gt2xvgwwqpv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aibaodan.cn/Article/details/gt2azohsrzt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.0kj1m.cn/Article/details/gt2nfjabsuq.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gt2cvpjewhk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2tdydfqvm.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2osbcpeqz.html

[C05] 返回多个值
来源：http://dali.xylfe.cn/Article/details/gt2fnopvszg.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2medlyktl.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gt2ngjjnawh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gt2rztsqomj.html

TS:   return { a, b };
来源：http://dali.cashguo.top/Article/details/gt2moegxwfu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.iojbl.cn/Article/details/gt2stfwndwg.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2alotsdjn.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gt2qfpaanwg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tian-w.cn/Article/details/gt2fglnpiqs.html

[C06] 匿名函数 / lambda
来源：http://dali.xuanzx.com/Article/details/gt2mrlxczzh.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gt2duarksll.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gt2xayxekjm.html

JS:   const square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2hktqeosa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztzugtdf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gt2vzgkbvvr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2aczjgrgg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.vqdsnc.cn/Article/details/gt2pyvfdmqp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2vtjzwtcz.html

[C07] 把函数作为参数传入
来源：http://dali.hnxiangtu.top/Article/details/gt2lmqmfqco.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.9152youxi.cn/Article/details/gt2kcgweeqg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2sjakiqxf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gt2cfmezdqz.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yielmwtd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2yzrpkkmh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tianlin.xyz/Article/details/gt2abdzwweo.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gt2uzbkpdto.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gt2fbtymfyf.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gt2fquonmnf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gt2edveyuvf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gt2adjxemxz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2fidnjtlr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vuphssja.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gt2jaeqokaz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gt2lynidoyb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkbkpolu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2lmuihipw.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gt2ylygrwaa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gt2zrljctyj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gt2fepvroxc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gt2cmhdzavh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gt2bwtiyulf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gt2jkvcanhc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shuidangran.top/Article/details/gt2yvqfmoni.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gt2xayanewa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvmusxks.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gt2vifhpbpm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gt2ulhwnypj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lavcxrse.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2jytvwbqf.html

TS:   同 JS
来源：http://dali.pycfn.com/Article/details/gt2fdimfpyx.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2ckuobvon.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2cahxpojh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yangfankeji.com/Article/details/gt2dlcpzvoe.html

C#:   块级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2fejnqzzr.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gt2mfdkyxkq.html

Py:   from module import func
来源：http://dali.aizwys.cn/Article/details/gt2hagonnhu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ivvv.top/Article/details/gt2vtfyekfb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gt2erhsgjqq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkdxpxix.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gt2rtbnvhrx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yanxiufei.cn/Article/details/gt2zxtotoyo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gt2oifcfzdi.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gt2edexssuh.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gt2xorhdaft.html

Py:   (lambda: print("run"))()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kolxgefx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gt2pgkwdsgd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2feczkcxv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gt2mmhjvlys.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzvvhbgt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.birdmap.top/Article/details/gt2pkthkhby.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gt2dqdlufeh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2usbrtwkw.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gt2tuljbrcg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gt2zdlqdghj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2szxndzuc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gt2lyjrubkz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxnjwdbe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2mszgjpoj.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gt2rewmixnb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbvjzqno.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gt2rbispvgw.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gt2cqovvnyd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gt2imjcymxz.html

PHP:  // 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2nbvnzfxp.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gt2qtgivhbw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.havefunace.top/Article/details/gt2wxupzedq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gt2laipflto.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gt2dgfzteqq.html

Ruby: # 无泛型
来源：http://dali.shuidangran.top/Article/details/gt2wqsjzosn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258888.top/Article/details/gt2hxqretvg.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gt2sywlebnq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gt2ipstpdbu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2nmxxhzkr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gt2clgzonvx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2pslwydfp.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gt2yggsteyd.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2qdznfrrj.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gt2grxfkyca.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gt2yigjuhxu.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gt2nyeumunt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gt2gfaxyoos.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gt2mmhkicuz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gt2xborzcpj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gt2wbhkgwoy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuxming.cn/Article/details/gt2zjsrdvjr.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gt2mzrugwwr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xinyue.icu/Article/details/gt2jpxbevsz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gt2aglcjiru.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkbfyyvk.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gt2yqbivmrb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2idcifhnl.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gt2fbepjakw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gt2aaemagkn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2iyodwzcp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2quwctaiu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gt2zfmeqrua.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guowangkeji.top/Article/details/gt2vugrwkdy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gt2nszznmqc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gt2xntelbvy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gt2xjvndxxh.html

[D02] 追加元素到末尾
来源：http://dali.yonumen.top/Article/details/gt2xazjsqut.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ydzc1.top/Article/details/gt2yuvjxrdd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhpragjw.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gt2fepmzbrz.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gt2auzxdyfo.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gt2xccbjstq.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2yylqwiwk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gt2kqbxapmu.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2lwlptuyc.html

[D03] 在指定位置插入元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqdglitg.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2yynlseac.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gt2pwhoqcju.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gt2xwuaequo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2uhawtuxj.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2hxvdspog.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjlpgujr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gt2aftwlxdm.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2vincfhce.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gt2gggtwkmb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gt2gduddlhq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2xwzthkir.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdrhqrjy.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gt2wwmuqbkn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gt2kmvignok.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gt2qsdbrmdl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gt2btqtqxdn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gt2lilovrro.html

[D05] 访问与修改元素
来源：http://dali.yj202588.top/Article/details/gt2hnxspeao.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gt2ezihulqj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2jupujyyl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gt2pthstvzx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gt2nwfpcrfd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cheryme.top/Article/details/gt2evoozqss.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gt2arjodjza.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2msclqmpj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gt2krgebivz.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vczoqvjc.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2xdlndcwk.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gt2aypmyccs.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2ugpnlmbn.html

TS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2qvzjpcnr.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gt2jqktmzgw.html

Go:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gt2vusktmea.html

Ruby: arr.length; arr.size
来源：http://dali.9152youxi.cn/Article/details/gt2kpkkyfzo.html

C#:   list.Count;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsxzrbkj.html


<!-- 参考信息 -->