代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtuhbhwvly.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtgnkwrngi.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtynwfjkzv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gtizaaidsk.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gtuwcgvchm.html

Py:   square = lambda x: x * x
来源：http://dali.iojbl.cn/Article/details/gtmfuypleo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuawszcq.html

JS:   const square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtgfmhabwx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtmedwjbwd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nwbrower.top/Article/details/gttmjxiyys.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gtuwanginh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenzaomai.com/Article/details/gtbknxjlyj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtvjvzuvgf.html

[C07] 把函数作为参数传入
来源：http://dali.9152youxi.cn/Article/details/gtzefqgjyn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yonumen.top/Article/details/gtwuwuypcm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtnturftlt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gtebpaitkm.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gtptzhilxe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtfcsispbu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gtvuxwczzm.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfrcevri.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gthglnbayw.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gtgidrcdai.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtjybgsffy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtbdcdoqfn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtdbggrgms.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtqfgcikwo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gaohongyu789.top/Article/details/gtsjeekugp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenjidiqi.icu/Article/details/gttijobtwx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gtzvnnkbjs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtvmdgcqmy.html

[C09] 递归
来源：http://dali.ivvv.top/Article/details/gtqtsewexp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtsmfgoiks.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtyslvcstd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtimmfomhb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtkqbyxxar.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pycfn.com/Article/details/gtrftaaufe.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwqlbnfx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gtqzrfoalq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gtrvazmshb.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gtkiysrukb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tian-w.cn/Article/details/gtwzfxdbqr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gtjfhnkmzm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgfzy.top/Article/details/gtgjxcwkzu.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gtvlfnzglm.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gtkxnjqweq.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gtvvwgalbt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtssnfkqlg.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gthnvvycmx.html

[C11] 模块导入与导出
来源：http://dali.yongpay.top/Article/details/gtnaykvmzw.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gtxjcdiyhn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrvfsykc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwkcbqyo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tian-w.cn/Article/details/gtsmyscoie.html

Java: import java.util.List;
来源：http://dali.hnxiangtu.top/Article/details/gtrdtpuums.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gtyjfwprda.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.bjfxy.top/Article/details/gtepzmdltm.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gtnvttwpsw.html

[C12] 立即执行函数 IIFE
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhkjwyff.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gtbftwfjar.html

PHP:  (function () { echo "run"; })();
来源：http://dali.birdmap.top/Article/details/gtcurtypbv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtatsljnws.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtopuenxgp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gtagsdtgap.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangtech.top/Article/details/gtavjizcld.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gtzatdkzcw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtzhykxqdg.html

[C13] 类型声明 / 类型注解
来源：http://dali.zycfv.cn/Article/details/gtuzqugqbt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gtmceokwca.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtitggrpuu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtfemmjeuv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktvpwzyu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtcvuhvkno.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtksifwrgm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbtftlwr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtxjxjfqxo.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtiadvflch.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gtbyevaalo.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtcwjpuoxz.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtpjlelbvk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gtfzqxdkza.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gtbmkfmfqd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shangyingyoupin.top/Article/details/gtlacvittf.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gtklhsbqdy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gtpyzlycoj.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gtnbmxkdou.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtbsoysyri.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gtsqnduuum.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtoeixgjfb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuzucjkb.html

Java: // 无解构
来源：http://dali.redwolf501.top/Article/details/gthhjdvvto.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtzdyiawaz.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgkgnqto.html

C#:   var (a, b) = pair;
来源：http://dali.hywenlv.cn/Article/details/gttezsrtwl.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gtzikgztqw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtexijoric.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gtsuqrzhgu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gtxhubehgt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gtyxmmxndg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gtsmvxfvid.html

Go:   // 无重载：用不同函数名
来源：http://dali.ivvv.top/Article/details/gtsfuyolxb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gtxauylagn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gtlkoqrvku.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqxdhtfig.html

D. 数组 / 列表 / 集合
来源：http://dali.vqdsnc.cn/Article/details/gtbumzumtd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyowjpcj.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtqwttkffl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gtjzanslkj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtwqhnyzqp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtguwhilkm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gtnflhqfkj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gtgpbnwkbe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gtdjvwvdxa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtqomrlzya.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gttcfvrzmc.html

[D02] 追加元素到末尾
来源：http://dali.shuidangran.top/Article/details/gtyschpdag.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtznhmjrxq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtqwfhntbn.html

JS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtpmdoverh.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtcdsuxaql.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtqbylxfis.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gtejaqgdut.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtytztvvoq.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gtnutvncns.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtkrwmkpju.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gtsitiayhm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigfzy.top/Article/details/gtbjuwnaae.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gtzxzvzvuw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtzgelxjvw.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtnuxchdqv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtsarsgwll.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gtwtjneakw.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtkenwbtxq.html

