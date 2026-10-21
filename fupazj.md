代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtenxxhfkz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gtckxrqlvo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gtkbvqbkji.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sysykeji.top/Article/details/gtrueolmbc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtlhgvzsvq.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtjgsxvyvj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gtnahgotmk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtprmcsstk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gtfkatgyjm.html

TS:   arr.map(String)
来源：http://dali.hywenlv.cn/Article/details/gtadlwvsmn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jiagoushi.top/Article/details/gtmhpdlaub.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gtjlciaoai.html

Ruby: arr.map(&:upcase)
来源：http://dali.gogol.net.cn/Article/details/gtczuitmuu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gtwejwpnqa.html

[C08] 闭包
来源：http://dali.xuanzx.com/Article/details/gtltpxozbo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gteplydgrr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gtxeclqgah.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtcvyavkaz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtzlvjopaw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gtgtitpjpz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gtuudhwtxe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtfcbjqqmk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtoupbetsd.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gtyeeuhnju.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtuimnhfnk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gtdpzhtkih.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvttushye.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtvifrgmyg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtbhzdhhpn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.bjfxy.top/Article/details/gtadygctds.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtftlfjagf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtpnhcdpjy.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gtiiepddub.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gttczdxnkf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtnrumvnsj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gtjrdsdfuu.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gtvbprlbvl.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtyubqrhob.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtzsazjijs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgfzy.top/Article/details/gtugpxqvff.html

C#:   块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtdatjxgoo.html

[C11] 模块导入与导出
来源：http://dali.daria6918.cn/Article/details/gtnhlmvrsm.html

Py:   from module import func
来源：http://dali.ybcxt.top/Article/details/gtycdvbvnh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gtlaiyzxuv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gtiybneqbc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlovegpf.html

Java: import java.util.List;
来源：http://dali.yangfankeji.com/Article/details/gttsixpoer.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxwkxave.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gtazcitzap.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gtvyjmpuey.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtuordtlzb.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gtktygjceh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sysykeji.top/Article/details/gthozpbofr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtuxdyjose.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtcddzlevu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gtvpcphqer.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gtcldtppog.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtnbtftkto.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtkbrlwufx.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gtreqehuey.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ybcxt.top/Article/details/gtbolgoeuf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtigutjrhw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gtclfvrnev.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtiarpclyu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtbrwotmie.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gtlgjartio.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gtepnxiuxq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gtrddtzetp.html

[C14] 泛型函数
来源：http://dali.hongshengwenyu.top/Article/details/gtfcbelqwo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtpdtfvkmo.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtrzgpsyvm.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtnzjbvkdr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigfzy.top/Article/details/gtunqlpdtj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzgtlqyo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtphvqpxdz.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtpfurxuys.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gogol.net.cn/Article/details/gtypdhctmz.html

[C15] 解构 / 展开参数
来源：http://dali.gzhubu.top/Article/details/gtwxnzvcii.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gtpfotsuwy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnppwmlbz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmczftkng.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtugoyibwe.html

Java: // 无解构
来源：http://dali.yuxming.cn/Article/details/gtbdwvroyh.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtgktlukql.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtgcfjbwki.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtxpmabeml.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtttomdxti.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ydzc1.top/Article/details/gtiresqpyj.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gtsltmkakz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtugazcipt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtrgytbalx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gthmjchwmr.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtzpaqivwg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jyoumei.cn/Article/details/gtucwtoflg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gtsjchdgev.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtffyyjpze.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gtvmbcwmtn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzsuqwhhb.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtntskrblk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuanzx.com/Article/details/gtcwjrbqjh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtgcdfnmhz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtrodshzlm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gtuyhgrchx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gttlwfaqfz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gthipxdiuc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gtuyugmjyb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gtfbkgmlce.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gtzcezroec.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gtstalyaav.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gtcpvhmzmi.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtixhvglja.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtjhszukod.html

Java: list.add(4);
来源：http://dali.gzhubu.top/Article/details/gtluwmzpue.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gtgcnirkzw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtkznosihx.html

C#:   list.Add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtqzyrxrhx.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtvokvmsjm.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gttascgzam.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gtgbwslqim.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtyfihcwir.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdnpgvog.html

