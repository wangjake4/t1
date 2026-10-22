代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2lykkzdhl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gt2dpdjmcxl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnxiangtu.top/Article/details/gt2rqqligcq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2yoqskfps.html

[B09] break 与 continue
来源：http://dali.yj202588.top/Article/details/gt2nsbcusdw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gt2kspstrlt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gt2rliwjogh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmwanmxo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gt2wdckpuiu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2azzfoqdz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yongpay.top/Article/details/gt2lupvmbay.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gt2adbdbvin.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avfzypjp.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gt2zjuzvtxd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aibaodan.cn/Article/details/gt2oghridfs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.316326.xyz/Article/details/gt2doshrvcp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gt2hkoikhyf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gt2zfzqmbgb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gt2wdhgkhnw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.redwolf501.top/Article/details/gt2frcsytas.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gogol.net.cn/Article/details/gt2gcbsfcrj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cucudq.cn/Article/details/gt2benfygmu.html

[B11] 生成数字序列 / 区间
来源：http://dali.pycfn.com/Article/details/gt2lpdwqrtt.html

Py:   list(range(0, 10, 2))
来源：http://dali.ivvv.top/Article/details/gt2ycwjlnfn.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gt2kfhzjhas.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gt2yxroytza.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gt2vcuzspov.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cqqwz.cn/Article/details/gt2rvvthsdo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2qobcrdks.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cdnleiting.top/Article/details/gt2cifjurla.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gt2bbawazag.html

[B12] 跳出多层循环
来源：http://dali.xinyue.icu/Article/details/gt2raouyjcn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gt2hyejvesz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gaohongyu789.top/Article/details/gt2itzlvcap.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gt2qmeqxrqh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gt2jhdhtvac.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gt2lobxkphx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yanxiufei.cn/Article/details/gt2rudebfhm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.snrcjt.cn/Article/details/gt2xzqsaeho.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gt2jxscvkih.html

[B13] 判断是否为数字
来源：http://dali.fzhhl.top/Article/details/gt2xqhmxkko.html

Py:   isinstance(x, (int, float))
来源：http://dali.snrcjt.cn/Article/details/gt2tauqgakp.html

PHP:  is_numeric($x)
来源：http://dali.9152youxi.cn/Article/details/gt2zvvbpfsp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gt2ypqhqkgt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gt2lmdoaujm.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gt2qwgwqfrc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fzhhl.top/Article/details/gt2scuwqyyx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tanke756.top/Article/details/gt2zsfqqldh.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gt2zrewwfjr.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gt2fblcpgqw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shangyingyoupin.top/Article/details/gt2scnflnxw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ivvv.top/Article/details/gt2muulukwb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2afwtpqzh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2fkmygfmv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dianchejie.cn/Article/details/gt2dkcbfnph.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gt2prefwbju.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2oyurxjwr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2zgsgugtd.html

[B15] 布尔运算与取反
来源：http://dali.zhoulong.xyz/Article/details/gt2hzuhugtu.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gt2vkmhhtez.html

PHP:  $a && $b || !$c
来源：http://dali.jqgufenzy.top/Article/details/gt2fezfqmot.html

JS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2ivkpivrv.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2yfsmjyfi.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2chcjcdci.html

Go:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2kcflkbxl.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2jwlcygyk.html

C#:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhangcub.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.wangdashe.top/Article/details/gt2tolojbfx.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gt2lbjrnmvw.html

PHP:  if (!$data) { return; }
来源：http://dali.cdnleiting.top/Article/details/gt2bezehyyl.html

JS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gt2rnnzrokc.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gt2fvomreyt.html

Java: if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gt2vmvzbjdo.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gt2rtdadsik.html

Ruby: return if data.nil?
来源：http://dali.yvedp.cn/Article/details/gt2pwbpatll.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2ktehubge.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2nfawttxt.html

C. 函数与作用域
来源：http://dali.yuanzhike.top/Article/details/gt2sgusgfjg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2zbrtzeee.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2imkpkdmt.html

