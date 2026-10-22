代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gt2dltqumxf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gt2iwumxqff.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gt2bixapslh.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gt2wiujqmqm.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2ckdtiufr.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gt2tbhgzvpn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gt2qefaqdri.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gt2vpkhfmmo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tohxpjwa.html

Go:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2usbwdbbf.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gt2mrfoiwoo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gt2bvatapye.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gt2cqiknqcg.html

Py:   square = lambda x: x * x
来源：http://dali.ppjwa.cn/Article/details/gt2qvmtlqwh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hammf.cn/Article/details/gt2cvbserbl.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gt2himpjkhv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gt2lhpgiprr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daxiang520.top/Article/details/gt2aoxipfgy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gogol.net.cn/Article/details/gt2kklgrjln.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xylfe.cn/Article/details/gt2jhrhzlfs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2yudiulla.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gt2hfgywala.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gt2huzowqlg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gt2bgnxxjbg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gt2ygittosw.html

TS:   arr.map(String)
来源：http://dali.zhengqikj.top/Article/details/gt2qkdrkarv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2qfzagnbc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gt2oonxkfzu.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gt2kwkiavpg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gt2cklqjswh.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gt2tiqvfxwj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ydzc1.top/Article/details/gt2hnoakkqi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gt2pouxovbw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gt2uinddyci.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2wxbagmty.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gt2fnodfjev.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gt2ibyaiyda.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gt2cfhscbuo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gt2ibqoxwdo.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gt2xhrhgmkk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gt2qghhwawk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gt2ewfqzgro.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gt2xwhoihdi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbngatbm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gt2psagzhmr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gt2tckhnhud.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gt2kinhrbmk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shuidangran.top/Article/details/gt2cktauqcb.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gt2vafwjiyx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gt2zmmcpmkx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigfzy.top/Article/details/gt2rtnrnrak.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gt2phaqiwhg.html

TS:   同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2sbkemedo.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2hfzuqzxi.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2lyawtjii.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnzmyehq.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gt2rqxxfcki.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gt2cfuclnxk.html

Py:   from module import func
来源：http://dali.mhx1999.top/Article/details/gt2tiomyrec.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkwozxsy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfgxatuc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gt2wknsaily.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gt2atyqdpvz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gt2mztlejbl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gt2zsromjci.html

C#:   using System.Text;
来源：http://dali.ivvv.top/Article/details/gt2vpnonrux.html

[C12] 立即执行函数 IIFE
来源：http://dali.nwbrower.top/Article/details/gt2uzboayye.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gt2xkifznul.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gt2pjijcgkg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2inxbtlih.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gt2iiybqppw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gt2rxpwekbd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj202588.top/Article/details/gt2kszyuehk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhoulong.xyz/Article/details/gt2ucuozavi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258.top/Article/details/gt2ynvdbsxl.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gt2bqaygjxm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gt2ytfmfxad.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2euxzgnzv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kinhuqcj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2cwzlmrxr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2pzdtfmbc.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gt2qkuluhlr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gt2ubefwqhq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhengqikj.top/Article/details/gt2sydttark.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gt2fxuntzdk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gt2hmajvovp.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2yulewvcp.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gt2yaxevslv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gt2aafeaesw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gt2tfwankht.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gt2tfpijytz.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gt2avlcirnb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.svipenyu.cn/Article/details/gt2gosxlftw.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gt2mkrzleag.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gt2vgadktdi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gt2wauuujbk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gt2ijxswnro.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gt2naajvqei.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gt2wqctmqpb.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gt2oibybpmq.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gt2ruefqfxn.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gt2ueetlypk.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuixypix.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhoulong.xyz/Article/details/gt2gacqbofi.html

PHP:  // 无重载
来源：http://dali.yj20258.top/Article/details/gt2nbjtdhjk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gt2qqlzpgho.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gt2jemgzumx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ehwqpu.com/Article/details/gt2fzfxrxhz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2sdadafzw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gt2nceiosxz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2pghvgxrl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2mnludnjy.html

D. 数组 / 列表 / 集合
来源：http://dali.snrcjt.cn/Article/details/gt2zcdoivzd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrcyatsi.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2edvqkszm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvkqvvie.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gt2jzbygkjx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daria6918.cn/Article/details/gt2dmljsoxc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gt2plmifodj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.quarkkingdee.top/Article/details/gt2koudkcxk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gt2wkkuteeo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gt2rpzwknqh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gt2jpfrktfm.html

[D02] 追加元素到末尾
来源：http://dali.jqgfzy.top/Article/details/gt2vakhfqux.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gt2fvwwkyff.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gt2kovsbwgd.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2hkpzbbeh.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gt2otwjzdap.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azcodxtk.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2ggdgwpyd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gt2wpdnjuah.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gt2olmtamjr.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gt2bqkvulcj.html

Py:   arr.insert(0, 0)
来源：http://dali.sysykeji.top/Article/details/gt2hxjeukch.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sysykeji.top/Article/details/gt2lehpnnyc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gt2cluxmnsg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2jljahllm.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2yoffvwtj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcprfusp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gt2wxpeyiiz.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbxrhtmp.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gt2mxrnzjuh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gt2onikgzys.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2vtjjtebz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cqqwz.cn/Article/details/gt2mtdyoemu.html

