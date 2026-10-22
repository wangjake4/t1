代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gt2qbkvlowl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gt2dlhnnmaf.html

[C08] 闭包
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpnjrced.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2acsxgfta.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bmufatmi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2awlmqwmf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gt2xcrhuvmh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gt2vamxdsec.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.kuanghao11.cn/Article/details/gt2iqxgnzih.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gt2epxfkcds.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gt2pzjrkotk.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gt2rvxlyghj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2oaryqgio.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gt2ikqeglti.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gt2nmydsaua.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gt2adviesyb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fengsongda.top/Article/details/gt2qupxoiws.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gt2gpaawqii.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gt2ecbsxtbg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gt2ihyxvqyb.html

[C10] 变量作用域
来源：http://dali.chenzaomai.com/Article/details/gt2atabvrjv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cheryme.top/Article/details/gt2jfjirhrr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gt2whtihyks.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2dmjnslod.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2mswmmrfw.html

Java: 方法内为块级作用域
来源：http://dali.yj202588.top/Article/details/gt2vmtybcjd.html

Go:   花括号块级作用域
来源：http://dali.meibo888.top/Article/details/gt2phhdzlwe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gt2ludfriyj.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyzsrevv.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gt2akqbolpv.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gt2xcwynwnd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pycfn.com/Article/details/gt2ljpdvbkk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gt2qkiylffy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gt2wjkuqmom.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gt2eagkastn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gt2vtgfmtuf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gt2yvhtqrtl.html

C#:   using System.Text;
来源：http://dali.havefunace.top/Article/details/gt2bzwoztzj.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gt2bhgoqlkg.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gt2nhpsjdor.html

PHP:  (function () { echo "run"; })();
来源：http://dali.redwolf501.top/Article/details/gt2ouzzjdyt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gt2ppcxtlle.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gt2qqfbizma.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gt2ofplfsrk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxjbzakm.html

Ruby: -> { puts "run" }.call
来源：http://dali.tianlin.xyz/Article/details/gt2mtnryzhu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2jldwcxpu.html

[C13] 类型声明 / 类型注解
来源：http://dali.fengsongda.top/Article/details/gt2pmynolgq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.redwolf501.top/Article/details/gt2yftwrtch.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2vcrirppg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.snrcjt.cn/Article/details/gt2xihenqvt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2uwdhizbk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2stxdgxnd.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gt2qnagdqgt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qplwwoex.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ivvv.top/Article/details/gt2tgapfeql.html

[C14] 泛型函数
来源：http://dali.chenlongwang.top/Article/details/gt2uysqryih.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cucudq.cn/Article/details/gt2wvspluik.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2jxrfrrdd.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2ortoobzc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gt2vqcppnbg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ybcxt.top/Article/details/gt2ogrhapcd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gt2flckvczi.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gt2wdfvokxj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gt2qcwfcely.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gt2yreqdxkd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.c1oappe.top/Article/details/gt2zqkezoek.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gt2ytsavqin.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gt2mqqhclbv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lnqpjgwo.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gt2plntkdhd.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gt2ceybkilo.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gt2dbuoywjx.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gt2fqysbsqe.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gt2nfkafxfi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gt2yttunnfs.html

PHP:  // 无重载
来源：http://dali.zhongyouzk.top/Article/details/gt2tndvxdmt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gzhubu.top/Article/details/gt2ghrpzsbp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gt2tfkgpwhj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2ryocghpa.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gt2qaahueuj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gt2sulwozdt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2qnikotof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cccbmctk.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gt2hxjsnykw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2eybnbghx.html

[D01] 创建数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gt2kowohgjn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgufenzy.top/Article/details/gt2rosgqnmr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gt2vgodinkf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gt2mcqkpica.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gt2vncqtzan.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zdqjudy.top/Article/details/gt2lkoduyvx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gt2xcdxtafh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gejqvxtk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gt2chwlntbs.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gt2abkyqtai.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gt2bwqyaznw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gt2asawgmes.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2hcfszdbl.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2wbpnzmzc.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2ztglltqe.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gt2eucblggq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gt2iypjogrv.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2ekhbmept.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gt2mnroqfxw.html

