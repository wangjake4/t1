代发 wailian999

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtnfrqxibn.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gtpcqmnkjb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258.top/Article/details/gtykjgupxs.html

TS:   return { a, b };
来源：http://dali.c1oappe.top/Article/details/gtfpkbsosg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenjidiqi.icu/Article/details/gtiknjiqvq.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtqzywljce.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gtelzbkjor.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gtkyxagapu.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gtgevytnxz.html

Py:   square = lambda x: x * x
来源：http://dali.yanxiufei.cn/Article/details/gtglbettog.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gtleyyyjlc.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrzrkrio.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gthxqzxzrn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtscgbshhq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gtrckobyef.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gtioowiweb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtodellhxu.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigfzy.top/Article/details/gtuchdvvym.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gtwmrbnwte.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtmcizykdf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gtrjarxyuv.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gtbmwtrxcu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fengsongda.top/Article/details/gtrahuaffg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aibaodan.cn/Article/details/gtqtgeiukv.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gtpxzavrzx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gtmoqnzecy.html

[C08] 闭包
来源：http://dali.guannengcc.top/Article/details/gthastjgvg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhapiczh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gtbsfdpkvv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtrhtpdxwx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtfmlkylgs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jyoumei.cn/Article/details/gtbvoecppa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangdashe.top/Article/details/gtgnvkfsyz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zdqjudy.top/Article/details/gtneoozcto.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtlaarbiov.html

[C09] 递归
来源：http://dali.vqdsnc.cn/Article/details/gtvbqmsiby.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtwfhkfyzl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gtnyartpiy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtxerhefnu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtsftzeinb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtzrdbljty.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gtbswqypbz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtllscvkkl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.c1oappe.top/Article/details/gtagxzcnbp.html

[C10] 变量作用域
来源：http://dali.meibo888.top/Article/details/gtdhczktyk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tian-w.cn/Article/details/gtlusgizdi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gtyqkdahid.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gtxhnrnopw.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gthpaqdgrb.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gtpzzwcrmo.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtbsikvqwx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shuidangran.top/Article/details/gtxlmyfjzf.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyvhdymt.html

[C11] 模块导入与导出
来源：http://dali.xuanzx.com/Article/details/gttlimljcj.html

Py:   from module import func
来源：http://dali.jinqigufen.top/Article/details/gthddyxdnv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gtcnqskvyk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gtliipucwf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.birdmap.top/Article/details/gtjyfsqiby.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gtnrjjobfj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gtkynhbhcl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gtppvzeiiv.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gtpnidvvys.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gtacjmogcw.html

Py:   (lambda: print("run"))()
来源：http://dali.gotoacloud.top/Article/details/gtqoythavo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gtgprqtxxm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtfeakfgzy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtqcedvksj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenjidiqi.icu/Article/details/gtwzvmfkcz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gtibbbppmw.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gtcybkrcij.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtvauztlkn.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gtsnfhxizm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gtxznevysq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtiuhgaoud.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fzhhl.top/Article/details/gtxszxlmil.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtclqvjslm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtepnjtrkr.html

Go:   func add(a, b int) int
来源：http://dali.zhiwuduotai.top/Article/details/gtjnpedetm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigfzy.top/Article/details/gtrwlnjxxe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pengpengdd.cyou/Article/details/gtnsyccupo.html

[C14] 泛型函数
来源：http://dali.fengsongda.top/Article/details/gtfqwautnw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cheryme.top/Article/details/gtuyuptmcm.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtfwbzpdpr.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtmwlyugjr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gtujjwxndv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gtgoimxrbv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ehwqpu.com/Article/details/gtsypkkjgb.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gtqxxwtzux.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gtnezorxfw.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtndmldbdr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gtlnxfmber.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gtemszvjvw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtqilsorig.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gtrcizgcod.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtguazvfgd.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gtpspoburc.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtthvshstp.html

C#:   var (a, b) = pair;
来源：http://dali.hywenlv.cn/Article/details/gtntljzshc.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gttcmspagi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwugqdycn.html

PHP:  // 无重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gterbmgtji.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gtuibrhjgq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gtglquuiop.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtvuwacgen.html

Go:   // 无重载：用不同函数名
来源：http://dali.ybcxt.top/Article/details/gtkuqdxqaw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gthuvsmuvm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sweek.top/Article/details/gtbnlyauns.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtdnpsyfrd.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gtwrwpiamz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtzemrzyro.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtzluusdfy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gthzgrxxja.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyxkcrjn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtenbgjscf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahxpnphf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxmjyqio.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gtptajxrvg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258888.top/Article/details/gtbhsalxrw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gtlqtkgfky.html

[D02] 追加元素到末尾
来源：http://dali.guannengcc.top/Article/details/gtxgxfxdal.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gtjpydeaxh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yonumen.top/Article/details/gtyleaqyxi.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtczxcinuz.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtrzqhzbjw.html

Java: list.add(4);
来源：http://dali.aizwys.cn/Article/details/gtplgvzugk.html

Go:   arr = append(arr, 4)
来源：http://dali.nwbrower.top/Article/details/gtbdjgoyly.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ydzc1.top/Article/details/gtohhmbkji.html

C#:   list.Add(4);
来源：http://dali.daria6918.cn/Article/details/gtfyaweghp.html

