代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gt2lqwflrjw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gt2elkxwici.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jiagoushi.top/Article/details/gt2xskknlmv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gt2peiowcmj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nanxinkj.top/Article/details/gt2cgvrofze.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gt2enuongdt.html

[B11] 生成数字序列 / 区间
来源：http://dali.ydzc1.top/Article/details/gt2uaguwlzy.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gt2cmygqooz.html

PHP:  range(0, 10, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnxhejgt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gt2vzitrpgh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gt2tkbyheeu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2pdsbulvy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gt2ufdotjmp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.316326.xyz/Article/details/gt2uzbdaxun.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gt2hljujkhj.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arwhtpxk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zycfv.cn/Article/details/gt2eqtidnfh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xylfe.cn/Article/details/gt2dvrssrhg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gt2xmthgjig.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2sbunhwcq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2wfmgsgjx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hysaishi.cn/Article/details/gt2xkucpwuq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ivvv.top/Article/details/gt2kzzgjmwk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aizwys.cn/Article/details/gt2penyoqvi.html

[B13] 判断是否为数字
来源：http://dali.zhoulong.xyz/Article/details/gt2dywsbwcs.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygkifkgp.html

PHP:  is_numeric($x)
来源：http://dali.yvedp.cn/Article/details/gt2qpvntvgu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gt2eqsurkgc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gt2emcipvsm.html

Java: x instanceof Number
来源：http://dali.dianchejie.cn/Article/details/gt2ocncbjcj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gt2btcdqjyd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsopzjdy.html

C#:   x is int or double or decimal
来源：http://dali.daxiang520.top/Article/details/gt2nvenqmdx.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258.top/Article/details/gt2bxobjpbr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jianghu66.top/Article/details/gt2ufzkzffj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daria6918.cn/Article/details/gt2vpavwiig.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gt2piknjygz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2simxstwu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2dkvaqxbe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtzwauru.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2xrrnlydv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmimlpdw.html

[B15] 布尔运算与取反
来源：http://dali.gzhubu.top/Article/details/gt2bolobvqa.html

Py:   a and b or not c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xalgnuro.html

PHP:  $a && $b || !$c
来源：http://dali.yueranfly.top/Article/details/gt2byvyxchl.html

JS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2czkxzwgl.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apguayrp.html

Java: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojpdbohy.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2mghhmydd.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2irwfzowh.html

C#:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2prfjoaee.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2igizsaml.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gt2vjsfejtx.html

PHP:  if (!$data) { return; }
来源：http://dali.zhoulong.xyz/Article/details/gt2epilnwyv.html

JS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehppxhtv.html

TS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gt2drkwmwxb.html

Java: if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gt2ddafbkhz.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gt2nqafctze.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gt2qjboiifn.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2epmzrtvf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vvuytxpp.html

C. 函数与作用域
来源：http://dali.hnqzz.top/Article/details/gt2qibiezgj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2dwywrpdm.html

[C01] 定义函数
来源：http://dali.yueranfly.top/Article/details/gt2aleglfmr.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gt2ifusopmp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fhmcauox.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2ikmosgxz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2bnirhbui.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2lrowncpj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkjjcjyd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2etaalyym.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2xkcpeeub.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gt2wnheefcj.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gt2towfahll.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gt2geufqmhc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2kevzxtkh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqiwejfw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jianghu66.top/Article/details/gt2cnamjnsv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gt2ypcjgetq.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgufenzy.top/Article/details/gt2ydlzfnjy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmqpetjb.html

[C03] 可变参数
来源：http://dali.nwbrower.top/Article/details/gt2pqcbuhaz.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gt2zorbeaba.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gt2ouxtjsaq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gt2hjrnetcf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gt2hrerwabe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gt2bpaljrpj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gt2yofmuxaz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gt2bhxtubmt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjpaonmm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gt2jgqylyom.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hywenlv.cn/Article/details/gt2fpsediyj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gt2vpwhaanh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gt2sdnptixo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gt2ihnfvebk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sysykeji.top/Article/details/gt2ukrckbto.html

Go:   // 无：用配置结构体参数
来源：http://dali.smart0.xyz/Article/details/gt2zqbkjnbv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2pzfgymkp.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2bklzwwxc.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gt2ubxarepz.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2hwauxvub.html

PHP:  return [$a, $b];
来源：http://dali.jinqigfzy.top/Article/details/gt2exzifgmb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gt2ehrnfocq.html

TS:   return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcjyghxk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.c1oappe.top/Article/details/gt2jaukptcz.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbbnhmww.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2plmzorha.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gt2bqkjwvht.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gt2rlsanokd.html

Py:   square = lambda x: x * x
来源：http://dali.gotoacloud.top/Article/details/gt2lrpwozal.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gt2sqpyfahp.html

JS:   const square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gt2vlrlxyat.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gt2fsgdjgeb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2yzyxdctz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cqqwz.cn/Article/details/gt2ecqtyuxf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gt2kkdktxlk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eowojqdc.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gt2dsljbxne.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gt2xjooocsu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2vepqnajm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gt2djlwuhwi.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvnliwkd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2wuzfkeue.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gt2knmvwxzm.html

Ruby: arr.map(&:upcase)
来源：http://dali.redwolf501.top/Article/details/gt2tbbrhtpl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwadflnw.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gt2aytbdpxy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gt2zkbrhbpp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gt2ofhvtzuz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gt2ofrgkpei.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2ewhgshvo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gt2yyunfnbx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gt2taswxwyg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gt2ilphdbpz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wjxqntyb.html

[C09] 递归
来源：http://dali.ydzc1.top/Article/details/gt2lhughesb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gt2ebvtkbki.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.smart0.xyz/Article/details/gt2dwjoqbck.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbwngmf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gt2bvydmggo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gt2focyvdco.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gt2rkwqygyr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gt2jikuqszi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbmaxpeq.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2ikidjlyt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gt2swtmyyho.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gt2gmbjfjtu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svwcofln.html

TS:   同 JS
来源：http://dali.fengsongda.top/Article/details/gt2zgssrmyf.html

Java: 方法内为块级作用域
来源：http://dali.xuanzx.com/Article/details/gt2rdxpybvt.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjhokqpc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gt2invoiiij.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2tkyylpgi.html

[C11] 模块导入与导出
来源：http://dali.yonumen.top/Article/details/gt2fwgmxvzk.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzgwoozv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gt2rcvkrexq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gt2lneirtbz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gt2pxwxewvr.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gt2dmjjdkse.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gt2ynozcmao.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwmojcxg.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gt2ozejcebp.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258888.top/Article/details/gt2pyxhfmbm.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gt2mdmmzcgn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.havefunace.top/Article/details/gt2wswtlnmf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gt2mhnznrwq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gt2xcsdrbsl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gt2yvivqavn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gt2gpjqtksv.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gt2yqafwzvp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2ojkyonek.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gt2plejdmbv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnfqkxye.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2zsgbgmbp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gt2jsynhinw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2oiuvrcxu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2deqvunoi.html

Go:   func add(a, b int) int
来源：http://dali.jinqigfzy.top/Article/details/gt2reyzxnlb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gt2xtfmbkjk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigfzy.top/Article/details/gt2jbwydwsn.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gt2zzzpjjcb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gt2zgpeuicd.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gt2ecparuum.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxrtdait.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gt2heikchnb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gt2tnftqgqk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntggoxeu.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2byhcralg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gt2pybwodvo.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gt2gxsinuiu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxuohiqd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqbgstsh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2krhrtxlu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yujiefyu.html

Java: // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gt2usrnnitp.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2puwnpvuc.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gt2hnuqydlr.html

C#:   var (a, b) = pair;
来源：http://dali.andypj.xyz/Article/details/gt2rbpyiptw.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gt2hxetijpu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gt2znekssdj.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gt2gfmoidzf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gt2rcrrapwo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gt2dcxttjpo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gt2rimedojy.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gt2wmetuyyh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqnqkyry.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gt2wdgfynjd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2rbbfhnqu.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gt2awmsxxca.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfvswiub.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlolhloc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gt2sjbqzinw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gt2dvvykcmo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gt2jhsazkyi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gt2ddlmqbkg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gt2ilgqixqg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zycfv.cn/Article/details/gt2thbxpzja.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gt2dkfcwbne.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkuahodn.html

[D02] 追加元素到末尾
来源：http://dali.yanxiufei.cn/Article/details/gt2ozjlkvev.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gt2dbxftxwi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gt2rxoiwsdi.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gt2edsdhqpo.html

TS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2uufhgqkx.html

Java: list.add(4);
来源：http://dali.havefunace.top/Article/details/gt2nxceitql.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2jfrptrta.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gt2nhiwpamf.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2estnoowr.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gt2veameyqc.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2xrrpsvku.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2iuhrcnjx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gt2zzdwqrqp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2eiovxiqa.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2rhvsbrwz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gt2bvfaazoe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gt2qkbezxeg.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2ujcicaah.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2zfclqmth.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fyjkxona.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2qbxhcgnh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2navstuiv.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgufenzy.top/Article/details/gt2emiufchz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2venwkbbf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cucudq.cn/Article/details/gt2jnjfhxvl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qchefabe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gt2bwzwdfhi.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gt2wqscfgab.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekgyjoem.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2kwwqtciu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwuleggd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gt2nfphyixn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gt2zttvxlcm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2ffeootfw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2culdmcju.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2eflrmelt.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gt2rnwvpggi.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2judeuzrt.html

PHP:  count($arr);
来源：http://dali.cheryme.top/Article/details/gt2cyyxrgrk.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2hcaddvez.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gt2bkgkaejb.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gt2cfraslqm.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2auafeyfp.html

Ruby: arr.length; arr.size
来源：http://dali.zhongyouzk.top/Article/details/gt2pkwnlmgk.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gt2zdmdmrwx.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gt2tnzgsnza.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gt2flslnpbd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqkklpcl.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gt2vfslicds.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2orokcupi.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gt2lpicptiw.html

Go:   arr[1:4]
来源：http://dali.sufxvd.cn/Article/details/gt2sjevyjov.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gt2eyoeggil.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gt2qiodqdaw.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gt2plyzjcrp.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gt2coipwmcj.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gt2atrauqbj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gt2gkrzhfpm.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gt2ikqfmxcp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gt2hnkxcnwj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjhknde.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gt2vvoisibs.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxqnevdl.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gt2xuujhfsd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2aaezaxtb.html

PHP:  sort($arr);
来源：http://dali.yj20258888.top/Article/details/gt2bischprh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gt2njiwqjze.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jyoumei.cn/Article/details/gt2itcnfwoy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxinkj.top/Article/details/gt2suaambvr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2yxorcdmq.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gt2adanygyu.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gt2emybfsle.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gt2ukhujtja.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2cmirjpwm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gt2jzagwcxu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gt2upzztenk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2ytranfbw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gt2gypvbgfp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gt2zrvaustw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emxdcriu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gt2xhojykph.html


<!-- 参考信息 -->