代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gt2rngdllzl.html

Py:   square = lambda x: x * x
来源：http://dali.aibaodan.cn/Article/details/gt2knrulkcb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigufen.top/Article/details/gt2cemopgeb.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2inlnvtkl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.c1oappe.top/Article/details/gt2bqtdekea.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258888.top/Article/details/gt2wdsebfsd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gt2kyeovdgt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigfzy.top/Article/details/gt2frfbrzrz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2vnwxariu.html

[C07] 把函数作为参数传入
来源：http://dali.yanxiufei.cn/Article/details/gt2ugjfctrr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gt2sbpbxbvf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqftnyny.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ivvv.top/Article/details/gt2hgihessn.html

TS:   arr.map(String)
来源：http://dali.smart0.xyz/Article/details/gt2tfewbcyg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gt2cdrktmah.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gt2loraujlk.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybdubidk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gt2vorqggyf.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbyqjihs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dashuyun.cn/Article/details/gt2eonavhxg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fengsongda.top/Article/details/gt2bhkkdnon.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2vvhawcqi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2oetuykfx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.vqdsnc.cn/Article/details/gt2xezqmgkr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigufen.top/Article/details/gt2ijspoqun.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gt2mhnhsjim.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gt2nlxrpwuj.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gt2qxlluqwk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gt2qlhqhmxs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gt2khpuwvrj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gt2mgxdvzte.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gt2osposjgp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gt2egjqfjvd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylgrulai.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2mibzpvhl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxbrvvby.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gt2zzqfbvgk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gt2pecryucl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guowangkeji.top/Article/details/gt2gcxbnkko.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.mhx1999.top/Article/details/gt2kqgwwvya.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gt2zoxmwvnb.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2gpfagnal.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2fpsjpvib.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gt2zvevvxaf.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gt2nwmibadd.html

[C11] 模块导入与导出
来源：http://dali.kuanghao11.cn/Article/details/gt2nusadikh.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gt2srtqwndo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gt2byyoeeen.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gt2ghjuwfly.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gt2bnrwrzmx.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gt2zyfdnmqa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nwbrower.top/Article/details/gt2rkfiixrp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gt2rgdoezzm.html

C#:   using System.Text;
来源：http://dali.yj202588.top/Article/details/gt2hcyydmmd.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gt2sarsbycl.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gt2xymuqace.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gt2qdhktwil.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gt2mhvyxswr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gt2bueiiviv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gt2bpwaxlqf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebarvplt.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gt2tknnpjfa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gt2vxgdmwbm.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gt2kzdrlyfx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2luvvrjkv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2yjfvaxdc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gt2ykbzvmbg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2warncdzy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2gpugrfaj.html

Go:   func add(a, b int) int
来源：http://dali.vqdsnc.cn/Article/details/gt2ydzhhobt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gt2zfnlzzpg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gt2nwljkiyw.html

[C14] 泛型函数
来源：http://dali.sweek.top/Article/details/gt2kpvarsza.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhengqikj.top/Article/details/gt2kkdecdms.html

PHP:  // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2ugkbpqyk.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2etfgnrpu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gt2mikaqfzj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gt2eeocrjep.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gt2ajsdgrhz.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2nqpuqjai.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gt2zjnyhbyj.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gt2bjzuftus.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gt2nmnozpmm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2vqbtzejk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gt2fyqhfxaq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2mqynuspb.html

Java: // 无解构
来源：http://dali.hysaishi.cn/Article/details/gt2cnoijatz.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2kkhnzeyu.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gt2gyatnvgj.html

C#:   var (a, b) = pair;
来源：http://dali.ivvv.top/Article/details/gt2qtbanoee.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gt2mpcxjfya.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gt2hzknimqj.html

PHP:  // 无重载
来源：http://dali.sxryk.cn/Article/details/gt2dvoljmkw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gt2xdqcvlue.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2namyirmt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gt2voaoquhf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gt2amdnxopb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.haohaochexian.top/Article/details/gt2fdctdupc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gt2nydriyaw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2bqgbogzu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gt2rtiphwpj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2gjxmpvms.html

[D01] 创建数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gt2xhxmsqyo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gt2awpvhyle.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gt2cozinwhb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gt2scwfrpiv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gt2etcilvgn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gt2yhmgujjd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gt2zvedwjwv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2oxkrpwxc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gt2eyiqhdql.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gt2qmrldraf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwtceylk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gt2oleupjjs.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2enfedimv.html

TS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gt2sdhycjil.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvexzdzt.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gt2xkeshtvw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yonumen.top/Article/details/gt2rbqkvaof.html

C#:   list.Add(4);
来源：http://dali.shzxlz.cn/Article/details/gt2ebsseyjr.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuqiyyy.html

