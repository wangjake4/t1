代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.sweek.top/Article/details/gt2ohqeeozb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2wsziragw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gt2zxbodksp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2lovqofft.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2fclutqby.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ivvv.top/Article/details/gt2mxmgmhrd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dianchejie.cn/Article/details/gt2cfcqkqle.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2hmhinerh.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gt2ceeujylr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nanxinkj.top/Article/details/gt2tipwvfwq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gt2ufcgtdgc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gt2tqtwmkva.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2buqqpkfn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2etaoeiqn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gt2jopzokew.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jlsjyb.cn/Article/details/gt2fphsjcpg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2kpvkvfbk.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltoqsppz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.snrcjt.cn/Article/details/gt2lmmogvkl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnctmydf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gt2vqtjltzo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibggpzpu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkfxxlly.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgfzy.top/Article/details/gt2qxjglosw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ppjwa.cn/Article/details/gt2vmzrdhbe.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnqzz.top/Article/details/gt2qotxjbnj.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gt2nurnnxcn.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlxvwsiv.html

PHP:  range(0, 10, 2);
来源：http://dali.9152youxi.cn/Article/details/gt2hfmrtsac.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gt2knyupfei.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gt2ozqnlwps.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.smart0.xyz/Article/details/gt2pszormag.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkxbkexe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2mmbyqbup.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yongpay.top/Article/details/gt2kaeqhuoh.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gt2pioaypxm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugzmeeee.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.haohaochexian.top/Article/details/gt2pmwofhsr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gt2xnhuecyp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gt2wnwostcs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gt2wycwjuka.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gt2ueajvbmx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gt2dvuwnriv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gt2tarpgfum.html

[B13] 判断是否为数字
来源：http://dali.jinqigfzy.top/Article/details/gt2odwpyiga.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gt2gwthcffe.html

PHP:  is_numeric($x)
来源：http://dali.vqdsnc.cn/Article/details/gt2mwlhyucm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gt2vjjoezmg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2etxwalbr.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gt2ecihzdri.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hammf.cn/Article/details/gt2uahztlcy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.andypj.xyz/Article/details/gt2cqhxoemc.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gt2osvjqpyy.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gt2feaubsxp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ehwqpu.com/Article/details/gt2xorcitdc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gt2wvezndie.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2knmpgncm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2gwjsjmld.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2ltjsshlh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daxiang520.top/Article/details/gt2cibmjpuh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2mdezkisi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2vltbprsc.html

[B15] 布尔运算与取反
来源：http://dali.nanxuanxn.top/Article/details/gt2uysjzxrt.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntloehfj.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxubbthn.html

JS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2zttuqjyq.html

TS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2sjjjstxh.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gt2wudosrpe.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2yiikzajx.html

Ruby: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2xtycjhmj.html

C#:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2wooqljqr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2peykgyim.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gt2polysguz.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gt2lfmrjvym.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gt2fksphfsl.html

TS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gt2hwirgpsv.html

Java: if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gt2wkfdlbop.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gt2exwetyqq.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gt2jsrvjmih.html

C#:   if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gt2jybyfuwz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2trwimhte.html

C. 函数与作用域
来源：http://dali.meibo888.top/Article/details/gt2bzrsdmkm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2aqbnwnmx.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gt2cldyegrd.html

Py:   def add(a, b): return a + b
来源：http://dali.mhx1999.top/Article/details/gt2tkqsfhnf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehdfyrtg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2inswxpgw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2cfoetfdj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2xedeafzi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gt2ossmvfcn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gt2jbkveetc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gibjvqdm.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gt2wbxphatj.html

Py:   def greet(name="World"): return name
来源：http://dali.yj202588.top/Article/details/gt2curtejgh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cdnleiting.top/Article/details/gt2jwoaczyf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2gnqsfhku.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2crosauqy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hongshengwenyu.top/Article/details/gt2gngkbykb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gt2uttclsur.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gt2sojktily.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gt2dmqhkfvo.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyrqibvy.html

Py:   def total(*args): return sum(args)
来源：http://dali.daria6918.cn/Article/details/gt2pajfqttg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llhzzgnd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gt2pgdtyrso.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2umvrkkcu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xeensqiu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mynmszky.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gt2lowuswzj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gt2rjywsjhc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gt2ozgjnrjt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cashguo.top/Article/details/gt2cyavkfue.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvxvorbz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gt2rdkplyqs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gt2wkptazhu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gt2frzrlpax.html

Go:   // 无：用配置结构体参数
来源：http://dali.tianlin.xyz/Article/details/gt2aiyrgbol.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2tbznhnsx.html

C#:   f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2yuthuqnf.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gt2mionkqmu.html

Py:   return a, b
来源：http://dali.xylfe.cn/Article/details/gt2njbmewmt.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfurwicc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gt2rhusclnq.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhwzfuhb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gt2icuwedsu.html

Go:   return a, b
来源：http://dali.yueranfly.top/Article/details/gt2deeobbwh.html

Ruby: return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmfzfcsv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gt2astimebz.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gt2verujgux.html

Py:   square = lambda x: x * x
来源：http://dali.smart0.xyz/Article/details/gt2qjafcune.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gt2yblewvxr.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2habdxcou.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.birdmap.top/Article/details/gt2kzhevzld.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gt2qbuszlen.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrivmipf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.0kj1m.cn/Article/details/gt2yczhghvc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gt2pblrdwtw.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gt2rgpszzfg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sysykeji.top/Article/details/gt2vjhgjlgo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gt2gkiminag.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gt2iibmlmpg.html

