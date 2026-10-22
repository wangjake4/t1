代发 wailian999

[B09] break 与 continue
来源：http://dali.zhoulong.xyz/Article/details/gt2zmxabpfk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gotoacloud.top/Article/details/gt2elkayivj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2kvopxshc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2ojfrxaqc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gt2xbhdygvp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkuxouec.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sysykeji.top/Article/details/gt2ljcmkrdq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gt2lgdrfsfw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2mkozrpws.html

[B10] 遍历同时拿索引
来源：http://dali.xylfe.cn/Article/details/gt2lglmuxbj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulcvybon.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangdashe.top/Article/details/gt2hbacluzh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gt2lcomrmrk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gt2vczzrwjg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gt2vwyzpqqu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbmkuxaf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnqzz.top/Article/details/gt2wcekgqtf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iujdibmo.html

[B11] 生成数字序列 / 区间
来源：http://dali.gotoacloud.top/Article/details/gt2sipggfhr.html

Py:   list(range(0, 10, 2))
来源：http://dali.hongshengwenyu.top/Article/details/gt2phkarbqg.html

PHP:  range(0, 10, 2);
来源：http://dali.316326.xyz/Article/details/gt2dpvvcugh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxztjcas.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gt2mjchuzbu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ruleobhz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuxming.cn/Article/details/gt2qrapzhpo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gt2aiqxgbab.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgfzy.top/Article/details/gt2cobfatmu.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gt2qsmwrvts.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.haohaochexian.top/Article/details/gt2zdsroxlm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zycfv.cn/Article/details/gt2xjdvpsaj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gt2iqgttyna.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2xfhyoeqn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gt2efrtztcg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fengsongda.top/Article/details/gt2ajhrlixr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gt2honvuebl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shuidangran.top/Article/details/gt2ngfkhqwq.html

[B13] 判断是否为数字
来源：http://dali.yueranfly.top/Article/details/gt2ncuopgyu.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fitsgixw.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gt2sgppmwfp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gt2njtbzseh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gt2fnvniwex.html

Java: x instanceof Number
来源：http://dali.hnqzz.top/Article/details/gt2wvlufrwj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yangfankeji.com/Article/details/gt2ioldadul.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhixingplan.top/Article/details/gt2jfuuflod.html

C#:   x is int or double or decimal
来源：http://dali.cashguo.top/Article/details/gt2xuohnlac.html

[B14] 判断值是否在集合内
来源：http://dali.pengpengdd.cyou/Article/details/gt2qiznuxxj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xinyue.icu/Article/details/gt2dkdnwvev.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tian-w.cn/Article/details/gt2nexmszfz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gt2oalrunvn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2wyfyqoxj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2unhqpsuy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guannengcc.top/Article/details/gt2pcvbzioa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.316326.xyz/Article/details/gt2quvkidjh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2jkujcqcj.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gt2vqunhtmk.html

Py:   a and b or not c
来源：http://dali.quarkkingdee.top/Article/details/gt2viinqdfq.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yedrsoyj.html

JS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2mhnpwbyv.html

TS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2biqqggbs.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pasdyqxv.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2nkjzypdl.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2moczvhyw.html

C#:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2ymdbeeco.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cqqwz.cn/Article/details/gt2urnaemxo.html

Py:   if not data: return
来源：http://dali.birdmap.top/Article/details/gt2aqepygml.html

