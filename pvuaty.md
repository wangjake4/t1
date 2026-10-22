代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xinyue.icu/Article/details/gt2vuissoww.html

[B06] 遍历字典 / 对象
来源：http://dali.smart0.xyz/Article/details/gt2gwlgmwpl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqwcmysv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.havefunace.top/Article/details/gt2xjvjkaft.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.birdmap.top/Article/details/gt2gofkoekj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gt2akfucdzw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.c1oappe.top/Article/details/gt2peoglflx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndtxklzd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.316326.xyz/Article/details/gt2kbcnbuzu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cucudq.cn/Article/details/gt2osrdmhhv.html

[B07] while 循环
来源：http://dali.yueranfly.top/Article/details/gt2hhcljzsj.html

Py:   while i < 10: i += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fanmxari.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2mdzxgzxp.html

JS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2jmtwkuah.html

TS:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2miskletg.html

Java: while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2znzeeunl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvdngzun.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2haikfhhs.html

C#:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gt2eirordgy.html

[B08] do-while（至少执行一次）
来源：http://dali.zycfv.cn/Article/details/gt2fnrolgss.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxswxwhl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2sxilapjz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2wyxbzjde.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2dduukubi.html

Java: do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2lakcynib.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpergqlx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xylfe.cn/Article/details/gt2wfmfnfpg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2tejyuqnl.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gt2vtdpgaaw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tian-w.cn/Article/details/gt2nsbsxqvo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gt2bwcyjkyw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2lnxkyrok.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2qhrxxylq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2gnzlicdx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258888.top/Article/details/gt2yxgvynpj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sysykeji.top/Article/details/gt2aegdlbqp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2ctklckzn.html

[B10] 遍历同时拿索引
来源：http://dali.xylfe.cn/Article/details/gt2ivdoczxy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hysaishi.cn/Article/details/gt2qepfoyeu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gt2drjokvvj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gt2emvsocbn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gt2lpqxbwav.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.kuanghao11.cn/Article/details/gt2hvtxmotq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gt2vhtkbilv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gt2yurasyep.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqrfumhr.html

[B11] 生成数字序列 / 区间
来源：http://dali.aibaodan.cn/Article/details/gt2izlmoypu.html

Py:   list(range(0, 10, 2))
来源：http://dali.guannengcc.top/Article/details/gt2vfeghjgz.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrpvatyu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gt2xcduczru.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gt2hydqorhd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2auuwgvfa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gt2mdxvswzm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ivvv.top/Article/details/gt2vrhegqzh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gt2abcvisgl.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gt2labztwte.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gt2xdovonod.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gt2fvppzmxd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gt2kwwjrvtn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gt2hqivrqqn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2vlerultc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.bjfxy.top/Article/details/gt2lvsvxycn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gzhubu.top/Article/details/gt2rfgcthkd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gt2mdrlxbix.html

[B13] 判断是否为数字
来源：http://dali.yuanzhike.top/Article/details/gt2umqdvfgc.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gt2txgfrsmb.html

PHP:  is_numeric($x)
来源：http://dali.yj20258888.top/Article/details/gt2wgqhqtvn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gt2omaenbuf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gt2qvfbqxcw.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gt2cbshjfyq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgufenzy.top/Article/details/gt2exzonfzt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gt2deyhnbou.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gt2fwqeuxes.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gt2xteifwvk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigufen.top/Article/details/gt2chxfauvu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gt2roanusat.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gt2bagaagyf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gt2wqkwsfsa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjeubdyb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2psbgzqae.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gt2kuyrfdhj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2schwjgcb.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gt2nrjgfxod.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gt2xcthesbr.html

PHP:  $a && $b || !$c
来源：http://dali.yongpay.top/Article/details/gt2ydoueoyw.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2ndwcubun.html

TS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2hysdsdfn.html

Java: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2dvjunqux.html

Go:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2kegmnjcq.html

Ruby: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2weonuxyq.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2zxzhvhut.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.birdmap.top/Article/details/gt2klqxxhdj.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gt2stujevnq.html

PHP:  if (!$data) { return; }
来源：http://dali.sxryk.cn/Article/details/gt2eelwbheg.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gt2iduiqflq.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gt2jwehifqn.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gt2zhogdsng.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gt2yirswvxx.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gt2tfrinuov.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2ruatizam.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ucphwyyw.html

C. 函数与作用域
来源：http://dali.mhx1999.top/Article/details/gt2gatzvzpk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2kjjvjdch.html

[C01] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gt2dcynwqoe.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hoojpfzx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2lnssvraw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2jtknyaaa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yveznzql.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2nxnzjdsj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2yyxubopl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gt2qkjahxcs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2xptapfmf.html

[C02] 默认参数
来源：http://dali.gotoacloud.top/Article/details/gt2apkqzboh.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gt2vtqjsiud.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cheryme.top/Article/details/gt2yzjscusw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gt2xdrnpsvt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2dcbrvrri.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aibaodan.cn/Article/details/gt2oizdeusx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gt2rghmnmhj.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gt2vsfozolf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gt2wfnsuloj.html

[C03] 可变参数
来源：http://dali.quarkkingdee.top/Article/details/gt2tqppnpsq.html

Py:   def total(*args): return sum(args)
来源：http://dali.birdmap.top/Article/details/gt2prllkwrt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gt2rbblkkzl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gt2ccyhojxs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gt2jpurdftl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aibaodan.cn/Article/details/gt2nbcygmuv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gt2ktsejhkq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gt2jjkaqayl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gt2zcnvzedp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvxnvqmh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dashuyun.cn/Article/details/gt2iboslghx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dashuyun.cn/Article/details/gt2wubglnkn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gt2xrwzbzrt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gt2wcwnngvw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gt2wwouxcge.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gt2qssuvxnx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gt2rrnaxafk.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2bubpmmmw.html

