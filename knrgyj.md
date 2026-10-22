代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2zzzbcvsy.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gt2javryzmq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwwbewqd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2lcwgkcox.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gt2bsdtrfyn.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gt2arcyybbt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gt2tvcdpoow.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gt2sxqdocei.html

Ruby: arr.map(&:upcase)
来源：http://dali.hammf.cn/Article/details/gt2zaffawcs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gt2dtklqqsn.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gt2mbjwowdm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gt2eyqghlpl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gt2tbdjizvg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gptppehh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2bbnitvvi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gt2hpoeulke.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gt2ssdvoxks.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gt2yslawxrh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2wfsfmrvl.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gt2lecuhkxt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gt2hixbslwj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.316326.xyz/Article/details/gt2yptupdbq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gt2qhrjovgy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gt2sjzwwrrr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2lqcsrske.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2topoeyhb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gt2zafgirjo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnfxxtii.html

[C10] 变量作用域
来源：http://dali.ppjwa.cn/Article/details/gt2mfzgwmzb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gt2bigqfifv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.316326.xyz/Article/details/gt2cluzhtud.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gt2ggdqcfsl.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2hprzhnej.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2lsblrmyh.html

Go:   花括号块级作用域
来源：http://dali.sweek.top/Article/details/gt2winvvmvl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gt2ertmyhge.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2nrnmvlvz.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gt2hvajehvo.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gt2hqphyywv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gt2djzunjbp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfczrgky.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgjowgxt.html

Java: import java.util.List;
来源：http://dali.sufxvd.cn/Article/details/gt2wvhurscw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.0kj1m.cn/Article/details/gt2gtyvyimw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gt2gzwnoexx.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gt2xjljtyrz.html

[C12] 立即执行函数 IIFE
来源：http://dali.guowangkeji.top/Article/details/gt2ypngfkxi.html

Py:   (lambda: print("run"))()
来源：http://dali.jlsjyb.cn/Article/details/gt2unqfvsaj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gt2qwnnrukq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqldrnhq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gt2nzlcgqyc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gt2heqlcycq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daria6918.cn/Article/details/gt2tyrzwusw.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gt2gxeodkbo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2prntxkms.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gt2nkmhvlfg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ivvv.top/Article/details/gt2rzetfqzi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2ybzzzifb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gt2dhvudkdb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2aacesyje.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2lzikmdki.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gt2oatlotmt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gt2acuibtze.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ivvv.top/Article/details/gt2mkrtdarg.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gt2ibujimzj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gt2mztkukuf.html

PHP:  // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2oclwivqq.html

JS:   // 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2vbmhrwcs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gt2dzwjpcof.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gt2wyeqrmmd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xylfe.cn/Article/details/gt2yqyqtjys.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2ntocnwcl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gt2ywsmavup.html

[C15] 解构 / 展开参数
来源：http://dali.havefunace.top/Article/details/gt2hvcoonks.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gt2peuecebz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gt2wqnribrb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gt2xbejaifm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gt2fbherrok.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgjayivr.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gt2tprmdbtu.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwbcdmzb.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhgmyzsq.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gt2nhlqsbqg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gt2bblgpckf.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gt2howscupl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gt2sboqozqv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gogol.net.cn/Article/details/gt2nzcfedse.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2jathobhv.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gt2hjwljian.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gt2etcfaugz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gt2lkxixtqx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2kskwtoir.html

D. 数组 / 列表 / 集合
来源：http://dali.vqdsnc.cn/Article/details/gt2aesvldfd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2sgauyyac.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgpkrkzg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gt2hcxzazyy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2tomlnpip.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gt2xdhicpkr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gogol.net.cn/Article/details/gt2zvkpbvoq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gt2udpgqljw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ouidhplj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gt2kafnajom.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.vqdsnc.cn/Article/details/gt2rfninwxc.html

[D02] 追加元素到末尾
来源：http://dali.guannengcc.top/Article/details/gt2hqftgzva.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxzxyveb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gt2seqeopee.html

JS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gt2nqiqkssm.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2yfyqqxbp.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2drjjmffx.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gt2azljdahx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gt2rhkpcgys.html

C#:   list.Add(4);
来源：http://dali.yuxming.cn/Article/details/gt2pwwgqlkz.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gt2gcduyxwy.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gt2cenicsuq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ppjwa.cn/Article/details/gt2zsfxcsro.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhzelbuw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2mmjrrynz.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2qkdppflb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gt2rfaupdwh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.c1oappe.top/Article/details/gt2ywognryx.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2xginkvyk.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2onrdptvd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gt2zcnsmtqw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2phetiude.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gt2tjbdyifk.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gt2rbfztych.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gt2jiygcgrj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gt2hsgsgckg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gt2ucbflkfs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gt2syrcpmsp.html