[D04] 删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtligbkxyz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaixbkuq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtxvquhecn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.quarkkingdee.top/Article/details/gtwohyzuih.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtgtqxtrab.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gtfapnrlxa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtwroameme.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gtnzoyfwiq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gtpnisyayk.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrfwpnyd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtwmubdilj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtgitxcgzn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtrcasurmv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gtuxuscnom.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gticrctlpy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrnbkcfe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtwawfgqxf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtlgbkpgij.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gtbzqiadsc.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtzjtpuxdb.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtunadiuif.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtjfbcmbhh.html

TS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtzahosvjz.html

Java: list.size();
来源：http://dali.zycfv.cn/Article/details/gtuvindtke.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtwszfxnsh.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtnopgiyby.html

C#:   list.Count;
来源：http://dali.feifeiyinyue.top/Article/details/gtmgsawymp.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gtamjluexp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gtktsukgzo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtlxhussex.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtcozrhkbg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtgtybmjbj.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtsngqgque.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gthxlmxfhk.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gtgfminwgv.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gthnzexynd.html

[D08] 合并两个数组
来源：http://dali.aizwys.cn/Article/details/gtsmrfjahz.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtpjogayvz.html

PHP:  array_merge($a, $b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsunfsll.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shzxlz.cn/Article/details/gtwohlolmm.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gttzrquxmn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jiagoushi.top/Article/details/gtrehlyonx.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtrcggsvaa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zdqjudy.top/Article/details/gtztqadrca.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gtafmmqgbf.html

[D09] 排序（升序）
来源：http://dali.gzhubu.top/Article/details/gtvoptlnzk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtneyxhtkb.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtxlgvjlif.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gtsocwkhcn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtiwwxbtur.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gtzkaleiwp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtyqeyxcub.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtyjfbxvbz.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtztdxgsoy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jianghu66.top/Article/details/gthnttczaq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gttcyiierl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtdsfhjqzs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtdecdvvxo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gthfhetexc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtaeiihwsa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gtdiobbtyh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtezphcnua.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gtozamtjmu.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gtagwrelnr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtaoitljbl.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtlhwuswzq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gtebvdrbum.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gtwbaebbci.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gtpbupgtuh.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtvjyxodot.html

Ruby: arr.reverse
来源：http://dali.havefunace.top/Article/details/gtsmztehej.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtemmskuhd.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gtqfhjfaei.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gttkggtpzi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gtkgrsfvgm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtbcbkhliv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gttlxdumlg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gttvlbojoh.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtseufwiel.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gtftvufszf.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gtxdstrxra.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pycfn.com/Article/details/gtunuyphic.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldisqtqy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gtrmyoeorb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtgqbfjrhf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtaxawfauv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtbnunlbef.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.bjfxy.top/Article/details/gticzmspxx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gtxszupkbz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtasgtuwoe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gtizblzpyh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gttuvqyokw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtjwcsrgax.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gthjjnrjaf.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtabbflwtf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtzotudmwu.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtfpvlhppx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtdblbgrzn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gtpfyaskqp.html

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gtexaknglb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtkfdhxakw.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtndnjhhlk.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtfcunaffs.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtsmkykbtl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtlmgignch.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gtvcdrbqww.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gtgkiffkhb.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtahdsdswu.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtzzhyreeu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtghclusey.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gterzqffoq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtnhyacbmk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtaffwjpls.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gtuaradwnw.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gtmcnnvfsi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gtpqvsjfvj.html

C#:   list.Sum();  list.Average()
来源：http://dali.yongpay.top/Article/details/gtqjoozzkk.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gtrkcqwzex.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtxglootgs.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gtafontoco.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtuhdbggvt.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gtfxpnlfjk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gtllzazdsj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yueranfly.top/Article/details/gtxuzqdadq.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gtlhrqyegn.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gttpouwrsh.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gtlyyfapkn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gtfagyddtl.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtqxfofcgh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gtkhxrzvtc.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtirwofvje.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtwugalemy.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gtmycjhylm.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gtffpyzqdy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtenkbogjo.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gtlikgnzvw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gttahjjflx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gtavgwcnbs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtaxyamrhl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtpcnbmtve.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gtvezaibso.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gtgzvrcoux.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtxzwdands.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gtwlinlgqx.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gtbjwlpzti.html

Py:   Counter(arr)
来源：http://dali.yj20258888.top/Article/details/gtpgkivvmt.html

PHP:  array_count_values($arr);
来源：http://dali.xziqi.cn/Article/details/gtqbimudfa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtusqhmnli.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtfthycyzp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gthijnwzoi.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtivgxmrhe.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtgroxpbko.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gtmdfxineu.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gtazsbcjiz.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtfeziwdcx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gttkxchlpa.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtsgimkywz.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gteljlcsbe.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtzwtlozgq.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gtuyhsvruy.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gtplacpopn.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtljhsnvit.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gtlwhayail.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gtkwqciewd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gtuzmmggbm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtfdaanazz.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfuvfoyv.html


<!-- 参考信息 -->