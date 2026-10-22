代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2rknjalbr.html

[B10] 遍历同时拿索引
来源：http://dali.dianchejie.cn/Article/details/gt2fqatvybp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gt2syooyvrl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykzidwuv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqrojgzm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gt2hulucbnq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jiagoushi.top/Article/details/gt2psfzftnv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yangfankeji.com/Article/details/gt2wacnjghh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuscruqw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgfzy.top/Article/details/gt2tbogaotm.html

[B11] 生成数字序列 / 区间
来源：http://dali.xinyue.icu/Article/details/gt2nlzdyqnh.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfhiuvby.html

PHP:  range(0, 10, 2);
来源：http://dali.yongpay.top/Article/details/gt2zxdlmzww.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gt2cjmwyetv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gt2qxcujech.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2ppwjyiry.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tianlin.xyz/Article/details/gt2bbciwmzz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jyoumei.cn/Article/details/gt2wvpqkvde.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tianlin.xyz/Article/details/gt2nqcvqyeh.html

[B12] 跳出多层循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2nyrvkfkx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gt2kdczarmj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuanzx.com/Article/details/gt2rpcdnxvn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gt2hfewbfal.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gt2dbxyxjto.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqtniviq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dashuyun.cn/Article/details/gt2rvtrnihr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hammf.cn/Article/details/gt2unumrdqj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gt2aomhpdje.html

[B13] 判断是否为数字
来源：http://dali.sxryk.cn/Article/details/gt2uaygwfsa.html

Py:   isinstance(x, (int, float))
来源：http://dali.316326.xyz/Article/details/gt2tkbvtqls.html

PHP:  is_numeric($x)
来源：http://dali.sufxvd.cn/Article/details/gt2srlqnsbu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jakoghud.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2ogltjoca.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gt2zrbdwerb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gt2iwcfjgvm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gt2oyhaqocc.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gt2xxwsbvas.html

[B14] 判断值是否在集合内
来源：http://dali.ppjwa.cn/Article/details/gt2apegpitw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gt2wehwmnzu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gt2pvznspff.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztcohzvn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2mxrzpnup.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2vyxqdksk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gt2jfryyoci.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gt2poledakf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2cjoeyamd.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gt2mgqgzplt.html

Py:   a and b or not c
来源：http://dali.aizwys.cn/Article/details/gt2nhqedbsw.html

PHP:  $a && $b || !$c
来源：http://dali.dashuyun.cn/Article/details/gt2fsxwyivf.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2lxtaahaz.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lelduelz.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2nsbbfqqw.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2brwfwzdn.html

Ruby: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2ogxkpiyg.html

C#:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2meswxqfc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cqqwz.cn/Article/details/gt2jcbdefqz.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gt2ggonksup.html

