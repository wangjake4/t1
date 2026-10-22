代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.gaohongyu789.top/Article/details/gt2bdwoprur.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2gbrgszud.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gt2mzmblqfv.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rasaiqrp.html

Py:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gt2fseexxto.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gt2hcpckpzt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxxisjfn.html

TS:   return { a, b };
来源：http://dali.havefunace.top/Article/details/gt2kjtvmpay.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gt2tylybwkz.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gt2enthkaly.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2bakzrmay.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gt2eteyxsrl.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkcllrts.html

Py:   square = lambda x: x * x
来源：http://dali.ybcxt.top/Article/details/gt2cjzewwpg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhongyouzk.top/Article/details/gt2wsxyrrfx.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2oaebmrgw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gt2cllsujcn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2poqgxznz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gt2yhrchnuv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gt2ocxmnryv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2odabkcgd.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gt2ixbtsokm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ybcxt.top/Article/details/gt2wrnoykfc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2fdfriats.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gt2cbahvcee.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gt2rrpcolhj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwjvtxwz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gt2obhcgwim.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gt2ttceztff.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gt2jvxwxzjd.html

[C08] 闭包
来源：http://dali.jiagoushi.top/Article/details/gt2tscmmktq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gt2khoefzga.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gt2ndydcoev.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2bndaenqk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2tluvvoca.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yueranfly.top/Article/details/gt2eliviqst.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gt2ykphcsxt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwrerfy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gt2cjildlon.html

[C09] 递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkatmdjr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gt2wphlfdrt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnqzz.top/Article/details/gt2mhufavxp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gt2mbgtxfck.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pasewmgm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuxming.cn/Article/details/gt2gfgqpeba.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gzhubu.top/Article/details/gt2uucspqfe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gt2fgopzlpv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gt2fojhaxnm.html

[C10] 变量作用域
来源：http://dali.cqqwz.cn/Article/details/gt2exwuohko.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gt2xmoaqgdl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gt2xqairdja.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gt2iepkwvoy.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2jvhymlhg.html

Java: 方法内为块级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2rktkvivq.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gt2mesxdibn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llimsnsl.html

C#:   块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijwwpoih.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gt2rcrtwlvq.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gt2khokzrmt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pycfn.com/Article/details/gt2fdxqigzf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gt2afisfeey.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigufen.top/Article/details/gt2owtaggzq.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gt2cjemrpfy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gt2fuauwftu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gt2cfhfjfwu.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpanzyoq.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gt2fmqtifka.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gt2wpayyogf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gt2brozqzhc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrgoztax.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gt2uorizkew.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gt2cksrweuy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gt2gnbuwxbx.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gt2yswcslhe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sweek.top/Article/details/gt2uoftpnry.html

[C13] 类型声明 / 类型注解
来源：http://dali.jianghu66.top/Article/details/gt2iruukabx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2wkttkljm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvxzihmr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gt2gyfupjxf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2ckyjklzf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2yicsopkh.html

Go:   func add(a, b int) int
来源：http://dali.jiagoushi.top/Article/details/gt2cgxkgafo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gt2frvrgiqo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gt2zhyeznnl.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gt2tmltteqd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gt2viyzgzaf.html

PHP:  // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2dmxlcfar.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2wdldruod.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gt2synbgwvq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gt2qqxbfmfl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gt2rnbjsrhl.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2ubvtvmhi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gt2avzarwol.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehrgvamn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gt2qrhmubrx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gt2zczouktz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gt2powamqbv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2tpghtemj.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gt2lcntdyqq.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2ifumiaab.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gt2qifdbzlo.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gt2ltowkpkb.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gt2yyzywjig.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gt2hspnokia.html

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gt2nwdxtbus.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gt2bxvoezsh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gt2hgjrzidh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxwvzpl.html

Go:   // 无重载：用不同函数名
来源：http://dali.sxryk.cn/Article/details/gt2emsbhour.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktcurzlp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkzohans.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2hltodoru.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gt2dkrpnofr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2gyhrbvzw.html

[D01] 创建数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gt2hixstgli.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gt2vklvquoc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuxming.cn/Article/details/gt2zfbkisma.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gt2swyqpsfb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gt2ayrzscge.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gt2zepnxozx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gt2hmpchrgb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gt2abomteqi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj202588.top/Article/details/gt2dabtfnjc.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gt2jsndpvpt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gt2esyphnnq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gt2ttbupweb.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gt2xxorsncn.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2oqsmkcnf.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2duxikvpi.html

Go:   arr = append(arr, 4)
来源：http://dali.andypj.xyz/Article/details/gt2hzogidau.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gt2qavuzigl.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gt2tpwqxqhy.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gt2jlqikcmi.html

