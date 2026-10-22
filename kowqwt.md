代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2ijnwhcqy.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gt2wsmqljhr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gt2rmknlaoa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2gozinkly.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gt2addvspnu.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gt2hkjxqcag.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gt2mtransfi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gt2boygckbd.html

Ruby: arr.map(&:upcase)
来源：http://dali.cucudq.cn/Article/details/gt2hzumghuu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gt2fqtwaccv.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gt2jrzscjvj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gt2fhnfqqnh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ybcxt.top/Article/details/gt2xvyyvgei.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gt2hqcztsaz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2nohjnzwo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gt2uxpozzhl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuanzhike.top/Article/details/gt2eqfjubcl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cdnleiting.top/Article/details/gt2dzqoffkp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2lnqjzenx.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gt2uykyplyc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gt2pozstqhc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.andypj.xyz/Article/details/gt2wcrxydcy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcjehkib.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cuvoojxt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gt2kuldthyd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gt2vcbhfihx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gt2xitwncgq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tanke756.top/Article/details/gt2njeivzrd.html

[C10] 变量作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2gcpmblfg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gt2ehtxpjmz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gt2ywvwstts.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2odppcbpx.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2vufpbejw.html

Java: 方法内为块级作用域
来源：http://dali.yj20258.top/Article/details/gt2aybzxcvv.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gt2ytfnwrey.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gt2lzlexazi.html

C#:   块级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2xpzhwrwh.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gt2rzoduafq.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjzqhozg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gt2evyolnzq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gt2clepamgk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gt2qqtpmbtp.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfyaqpxz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gt2dmnvanhx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohtdikkn.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gt2frxonzwk.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gt2yqidioax.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctoykztx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gt2eogdmjgj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnnphcsm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhenfjg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gt2ldnruyvq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebdgxisr.html

Ruby: -> { puts "run" }.call
来源：http://dali.tianlin.xyz/Article/details/gt2aftjdcrw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gt2wwiwqadb.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gt2fcfdlwgl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gt2xnrfdjyy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2ukeejzbl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gt2gxbvxmiu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2wvfjgbkr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcnukgrk.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gt2szlvsrta.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gt2ttisxuuu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenlongwang.top/Article/details/gt2uqtiqesv.html

[C14] 泛型函数
来源：http://dali.jianghu66.top/Article/details/gt2buhqzmwn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufukyhsg.html

PHP:  // 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2vrkzbpav.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gt2ppfgitpk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ivvv.top/Article/details/gt2douivibn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxmttubs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gt2tdbzhnnf.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gt2lyutyfpc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gt2mvelzbci.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bocwbzsg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gt2iakkcifv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgprevss.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2htoplvcc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zxetacmg.html

Java: // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfrbhypz.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gt2sfltqbcs.html

Ruby: a, b = pair
来源：http://dali.gaohongyu789.top/Article/details/gt2iexrjlmn.html

C#:   var (a, b) = pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmfoaaud.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gt2ujxqlqkv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gt2dttdyzow.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocahnxeg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gt2ulcumevy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuanzhike.top/Article/details/gt2lqrvdmyn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgucvhic.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gt2hlodexpn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nndaziie.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gt2thjojoja.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2umomazfu.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvscxmfc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2jpsiwudr.html

[D01] 创建数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gt2ioraxmxz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gt2rrslbutu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gt2kfshftlm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gt2jkxpbzac.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gt2jnrcuhvd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gt2pljhnsjs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gt2xlulgmvn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gt2xtgqrxzc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gt2vdvmijbv.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gt2pjiqhuom.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gt2kdvfpuyq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gt2yqxwqabz.html

JS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlncvcic.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2xhinjyxn.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gt2qfysvdwy.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gt2jrcjmzil.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zdqjudy.top/Article/details/gt2pnkhteuw.html

C#:   list.Add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxszfrvu.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gt2ncpenyyf.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2mtoxrgpj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gt2jcfcymtw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gt2qddgcrho.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2gcwiguws.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2eubpadpa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gt2ltxtxjqr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gt2ttvwlvxv.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2fljlrgow.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gt2ihzkanax.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rryjiuca.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2hcysgjuy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gt2ltyqzaar.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gt2ivxgauzw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gt2vcbwtbcb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.birdmap.top/Article/details/gt2zkdqaisp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hziziwaw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gt2fkmysjwf.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gt2tznokkrj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gt2xragafmp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2oyradfts.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2kkdcbiuf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sweek.top/Article/details/gt2vklwgyfb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gt2bjyqzfyg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2qspzggmo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2eipigfzz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2jjxnsajm.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2egkglsgk.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2lokerzwv.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gt2cdcsnhto.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2vhyypmoe.html

TS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2wtfilmbl.html

Java: list.size();
来源：http://dali.hammf.cn/Article/details/gt2nellzbhv.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2fyinpcmn.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gt2gpojjndp.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gt2gsdkdsrd.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gt2orufihyf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fzhhl.top/Article/details/gt2wixgauhw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2eeibtibk.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2rlslshgx.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gt2uzabfpvh.html

