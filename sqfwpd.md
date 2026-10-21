代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pycfn.com/Article/details/gtvktimqto.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yangfankeji.com/Article/details/gtmgrdrzcn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gtdnlxcflp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gtczaucvlq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gttvqzitan.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gtyscmfcov.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cheryme.top/Article/details/gtkancwsjn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jianghu66.top/Article/details/gtoytrechn.html

Go:   // 无：用配置结构体参数
来源：http://dali.haohaochexian.top/Article/details/gtyoqirheu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtetasqahg.html

C#:   f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtghvbodic.html

[C05] 返回多个值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqezxtxcu.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtaxnvjzon.html

PHP:  return [$a, $b];
来源：http://dali.daria6918.cn/Article/details/gtbnffslud.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtbskzvypc.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtfbafuirv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtwuknjnal.html

Go:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtsgxzfdyw.html

Ruby: return a, b
来源：http://dali.aizwys.cn/Article/details/gtebcbxdfd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tianlin.xyz/Article/details/gtocmzibxo.html

[C06] 匿名函数 / lambda
来源：http://dali.yvedp.cn/Article/details/gthcojtjkm.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gtwdzubhiu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gtfypzxewd.html

JS:   const square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gtrihbnhsw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtsqlujyts.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlfteepf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gtuxoclerf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gtjmnwpdej.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtifigqpte.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gtaqtxnvoz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gtfiwfrqph.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guannengcc.top/Article/details/gtrmdjnvpn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tian-w.cn/Article/details/gtsukvyabt.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwukhgljf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gtlipwufcq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gtuqqsvghz.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gteuiynxnt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.vqdsnc.cn/Article/details/gtmufxvznp.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gtwoyhqcak.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gtzhymhpbs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gtimotycoh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtrembimhv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtunffqwys.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gtzykoqgej.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gtfkbxxyvo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenjidiqi.icu/Article/details/gtcrhgjmby.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtzjdxpgia.html

[C09] 递归
来源：http://dali.tanke756.top/Article/details/gtosfpgvps.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtzagfqmlx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtuyiefzrd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtxtuoeghf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtxhctzgzo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyglrplzv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gtruusvgid.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdedjuhsd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gtfuaqatws.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gtitzjabzq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhongyouzk.top/Article/details/gtvtnlasrc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cqqwz.cn/Article/details/gtsnvpjban.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtqqpyhthg.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtxatlnhln.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtzyrfxqad.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtvwtbvwyi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gtegnkzsjf.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtsicmlyis.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gtmpwecese.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gttmmafbvh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yanxiufei.cn/Article/details/gteyvtkqwr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtxwzpascf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gtctxlgohe.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gthitrokyz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tian-w.cn/Article/details/gtkpsabnmz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gtrngpajvi.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gteuitgwxh.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gtuywdifud.html

Py:   (lambda: print("run"))()
来源：http://dali.hammf.cn/Article/details/gtbicatzhq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgfzy.top/Article/details/gtbyhgqjrn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtcozdbcvm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtokvsnjkm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangdashe.top/Article/details/gtzjiknmsr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gtwmygplmz.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtejhlydnd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gttmfgzizq.html

[C13] 类型声明 / 类型注解
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcszzmecg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtsingukwr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtrnmguavv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zycfv.cn/Article/details/gtvoqockyr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtwdqcbtcd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtlqykrmbb.html

Go:   func add(a, b int) int
来源：http://dali.daria6918.cn/Article/details/gtirmtwnln.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gtbmmnrjml.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ivvv.top/Article/details/gtivuzlqyh.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtyhbuptaz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gtywunbcbn.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtnarxbnwu.html

JS:   // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtfiphqsht.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gtlrdleaov.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ybcxt.top/Article/details/gtqjiykdup.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gtgsqrkjsp.html

Ruby: # 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtmcakwvdz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gtokzehjnf.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gtwwhzgofq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gttidmidgh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gtwtatxief.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpovfncth.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gtvwbvnqbf.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtkpwtcfnd.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtgcfmikmn.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gtirqtclxy.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaneslcr.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gtlnggigvx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gttywapcgz.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtjadurypr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenjidiqi.icu/Article/details/gtwamnpplj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gteergeefz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gtyymvelsc.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gtpptcubuu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gtxfynzuxx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtogetziwy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgzhbqqwf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtudhwxlga.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjupevsoi.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gtnzznkfuv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtratlyohh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gthhrmtlqf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtbipiodvw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtbbhzfxew.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgufenzy.top/Article/details/gteotfbgoz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtdyormifs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywnslavr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ydzc1.top/Article/details/gtjqtjdzzh.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gtcbgabcua.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtcngnuivi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gtesvavibu.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtlpfmmqdy.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrdcmddp.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gtihkqwzmo.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtpudrzgdp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gtetwddybj.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtjqpiqjce.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gtpksfnneb.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gtvskwlwyy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gtcraiyjtf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gtdxbncwvm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gtlprbfvit.html

