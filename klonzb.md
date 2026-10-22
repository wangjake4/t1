代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2luvhxoim.html

[B06] 遍历字典 / 对象
来源：http://dali.bjfxy.top/Article/details/gt2ccwkcxau.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frjolhwe.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj202588.top/Article/details/gt2nxhqzjkj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gt2whjcbzdb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ryiuunai.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edhmwhlt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhoulong.xyz/Article/details/gt2bwngzati.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuxming.cn/Article/details/gt2ixgfjpxg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cheryme.top/Article/details/gt2csknquib.html

[B07] while 循环
来源：http://dali.sysykeji.top/Article/details/gt2agmllmdz.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gt2splhpkvd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fzhhl.top/Article/details/gt2rluxwjsg.html

JS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gt2ormedogl.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvclcqum.html

Java: while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikhyapov.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gamczoxq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.iojbl.cn/Article/details/gt2ctecdcvn.html

C#:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gt2fszkhnid.html

[B08] do-while（至少执行一次）
来源：http://dali.havefunace.top/Article/details/gt2tgrkmsif.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangdashe.top/Article/details/gt2gxnxkftc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gt2eaauomxe.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgnnotlr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2laftgadj.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2kyjcdtpv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jyoumei.cn/Article/details/gt2nmvoouqc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xziqi.cn/Article/details/gt2hukzfxra.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gt2vigndevv.html

[B09] break 与 continue
来源：http://dali.havefunace.top/Article/details/gt2vlbmjbug.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gt2xbombgri.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2igpomwoe.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gt2kjdxlpvb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2wdpolkhl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlcngkhh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gt2htzrxhqk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkxtdtt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2kqjlzspg.html

[B10] 遍历同时拿索引
来源：http://dali.snrcjt.cn/Article/details/gt2fhdpjqnc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuanzx.com/Article/details/gt2vlriqnlk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zycfv.cn/Article/details/gt2htzygebj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gt2utwwlwxo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gt2fcffltuj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.birdmap.top/Article/details/gt2ugmpwahn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gotoacloud.top/Article/details/gt2wmozrkdw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lojsatdh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sysykeji.top/Article/details/gt2gogybpem.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gt2ivzpscxi.html

Py:   list(range(0, 10, 2))
来源：http://dali.quarkkingdee.top/Article/details/gt2jrjqenmz.html

PHP:  range(0, 10, 2);
来源：http://dali.yvedp.cn/Article/details/gt2sxoznixk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gt2eqempsoc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2umvjsywn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2skruvlgf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gt2wwmncljd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jiagoushi.top/Article/details/gt2foztsncc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gt2kmezjpsd.html

[B12] 跳出多层循环
来源：http://dali.aibaodan.cn/Article/details/gt2secdrush.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gt2cbpyolqp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gt2tslpmtgs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gt2xdinvzli.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2ueklppdb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gt2xeewwbgl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.svipenyu.cn/Article/details/gt2odwgenzu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gt2ynmjottn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guowangkeji.top/Article/details/gt2fmouximt.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwigqdgh.html

Py:   isinstance(x, (int, float))
来源：http://dali.tanke756.top/Article/details/gt2yedujupp.html

