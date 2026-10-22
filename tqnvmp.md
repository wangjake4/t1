代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2htmvbgid.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2stkllyld.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cheryme.top/Article/details/gt2dlyfqbwm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gaohongyu789.top/Article/details/gt2ntguhkwd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2rfaesaze.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gt2tikvbhez.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.kuanghao11.cn/Article/details/gt2lkfouzrs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2flbviywx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gt2tcaivona.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gt2izputzln.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cdnleiting.top/Article/details/gt2axwczuli.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.9152youxi.cn/Article/details/gt2folkzwck.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtybjfig.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtihndkg.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gt2yocupith.html

Py:   list(range(0, 10, 2))
来源：http://dali.nwbrower.top/Article/details/gt2yxhdoygq.html

PHP:  range(0, 10, 2);
来源：http://dali.9152youxi.cn/Article/details/gt2hlmmyucv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gt2nilacwae.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2umvzficg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.guowangkeji.top/Article/details/gt2jutixdon.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmnrztij.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgufenzy.top/Article/details/gt2vhgywgpn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.redwolf501.top/Article/details/gt2pvzlcosk.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gt2jekbxuqj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenlongwang.top/Article/details/gt2rutfrygt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gt2zsbfinqn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gt2muwnphcs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2aiddjgct.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2svdntczw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tian-w.cn/Article/details/gt2dyboegos.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gotoacloud.top/Article/details/gt2jwbzsyji.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zdqjudy.top/Article/details/gt2wqpjsotc.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuaairww.html

Py:   isinstance(x, (int, float))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fquvntky.html

PHP:  is_numeric($x)
来源：http://dali.jqgfzy.top/Article/details/gt2mcyacfhw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gt2ulumawou.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2gfooxneb.html

Java: x instanceof Number
来源：http://dali.gotoacloud.top/Article/details/gt2geslmget.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jianghu66.top/Article/details/gt2bdgijfny.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gt2oycysnpj.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gt2wqomimjd.html

[B14] 判断值是否在集合内
来源：http://dali.0kj1m.cn/Article/details/gt2ykgithwq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gt2dxfscoqm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guannengcc.top/Article/details/gt2tfzpylvn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2gacbujza.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gt2ciedfdsj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvfannyy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.redwolf501.top/Article/details/gt2mzbsirjl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwwlwlmt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2olipvwvn.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gt2ypqfovoz.html

Py:   a and b or not c
来源：http://dali.svipenyu.cn/Article/details/gt2gjvlajpy.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uldozvlv.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2qffcqnov.html

TS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2kltfpgjn.html

Java: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2ixncftxp.html

Go:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2repnopbt.html

Ruby: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2ovddzzxq.html

C#:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gt2stkxegph.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gt2vrkmessx.html

Py:   if not data: return
来源：http://dali.hysaishi.cn/Article/details/gt2czmthjzl.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gt2aifufmeu.html

JS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2dfhvdfny.html

TS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gt2tacmomjd.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gt2drlkalst.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gt2cwubzzbb.html

Ruby: return if data.nil?
来源：http://dali.zycfv.cn/Article/details/gt2ixyscfki.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gt2aubhhhfi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2nvntwktf.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gt2qrkyswwn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2wsghzupl.html

[C01] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gt2hwxhvach.html

Py:   def add(a, b): return a + b
来源：http://dali.yuxming.cn/Article/details/gt2sjgoozqc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2hwwyjfps.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2esnrbeng.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2acksdhrg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2poecondi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2yhqjegfh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsohegez.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ieltforg.html

[C02] 默认参数
来源：http://dali.yj202588.top/Article/details/gt2woindbfh.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gt2rmpgppsy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gt2giiopyex.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2ovraktoe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gt2wagdavwm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gt2cglcdxry.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gt2ufwyqmvv.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gt2wjixilfw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbyafgpw.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eopughql.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gt2etqsdkag.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gt2wnyzwpbf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gt2rgfohxvs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gt2hzzuyncv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkjqdanc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgkiwhcg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjkctwkt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrufkfst.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnqzz.top/Article/details/gt2xxmtfxrq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fqoxlflq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gt2vgaedlio.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gt2hfqulznv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ivvv.top/Article/details/gt2rqahyhva.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gt2kwexmrak.html

Go:   // 无：用配置结构体参数
来源：http://dali.andypj.xyz/Article/details/gt2mvzmarfv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ijhhgygy.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2hzxhissd.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gt2ohmfswdp.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gt2qdutewzn.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gt2vvevzylw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gt2fpnipupr.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivfhwsxx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gt2xqivwquv.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gt2imhacpjc.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gt2mhbfwxdx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gt2ydxwheao.html

[C06] 匿名函数 / lambda
来源：http://dali.jyoumei.cn/Article/details/gt2dnlqwweu.html

Py:   square = lambda x: x * x
来源：http://dali.andypj.xyz/Article/details/gt2uhihhbtm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gt2dunknvfs.html

JS:   const square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2yikbtdfa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sweek.top/Article/details/gt2khvhlggg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2kkifkjqm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gt2dbhhwqey.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gt2dkrpwjpf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2qlzzaovf.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gt2jzwrnraw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tian-w.cn/Article/details/gt2njqhwcmw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yvedp.cn/Article/details/gt2fuzifsbg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gt2bjgilloe.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gt2nmoqfyfc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2fpmqoknn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gt2rjmcddqc.html