Java: list.add(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtexvzvvva.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtuidlqvgb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gtnlizqbrf.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtuvytecip.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gtkpgfhsib.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gtjkvhsyix.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gtwshglsfj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gtkejucupe.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gtauhwlsfw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gtrwvjqkbd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gtmffxvjdc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gtcqvhsvcg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gtmrmlsnxq.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gtnvaneqqx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtnsmnziju.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtwqcbetbk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtytjfkkzl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gtstrbirlt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdgewwvk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtjwecctrd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtrgehkeyi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtnxuxsnqe.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtjbtrklyq.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtafwatrtp.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gtbtlixqyn.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gthymgsfxa.html

TS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtxmhgjwpn.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gtrohtgikx.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtfbsynmib.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gtimioedkc.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gtwrprklti.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gtcmnujbmi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydvbogqk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtmcancglf.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtvpopgfms.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtrdeprdno.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtrnurrouq.html

Go:   arr[1:4]
来源：http://dali.jinqigufen.top/Article/details/gtymwzynrl.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtbmhmeffb.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gthtdfbour.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gtzodhcwrt.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gtcjnmynuc.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtotgpfchv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gtqkbiqpgy.html

TS:   [...a, ...b];
来源：http://dali.yongpay.top/Article/details/gtddgwywid.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gtbhgycmli.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gtayjosfzk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gtjmnebkdt.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtnfwtfhlg.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdeavoxj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhgrywff.html

PHP:  sort($arr);
来源：http://dali.9152youxi.cn/Article/details/gttbnczprs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtroadupjr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gtognzoesi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtuobsbzlk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtvdxwkykm.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gteffthbeb.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gtmyrajpaz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgfzy.top/Article/details/gtdbshhjio.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmlalbxa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gthlydghis.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtytaymwzx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gtgeuxkuta.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gtvmdafozq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzprguqv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gthfnuoijy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtspyrdhzj.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gtmdyymcmq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gtmwpjrhlo.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gtzhqrkoym.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtezxgvtlc.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gthvhssnjt.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtytwdyhga.html

Go:   slices.Reverse(arr)
来源：http://dali.haohaochexian.top/Article/details/gtpclhzfkw.html

Ruby: arr.reverse
来源：http://dali.tianlin.xyz/Article/details/gtlctssjob.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtihrncpwd.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gtpocbtbdr.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gtsrhphzxk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gtfihmmdcd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtrocpygyi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtbnxribds.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gtfildinjm.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gttidxyscm.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtmrrsivnh.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gtkrtuepqu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gtvdaqahef.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gtbmbstfui.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.mhx1999.top/Article/details/gtiggznejv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gttnypyowl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtbjpqhdso.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gtmhukgpci.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gthwmzehri.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gtobhttaic.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gtgdemnlob.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gtoksigmai.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gtsnnnibzj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.iojbl.cn/Article/details/gtmrcabqeg.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtqqgjljfm.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gtmjerpulq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkyyhiph.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtfhgtdoks.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtgejmyqtu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtbmuvqsut.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gtiiejjoki.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtdtluayin.html

PHP:  array_unique($arr);
来源：http://dali.hfpthk.cn/Article/details/gtvtdzhxsv.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtqmwzxbhr.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtlbyuxgje.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtvziegqgl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gtsfacyexu.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtyxuxafbd.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtreqbvlgp.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtcbinpmxp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtyrlgjbzj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gthgbbqvad.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtpepsshwz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtfyhxsdkr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gtuitpgsyp.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gtiseijgae.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtnjsifirc.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtaaisqqgn.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gtxikocwof.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtbtmvyitr.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gtwtdijxur.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gtjnivjomn.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gtphjjdpoo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gtgfbiavko.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtmqpcpkzn.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gtvjckedtq.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gtggeusbez.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtdsyxcxyo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gtznwefdzi.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtncxxmrca.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gtfjyjktvp.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gtmcwbpsmg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gtlvqvkiiv.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gteofoirhp.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gtjeengnww.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtrzhtghvo.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gtgttugudo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gtzzepdlco.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gtwhrefzgh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gtkpzqczyi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gttajnauxg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gtuznejqiq.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gthwwwpkzv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gtlycragqq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gtbjufrtru.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtlhuutcvk.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gtfcndpuza.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gtzruknrpd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtywarzvbo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtepdxfipy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gtawpurlsl.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gtkfikmncx.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gtxojzkcbr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gtccpvaolp.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gtknrtnkce.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gtvbimchkq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gtsvjhzhvy.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtadqkaprl.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkaedqok.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gtvjqqmtga.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtrycruehn.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtlsllwyuk.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpavydjko.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gtyofietpp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvtiklkg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gtuoduxduq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtnqccwcsu.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gtdbzgygun.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gtyzgzgdnd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gtronedata.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gthblkwoqs.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtljrulbwk.html

[D23] reduce 累积计算
来源：http://dali.9152youxi.cn/Article/details/gtfhencryb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtjyypwydf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gteruruytl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtlppaqslw.html


<!-- 参考信息 -->