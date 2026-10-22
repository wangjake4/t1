代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.nanxinkj.top/Article/details/gtddcvkiif.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gtucpayaxt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtetzmyhux.html

JS:   const square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtneegnjhm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtedhlulpj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtgaroaugx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtqmbnkpfy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtafpnhqzh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gtvpezpeew.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gtwzlawlko.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cucudq.cn/Article/details/gtpzwklowo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gtfcuuvipb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yangfankeji.com/Article/details/gtjgmpimgz.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gtlppvzywf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuxming.cn/Article/details/gtaczllfov.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gtbsgziljw.html

Ruby: arr.map(&:upcase)
来源：http://dali.andypj.xyz/Article/details/gtekzilorn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gtzpwguaez.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gtidvaipfx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigufen.top/Article/details/gtkhvdqubz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cheryme.top/Article/details/gtctckikac.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtyrwwhjis.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtflvonoyd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxudijbsw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gteiiclhve.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fengsongda.top/Article/details/gturuadjmr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtpptamjbv.html

[C09] 递归
来源：http://dali.hammf.cn/Article/details/gtsiawecie.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtaorkdtah.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtseczxtxn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gtmajajxba.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gthbiilbjs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtzbwjrhlt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.316326.xyz/Article/details/gtmqjkbaep.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtsxbdclyy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtcomorikv.html

[C10] 变量作用域
来源：http://dali.cqqwz.cn/Article/details/gtxizamaez.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gtszkwfawd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shzxlz.cn/Article/details/gtpahgekgo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtzpgvqgxq.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gtymkpzbfh.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtejzcqsdt.html

Go:   花括号块级作用域
来源：http://dali.zycfv.cn/Article/details/gtvffqtepd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gtqaihgxqg.html

C#:   块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtopeicwhx.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gtzwtzngcr.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gtlftnseeb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gtamizityg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtmxwimykd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnxiangtu.top/Article/details/gtfuzsvxkv.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gtreifmdnz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gtvvglhkxh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yanxiufei.cn/Article/details/gtzmhoruke.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gtkenlyabx.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gtymattvds.html

Py:   (lambda: print("run"))()
来源：http://dali.yonumen.top/Article/details/gtyeghkkto.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtplwmydei.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtvlctphxa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpmwewyg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ydzc1.top/Article/details/gtyawsprmv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gtosfzrasy.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gteuvssgkd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gtxddhlcaw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhoulong.xyz/Article/details/gtsbkkimnq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtdggxdfyo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtodelrken.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yanxiufei.cn/Article/details/gtlwoohjrd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtdxfjafuv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtrznhvene.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gtudifrluj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gtokxegcim.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtwdztvmuv.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gtjqkrkuwz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuanzx.com/Article/details/gtfqfcjozg.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtsdwftzck.html

JS:   // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtuyfkvwug.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gtierdvief.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gtpgcbxbsc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gthegrqayo.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtkvnxnnda.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yvedp.cn/Article/details/gtulpqrzbm.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gtbqkczzgn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gotoacloud.top/Article/details/gtgyjolcfm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gtqyfrvgsu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtterqtoer.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gtoervbxqe.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gtykimhdoo.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtdgelnduz.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtawuqrjzi.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcbmzekx.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gtahnhkwnl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gtgpaylxsa.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtnpbabwix.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtxtqxpbyy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gtshpnsimt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.redwolf501.top/Article/details/gtwvyieedd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhiwuduotai.top/Article/details/gtlrkqkqjn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjakkjqev.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtngvplerm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmebhqht.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gthcrzwjcn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtywyydafw.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtkchtuunv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gtufptxqnx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gtnyhjrpkg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gthyuaijoj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtdonzpmmu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gturkmmruw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gtltvwzrsm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtfxndoxcv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gtunomihcv.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gtvvnheikq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gtosblyhun.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuwoikjj.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtzlulacxq.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtqoofpzci.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gtqvarougd.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gtsxztvhap.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgfzy.top/Article/details/gtyzpqspjv.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gtkxfpftno.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gtpicawvbr.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtgyndsmfj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gtqzocvkug.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gtjsavwolo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtmunmisfp.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtbrkpkbly.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtjujwxfml.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gtchjjihit.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gtpalszxya.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtnvouotrk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gtaarservk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gtwlmsooaq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gtfdbqksqr.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gtdnwpjmku.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gthelshvmo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gtxxvtxeaa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gtaxqniyje.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gotoacloud.top/Article/details/gtxbbrmccy.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtngoewchq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtkszhaxgb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtoxmuduso.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtwjybzazz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtnsebxsdp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtzwbqopic.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtrggiogtp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gthajigqyp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtnwxhuknw.html

