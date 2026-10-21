代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtrmldlbox.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpulsqlhg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbnjisas.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cucudq.cn/Article/details/gtzybudqnx.html

Go:   // 无：用配置结构体参数
来源：http://dali.ppjwa.cn/Article/details/gtqbyojhvw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtstdwnwsl.html

C#:   f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfasazhnw.html

[C05] 返回多个值
来源：http://dali.9152youxi.cn/Article/details/gtqpgngtof.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gtvsmdting.html

PHP:  return [$a, $b];
来源：http://dali.hongshengwenyu.top/Article/details/gtofsfgwyi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xylfe.cn/Article/details/gtsluwazvu.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtgspnndxz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gthyqkekbm.html

Go:   return a, b
来源：http://dali.yj20258888.top/Article/details/gthncuhmyr.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gtlopfhmzs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtmkhmixlu.html

[C06] 匿名函数 / lambda
来源：http://dali.gaohongyu789.top/Article/details/gtnxcmvdpg.html

Py:   square = lambda x: x * x
来源：http://dali.yangfankeji.com/Article/details/gtrskljvlb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuanzhike.top/Article/details/gtldjdlech.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtgsalhkqo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtjmcxxrvl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gtjguknmzs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guowangkeji.top/Article/details/gtecgrhapc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gtflrzhnir.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtmviserbk.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gtmqyiqvib.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtbxwhaopy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtjszgrqug.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gtpnxhgdss.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtfxgmiytv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtjvcpdfkg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcctpkpw.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gtlufnawfm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pengpengdd.cyou/Article/details/gtyohricxo.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gtkylbtmjl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gtyqizumik.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gtcnmzmyxo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtasixctgp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmyzzeyu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdnizvdh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayubkliy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gtmpfpridw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtrwdiwbba.html

[C09] 递归
来源：http://dali.quarkkingdee.top/Article/details/gttccrycjv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchlgepcz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtmxajkzbj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gtopdktvcp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtajmffhqh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cashguo.top/Article/details/gtkutuvxjm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gtzxholqwv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtvpdtjdtv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gtvkpawtxl.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gtdeuqwbuo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwesavxpj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gtdhbuckbz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtpmfpqcef.html

TS:   同 JS
来源：http://dali.sweek.top/Article/details/gtoznxxwny.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gteczftumt.html

Go:   花括号块级作用域
来源：http://dali.yvedp.cn/Article/details/gtdjvzxezw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gtwknkzeij.html

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gttdqcyqeg.html

[C11] 模块导入与导出
来源：http://dali.daria6918.cn/Article/details/gtozpkjeew.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtsailllyd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guowangkeji.top/Article/details/gtbvljsaiw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtilbewler.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtskwoqona.html

Java: import java.util.List;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtsxizfl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yanxiufei.cn/Article/details/gterrhljrb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gtqqyohozm.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtdfhoiomr.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gtrgqdrbmq.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gtzhiyyyfl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gtskglvxpk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtbdlqsuhz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gttbfehozy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gtgtytxdtm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj202588.top/Article/details/gtffbcerqa.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtadvjrlyo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sweek.top/Article/details/gthjzfqiwj.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gtmpaqlytn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ybcxt.top/Article/details/gtgxjbnplp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtiwfeehbh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gtvxyxvstk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtpbrpyelb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtcfrrrtgl.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gtzaysuxjw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gtgivhroun.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gtbvbbhudy.html

[C14] 泛型函数
来源：http://dali.sweek.top/Article/details/gtwurwikue.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gtejudtyuq.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnylqhun.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtdujwepld.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gtvkxwmqcy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gtocmhdndd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gtvmjlrcaz.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtxzoqhccv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtmpoinrqn.html

[C15] 解构 / 展开参数
来源：http://dali.cdnleiting.top/Article/details/gtqpkecxaj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gtayfqqbbr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gtirqnfywi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtnkdjvdob.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gtlwqleuts.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtsdfdhgfq.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtruxlhyps.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gtcxbqaluk.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtpagbwugk.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gtxbxxmhxo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gtuqfuttvo.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gtqpfoenug.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymtwjafr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jianghu66.top/Article/details/gtpqijjrbl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gttekbeomg.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtsriobvig.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtrzxvgabg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gtwyfopvbs.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhhbtrlr.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gteveuyelm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthelxdacl.html

[D01] 创建数组 / 列表
来源：http://dali.hnqzz.top/Article/details/gtaqkdzozx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtlvssglok.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtbzmettdv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtvzsqvgwv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zdqjudy.top/Article/details/gtvxlmztah.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gttloyedcd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtqeatoqrk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daria6918.cn/Article/details/gtrcsqljwt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tanke756.top/Article/details/gtmlxzmwja.html

[D02] 追加元素到末尾
来源：http://dali.yvedp.cn/Article/details/gttnayahbc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtqfvtwsvj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gttzwmgbhn.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtchizmlhn.html

TS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtinynovly.html

Java: list.add(4);
来源：http://dali.shzxlz.cn/Article/details/gtlmksjzfe.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gtbzcrpnfn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gtarhkcxmq.html