Java: list.add(0, 0);
来源：http://dali.cashguo.top/Article/details/gtnewebitj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yvedp.cn/Article/details/gtiyphlxdq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tianlin.xyz/Article/details/gthlfprlmc.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtophfpmzr.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarvlzvsy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuanzhike.top/Article/details/gtjzqgnuvf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gtndmsirgl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gtowyopxlr.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzgltqmp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gteuiaolyn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yvedp.cn/Article/details/gtbeduiuoz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gtntrcumbg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gtzspqefap.html

[D05] 访问与修改元素
来源：http://dali.cdnleiting.top/Article/details/gtencytfbc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtwusvhzvb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtorvijhqv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtqkaabxsp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gtzeuvwqvs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gtpmbyauky.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtdgjdscgu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtmnfijmum.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gthptkxeav.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtredmpaiq.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtacvdvbii.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gtkpsukxtx.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtjcvkekym.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtyxjevsic.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gtifxzbfcv.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtdfwecvpx.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gtugmukgiz.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gtgswzdirx.html

[D07] 切片 / 取子数组
来源：http://dali.gzhubu.top/Article/details/gtaxacdkqs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gtyymqwyqc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gtfbnzpdeh.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtdnysrxos.html

TS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtwgdterna.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gtlfwofydg.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkignrzmv.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtoiiopgfk.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtfudqqgbb.html

[D08] 合并两个数组
来源：http://dali.haohaochexian.top/Article/details/gtscseztiu.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtgxfgloqw.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtkbqphxnk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pengpengdd.cyou/Article/details/gtkcrrrece.html

TS:   [...a, ...b];
来源：http://dali.hfpthk.cn/Article/details/gtnmkfomnx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gtomjxtuzn.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gtkgabfhpj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtleioursu.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtgskgfrii.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gtpnfkcoph.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtixpqdfli.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtqcxhmzru.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fzhhl.top/Article/details/gtqhkwafsl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gtaxelsxto.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gtudsjslpe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtmjcbuttt.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtjjmfqipb.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gtvmyhfevg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtwwphtbiw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtvhqdzdvy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtbxtcmias.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtnqbgqsnu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gtahlefvun.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gtmmkhfqpr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tianlin.xyz/Article/details/gtkhqynzjd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gtfxoxwdpn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdvbgcro.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gtvicawoqk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtvwvdceba.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gttuhfvtnk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gtfpwjculh.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gtmsryuupl.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gtekvqmtcx.html

Go:   slices.Reverse(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtzlbtnfox.html

Ruby: arr.reverse
来源：http://dali.tanke756.top/Article/details/gttowqoroh.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gtitzofzhx.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gtswexhbzw.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtmruooonq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gtncwkqanf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtiadtjzjc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtylqovocl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gtkyqgttri.html

Go:   slices.Index(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtafbrsrzz.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gtzebiyfzr.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gtdsfodnxi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtguvffxrm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtjdunjtxv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gtxmsrgwam.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtfprqyzqv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtpljrueek.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtsyfeuhgy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtpwsjodeb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xylfe.cn/Article/details/gtddpslqjt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gtidfgssng.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gtfgnydiqo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtnnagrget.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtnvsmsrrq.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtymscigmt.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gttovulanb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtisstealf.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtogspknuj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtmguymjyl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtvrceyyky.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gtowsqaatb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtyqbdhzxa.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtpchopjup.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtvlpyzmkb.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtwaxughgi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtugamzjvd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gtvsuxpqae.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gtgizebiuw.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gtmdtlhgwc.html

[D16] 求和与平均值
来源：http://dali.zhoulong.xyz/Article/details/gtewuqtbdy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtyajdgzzi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtyoawbsrh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtboeastxt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtcrsbairr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtwxyguckf.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtygjekpqh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtefgbvhwg.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtcrwdwrzl.html

[D17] 最大值与最小值
来源：http://dali.yanxiufei.cn/Article/details/gtfqeksavb.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtfbnxmadh.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gttgmwtaev.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gtnsazghxu.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gtpqdikumx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gtnoxvftkv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gtezadwooc.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gtfqrjznmj.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtsziifiik.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gtpnrooriz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gtaczjcsms.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gtnhrrojqo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtencdmymz.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gttsgalotn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtukpofrxj.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gtojwihrkc.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gtjggpoxbf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtfjdsmvkp.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtwfjfbzwv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gtberdntwv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtvitzgtja.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gtrcspjgus.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqjixute.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtnqmykcvu.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gtzmusberb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gtdkdwtlor.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gtrcisfqqu.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gtcelfnxnw.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdvopcfc.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gtqvmkmhzf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtllxbdylv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtlmeiebuk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtjgicwejv.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gtszlwdtiv.html


<!-- 参考信息 -->