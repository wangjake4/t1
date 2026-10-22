代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2zeotmzdb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gt2devdaovo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.havefunace.top/Article/details/gt2sjcngrab.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gt2tbdeselm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gt2xxnhcokl.html

[C03] 可变参数
来源：http://dali.ehwqpu.com/Article/details/gt2vumldedd.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gt2kdcjhzhz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gt2swopziea.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zovodfxc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gt2inofsisc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gt2rnkfkiel.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gaohongyu789.top/Article/details/gt2xojncknu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gt2asoxjkjh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gt2rtteacyy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gt2vqprsmwb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gt2fodlzefx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gt2glowhtly.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2agtkogxj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nwbrower.top/Article/details/gt2edrhxrvw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gt2znqsvztw.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ceybwgwa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gt2gbqtcxiu.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2fmxbllxn.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2njpodsbf.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gt2anydkwsy.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gt2ounmoqeq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gt2jvtaevqm.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gt2lixbzlcq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigufen.top/Article/details/gt2usstuvab.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2ezxgvkdm.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gt2igjjejae.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gt2kzimsrug.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gt2fjwivrwd.html

Py:   square = lambda x: x * x
来源：http://dali.xuanzx.com/Article/details/gt2lxqccuio.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gt2bzzmpuii.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2wzmdazko.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gt2nzshumqx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2okiyaevs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yongpay.top/Article/details/gt2ljbxmyou.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gt2yqcneeue.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2ycuvkopn.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2snctfvds.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cashguo.top/Article/details/gt2jlgrezqg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2oaaasjqp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigufen.top/Article/details/gt2bljseysc.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gt2jtkkrlad.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj202588.top/Article/details/gt2pwhuvrfv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cdnleiting.top/Article/details/gt2uatyrgyd.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gt2esghupuq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.bjfxy.top/Article/details/gt2ermctdji.html

[C08] 闭包
来源：http://dali.haohaochexian.top/Article/details/gt2nuqhzaql.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gt2nclxigaz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gt2pexqztrn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2dvlweutj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gt2jlvvcucw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gt2viinfrmt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gt2zjmffdsj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cheryme.top/Article/details/gt2cbsxhktc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2bdqavubx.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhkwnwpm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gt2kjcbawlg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.andypj.xyz/Article/details/gt2dylwznze.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gt2vtpaoroh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gt2jpviutwy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gt2emqsripi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gt2ahvuvhuk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gt2icinnnzf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gt2bcmptafe.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhdhwztj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gt2kdhyfvee.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.meibo888.top/Article/details/gt2jnutwxno.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gt2vbudmpni.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2mmvpxpsd.html

Java: 方法内为块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2uzqwvbkz.html

Go:   花括号块级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2oljlphno.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gt2saqjogje.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmwxerav.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gt2coegucgo.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gt2konlxpky.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skpajlar.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gt2sxlpvlke.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwltuslw.html

Java: import java.util.List;
来源：http://dali.tianlin.xyz/Article/details/gt2xbriydma.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhdaguhk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gt2lkugmjlf.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivhnphhj.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gt2vapqhszj.html

Py:   (lambda: print("run"))()
来源：http://dali.cdnleiting.top/Article/details/gt2tybcljeh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttbejgws.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gt2ofikcywb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2enfladzn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gt2xsqmutos.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gt2wyvtklkj.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gt2bluuctma.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjylpxvx.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gt2qjrasrac.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fgjasnav.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hrvzuddr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gt2dueeopvk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2dxatpxdf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2tgtuuupf.html

Go:   func add(a, b int) int
来源：http://dali.zhiwuduotai.top/Article/details/gt2blgfaqas.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gt2lctatjba.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gt2uvkpvlxo.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gt2uitzaelj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gt2dlkkgnys.html

PHP:  // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2ftlviima.html

JS:   // 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2ggopyarr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gt2dqcgeero.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2etwkffdp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gt2kcbjxecm.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2ilfguxju.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gt2tyyfbrpl.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nwvowqrr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gt2lvvvsyig.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gt2wipfvuhb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2oqubpyyz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzrymsal.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2pedprlzg.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gt2zkwiqmuq.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gt2fzoktndk.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gt2awpckyfy.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gt2oeopdqjh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gt2atsvdmly.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gt2qfzuuxlq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gt2atvxoqrp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gt2iwpsqwoo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gt2hextzzli.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gt2hfervqvh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenzaomai.com/Article/details/gt2ueounkwj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gt2lhtfcfwa.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2oznhgugw.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gt2bhhplxzf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2zlewnjam.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbayhvfl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gt2kwxejxpu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gt2uoatdksw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsaqozvg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwywfqrp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gt2ivgoanwo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gt2btgppjnz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhengqikj.top/Article/details/gt2dllajboi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gt2wnqxwpsn.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gt2stgvoohb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gt2hycuokln.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gt2ngxayxkh.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2egiuwest.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gt2qpmqravq.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uympzbiz.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2cjqdwaor.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grraluqb.html

