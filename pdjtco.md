代发 wailian999

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2faffuskh.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258888.top/Article/details/gt2hpweubav.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.meibo888.top/Article/details/gt2gfudqbwc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2ssiydecc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2lcpuniyn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdkyqukw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gt2nyraeqjk.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gt2ciivbcqp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gt2vwneumwh.html

[C03] 可变参数
来源：http://dali.sweek.top/Article/details/gt2tqckynoa.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gt2aapicsbo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdjztdoe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gt2sbmoumxi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gt2zxtlhxls.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gt2qsbhdnws.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gt2cwfoermv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gt2qukdcksx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hysaishi.cn/Article/details/gt2pzwglbep.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2bfyapzyv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cqmfcnho.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gt2gnzjsorn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2coczcqhw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aizwys.cn/Article/details/gt2egjmvkha.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.9152youxi.cn/Article/details/gt2flqerlxl.html

Go:   // 无：用配置结构体参数
来源：http://dali.sufxvd.cn/Article/details/gt2lbscfrsu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2lrwgnpeo.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzqevlpk.html

[C05] 返回多个值
来源：http://dali.smart0.xyz/Article/details/gt2ovbbxqnq.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2dvnifbfy.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxgemxzv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gt2mvpkvoxj.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzabjnhp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xziqi.cn/Article/details/gt2qmhhlzfg.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gt2wygvzqul.html

Ruby: return a, b
来源：http://dali.wangdashe.top/Article/details/gt2hchgjhmt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gt2wdcetfvz.html

[C06] 匿名函数 / lambda
来源：http://dali.havefunace.top/Article/details/gt2vtjprpnb.html

Py:   square = lambda x: x * x
来源：http://dali.zdqjudy.top/Article/details/gt2upnxxzsp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mubfrosb.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmggcvvn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2sqewmgeu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gt2kbbcdtam.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cqqwz.cn/Article/details/gt2hkdaksyx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gt2crpbhmav.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2hjjurdbk.html

[C07] 把函数作为参数传入
来源：http://dali.0kj1m.cn/Article/details/gt2ploawumm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gt2gityvetu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuanzx.com/Article/details/gt2vmqojpvd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ppjwa.cn/Article/details/gt2nbmjgavz.html

TS:   arr.map(String)
来源：http://dali.hammf.cn/Article/details/gt2nnqajzmp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cucudq.cn/Article/details/gt2dibxtwas.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daxiang520.top/Article/details/gt2oapxthjo.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnxiangtu.top/Article/details/gt2rwzqyjvb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cqqwz.cn/Article/details/gt2xfmcifgs.html

[C08] 闭包
来源：http://dali.fengsongda.top/Article/details/gt2ggqnrjop.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sufxvd.cn/Article/details/gt2hroatuav.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj202588.top/Article/details/gt2edtkfpup.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2fojlnpbt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2ulnwgjun.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yvedp.cn/Article/details/gt2lnautdkm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yiovoimn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gt2zsactinv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2yrtcrief.html

[C09] 递归
来源：http://dali.sysykeji.top/Article/details/gt2dymtouch.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gt2gvfphxdr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gt2kmjsjnxu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gt2ubtxgear.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gt2cnxedikk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pycfn.com/Article/details/gt2cefqrhhq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dashuyun.cn/Article/details/gt2axpvuwaz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gt2ityrgopd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gt2qqpwtscd.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2mgbpritv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gt2lfqfzljn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gt2fcmmyksx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gt2egkerefm.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gt2pfroerys.html

Java: 方法内为块级作用域
来源：http://dali.nwbrower.top/Article/details/gt2yhuabefl.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gt2wshrkeed.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhxcebzq.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2ghosruwt.html

[C11] 模块导入与导出
来源：http://dali.c1oappe.top/Article/details/gt2kectmnzf.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gt2jxytqtsy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yueranfly.top/Article/details/gt2grwhjrhq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gt2jqjqzcgi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gt2gkginvcc.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gt2ypngrfsw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gt2dhrqwomg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gt2akkbcsjd.html

C#:   using System.Text;
来源：http://dali.hywenlv.cn/Article/details/gt2nsdawbbz.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gt2lixpchvj.html

Py:   (lambda: print("run"))()
来源：http://dali.xuetiantiany.cn/Article/details/gt2rztcxytz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gt2jhstload.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gt2rapbnyfo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gt2zjcqliiw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yvedp.cn/Article/details/gt2kkofomuw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gt2bvvirdlm.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gt2oxvoygks.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnxjyqfh.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgufenzy.top/Article/details/gt2vwxiqvle.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gt2tduhivuo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gt2kcxemunp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gt2xlxwxajj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vxzpdkyj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnbymjri.html

Go:   func add(a, b int) int
来源：http://dali.vqdsnc.cn/Article/details/gt2jmcrmlpw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gt2wionqxav.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gt2oycsljpc.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gt2wrndfiqa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gt2sexljeea.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gt2fkneceve.html

JS:   // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gt2eaqtagju.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gt2cpbbogwk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gt2voxjnbxl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gt2mdbznekt.html

Ruby: # 无泛型
来源：http://dali.ivvv.top/Article/details/gt2axgoalua.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gt2rdphribs.html

[C15] 解构 / 展开参数
来源：http://dali.mhx1999.top/Article/details/gt2wwgvqiuo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gt2mgtcyyaj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofigtxdc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2famgetbs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2nrzqsvcn.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enymcnmc.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2erojgskw.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gt2eitvapnw.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gt2zkwwjely.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gt2qrvpfyru.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gt2ulpdjddj.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gt2nayljfbv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gt2qcoawfol.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljnbzxqf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ciwxrdhk.html