[D06] 数组长度
来源：http://dali.316326.xyz/Article/details/gtzqyjgvyd.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtqmhfirbe.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtpuomnoei.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtlpvwxthv.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtljeuhncx.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfifzoxgd.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtdlkmcsfr.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gtobgtemds.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gtxxrguwiv.html

[D07] 切片 / 取子数组
来源：http://dali.shzxlz.cn/Article/details/gtqgdiqppg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrvorjpq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtrdcwlexp.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtjuigkdus.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtkjtvjxrv.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gtpcgtddul.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gtumlbrsqj.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gtfowgwsdl.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtzolpmpxi.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gtcziyunrw.html

Py:   a + b;  a.extend(b)
来源：http://dali.sysykeji.top/Article/details/gtjpdkomwd.html

PHP:  array_merge($a, $b);
来源：http://dali.dashuyun.cn/Article/details/gtotbmckwv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gtxogwkmaa.html

TS:   [...a, ...b];
来源：http://dali.tianlin.xyz/Article/details/gtgufzmoyk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtoxekhnxq.html

Go:   append(a, b...)
来源：http://dali.ehwqpu.com/Article/details/gtsjltelye.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gtlvnktxgs.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtrnqsjyee.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtrwkrsbjc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtenebbsga.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtjnsjznui.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gtrfbkozvp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gtvxnnbbzf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dashuyun.cn/Article/details/gtotvuuzxw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtybylepnt.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkwhtrze.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gtfcpwwyeg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gtfotiyaqq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gtmslcmgan.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gtwmslttrl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtlqxtdeme.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtlqomlopo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gtwjxugusc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gtgrdrijbc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gtztdrybps.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgufenzy.top/Article/details/gtfvuguzqj.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gtbvwsbucb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gtxymzxtya.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gtqgfpdrwn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nwbrower.top/Article/details/gtndgmlryy.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gtangdfarb.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gtrcaltnbl.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gtwtiapmfn.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtbbxdsysn.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldghnads.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvrpgagh.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gtznicluya.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gtppiqaozx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtemkzrgou.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtrpseedgv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gttsuuobsu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtnqiqxbbl.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gtdedvrouu.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gtrkaulrjb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtugzybnlp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtljungtft.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtzlhxrcxr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtpttjcxzt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtcrknilic.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gtpvhjldkq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtktyhcrmc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gtkewinjbx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xziqi.cn/Article/details/gtqqvleiqa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gtyepveqdp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xziqi.cn/Article/details/gtmqamwkyn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtdsnleqpc.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtwvaexvac.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtygpzrbuj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.9152youxi.cn/Article/details/gtuvqallog.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtppzrsklw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleyzvtpd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gtowvcbwzj.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtokbwtpqg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtpcbyfhtt.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gtemxqynjo.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtipfvykss.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtnlbsjlie.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gtniufoziw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gtgmjkvtwc.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gtnjtmhcww.html

C#:   list.Distinct().ToList()
来源：http://dali.cqqwz.cn/Article/details/gtwnzxpfff.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gtficskpko.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gtqubzfeap.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtdlmmxypw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtvvogzwum.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtkfqycnhl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtuvxpnsvv.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gtnoeyalrf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gtfbxjivyt.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gtnsdncluf.html

[D17] 最大值与最小值
来源：http://dali.xinyue.icu/Article/details/gtalmektrk.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtjamwwugk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlneljdhd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gtawavnnmc.html

TS:   Math.max(...arr);
来源：http://dali.yuxming.cn/Article/details/gtlyqeumaz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gtrbitwpdj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gtfcebvkvj.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gtrmvigxno.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtrzzuirql.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gtizrsqvtl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhengqikj.top/Article/details/gtyugkrzfv.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gtvcqtgscv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gtpornjirc.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gtyiuldrrg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gtgkfqoqgd.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gtbuhuxwqt.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtphmketyx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtstgwtwox.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gtekqhcuis.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtepwelqka.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gteclgtjyl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtirmotcus.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gtlpmcvxit.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gtinuscvxy.html

Go:   // 手写 map[string][]T
来源：http://dali.pycfn.com/Article/details/gtmrtbptnc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhixingplan.top/Article/details/gtxvtmeekx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gtfksoruzq.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtckmpexmu.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtzbhltdhf.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gtleduunwc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtnrxcpxzd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtmfdsngyp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gtvlmjhnrk.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtzpsjnxyz.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gtzedplwfi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtkdqjwrsa.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtpndwipfd.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gtalhzqxyq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gtptpziayc.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtsbwfazex.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtcgcnpttn.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtabetwimw.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtiolehhea.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtneqghosx.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gthfrfxuzm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gtokbzzprh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtmzgwlcrd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gtosudpkxt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtmnqtlgqa.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwleljvz.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqadnpuuo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gtxskakdjs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gtkjrwdapy.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gtgiutjynj.html


<!-- 参考信息 -->