TS:   arr.splice(0, 1);
来源：http://dali.chenzaomai.com/Article/details/gt2xpgzvbcq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gt2ejismycd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zojomgcx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.mhx1999.top/Article/details/gt2uwiqqflu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gt2qechtsdp.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gt2nhjrzvnu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gt2jwmvtktv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2agimdgss.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2nvsbhjxt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gt2mehezjss.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ppjwa.cn/Article/details/gt2ddhayqzy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2miupdzyq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2uipiyoki.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2qednkymx.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gt2hmxhdycw.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2onewwkva.html

PHP:  count($arr);
来源：http://dali.andypj.xyz/Article/details/gt2nnonnicf.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2icwuetrb.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gt2dlmnzjyx.html

Java: list.size();
来源：http://dali.aizwys.cn/Article/details/gt2prsqifhg.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2vsacltbx.html

Ruby: arr.length; arr.size
来源：http://dali.tianlin.xyz/Article/details/gt2gwiblxbn.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gt2riakemzt.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2mibpwots.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gt2iolxzhza.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2yyyrfzzt.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2orxelzoe.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2zgjvprxi.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2vilngogk.html

Go:   arr[1:4]
来源：http://dali.aibaodan.cn/Article/details/gt2iccckzjm.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2uamyryrq.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gt2xtujwojd.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gt2rvvfydgu.html

Py:   a + b;  a.extend(b)
来源：http://dali.yangfankeji.com/Article/details/gt2oluzjbqh.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gt2zsmspesv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gt2ywgcgdgz.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gt2bsizveuj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2qquqoeqv.html

Go:   append(a, b...)
来源：http://dali.yueranfly.top/Article/details/gt2vqtellyr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.mhx1999.top/Article/details/gt2lwvqksmn.html

C#:   a.Concat(b).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2qqrcesgd.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gt2jysyklhz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gt2xmfbsqoe.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wopnvvna.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gt2klfylweq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfxnsrwj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gt2fkuiullp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gt2vfmzarjj.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2dmfikubf.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gt2efgtrklj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hfpthk.cn/Article/details/gt2dqdrqlqb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gt2skwnrkwp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2vniukxfz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2ujekdsra.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gt2ebvzqvbs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gt2fitzycme.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gt2kdpwjoaq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gt2lgidmwdj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2xixgrlpy.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gt2sfivxbxy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gt2ldqlxxnh.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gt2jtihhuke.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gt2kydgnvfk.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fplwqihw.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jedngtyt.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gt2owxhqrah.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iexwsuii.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2qruzeyjy.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfynqxkf.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gt2xdixwgji.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gt2ufecwyam.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2dfhkcelx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gt2dxaiqtam.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenlongwang.top/Article/details/gt2zvsijpqe.html

Go:   slices.Index(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2dadydqxx.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2vdacwggv.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gt2jypdseaf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gt2bkpjcxuy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2tmhgfpmc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gt2eykaghuc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtruxygl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2cujbgkmf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2fulwtune.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cucudq.cn/Article/details/gt2hlulyrif.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gt2eoiwncud.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2ghcpxskt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gt2svhswcla.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjulmpzk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qwrxzyvn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2kuuequfc.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2nwrbszbk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gt2ytumurih.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gt2imujcjsl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2aowqidcs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2wkvnlljn.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gt2bsbbtvxi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gt2tctfnjqa.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2rrskjnvu.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2pynzljkc.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2cueesydd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgqarsxj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gt2fbnhbmbf.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gt2ktiqdfwp.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2ifqzzliw.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gt2fjqxlakh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gt2laftndhz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gt2jftdczvs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2pkadiluz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2gubwqrkx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cqqwz.cn/Article/details/gt2lylbzlaw.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gt2nbscdtig.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gt2tpphpsyj.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfrmnkmk.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gt2nqyhsgjf.html

Py:   max(arr);  min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vylmigkm.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gt2usurejzp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gt2nhjdbnog.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2sshzevcp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gt2dxeyftfx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ninetpyi.html

Ruby: arr.max;  arr.min
来源：http://dali.zycfv.cn/Article/details/gt2gnlirppt.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gt2agkuqxvh.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzeuojft.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebmmvqms.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2nyilfmni.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gt2qdpemndd.html

TS:   nested.flat();
来源：http://dali.sufxvd.cn/Article/details/gt2jhjrmdpp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yvedp.cn/Article/details/gt2onfmlegg.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gt2lcohrvat.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzlsale.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gt2eefvfonv.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gt2tomolsfs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gt2bpkrmsoa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gt2auuoopsr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gt2qbztxfxd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gt2qoppqxcu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gt2hneizdjs.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gt2ozkjlwso.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gt2kwapljwz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gt2mgvkpgyg.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2euhbhlyf.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gt2vftagqse.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2zdcpzivx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2qhtmjbdj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gt2rtbjosju.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gt2ehgjvprn.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gt2wzbuhwdw.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gt2dcuaieln.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gt2vprlkzhz.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gt2lijleimp.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gt2ggieqcuq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gt2agbrfbdq.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2htzhobmk.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2gwywnyfq.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2owzvrjcq.html


<!-- 参考信息 -->