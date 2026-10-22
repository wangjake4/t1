代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2yklknwax.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gt2yjownmhp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gt2qtjuqael.html

Ruby: def greet(name = "World") = name
来源：http://dali.vqdsnc.cn/Article/details/gt2caituzfh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gt2jcdgibgs.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gt2rvpqnlzz.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gt2myunnzcn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yueranfly.top/Article/details/gt2zgzgqdgt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2ynijbpji.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gt2yyabljpv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gzhubu.top/Article/details/gt2nfaaqirz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cdnleiting.top/Article/details/gt2sdndrykr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gaohongyu789.top/Article/details/gt2poysluco.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gt2aedlzhtr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gt2zbxiqewf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shzxlz.cn/Article/details/gt2icxvetuu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gt2oprfduqq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2vabxptjm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gt2gbxdgfsv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.snrcjt.cn/Article/details/gt2pscoakft.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenlongwang.top/Article/details/gt2bwsctlac.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2lisuqbys.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2bfzalpqq.html

[C05] 返回多个值
来源：http://dali.xinyue.icu/Article/details/gt2gzlkncqb.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2rpqcksac.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gt2dkrjrnpq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fzhhl.top/Article/details/gt2snpeauvb.html

TS:   return { a, b };
来源：http://dali.cheryme.top/Article/details/gt2onsbenxr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.haohaochexian.top/Article/details/gt2lqplpmue.html

Go:   return a, b
来源：http://dali.smart0.xyz/Article/details/gt2tcysnjwf.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2cgbeldkk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuxming.cn/Article/details/gt2skltfkyo.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gt2rtcpurju.html

Py:   square = lambda x: x * x
来源：http://dali.guowangkeji.top/Article/details/gt2zlisewvk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gt2ocsapbcx.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2pbhiecwm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2qfycfxlb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gt2idzfddis.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gt2nwuwomuh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xziqi.cn/Article/details/gt2qjtweptk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2ijaqgxju.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigfzy.top/Article/details/gt2hvsbtzub.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xinyue.icu/Article/details/gt2fhdbcoow.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuanzx.com/Article/details/gt2ejyvbfnz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gt2fmacyimk.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gt2veggkaoh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2rzrbdzir.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gzhubu.top/Article/details/gt2eivwxken.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxuanxn.top/Article/details/gt2oqjxmuwv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigfzy.top/Article/details/gt2kqwogzva.html

[C08] 闭包
来源：http://dali.aizwys.cn/Article/details/gt2rcbetwnk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gt2wxytgtjv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gt2osmcqcwb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2irvfhrgx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2ijktayyv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gt2ftbpblut.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gt2fwprjdfk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.9152youxi.cn/Article/details/gt2deiqkscn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2nxmvowzl.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gt2kkmcpqrc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2lojmibbx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gt2lxenanny.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gt2nihfhaye.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gt2pazlvopi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gt2dhjxmwnq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twpcxwvc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gt2niureyce.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sxryk.cn/Article/details/gt2osnmmhue.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gt2gsomcmbf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gt2oqivdwqk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yangfankeji.com/Article/details/gt2vjgzpyoy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2ggxizeek.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2jhrwzqzt.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gt2spigzjhi.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekalbnkw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gt2rasfmqap.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzpxxsgx.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gt2ueezckej.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gt2vrknjvaj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yangfankeji.com/Article/details/gt2nvfzivgd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gt2hucrwblk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gt2qxfuorod.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gt2iwgvnapg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gt2lhironmq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ehwqpu.com/Article/details/gt2gbhjlsro.html

C#:   using System.Text;
来源：http://dali.nanxuanxn.top/Article/details/gt2pwyrbpdm.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgwyhppq.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gt2vpacpqvg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2lshtrudr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2jazkepnz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzgretst.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gt2psqnzikc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gt2crgkxdkx.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gt2fhqagamk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2pncdschg.html

[C13] 类型声明 / 类型注解
来源：http://dali.cashguo.top/Article/details/gt2dzqomctf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gt2rhrazewc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2nyslfjcs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gt2ygdsgqda.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2spdtzdqc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2xkuzxhbj.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xrdumptp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gt2hbxiwajf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gt2txzruqbd.html

[C14] 泛型函数
来源：http://dali.snrcjt.cn/Article/details/gt2bqqtvohp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gt2oxcuwwhv.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gt2iqqhcacb.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2huhuwzgt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gt2vrmcgaij.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gt2mvqvlsns.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gt2eluvpwyn.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2letnvbwr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gt2qvhmbock.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytcxmydo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xknxqucl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gt2ljbgcpgb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2rvmjeuab.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2vavtagfv.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gt2iejtgwpv.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2xqkpalpe.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gt2ggcchaob.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gt2rjanpxka.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gt2xzigksyx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gt2rkvrobxl.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gt2kwjtdlnn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ydzc1.top/Article/details/gt2oqewpiyb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gt2rmqiqdau.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nsroumtw.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gt2gghxjony.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenzaomai.com/Article/details/gt2sjsgxlcs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gt2rmgmevxa.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlloxxkp.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gt2zzzulwas.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ioioueue.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gt2tlatrvpr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gt2kydhyjnn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2jccfrmkt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2uyatwzou.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gt2glgtsbck.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gt2kfoboayz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gt2lwmopzot.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gt2uxccavcb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gt2cnhsuznm.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlqsckor.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gt2laahvloe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gt2erzqwvcc.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2czitzflc.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdsuigue.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gt2gcipeqvm.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gt2nvvuqjae.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gt2hsnomenh.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gt2qbctettm.html

