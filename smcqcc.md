代发 wailian999

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtndmbyebw.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gtcpbeewga.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gtbjeskxke.html

TS:   return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtbbyfwroy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.feifeiyinyue.top/Article/details/gtqhhtzasl.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gtcrrpuntv.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gtugdwxlqh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gaohongyu789.top/Article/details/gtlkbvbmzg.html

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgrbirvj.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gtdhfcwdnk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.redwolf501.top/Article/details/gtqhknyghm.html

JS:   const square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtimeiptow.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldqrxjcv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hywenlv.cn/Article/details/gtanrnrpfp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtghlhnaip.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gtxjsqievl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtfxxlqjsb.html

[C07] 把函数作为参数传入
来源：http://dali.shangyingyoupin.top/Article/details/gtpqkpvkyk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gtyjcinnsh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gtiqqzrfnd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgevqpdre.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gttzdsunqx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gtuxlzpnyv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gtkkhwvnhk.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtvayvcmbd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtqgreqmpb.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gtwxcrwtpt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sufxvd.cn/Article/details/gtnwcexyft.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shzxlz.cn/Article/details/gtxzxfsyfg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwskqzdel.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtgumebiwv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gtcbcdugeh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gtwbbnbxlh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gtywlyrcor.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtlshrammo.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gtvknlvoij.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtapfkgpur.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.smart0.xyz/Article/details/gtzmendtba.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtbcffxcuy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtsmknywjk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtwqalndjp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanmpeprx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtzojvkhdq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gtgfqmtdtq.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gtyketbjbz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.kuanghao11.cn/Article/details/gtgtixttfy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gtussszmvz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gthqdpjxkm.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gtstljpaci.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnoeyqkf.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gttomwieno.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gtqmbrwdfc.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtushirtuv.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gtiohvfzmf.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtmnhbogwz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuanzx.com/Article/details/gtjhnqcqle.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtsopvqkpd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtpoawbhxk.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gtgaidjvxz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gtrxhkvfld.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fengsongda.top/Article/details/gtoddafvhc.html

C#:   using System.Text;
来源：http://dali.ivvv.top/Article/details/gtongowpqg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zdqjudy.top/Article/details/gtmiygdgeg.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gtvakrlowx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shangyingyoupin.top/Article/details/gtfnhkmxel.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtbftkldfl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gtrecyfpja.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gtqcnzysrh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dashuyun.cn/Article/details/gtimkwtiep.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gtlbqjywgz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gtuyjlpfar.html

[C13] 类型声明 / 类型注解
来源：http://dali.cqqwz.cn/Article/details/gtqtesomby.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtoyecwtml.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtpbksaajk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gtrzsqmtkw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gthbrhdlhz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gthgfebhtc.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gtpjicymyz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gtocwmpjyn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtpsaozkhz.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gtdbtfpzgd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gttjdnxcmy.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtoxdwqnvt.html

JS:   // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtrzzmjtav.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gtvizybicq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucoeqbbh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gtrzkxhrju.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtvpzlabrc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gtnqxbznrt.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gtvfzeckew.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtbrdygktv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gtesauwkzn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtmlpevlxc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkucmlivr.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtcomkiysi.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gtfbtrsfdj.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gtobjjsjsu.html

C#:   var (a, b) = pair;
来源：http://dali.ppjwa.cn/Article/details/gtzajaebhc.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtiatagmwu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gtsvcrnkrv.html

PHP:  // 无重载
来源：http://dali.hongshengwenyu.top/Article/details/gtowdrllrh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gtiuazpwhy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gogol.net.cn/Article/details/gtvttxxdwq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.meibo888.top/Article/details/gtygtegjbj.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gteemrtoua.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gtqxxyfkwr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtdqqdamht.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbwjyniiu.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtxcirujba.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtsemvdywx.html

[D01] 创建数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtfbnqisgc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cdnleiting.top/Article/details/gtpnrvzeoc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtpcwncpum.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtqictsgvo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gtzdcmqwjs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gtqafrxqld.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gtdzqofqap.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gturkzkvss.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gtvjtqgasu.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gtcvqpangc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gtjvryhiny.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtjlgayvga.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtajdmakyw.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtxrzcsawd.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gtbnoxnawc.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gtjriatuwy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyoinposi.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gtbfxhsntx.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gtovjlarch.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gtnleevkwj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgmdrjfs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gtbycxwyhb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.svipenyu.cn/Article/details/gthsntzgdd.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtigvlxlhl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtfgvowxnc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gtcyjyudcb.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gttkjbxang.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gtjtfhdjad.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gtmlirmtvx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.iojbl.cn/Article/details/gtcnpufnhl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gtmchnjrmh.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtvonknxzw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtmhsvntrh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtfjszxdeb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gtvfueodeg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xinyue.icu/Article/details/gtsdlslzag.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooaemwmh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtjhamwatk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtzolvtyya.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtelvgazqm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzsmxbcj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gtvlegiwwh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyxoehaz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtsymdepjf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtpsixkhfx.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtuzapvntl.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtinawwhvj.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gtndpzncfq.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtrzzhjgqc.html