[D03] 在指定位置插入元素
来源：http://dali.hnxiangtu.top/Article/details/gtjorlbzzu.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtzxsbnxgb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gthjrcfiqe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuanzhike.top/Article/details/gteioqhukl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtjuzsycrf.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtneqelfet.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gttaiknjng.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gtlzrtrner.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtejjkedmf.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gtcugsiytf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gtaueonrvh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gtcsuyonlp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtkrfwynqh.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxinkj.top/Article/details/gtaqawbocj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gtbsmbxatq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj202588.top/Article/details/gtgohzgazw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gtxdvlddhj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gtzexwznyu.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gttryoloqv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcojvhjsh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gturzgqhmq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtrsgbambu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gtdrmtfyti.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gtkkeimbag.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtwdevyveq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gthctvqccy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtorjpdlyf.html

[D06] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtusqqopes.html

Py:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtowscjcsg.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtdmishpsj.html

JS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gttifaqtvy.html

TS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtvcxduzvg.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gtqkxshvei.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtxhmycbey.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtqzktmeug.html

C#:   list.Count;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzroxamve.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gtcajfgyea.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtinsgmtfb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtrvnimzyx.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtfltydwmf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtuesebxdr.html

Java: list.subList(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtmxnbxnaa.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gtfbnvxtpc.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gtylczufrc.html

C#:   list.GetRange(1, 3);
来源：http://dali.xinyue.icu/Article/details/gtsmvjoiue.html

[D08] 合并两个数组
来源：http://dali.wangshuangyany.cn/Article/details/gtvzdriqpm.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gttqqdvtxz.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gtampjbkxg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gthzihclsf.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gthwjbevyu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gtguqhalim.html

Go:   append(a, b...)
来源：http://dali.dashuyun.cn/Article/details/gtlwocjdci.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtbrybtmyc.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtmwilucpf.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtvccemigj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtzvgjbihq.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtyrqrhfxp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gtndnqnlwn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhoulong.xyz/Article/details/gtfqnkoyou.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gtkseippgp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtqaurymqx.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtrhcwmuyg.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gtrxttxsyh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gtvxygjsxc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gtoujcfclz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gtbgolslpb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtyipbkcfu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtbgjuccbx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gtepgtabsg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gtaomoqcqj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.mhx1999.top/Article/details/gtnxqsihhr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gtrfszhuct.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gtubsltevf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yanxiufei.cn/Article/details/gtteqtoigj.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gtlcncjfxn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gtkxgyrrwl.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gtptndwovo.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gttlvmjjaz.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaoclrabi.html

Ruby: arr.reverse
来源：http://dali.cucudq.cn/Article/details/gtqnvptdip.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gtztrtildu.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gtfmnaqohu.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtojrctdbn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtidqyzkwt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtpvymutrl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtsmkbchfs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gtzzakyqld.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gtgsdqhcys.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtrnatglyh.html

C#:   list.IndexOf(x);
来源：http://dali.yueranfly.top/Article/details/gtqnnerjyh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gtswyugymv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gtxqhccqje.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gtdioqsgfa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtfukwksvi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtleppfare.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtswwqmzih.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtumkyidxx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gttkwrhbvi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gttnmihiav.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gtcznxgeah.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxinkj.top/Article/details/gtelkrqlgk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gtgvhzugtr.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gthwojdhtu.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtqmpzzxgt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gtyddpzzed.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtecwwpjnq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cashguo.top/Article/details/gtulnulroj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gtcfddchew.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtwlszpvtd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtdqplksrh.html

PHP:  array_unique($arr);
来源：http://dali.yvedp.cn/Article/details/gtqddqvexi.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtnyesjscs.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtmbkslttk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtgysxdtwb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gthnbputhp.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gtkyrmqfnr.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gtjysiwmew.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtuemwsivc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtkhbvmvlk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gtrwocszws.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtgorhslmb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtvhpheunw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gtdvsldgzk.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gtirdjnajq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gtyanlxxpb.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtsrxxghir.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gtvermfcxc.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gtfkrycygr.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gtxofzewyy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gtpyxiqtuc.html

TS:   Math.max(...arr);
来源：http://dali.gaohongyu789.top/Article/details/gtnuujidhj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gtvhqxdyee.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtndbouasf.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gtkniwaqef.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtctknzmxg.html

[D18] 扁平化嵌套数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzmxpxvb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gtxnlcalcs.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gtbftrbfuo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gtoubjvuso.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gtiswhvyhw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gtsxbheaqm.html

Go:   // 手写双层循环
来源：http://dali.yvedp.cn/Article/details/gttsyvbkyu.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwppjobd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtfltfsqwz.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gtmjrdahvo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gttfxzwsmw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gtqgblbtgy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtvalqizag.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtahantnvt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.quarkkingdee.top/Article/details/gtrvpxeyij.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gtfufeflkb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gtxrvqnvvx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtsdpzbfut.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gtswgylidw.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtskqlpqmv.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtelrhihqt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtljqdzmsa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtsnmrtdxf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtmudddtys.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gtgdsdtzie.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gtouqmuxde.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtllwbmsok.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtdbzzpsvx.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gtaldnedac.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gtetmocxur.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtinubmjvm.html

TS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtyjqnmtdg.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtukuygsuy.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gttjsepnmr.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtvkngvhxu.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtrgnwrldb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gtlppioiaf.html


<!-- 参考信息 -->