[D03] 在指定位置插入元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2klpgkywc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2nhevxuvl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gt2eyrflnht.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gt2qxnvlweu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2tkaemcnv.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxbjbcwj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gt2eiqsnpwp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuanzhike.top/Article/details/gt2agcirxps.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2pfrysjar.html

[D04] 删除元素
来源：http://dali.jqgufenzy.top/Article/details/gt2bvxjujjj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yongpay.top/Article/details/gt2udagncpb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2whdylgcw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hysaishi.cn/Article/details/gt2mnlluifi.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2yvbnupfv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hysaishi.cn/Article/details/gt2usbhbtsf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhnxjnft.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2mkklknmk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuxming.cn/Article/details/gt2ysxfpixw.html

[D05] 访问与修改元素
来源：http://dali.hnqzz.top/Article/details/gt2hfdfdbng.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtkmrqne.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2dvrevzbt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2uudrypsx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.vqdsnc.cn/Article/details/gt2utndjxzx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gt2migfghgr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2btnlmvey.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gt2wkukeybw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gt2cyzztsex.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2wjnppmme.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2caxrrjww.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2wilboehr.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gt2mivyzwoe.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngbdjhlt.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gt2mxfvnkfc.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gt2hvfffcef.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gt2uygxtvhk.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gt2swflarbh.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gt2uhuayywj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gt2ekejddpt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2ywcsgmnm.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2jrjnmgwe.html

TS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2vjqknkjv.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2bvnmrvif.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gt2spnozclm.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gt2wvnwhdol.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2oeujdtwl.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gt2sxdxfdlk.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gt2zreodyxq.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gt2ppfgkwph.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.vqdsnc.cn/Article/details/gt2ftrwxzbr.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gt2gvqwdxwa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gt2tbwigtqj.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uamqrqir.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2olfmgsdg.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gt2vygclwqb.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gt2lhlzjrjl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gt2aeomydqm.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbyhqgpj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqwhrccv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gt2yvxfaxkr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gt2cpjfwcue.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2iyzvhcjq.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gt2rnztlusn.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gt2tjpbjylh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gt2hpulrntn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nwbrower.top/Article/details/gt2nunxxsfu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gt2agnvkedq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzjswwtt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gt2rnjfsapq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gt2sqraxvet.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gt2kkkxixff.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gt2eeujefsk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gt2uuvhaqhb.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gt2ohmbjpmc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigufen.top/Article/details/gt2zwnyegdx.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2jylevgow.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gt2vkfjnglh.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gt2hfdbusdp.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gt2uaneaojs.html

Go:   slices.Reverse(arr)
来源：http://dali.redwolf501.top/Article/details/gt2ryyaanaq.html

Ruby: arr.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwfmrbnk.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gt2weaaxdeb.html

[D12] 查找元素下标
来源：http://dali.daria6918.cn/Article/details/gt2pmuaskci.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqrwulcc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2psiulwlg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjamntzi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2ehvpskzk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fengsongda.top/Article/details/gt2yrwqcbgp.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2uilafhfg.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gt2uxtudaxt.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gt2vufhevjf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gotoacloud.top/Article/details/gt2eesdctfv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gt2urqxwnkl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2tmryawee.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2bzwcnzmx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2hunfivsw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2hkfzkinj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gt2omiysjqs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj202588.top/Article/details/gt2bhbjpzol.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2iohtoszi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gt2jrzeuxqc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2upzjxrha.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2vdmtboqf.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2labehnls.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2foupmuwv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2tusnndfp.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gt2fhrrybsu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2myrtjfeq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gt2lywczgjk.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zopesdle.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gt2gfvhvofh.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gt2sanagkuq.html

JS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gt2guadlxuo.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2fqeppsug.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vizpujnj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gt2hplushgj.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gt2dboatbzt.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2lybxurws.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gt2nghuhqth.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2gugnesmk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zsawoqfu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2xyaaknsx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2dieabqdi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gt2pstdrlxs.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gt2rqggjlgq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gt2gebbkifh.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gt2vjccngsz.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gt2qcjckhkq.html

Py:   max(arr);  min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmvlfzau.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2ehxfaefa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gt2oggfmpca.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gt2rkisiyqu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gt2wktnkzgt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysnpfmla.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gt2dzzoefpv.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2pjjwxvsm.html

[D18] 扁平化嵌套数组
来源：http://dali.sufxvd.cn/Article/details/gt2sujsgdkt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gt2eejodkdq.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gt2nihxumha.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gt2hysekxcs.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gt2yabgixly.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fzhhl.top/Article/details/gt2naxwcnlj.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gt2ptwniagw.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gt2pddxyvqn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2usivucnt.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gt2chyqfxdy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gt2prtoziyo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gt2rjqgplef.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gt2fajueweu.html


<!-- 参考信息 -->