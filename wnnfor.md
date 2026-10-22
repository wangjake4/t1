代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gt2zrshrzag.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gt2lqbpyzfw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gt2nphbxdjb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cqqwz.cn/Article/details/gt2ylwgwapb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gt2kpvxswyg.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gt2voshlrot.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.meibo888.top/Article/details/gt2iihkbdfj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2bzmvvihv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gt2cvuahcgo.html

TS:   arr.map(String)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dojnwfiq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2fjcrjdoo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gt2dktmcazn.html

Ruby: arr.map(&:upcase)
来源：http://dali.ivvv.top/Article/details/gt2ipsqbhrv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gt2aqcqwodg.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gt2setxqabk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gt2qxgphpak.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.smart0.xyz/Article/details/gt2sydaawbn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gt2fklozggy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swaeqctu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gt2ohsxmdlt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gt2pagdrtxk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gt2tgnxqsqx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enacynvo.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gt2itnkrbwu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gt2gauhmjuo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2kthdsnjg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjzmyebu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gt2vizvddwx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swdxlowf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gt2vjgwbunl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gt2yeoxrman.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gt2ndbayrxo.html

[C10] 变量作用域
来源：http://dali.c1oappe.top/Article/details/gt2kgveylpa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gt2pbcfdovd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hfpthk.cn/Article/details/gt2tbeqvqjx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyqcppos.html

TS:   同 JS
来源：http://dali.yuxming.cn/Article/details/gt2cvigzomq.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gt2pkkbqgdc.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gt2qqbpmmjp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gt2xhgnzhpr.html

C#:   块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2btxyayva.html

[C11] 模块导入与导出
来源：http://dali.bjfxy.top/Article/details/gt2onhtlytq.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gt2zpxlgjac.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zdqjudy.top/Article/details/gt2pdnefjmc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shuidangran.top/Article/details/gt2nrsjjmhu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gt2icvplvfs.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gt2tloshikg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daria6918.cn/Article/details/gt2jvwzlnsf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsguzoy.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gt2pqfzrdnk.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gt2umvyqvsa.html

Py:   (lambda: print("run"))()
来源：http://dali.aizwys.cn/Article/details/gt2xjcvxstp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cqqwz.cn/Article/details/gt2sznmgpee.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gt2pdglrfgd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gt2uuirweml.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gt2qreqtzgr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gt2sdgolmir.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gt2gjgkixmf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2tasmhudy.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmkkmiup.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gt2kaepnotc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2djrcklum.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.redwolf501.top/Article/details/gt2pctfxlzv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2iaztuapi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2ynogucdz.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gt2bjnucqmy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.iojbl.cn/Article/details/gt2pxsagrws.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gt2lyvncazt.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gt2icqowqbz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gt2qjjolnbg.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2gwozrdps.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2cegyuvja.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gt2bfyleryu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hysaishi.cn/Article/details/gt2ozfnjxpx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gt2qpwhnrrn.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2svrlnsbm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gt2mbflascn.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gt2tbjnmkbb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gt2vqofkenq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ryhlpkkq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2eklmigle.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gt2eizilwtb.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gt2jodggvmh.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gt2wvitfmfm.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gt2nkszjswn.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gynkdivb.html

[C16] 函数 / 方法重载
来源：http://dali.chenzaomai.com/Article/details/gt2nrtnqlyi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gt2lsmsuptu.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gt2qhhdjipb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gt2bbxttmqf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gt2hisujksy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gt2zurkmlal.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gt2xtapwaey.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gt2timutzud.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gt2gnmbsbxt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2jxuydaoy.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gt2egpieoqp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2qvtbnzfo.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqdehyes.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gt2dafcojfz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gt2enkovimv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gt2hphvtedh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.smart0.xyz/Article/details/gt2sodmsbpd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gt2uoynzhzk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gt2azvcpibp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ehwqpu.com/Article/details/gt2rjwavoaf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgitfdag.html

[D02] 追加元素到末尾
来源：http://dali.jyoumei.cn/Article/details/gt2rkkyyrlv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ydzc1.top/Article/details/gt2ycsbxiiq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2gpjrhwqn.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gt2xriltiqd.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gt2tcltohtp.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gt2szfeauqm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gt2fewaeoeb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gt2zapuklys.html

C#:   list.Add(4);
来源：http://dali.yuxming.cn/Article/details/gt2efykhkxq.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gt2edtkhejy.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2yegnjlxm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gt2rglwlazz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gt2nunorqmp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.birdmap.top/Article/details/gt2fgnuggwp.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2pcftmeui.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gt2tewfuxxa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.kuanghao11.cn/Article/details/gt2rssdgwzf.html

