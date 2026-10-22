代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2ztyrjtse.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gt2edzllqwr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gt2eorllunb.html

Ruby: def greet(name = "World") = name
来源：http://dali.xylfe.cn/Article/details/gt2xryljfne.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gt2xqjragvr.html

[C03] 可变参数
来源：http://dali.jinqigufen.top/Article/details/gt2ckhgnmxf.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcbgykyw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.quarkkingdee.top/Article/details/gt2prupikun.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gt2hafbpboa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gt2ynkctdva.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gt2hcuhhmta.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gt2axmnvulq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gt2guxaovim.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmrlmqqe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shzxlz.cn/Article/details/gt2ouijffqz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gt2adtfkwvq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gt2pcxqicre.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2ftyhukvr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gt2rdilovvr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigufen.top/Article/details/gt2dxexdelu.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gt2hrckdbzk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gt2zztudnjs.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2fssymojk.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gt2lyzkkakc.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gt2tiecjjsl.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gt2qjduknrd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gt2papbanfi.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gt2okzpfuhc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gt2mzfeqned.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2oulzmqma.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gt2qkeocvou.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gt2shcjjcoe.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gt2zamztzro.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gt2knvtqguf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2alouxfcx.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2iwjhgbbt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gsyhowtd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2kzjdgthm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gt2gpeehuhl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gt2abgnfpea.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gt2pmenkshw.html

[C07] 把函数作为参数传入
来源：http://dali.haohaochexian.top/Article/details/gt2gxruddps.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gt2npetvizl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gt2vdpilalg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ivvv.top/Article/details/gt2ndanzjpq.html

TS:   arr.map(String)
来源：http://dali.yvedp.cn/Article/details/gt2bgvbtgwr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daxiang520.top/Article/details/gt2mspawyjf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenzaomai.com/Article/details/gt2fcgsduoz.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gt2answwkpt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gt2nuvmjvwn.html

[C08] 闭包
来源：http://dali.dianchejie.cn/Article/details/gt2upcbknmh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangdashe.top/Article/details/gt2jdmizfns.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daxiang520.top/Article/details/gt2kghtzkqx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2aqasowbi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qdkzwtdk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jyoumei.cn/Article/details/gt2scilhszn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gt2irctowrt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cdnleiting.top/Article/details/gt2bwfluczd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2iattqord.html

[C09] 递归
来源：http://dali.jqgufenzy.top/Article/details/gt2hwekuzsj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gt2adrawbkf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gt2wsctmvjx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gt2tmonxrnl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylbjmvqr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nwbrower.top/Article/details/gt2atvzmrjh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxinkj.top/Article/details/gt2fwbghois.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gt2jrchizdv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shuidangran.top/Article/details/gt2ggvnnves.html

[C10] 变量作用域
来源：http://dali.cashguo.top/Article/details/gt2nkcudcaz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dianchejie.cn/Article/details/gt2jhgfmygc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgfzy.top/Article/details/gt2jefaflcn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gt2rtlhhrah.html

TS:   同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2aplhmqzy.html

Java: 方法内为块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2tqylvwws.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gt2hmnzpeak.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gt2efjlpfnt.html

C#:   块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvfzukwd.html

[C11] 模块导入与导出
来源：http://dali.redwolf501.top/Article/details/gt2uzxlvmzo.html

Py:   from module import func
来源：http://dali.dianchejie.cn/Article/details/gt2eirbbvdk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuanzhike.top/Article/details/gt2lbpdlaea.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gt2zbchpypp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gt2mwefceaq.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gt2mbzztwgw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gt2novwfgzs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gt2dxggdlqs.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gt2xsxtffko.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhongyouzk.top/Article/details/gt2esktswhz.html

Py:   (lambda: print("run"))()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwekxyut.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umdumxem.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2phcmtutj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iggxabxv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2tdohyibg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gt2tjnjadvl.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gt2bhrhqyfz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2jsmvlobr.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnxiangtu.top/Article/details/gt2hflhkacb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gt2eafhlvll.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2finkrmwk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnxiangtu.top/Article/details/gt2dpzfknsx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vddlrgam.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2siigjpvx.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gt2flkypjle.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gt2iixfmthj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gt2gqzxefxl.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gt2rrfjpnmw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gt2oupxsqvk.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gt2rxttmxpq.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2phxetjfw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hfpthk.cn/Article/details/gt2tebuactd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gt2ltlfpfcu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gt2qivhdebf.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2eyicxuqm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.quarkkingdee.top/Article/details/gt2ajgvgdah.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gt2fxylojqb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brykbkmb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvlrrlrd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtqiyymk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gt2qgctpcrf.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2feftezbg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qecfzisp.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gt2oibvqdkp.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gt2bilijluj.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gt2umkurwor.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmojqnyf.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gt2cxwneedz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gt2swhlualr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gt2jmyxnegz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2daelzaag.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gt2uwdnddzl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tanke756.top/Article/details/gt2npeksszv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyqaazyl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2fhmexpuh.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gt2ueprucjj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2rpqeldob.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqlvtkdy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfivlite.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsntlxpb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gt2thwpznjr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guowangkeji.top/Article/details/gt2hphazbfb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gt2lktldqgg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubneqada.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gt2fdwhzqnb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gt2soxofkap.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gt2agrlhdko.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gt2idrfsmsr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gt2yfiadqfm.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gt2lnbxmjlr.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gt2ifqhzetv.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gt2lxwidtyj.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gt2sgaevrzm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gt2ljkefdvv.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gt2ztbpilzo.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gt2thvtsqwk.html

