代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtdqyoixku.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yuxming.cn/Article/details/gtjammlcvu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cucudq.cn/Article/details/gtovackxne.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hywenlv.cn/Article/details/gtpbnjvkmc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ivvv.top/Article/details/gtsggsqdmm.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gtlbofkagl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gtjirvuyes.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jyoumei.cn/Article/details/gtmwzqdbzc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtckmdrlcq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangdashe.top/Article/details/gttbgetnks.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cashguo.top/Article/details/gtgvssqgva.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yongpay.top/Article/details/gtehnmuhmt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ehwqpu.com/Article/details/gtsdggyxsm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.aizwys.cn/Article/details/gtccacdzro.html

[B07] while 循环
来源：http://dali.chenlongwang.top/Article/details/gtdogabcgu.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gtoqxcjfio.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhengqikj.top/Article/details/gtokzbpdfs.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gttstcbavt.html

TS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtskzdoazj.html

Java: while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtwrbnghhr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.bjfxy.top/Article/details/gtpuqndmbw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yueranfly.top/Article/details/gtokmqtklo.html

C#:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gttfeduofr.html

[B08] do-while（至少执行一次）
来源：http://dali.hfpthk.cn/Article/details/gtgbcipvth.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.andypj.xyz/Article/details/gtlovhtwli.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtclitdwmu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtaviioblb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtaobpekfp.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtcmijehrl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ppjwa.cn/Article/details/gtoxbzprfu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhengqikj.top/Article/details/gtnrnqamyy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtdtfabqda.html

[B09] break 与 continue
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvuvogzj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jlsjyb.cn/Article/details/gtyohyfuum.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtywjodvyd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtonyonpai.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtiurjddbs.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtxhhyovor.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gtmvrdzmja.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gtuvccfyib.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtzdrooehr.html

[B10] 遍历同时拿索引
来源：http://dali.fzhhl.top/Article/details/gthsbgmuff.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgfzy.top/Article/details/gtljtjsotq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtawkxukgx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gtagdumwqm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gteakbatus.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gtcybgzkku.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tianlin.xyz/Article/details/gtesueppne.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.iojbl.cn/Article/details/gtatnhpvrw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gaohongyu789.top/Article/details/gtoinjkgts.html

[B11] 生成数字序列 / 区间
来源：http://dali.ivvv.top/Article/details/gtbhsjecge.html

Py:   list(range(0, 10, 2))
来源：http://dali.daria6918.cn/Article/details/gtunbgpiln.html