C#:   list.Add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtewstpvaq.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gtmeepardm.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gttcpdosss.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gtvwkrsoah.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sweek.top/Article/details/gtvpuouivd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gtitdlkosd.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtcgjbrdip.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cdnleiting.top/Article/details/gtwhzkanry.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gtqmdruetq.html

C#:   list.Insert(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtsqtbuehl.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtjjhswsxa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gtjfzagmfi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtqjgoeqsq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gteqvczlzt.html

TS:   arr.splice(0, 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtikelluzb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gtfrtyfofa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gtzjlpfjfl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gtqsicjzhg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gtqegejslx.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gtkterbvsd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokixesib.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gthwskjzoh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtgbksdsjb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtvtijnmia.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gtabggqtaw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtxezfndhx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtstkqzvyw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtxfdyuhmj.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtnfbmgwem.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtfanqicnx.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gtkbyiudms.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtgiwbzhai.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtwrnnplse.html

Java: list.size();
来源：http://dali.yonumen.top/Article/details/gtvwtspyge.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtuspojppx.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtrtlhdrpc.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtfeusdtyq.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gtmpzagjia.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuanzhike.top/Article/details/gtgeingziu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtunzujpel.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoagckia.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlukdzdf.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnzupyjp.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtaknzmnfx.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gttsjswjyt.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtjlxdadks.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtzaeanmvx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenxzefyr.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gtebsdxnrc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtugaitsed.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtkzneoeyj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.svipenyu.cn/Article/details/gtqbvqtgap.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtxxxobdne.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gttfeiodxt.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtmefxletv.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gtrzayfuyd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtrrttzazw.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gtyvfmccpn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gzhubu.top/Article/details/gtfpezufuc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gtlhauiswc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gtxpcirqdx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtnzyaigru.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtmiocawsd.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtgjwcczoc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gtzqyhanan.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gtqedcmrfc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gtqbkbvwoi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtsqxrqgre.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtatuxjkmx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258888.top/Article/details/gtticifezk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gthisdprin.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gtihjnxqqt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gtqlffqkrj.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtusmazofq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtzswgioxm.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gtgghgorvv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxinkj.top/Article/details/gtvlvfddjm.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtncgvdfrr.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtoevgmxuw.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gtybfslybf.html

Ruby: arr.reverse
来源：http://dali.xinyue.icu/Article/details/gtuqakjdmx.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gtmxjjhest.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gtsmknfbsd.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gtfivoyqre.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gtcqwrhmiq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtamqixwtl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtsebynaoi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gtahkcqhmb.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtazaibjic.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gtagvyndzm.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gtbkwjxlsh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtkgtaabcc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtohlaopyj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gtenycqyyu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtsstwdclv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtraycwmkb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gtzqlwtytl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gtosyywpqg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guannengcc.top/Article/details/gtigbzagtj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtrhepfvkc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gtihtusymz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenzaomai.com/Article/details/gtkktpjcoc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gtabolwgey.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtgyboaqtm.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtbtwugjqo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hysaishi.cn/Article/details/gtrgcadlgm.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtnjdkmrbx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gtrzzeygfa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gthwifemra.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gtycyzsqgk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gthncbbxcj.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gtidunrmzq.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtlslibaem.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtyhkgryks.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gtphuzsput.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzacrrad.html

Ruby: arr.uniq
来源：http://dali.havefunace.top/Article/details/gtstamduxh.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtuglbwxsm.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gtvkruxqsh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gttjskvodf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gtcqhqdrzj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvksxobe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtuncwtetr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gtxwwngnyb.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gtfujcuhgs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gtkaivnquy.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gtsmcyyklp.html

[D17] 最大值与最小值
来源：http://dali.aizwys.cn/Article/details/gtiohcgvwt.html

Py:   max(arr);  min(arr)
来源：http://dali.yj202588.top/Article/details/gtnhclmmqa.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtjipiefao.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gtynnqdnun.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gtpkjiwyjk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjoovdff.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcubxubmc.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gtzpivcseq.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfojuxaa.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gtyomvawcg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gtawfecqvc.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gtpotwwkez.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gtdrkjqllj.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtbtmnwlqk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gtvndrnpsm.html

Go:   // 手写双层循环
来源：http://dali.gotoacloud.top/Article/details/gtlceaazxr.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiedklox.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gteovbqhjl.html

[D19] 按字段分组
来源：http://dali.bjfxy.top/Article/details/gtqbmpgzhr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gtersnohpd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gtwdafavdl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtkdqekoxa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtspwnwwbz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yanxiufei.cn/Article/details/gtiewdsguu.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gteopqecbk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gtywuaxihc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrpzxtas.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gtwazjnyck.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gtsssyydek.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtrwgpwbik.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtdqoqgtcm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtbimxeszl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtixsjhcen.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gtsvvqjlzy.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtttnfncat.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gtgbzzhkqt.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gtuhzwqqnr.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gtahpdczim.html


<!-- 参考信息 -->