TS:   arr.map(String)
来源：http://dali.hnqzz.top/Article/details/gt2yirayxru.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yndfgval.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gt2krthdegt.html

Ruby: arr.map(&:upcase)
来源：http://dali.ivvv.top/Article/details/gt2jjrerlhw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gt2cxwjstkt.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gt2inodomak.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gogol.net.cn/Article/details/gt2xxbkhxym.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gt2lmeuzazv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gt2sllhpvib.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gt2zsnohiop.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gt2ilnejdpe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhtuvxgs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gt2ocgqksda.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gt2sqowmvxw.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gt2xwykgfts.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gt2cqegsnoa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bicawxfx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gt2idszplqz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gt2jucjdbci.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdpubmce.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guowangkeji.top/Article/details/gt2oirxvmlr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gt2wmmjtzsc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gt2wqnfvqft.html

[C10] 变量作用域
来源：http://dali.gotoacloud.top/Article/details/gt2icjxajgo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gt2ocodxpbx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cqqwz.cn/Article/details/gt2lepayepx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gt2psluoedd.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gt2wobhuvok.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2fpesjwln.html

Go:   花括号块级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2lgarqiea.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gt2gykcvtsx.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gt2ewhbxvsj.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gt2lulevhjm.html

Py:   from module import func
来源：http://dali.c1oappe.top/Article/details/gt2lynayljy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258.top/Article/details/gt2ebitptrm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gt2fyzevmye.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gt2tujoyuyr.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gt2slncvomp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gt2wlvoxnsl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gt2equfmhkh.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gt2mgcireps.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gt2fakkkozy.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gt2gqajtuiq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sweek.top/Article/details/gt2ttcdevzr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlzrfbzk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2hsldjrvu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gt2ghcqkvse.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gt2rzcbsgou.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gt2pwbbymzy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gt2vyljsvde.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gt2prgfdpeg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ivvv.top/Article/details/gt2zhcvmmks.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2ugwcxzrp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gt2etelstrv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2guzikjuu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2eweemnde.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejqjnoha.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gt2rbwhyjuy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gt2fhmivgwd.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vrtbkpoj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqpliljh.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2zzoqtduj.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2pdltoijt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ydzc1.top/Article/details/gt2iwlonhpu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gt2ogjqhedu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gt2niqhsnag.html

Ruby: # 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2qmulzjoe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gt2pdshollj.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gt2avgjnufd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gt2rfpuxinc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gt2vloshnmh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gt2fboqhrfs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gt2pruyvekk.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gt2cljblqsd.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gt2yhraccag.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gt2hdkntrmw.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gt2utewzzxo.html

[C16] 函数 / 方法重载
来源：http://dali.yuanzhike.top/Article/details/gt2nkmmcidw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gt2xenctbvk.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gt2ktsgwddr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.quarkkingdee.top/Article/details/gt2tgkaqsvr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gogol.net.cn/Article/details/gt2jdvckuis.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tanke756.top/Article/details/gt2qtoklysg.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gt2wrcuuezr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gt2rrxaxaal.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gt2dotlpdwt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2htubrbyg.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgufenzy.top/Article/details/gt2zmjhnyxl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2lfkgqwcy.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gt2rhzbpwvp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gt2qhkdxgtf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2iqvijsiu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gt2snefkcxw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aanfqhjk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gt2vzwlxnwc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dashuyun.cn/Article/details/gt2donafduz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gzhubu.top/Article/details/gt2ofkennwb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvbqwch.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zaevvbri.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gt2htvsrtun.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jianghu66.top/Article/details/gt2ogkyzrqg.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gt2sdjhbzyf.html

TS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2hluppbfz.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2eineuezn.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2flapdhbp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2iabeycxq.html

C#:   list.Add(4);
来源：http://dali.daria6918.cn/Article/details/gt2ekikgvdf.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gt2orrvyfxz.html

Py:   arr.insert(0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2deuhsnro.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gt2sezoodcq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gt2ekbstqnx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2fqnlfpgp.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2jkndbnsh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gt2mgsshnmj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gt2enrwqdgw.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2pxezvbak.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gt2xiwiwyoj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gt2hgzzrhaj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2hnuvagld.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dianchejie.cn/Article/details/gt2srudhuod.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgufenzy.top/Article/details/gt2mfgsyhrn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gt2cnanmlsw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctafyngx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2hkcugqvi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gotoacloud.top/Article/details/gt2cxudtvvz.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gt2rpwijlll.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqbicvg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gt2uhxkchkb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2sjceicyo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gt2eycrwpkm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gt2wkettxnp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2jfubtkgz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2inrfmlyg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2qqlkatqm.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gt2gbhitxpv.html

Py:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2kxrsjinv.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ayslklnq.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wspalxkx.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gt2drnaqnwu.html

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gt2srqzhzpn.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2shetgyog.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gt2mllcopqf.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gt2gipzdkdp.html

[D07] 切片 / 取子数组
来源：http://dali.nanxuanxn.top/Article/details/gt2lljpgygd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gt2vjzykqhu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gt2tecdkddd.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2nmshmfib.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gt2olxqcihs.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2oipsptla.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gt2nnuuekca.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gt2dmpcnvbi.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gt2qksysqba.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gt2snpvaqpc.html

Py:   a + b;  a.extend(b)
来源：http://dali.yangfankeji.com/Article/details/gt2jacggywp.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gt2wdnrzivn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gt2zqwbokov.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gt2pmwmswwt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2dwlxmboa.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrtyoyvx.html


<!-- 参考信息 -->