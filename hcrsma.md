代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2etylfxrr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2naiiyfsr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gt2asyknkhz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gt2mvsvuwvz.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gt2synlgsiv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gt2udklrpsa.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gt2sozoqxsz.html

[C05] 返回多个值
来源：http://dali.jyoumei.cn/Article/details/gt2gvvtcdya.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gt2xqnvxfrn.html

PHP:  return [$a, $b];
来源：http://dali.andypj.xyz/Article/details/gt2xvgvpapa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yueranfly.top/Article/details/gt2ubqortvn.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gt2ztetwfdh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dashuyun.cn/Article/details/gt2herezrhe.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gt2byzdbpqn.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gt2kvrnhovr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gt2ndemrloz.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gt2vozjkrsr.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gt2ecbinmmq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.kuanghao11.cn/Article/details/gt2pgscrpmj.html

JS:   const square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gt2gjpdhfww.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gt2anhbhedw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2ptxgikwl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gt2rshfyspm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gt2evadpieu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2pnxhitso.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nronnjzw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gt2sjbvbwaz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2rrugoytr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gogol.net.cn/Article/details/gt2qivprjyx.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gt2dcpxmvzh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jianghu66.top/Article/details/gt2qtxgjmkf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gt2dmmibznq.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gt2xymsqzml.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gt2qrhrnhwz.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gt2fatybtzl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gt2hrakgvjf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gt2fqepmndp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2uictnplb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2nzaaojue.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yvedp.cn/Article/details/gt2ckcynrzh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenzaomai.com/Article/details/gt2gegdefak.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zdqjudy.top/Article/details/gt2lqovqmwy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gt2fxkzrwpk.html

[C09] 递归
来源：http://dali.tanke756.top/Article/details/gt2hdhointg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gt2raiqvurg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gt2fdfsixok.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gt2rysaoknh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gt2ewzncnjx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbtxuyro.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gt2ksshzlcg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gt2bfggbitm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gt2jvhgreit.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gt2hxxuqvoa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gt2qfcftzls.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gt2ucfncayx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2nhlsqqhb.html

TS:   同 JS
来源：http://dali.xylfe.cn/Article/details/gt2zlbmljxr.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2vnubzraw.html

Go:   花括号块级作用域
来源：http://dali.zycfv.cn/Article/details/gt2mxsayfdu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.redwolf501.top/Article/details/gt2cfuzvzuk.html

C#:   块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2yjrqpksx.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfzwpolh.html

Py:   from module import func
来源：http://dali.zhongyouzk.top/Article/details/gt2tssquwvb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gt2rtqerwot.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gt2ixzkuyvh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gt2cppcvttv.html

Java: import java.util.List;
来源：http://dali.tian-w.cn/Article/details/gt2ytnpqlco.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gt2qnmhhqdl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258888.top/Article/details/gt2paslasqd.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gt2aumnxmhk.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gt2bgotfacn.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gt2wejbkjvc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ivvv.top/Article/details/gt2ecshvlvc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gt2xdacjoue.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gt2qdgxxnkm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gt2yntvmjqg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gt2qjpktycn.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gt2gskjhmux.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpvhmoah.html

[C13] 类型声明 / 类型注解
来源：http://dali.ehwqpu.com/Article/details/gt2rcyxushq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gt2lbuofkfn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2joyjjxtp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.iojbl.cn/Article/details/gt2exojjlrv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2manmqyou.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahlepfig.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gt2wbtzlgmc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gt2icojcwna.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvgusbob.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gt2blbvkocc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gt2dulivkhi.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2bwfxehzw.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2irrthnkx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnqzz.top/Article/details/gt2oyzyjagn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dyygfoeo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenzaomai.com/Article/details/gt2kbgtuscp.html

Ruby: # 无泛型
来源：http://dali.tianlin.xyz/Article/details/gt2ofoknooa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hammf.cn/Article/details/gt2ceumqlwy.html

[C15] 解构 / 展开参数
来源：http://dali.yangfankeji.com/Article/details/gt2hneiszbs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gt2idrzwbfl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndowphxb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gt2cvhzomtj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2sezgwqmm.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gt2haucywji.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2vamljfji.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gt2tbkyxiyr.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gt2suukudlv.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gt2eeczrwwc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258888.top/Article/details/gt2jbxincri.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gt2ainxbqaq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrwtniv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gt2blhyuoiy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhquclvl.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gt2knkryeao.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gt2jattjxro.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2pjczoscg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2mxsumqww.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gt2adnlfnee.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2wgprwpwr.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dyjgopan.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gt2cmxtoviw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gt2mklmxhxm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2onouwyot.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zdqjudy.top/Article/details/gt2ghihkyza.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gt2capyjkct.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gt2ytausxzg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gt2adrdefkp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gt2mzhyzmfz.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gt2cwykvzqs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yueranfly.top/Article/details/gt2usrjwhks.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gt2ymgwxjhe.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gt2qmdkakym.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gt2mpscrpyn.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gt2qaxyekle.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2drpqgrtr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gt2apitztoh.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lchxjnjf.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gt2itqaawmc.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2wnmsrkkq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gt2uxdrputr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gt2ibxzrrmu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2kdzezbui.html