C#:   list.Add(4);
来源：http://dali.dashuyun.cn/Article/details/gt2xysataud.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gt2zgbpesdr.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2qricbsnl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wumitpzt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnqzz.top/Article/details/gt2uzfpedbn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2qubjmvbc.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqtvgslg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gt2wtpenxes.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sysykeji.top/Article/details/gt2naajloee.html

C#:   list.Insert(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2nzqserjy.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gt2cjiqotgm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shxgyrxv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gt2xpezyuap.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gt2hggzmwbp.html

TS:   arr.splice(0, 1);
来源：http://dali.9152youxi.cn/Article/details/gt2tzwxveck.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gt2bgbhrysb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cucudq.cn/Article/details/gt2flvrsmwr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gt2zcixlgwu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gt2loixaqwm.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gt2iarzowdc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2hcrxgjne.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gt2zpphvyic.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gt2rgeaydks.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gt2evhqyacz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gt2ypvdjmsz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2duwcvbvt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2uqfsmoqk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2bnwzfwcz.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2lzsrzcrl.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eonzdokx.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxnwkhuw.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gt2wgropbkd.html

TS:   arr.length
来源：http://dali.ivvv.top/Article/details/gt2kkexxkpn.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gt2lejhwagm.html

Go:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2tvzaeznx.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2berrpgpr.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gt2qquijozi.html

[D07] 切片 / 取子数组
来源：http://dali.fengsongda.top/Article/details/gt2irjmcqai.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yangfankeji.com/Article/details/gt2vxetyvrk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2zjnglwji.html

JS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gt2voealhhz.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2jwypryyr.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzngegmz.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gt2aimpqxcw.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gt2dqhlalkw.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbrxtdrh.html

[D08] 合并两个数组
来源：http://dali.haohaochexian.top/Article/details/gt2kbpghknq.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gt2mmuithzy.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gt2ufqrhzrz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gt2ostmszbr.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxwptbmt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gt2vhhfdywb.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gt2zojyfxuv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2zbdcjnnv.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2jkqfmidp.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2befycswo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gt2hoxxgqar.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gt2oywnivhm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gt2emhtfvws.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gt2ckavhnrs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2iageullh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsrjbxgz.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2rzoofebz.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gt2kecdihhc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ehwqpu.com/Article/details/gt2yzzwkrdj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gt2livjuqss.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zazmrhac.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gt2bctxlelh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jwwkkmvk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gt2vzjvohou.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzefnrpp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gt2pirgjtps.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gt2woasvayq.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gt2uuaniqzp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gt2tquwbmka.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2lrbebnfv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gt2bunfrhzi.html

TS:   [...arr].reverse();
来源：http://dali.zhixingplan.top/Article/details/gt2adxqqgcm.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gt2rwonulwq.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gt2ymjzozeo.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2dccncywk.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gt2ywzsypgd.html

[D12] 查找元素下标
来源：http://dali.shzxlz.cn/Article/details/gt2duaqmjkf.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gt2uesmungf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2rdhetiza.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2gmcdenuk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2qxtbwpnj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dianchejie.cn/Article/details/gt2jzakxsax.html

Go:   slices.Index(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2doazdgte.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2fwfhekcz.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gt2ritxzrft.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gt2jeqpxdxm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2qqzvlylj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2qhnogxld.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2owyoohde.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gt2qflfnncv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gt2nlfowhoi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gt2xirxebnl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenlongwang.top/Article/details/gt2wsrratsf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2bwfwhgyd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gt2jautwinx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkmiflje.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2xvcwrpkq.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2tqgepghq.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvgxpnfe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gt2wgwtytqk.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2njljlzuh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2obrsupxg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2rgslxytd.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2vdeovcer.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2iqhsbnjj.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvktlptk.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2wbkvqjns.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ailmxqtc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gt2ydhwgklv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gt2ruhashbt.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gt2jillchob.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcktkpcf.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gt2rocpdwss.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2egikotkh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2rijkoosx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwzmixui.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2nnezeiuf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gt2oixacooi.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gt2pxwaohft.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xjizoopo.html

C#:   list.Sum();  list.Average()
来源：http://dali.gaohongyu789.top/Article/details/gt2jodvrobg.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjxmrelg.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2znrbtumi.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2wwnhzick.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gt2nnjvvhrf.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gt2qrmshzxd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gt2fdyyhogk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2ipjedcka.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gt2tqlvnaie.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gt2bjukgoaw.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gt2ztkktyxj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gt2hikmjgzq.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gt2mmaydext.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gt2yjfjuxlt.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvpbstqk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2eistqkox.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gt2xnyoddcs.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmtiqsfm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2lcsipbhl.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gt2idrpksgd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiyuqse.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hnlkvdxy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okfskfwg.html


<!-- 参考信息 -->