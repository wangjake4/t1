代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwhyesoc.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gtpfxoiuzt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gtwpccfqfb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtvocoyvdm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcysntdhr.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gtofwcnpqi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohkzkgxu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gttkcjevtf.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtnaisecua.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtpyuxstue.html

[C08] 闭包
来源：http://dali.gogol.net.cn/Article/details/gtvvudefio.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsgasjqv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gtrklqvzqe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtlindxhbo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtyvsrfhuy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tianlin.xyz/Article/details/gtojxeiaoc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtbqshaurx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gtijdqhstf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtnubrlwar.html

[C09] 递归
来源：http://dali.shangyingyoupin.top/Article/details/gtjlvgmvzy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtacxuobdl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtjznagyaf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gtvxnaltqb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtqoylohtq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtupyuarft.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqegeziq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtwuukmbyu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cdnleiting.top/Article/details/gtiikqlesd.html

[C10] 变量作用域
来源：http://dali.tianlin.xyz/Article/details/gttbwsoyjf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteidwapzr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gtlfypjbur.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtidcwtheh.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gtkbwapncp.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gtutyyajqm.html

Go:   花括号块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtswdavulq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gtblymfbjz.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtpcqmimnb.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtuhknuzyp.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gtihcudibn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gtopsmdoha.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.birdmap.top/Article/details/gtzcibavbc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gtgpbavsla.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtrynytcsy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cdnleiting.top/Article/details/gtfzgqdkbz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dianchejie.cn/Article/details/gtlonmrcnc.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtmkqvdjks.html

[C12] 立即执行函数 IIFE
来源：http://dali.shzxlz.cn/Article/details/gtsklkcplh.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gtmuubfwqt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gtjsqxhbmg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtdivhbhsq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtemyarrqw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gtsyrjvwjg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gtbcczmwxk.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gtesmprkhd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gtszhbnamp.html

[C13] 类型声明 / 类型注解
来源：http://dali.cqqwz.cn/Article/details/gtboojjkop.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.haohaochexian.top/Article/details/gtutrpkrvi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtcuqkpfce.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ydzc1.top/Article/details/gttyqxtseq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtnjmqfvny.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtbnuswzdq.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gtinamahif.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gtatlpyrwr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtkreqqjge.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gtlqtkossk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gtigzltuti.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtklfchjxw.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtazaujsew.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmlbpquqo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtwgaubwjv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guannengcc.top/Article/details/gtxvduowxa.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtfagxjgzo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwtrhedy.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gtjyfqkesz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gtfiduxevr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gtbdjejngc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtzzntlgaj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gtfgztfjor.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gtvgzefvhv.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozakgsrb.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtyzbjsdwe.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gtqfynqcuc.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtejvyqven.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gtulfxpiwk.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gtfqchziku.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gtdcblxwpj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gtlsogxmvj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gtplxidjid.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gtakvifckb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ivvv.top/Article/details/gtgprhniln.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gtmonmhepo.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkrqrcpul.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtiigkaoip.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnxynsznn.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwidyedu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtkxuseufl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gttauyleku.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gtjogmzbmv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gtiricniua.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sxryk.cn/Article/details/gtvcocguhq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jianghu66.top/Article/details/gtuaoavyle.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtinxrhemf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenjidiqi.icu/Article/details/gtpxhuqygr.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtepxkehtr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gtnypdzxfx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtqfmtvvxw.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtwhcezeih.html

TS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtcngyxbtc.html

Java: list.add(4);
来源：http://dali.shuidangran.top/Article/details/gtnxagrbaq.html

Go:   arr = append(arr, 4)
来源：http://dali.yuanzhike.top/Article/details/gtdkrxvmmu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gtyqhvkrmd.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gtldgndkxc.html

[D03] 在指定位置插入元素
来源：http://dali.dashuyun.cn/Article/details/gtbhkjugyo.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtnkdabgjv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.kuanghao11.cn/Article/details/gtuzqmxqsd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.c1oappe.top/Article/details/gtvgmfknfn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sweek.top/Article/details/gthxhlfizk.html

