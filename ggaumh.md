代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxinkj.top/Article/details/gtmrtctbai.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gtnvhwdjbl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gtmjhrions.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gtftlcggzb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gtwvjmitil.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtyekvrrqd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gtqgqbmoeb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gtbhqrming.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtocubjyfb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtmsnzxmoe.html

C#:   f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtzxsuiiuh.html

[C05] 返回多个值
来源：http://dali.tian-w.cn/Article/details/gticmygplm.html

Py:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtbadpqaba.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gtdrnskhpe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangdashe.top/Article/details/gtcqslklek.html

TS:   return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtvutbzuuy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daria6918.cn/Article/details/gtgyykixpy.html

Go:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtrwhyxuvk.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtijamirlc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gtqyktxebf.html

[C06] 匿名函数 / lambda
来源：http://dali.yongpay.top/Article/details/gtvvtxsrdv.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtieqpidpq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gtnokbaxkx.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtrmaqkbxs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtgdpffoix.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cheryme.top/Article/details/gtshknlzfu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xylfe.cn/Article/details/gtugxbkobi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gtvtmosnej.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtplnbqkik.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gtkbsrbnxy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtxybripnm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pycfn.com/Article/details/gttilzalii.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gtmfxyttxo.html

TS:   arr.map(String)
来源：http://dali.nanxinkj.top/Article/details/gtnwkmmoqb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.smart0.xyz/Article/details/gtwssuuatf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gtravbnvhw.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gtrisaxklu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtdyhrpuub.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gthvbhkldi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ppjwa.cn/Article/details/gtolbjphif.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gtzgjqdckx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gttqzetaae.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtawjsiuha.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yueranfly.top/Article/details/gtslfrinrz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gtpxmnbbzi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ppjwa.cn/Article/details/gtvdifdtat.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtmezdzuao.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gtlczhpxhi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtbiychoxb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.316326.xyz/Article/details/gttqdhirvq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtlnttoyul.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtecmumpkp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cashguo.top/Article/details/gtctzfazzu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gthmwmeafr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtydaaxytf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtsxdjgzak.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gtgljamfhq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangtech.top/Article/details/gtkozcpxkf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gtirzuolrg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gtqoesfbcn.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gtmznkfhxa.html

Java: 方法内为块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtunlsolzd.html

Go:   花括号块级作用域
来源：http://dali.zycfv.cn/Article/details/gtetbddefy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gtmxamohie.html

C#:   块级作用域
来源：http://dali.fzhhl.top/Article/details/gtlwdusqdc.html

[C11] 模块导入与导出
来源：http://dali.daria6918.cn/Article/details/gtfffioaur.html

Py:   from module import func
来源：http://dali.0kj1m.cn/Article/details/gtwjjadhhr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuanzx.com/Article/details/gtaxbtourr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gtcpkzgshx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gtqsgtgaex.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gtnywuslux.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtmgyeiagg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtwawosicj.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gtsvqnmcxr.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gtdldwbcya.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtovwfgfvx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jlsjyb.cn/Article/details/gthucyjtnn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtwkawhwkm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtmhqdzila.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sufxvd.cn/Article/details/gtycqskwpa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.snrcjt.cn/Article/details/gtspxgfalh.html

Ruby: -> { puts "run" }.call
来源：http://dali.fzhhl.top/Article/details/gtbsudstug.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuxming.cn/Article/details/gtqjgwcarc.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtttnjfkrt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtlbrahkng.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtuhcintst.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258888.top/Article/details/gtwshxamcd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkdendnxb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtgevqdydk.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gtucygadfa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtpyqzkwox.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dashuyun.cn/Article/details/gtvcpkjuaf.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gtfzpkzqku.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gthwumkpvy.html

PHP:  // 无泛型
来源：http://dali.sweek.top/Article/details/gtfrzcxnje.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtazzpskwt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gtgissybst.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gtimksjjjy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gtbnmgaphn.html

Ruby: # 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtylqqcuxd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuetiantiany.cn/Article/details/gtmfybfcis.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gtuymbnfje.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtudfeozre.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkrmshny.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyvgkmuod.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtmmpgfhzu.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gtzpnssvdf.html

Go:   // 无解构
来源：http://dali.c1oappe.top/Article/details/gtmzozbxgh.html

Ruby: a, b = pair
来源：http://dali.tianlin.xyz/Article/details/gtfsqoyybr.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gtiroifvjw.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gtpsjfskqb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtvgluprvt.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gtnsdzkdkv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gtgjddiyzw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopvjjzkl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtrrjgsvxj.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gtoalhpfgg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gtcnxlbfqu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gtkyzrzplk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtufowkrdd.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtucedbeqt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgtgjqjnk.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtcquubczr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtlyoxulst.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sysykeji.top/Article/details/gtddcuukqt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cashguo.top/Article/details/gtmpnrszkv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gtftyarxke.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gtwjpweqff.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gtlaaubdmi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gtmcpaeiuo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtenkbhiht.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtrhutzcio.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtyixchmed.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xziqi.cn/Article/details/gtjprjmlmu.html

JS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gteulcjqmc.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtgpsdkkch.html

Java: list.add(4);
来源：http://dali.shzxlz.cn/Article/details/gtqeapkine.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gttryqxwet.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangshuangyany.cn/Article/details/gttoxnnynx.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gtbersnoir.html