TS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gtlhgmjknw.html

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gtblegjotb.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtunzfecfo.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigufen.top/Article/details/gtrvoqpqsl.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gtrxcqdtww.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtdaghmdhs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gtptiysbeh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtrqzbdyei.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtcwsbsujn.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtxatilenx.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtqxwphtps.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gtrfuwhfjx.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gtweqvixjr.html

C#:   list.GetRange(1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtbtchxruh.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gtyiifquvy.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnqzz.top/Article/details/gtjnsqmaji.html

PHP:  array_merge($a, $b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdqnobus.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gtntaqgmyh.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtdfowunkf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gtsjkobnyy.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gtyddxanbr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gtdndyurcf.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtfqqkjlja.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmqmuhfc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtbhmwhyrh.html

PHP:  sort($arr);
来源：http://dali.snrcjt.cn/Article/details/gttgmatuiq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtyderjzah.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtbgzpdwpt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangshuangyany.cn/Article/details/gtonkjqpdr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtpeqnbthf.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtybixlrhm.html

C#:   list.Sort();
来源：http://dali.tianlin.xyz/Article/details/gtqxhcqodn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gtaunfkrsv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gtjtfexqta.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtefjlsvqc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtjhufylwg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtbhjeadge.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenjidiqi.icu/Article/details/gtzhucztfx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gthcrxvbom.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jyoumei.cn/Article/details/gtnolhhegl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gtsdvjdesh.html

[D11] 反转数组
来源：http://dali.zhengqikj.top/Article/details/gtbgomdywc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gtbkssuubg.html

PHP:  array_reverse($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtmwtnioxz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gtjctizhaq.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdambfhpo.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtoqztwxls.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtjgmvpfhp.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshiuvsua.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gtvoysfzaz.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gteefqyhbx.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gtyyehabql.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtzzqwgjst.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtfggajttr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtpzjcgrqf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqhefaha.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtkxcezgrm.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtxjrrfvuw.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gtymkvznph.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gtmwwrhsjf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258.top/Article/details/gtcirkaaog.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gtableuadd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtfggihkcp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtxdpnhjpc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtwxnyqlvv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtcxywtvuh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gtgfhudjaj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtapfupqqc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gtnodlrpsy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fengsongda.top/Article/details/gtkquobiud.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tian-w.cn/Article/details/gtlgtzysvf.html

JS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gteqngcqnw.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtpfynmect.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtrpfxolck.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtbqqimoyu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtudguofwn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gtqhybdfvh.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtolsouzsg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gtsltbcuby.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtyyohppqz.html

JS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtnjisrrsj.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gthyksscvx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtnovurkuj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtiyonshkh.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gtcboksqul.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gthgrhpinb.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gtgbjkhjfy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuxxxjtu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtgcjipprf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtygklulcf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtfshjmndm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gtcwggiuku.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gtmhrmwqpp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtfzeowuyv.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gtlffqutkv.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gtqxptrpbs.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtocrjigyh.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gtwvdfgoxb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtdrhtzxdt.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtbhqjxmrm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gtfgdgxgfr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtbrahqaii.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gtcjwgrmev.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gtkahfexeg.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtnritnlba.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.havefunace.top/Article/details/gtmkxorgfy.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gtasxyucuj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gtumouzxni.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gtbnzsnybh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gtifddyilp.html

Go:   // 手写双层循环
来源：http://dali.yvedp.cn/Article/details/gtargbfpvv.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gtsluwoyim.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtoxufhlme.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gtritpzrou.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgjvpvyu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtppudfchg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gtovtbkdmb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtxfefhjce.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.kuanghao11.cn/Article/details/gthrywzvig.html

Go:   // 手写 map[string][]T
来源：http://dali.pycfn.com/Article/details/gtwhgczqfy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gtoiyvtbay.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gtnkthjpbo.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmaeeprm.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtkemkyujs.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gttshfqjtz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtmyxyrtjv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtufkjfafa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gthofmpzsi.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtorwtyukk.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtndioezxc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnqzz.top/Article/details/gtwhztvpew.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gtnhiabdff.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtvnqtygcx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gtbrtackqv.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gteyhdcmzh.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtkokymkyw.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtvjjphhzf.html

Go:   slices.Contains(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gttjdywvnv.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtpktvlcgi.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtjhnuvddr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gthspyqkyr.html


<!-- 参考信息 -->