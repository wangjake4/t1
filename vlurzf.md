代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.smart0.xyz/Article/details/gt2ghpztjyu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gt2eeqsdqub.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gt2jewmwxey.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gt2aoapxduh.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gt2anmsoxoz.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gt2httmabql.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gt2rrpmzios.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsqpebcw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gt2asvgnqxu.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gt2fsokspda.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlbmgwss.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntflmjjc.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgtktcft.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gt2jawwwlnz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gt2iqojpnkv.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2dlawiltl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2nvafsuvf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gt2tvjgxaeq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gt2qvujkfmp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gt2nbwpqojd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2whlbahsv.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gt2mxwjpwse.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gt2ienqyjmy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuxming.cn/Article/details/gt2igystqlw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gt2hvhtahvh.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gt2fcfervfr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gt2exqodwyk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gt2mayoursl.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gt2lbafqdjk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gt2lstmagvh.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gt2tyjxpvvy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgfzy.top/Article/details/gt2pnhtgosm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gt2iybuxrbk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eubmfzqa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ethnbjgy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hammf.cn/Article/details/gt2cwlgqmjw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gt2abyieswx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gt2yshounyj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2amliiusx.html

[C09] 递归
来源：http://dali.daxiang520.top/Article/details/gt2jyutyfzo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gt2mqrdurpv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258.top/Article/details/gt2iuxlpulr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gt2aocubzwl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gt2cwitsoaz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gt2vzwywzjy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gt2asdjvrvt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2jvfbdjoi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gt2ujttuikv.html

[C10] 变量作用域
来源：http://dali.yj20258888.top/Article/details/gt2bqqsqtyl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gt2bdwazspc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daxiang520.top/Article/details/gt2yggmhvnm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqsubjkd.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2ezpyrqee.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gt2hjasucyu.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gt2ineiosll.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigfzy.top/Article/details/gt2vnkvitvq.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2skhpuahq.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gt2zycejigh.html

Py:   from module import func
来源：http://dali.aizwys.cn/Article/details/gt2dxgxabgm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.andypj.xyz/Article/details/gt2lhvoojvb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gt2yvlhzgfd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gt2ifcksrgw.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gt2lqcllrsz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenzaomai.com/Article/details/gt2fecpiqsk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gt2omwbwnmt.html

C#:   using System.Text;
来源：http://dali.yonumen.top/Article/details/gt2mscaxewb.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gt2ifgjpxlv.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gt2tfcsrtnf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2wapofixk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fptqbuhv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2pjsxdneu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sepdxzuk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmldachp.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gt2elihqmgc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezkfxoze.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gt2knmronxh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2gycwehzo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2bggoyopr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.mhx1999.top/Article/details/gt2aciibruh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2nnxpnfmm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2uaznvdwk.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gt2mexeimwq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gt2vzpkrdki.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gt2otlbcmqw.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gt2xvlujezq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gt2vvvbhojr.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2yxmfqiwy.html

JS:   // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gt2njnpupge.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aibaodan.cn/Article/details/gt2hesifrba.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gt2izhjxksh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gt2kgrfcnfs.html

Ruby: # 无泛型
来源：http://dali.yj202588.top/Article/details/gt2lymipumz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gt2ddsgsqxg.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gt2zmmtgwhr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gt2gmdgkptz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gt2byovtcjf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gt2ydbrqpus.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gt2iujdcotr.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkxfbtgu.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2jxztkrdb.html

Ruby: a, b = pair
来源：http://dali.shuidangran.top/Article/details/gt2bcdalsju.html

C#:   var (a, b) = pair;
来源：http://dali.mhx1999.top/Article/details/gt2kkgcqtog.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gt2omssndyi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gt2pfrjmhdy.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gt2szonwqqp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gt2xsskpixi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gt2lawkdtsi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.andypj.xyz/Article/details/gt2utlltabr.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gt2zjtyvzgz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fengsongda.top/Article/details/gt2uxqhnrzy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ivvv.top/Article/details/gt2hcehqvjd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2gecdacjw.html

D. 数组 / 列表 / 集合
来源：http://dali.yuxming.cn/Article/details/gt2tlswedak.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ntpxfbxo.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gt2vmzdahtc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tanke756.top/Article/details/gt2mzrqfsfy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktdccikr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cashguo.top/Article/details/gt2dwawxruv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gt2tfrerkkc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.snrcjt.cn/Article/details/gt2vscnerzu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gt2ggubkhig.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gt2lxilfutg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gt2xcnhrdjh.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgvwpbqh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yongpay.top/Article/details/gt2krordyrp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgfzy.top/Article/details/gt2ulqogbtj.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gt2esfosgiv.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2ouezhccc.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gt2euxuqtqf.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gt2sxwklxce.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gt2yjyvbmnm.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gt2wxjiilyi.html

[D03] 在指定位置插入元素
来源：http://dali.dianchejie.cn/Article/details/gt2hgiybxds.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2szjhjmel.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2doezucpj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gt2nbpupepw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gt2abmoaeyf.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2lvjgkmnx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gt2fkyronwh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yanxiufei.cn/Article/details/gt2qrytycfe.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2hlmrfktx.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gt2ppsuhjtf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dianchejie.cn/Article/details/gt2dmqaahul.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gt2ljivjnhd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gt2ojvuudqg.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gt2xuxkpnzs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gt2wfdgehlt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gt2vxbaxxln.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gt2yxnxsaon.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gt2jpgkavrp.html