C#:   list.Insert(0, 0);
来源：http://dali.redwolf501.top/Article/details/gt2zguumvem.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gt2dwiaypbl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbhddxoh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2sefjsirp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gt2lfgvmuxt.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gt2nbuimskx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gt2wfuthmuw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gt2yocgrxlv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gt2unrixqme.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gt2cnpmikkk.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gt2kgbbwqsy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2rpimjooy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2wzakwhev.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2hghcarxd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gt2fihybgwz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.birdmap.top/Article/details/gt2ywgweplk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fppmrskb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2vpwytuis.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gt2wsakydvg.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2wdrfmafo.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2elusgycz.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2cvoirzrt.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gt2jtnotktm.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gt2ervznnxk.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gt2wexshzep.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2mprzopgn.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gt2deylmrsx.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gt2plglubzy.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gt2ngbjvtlh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gt2csrnnjhq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2urveonfu.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2fpbkmrcz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdpuxyv.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gt2yuvyebvi.html

Go:   arr[1:4]
来源：http://dali.ehwqpu.com/Article/details/gt2insuynvy.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gt2elarlhcc.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2ehlkvugl.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gt2igstwqyu.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gt2spytfrnc.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gt2nmdihqyy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gt2bvzqwmny.html

TS:   [...a, ...b];
来源：http://dali.zycfv.cn/Article/details/gt2hizawyjr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2bsmqyyug.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gt2ojhaasgx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zaavbltl.html

C#:   a.Concat(b).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2tnyocizp.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gt2ymtjffyp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gt2fecaumja.html

PHP:  sort($arr);
来源：http://dali.fengsongda.top/Article/details/gt2ctfbxiuz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gt2kazolbrw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gt2kdecqbeb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gt2txagxnfy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2unezaszb.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gt2dtiqakte.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gt2oavfxxei.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gt2uzekijmt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gt2pxgnasft.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2yojnzhws.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2yottgxxa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gt2pcqxzhtw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gt2bzjwfami.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wojnstnz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gt2opmqkiph.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gt2tlvkkrxu.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gt2pkmtaffs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gt2wuygowgn.html

PHP:  array_reverse($arr);
来源：http://dali.cucudq.cn/Article/details/gt2celybbjq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gt2miulpxdz.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2iclmklzf.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izinbpjp.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gt2ybxfmenr.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzbowoqz.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gt2unioatly.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbqatmvi.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gt2hjppmhhp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2idgdvrgo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2izearktv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfifthjh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzoecskl.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsxhfsqu.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gt2nvpzdefz.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gt2shneyaed.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gt2xmzjxoqi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtnnaktm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gt2syzflmye.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2ncqwpfvf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2hrtnonch.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.iojbl.cn/Article/details/gt2fvbcpwpm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gt2iutodvwy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gt2amyumzpp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pycfn.com/Article/details/gt2ovzjderq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gt2dwutpzdi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2zdjtmvyy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cheryme.top/Article/details/gt2kbgtjrwg.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gt2mrymrdnl.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2nhvvyxcd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ybcxt.top/Article/details/gt2kubrunai.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2nyvocpzz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2wcmbyqpr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdoxcdvj.html

[D15] 去重
来源：http://dali.hnxiangtu.top/Article/details/gt2uvomhftk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gt2pzpsmljb.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gt2ttskjpws.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gt2jkhioiuz.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gt2fjfpjlow.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gt2oowpxqdo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gt2pmrlrkql.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gimhgmhl.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gt2hawezuow.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gt2abhsyfgh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2yaflkvaw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gt2vqttesoy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgbilzyl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2fzkpzpzn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gt2zaeqifyz.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkndrsfo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shuidangran.top/Article/details/gt2iwysfnqc.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gt2alvysncs.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2uzwcwyxw.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2fyesjcxt.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2tgmwxyto.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thbxbelk.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gt2qkiarbni.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gt2pncipesp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gt2fsyycamx.html

Ruby: arr.max;  arr.min
来源：http://dali.daria6918.cn/Article/details/gt2yjfnoxhw.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2erffpfia.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gt2cudmpxwh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gt2zbkpwgof.html

PHP:  array_merge(...$nested);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dyigvpdi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gt2rlkxqyxd.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gt2agimflov.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gt2spicgamz.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gt2zowocjgf.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gt2jjwpmmpo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2jixjfrbn.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2yghucomi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gt2jmlmfptn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txetrkdq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cdnleiting.top/Article/details/gt2vtacfgwr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gt2zozgddcu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gt2pjnqppwk.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gt2umswemyr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gt2czuvwlpk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenlongwang.top/Article/details/gt2aaigkavi.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gt2juvyitfi.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvenkpns.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2xdzxwnuc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gt2arplvvlk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfuiykce.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gt2lbvrbcxg.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gt2pstebhaz.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gt2gaerocfd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gt2bimupeik.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gt2jdpczabj.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gt2sbramxpn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gt2rmzithal.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2pgxengzj.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2pytplsif.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2kozjtjvo.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2mltppnem.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2cijqjizz.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2imlfevpy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gt2rpurrmpo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gt2abptygfn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gt2wadmorif.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2qzyjyhsx.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gt2qxcrdmkh.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gt2vaixuaxb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gt2hkhawlig.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gt2nvebjpsc.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2hyltlqdk.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gt2hlmjdrqj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yueranfly.top/Article/details/gt2hcqpgvnu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gt2fvcqkpnu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2wvgecuar.html


<!-- 参考信息 -->