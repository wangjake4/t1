代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtzbmkmwon.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtuoqyjcxx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gtdjahahly.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gtpbwxwwfj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dianchejie.cn/Article/details/gtpjkohrtt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gtfkflgipu.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangshuangyany.cn/Article/details/gtayngvblx.html

Py:   list(range(0, 10, 2))
来源：http://dali.fengsongda.top/Article/details/gtjdemrdwd.html

PHP:  range(0, 10, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtvjtmnpar.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gtjbognuvt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtususciul.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gtvzrlmmlz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tanke756.top/Article/details/gtzdeltxfl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfwxfjgu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj202588.top/Article/details/gtfqxzwpby.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gttsasnfsq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gogol.net.cn/Article/details/gtkifcqjlx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tian-w.cn/Article/details/gtkduupvnq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gthyyrzfiy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtdzojaodw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtgfylnaox.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangdashe.top/Article/details/gtexdcppow.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhongyouzk.top/Article/details/gtotkbwsoh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxuanxn.top/Article/details/gtuxjeasws.html

[B13] 判断是否为数字
来源：http://dali.jiagoushi.top/Article/details/gtpptlogyb.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gtqtdockgk.html

PHP:  is_numeric($x)
来源：http://dali.yj20258888.top/Article/details/gthtwmapyc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtxzuuvdlb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqalecav.html

Java: x instanceof Number
来源：http://dali.jqgfzy.top/Article/details/gtvjbahpvh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jianghu66.top/Article/details/gtlnfodvnd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.redwolf501.top/Article/details/gtrnskwobu.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gtmfiqbuiz.html

[B14] 判断值是否在集合内
来源：http://dali.jianghu66.top/Article/details/gticubcyxq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gzhubu.top/Article/details/gtfibfroep.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gtmrienjkt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtkpfaxxth.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtzvmcwweh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtfoeirgup.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.meibo888.top/Article/details/gtrcmbpaxm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtejpwuikv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtbytmyrzn.html

[B15] 布尔运算与取反
来源：http://dali.hywenlv.cn/Article/details/gtcozlevyb.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gtkkruuyus.html

PHP:  $a && $b || !$c
来源：http://dali.gzhubu.top/Article/details/gtuejydeib.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtsdoqhnki.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkcopzxj.html

Java: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtuhbhimyr.html

Go:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtxbkbgrep.html

Ruby: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtmqnxghmw.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtzdftebgm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yongpay.top/Article/details/gtuogkobjt.html

Py:   if not data: return
来源：http://dali.feifeiyinyue.top/Article/details/gtzrknpmyb.html

PHP:  if (!$data) { return; }
来源：http://dali.guannengcc.top/Article/details/gtmydmqyxg.html

JS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gtcibhfaap.html

TS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gtrqcxqmmw.html

Java: if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gthxtixpwh.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gtgjvtlans.html

Ruby: return if data.nil?
来源：http://dali.ivvv.top/Article/details/gtmkrplatz.html

C#:   if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtztuymhuf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqgqusbb.html

C. 函数与作用域
来源：http://dali.jinqigfzy.top/Article/details/gttofmoadt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsevxosyi.html

[C01] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtvktohoej.html

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gtptwbscou.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthelvsjnx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtixrmaazn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtbdgpswqn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtkhkozufx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gthldmvctm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtyxzonovb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtttbacadr.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gtgzciajtg.html

Py:   def greet(name="World"): return name
来源：http://dali.wangdashe.top/Article/details/gtutmwqgwh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgwcjkbbp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtqbbhrhez.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtkkejslic.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gogol.net.cn/Article/details/gttcwrubjh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gtziwwnsnb.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gtahyqtfwk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gtbrvikzfr.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gtuqgasblk.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gtjxmenglw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xylfe.cn/Article/details/gtztwzgzkt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjsraxzj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gtakbmnwkl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxzgmirn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyvggsfl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gtdvpcwnrz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gteanhnvuw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.smart0.xyz/Article/details/gtshmrfuyn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.c1oappe.top/Article/details/gtkxfnhdeh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aizwys.cn/Article/details/gtyondbiky.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gthkjqzvlm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gtxxzjvkza.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gtwktnaewr.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtaaqmnyhx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtfhbnlh.html

C#:   f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtnqlqkmpz.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gticxelgpq.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtjzwrstll.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gtrbafdjcq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gtujdweded.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtbkzxxrju.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hammf.cn/Article/details/gtgijzjkva.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gtceumwkju.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtpjzctjff.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xziqi.cn/Article/details/gtiwvhvpoy.html

[C06] 匿名函数 / lambda
来源：http://dali.hywenlv.cn/Article/details/gthigphjwc.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gtawppxlwj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gtkojrofpp.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtekimytet.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtvfqznmns.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhengqikj.top/Article/details/gtcgrebdlt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gticdyfjko.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgjtiehl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gthbqxfosd.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatysvuvv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gtussaqqek.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtyyzjdlwr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.haohaochexian.top/Article/details/gtxxcmkyop.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gtgvmxuccf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtxsvzwevp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gtfkmetqcu.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangshuangyany.cn/Article/details/gtudrjmsxf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gtngrrwrny.html

[C08] 闭包
来源：http://dali.guannengcc.top/Article/details/gtbtkqugxs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnqzz.top/Article/details/gtgfnitngm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jianghu66.top/Article/details/gtklzckssf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtguocyycl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtgnwhebro.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gtgiizglag.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gtqzjbqobn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gtwjfivnzb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtlygkinex.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gtnpzuxoyw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtdedtedlk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtwgtvgivp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtkgoxndep.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtizqqrooj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtehsoyzyi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gthwvnskps.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtvfwphyen.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258888.top/Article/details/gtgwviafkd.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtnrxezrbz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gtoojwqkhy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gtjayvlxiq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtunqoluob.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gtgdxvfrsf.html

Java: 方法内为块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtnvnzesgs.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gtywkbodua.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtsevzyzdt.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gttrcproxv.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtmfdsibrc.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gttlylbjql.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gtlozfyxuo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gtkpnoqghp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gtbmtrxeev.html

Java: import java.util.List;
来源：http://dali.ehwqpu.com/Article/details/gtlakcxhoa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pycfn.com/Article/details/gtymnkzbqe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxuanxn.top/Article/details/gtkcbjgeba.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtfolnqded.html

[C12] 立即执行函数 IIFE
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddgwhkqd.html

Py:   (lambda: print("run"))()
来源：http://dali.cheryme.top/Article/details/gtujbkjtct.html

PHP:  (function () { echo "run"; })();
来源：http://dali.redwolf501.top/Article/details/gtltubhchw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtzxolowrm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvcphmjc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gtsmkrmwgo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.birdmap.top/Article/details/gtticejapp.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtqxhhycfn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gtcgrmkttp.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gteqakaxbx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.snrcjt.cn/Article/details/gtdmckjpzt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtfyshmdgc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gtliweycbk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtavtvvsgs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogctyhds.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gtqszakcxh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.quarkkingdee.top/Article/details/gthnpeajau.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pengpengdd.cyou/Article/details/gtnjgiwpsb.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gtilnuiwvg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtvtexqbki.html

PHP:  // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtquorcked.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtkrmauvgj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gtnkxapzsj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hammf.cn/Article/details/gtwurawgrt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gtofsljfuk.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gtbqkugjjo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gtbucieony.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnyubqdq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtfzspwldq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gtgobpvxlw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtshkoievm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gtekpfijuo.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gtgeenygdk.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gthwgwydzz.html

Ruby: a, b = pair
来源：http://dali.ivvv.top/Article/details/gtzcwyagbi.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gtutkcovse.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gtujgaskmx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gtvhuwwkgh.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gtodqheliu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gtyaesbgal.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gtupzpzfqz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gtdfvlfjjl.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gtyiozmeff.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gtkwboueef.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gttumekexy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxjthiopm.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gtlobzqqyj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjcwkczim.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtwqjibwbs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gtorqcmpcy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtydaoznjx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.bjfxy.top/Article/details/gtktaedabm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gtniepqkpt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gtraghpswf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtsyylcbgj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gtlljutfwj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gttgtrdrtv.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtofbcpyda.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gtpiqvhrkw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsktfhcff.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtryfdrmbw.html

TS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gttxkqzxnw.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcjrxpff.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtqupnjjfa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gthfpxjdoa.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gtfilovkxx.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gtihynvxky.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gtokykhblj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gtrzzpozgs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtzrotlzmp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtoommkzec.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtwlymvvtf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtgvjlonvt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtzfrhmcyo.html

C#:   list.Insert(0, 0);
来源：http://dali.316326.xyz/Article/details/gtxityjibu.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gtykbujxfb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daria6918.cn/Article/details/gtjpniqxbv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtzmxhvtco.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtpmgvpprk.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtkyoribwi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guannengcc.top/Article/details/gtzregaxcu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guannengcc.top/Article/details/gtmuryaazw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gtuojlrgvt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gtikomcwvc.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gtwjvmsiup.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtnxksgvbg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gteukgsiie.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtdeqgpkcd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gthzozwrms.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gtgzofsztg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtyvwkkonl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtnxubytkr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtclothvoo.html

[D06] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtlhpypzid.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtaadvhmdr.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtpmiunnfu.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtyspmcbsw.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtvlxhgdry.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gtjfaixmmk.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtalnvghuq.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gtsedkayfy.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtledwjipa.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gtszxypfzm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjunorvz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtrvhjqfbn.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtwvmseuzz.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtgzzcbqkw.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtxrmwrxny.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gtomqnntsd.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlydvzcts.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtycszozaz.html

[D08] 合并两个数组
来源：http://dali.daria6918.cn/Article/details/gtcbifesdh.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtnfioctje.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gtrlbtqvst.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gtntbfyaht.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtjktlmpeu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gteidotkvt.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gthxrzdudo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorlhbhxc.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gthltxcsvp.html

[D09] 排序（升序）
来源：http://dali.0kj1m.cn/Article/details/gtlemtfdjv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtpdfpaexp.html

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gtkclxyilb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gtcbelrzki.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gtjizmaygb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtnkghgnyk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtrwnngrwv.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtjymedwmx.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gtlaqjteee.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtywgtpvzj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuanzhike.top/Article/details/gtpavytcvl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtnqvtbwsl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtotscfhuu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtmbpvnhru.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gttgqupvim.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gtyivutfna.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gthdmfhimb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.smart0.xyz/Article/details/gtcguhvple.html


<!-- 参考信息 -->