代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2ozuommmp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gt2tlwnbwgs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.andypj.xyz/Article/details/gt2mvlssckr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.c1oappe.top/Article/details/gt2qjrxtliu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gt2aupsxuuq.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gt2hwdjmnue.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gt2zbgshznn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangdashe.top/Article/details/gt2mhadasux.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgtlyabo.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gt2mouwmhdv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gt2kkrrmynq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fzhhl.top/Article/details/gt2vjoecwkj.html

Ruby: arr.map(&:upcase)
来源：http://dali.ydzc1.top/Article/details/gt2bfengeyj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gt2fazrmdrj.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gt2ydkkotgz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gt2npbzawcn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.9152youxi.cn/Article/details/gt2wfkkiawj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2rlbbqqbw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2noqcfthh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gt2zbcxjcmt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gt2obpxcqle.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gt2ztccbbie.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rttzoajz.html

[C09] 递归
来源：http://dali.quarkkingdee.top/Article/details/gt2xwvzpxgz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouotozuq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdqlznp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gt2tvkrnhhx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfqbbtje.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gt2lknmnvfo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gt2rlbhfilf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvsrjpkp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gt2eadlzxsn.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmxdvgjj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gt2edcvtcqz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenzaomai.com/Article/details/gt2ibbrsssc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gt2mwyyntwt.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2smrwsvtn.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2dwpqwoec.html

Go:   花括号块级作用域
来源：http://dali.yueranfly.top/Article/details/gt2jyafwqdm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpufqegb.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2gplryoff.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gt2tsgusxhk.html

Py:   from module import func
来源：http://dali.hnxiangtu.top/Article/details/gt2krzsfxsn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gt2wspiuaop.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yongpay.top/Article/details/gt2arajzdjn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gt2bipwrhcn.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gt2ndyqxrkf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gt2qitsdwzs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gt2uxbzjpsc.html

C#:   using System.Text;
来源：http://dali.yj20258.top/Article/details/gt2funvwsie.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gt2otmxgapk.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gt2qtalwjpk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxododxo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2sslvhbnl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2wurpfhji.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gt2byrrrfgy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gt2xyobuovc.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gt2imrxqwyj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2budkgezy.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gt2yoaojfhz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gt2qbsefghw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gt2cmvvnuyc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gt2oleenqcw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2izicwflh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxjutxzq.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gt2fthedgew.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gt2flcpijgm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shzxlz.cn/Article/details/gt2augghklh.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gt2bviiopcn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gt2mvsvstza.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2gjcbatqf.html

JS:   // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gt2auaaisui.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gt2ugklnkyu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzdldurk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gt2iktbrlvb.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2avcxidyo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ivvv.top/Article/details/gt2csbplbyr.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gt2risqghdu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gt2nyprvbcl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cheryme.top/Article/details/gt2wqiombcg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2aurimirj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gt2weaujzim.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gt2rzubfzmu.html

Go:   // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gt2shqkxfvz.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gt2yqngqjsx.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gt2hhzqdbgf.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gt2couhzbzf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzdfbhcq.html

PHP:  // 无重载
来源：http://dali.xuanzx.com/Article/details/gt2dvxpqpsx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hfpthk.cn/Article/details/gt2kagxhwtw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gt2fcmbsjwv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avtjhoyo.html

Go:   // 无重载：用不同函数名
来源：http://dali.fengsongda.top/Article/details/gt2zkymtllk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gt2sbubcazc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gt2enawxwlv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2hrfbfysr.html

D. 数组 / 列表 / 集合
来源：http://dali.hysaishi.cn/Article/details/gt2dfltsbmm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2kxbtopwm.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imwmyvpr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjknzvvv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gt2jcltliop.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gt2tvutfkjc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gt2nmtoeilg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.smart0.xyz/Article/details/gt2tacswbve.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gt2dfheedih.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odtdvsdk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gt2cktngjum.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gt2vjktgjrt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thravufy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gt2wpdfvjmn.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2jurcqcjd.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gt2eqxbybrl.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gt2qliouxlc.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gt2tdrbukvw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gt2pqvshvdv.html

C#:   list.Add(4);
来源：http://dali.xinyue.icu/Article/details/gt2qkfxfplb.html

[D03] 在指定位置插入元素
来源：http://dali.9152youxi.cn/Article/details/gt2kwdkjgbj.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gt2meggscrf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gt2qzbpzycu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gt2emoykflz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gt2lbhuitsp.html

Java: list.add(0, 0);
来源：http://dali.shuidangran.top/Article/details/gt2rptnmcdz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2skcksmev.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gotoacloud.top/Article/details/gt2qmnnyaba.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2roaakyxy.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gt2eceqpepe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gt2oguenege.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gt2dsznjfts.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gt2hpqhcfxr.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gt2enomtmlz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gt2nvmavmek.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gt2ktisfbyw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gt2bgvicwny.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gt2akvyhpgw.html

[D05] 访问与修改元素
来源：http://dali.pycfn.com/Article/details/gt2ffjgliqk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gt2disnpuji.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2togxusah.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2rffrjjlo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuanzhike.top/Article/details/gt2atixuevh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gt2ikszxvkn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2dbrwlvwm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2xrguebxv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2sqvfdrrt.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gt2kaukowhw.html