PHP:  if (!$data) { return; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2meugjdgw.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gt2uwzdznog.html

TS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrzfrpuj.html

Java: if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gt2rdytpncb.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gt2zibvzgrb.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gt2pjwtdlcp.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gt2smyucinq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2rergtnnu.html

C. 函数与作用域
来源：http://dali.zhixingplan.top/Article/details/gt2nfobrlkj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2pnsogxtc.html

[C01] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gt2vnsrenwb.html

Py:   def add(a, b): return a + b
来源：http://dali.sxryk.cn/Article/details/gt2ruwzmlle.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2ijvdrmri.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xdxqtlqh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2dfommubj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2bibtcdzi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258.top/Article/details/gt2eknbvryw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenzaomai.com/Article/details/gt2maotjujl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2otwamoiq.html

[C02] 默认参数
来源：http://dali.hammf.cn/Article/details/gt2wvgkmewc.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwzvmonj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shzxlz.cn/Article/details/gt2orfnoufh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2ypcvxaid.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2mbnbtedn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gt2mmpyyuwh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gt2frieiqcq.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgufenzy.top/Article/details/gt2ufqfaxgq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gt2eqfbyoqq.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdcinukp.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gt2jltlaghd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkuxyfy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gt2egqxtivm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gt2tdehhgtp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gt2flrvotrw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gt2tqpronhu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gt2iauucsiu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gotoacloud.top/Article/details/gt2brirlyzg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gt2nkufgnid.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gt2bapdrepw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ivvv.top/Article/details/gt2dflbbyty.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvyervwg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smkzfvlw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gt2uhdfjabi.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2navkecvc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2meuzvlpt.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2cxxrmnid.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gt2cawnfzpm.html

Py:   return a, b
来源：http://dali.birdmap.top/Article/details/gt2ajywqeiv.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gt2oatzgdcu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gt2iloioqzf.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gt2kdoksbaf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gt2bejyokzh.html

Go:   return a, b
来源：http://dali.yvedp.cn/Article/details/gt2gzmseamh.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cckrcrll.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenlongwang.top/Article/details/gt2aewlilwn.html

[C06] 匿名函数 / lambda
来源：http://dali.sysykeji.top/Article/details/gt2tmectvwb.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gt2qqcihwrc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.redwolf501.top/Article/details/gt2dfcycpzz.html

JS:   const square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2iozxvmsu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuanzx.com/Article/details/gt2viclrkno.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gt2sqvtemuu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fzhhl.top/Article/details/gt2zjnphcny.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gt2yagvvrsy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gt2issbbppe.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gt2tfxrhkda.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gt2oqsauvwp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ydzc1.top/Article/details/gt2qmvcnodb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clvzedgn.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljgnjdca.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqrjdorm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ydzc1.top/Article/details/gt2xmlxinvs.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gt2nvmsnjze.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.bjfxy.top/Article/details/gt2wholdpyl.html

[C08] 闭包
来源：http://dali.cashguo.top/Article/details/gt2bjqheqdo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gt2gbygqghi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yvedp.cn/Article/details/gt2zkmxcagc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gt2gxkhyyes.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2oyimarhb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrxfinoa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqsctgdn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cqqwz.cn/Article/details/gt2ymedlzpr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gt2hdjcgqae.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gt2ndshugkh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gt2ulcxmjmq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gt2rurgrest.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gt2nifmkere.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gt2bwyjneas.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gt2gggjnefh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fengsongda.top/Article/details/gt2kfxrzbii.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gt2fwdzjtas.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gt2kfhmgrzh.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gt2mnfsdpxl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gt2qaoicgql.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gt2lsotvrdt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovycrjsx.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gt2qqvmoalg.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gt2yypfzyxh.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2afumyhvl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gzhubu.top/Article/details/gt2rmvfadll.html

C#:   块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2axyevijj.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jaobyspt.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdianpwk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.mhx1999.top/Article/details/gt2jzouxlar.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ivvv.top/Article/details/gt2yubgeact.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhixingplan.top/Article/details/gt2bjysxlrz.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqqxgunw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gt2rnbjjnzz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gt2wonhxwiw.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gt2gusqqvio.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gt2owpvipoj.html

Py:   (lambda: print("run"))()
来源：http://dali.jlsjyb.cn/Article/details/gt2bupwxjpk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gt2zjljuuhh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2nrlaebxf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gt2keqwdmad.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gt2cwnahuin.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ehwqpu.com/Article/details/gt2liyafjjp.html

Ruby: -> { puts "run" }.call
来源：http://dali.yonumen.top/Article/details/gt2vsfzdspc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gt2qvqaxlrq.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gt2fukfywpy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gt2ynzcemzb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2pnrqiuup.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gt2kuccjbui.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2uwroptyc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2octbvvbp.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gt2hrxxiown.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gt2rbgwwksc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gt2qzecllzd.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gt2ioxoqpll.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzyvefgt.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqqwcxke.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gt2vximwvqt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gt2gwspgixh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2sycrqvhe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gt2izvowxpf.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2tpccxjwm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gt2ukgqrvbn.html

[C15] 解构 / 展开参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2guwhmqur.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gt2eyqanzfr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gt2bmoiudxl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mchucadh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gt2mxrvvunt.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2myfculjh.html

Go:   // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gt2eoypgubn.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gt2ukjsgdqu.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gt2xqzlkcnk.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gt2ztidpnvc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigfzy.top/Article/details/gt2ejuarsda.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gt2vbeflnrw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbxukxvm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gt2qdjzfsfe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gt2vixeqwxe.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gt2ihbbqlpk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsbnegrn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gt2zentatgj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkjpktjg.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gt2eyfdfglg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2cbopvnzt.html

[D01] 创建数组 / 列表
来源：http://dali.hnqzz.top/Article/details/gt2kfcsbxwj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gt2msihvvjk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gt2rxaghprq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gt2oaspfpdu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnbymbpi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuanzx.com/Article/details/gt2kuoctrop.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.0kj1m.cn/Article/details/gt2hygzwbzs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gt2zmzklzwb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gt2llgfzxeg.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gt2bbgqdgvd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gt2auzynikn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gizstijj.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gt2pqboddzu.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gt2nkzsubjl.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gt2wictrxqt.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2nynzspim.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gt2afyusbcc.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gt2ngfjoqei.html

[D03] 在指定位置插入元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpcerpnn.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gt2eufhkaxy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gt2bmvjaton.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gt2blsjigxd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2tmjqxane.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbhwsmq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2erotpxig.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gt2nixdgnvf.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2kakigbak.html

[D04] 删除元素
来源：http://dali.birdmap.top/Article/details/gt2odrbnwng.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gt2dbemdmjm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2tvksysus.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gt2dngjhkuj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaytowx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gt2dxwtfkpc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gt2mlnlekpq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gt2rqiyctfj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gt2hthrrzjl.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gt2ojolgwif.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2dwlhsnhr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2aekqrogk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2ucvrbvph.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gt2gbsyslnq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gt2rlsusbuf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2yxtisqcr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2jcwcxmzn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2kakysmcz.html

[D06] 数组长度
来源：http://dali.tanke756.top/Article/details/gt2lwfmhkdp.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2cwxadpls.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2wesuhjdn.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gt2uozqgyxu.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2auisbgff.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gt2txbjgayi.html

Go:   len(arr)
来源：http://dali.havefunace.top/Article/details/gt2kjdsjedz.html

Ruby: arr.length; arr.size
来源：http://dali.gogol.net.cn/Article/details/gt2jjyzzolv.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gt2jwibnaug.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gt2ealweomi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gt2vfhnkkqp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gt2xudfwjkj.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2qrtuxhny.html

TS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2voovbbqk.html

Java: list.subList(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2uzlvmdfh.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gt2lubcurks.html

Ruby: arr[1, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgxzgxvv.html

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2ktgbesun.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfelvchr.html

Py:   a + b;  a.extend(b)
来源：http://dali.jiagoushi.top/Article/details/gt2vaxingkp.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gt2pmfcgdnn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gt2loxpelwr.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gt2qkqjzfst.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xftdgptf.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gt2abpgjyno.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gt2kmsyvpxz.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gt2efgwlzqj.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gt2pvapangg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gt2crznadfm.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gt2lclppgpf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gt2ragratgg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangdashe.top/Article/details/gt2yvftjzeb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gt2mexxlkqu.html


<!-- 参考信息 -->