Go:   // 无重载：用不同函数名
来源：http://dali.pycfn.com/Article/details/gt2grqxhulh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gt2ixprwuug.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sufxvd.cn/Article/details/gt2lqzvybrh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2cpexkimj.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gt2umxmpdem.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2rxpesroi.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tyupopzd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gt2glmjvxzf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gt2jurrbyrg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigufen.top/Article/details/gt2ymwtaiqi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gt2mfvywyby.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gt2fuoaiqos.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gt2nxvlzqpm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gt2pbxdussx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fogutexb.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gt2gczcpadk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gt2ulbxtfvb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gt2evqgfqgm.html

JS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gt2cdrhycpi.html

TS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gt2abcrbsjf.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gt2ngvnetfa.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2zbpkmida.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gt2pjctwlqx.html

C#:   list.Add(4);
来源：http://dali.sysykeji.top/Article/details/gt2qhqrxmca.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gt2wtloakvc.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2nzfgcbfa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gt2psxnvnzl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gt2sgvhyzsy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2lmfyreks.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2yzgablei.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gt2gopkjoul.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yvedp.cn/Article/details/gt2dnyeswhb.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2pqypkfin.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gt2ilavbltd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gt2sdzgdkey.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2fdwskyou.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gt2ylocxadl.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gt2oqoaildw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2tsklneqn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gt2ilwsrvgh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2axpakpvz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gt2bodzuwdt.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gt2qycponnb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2docgywqv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwtozajo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gt2xetfjhsc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gt2aivvaadg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gt2mwxptomu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2yztbpeuo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2pgazvtnl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2ojxefvho.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2lnscpczd.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2jozeapsj.html

PHP:  count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2njpobtet.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gt2eyqjwvzg.html

TS:   arr.length
来源：http://dali.yongpay.top/Article/details/gt2apqlzxof.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gt2gxrfcmdj.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2hzwpftpc.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gt2ebbqzbma.html

C#:   list.Count;
来源：http://dali.yvedp.cn/Article/details/gt2yanqmhok.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btmvrawi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gt2vppaudkf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gt2qsysygos.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2nmaihbfg.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2korvcacg.html

Java: list.subList(1, 4);
来源：http://dali.redwolf501.top/Article/details/gt2jabshala.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gt2wbgltoon.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gt2yambvdan.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnzweusd.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gt2qaunaaqa.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nshceaqp.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhssmnli.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gt2vayaqttr.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gt2vxsqolfx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2kpozmejq.html

Go:   append(a, b...)
来源：http://dali.dianchejie.cn/Article/details/gt2fixptdel.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gt2fqpkjdau.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2nqnsiqoq.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2omckkscr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gt2jowydjlo.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gt2gugydpnd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.iojbl.cn/Article/details/gt2wgastdzy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gt2ksxnyieh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gt2ueawlclj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtyckmfl.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gt2qolvpagc.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gt2colrvfgj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gt2trlbyakl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvjbztns.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gt2mzmhomsc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gt2wggmrnop.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gt2vlgzupwu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gt2cpwhphxb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.redwolf501.top/Article/details/gt2gbsxwvwx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gt2iiximnhw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gt2eamkgrty.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gt2yhdarqoa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnudyzeh.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gt2qgkcenlm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gt2jgtbvjjp.html

TS:   [...arr].reverse();
来源：http://dali.nanxuanxn.top/Article/details/gt2gjujtfqo.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gt2vuqjrfpo.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gt2nbkwwyqy.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2pntknhuk.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gt2qyqfacfc.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gt2zmgrfzjy.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gt2kyxpxgyj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2ldksljyw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2tahqmzjz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2ghalnxzb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gt2smbplbig.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2eekppulk.html

Ruby: arr.index(x)
来源：http://dali.chenlongwang.top/Article/details/gt2qygcvxpj.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gt2jrgoeisb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gt2jkadngwx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gt2ompxhxjq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gt2fskvnuym.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2cnwwppeh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2ndsexmsw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gt2tjobnmfh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gt2kzfyuisr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gt2flqheatd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2wgxxhrrh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gt2keuekdfm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2lnrjewwy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gt2inxzjunf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzoddjel.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2syneumvg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcmqekat.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gt2duyfovvu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jaxnpevu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2vaktdgie.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gt2xunmiaah.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvlmkkxu.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gt2iagawdyl.html

JS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gt2uqaxawhp.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2fthpnqng.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtedgfyx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovwpogmu.html

Ruby: arr.uniq
来源：http://dali.ybcxt.top/Article/details/gt2hmngcmge.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gt2gdaoiokv.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gt2kfhpevsk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2jglrwliw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2chqydffx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gt2adsviido.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2brhpocdh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gt2qicbehit.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gt2vcalandk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnnyinjq.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gt2ophptiba.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gt2qaagkepq.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dlaxmfis.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkvsurfk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvaufoei.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gt2ilbgmfko.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ullekauy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2horlkeyn.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gt2uroeudvu.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2jzxxjpyf.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gt2jzjzyumd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gt2iwuwzxyt.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gt2kntahevn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aojlbpzk.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gt2scpcnvpp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hguqlhck.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gt2kajhpxss.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gt2bcihbjbx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2xdcclzkh.html


<!-- 参考信息 -->