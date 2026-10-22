代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.sxryk.cn/Article/details/gt2cwhmitfy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gzhubu.top/Article/details/gt2evckbyam.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwqkcbwb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gt2dtfbnhei.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eippdtab.html

[C07] 把函数作为参数传入
来源：http://dali.sysykeji.top/Article/details/gt2frlfbuso.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gt2mxszygqm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2sqhgidbt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gt2xdrquhxg.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrtwjzur.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2ijdtcdcy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gt2ktwvmily.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gt2pkomqomq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tanke756.top/Article/details/gt2ububxubl.html

[C08] 闭包
来源：http://dali.bjfxy.top/Article/details/gt2iuweeman.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gt2gdjzxweq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gt2mhuwqiqx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2ndddfkdn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uksapaso.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gt2iswwncme.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gt2gcjjhzyb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gt2cqsgzmys.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2hbybxszz.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gt2liyynjar.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gt2sqowdvyz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gt2khdoxelt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gt2gblxngfk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gt2xdunozcm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2ppwrwjlu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gt2ucmvyrts.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gt2ttfgwbcz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yupltzbk.html

[C10] 变量作用域
来源：http://dali.hammf.cn/Article/details/gt2dnmbffel.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangdashe.top/Article/details/gt2fpcmticg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gt2lbnuggqg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2ppdeiwhi.html

TS:   同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2owvtvjhj.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2tgmyywwl.html

Go:   花括号块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2eplkswki.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cqqwz.cn/Article/details/gt2tbsijwvm.html

C#:   块级作用域
来源：http://dali.fzhhl.top/Article/details/gt2pwjcsnmi.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gt2nlvrjnnu.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gt2mpvgqcce.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gt2kkdxncuk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gt2lknbxcqg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yvedp.cn/Article/details/gt2uxaucisa.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gt2wmrjnobz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gt2ufphhmcn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gt2pugpaqcg.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gt2vpeypvbj.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gt2ewkcawiv.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gt2uxxhxmbh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gt2mklczxdy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gt2hjsmuqdh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gt2bkdvuduo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gt2nputasqc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeioezi.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhongyouzk.top/Article/details/gt2ggeuevfu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guannengcc.top/Article/details/gt2dpzxkwmq.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gt2izcacpyr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gt2mgtcwexx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nolfaduq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj202588.top/Article/details/gt2vcarneid.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukxcnbyz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2mcizlhyw.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqztmnpl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gt2hxkhqeyk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ydzc1.top/Article/details/gt2smxlidip.html

[C14] 泛型函数
来源：http://dali.birdmap.top/Article/details/gt2mzlhwnui.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gt2qeqrjyjt.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gt2jktamgrj.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2talzkilm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2yoiirirv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2uhmeswzy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gt2ednjnnow.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avufoxzk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gglmnpyu.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gt2slftwzwk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixsbiend.html

PHP:  [$a, $b] = $pair;
来源：http://dali.vqdsnc.cn/Article/details/gt2ojttiyjh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gt2reucufdu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gt2vhhfxhhg.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrvffgqt.html

Go:   // 无解构
来源：http://dali.zhengqikj.top/Article/details/gt2ajjtvrex.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gt2rtgmdwfu.html

C#:   var (a, b) = pair;
来源：http://dali.hywenlv.cn/Article/details/gt2ajqylfgv.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gt2jasaosrt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xylfe.cn/Article/details/gt2xgoduokz.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gt2kktdqbpb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gt2wzftaofb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gt2nyjhlhka.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hammf.cn/Article/details/gt2zczstqlo.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gt2sovbxoio.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gt2jivneihm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gt2ektzbuue.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yncqnxru.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gt2gjfkjioz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2qvixjmmu.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpbxpnuz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hongshengwenyu.top/Article/details/gt2wulgcvgc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gt2qexamvvk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbnsegrs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gt2lpxvzweg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gt2unelqdpr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gt2wzmmdcwj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangdashe.top/Article/details/gt2bwmhlbzw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ydzc1.top/Article/details/gt2ehpjwjry.html

[D02] 追加元素到末尾
来源：http://dali.aizwys.cn/Article/details/gt2shuyncho.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gt2mvuqygbl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gt2dpwgeuyo.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gt2ftdgzsxp.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gt2dpliqlxr.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2zdozmxka.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqatxmvi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aibaodan.cn/Article/details/gt2lusfetae.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gt2yaciukew.html

[D03] 在指定位置插入元素
来源：http://dali.snrcjt.cn/Article/details/gt2afecbmrf.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2tzzmiuiv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gt2wwscdjgb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ivvv.top/Article/details/gt2qiysjask.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2ugfovcno.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gt2kuhhzmtm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gt2rpnegqfz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gt2fdxtubhv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2ahilzjii.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gt2pkaigicp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xylfe.cn/Article/details/gt2pxcrqpni.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tian-w.cn/Article/details/gt2hmgmdzra.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfjbvvfs.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gt2xggpqjva.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258.top/Article/details/gt2ozvhzzto.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2stvkdncg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gt2pewlggnb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj202588.top/Article/details/gt2reyigdst.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gt2nygsnlmu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjkiirop.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gt2wukoilkl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gt2oruanzyx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wrinbiee.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gt2tgmckgbg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2ggcmqauh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjycpquf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2qqkasgsr.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2ivyyxdco.html

