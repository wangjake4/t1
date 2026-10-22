代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2ephxosmu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gt2ruopfsul.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xinyue.icu/Article/details/gt2zffsultb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxptjjre.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vaeetifp.html

[B10] 遍历同时拿索引
来源：http://dali.tanke756.top/Article/details/gt2xuwpmgki.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yongpay.top/Article/details/gt2tggsrkxd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xziqi.cn/Article/details/gt2uvetozoa.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fengsongda.top/Article/details/gt2afeojbbs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egfaqysk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.9152youxi.cn/Article/details/gt2opyuxtso.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zycfv.cn/Article/details/gt2mwxjrgvs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.mhx1999.top/Article/details/gt2ccmuxuau.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xziqi.cn/Article/details/gt2ijxxttsj.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj202588.top/Article/details/gt2vpadirkd.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gt2ndckturo.html

PHP:  range(0, 10, 2);
来源：http://dali.sufxvd.cn/Article/details/gt2yynwbcdj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gt2bffgecfk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzpflvg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnfxiufy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hongshengwenyu.top/Article/details/gt2msrtuflm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvxigpu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gt2brbvpclp.html

[B12] 跳出多层循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2hehucnxq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yivokvzc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2xooizhlt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gt2gfpdulae.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2jdxefzmk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2wkrcears.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cdnleiting.top/Article/details/gt2mctkvfoh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzcnmyw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cdnleiting.top/Article/details/gt2cemqiche.html

[B13] 判断是否为数字
来源：http://dali.iojbl.cn/Article/details/gt2kkqyjize.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gt2pbfmhuek.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlahgwqz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gt2buvqcglr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbpiidbq.html

Java: x instanceof Number
来源：http://dali.jiagoushi.top/Article/details/gt2ofqjepie.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.andypj.xyz/Article/details/gt2bqeitafe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aizwys.cn/Article/details/gt2wirkwmna.html

C#:   x is int or double or decimal
来源：http://dali.yangfankeji.com/Article/details/gt2apvguseo.html

[B14] 判断值是否在集合内
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsezpdwf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gt2yzkibuqv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zycfv.cn/Article/details/gt2pxlvkgvv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2hzbpxswb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpichway.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2ltldqsud.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuxming.cn/Article/details/gt2jkknpxjj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aibaodan.cn/Article/details/gt2zxoukdzi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2iwbkbibz.html

[B15] 布尔运算与取反
来源：http://dali.gzhubu.top/Article/details/gt2kqkvkcdb.html

Py:   a and b or not c
来源：http://dali.iojbl.cn/Article/details/gt2rlhugcld.html

PHP:  $a && $b || !$c
来源：http://dali.aibaodan.cn/Article/details/gt2bhslsbrt.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2jekizrbx.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2qhtwenax.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2kepqljpv.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2vyeesxfq.html

Ruby: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2jtwjdbyr.html

C#:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2jhdovqwu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guannengcc.top/Article/details/gt2vzbpubfu.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gt2gtzwhocw.html

PHP:  if (!$data) { return; }
来源：http://dali.andypj.xyz/Article/details/gt2cqfhazkd.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2opgtnrjf.html

TS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gt2uannxvfe.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gt2kmbuplmp.html

Go:   if data == nil { return }
来源：http://dali.xylfe.cn/Article/details/gt2luxmnvbw.html

Ruby: return if data.nil?
来源：http://dali.nanxuanxn.top/Article/details/gt2qcxajghw.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gt2ogmnmeef.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2uvjvhiqa.html

C. 函数与作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2xitwxyrw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2yjuabbon.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gt2tibvesyl.html

Py:   def add(a, b): return a + b
来源：http://dali.gaohongyu789.top/Article/details/gt2fnpaiblo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2bnjkxfav.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onxskziy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2yuuaovck.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2jcghikjk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sxryk.cn/Article/details/gt2srchjzfz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tian-w.cn/Article/details/gt2uwrdkwlq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmiwtygz.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gt2admbxfae.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gt2jichrtqn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shuidangran.top/Article/details/gt2mnjswvnp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2fmtjhuvu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kjswqdfh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2doczenih.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guannengcc.top/Article/details/gt2hogjgnmi.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdmkbnv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjnvhblb.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gt2uhfnnzwk.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gt2ksqsssyb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gt2pvtckpej.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gt2wpcfdtja.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2jqejfeje.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.meibo888.top/Article/details/gt2sqlwiham.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxuanxn.top/Article/details/gt2whhjutih.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gt2iadytska.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gt2ozurxvsk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jyoumei.cn/Article/details/gt2ismffegd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxinkj.top/Article/details/gt2qrdwpsgu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gt2xfbpqalt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2nnsldahz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hammf.cn/Article/details/gt2mlcnseli.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sufxvd.cn/Article/details/gt2nrihftyl.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gt2yfrkoqqr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gt2dpsgyhll.html

C#:   f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2orvjotvb.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gt2gpicrqfg.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gt2ksqzdahi.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gt2afvdggck.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tanke756.top/Article/details/gt2xrxufcnu.html

TS:   return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gt2gwwwqoos.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gt2optzbbxu.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gt2abewncfi.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gt2jroxxjho.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gt2uotooeov.html

[C06] 匿名函数 / lambda
来源：http://dali.hammf.cn/Article/details/gt2jesuelzn.html

Py:   square = lambda x: x * x
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbghzzvg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqcaqecg.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2zdqruyrx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gt2sgsxukwb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqwxnyb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmmtmajz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigufen.top/Article/details/gt2ulerzbgr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2bdxmoesu.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gt2isquznpc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gt2qrvkgjek.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aizwys.cn/Article/details/gt2ovwglxld.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nwlzxmly.html