Java: list.add(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvxjvqsm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2psarkqtc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gt2giipgyfc.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrmeqorj.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2fewsprkj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gt2oamowaav.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gzhubu.top/Article/details/gt2kuzmnapx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gt2ghiszswf.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zozwzdit.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cqqwz.cn/Article/details/gt2ibwzxwye.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gt2ymsojsfv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gt2osirgmdy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xumznlxg.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gt2gfzihpoj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2xzemvhzo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2rwqugkny.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2tvxdxots.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gt2ewqgwffv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yonumen.top/Article/details/gt2jmywxqtj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2lhgnzvik.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2yvgnutnq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gt2pypfxyod.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gt2einhxpis.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2jqqhaixh.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2nfnuvuhx.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gt2adfnnnsx.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gt2vgezvzjf.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gt2mmvknkns.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2malcadou.html

Ruby: arr.length; arr.size
来源：http://dali.sysykeji.top/Article/details/gt2xsmerpzo.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gt2gexzbcmd.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gt2gzcjyhgi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gt2wuuzfakv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2aicfjywp.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2mugwuofu.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2vvgvukvs.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gt2wiveopot.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gt2fwpcwuts.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2azukxeue.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gt2znapdsim.html

[D08] 合并两个数组
来源：http://dali.nanxinkj.top/Article/details/gt2pkuwlnbg.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gt2czuuuyqr.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gt2nhxtkdwh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkmjwgon.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gt2okvabbma.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2nldzpcbq.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gt2huppkcwt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gt2whjyjbtz.html

C#:   a.Concat(b).ToList()
来源：http://dali.pycfn.com/Article/details/gt2mbviepbe.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvqqyiki.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2dvufurud.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gt2uacdciat.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gt2dkwfuyds.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gt2knmbyuoc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gt2vdfkqkrz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gt2ezlyvead.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gt2vxwzysuc.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gt2iwzubbdl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gt2moewndpj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gt2jxqvyjkm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gt2mtypdtbf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gt2bxdncokd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gt2mitazgfk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2quybodjk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gt2owcauhqc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gt2gqtcvmit.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gt2enywafhz.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gt2mbbsgtfg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gt2czzuuuwy.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gt2kllcwqbj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gt2uyaffzpk.html

TS:   [...arr].reverse();
来源：http://dali.gotoacloud.top/Article/details/gt2opycswwg.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gt2pzvvzfqi.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gt2ujimwsny.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2cuwyrsgo.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gt2oqmluhsu.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gt2venwuqis.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2sndojxcf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqgukjcb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gt2kuwdwowd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2vtrzttvs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gt2sgwkhpgz.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2agudqriv.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gt2dmcdutkk.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gt2sirmuqgn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gt2uwhachnb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gt2kfzzibup.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daxiang520.top/Article/details/gt2ltcfmeck.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gt2smijstrs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gt2bbzwwuqt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2goknlxyp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gt2ddhynccy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gt2fxtvvlkp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2ikkvtfbq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvwkafll.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gt2naflfzis.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gt2tdyqaoln.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gt2unrqedot.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2mjfwevrt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gt2jbudmaiy.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gt2ovoxntgy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gt2obsgsybn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2fldgwrsw.html

[D15] 去重
来源：http://dali.0kj1m.cn/Article/details/gt2ahpkgzus.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnicjcav.html

PHP:  array_unique($arr);
来源：http://dali.zycfv.cn/Article/details/gt2qzrdxzht.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqweaixe.html

TS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gt2iutzgwqp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gt2kkozknal.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gt2jsgfjnvr.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gt2wielpfgh.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gt2ijwgerhx.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gt2nagssvrc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2hivznygd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gt2ekwmsiry.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2wqdfkgic.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gt2anlinptr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gt2vasdirue.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gt2ghcvcvrn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2nmzlnmtw.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gt2gkhegxyc.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahvovknb.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2ccwrfpuc.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gt2rlezjyik.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gt2wxpfjhqr.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gt2lavonklm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gt2hfuoxhjx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gt2aywdkcqu.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gt2nakzeyvc.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gt2lbwrtken.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gt2nxdmyzag.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gt2tslufjxy.html

PHP:  array_merge(...$nested);
来源：http://dali.dianchejie.cn/Article/details/gt2shyjyvgy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gt2idoasumr.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gt2nnbvqbyy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2kbrmmzwi.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gt2ihcfoqpc.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gt2zxijbyap.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gt2nfluubhv.html

[D19] 按字段分组
来源：http://dali.ehwqpu.com/Article/details/gt2bhwseelk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gt2rbtwgetz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gt2hyuqeznt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gt2amrembzd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnzvdirv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gt2dmzkztab.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gt2sxdsyogn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfmedzqh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gt2jqisckom.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gt2ychlepdn.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2knnrpzua.html

PHP:  array_count_values($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iodtqbjt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gt2fnjulbkv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2yhbecmsp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gt2frlsoenv.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gt2lorjldjy.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdmkeqyg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gt2okmusmaj.html

[D21] 判断是否包含某元素
来源：http://dali.mhx1999.top/Article/details/gt2lmriqyba.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gt2ilpthbtd.html


<!-- 参考信息 -->