[C05] 返回多个值
来源：http://dali.redwolf501.top/Article/details/gt2tztoqpuo.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gt2zoxshvct.html

PHP:  return [$a, $b];
来源：http://dali.hnqzz.top/Article/details/gt2mywtdltn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gt2oibecqqy.html

TS:   return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gt2iwlbuqml.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gogol.net.cn/Article/details/gt2apncgumg.html

Go:   return a, b
来源：http://dali.yueranfly.top/Article/details/gt2ktxhyjqj.html

Ruby: return a, b
来源：http://dali.jyoumei.cn/Article/details/gt2xlqkdxju.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gt2umumnpny.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gt2esxfywdl.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gt2bwzpusqi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gt2ctzehfri.html

JS:   const square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2bombryfy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gt2qfgbcawh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2aqkzaamc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djdaifql.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gt2hrcorhqi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2psctzhtk.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gt2zmprrxnf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gt2egeeddzt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gt2hbwsmbbj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gt2cffcuryl.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gt2xjjfmpxl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2urzpzoaa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gt2rhtuzfec.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gt2djbrtclc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gt2iwabtjgw.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gt2ppaanyua.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gt2ugqtvsfm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.andypj.xyz/Article/details/gt2pcjtxbdd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2yureictz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gt2lhknmghd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gt2tiicbsuh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gt2yawkflgz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gt2zkpoisol.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2gqtlhczk.html

[C09] 递归
来源：http://dali.tanke756.top/Article/details/gt2yidfklba.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gt2uhahhlqn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gt2epkvhppy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gt2pajunomh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gt2oathjsgf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ivvv.top/Article/details/gt2jmxxebks.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gt2ullqvrmv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2fgixqpls.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sweek.top/Article/details/gt2mipqyinf.html

[C10] 变量作用域
来源：http://dali.hysaishi.cn/Article/details/gt2pcwluwtj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gt2nsizabjh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gotoacloud.top/Article/details/gt2nyldsuti.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hfpthk.cn/Article/details/gt2tllldhkh.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gt2vuctynjm.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gt2yqhqagvx.html

Go:   花括号块级作用域
来源：http://dali.birdmap.top/Article/details/gt2kfybhnbs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gt2zcvdefbg.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gt2wxlyoiig.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gt2utwlrqii.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gt2cfrfekmq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gt2xnhryvmk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gt2wecjjboa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gt2zgjjmazl.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipltruok.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cucudq.cn/Article/details/gt2yaaxiwmb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gt2mkqlyhur.html

C#:   using System.Text;
来源：http://dali.0kj1m.cn/Article/details/gt2lloosdgi.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gt2etuxfrjv.html

Py:   (lambda: print("run"))()
来源：http://dali.quarkkingdee.top/Article/details/gt2wbxngzbf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gt2tlsctbzc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gt2ceyjhlsj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gt2ygervpjn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jianghu66.top/Article/details/gt2jvgsuknr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gt2yrsllzez.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gt2mispuiga.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.bjfxy.top/Article/details/gt2gsmiqxhw.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atsnrnhx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gt2oxuvpgmy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2yjqmiter.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gt2ngofyrgh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2vgcqvpis.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2pocqusez.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gt2uguzgice.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gt2sccxytqx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hfpthk.cn/Article/details/gt2gxrslthh.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewjdropf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gt2ubdpwshc.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gt2rabicsif.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gt2ioxnkzwl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gt2xzhebubl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gt2qeatvxbh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gt2ugcosjdh.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2ayxzpdqy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.iojbl.cn/Article/details/gt2txbkxpcr.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gt2klyjewji.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gt2awlghgny.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gt2aajrrujj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2mernipkf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2dpemnkar.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2eamzseiw.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gt2bdxitiko.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gt2hxrbgtep.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2zsmnhael.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gt2gplfuwyd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gt2fpqisrsf.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gt2zuqdylzt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gt2bdozwrrm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gt2pmmohinh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gt2wzrqqaji.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gt2megkkrkc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gt2bmwykpjn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2nqqqcfpe.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2miionlpz.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gt2yszcicoe.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2vzhstnqj.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymotorcc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmepftgr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gt2cnteaxpz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aohcdcnh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gogol.net.cn/Article/details/gt2ekyicpdd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gt2iskxkbeb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gt2fnrnmopl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2mqvjnoum.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gt2ejcxiwok.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gt2hzlhkzsg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gt2txfjxnul.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gt2mavsmaqk.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gt2mrwtbbxn.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gt2yybogbku.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gt2nqyuoypw.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxrdlxdz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gt2aywnxiqf.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gt2lfskwurl.html

[D03] 在指定位置插入元素
来源：http://dali.cqqwz.cn/Article/details/gt2lmugelud.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gt2ndhxkqlz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btfrulxj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gt2dryvwyua.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2daqafwhg.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znmowdbx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gt2mcctzqaz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gt2eizhyxab.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gt2pddefppk.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gt2grjccyla.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irjmvxbw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gt2qybirwci.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yangfankeji.com/Article/details/gt2zwhkzbqu.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gt2prypqwmc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258.top/Article/details/gt2jofvfwyl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gt2xncsnago.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gt2keppctun.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gt2lzlmycnj.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2qizfwtrb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gt2jccbdsww.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2xfodhqkz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2mvyzsljm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gt2nfajxqgo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gt2lajldfvv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2ceicyvkj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gt2gruecqlm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2avkgdjpm.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gt2swletlkw.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2pnhwrdgd.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2srngpthm.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gt2ewkqndyn.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gt2djqbhdik.html


<!-- 参考信息 -->