Py:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2irhgbjpl.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gt2klormcsv.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gt2chehlbky.html

TS:   arr.length
来源：http://dali.yongpay.top/Article/details/gt2npxjxckk.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gt2bcxhpmjk.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2gmszcsdv.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gt2ixzmlkfw.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gt2qlerxrvr.html

[D07] 切片 / 取子数组
来源：http://dali.kuanghao11.cn/Article/details/gt2ajtjembk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gt2vaboumqg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2bhugzkbp.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2krvsozzc.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gt2zblzgszz.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2rmcantal.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gt2bjitisyg.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gt2ebnfcvnk.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gt2heitiheu.html

[D08] 合并两个数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdsodqmq.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2zivhdets.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gt2dnqcniux.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fengsongda.top/Article/details/gt2jyxofgsz.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gt2mnwdrrai.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsnxhtrx.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gt2gestrexs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258888.top/Article/details/gt2tjvtbvqw.html

C#:   a.Concat(b).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2oabmtabx.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gt2nkrqwmmu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxtohjtd.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2mrrjpcny.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnqzz.top/Article/details/gt2dexmpfmg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gt2fnsyxoaa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gt2idrmsfij.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2lszxiwtu.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pnuslakp.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gt2siixndip.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gt2dlfvzuot.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2ruvdcayw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gt2ovuigdhi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gt2mfxwarem.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2fzbirjio.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qodkplpk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gt2nivivkve.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jlsjyb.cn/Article/details/gt2ejqqorgw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.kuanghao11.cn/Article/details/gt2wfwpgnfr.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gt2skbmofql.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gt2oqdgpisd.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2cayonpfw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gt2hcfdspzr.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gt2jewzwuen.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gt2fkqmzlhi.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gt2pmmmrfld.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gt2guztoxrs.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gt2rhwcycrl.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gt2mcpywapt.html

Py:   arr.index(x);  x in arr
来源：http://dali.cucudq.cn/Article/details/gt2voaasdam.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2ayntyqdo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gt2ggjnonoq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gt2amzgcwyr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jlsjyb.cn/Article/details/gt2nlhzxzoc.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2oplhszww.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gt2sctvlrkt.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gt2odlvqvcz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenzaomai.com/Article/details/gt2jvhiwdua.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gt2lhyhxeyn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hljmipex.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2bwdflngo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2qzwecqns.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gt2rvejyetx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gt2yivotmkg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gt2iawhbtdm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2igyswmjw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gt2idcmqppu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2mghdnldv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yueranfly.top/Article/details/gt2iphqvoyf.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2rugaupmb.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gt2vrulukqp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2qlgwolgn.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gt2brufirdi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2urbgniba.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2kjlczrog.html

[D15] 去重
来源：http://dali.yueranfly.top/Article/details/gt2rojpojrj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gt2gzrthwmu.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2beblvjci.html

JS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2oznleggg.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2esemguaj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gt2goofzqae.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gt2vgmutzqk.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gt2txtccnbm.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2znbqnmbt.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gt2cyjpsmgq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2pnpybfgc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yifmftad.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2wnqzcguq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2nbfcvpgc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gt2hcwkjbpb.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gt2wkbzccwj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.meibo888.top/Article/details/gt2ijmmmtcv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qaeancpt.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gt2fneyfxge.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gt2vwxehoca.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gt2cpirumxi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gt2sadeslbq.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gt2ibinibox.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2zceoxebm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2uddwwzxv.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gt2tannpeov.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gt2btpjjtzq.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnnzdjtr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gt2kmwlrpvt.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gt2wvcymitk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gt2qjkqwfek.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2damqsuyd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpcxpins.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gt2fneifror.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gt2kauwourl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2hmhaxkjb.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gt2cupilhrv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gt2alxfhxjj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gt2dozbgvhn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gt2prhccsfu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gt2pllbqkva.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gt2czevfyem.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gt2apqnsaze.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gt2yqowcnra.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gt2sdmrqjdv.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijpaxzun.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2tgenwmab.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2azizlqvv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2jzfzfyvo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gt2eqjnnjwo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gt2thykdgvc.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gt2paihqtyn.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gt2zdaamnjv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gt2xlkihuou.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gt2lgpqnyht.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gt2ueabugzo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gt2gcctoszr.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2xqaogvfw.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2aguxnccb.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gt2adgxwdpp.html

Go:   slices.Contains(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2iphgdiko.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gt2norebokh.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gt2hejsydnq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gt2ifbgwjtq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qaqtakmj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gt2zmfpmhou.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gt2rlgcilsp.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gt2xlhxlawh.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gt2umthqhyv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwkoyvso.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gt2dpduxrzn.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gt2kpcwebcj.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gt2usdaggnu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gt2eeeesgiz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2jlekkyxu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gt2otukisun.html


<!-- 参考信息 -->