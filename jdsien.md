代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnqzz.top/Article/details/gt2dcoscrsz.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gt2vhouumfk.html

Ruby: return a, b
来源：http://dali.cashguo.top/Article/details/gt2vshqbnmy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gt2hxofedai.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gt2rvkygfvp.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gt2vecovpit.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oerkeqwo.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbbbcwve.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ivvv.top/Article/details/gt2afomkhnm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sxryk.cn/Article/details/gt2puqsiupv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yojapqon.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gt2nmfrglhx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2tdnzjxrj.html

[C07] 把函数作为参数传入
来源：http://dali.yanxiufei.cn/Article/details/gt2ddyvehjn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zdqjudy.top/Article/details/gt2mjzanaot.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2xrccmjwa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gt2nibhgnxo.html

TS:   arr.map(String)
来源：http://dali.zhoulong.xyz/Article/details/gt2jefdatqh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj202588.top/Article/details/gt2gxfulqat.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvjpudfb.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gt2vwuapixs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gt2aokdxdbi.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gt2irffelrb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gt2nenwbned.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gt2ttmjvxnp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2pdebkjqz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2qobwrfpo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gt2auakxmyt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgfzy.top/Article/details/gt2vjveagxh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gt2lpjfkkwm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2tbpuwfem.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gt2eeeygpvp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gt2wwfrdaky.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gt2atnzsdfr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gt2mifjebtz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gt2wgaftzxh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gt2hohgcngv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gzhubu.top/Article/details/gt2qtbxrxbk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gt2tcuqkntb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gt2giahberv.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gt2qpnibenq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuxming.cn/Article/details/gt2kztrgzvy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gt2doayqagf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gt2rqftjogw.html

TS:   同 JS
来源：http://dali.wangdashe.top/Article/details/gt2maqywcrv.html

Java: 方法内为块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2djozitxb.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2dxzbixul.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jlsjyb.cn/Article/details/gt2wlxracps.html

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2wshtmcxx.html

[C11] 模块导入与导出
来源：http://dali.cdnleiting.top/Article/details/gt2vqcbwdnz.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gt2qjvxtbru.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.redwolf501.top/Article/details/gt2cpjomqpx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gt2jvbyewij.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldcgwktr.html

Java: import java.util.List;
来源：http://dali.sweek.top/Article/details/gt2yawizrlb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmrprbbl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gt2yrvrmxpx.html

C#:   using System.Text;
来源：http://dali.hammf.cn/Article/details/gt2msjryzuh.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gt2lkjadxzs.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gt2doakfgbj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gt2nlmstvwk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gt2ehsqhjur.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdxxqmym.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.svipenyu.cn/Article/details/gt2rieccbec.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gt2zukhhrpx.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gt2mmlmzudu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sweek.top/Article/details/gt2ibpwhmdc.html

[C13] 类型声明 / 类型注解
来源：http://dali.shzxlz.cn/Article/details/gt2oxffugkg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gt2fgcfvfhq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2zttnppdq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuanzhike.top/Article/details/gt2gpcmfjdv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2anlpxzdu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2yiqbdouz.html

Go:   func add(a, b int) int
来源：http://dali.andypj.xyz/Article/details/gt2qfoggqab.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.birdmap.top/Article/details/gt2coflydsu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gt2ujbfdvab.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gt2fblphwcv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gt2segzpazx.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntmsnalh.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2ygslamvn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gt2kqhcaaqk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zujtlout.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gt2kbjxrlwp.html

Ruby: # 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xohbfctz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gt2smbzkyeg.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gt2foxjjbzi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gt2zntzxcxb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nipifems.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlthjlie.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2apbqpyqb.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gt2dknujwpg.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gt2woimurpb.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gt2oljpyzcy.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gt2earhokvb.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gt2ecnhomws.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenjidiqi.icu/Article/details/gt2ediogume.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gt2khfkjpzq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idtihipf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvzfyqyh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ankuaufg.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gt2ktxydwqs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gt2zfflardw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhnmcffj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2lkqmniim.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2muqdzycd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mtzbaxep.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gt2asvkpvjt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2joxehjtl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjxhqgkq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gt2thnqueac.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gt2wbmayake.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gt2fwtrbxfe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gt2eixmiwht.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jianghu66.top/Article/details/gt2cykqnpsh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gt2dghvnrre.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gt2hdpxpxav.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gt2sdksegvy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gt2jkyhbrxv.html

JS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gt2gfsjucgo.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gt2bgxbniel.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2seyvetmd.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gt2arwinpzk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sxryk.cn/Article/details/gt2fopdujeu.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gt2mqiewlkc.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gt2ancpcrzh.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gt2cfixsade.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sysykeji.top/Article/details/gt2gdagsqbw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gt2pfajnwxw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tanke756.top/Article/details/gt2pvkzllhx.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2oqfciwma.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gt2qhpfysdf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gt2ispzanvv.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2qsmjiblv.html