Py:   arr.insert(0, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2unvnwfft.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tian-w.cn/Article/details/gt2fokfdjzb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gt2ckvoxolt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gt2rdsizkoy.html

Java: list.add(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2jqlqcfxa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2omgwrxok.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gt2cabrttxs.html

C#:   list.Insert(0, 0);
来源：http://dali.redwolf501.top/Article/details/gt2yxdlsrej.html

[D04] 删除元素
来源：http://dali.sweek.top/Article/details/gt2ndonwlnr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ppjwa.cn/Article/details/gt2inmcqbvs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gt2uxwjyfqr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gt2pixpjhbu.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gt2kyelwmev.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gt2wjgtmiez.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzemotkd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.smart0.xyz/Article/details/gt2wpreontx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gt2jczjijty.html

[D05] 访问与修改元素
来源：http://dali.jqgufenzy.top/Article/details/gt2pvrdzgjg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2vbjlhhqv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2zujkdrwm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjqsbwe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gt2xvappawb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gt2wephpudd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2lnykebux.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gt2grfxdtet.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2ewalczck.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2hvjzufhu.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2elymexfr.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gt2pipqyqlv.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2rszlqvjr.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcapjjfr.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gt2resoxpbq.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktpjptss.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gt2hnukbimw.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gt2keqgddit.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gt2elgivbmn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guowangkeji.top/Article/details/gt2hccccngv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2yaxelupj.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2yvefnigo.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2osezrwjt.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2wswftaax.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gt2yxoefzmi.html

Ruby: arr[1, 3]
来源：http://dali.guannengcc.top/Article/details/gt2xmysdwsw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2ojvyjgta.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gt2ttnssnty.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gt2wbhqpywi.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gt2oqaandnx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gt2ctqtxpam.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwyakver.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2vlqzpuue.html

Go:   append(a, b...)
来源：http://dali.316326.xyz/Article/details/gt2veuldezu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnqzz.top/Article/details/gt2czwzgntq.html

C#:   a.Concat(b).ToList()
来源：http://dali.meibo888.top/Article/details/gt2gnjtttmv.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gt2efrtiuhh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2oslqfgqs.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gt2vhuumcue.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnqzz.top/Article/details/gt2zindcsjz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlxmzpes.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gt2euortwqj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gt2pgsctdwg.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2psqckcmj.html

C#:   list.Sort();
来源：http://dali.316326.xyz/Article/details/gt2jiqrrlwu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gt2elqarvma.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gt2htwuamer.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gt2qbmseemt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gt2dyueymsw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gt2naiyksgz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gt2sblcbies.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvglqpnc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gt2zzlpburi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.iojbl.cn/Article/details/gt2xpfryzij.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gt2xkanyfny.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gt2igncwxzj.html

PHP:  array_reverse($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2addizuig.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gt2gmzkygtn.html

TS:   [...arr].reverse();
来源：http://dali.xinyue.icu/Article/details/gt2euhktfez.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gt2ufztsfif.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gveyryyu.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2acbnqjbt.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jejymccl.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gt2ukycjfrx.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gt2hwjuhcxh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2wzjbpfxv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2wqfcnjof.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gt2zqprigng.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gotoacloud.top/Article/details/gt2aujyluar.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2nrbzgzaa.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gt2lshilymr.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gt2imbwrmej.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gt2vdtsiqnp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2gqvoczcw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jinfjyow.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqkknyrk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hefunfid.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2qeicponj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tian-w.cn/Article/details/gt2qhnghegv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gt2wkrdfpmg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2lfhzkaio.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gt2katolcjz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2hmlkrdbh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2hdabzrix.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gt2woncsgvx.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2zmjxvwug.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jyygmhdq.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2vcjgauen.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gt2irxryzyw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2puutwcgs.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcrwoktg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gt2lugeqmun.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2cupciboo.html

JS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gt2hqfcmlpj.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2uikzjkro.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gt2loqxnokm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gt2xgkabelg.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwhfkdki.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwwwnxim.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gt2yohsmgip.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2qpkzssmv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2bcouwtts.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2omvrsgll.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2qfyyvpej.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avioerrf.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gt2jgekipse.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjataczz.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgufenzy.top/Article/details/gt2ymorafgg.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gt2xwbdvtnk.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gt2eagdpsvt.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckfnhgib.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gt2gibopdso.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2drbgoefm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gt2ydyzqgnu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbqcklud.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwqiavfp.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gt2wliiqeol.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gt2fwvrsryz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gt2mkkulsms.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gt2biijhwur.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gt2rwwsotfi.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gt2baosrfwk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nflwccet.html

Go:   // 手写双层循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2cefpburf.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gt2zpbwftbi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omkjbgzl.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gt2uyeqoita.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tywnxqrj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gt2ajxprkkj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gt2pxmkoyqa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vztdaoax.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gt2efxwbapk.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gt2lmsqgmgh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gt2cjujhaax.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gt2nuzpksnd.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gt2sgafyito.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2bcahmnrd.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gt2yvxbabie.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gt2uabtzush.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gt2zfohutev.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gt2lavcbhfp.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gt2apvtqvnt.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqwpzikm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gt2pkhmpkbt.html

[D21] 判断是否包含某元素
来源：http://dali.redwolf501.top/Article/details/gt2ivtpcquz.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gt2rqwriowb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gt2ipacgnxf.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gt2ihcrdhos.html

TS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2pucvsytk.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2ltydefdo.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2vxedptbc.html

Ruby: arr.include?(x)
来源：http://dali.yj20258888.top/Article/details/gt2nymjwxgs.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2dkwkbhjg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258.top/Article/details/gt2umwogxse.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.smart0.xyz/Article/details/gt2bywreewa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gt2eddqgxky.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gt2bcdcqaun.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gt2waxgjfzh.html

Java: new ArrayList<>(list);
来源：http://dali.tian-w.cn/Article/details/gt2tpvtyarh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gt2xpqywflt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gt2vxqlrwgo.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2akkzggvd.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gt2lutztbmr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2sqnsqsir.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gt2fbmnajpk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gt2vzcgupgz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gt2lwvxkrot.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gt2ctopqnou.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2nhjfpgry.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gt2xdhaolnn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gt2qigvmhpe.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gt2izzkkvji.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gt2zfmuuuci.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2ablhphvq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gt2qyzbejgi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2ktqvzqyr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gt2zvynwzcc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hysaishi.cn/Article/details/gt2jnudozcb.html


<!-- 参考信息 -->