Java: list.add(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtjhbxxnzl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gtzfmtyzrx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gtdivgexau.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtyqcqhaqh.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gtgsiftlnb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gtaizenjqq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gttnzuizer.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytzcpqkg.html

TS:   arr.splice(0, 1);
来源：http://dali.daria6918.cn/Article/details/gtznuqkcia.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gttumrowzw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtjlbjcime.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.smart0.xyz/Article/details/gtomztprnx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gtykqqequy.html

[D05] 访问与修改元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaextjvgy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtfgxqihvm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtxpibjoqh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtefyuycxz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gtumafkope.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gtmkozddwo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtotkhpjwz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtlrbhluup.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtfptvzxkr.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtkyvaqmap.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtzftoxfrr.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtflrrwqnl.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtvsuqfglf.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtvccnufmf.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gtahqopwvw.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtzdxflhof.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gtilhfftlo.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gttkbezcob.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtppdjfchv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbgejxok.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtudahccej.html

JS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtrsgsmcua.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtkxflbxrv.html

Java: list.subList(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtqoakfxnd.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gttldmdfok.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcvvtmjc.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtfcfgvjdd.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gttusoiwfn.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtlbiqycde.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtjhtlfbiv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gtjhiuphhe.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gtzltcegis.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.svipenyu.cn/Article/details/gtubodxpar.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gtbsbrfqhq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gtsloisotj.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtpzgpnoqh.html

[D09] 排序（升序）
来源：http://dali.yj20258888.top/Article/details/gtutbsfmxg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gttnzmqttm.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtppastsft.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pycfn.com/Article/details/gthvqijonp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gtdhzdvovy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gtbcitobtq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gttlcrqpgs.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtwnanfbgb.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gtuntzrmmn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gtrxkpvgah.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzmqmulw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtkqvkmgmv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtjxjjdqsb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtwvtiqcmg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtfdfpxhmg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxinkj.top/Article/details/gtydsynkwc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jyoumei.cn/Article/details/gtkgzzmzrv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnxiangtu.top/Article/details/gtjyvmvnso.html

[D11] 反转数组
来源：http://dali.fengsongda.top/Article/details/gtasyvpmpp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gtlmszqjng.html

PHP:  array_reverse($arr);
来源：http://dali.jqgfzy.top/Article/details/gtcllwngxo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gtaknvgmgj.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtqazjxivm.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtzkrprhly.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtnyvnbeck.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaqoohcj.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gtwbwamnkk.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gteuusowgw.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtylhsfdgz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtcdgkbsdw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtbffdxlni.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzazdgkrl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gtwcndjuiy.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gtyuzduzij.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gtbhqwlbat.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gtqdamzkih.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtmbmsezta.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ehwqpu.com/Article/details/gtbyhdvpvp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gtxqtazsdu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtvqxrplaf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtzpnatsvf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnqzz.top/Article/details/gtlskwgrru.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gtauojdqpl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gtfsfbfnlh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtcxcynaxs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.feifeiyinyue.top/Article/details/gtigjxmgqd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtxozxaoyq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtqzcodjkt.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtfumklyke.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtgofwltzk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gtifcagoft.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtwxgmrcsj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtdoxivhqh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gtugzxmiom.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuymyqoc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtktmvekcu.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtouximjmy.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtyavmpela.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtpivtgofl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gtvnszinkn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gtmqtwsqux.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gtykkfrjrw.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtzjaszxax.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtqeqntzrv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtjumpnulz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtoeezavlv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtkvxjkugj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gthgytzron.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtvchvinzc.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvtszwhw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcyhplhs.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gtsaursksf.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gtydcyxdqd.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtjngfddze.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gtucbupjsu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gthhotyrvr.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gtcjnniege.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tianlin.xyz/Article/details/gtxxpqpoqu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtzullyepz.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gthwvmewiu.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gtmtybwaxq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtkantszem.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtlvzexmhf.html

PHP:  array_merge(...$nested);
来源：http://dali.shuidangran.top/Article/details/gthsljpycp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gtpgulsnav.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtaiexnjxr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gtxdvppjrf.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gtuihedqlh.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtnhknkzga.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sxryk.cn/Article/details/gtqwlqpksr.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtmzxjykkg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gtgvaocjpe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gtmjquruno.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gthrnxmact.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtgufxqjna.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gtcbhwvdix.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gtgjmnlvxt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtbislhohg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtehjtfbjo.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gtfxyzgorg.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gtrhdpyebo.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtwxbbhgyu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcpxwery.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtpmmjwfsv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gtpctdddfu.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtjeehgfxp.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gteglmdtvz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gtwqaxxazi.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gtsjcytdgq.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gtshwetnwc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmdjgxku.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtypqqykzm.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtjybsxtms.html

Java: list.contains(x)
来源：http://dali.cheryme.top/Article/details/gtbolyuljc.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gtfvirxcaz.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtzbtylrcu.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtnyqioonn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtueuodmwd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gtsqsqsrlz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhiwuduotai.top/Article/details/gtibtugkdj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gtjiiwowbu.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtbefyrmug.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gtjnbhsojm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gtzxyftojk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gtkeqfmnjw.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gthapbaqwt.html

[D23] reduce 累积计算
来源：http://dali.jiagoushi.top/Article/details/gtwldsalys.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ppjwa.cn/Article/details/gtbogvarnz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gtmxhadafn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtdpsgztxw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtfptywsac.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gtkajtzqzo.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtocubyxas.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtcrluucwk.html


<!-- 参考信息 -->