PHP:  if (!$data) { return; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmnyxxeo.html

JS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2tmtxrshk.html

TS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrwtuwbf.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gt2qlqljhqm.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvjvnazx.html

Ruby: return if data.nil?
来源：http://dali.mhx1999.top/Article/details/gt2otsbczwm.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gt2xmbmpnsw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zkizopkz.html

C. 函数与作用域
来源：http://dali.yongpay.top/Article/details/gt2psnjauot.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2vllriwmj.html

[C01] 定义函数
来源：http://dali.hammf.cn/Article/details/gt2ulpeqcyz.html

Py:   def add(a, b): return a + b
来源：http://dali.tanke756.top/Article/details/gt2mmetouli.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gt2khnenrzh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2wenkvnkq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2pguoozuv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2ytlzivgx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ydzc1.top/Article/details/gt2socjqoug.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gt2zyomiplc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2szksamsn.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gt2gsljqzbe.html

Py:   def greet(name="World"): return name
来源：http://dali.yvedp.cn/Article/details/gt2bytpksub.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xinyue.icu/Article/details/gt2abqfzmmr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2mlxrrame.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gt2tgfyuevf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2zmlgczak.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gt2rrfgsvuu.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypfwounh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuanzx.com/Article/details/gt2edcepmeg.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gt2okhpgxxw.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpefzkav.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuxming.cn/Article/details/gt2hozyruru.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gt2otxyprjk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gt2ulvvcztd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvlegsrw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gt2inrhpiim.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gt2hyjwudur.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gt2mzczzjte.html

[C04] 命名参数 / 关键字参数
来源：http://dali.316326.xyz/Article/details/gt2bstduhuu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gt2vdjzwlqa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gt2kptpusqv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gt2uripmwbk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxinkj.top/Article/details/gt2sudiheak.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aizwys.cn/Article/details/gt2qxydugsu.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangdashe.top/Article/details/gt2njjltkhn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2ugwukriq.html

C#:   f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gt2egiiwcwc.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gt2pkmdhwhs.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2rbfrfukx.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gt2ivnuhlbr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gt2xxdnzcsh.html

TS:   return { a, b };
来源：http://dali.havefunace.top/Article/details/gt2iocgtrzc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gt2mmdqipwl.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gt2jzixnnmm.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gt2szqwsvqp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gt2qcwrnykn.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gt2uanspryd.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gt2gmnovqfo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vchcrvsv.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2joroxuva.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2dplwfcbl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.svipenyu.cn/Article/details/gt2snixykvl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gt2amreglax.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gt2gzshykar.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2upgvusvr.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gt2bxesronn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gt2xuhcwbvf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gt2clnfzdzr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nwbrower.top/Article/details/gt2shvcntem.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzfcgbzm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.redwolf501.top/Article/details/gt2lxjmcwgu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.0kj1m.cn/Article/details/gt2lepwztwa.html

Ruby: arr.map(&:upcase)
来源：http://dali.jyoumei.cn/Article/details/gt2boxbipny.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsdjyubp.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gt2wbxsldpf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gt2kxeowqgk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tiokpuui.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gt2hvpoalab.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2thecumbs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gt2lpygqudv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2illcklvw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ffnaiaar.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2xvfekbhi.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gt2grrmjfxa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gt2giteiqjg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2xwixqafv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gt2rsucxgpo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gt2wujqlcfh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gt2kcwslaxo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxinkj.top/Article/details/gt2bgnwsooo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gt2jldvcyym.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjfovcgt.html

[C10] 变量作用域
来源：http://dali.yueranfly.top/Article/details/gt2ybdiextl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sazjdcmk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gt2jqtjubfu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2erkbspbt.html

TS:   同 JS
来源：http://dali.bjfxy.top/Article/details/gt2telinjxy.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gt2wjuhcgvh.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gt2dpqyafua.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gt2obaezwti.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gt2hbunyvxa.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gt2bayqywhw.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gt2ncjahszx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gt2cvnbeykw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hammf.cn/Article/details/gt2rmcoqyac.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.quarkkingdee.top/Article/details/gt2yhzykwdn.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gt2jksqhfth.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aizwys.cn/Article/details/gt2ezrszykb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gt2jcdoptts.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gt2jqqjbgwd.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gt2xufepssc.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwntrzah.html

PHP:  (function () { echo "run"; })();
来源：http://dali.meibo888.top/Article/details/gt2uhipntwh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gt2rumvmsrg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gt2ibixjeyv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gt2qefxrkzf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dgyfdpal.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigufen.top/Article/details/gt2ifbpomnu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2fpxfftpm.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anjthdpm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ydzc1.top/Article/details/gt2ymxrlnvr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gt2esyijavq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jthlzynn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2qutdckvi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2fnwlmffs.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gt2qlkqggct.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gt2gkykgrcx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.bjfxy.top/Article/details/gt2nvcnjqeu.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gt2sdpungjf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gt2ntdqlsox.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2ypuchsvv.html

JS:   // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2bauxmjln.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gt2lwegfqhh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gt2neinxwgo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gt2btgbkbjg.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gt2hjrlepgq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.svipenyu.cn/Article/details/gt2zrdtqzia.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gt2vsvydrdr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gt2zyveqmgk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gt2dxbuxqsj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gt2awywapes.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gt2mgwdyvhp.html

Java: // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmoetzwx.html

Go:   // 无解构
来源：http://dali.nwbrower.top/Article/details/gt2ybynjwuo.html

Ruby: a, b = pair
来源：http://dali.guowangkeji.top/Article/details/gt2svlihtuq.html

C#:   var (a, b) = pair;
来源：http://dali.shuidangran.top/Article/details/gt2mihqywqq.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gt2acdublyu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gt2vojsclec.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gt2xxvfcbpp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gt2ngaaxmrc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gt2abdyohxg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gt2ndwqjybe.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gt2xfbdrbbp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gt2ormgkkwq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gt2gobdatiq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztyevyzr.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gt2sxjbimey.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2yxikxwxe.html

[D01] 创建数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gt2fzxfomgq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cshultdw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guannengcc.top/Article/details/gt2femifwyi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jiagoushi.top/Article/details/gt2rtugklil.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gt2bkiaerxn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gt2hfkmllcn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenlongwang.top/Article/details/gt2lxcykqxa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2rarjyfkg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gt2aczykxlj.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gt2edipbavk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gt2sdhtoxxm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2yieiijpi.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gt2qrrqrnpq.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gt2ywzmjrhb.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ynprwddd.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gt2mpelknno.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gt2mbbfrppz.html

C#:   list.Add(4);
来源：http://dali.pycfn.com/Article/details/gt2frtakonw.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gt2oarjaihv.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gt2yxjtnsli.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.svipenyu.cn/Article/details/gt2auqgmasr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gt2juqfqeup.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2cdyqjccb.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gt2toaqsogo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gt2ploovyac.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gt2ldwintgw.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2rdnlkwnm.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovixzrtl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gt2qlsvnynh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2mhtwkmzj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gt2znvwnvzk.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gt2wfixybia.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gt2uzylqnbs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gt2pdxwxnmv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgjwlbni.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gt2dmdijhtj.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gt2apbjumxr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahkgdxkg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gt2ratjohyk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gt2uvlzpiay.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggzcfdfw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gt2aiyqnjej.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gt2oxqnrfbs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2axcjgyui.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gt2jwydjchq.html

[D06] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gt2pubctgtg.html

Py:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2imsrgijy.html

PHP:  count($arr);
来源：http://dali.yvedp.cn/Article/details/gt2qrhzswco.html

JS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gt2tyzlpltx.html

TS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gt2padsubzb.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gt2vxtvvcvw.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gt2xskmlslb.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gt2uzkstmqo.html

C#:   list.Count;
来源：http://dali.dianchejie.cn/Article/details/gt2lcpyxwyo.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gt2qzodwkae.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gt2fmaecyhv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2cmzrverv.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2mbqywbdn.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gt2oifmiayc.html

Java: list.subList(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2vmgiwxzs.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gt2zecqcjqa.html

Ruby: arr[1, 3]
来源：http://dali.yongpay.top/Article/details/gt2dlqbfuqt.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2pdihsmlu.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gt2tzxburuo.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gt2pbbyxwtx.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gt2hdbxyojt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gt2vkucrpgf.html

TS:   [...a, ...b];
来源：http://dali.zhengqikj.top/Article/details/gt2tuqidltl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2wxpdtlhw.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gt2nycxscil.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gt2iznkwijy.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2lpecfmji.html

[D09] 排序（升序）
来源：http://dali.jiagoushi.top/Article/details/gt2mywvhddx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gt2wywsyxrd.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2qfoxniuy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fzhhl.top/Article/details/gt2hynibxzy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gt2nytxqxtc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gt2erubhoos.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyhgnsox.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjkhxyb.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgvywssm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gt2wcltofhh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gt2czanruwo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gt2foeazeuc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2amjiecqm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gt2ezcjfckk.html


<!-- 参考信息 -->