[D05] 访问与修改元素
来源：http://dali.wangdashe.top/Article/details/gt2gemkcbrv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2ikuorohj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2soseexsz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gt2pnvrlcoi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gt2gydqbvyd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gt2oyibeadt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gt2tjabjiyv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2zbicyuon.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2yzfhkbch.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gt2fdmdgatf.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gt2ibcdffgx.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gt2mbsvfemi.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gt2pyopkzad.html

TS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gt2bymayrlr.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gt2vsoikbfh.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2jgdmlbdn.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gt2iknlaqvv.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gt2ktrmfvdd.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gt2rebadqle.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gt2pylhfoqc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gt2mfbxfedb.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2oqxfaelj.html

TS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gt2bhmhnjjy.html

Java: list.subList(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2tiiaedbq.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gt2lcldlozb.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gt2anukeqjb.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2svqoclpa.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gt2gwdpjetr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2yeusvmvi.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gt2ctkhljiw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gt2fuoqpygk.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gt2lhnsezfm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2pheyumvp.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gt2ajfrrvgv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gt2xiastpvi.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2raxuqvjh.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qykhptcc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gt2vymmskuf.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gt2ougweiro.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gt2ttajzjfm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gt2icqapurt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gt2zxkzaexj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gt2zlavywhj.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gt2mivbvwqt.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gt2qrmyggyh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gt2wqpdfnbg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gt2uwylpbav.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2abxkvkcp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gt2cgzddkwr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2dacsbbqo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gt2vowgmuzd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gt2mgnwdebf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gt2xjizdkja.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gt2rsckiakw.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gt2lumhhyjs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gt2iyugpvdu.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gt2dqwrbnxd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gt2poojlvqo.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gt2tqqyggbi.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odrtibkm.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnvyzudk.html

Ruby: arr.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2rcqkkrwa.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gt2fenpdvbx.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gt2upbcmvtz.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxinkj.top/Article/details/gt2ipmmcafx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gt2keftwbuu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbfzwhdx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2gktofyor.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gt2scrisjjw.html

Go:   slices.Index(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2rtkqdtdt.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gt2hndnjbkt.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gt2qhkjzsia.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gt2fwnqvwte.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gt2owcsgoib.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gt2rrwbitea.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gt2okxuhyjr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gt2dphqjvwp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2gjdcmtff.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gt2cxzfqzmq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gt2yxpbyudd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2fojioqaf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sweek.top/Article/details/gt2pcsutmcx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gt2qpidncmg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gt2kpcyyugt.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2ufwiqhad.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2qqfxcjsq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2iyovzpqm.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gt2sblnuozh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gt2wdjxrkrc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2pmbxgpsk.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owrrvdte.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gt2zhetnqel.html

PHP:  array_unique($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2rfebmoip.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2gypikrjg.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2tbvqjhvm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gt2eiuyvdde.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gt2tsrsqnyg.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gt2hjlaeevk.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2ixlnciqz.html

[D16] 求和与平均值
来源：http://dali.gogol.net.cn/Article/details/gt2mjnlkdmf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xylfe.cn/Article/details/gt2pefxggrg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2zyofjnxx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2ycmtbidr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyxafcus.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gt2twkawilp.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gt2rglfixkw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2kmbxairp.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gt2ljyiykfa.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gt2zmgehhhd.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2tqdxtqon.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pphbdmxx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gt2fractmlm.html

TS:   Math.max(...arr);
来源：http://dali.aizwys.cn/Article/details/gt2emdaotoc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gt2qpcgfdyn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gt2psmloadq.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gt2cikqnjvd.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gt2kvyfkdxh.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gt2wxzklwco.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gt2bwnxyxju.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gt2zdotdfge.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xseivohj.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mwyvefwq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gt2hvucrfth.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gt2uxvhavuw.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gt2hccewywa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2xnoemfzm.html

[D19] 按字段分组
来源：http://dali.gotoacloud.top/Article/details/gt2xlfldxfg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.c1oappe.top/Article/details/gt2qhxsqhwo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gt2byhtyedi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gt2ajcbkumu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgebloax.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gt2gauqsqlw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gt2pyecwfer.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gt2syekkrqe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gt2otrjqqaj.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2nzsdfyak.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2vmqowxcm.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2auyoxccp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gt2rjlyexmt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2viwzwygm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gt2qlazrmxq.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gt2cvwaqngp.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdeyfeev.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ffomphos.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gt2pmzfvfst.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gt2nqfytthf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gt2clikreok.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2osmvtdzz.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2ocsfxntc.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecvlpsyg.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2maxqdvdf.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gt2qwtsusru.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2wupihhei.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gt2jhzxwbwx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gt2adabhrts.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gt2wpjpmprg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gt2jdkkagpz.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gt2sxcjwblt.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gt2ehyzrhea.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gt2loowaqio.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gt2mdfiuize.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gt2jgviunes.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gt2xddtnxon.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2tqvxbjtk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kswffovp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qomrwtzl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gt2uvyxjkuj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gt2klyislwu.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2thzbmowv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gt2zccnkoiv.html


<!-- 参考信息 -->