Py:   arr.insert(0, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2mkybphnq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gt2rfirujyb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hysaishi.cn/Article/details/gt2nijhygvj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2wjxdldnj.html

Java: list.add(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2ozhwfdfg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2fpxxrkwm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xziqi.cn/Article/details/gt2ioqvbbfq.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yofmvxxb.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2efngkxnq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gt2fiwxcljd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gt2ieqhhwzg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wifukmau.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigufen.top/Article/details/gt2mimlyppp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2gkvvfbzz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhongyouzk.top/Article/details/gt2kbuskaww.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gt2eethufkw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gt2ntmlovdr.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2eobbftzd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2fimimbqc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gt2dqtnzyug.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2hynqpqmr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tian-w.cn/Article/details/gt2lvewyndm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gt2zskumjgo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gt2tzaibxrr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gt2lpqqnoqc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2gygbzoxu.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gt2ddagmeaw.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqplwhxy.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gt2fmvjiocx.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gt2vhimgohw.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gt2rtkytmkg.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gt2yleozbou.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2lkskzuhx.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2whqpyqjx.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gt2dzpuuhmp.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxausmwr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gt2yhjjrers.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2dfocxyoz.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2imqnrbpo.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onrfyajc.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2uedrpfrw.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2asrcpxlv.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2kbfzhsck.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2nbfusxxa.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gt2nrabulud.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gt2kcwfglac.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcfrapjv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gt2mwyoxair.html

TS:   [...a, ...b];
来源：http://dali.ybcxt.top/Article/details/gt2qcfyicuc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gt2cnxdiknm.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gt2kgkosxzn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gt2gzygnpag.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2qfiuwaof.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gt2ixnsvskp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmjrewok.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gt2ecwtnogk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gt2sxriqexr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlgpnnuj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kervswwe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gt2bbzecncc.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2tzxundpk.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gt2zpahqtuv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuanzx.com/Article/details/gt2rydmthjk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gt2qwadjeok.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gt2vlolalzx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gt2xxonztzt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2rakwodgs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gt2tjhixxjf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gt2majkctmh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gt2hbaqxkpi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gt2flwlakwx.html

[D11] 反转数组
来源：http://dali.hammf.cn/Article/details/gt2yrbynqff.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xroszdgk.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2ttjgfjow.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gt2xocgwyiy.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gt2lrrtgiwj.html

Java: Collections.reverse(list);
来源：http://dali.yj20258.top/Article/details/gt2imqmidmz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlrwsupd.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gt2bqvadite.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gt2qzobyvzl.html

[D12] 查找元素下标
来源：http://dali.daria6918.cn/Article/details/gt2rgwdyjcj.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2bpoyawgx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gt2iwonhhkn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2itkwqbdn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2xfymslej.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gt2akmczoto.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2uztutshm.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2rbgdgohg.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gt2ezogpgxb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gt2wazxiiea.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwxlzwkt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gt2itkeccmo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gt2wyneyabj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2fqvnyuwh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gt2wnflirbd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gt2zuuuaiuq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gt2nafrbllp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2ukporful.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gt2yjmhthsg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2vxblbbkc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2puxzynea.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2natmjtcw.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2xhgmbssf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2iccqbyyd.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2mycmecuq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2zpgtdslo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2gbnnzvgo.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gt2ykjaifwp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2iernmwcj.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2ykzshcxf.html

JS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2bzlnxftj.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2fyekrvyo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gt2wrdbbdjr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gt2jqaxwtzy.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gt2qeauasrg.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2eqmpchau.html

[D16] 求和与平均值
来源：http://dali.hammf.cn/Article/details/gt2hfjsaklk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2ugllzovy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2uhyckimv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gt2brbqrkee.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2jhcuxyln.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangdashe.top/Article/details/gt2hcvonczi.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gt2hhuzlclc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.birdmap.top/Article/details/gt2hukvysda.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gt2jdhivzge.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gt2imwesxag.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2gyljmahi.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gt2xcpqjnad.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gt2hwmsxkxg.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gt2rrmxzvga.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gt2dczpoehy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2vaenkmux.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gt2ocmzhjdg.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gt2fnhbvyqn.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gt2gblwadul.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gt2ibvesufw.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gt2iimgbsrh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyqkvtaf.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjkvoolz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gt2tbatucvq.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijhblbjp.html

Ruby: nested.flatten
来源：http://dali.fengsongda.top/Article/details/gt2emnfxnrp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2qunsuxux.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2jdkilpbu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gt2tmkygeqq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gt2akpvwwpg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.svipenyu.cn/Article/details/gt2zjblodix.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gt2ywftrwxy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gt2uzflzyvv.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gt2vzcbzuun.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gt2fnfsrmll.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gt2jgoblako.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gt2nifbxlos.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gt2avqfevhu.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gt2ictpvbgz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gt2cktrzqex.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2vrjtoobw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cucudq.cn/Article/details/gt2yewjyaor.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gt2ovrvnuah.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gt2woemkwra.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gt2spjasfgr.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gt2itreecyr.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gt2gztkfalv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gt2lbhftigc.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2xdcmiwfk.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2gnjyxtsm.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2hcoajxcg.html


<!-- 参考信息 -->