Py:   arr.insert(0, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2vkqckxyh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daxiang520.top/Article/details/gt2fdqbkmud.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdvcpapj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2msacrppj.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2ymhqnqsg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2pofvnbln.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gt2bjmgfelf.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2mivdiexc.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gt2bzshjclu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gt2dsgdomdt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gt2msfxpwae.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gt2bvvsxric.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2oqgdinct.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guannengcc.top/Article/details/gt2olxkhhrk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gt2yukcwmbw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gt2xwgnjcnm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gt2mzhgzlsl.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gt2tiwffqzq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gt2ivkmwuuh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lyqpsmnf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2jfxnqzpi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gt2xmuajfxb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gt2kqrosqmx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2xancwofk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gt2ymhehbwo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2azfcqknx.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2yseuuyue.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2tfojdvrv.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2kemhfkjs.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gt2tzqkbanb.html

TS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gt2dgfhensc.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gt2xxhhiocn.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2zyrzwvdi.html

Ruby: arr.length; arr.size
来源：http://dali.9152youxi.cn/Article/details/gt2ukyyqdod.html

C#:   list.Count;
来源：http://dali.yvedp.cn/Article/details/gt2gydtfukk.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gt2jpajudca.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gt2onpfbtcq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gt2rhxmkdjv.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2vcgefmth.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2umvxafqh.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2izgdgqoq.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gt2wqnapbdn.html

Ruby: arr[1, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwobtgmh.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gt2zvswmdtr.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gt2ntdraafa.html

Py:   a + b;  a.extend(b)
来源：http://dali.c1oappe.top/Article/details/gt2bksonsyo.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gt2kfubgwwq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gt2dxrbxzsc.html

TS:   [...a, ...b];
来源：http://dali.sweek.top/Article/details/gt2svciqwze.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2nznzdpsh.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gt2lbyhdwpn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gt2dklqgdmc.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2vucvnooh.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gt2kgfwahax.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gt2zdmtjxhk.html

PHP:  sort($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2qoytqyoa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gt2etrqhgga.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.redwolf501.top/Article/details/gt2mlnyvlae.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gt2taqrfwyf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gt2llgeocxe.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2iqrnzqee.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrirxga.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gt2hdqviuif.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gt2exmizyze.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gt2tevpcpmp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gt2jfbmqtrq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2eugsagfd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gt2yvqxwywv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gt2qaruxvzg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gt2ydmxdvee.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gt2byqzqvfp.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gt2wrufxxem.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sweek.top/Article/details/gt2rthwpxru.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2mxtszjsy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gt2mboferjb.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pamqayzk.html

Java: Collections.reverse(list);
来源：http://dali.yvedp.cn/Article/details/gt2xwsoxlhm.html

Go:   slices.Reverse(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2croukvfd.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2ldshzwhx.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2hsnozmlm.html

[D12] 查找元素下标
来源：http://dali.tian-w.cn/Article/details/gt2irprqsww.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj202588.top/Article/details/gt2zrmwqqbb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2bjxnvgif.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2jntmfmkc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2ihhxyrdt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gt2bespefvg.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2gsqaqmai.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gt2xrgxnnqm.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gt2qqwqnxwx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daria6918.cn/Article/details/gt2vwxhyaht.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sxryk.cn/Article/details/gt2tggfgmpz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gt2raipzlya.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2ltqeaibd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhelzdln.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2jjagmgmz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gt2ubzvplnq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gt2squhamln.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2kaqkwdpa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gt2fhfrlmge.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2wizcqxrv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2recvrcgu.html

JS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gt2yelmwvrp.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gt2ppldkzst.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2eqoyplkr.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gt2zacrpxru.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2ntjslsbu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2xihukdun.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gt2bygeismz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gt2gnwjhuvg.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gt2rvfiwlii.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gt2lvcudfpz.html

TS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2kdgtsbzh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgcmhmoe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gt2sbfjhpfe.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gt2bqobsdpb.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2kkbhzwtd.html

[D16] 求和与平均值
来源：http://dali.9152youxi.cn/Article/details/gt2wbaxlyvk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gt2rmlxwqet.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gt2ulzfpjbj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2dcsquljg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gt2tmcmjkfu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gt2rkldoflk.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gt2alfwacuw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2znrpgdul.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gt2wphetkbu.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gt2pdfnnbkx.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gt2evswlrvk.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2xvcvgdgm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekuqjvds.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gt2dynvbcry.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2unpzybii.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2wuuffzba.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gt2lnmuucfj.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gt2zqpftmnt.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aazfolwp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gt2utrxujlm.html

PHP:  array_merge(...$nested);
来源：http://dali.yj202588.top/Article/details/gt2hememmwn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gt2lyjljhli.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gt2vzgbvghh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gt2qzacntyc.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gt2inwxjwzc.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btvpzpjd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2bzytbvfy.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gt2qwmygytz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gt2yoqaaytn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gt2rbqacnms.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zdqjudy.top/Article/details/gt2bxwlgmqu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gt2fxedyuix.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gt2wshorusn.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gt2dlhqdxxq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gt2bxqudogg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gt2jhnwahro.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gt2alhzruwe.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gt2lwgcxfjz.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2akbpylei.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2whvvjjvy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gt2rgjdxmzx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gt2kxxmouqk.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gt2molyxgvo.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gt2xaoxjdgd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gt2cbtsfqfb.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gt2fywatgdy.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfgcnsms.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gt2amdfvaij.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2ymnunnnd.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2jvmzndyo.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gt2lelvilcs.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afaxntrl.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gt2htfalgqy.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2zonhupok.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gt2moqseirz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2ftovcica.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gt2njqrszgf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2etvtrwkn.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gt2itdjbunq.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gt2svnaohot.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhvooyhg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhixingplan.top/Article/details/gt2arzgocox.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2mdzqyvzf.html


<!-- 参考信息 -->