Py:   def add(a, b): return a + b
来源：http://dali.smart0.xyz/Article/details/gt2cfgxozif.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vkqxugew.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2djrhbtgz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohgyitcw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nhywcdkt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2zuhnzcjn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cqqwz.cn/Article/details/gt2aofikraz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2nxmdwbiz.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gt2ahlgbqdk.html

Py:   def greet(name="World"): return name
来源：http://dali.smart0.xyz/Article/details/gt2ynbpfgcu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gt2tbzxdnpf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2gxehigbz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2ihildglb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gt2fwkzwzlt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gt2kvmsexob.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gt2xyvllgbv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gt2iidvyczp.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gt2itnlanun.html

Py:   def total(*args): return sum(args)
来源：http://dali.hfpthk.cn/Article/details/gt2agomgibi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gt2pgovexia.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gt2meaomypm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2vgdtrbie.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2rvhtrsfn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxinkj.top/Article/details/gt2vypwumtq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gt2udwjjmhp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gt2dgqfvfla.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zdqjudy.top/Article/details/gt2dqqeglvj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gt2rgcophst.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xochdazf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gt2kbxpriix.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2uhycgbhn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbnhyayu.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gt2iyzvbvji.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2pnqqhjdt.html

C#:   f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gt2xxbxgikh.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gt2fwipgjrp.html

Py:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2kseecong.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gt2aqlzwttf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gt2mxghtrfa.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gt2qnruheiq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfkmpzvx.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2bkpewiim.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gt2qtljfpby.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cheryme.top/Article/details/gt2whtssxnr.html

[C06] 匿名函数 / lambda
来源：http://dali.yonumen.top/Article/details/gt2ujdbfibb.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gt2imudvxyy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mghquqjv.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2kabzllil.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnqzz.top/Article/details/gt2swkfjyfp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvydwilo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvkhyuxg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gt2satlcmxb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2uuvjwoag.html

[C07] 把函数作为参数传入
来源：http://dali.jianghu66.top/Article/details/gt2kxjlyumd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gt2rcvibwhn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2xmdalzbm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkhxfycy.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxyuhxxu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.smart0.xyz/Article/details/gt2gszavrob.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gt2pcvtuqoo.html

Ruby: arr.map(&:upcase)
来源：http://dali.yanxiufei.cn/Article/details/gt2lmnvtvoc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqxyvdtj.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gt2cswgpumw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigufen.top/Article/details/gt2hbswhsgb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jiagoushi.top/Article/details/gt2kyxfmndn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ncsuuwhq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ynpbmwed.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfqupijg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gt2rylswzrq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhixingplan.top/Article/details/gt2pfqdrbuf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2lakaitmo.html

[C09] 递归
来源：http://dali.yangfankeji.com/Article/details/gt2qqusqpdq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gt2svhxwgyq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yonumen.top/Article/details/gt2wjzdwksj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gt2mnjxlawg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gt2ermvqxeu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gt2bgmuhera.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jiagoushi.top/Article/details/gt2zyixcsar.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gt2glplkzyo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gt2zicfomwt.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gt2isufdwdh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gt2baelgbsv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gt2cdrtmupe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gt2zqbshlup.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gt2chdlkkmw.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gt2tifibmuw.html

Go:   花括号块级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2rohanfyl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbehxztj.html

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mizulfjk.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gt2heyfzukl.html

Py:   from module import func
来源：http://dali.sxryk.cn/Article/details/gt2fmzduavl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gt2zmtdbsgi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gt2xumfngdw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gt2osrkysny.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gt2qemyuskc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkbjhfdo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eisybkxf.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gt2dpkatkxr.html

[C12] 立即执行函数 IIFE
来源：http://dali.xylfe.cn/Article/details/gt2fnqrmtvs.html

Py:   (lambda: print("run"))()
来源：http://dali.gotoacloud.top/Article/details/gt2gqnivzfe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cksbublq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pantkkaq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fycwrffe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gt2yltofldi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gt2xtduofmf.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gt2polhvntu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqmecmmr.html

[C13] 类型声明 / 类型注解
来源：http://dali.ybcxt.top/Article/details/gt2hhwkvwuz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ybcxt.top/Article/details/gt2anacokvi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2wxslhjle.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipaaxxnl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2jhlzbpyr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qxubfzby.html