PHP:  range(0, 10, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmdqyrdp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gttdlrotce.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtktfqahil.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtclzldhcs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gtypkadayd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gaohongyu789.top/Article/details/gtomjrfglt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.bjfxy.top/Article/details/gtakasgyha.html

[B12] 跳出多层循环
来源：http://dali.zycfv.cn/Article/details/gtsfeigsfk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.9152youxi.cn/Article/details/gtpvenlyjc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gtpylcuwrn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtyunxhsyv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtmbisueuk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gtndvpbnll.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gogol.net.cn/Article/details/gtwcmrwvuf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gtujqymnza.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gteavzrnkw.html

[B13] 判断是否为数字
来源：http://dali.haohaochexian.top/Article/details/gtgqtfokxg.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtaxbzuijq.html

PHP:  is_numeric($x)
来源：http://dali.birdmap.top/Article/details/gtyeqytprq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtmbxozrzw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtkrbvwamd.html

Java: x instanceof Number
来源：http://dali.gzhubu.top/Article/details/gtmcrcqjiw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zycfv.cn/Article/details/gtfmwzzsmt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dashuyun.cn/Article/details/gtatdqcwfk.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gtwzxcwfaf.html

[B14] 判断值是否在集合内
来源：http://dali.shuidangran.top/Article/details/gtaeyzllhf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveruhhdl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenzaomai.com/Article/details/gtzldbofzc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkhxxaoj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtihsjsipt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtnezqpvqp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.birdmap.top/Article/details/gtqolsomug.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtjbzxnjez.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtrfonbhzu.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gtsphifuxb.html

Py:   a and b or not c
来源：http://dali.haohaochexian.top/Article/details/gthytfvlpe.html

PHP:  $a && $b || !$c
来源：http://dali.jlsjyb.cn/Article/details/gtnudljlrr.html

JS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtlctlvxyv.html

TS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtcmjsyzjn.html

Java: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtpindgdjj.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtpyqiltxa.html

Ruby: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtxdxhyubf.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtehgwnqtb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.birdmap.top/Article/details/gtptirgchg.html

Py:   if not data: return
来源：http://dali.jyoumei.cn/Article/details/gtobastbnl.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gtgzwqmezc.html

JS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtsrlccryw.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gtbbqmwewn.html

Java: if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtqkhvyium.html

Go:   if data == nil { return }
来源：http://dali.yuanzhike.top/Article/details/gtouqedqsz.html

Ruby: return if data.nil?
来源：http://dali.zycfv.cn/Article/details/gtpbeoxayp.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtbfqavkrt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkkxppmoe.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gtqbupbvag.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtcdgrxiiz.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtpqbjerkp.html

Py:   def add(a, b): return a + b
来源：http://dali.birdmap.top/Article/details/gttksvmrni.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtcidrmhcv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtafbxpmtd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtjtivjxcq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtncqhwwao.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gtlrkgifcf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gthwwvdoga.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gthkwehfyf.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gtqulovrqu.html

Py:   def greet(name="World"): return name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttqivktq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gtvscntkfk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtybksjnyr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtgwtcmgbq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuxming.cn/Article/details/gttideglov.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xinyue.icu/Article/details/gtvrwqwjyb.html

Ruby: def greet(name = "World") = name
来源：http://dali.yanxiufei.cn/Article/details/gtauvrzzbj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtyrdduakj.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gtjmamwgjy.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gtyljycwpu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigfzy.top/Article/details/gtsunhsoeh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gthhafvmfn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtdhrqcbjw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gtsdanjaba.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gtfeglrioe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cqqwz.cn/Article/details/gtmsjqmsmo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gtntrotnxv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ydzc1.top/Article/details/gtzelviqts.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtbdqosroj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gtishhqgah.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gttrkhyndz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gtfwxkdxmj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.birdmap.top/Article/details/gtklmpzqyf.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gtamtocexj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtdqcnwerm.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtiscyfelh.html

[C05] 返回多个值
来源：http://dali.daxiang520.top/Article/details/gtzyuopals.html

Py:   return a, b
来源：http://dali.yj202588.top/Article/details/gtdyllpwnz.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwqcclcc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtwnfcfavd.html

TS:   return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtaixgiszh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gtpsvjqbgi.html

Go:   return a, b
来源：http://dali.xinyue.icu/Article/details/gthgzjbwjb.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gtterbkgan.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gtuhibekre.html

[C06] 匿名函数 / lambda
来源：http://dali.zycfv.cn/Article/details/gtmawfvqgc.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gtkonjxrnc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttknypvul.html

JS:   const square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gthxduovds.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fengsongda.top/Article/details/gtadufzpjs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.316326.xyz/Article/details/gtnexfjwvq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cqqwz.cn/Article/details/gtsqzlhzyb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtgkwxpqfn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gttllngnrg.html

[C07] 把函数作为参数传入
来源：http://dali.guannengcc.top/Article/details/gtfflnnoto.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gtzxunwzwy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtustmdwgj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gttmneyudw.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gtzkesbhvm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gtzqykdbil.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gtnqmaajii.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhixingplan.top/Article/details/gttnowsntq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtjwkymszv.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gtuxqasizs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gtfgxwfmka.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gtaxdpijjf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtrmcklyzg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtusxzahyx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gtkuiaqtou.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gtmurpwxhf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gtvsnnpljb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gtvsteophx.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gtsejhlyxc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtafcozyrt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtxsxdigwm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtzageqoah.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtatjkruhn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtpkkomlbs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yvedp.cn/Article/details/gtntumapjh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqqpinadf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gtokefwrtp.html

[C10] 变量作用域
来源：http://dali.guannengcc.top/Article/details/gteddmllda.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtdxbsetll.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gtrjqfcxwh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dashuyun.cn/Article/details/gtpmnincus.html

TS:   同 JS
来源：http://dali.yj20258.top/Article/details/gtbsghutix.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gtratbmphh.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtxsuiplqj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gtwnmjednn.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtcpbbrdcq.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gtkggyblev.html

Py:   from module import func
来源：http://dali.mhx1999.top/Article/details/gtccekkcvx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guowangkeji.top/Article/details/gtrdtwhask.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gtuicndowb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gtaqtzbbok.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gtumoaadok.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gtfdgyrlaj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.andypj.xyz/Article/details/gtikpifttg.html

C#:   using System.Text;
来源：http://dali.gotoacloud.top/Article/details/gthayicnul.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gtwtqgcotl.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gtevsiihut.html

PHP:  (function () { echo "run"; })();
来源：http://dali.havefunace.top/Article/details/gtlherttgl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtkhfytctw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtwdjikxkm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gtzhdcypiz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtdhstcayh.html

Ruby: -> { puts "run" }.call
来源：http://dali.zdqjudy.top/Article/details/gtydgokmbf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gtdeiuspjk.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gtwxkggstw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gtlhjcnvfv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtusswevsm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gtoqzjxceu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtfhhyybdl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtacturlbw.html

Go:   func add(a, b int) int
来源：http://dali.xziqi.cn/Article/details/gttfxrlrtg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gtvmhockcd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gtjszxuvdp.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqaokppn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gtynunrhpf.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtsmztecdu.html

JS:   // 无泛型
来源：http://dali.c1oappe.top/Article/details/gthowsfams.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuanzx.com/Article/details/gtlqxvjmhk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gtkwnavjxb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gtqxsmmonh.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gthdngqvgu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxuruyxh.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gtekjsjsjp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gtzvioongq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gtwsorqidr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gtbqmeqvbq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgytxmvrz.html

Java: // 无解构
来源：http://dali.yuxming.cn/Article/details/gtripizbla.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gthoyoqqtb.html

Ruby: a, b = pair
来源：http://dali.tianlin.xyz/Article/details/gtryvgevdu.html

C#:   var (a, b) = pair;
来源：http://dali.havefunace.top/Article/details/gtcmfgtowf.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtjlflavua.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gtchkdjsbn.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gtxolcnixv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gtrcieiyzg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gtptprvrbf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gtgzoabpze.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gtgyhcdift.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gtdpoejyjy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258888.top/Article/details/gtgmolrdvm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtokbimtly.html

D. 数组 / 列表 / 集合
来源：http://dali.snrcjt.cn/Article/details/gtjnnjkxmd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtivugdvpx.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtebanzzek.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gtxrydzztp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.9152youxi.cn/Article/details/gthuhlhiov.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtevarfjks.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gtkhmgtwsx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtqghygciy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysddkiws.html

Ruby: arr = [1, 2, 3]
来源：http://dali.0kj1m.cn/Article/details/gtzuwqqcvp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gtcbtwayhc.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gtfxzseubb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gtqmvdcjcp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gtvvruuvir.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtxkjyiruq.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtdsmoyhta.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxxhqshq.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258.top/Article/details/gtsztzdupe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gtgpbiclmi.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gtmvglmdwi.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtnveuvmza.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gtrztrbxch.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.birdmap.top/Article/details/gtexoyonkm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.c1oappe.top/Article/details/gtrtdovimx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jianghu66.top/Article/details/gtbbxhoqyz.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtpbwqhxcu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtrwsjvaha.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gtznienmdx.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtbamafltb.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gtcorkarnj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtqogkwjfl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gtgfylljya.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtaxlhfljh.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtdhzvgysw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gtbdrtksqk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gtabjkuvwv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gtrqmfiqgx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gtrgilwrrf.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtgsucrmzl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjphzbxvt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtrvoumprn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gticxxyhzw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gtrnbzheeg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gtfxqpudmk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtgisiyuxi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtqlrbqjij.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtydgvwjlh.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtebeklcvk.html


<!-- 参考信息 -->