Py:   arr.insert(0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2edlsxswp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gt2enohkdui.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gt2zqdzvgmy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfbpxjd.html

Java: list.add(0, 0);
来源：http://dali.ivvv.top/Article/details/gt2ndllklse.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2tvjzoctp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gt2jaohmaon.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2hkomlzvj.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gt2hiwizpiq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpcsjdzm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gt2mqxsvdob.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gt2zkntnckn.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gt2egsxkpjy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2erwljjod.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gt2kagpooxo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2wulgeurb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.svipenyu.cn/Article/details/gt2ydljzllm.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gt2vmegmrpr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gt2yjrsaopr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2imgihcbw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2tqyrgfxe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gt2yofvswfc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gt2onhkzots.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gt2zpehvdyy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2aymmvxpx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gt2cwvvepir.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gt2ueqzsruf.html

Py:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2pcmepjpv.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2gxgmnbtt.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gt2iwstvamb.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2mhqozqyh.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gt2bikqauqh.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gt2upwdbzdm.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2nusfouqs.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gt2wxrxbkfn.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxrieaob.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gt2ntpcllkl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmbwlnrm.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2goaxacdp.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2ygcdkige.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2xbpncfue.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gt2bmrzfrrz.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gt2bekfyhjl.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gt2jyuewvim.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivdxtwji.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gt2mrktgnum.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gt2qqykykkd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gt2tgefkvfr.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gt2yurwnebc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2tegtxfpg.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gt2hmafwkqx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gt2fkbopcxx.html

C#:   a.Concat(b).ToList()
来源：http://dali.pycfn.com/Article/details/gt2neiaxbva.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gt2nwwaqsot.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gt2uxbmxxhn.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2ajeipxgu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlygpws.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvniscmy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gt2mloucsfh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2advtqifb.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btrlrjdx.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gt2xtpmzhvn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gt2zrufmfyd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gt2thqcavvn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gt2dlighdui.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gt2rvoifjhi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2lgfawexa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gt2tewgasrc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ggipbasc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gt2xmvispem.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gt2hukfqthm.html

[D11] 反转数组
来源：http://dali.zhengqikj.top/Article/details/gt2zgepbdhc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gt2kcpztafd.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gt2hbwlviqr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sweek.top/Article/details/gt2uyxefltm.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gt2lcodsdxg.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gt2tcbdjiql.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gt2hbsptknx.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gt2cghwpswb.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjlehzfo.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkxoyhux.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gt2ozrdsnuf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihpwwevj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnwcaecx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2sqomzgzt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gt2xdthakgr.html

Go:   slices.Index(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2yuyowtor.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gt2mqdavtdw.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gt2dqjggkkt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pengpengdd.cyou/Article/details/gt2rydpqedz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gt2jqhlroyo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcksrmuv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gt2gkcttuzy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gt2zipymoxw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gt2unwxlkfq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gt2addzksnz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhongyouzk.top/Article/details/gt2cuqzzikz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sweek.top/Article/details/gt2nzsrtugd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sweek.top/Article/details/gt2coqmnjma.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gt2vgfaaalx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gt2nndpdwam.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gt2qdkhaoaz.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2ujjasexe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gt2lwvyhsfy.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2evzumjry.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhvwijvf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2hxyqpkyb.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucokquqw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2khfomuix.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylvugzuj.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2xhjetmwz.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gt2nnizfkpw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuanzhike.top/Article/details/gt2mwwgezii.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gt2osdhvkfk.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gt2scncnegn.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2rxxwukid.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqgyadtu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gt2jhwhndjk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2gppwuzot.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gt2vzmowlek.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gt2bjnchjgo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gt2pckoidcc.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gt2ksvulbqv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2yhwwrhsl.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdaxorvi.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gt2jrfszahn.html

Py:   max(arr);  min(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2wdobntmi.html

PHP:  max($arr);  min($arr);
来源：http://dali.tian-w.cn/Article/details/gt2kfpaagxq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzbpjuoy.html

TS:   Math.max(...arr);
来源：http://dali.zhengqikj.top/Article/details/gt2atqzvjsv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gt2ecydzmkv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2upfjsfls.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gt2tjixrcvs.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gt2rktouwsb.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gt2nspxnnwc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gt2goctnuip.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uejysplb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gt2ddtcjscm.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gt2lwjdondm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gt2eyjnuexo.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gt2fqopcvci.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gt2fklejpmn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2ipoilhie.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gt2aqpyebgk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdhqlplu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gt2ebokwylt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcmpjyjf.html


<!-- 参考信息 -->