[D04] 删除元素
来源：http://dali.hnqzz.top/Article/details/gt2xajuhwib.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gt2ascsulnb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2nbsoyjar.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uldjfggj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gt2kiimoram.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gt2miwtpzdk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgygzudi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gt2fvwfapte.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gt2xixqvoua.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gt2kitcvfix.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2blnsbdhe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2xhjwzdys.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2wtjjmaeo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tian-w.cn/Article/details/gt2xgfeozps.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jllnfzhp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gt2actkqluf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2guwvfrco.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2kagfeeos.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2knogrybk.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2jsexcxni.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfhrbrov.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2uipypyvs.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2youmoclb.html

Java: list.size();
来源：http://dali.ppjwa.cn/Article/details/gt2bpomjvgx.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2xtjnfdnt.html

Ruby: arr.length; arr.size
来源：http://dali.xuanzx.com/Article/details/gt2guxjsgpq.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gt2ogxmzbsg.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gt2lftdpssl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gt2tzzqhbxr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2wslcppzx.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2ahcmfutr.html

TS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2rdptrlre.html

Java: list.subList(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2iawbqywz.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gt2gjobnuez.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gt2ozlxgtzm.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2balpppaw.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gt2icxxqbvn.html

Py:   a + b;  a.extend(b)
来源：http://dali.xziqi.cn/Article/details/gt2vkvnvpfx.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gt2tkzphjug.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gt2ymxzsitc.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcedlegi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2syfkwsad.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gt2gtiiipje.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzwyhriy.html

C#:   a.Concat(b).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2gxxpxkoa.html

[D09] 排序（升序）
来源：http://dali.yj202588.top/Article/details/gt2nippnwon.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqfwxtwg.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gt2utojvcee.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gt2hjojrkxe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gt2kysswoxc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gt2rpiwmcqv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2xmrdrvrg.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gt2zzstfagf.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gt2ymiztzix.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hebbjlde.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gt2rztnwusp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gt2ycnkdctf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gt2meiuhejl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gt2eycelzmy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gt2noveixfg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gt2pgpmlulm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gt2ogqpyqoy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gt2zedxvyla.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gt2wykjzwio.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ybcxt.top/Article/details/gt2doasuzmt.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gt2mlhzuxqq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gt2upbvnhuw.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gt2vnidpdlw.html

Java: Collections.reverse(list);
来源：http://dali.zhengqikj.top/Article/details/gt2fwwwhmog.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gt2bvgtdihb.html

Ruby: arr.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2ukbozbgt.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gt2zbtnqsal.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gt2owspotac.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj202588.top/Article/details/gt2yywxgvze.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gt2ywxjiwqk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjlhtbco.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2zwtwsvga.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gt2rfunibsl.html

Go:   slices.Index(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2splawqer.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gt2apkuvdoy.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gt2bfzuakih.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gt2mwqtaseo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gt2fknggwsv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gt2hcivfmxr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2pgwqprht.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2zpynzfea.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yonumen.top/Article/details/gt2fclimwnz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpmmltt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gt2tptnhilq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2lrogvpux.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ybcxt.top/Article/details/gt2duxvdeso.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2jqbjfjni.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2igxlctye.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gt2aurmcuco.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2fkputtgh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjfjortx.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gt2rnwofyux.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2khbavtfd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2rfkwrwxv.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gt2gusvdkjm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2zejrxwqc.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2risgetrj.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gt2ijnkncpn.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2deqzptcr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gt2mdhcewcz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gt2tpwbymxm.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gt2vtvatfjp.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2sguxdybp.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gt2bclowaij.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2hqkhvzog.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2juddvnvg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2dzshatrf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gt2xkeflapa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gt2raoyodiy.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gt2dhjesgox.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gt2cokiafft.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gt2jzlegvlc.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gt2axhufohl.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gt2ocxwdadt.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gt2vqpzrthm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gt2dldcrehl.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gt2iulmallj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2oethxdnw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gt2qnggbfkt.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gt2xwevwvtd.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gt2ruiijgxw.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gt2secgjvsv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gt2lrwlagbl.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gt2lcjwrdpv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kozhhugc.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gt2agyzrceg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2seedzndb.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gt2kzmllrxi.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gt2zrvyilor.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2rchhlbcs.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gt2qsayypwh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gt2wswawivb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gt2isaqvmas.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gt2suoabxdh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gt2ppoonfib.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gt2xzcgmdpd.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gt2sncjcyzz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gt2ltcudykm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hammf.cn/Article/details/gt2ioahqosc.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gt2miaooqoa.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2towfcpwj.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnnoswkh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2rgueufya.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpcupfsp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuxming.cn/Article/details/gt2iepdaakq.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2acleifsl.html

Ruby: arr.tally
来源：http://dali.hnxiangtu.top/Article/details/gt2qrihnkyk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gt2mosycfdm.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gt2jcueajxh.html

Py:   x in arr
来源：http://dali.sxryk.cn/Article/details/gt2qylmfewl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gt2atdnmrco.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2iatvnkak.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2jjkdhnvw.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2adhbevzu.html

Go:   slices.Contains(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2wmycgwvy.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2fdqflbpe.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2dzpepigm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gt2qvptmuro.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gt2vtevwuvf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gt2ksbnmpax.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gt2teaprcse.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gt2gpfqqzam.html


<!-- 参考信息 -->