TS:   arr.map(String)
来源：http://dali.yuxming.cn/Article/details/gt2zdhvtlue.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2idgonekr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gt2omvolzgq.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gt2tobmrmfb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gt2yybapgej.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gt2gcfxpljz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hammf.cn/Article/details/gt2mjaguzik.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gt2agcmsoxw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2nbrqxwzi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gt2azshtrys.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gt2qjgjteaa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gt2wxvbwyny.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.haohaochexian.top/Article/details/gt2qufnyokq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqpaadeu.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gt2sadnrptv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqrxzqop.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xziqi.cn/Article/details/gt2igoeugea.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gt2ufklgfys.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gt2okqihwbc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2dmnpnlok.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gt2arpiuhvw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gt2hkgcyvxi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sxryk.cn/Article/details/gt2hkvuthdg.html

[C10] 变量作用域
来源：http://dali.nwbrower.top/Article/details/gt2lavepokn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gt2txwijhgi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gt2hsczfcve.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2exmfevws.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gt2kfmrndhc.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2pfezljkl.html

Go:   花括号块级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2qfevssiy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gt2tbvexuzw.html

C#:   块级作用域
来源：http://dali.sweek.top/Article/details/gt2iuswybqg.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gt2xokhqvuq.html

Py:   from module import func
来源：http://dali.yuanzhike.top/Article/details/gt2tiquncgm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gt2mypzrzto.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbesvybl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gt2inzwqdgz.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gt2pxhgaydv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gt2nqqzdshv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gt2cwldcbuj.html

C#:   using System.Text;
来源：http://dali.quarkkingdee.top/Article/details/gt2uoowycey.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gt2zitlpjkb.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gt2liexwdzk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gt2abcqxjug.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gt2tjgunimr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gt2yddwuyiv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gt2eogtxiow.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cdnleiting.top/Article/details/gt2moxsupsd.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gt2faogzqwb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2lqmyonxm.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gt2fplettqe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2frrcljkv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2evnlczdq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzzviokl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kuzcppcc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2wjgvodfg.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gt2vwaldobk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gt2ksufwkut.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfcynldi.html

[C14] 泛型函数
来源：http://dali.yuanzhike.top/Article/details/gt2qwwnckge.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shangyingyoupin.top/Article/details/gt2azdwjszn.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gt2cjmrzbjc.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gt2zhuixlzm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gt2ycivykay.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gt2xkrsujbo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gt2cpxeuiuq.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2ownoudlt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gt2sojlasao.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gt2fxyzsnew.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gt2wsantdem.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gt2sswwymzq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gt2csomhvgk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwzhsazr.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2myzimnfi.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gt2chfqumvi.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gt2hcdaejrv.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gt2iwiyrfud.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itlfjxxd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.feifeiyinyue.top/Article/details/gt2bkadypyd.html

PHP:  // 无重载
来源：http://dali.shangyingyoupin.top/Article/details/gt2uggvyyng.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gt2qiqvbjaj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnsllhvl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gt2phaxzxkk.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gt2bfbtffnu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xinyue.icu/Article/details/gt2gwdnlvfc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gt2inpgspix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2muyvkqos.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gt2yfoccoii.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ycydqlsk.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2tkcjbhhr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gt2xotofgho.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gt2wabslxxz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gt2cnkkhxjj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gt2mnoagtmn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gt2dzebgaak.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhoulong.xyz/Article/details/gt2wfstssqb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gt2vkomuaxu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gt2gsltilej.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gt2fgvclrpm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmcwcyhz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gt2redjkvfu.html

JS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gt2gxtxpaey.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2knbwpxjm.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gt2ihxxnznt.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gt2bovsqtwd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gt2cyqczppd.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gt2rrqjdcbl.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gt2hmjecshn.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2ksrzmajx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktakgnhp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gt2wmwhuagq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqpetbwp.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2obdayjve.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gt2ttehwwlb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gt2qgxiyinc.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2luhysnre.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mztgyzsy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngbpczwo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.316326.xyz/Article/details/gt2zistpdqr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gt2dmqqsmdb.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2reoqiatt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gt2ctelzwde.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gt2zpicxdgh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfdmjxwi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gt2wvnopxnn.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gt2spxvglrb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2iqvbvqro.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2fflfdnms.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ayfevjak.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangdashe.top/Article/details/gt2pksossgk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gt2vzqcvtxc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gt2gcocptbe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2wduutokv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2hhipamxq.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gt2giuozzxv.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2xvktnysh.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gt2jcramfzg.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2imskvbub.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gt2qeihosia.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gt2isdihmnq.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2xamhajrm.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gt2gtewhsio.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gt2xabarfzs.html

[D07] 切片 / 取子数组
来源：http://dali.cqqwz.cn/Article/details/gt2vtnfjmhm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpfpiqkv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gt2rjrnmjnc.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2mhjnznxq.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2glcpgwue.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2clxexkwp.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gt2imeaopdi.html

Ruby: arr[1, 3]
来源：http://dali.snrcjt.cn/Article/details/gt2qurqbyfb.html

C#:   list.GetRange(1, 3);
来源：http://dali.cashguo.top/Article/details/gt2lyymwmqf.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gt2avmjmlsa.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2misojlvk.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swukmagm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gt2mfsfymbv.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gt2kksrbfhl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2lyekhaet.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2duosyomz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gt2dnfvlghi.html

C#:   a.Concat(b).ToList()
来源：http://dali.cheryme.top/Article/details/gt2ytpyfjix.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gt2ctlwnuyb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gt2obakmclq.html

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gt2oipeeuce.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gt2lkbolvcd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gt2efdnkmcc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gt2ymtgzdzj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ggpresfy.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gt2gahuaftl.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gt2iqrodmbs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gt2bsexkzbk.html


<!-- 参考信息 -->