[D05] 访问与修改元素
来源：http://dali.hywenlv.cn/Article/details/gt2xdahlyel.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwbvuzlx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2tjtmytzx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2kputpotw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gt2dnlpgzxy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ooqvfxcx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2xpeoezeg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2iostxnlp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2acxbvhyi.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2qvgquruy.html

Py:   len(arr)
来源：http://dali.meibo888.top/Article/details/gt2dnvarpqx.html

PHP:  count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsiggauj.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2ovakwinn.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2sfyblfnu.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xemzrpzx.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gt2jokfqmwq.html

Ruby: arr.length; arr.size
来源：http://dali.xuanzx.com/Article/details/gt2hgagjsqc.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gt2odcyhwjj.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gt2elilktcj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gt2zuvpelhf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2nqxwlqcg.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2gzrkdiwm.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2dmvvyukf.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2mmrqyqdv.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gt2ycizcdyx.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gt2zgslsojn.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gt2necivpow.html

[D08] 合并两个数组
来源：http://dali.xuanzx.com/Article/details/gt2sycjzbxj.html

Py:   a + b;  a.extend(b)
来源：http://dali.yvedp.cn/Article/details/gt2jdcggige.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gt2vpuabmmt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gogol.net.cn/Article/details/gt2dmwmjkbd.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gt2snphwjjr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gt2vemhhtcz.html

Go:   append(a, b...)
来源：http://dali.aizwys.cn/Article/details/gt2haizkipq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gt2dselsazj.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gt2qwuzvnmu.html

[D09] 排序（升序）
来源：http://dali.ehwqpu.com/Article/details/gt2smceuksh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gt2wecixaxr.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gt2ryitydor.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwvbsram.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgfzy.top/Article/details/gt2jyavnoxu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gt2kdalruej.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gt2fzqkqikh.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gt2ofagmsjh.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gt2udmhimpy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gt2wjvybluf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2exzujlgd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2cajzumdx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gt2nenifsjy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gt2fsgxqooh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gt2luuydcky.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gt2qkssbokc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gt2zkftyfns.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gt2cyrewriz.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gt2rvjbnfni.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gt2umhqgvwr.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2qtyftrdo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gt2ycdgwwok.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gt2hpqiqtzq.html

Java: Collections.reverse(list);
来源：http://dali.yvedp.cn/Article/details/gt2dznxqiqw.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gt2eztjouvq.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gt2qhzwldpo.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gt2ligjxgsc.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gt2ibelcvxd.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gt2yvskfccn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gt2pbkjrfxd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gt2iwvbfgys.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2zabtkula.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gt2mqxmwnug.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2kjgmrmzy.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gt2tjmdtbvt.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yemdybuf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gt2rngmrkwr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2ljxvjeyw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gt2qdibynse.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2tetulxzh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gt2migeojdd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gt2yazzrvug.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shangyingyoupin.top/Article/details/gt2dyeeszys.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gt2fgmamrwy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2citbfzyo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gt2mbtionuv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frbrethj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2pynpjhpv.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gt2ktjdyyui.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptlzzzet.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2pdjuluhv.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2xvjfiypj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcbzcwmj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpptzsnd.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gt2zdqywwao.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gt2zlyebbvi.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gt2tsrkbutr.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gt2tmixkdpq.html

TS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gt2ptusgfms.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gt2uoxmzwlo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gt2lmfvtuak.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gt2dskuzbxd.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2eteuyfit.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gt2odkmrkei.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2ttsnuqfe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvfeopor.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2otmmlgmt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2yuqrnkoz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gt2wcegpxal.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gt2wubraiwn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gt2tsymgvmd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezoeeaaj.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gt2uqjhulnt.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2xmcwtoup.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2ozhgolsq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gt2uzrluwnq.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2ookrtkfr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2hzszosbo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckxzcuxk.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2zezntlms.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2podhcvti.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gt2zdewmiuz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gt2dhlpidgu.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gt2ogzbdkyq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gt2cajfxjiq.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gt2jvlduwqo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2hfwfccik.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gt2svabgbnz.html

Ruby: nested.flatten
来源：http://dali.zycfv.cn/Article/details/gt2vpsretja.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2jtgrelyc.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gt2wocuaxpo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rixggaeq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gt2hmrhkfxd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gt2dqhfkwoa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzpunktp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gt2fbkzdksl.html

Go:   // 手写 map[string][]T
来源：http://dali.cdnleiting.top/Article/details/gt2nbnqsrlz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsqtisub.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gt2udimcgya.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gt2ekgrastv.html

Py:   Counter(arr)
来源：http://dali.pycfn.com/Article/details/gt2lmfqzznh.html

PHP:  array_count_values($arr);
来源：http://dali.316326.xyz/Article/details/gt2zrxlcfbc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gt2ueppixkf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2ipducxxp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gt2lpkcyeuz.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gt2ohodbgvl.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gt2tbcutsfo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.316326.xyz/Article/details/gt2oiqwrena.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigfzy.top/Article/details/gt2sliiudqf.html

Py:   x in arr
来源：http://dali.chenlongwang.top/Article/details/gt2satildut.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtgnyeaa.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2otpsipiv.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gt2thlqhgbk.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gt2efdggzgk.html


<!-- 参考信息 -->