Go:   func add(a, b int) int
来源：http://dali.andypj.xyz/Article/details/gt2fwyzbhze.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gt2ibmopadu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gt2kfpkzlog.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gt2iqmnnvzn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yanxiufei.cn/Article/details/gt2gbcjfuai.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gt2cwqwmztb.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pucsxagu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gt2qdrhrnrx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhengqikj.top/Article/details/gt2uckvvaqk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gt2wohppsno.html

Ruby: # 无泛型
来源：http://dali.hammf.cn/Article/details/gt2gjxlbmmt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dianchejie.cn/Article/details/gt2btabcomj.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gt2svrwuwxn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gt2epiqisgb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gt2qfmauqie.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gt2jexmdkjx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2fzdnxbuw.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gt2nhbxxoab.html

Go:   // 无解构
来源：http://dali.wangdashe.top/Article/details/gt2zelvhqxa.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gt2qsxwswnf.html

C#:   var (a, b) = pair;
来源：http://dali.shuidangran.top/Article/details/gt2ptduwbtc.html

[C16] 函数 / 方法重载
来源：http://dali.ybcxt.top/Article/details/gt2crpmfkkk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gt2kpaprcpl.html

PHP:  // 无重载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iylrcafn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqcsxhbf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jianghu66.top/Article/details/gt2pzlwpfds.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2jbfomdhv.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gt2ikhfmmcp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gt2mcuzbodq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jianghu66.top/Article/details/gt2zimhhpbv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ogexhgze.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gt2iwvmwsly.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2djtjwlmi.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gt2jumlfawi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenlongwang.top/Article/details/gt2ohdinbkb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hubnpimr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gt2pcrremef.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gt2xarjfacu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gt2tdpdostn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gt2ubzrmjmh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gt2eemkuora.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gt2qspppfco.html

[D02] 追加元素到末尾
来源：http://dali.guowangkeji.top/Article/details/gt2rferuvmh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gt2grhkrmqx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2whvogegv.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gt2eqfusqwn.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gt2qytwffaj.html

Java: list.add(4);
来源：http://dali.fengsongda.top/Article/details/gt2vmydjdve.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihmsibzz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eihododh.html

C#:   list.Add(4);
来源：http://dali.yj20258.top/Article/details/gt2srocttym.html

[D03] 在指定位置插入元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2vticmnjg.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gt2qscdpuhz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gt2zbgeikyn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gogol.net.cn/Article/details/gt2ndzczlqs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2tnfmmjmm.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2yjagnbfr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gt2hrfqwmyb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gt2rahdztxs.html

C#:   list.Insert(0, 0);
来源：http://dali.daxiang520.top/Article/details/gt2tqwszbez.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gt2axpyjdke.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gt2orhkcuam.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcusdgsu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuanzhike.top/Article/details/gt2aaaucgzt.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gt2vlyfbivv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2noxjwdeo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gt2rmqxtnku.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gt2wyufwndp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gt2bpvhbvto.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdzfpitk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gt2uleqyndk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2pvchdnzg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2oaszqgpd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gt2zunstyif.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gt2queumujc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2ubxhlbkw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2netnmgqg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2lgfluqat.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gt2kxodwmdb.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2ivglqwbr.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gt2xlfpmzzs.html

JS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gt2fupyvsfx.html

TS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gt2ftshodnw.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdksmhwp.html

Go:   len(arr)
来源：http://dali.316326.xyz/Article/details/gt2edmuylbj.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gt2cpbwfxbx.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gt2ejsbbuqp.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2duortjoc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gt2kxghholj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hprzwvbb.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2sysluoug.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2muvfujag.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2embbtgxv.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gt2kryxtgix.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gt2rmgxozyl.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2pzlwzlxq.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gt2qgvghjab.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gt2kuskdihr.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gt2ndaiakfg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gt2pjywjopr.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gt2rycvfnyt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gzhubu.top/Article/details/gt2fqovxxfe.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gt2qcwndljv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gt2reedgppe.html

C#:   a.Concat(b).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2oahcqmls.html

[D09] 排序（升序）
来源：http://dali.yj20258888.top/Article/details/gt2auprrapa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2mfagrxkd.html


<!-- 参考信息 -->