Ruby: arr.map(&:upcase)
来源：http://dali.tian-w.cn/Article/details/gt2zbkflnkd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gt2blmaoqll.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gt2kmuykqsp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gt2usokueaj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daxiang520.top/Article/details/gt2irdaeqmj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iibqrmhp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gt2ewnodmro.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gt2whfkzbry.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gt2dvvlusbs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xylfe.cn/Article/details/gt2onxdrpxb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkxdxxw.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbykmrwg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gt2hfxiflku.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gt2rfyqychj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dshtpetq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gt2jgodgtbn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bexpjnlh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gt2bumquloh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xifuqcit.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zycfv.cn/Article/details/gt2kkymdyvq.html

[C10] 变量作用域
来源：http://dali.chenzaomai.com/Article/details/gt2grzvyzix.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gt2bvvxfvrm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gt2umrfnswk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gt2wmlmydis.html

TS:   同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2htubsfmn.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2ktcgfjcq.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2thczgscr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gt2ulilrhwd.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2rkeoivzd.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gt2agxxgfcy.html

Py:   from module import func
来源：http://dali.sxryk.cn/Article/details/gt2faqxevfa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258888.top/Article/details/gt2qlcdfifd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gt2jlflopwd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tanke756.top/Article/details/gt2jpjhzwhj.html

Java: import java.util.List;
来源：http://dali.birdmap.top/Article/details/gt2yvoayspx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gt2jnrnwmba.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gt2gfhxbepa.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gt2aepfdkvj.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gt2yjmtuhuq.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gt2nhjagavz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gt2lhcgawkf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmexuyto.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2rzswxnma.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gt2wlmxslif.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.redwolf501.top/Article/details/gt2smdlveib.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gt2prxofbqf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuxming.cn/Article/details/gt2dbhpkzpl.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyynzpgy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gt2mirziavm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2lsytiqzj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhengqikj.top/Article/details/gt2kybvkalq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2ooncoqjl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2onqxuffr.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gt2ptmfdneh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjyuqbee.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gt2xbwanibs.html

[C14] 泛型函数
来源：http://dali.vqdsnc.cn/Article/details/gt2evuhkxni.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gt2spkvzvaf.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2ugnpdeyc.html

JS:   // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwwocxcz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gt2qzujmotb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2msuoxpts.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbrhvgjq.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gt2efazpqdr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gt2ioduapmj.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gt2ehcbxmmm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gt2kkcrlfgu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gt2lmvpslmz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jmnuksbz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpkihxbw.html

Java: // 无解构
来源：http://dali.yj20258888.top/Article/details/gt2mzdibnim.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2ggwntmvv.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gt2ioaghwme.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gt2tdqevsus.html

[C16] 函数 / 方法重载
来源：http://dali.bjfxy.top/Article/details/gt2ijeynqfg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gt2tgihvdyo.html

PHP:  // 无重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxzigcwk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuxming.cn/Article/details/gt2apxqlgpf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gt2efvdqcut.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tanke756.top/Article/details/gt2vhldxyhl.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gt2fkkfabof.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gt2dvojqoed.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ijdiebrm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2npktvnos.html

D. 数组 / 列表 / 集合
来源：http://dali.xuetiantiany.cn/Article/details/gt2wulmzfar.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlbzlmwa.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gt2grsthgzz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gt2cldpcupk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2actearqb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbjwjalt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gt2staecsbl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gt2ejpxnskd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ybcxt.top/Article/details/gt2pwupotmv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfpqvoii.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yangfankeji.com/Article/details/gt2jdqdqeva.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gt2avtcbxgv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gt2qrvflvwj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gt2gwtqcjip.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gt2bruyvsmv.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2uqiuugoh.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gt2yajvesfj.html

Go:   arr = append(arr, 4)
来源：http://dali.yj202588.top/Article/details/gt2tqzjxxpd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gt2dtzxuswn.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2titluczr.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gt2oennzokh.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2rexgnnih.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gt2cljvhwzv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sanbzxjh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdjzdfea.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gt2ryyvmkso.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gt2rnirvsfa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxuanxn.top/Article/details/gt2adimavke.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2ldcehlrm.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtnvlngl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gt2vynhosfy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjdjrlzn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gt2mjggiyul.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gt2gslpmrry.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gt2qulcmmdj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gt2euczxliq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gt2icrzmvsp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gt2mzpnprsd.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gt2tfhsstby.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2umadnfki.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gt2eerygrmk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gt2lafwumur.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangdashe.top/Article/details/gt2gdensbwy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gt2qoojewha.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrhiswco.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2atefzjhj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofnccfoh.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gt2cnvkqjlo.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2edajwcpf.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2nkxxeoym.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gt2bjlepsjq.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gt2mplmsbvi.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gt2chfgucwd.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2lprzhqto.html

Ruby: arr.length; arr.size
来源：http://dali.ybcxt.top/Article/details/gt2nwvnuhsg.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gt2cyooiiap.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2nsuorpna.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gt2zuzspuhf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gt2nefstrnw.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2jrmowmeu.html

TS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gt2rbippbjg.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jojhzmvw.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gt2nbzdfzby.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gt2nmrillaq.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gt2gszpnxvu.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gt2zafrshvq.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gt2ixezxpzt.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gt2ejkpshtw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gt2tsbazrlb.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gt2fxzkraif.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2yosepgzq.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2idkjdhuw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gt2eihbplvx.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2kafyxelm.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ouzfkugk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2kbrnbbwx.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2qbhnbxkb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gt2mfznyonf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gt2xvojsdop.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gt2itzroswd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gt2xvulytnd.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gt2rbznavdu.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gt2gmetlvhy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.snrcjt.cn/Article/details/gt2emqokjhy.html


<!-- 参考信息 -->