PHP:  is_numeric($x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxxthnpk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gt2lwnzzyzo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gt2otyyngih.html

Java: x instanceof Number
来源：http://dali.smart0.xyz/Article/details/gt2nuswaxxj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuanzx.com/Article/details/gt2phgurbqr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gt2sizqrtjy.html

C#:   x is int or double or decimal
来源：http://dali.smart0.xyz/Article/details/gt2ndaoskaw.html

[B14] 判断值是否在集合内
来源：http://dali.ydzc1.top/Article/details/gt2mnqyjsyu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigfzy.top/Article/details/gt2ukbsjfsm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gzhubu.top/Article/details/gt2jdkjzlyi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2grnqsldk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2xkhbugpd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gt2xkjspvwz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hfpthk.cn/Article/details/gt2qghfkebi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shuidangran.top/Article/details/gt2fuxhcsla.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2rehqlzpu.html

[B15] 布尔运算与取反
来源：http://dali.daria6918.cn/Article/details/gt2zwwjaanq.html

Py:   a and b or not c
来源：http://dali.ivvv.top/Article/details/gt2jffuucun.html

PHP:  $a && $b || !$c
来源：http://dali.mhx1999.top/Article/details/gt2xbrmdoxk.html

JS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2xhqtekgz.html

TS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2frulquyy.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2hruwkxkp.html

Go:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2qiddtvbh.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2djprxkob.html

C#:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifxhibah.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sweek.top/Article/details/gt2byzjmcdf.html

Py:   if not data: return
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjbmhhge.html

PHP:  if (!$data) { return; }
来源：http://dali.zhengqikj.top/Article/details/gt2fgnnejxm.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gt2snrjfnek.html

TS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gt2brqovqtu.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gt2rdxkhtls.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gt2bptndspe.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gt2plqvddho.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gt2qykmaura.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pohyqffr.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gt2rdyihcje.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnsahetg.html

[C01] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gt2fxsvziuy.html

Py:   def add(a, b): return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2yqpzdfnt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgcvlmac.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2lsudemvv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2gcfbjdzf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omgoejbc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2tfhyxfdu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hfpthk.cn/Article/details/gt2omdxvbyj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2evagmqsa.html

[C02] 默认参数
来源：http://dali.hammf.cn/Article/details/gt2dvphhojm.html

Py:   def greet(name="World"): return name
来源：http://dali.hammf.cn/Article/details/gt2yqgdsild.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tianlin.xyz/Article/details/gt2mveqxcsg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2sgbvudas.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2rbmghadu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shzxlz.cn/Article/details/gt2ysizdhcq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guowangkeji.top/Article/details/gt2aybmgljb.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gt2amvjucsw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gt2pixcklsv.html

[C03] 可变参数
来源：http://dali.chenlongwang.top/Article/details/gt2snordwyl.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gt2sftitppi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aizwys.cn/Article/details/gt2emzoaxij.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gt2puexxczd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gt2mgyhagem.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gt2isvytrzi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gt2azgebnck.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gt2lfwxsaqu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gt2wiapjsjn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gt2imnxlvvd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gt2cfnongyw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gt2dmlejfek.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2umvvkrnd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.andypj.xyz/Article/details/gt2kahsnudk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.vqdsnc.cn/Article/details/gt2yzvksfhx.html

Go:   // 无：用配置结构体参数
来源：http://dali.quarkkingdee.top/Article/details/gt2nkqbvxla.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gt2tnkjltqa.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gt2ajbvupng.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gt2yxmrsduj.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gt2cykzqlbw.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gt2hfqrhqsw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.316326.xyz/Article/details/gt2ejajypdd.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gt2jrhnoxrm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gt2mqwgnlcx.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gt2pvqpxmcy.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gt2wcmcynif.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gt2rglrmayt.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gt2oloyryub.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gt2aeaayztw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.redwolf501.top/Article/details/gt2oteztfvj.html

JS:   const square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2xzsalruk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.mhx1999.top/Article/details/gt2qwyedihd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2juohcgbm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hammf.cn/Article/details/gt2ivnmcyyd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gt2stvoqpms.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gt2abqywgem.html

[C07] 把函数作为参数传入
来源：http://dali.jqgfzy.top/Article/details/gt2fyaktlks.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gt2dghkxbbu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2qnjrdxmj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ighwmfcz.html

TS:   arr.map(String)
来源：http://dali.birdmap.top/Article/details/gt2qxcwcaxf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.havefunace.top/Article/details/gt2quhwygnm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gt2wsythjot.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gt2wnczrxim.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vajkrscm.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gt2ldnbtmms.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgfzy.top/Article/details/gt2hweqwdck.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gt2herzcbao.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2hezsibyx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gt2tjamockz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gotoacloud.top/Article/details/gt2ypoutora.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gt2awywzuiw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2hseqvfit.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2whwqdnul.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gt2ndawjtpy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2hhncxfms.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivugppal.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozrblbzd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yifacfyf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnkubbxx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tianlin.xyz/Article/details/gt2cccsyqls.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2aqupkvxv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gt2gzwmxvma.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2izgdecfh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gt2jfutlwez.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdtrsspj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gt2gglinejg.html

TS:   同 JS
来源：http://dali.ybcxt.top/Article/details/gt2sxwdercl.html

Java: 方法内为块级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2nnltzetw.html

Go:   花括号块级作用域
来源：http://dali.ivvv.top/Article/details/gt2zdiacaxe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exuebell.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gt2zfnaywcv.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gt2tspfwcws.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfazwjdr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guannengcc.top/Article/details/gt2cwtftgwq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gt2phqyvxtw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gt2flhkuesl.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gt2vnvnksrs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gt2ypqtjbat.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ugrxopxu.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gt2lowaewwj.html

[C12] 立即执行函数 IIFE
来源：http://dali.birdmap.top/Article/details/gt2fiyngpyf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrevhsd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.9152youxi.cn/Article/details/gt2rtrfrkvg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gt2tjsjsqwz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gt2bagglzmu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhongyouzk.top/Article/details/gt2ipgtarql.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gt2ppxkypxp.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gt2wengivru.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2bioberqa.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gt2slffvyfw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gt2jzywjeam.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2hsnjnult.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fengsongda.top/Article/details/gt2iqmbepqc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2umqjvbod.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2hovhzhgv.html

Go:   func add(a, b int) int
来源：http://dali.daria6918.cn/Article/details/gt2qyuqdscf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zycfv.cn/Article/details/gt2yzbjdxuq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbmgzufo.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gt2dgzfjeew.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yntodfsp.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2nvynofrp.html

JS:   // 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2ojqinlrn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gt2ocplazzs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hscpygyh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xoefxihh.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gt2tyacakcq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gt2dkfddgio.html

[C15] 解构 / 展开参数
来源：http://dali.guowangkeji.top/Article/details/gt2upfejdfo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gt2iqgixnfv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gt2lmgsqarc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijzvsfhe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cashguo.top/Article/details/gt2qgrrmoth.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gt2omwkzfpy.html

Go:   // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubjricql.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aujchera.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbaeakzj.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gt2oddnjiil.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2ocdbxzsl.html

PHP:  // 无重载
来源：http://dali.yj20258.top/Article/details/gt2ssniflkt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gt2pkssyjtf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gt2vkglnkcl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ebkolape.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gt2nxpezrue.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2iuchydlu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gt2nkyynrwb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2cqutaukv.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgufenzy.top/Article/details/gt2xhfqgdhl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbsgmmvq.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gt2ktiwkghf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gt2apqrqcwo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gt2efatzvwi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gt2vimkbykv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shangyingyoupin.top/Article/details/gt2ounilqta.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gt2ekvxisap.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gt2slffnkbs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gt2lhfhbqdr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxinkj.top/Article/details/gt2zqzmxgzv.html

[D02] 追加元素到末尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnvklrdo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gt2svkgihus.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gt2wycrujer.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2uwuaqtss.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2ohjbmrwg.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2davcknii.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gt2gopbrrqa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhengqikj.top/Article/details/gt2lcrysheq.html

C#:   list.Add(4);
来源：http://dali.sufxvd.cn/Article/details/gt2takxcbfr.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gt2nfuwlhzc.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2nhfutbhs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zntrqenw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gt2twswzyrz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2viliycyr.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2hxvoadss.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ehwqpu.com/Article/details/gt2eifzrolz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gt2xbrqpcgd.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2csnuypyq.html

[D04] 删除元素
来源：http://dali.guannengcc.top/Article/details/gt2fbktchqs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gt2qndefasg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gt2hjgikqty.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gt2rttvxjcp.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gt2yacsxwub.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gt2ymbmtgeh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gt2mgjpszcu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gt2thzaeonn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gt2xrdkoirm.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gt2fjulaqwo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2qjlmqpew.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2lcpuqhxa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gt2krldoujy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cgmqtrnl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gt2pvtbzmfz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2nwgelvgq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2ctbqbddq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etzlgtmv.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2fysjcxsw.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cuxkcmbt.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2tkuuqruy.html

JS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gt2roumvbbb.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlzwzzej.html


<!-- 参考信息 -->