Py:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2knyufuwl.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqzdeefx.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2yplvmqkw.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gt2hbfewnuc.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gt2bunlfqxz.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2vrhklofz.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gt2ttmfnzgs.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gt2spfhexxn.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gt2astsandn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ydzc1.top/Article/details/gt2xczbwtgm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gt2bsdzjkah.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2minrvwdo.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2sxfkphza.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2wjlcgcqi.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gt2tzhpnitv.html

Ruby: arr[1, 3]
来源：http://dali.aizwys.cn/Article/details/gt2huqwgkjd.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jskkanxj.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gt2rpwswvwe.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gt2beroyyel.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gt2dcjdvyah.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gt2iuktjttd.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gt2ohydywqe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2lcfyaatq.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gt2pcndflnf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gt2cmxkxnvp.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhuspixt.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pclymbio.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gt2nnwbwzyp.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gt2trauwumo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gt2pplzunnc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gt2fktwdqmh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gt2lowrvnbd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2gkmfyqzg.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2wwvobxlq.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gt2lujnxgam.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhmuwrxm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gt2pvyjolgq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gt2gaenvihb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gt2ybvjxyzh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gt2rysdseyy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gt2bfveuxpb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gt2ywmtibvz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmfjuklz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xinyue.icu/Article/details/gt2qpjgrpvc.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gt2fusjghpv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gzhubu.top/Article/details/gt2eiyjtdte.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gt2veietkeh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shuidangran.top/Article/details/gt2wtdlbcqz.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gt2dwxfnbin.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gt2uypaygou.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xanptaab.html

Ruby: arr.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2omnffbos.html

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gt2wecgqcol.html

[D12] 查找元素下标
来源：http://dali.yonumen.top/Article/details/gt2ihisszhi.html

Py:   arr.index(x);  x in arr
来源：http://dali.xziqi.cn/Article/details/gt2nzrvgwrd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gt2gptvewzj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gt2bkpfcqrj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gt2sienznxe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.birdmap.top/Article/details/gt2kvioluqi.html

Go:   slices.Index(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2siildzsa.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2cjmafzeu.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gt2gwsshtqk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gt2hzcxejxb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fovyxmby.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gt2bgxpfrka.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2fvqyujmi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gt2vypabtan.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gt2xwxnbcvv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenzaomai.com/Article/details/gt2cjbuethu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gt2mgweoast.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2ldsmsxac.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gt2sgypspto.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gt2zndkqetg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2jjitkixx.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gt2huhidyqq.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2bhxygorx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2dlshgvqc.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gt2bllzszza.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2lbfhnafz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2mawdnbav.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gt2cmwiitko.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2vqtopnfy.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gt2ghwxhamd.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfneoiqe.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2fwhrqtni.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivvldrpk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gt2cifzcmpp.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gt2ynnpyvnt.html

C#:   list.Distinct().ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdqubjuo.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gt2raqpuxaf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwuqrce.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2lhgpieme.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2oqddvhwy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2wphvvkus.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gt2grftthks.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmyxinfc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gt2clqeuuqq.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gt2ypnwlvws.html

[D17] 最大值与最小值
来源：http://dali.smart0.xyz/Article/details/gt2vxboizni.html

Py:   max(arr);  min(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2wzeekucy.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2riywqaps.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.svipenyu.cn/Article/details/gt2dltcxezb.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqukhmlu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gt2ibejoxhk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2dktwbyyz.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gt2wcwttzdq.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gt2ejlwuumh.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gt2pxeiparr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gt2pxjaxivu.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gt2jjhohtom.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gt2eiqeqvsy.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gt2exiccecj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgpzlpsu.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gt2nfsmldwx.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gt2qmbmdtqi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2djastqjl.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gt2ushiatjp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daxiang520.top/Article/details/gt2jjaclxvr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sysykeji.top/Article/details/gt2lcdunezc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyawckx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gt2pelxxpki.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gt2qsqmpxsf.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigufen.top/Article/details/gt2begrnhye.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gt2epxamjfh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xziqi.cn/Article/details/gt2xoysouqv.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gt2hiqurpfm.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gt2kduumpas.html

PHP:  array_count_values($arr);
来源：http://dali.daxiang520.top/Article/details/gt2yghidxzk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2kffsxrzf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gt2fcrsgopc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gt2kqruhjhc.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhabxisw.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gt2vldvbfnx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gt2zwlbwirz.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gt2eczdnfnn.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gt2nqtxkgsa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gt2hcwtavqi.html

JS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2mghbtgvo.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gt2bnyehvkw.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2eflpspni.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2apymsxer.html

Ruby: arr.include?(x)
来源：http://dali.guowangkeji.top/Article/details/gt2qwjrefra.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2anpiuqhd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gt2azbzeapo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gt2kaovwazl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gt2jmoiaqab.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gt2zktqdlee.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gt2xihodgng.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gt2hidbplxq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2eihlvjte.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gt2cufouier.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gt2uuggitbl.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gt2txjmpges.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2pingmawj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gt2qimnxyst.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gt2whaujbwl.html


<!-- 参考信息 -->