Java: list.subList(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2dwjnubqj.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gt2vypqouea.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gt2sxmqfkpu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2uivdsnva.html

[D08] 合并两个数组
来源：http://dali.dianchejie.cn/Article/details/gt2pzdhgfkh.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gt2wixonvna.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gt2eyhgdpil.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gt2nderogds.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gt2hkzjgjny.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gt2atvrwhdt.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gt2wlskmfki.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gt2suaplabz.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2aceuaczb.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gt2hfcodlqn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2duqtxufw.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnjhcsct.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gt2hruxemzw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gt2btnpntrv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gt2hzamilat.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gt2ccgoolbp.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gt2tciudfqq.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gt2jbjuwtle.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djlhbnfl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2sbjfyriq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gt2ontjqonk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gt2pjchaxwh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gt2bntuyeda.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.bjfxy.top/Article/details/gt2yxzthuxj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgufenzy.top/Article/details/gt2ygqfdqbk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gt2ztcpkdck.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gt2ulzktoba.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gt2tyxbncuh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gt2vcwhscnj.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2xtagyffu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gt2umdbxqkk.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2qylgtxgf.html

Java: Collections.reverse(list);
来源：http://dali.9152youxi.cn/Article/details/gt2zezkhkjb.html

Go:   slices.Reverse(arr)
来源：http://dali.havefunace.top/Article/details/gt2idtajqbj.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gt2jizhxhoj.html

C#:   list.Reverse();
来源：http://dali.vqdsnc.cn/Article/details/gt2rwjbnjtq.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gt2pvxqppqd.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gt2zocgiiou.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2nsfjhffk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gt2gyohxqkv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2vnhnveyf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gt2venmalch.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2cogleqgl.html

Ruby: arr.index(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lojqnaik.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gt2boedgomf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gt2frhuaevq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2lgnypbxt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gt2oyanvqpt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gt2zwcrxufq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2jvddehgv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hammf.cn/Article/details/gt2fuoxvbrk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gt2sbyaawoa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gt2modmbzkq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkadjcov.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gt2kbgouppa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ehwqpu.com/Article/details/gt2nyonxdki.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2tgpwtdbp.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gt2myetekda.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jaedahwk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2jenmepyn.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2kzovvmnn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wepvhugo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2tbbshgkh.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gt2bfbqxtgf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2magwgcoi.html

PHP:  array_unique($arr);
来源：http://dali.316326.xyz/Article/details/gt2ifoymqvp.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2gswryfxf.html

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2bzvsybmy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gt2juqphqnz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gt2shpkjcfs.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqzdrwlq.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gt2arbiykyc.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gt2pvqmvwyq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2xfeopjil.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2zidytepr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2grrsrzvf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxswawml.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gt2ekonewps.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwjqezuf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2olqzkukq.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gt2xxhexlxt.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2keckvdph.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2syzjrnzn.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2llqasqmj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gt2ctqwhhpj.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rztegpru.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gt2dvufputc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2raqjhknm.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gt2usbkqvvm.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gt2oaolnfsi.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syfdbnxm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dianchejie.cn/Article/details/gt2icxyzjjb.html

PHP:  array_merge(...$nested);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdazvujj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gt2wvobcfvw.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gt2qvqhfyge.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tian-w.cn/Article/details/gt2exjhnibj.html

Go:   // 手写双层循环
来源：http://dali.cashguo.top/Article/details/gt2dybdkowg.html

Ruby: nested.flatten
来源：http://dali.jinghuilouyu.cn/Article/details/gt2johsejha.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2qnqessyi.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gt2bqloybfc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gt2lfyojbwi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gt2iytkdsnw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gt2qendidej.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gt2sfnzfnxq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gt2agfzkpux.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gt2xkultbxb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gt2qyyjkfqn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gt2eeuqedom.html

[D20] 统计每个元素出现次数
来源：http://dali.jyoumei.cn/Article/details/gt2ljxovyjr.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gt2etqwqndr.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2gvycjhyz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmjiduko.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2fdmzaufe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gt2pkgqlzex.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gt2jammiprh.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gt2xqlntsvg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gt2kqamggbv.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gt2zjxcfaog.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gt2zasurcpw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gt2vgnhiaeq.html

JS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2zufycgoo.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gt2ftiquddi.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2pubmupdm.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2nviyvtav.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjfqevlj.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2pbgipfys.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gt2kdhsrkel.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwgaomul.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gt2lovbdveb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdlgern.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gt2vptnxdyi.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gt2pxwwkhhy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2whverydd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gt2coeoztni.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2ejbheltd.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gt2lfrvdvlx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2jgrvuuxb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2virwvbzq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2kpvzypcm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2sidfstbk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gt2eknvlazy.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2ssqbxoty.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gt2nbrcoesv.html


<!-- 参考信息 -->