[D03] 在指定位置插入元素
来源：http://dali.nanxuanxn.top/Article/details/gtfaqcezbq.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gttcduglsn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gttoxcbxvd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gtutcyhuww.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtejjssnmj.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtefojmkay.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtlvxauxui.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guowangkeji.top/Article/details/gtqofirpin.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtqdnxcisy.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gtooaxfxgo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gttkojpbcl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtdxqkbuzh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gtyniabixu.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gtwdufxbbj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gtgdkthpyk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.vqdsnc.cn/Article/details/gtsvrgswyt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gthayvpehd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gtojwdsgcy.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtplsnvhep.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtdcecvokf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtddtbmbeg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtpnocwjtf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gtzkvyoiur.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gtqsrygycs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtgdfxumeq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtyeetqfeg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtqrtqkqvv.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtukvluzda.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtevzrirrv.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gtuypkylmp.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtdeoyjqmk.html

TS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gthhgwprqw.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gtyudcrkqt.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtbkpxpopc.html

Ruby: arr.length; arr.size
来源：http://dali.sysykeji.top/Article/details/gtfxteqsks.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gtmplhtlsu.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtmtejvwui.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gtmkfckxng.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtgrohxgtr.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gturewtlsa.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtahczexio.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gteengermo.html

Go:   arr[1:4]
来源：http://dali.xuetiantiany.cn/Article/details/gtlckwcwsp.html

Ruby: arr[1, 3]
来源：http://dali.nanxinkj.top/Article/details/gtulftuflj.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gtmhsmsozl.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gtqazoausw.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gtrbdpusgb.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gtkjayqhzq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gtbuhudjcg.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gtdpcszksd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gtytrbqxin.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gtqiwinnph.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gtoykttvtd.html

C#:   a.Concat(b).ToList()
来源：http://dali.cheryme.top/Article/details/gtsyobwdhz.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gtyfuubhfp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtjkwhrwrz.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gtznhzhffo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.feifeiyinyue.top/Article/details/gtgxobfqum.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtbvldhtco.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gtxvslpyqd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gttpmxtviy.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gtxhhfvozb.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gtddlvpqeq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gtqlwelyjg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtupibpead.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gttglphsca.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtkgifmlsm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcqhkgoh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gtenritred.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gtmnuhzbcx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gtxrylgprj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dashuyun.cn/Article/details/gtplblxasx.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gtikttyrek.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gtjrmrtqnr.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gtlgkpqise.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gtvynfiown.html

TS:   [...arr].reverse();
来源：http://dali.sysykeji.top/Article/details/gtxkpeccvu.html

Java: Collections.reverse(list);
来源：http://dali.nanxinkj.top/Article/details/gtrgovdrve.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gtenbszsbr.html

Ruby: arr.reverse
来源：http://dali.wangdashe.top/Article/details/gtasavulez.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gtnpllrpkx.html

[D12] 查找元素下标
来源：http://dali.xziqi.cn/Article/details/gtgqftncyd.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqlqrxhw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtyewpqpug.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtjuqbxyxd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gturnlocxh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hammf.cn/Article/details/gtksjotnnh.html

Go:   slices.Index(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtgxvgjgrr.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtzuynngxd.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtmtydznuw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yongpay.top/Article/details/gteosfquod.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ppjwa.cn/Article/details/gtjtawqpwf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gtdystzpsq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gttgzkvylk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gttkjfsyml.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gtnbwnokzv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gtanslrjcr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gtkrmofgwc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoinycot.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gtufingcos.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gtkleptmbt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gtbtruyvrh.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtcupsuqvo.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtpnjmseoc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gtvrlukfaw.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtaoqrkcqg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gttscxzzvm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxizgnie.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtnawwwaxb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtlikwlnfz.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gtwddyzxsh.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtbjxuxqqx.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtdlrrqvol.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gthttwqnyv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gtzlirnvkh.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtdguryziy.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gtixbjzywg.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gtfpgqbumc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtzslztscq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtuesetckt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtsizwcrqt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtgpajlxkg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gtopymfgmm.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gtpxswyhkj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guowangkeji.top/Article/details/gtyyfiiddo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gtoriwposj.html

[D17] 最大值与最小值
来源：http://dali.chenzaomai.com/Article/details/gtfrlvwstr.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtumrhricx.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtuuwazdit.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gtdxtmplvi.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gtxrbnshcv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtmgnryqbe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gtlhgteedf.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gtljzjnyxe.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtjbozexjw.html

[D18] 扁平化嵌套数组
来源：http://dali.fzhhl.top/Article/details/gtsddqyelx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktnwvggf.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gtnibuukxw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gtgvfkpywb.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtlqwociiz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtrofocndn.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtmizgskms.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gtaukawlsr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtguddknib.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gtffmbtldq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtgujnllvp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gtirhjraqz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gttsknnfoh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuvsytwo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtxvcymqqu.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtqjvamgcs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtuaepdajh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gtkvqbxmaa.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtpqgjnbiz.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gtsryvgypf.html

PHP:  array_count_values($arr);
来源：http://dali.yj202588.top/Article/details/gtbtzpxzgo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtwqozxuzv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gttfhapoop.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gtyzmfpjqh.html

Go:   // 手写 map[T]int
来源：http://dali.316326.xyz/Article/details/gtqkvpuorn.html


<!-- 参考信息 -->