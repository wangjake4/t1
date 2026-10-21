代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gtjnpodyzw.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gtmztoqoxs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhengqikj.top/Article/details/gtwjduzbxt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aizwys.cn/Article/details/gthxjhwoua.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gtyqvtlbjm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shzxlz.cn/Article/details/gtbdjrhkdi.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtfkchczur.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gtpcgkxmsx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gtonurlyqf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtvaeeflum.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtrtwwkinv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gtfoacwvcz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtggewmzrr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ppjwa.cn/Article/details/gtbvqaezvj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwudpskwj.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gtruubljeh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtbomugsss.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkozfatk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtihydxeok.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gtfwosjcfo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtbtkrphak.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gtpdwjmimb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtfqsunfdz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258888.top/Article/details/gtbkyvfuwn.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gtubmhsdqd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gtglvihnvv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shzxlz.cn/Article/details/gttktsvsfm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiylddfw.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gteyokwory.html

Java: 方法内为块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtkaygtftf.html

Go:   花括号块级作用域
来源：http://dali.yuanzhike.top/Article/details/gttvhrdazx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujfeirsw.html

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gtmudtfspv.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gtjlnucxal.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gtulzshzpb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.meibo888.top/Article/details/gtmwwftfoi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtiktbqywb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gtkrurwtfg.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gtwppszlep.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangtech.top/Article/details/gtciggudvp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gtbfslmapy.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtjznhpblu.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gttqbdinmd.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gtvgzejywx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gthckolhos.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtavwykiuf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtgkojnoob.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gtacvtmpuw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtojxtrwhy.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gtzrjbtesz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dashuyun.cn/Article/details/gthqkdjccv.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gtkifnulji.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gtzkwqoplr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtearonwoq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtfppbbnaz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtoxddiabq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtayvajrwa.html

Go:   func add(a, b int) int
来源：http://dali.jinqigfzy.top/Article/details/gtmsypdgel.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gtmmmfhuhm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gtinmshjpl.html

[C14] 泛型函数
来源：http://dali.yueranfly.top/Article/details/gtzlbzlxnz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqmxkpvh.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtojvmdbwb.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmckgdtt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqvwqett.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwetiifkl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuetiantiany.cn/Article/details/gtehdvtwfp.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtgkenrqah.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gtjkhrmxcl.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gtdmfnflgf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gtuqhoehbz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.0kj1m.cn/Article/details/gtvtkegppq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtkkjvrege.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gthgtgjgtz.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtjodytzzi.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gtrlkapqhg.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdaxydso.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gtzqciqcxg.html

[C16] 函数 / 方法重载
来源：http://dali.jqgfzy.top/Article/details/gtrawcufhh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aizwys.cn/Article/details/gtssipmcgc.html

PHP:  // 无重载
来源：http://dali.chenzaomai.com/Article/details/gtlyguxiti.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxuanxn.top/Article/details/gtfiaahhcn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gtgkcjjdna.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtwokrmbsw.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gtyfrzlgrt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gtfsaeodbr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxgabinhb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtgmahnfts.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtpwlazfqu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqgydbnuz.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtbnjxnfup.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gtsbgjwcvf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtzwjbtofz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtehrxgpfd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gtvjqbmdls.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tian-w.cn/Article/details/gtraowmvtv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gtsregxgqv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtufpugdym.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gtmnbjqrvs.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gtnoqlzkjg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shuidangran.top/Article/details/gtbykdswoz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.quarkkingdee.top/Article/details/gtwbstvwvh.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtkvphwuog.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gthhmgvaye.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gttjkuiuzi.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gtilxfbwvm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gtizoohdgw.html

C#:   list.Add(4);
来源：http://dali.xinyue.icu/Article/details/gtftqtodxj.html

[D03] 在指定位置插入元素
来源：http://dali.snrcjt.cn/Article/details/gtmhgeevko.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gtpkojcocu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tian-w.cn/Article/details/gtxrhlhcms.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gtwmkqilwp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtklvukvns.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtdrhevnzx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gtvqukyzcl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gtsdroflbi.html

C#:   list.Insert(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtvygernuk.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtxgfrcmvz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gtfgtvdcwg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gtkfyclzvi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gtchcabuvg.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gtwzagunpu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtqwgnxfxd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gtzjerurkz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtrohwockj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gtbnpdovjl.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gtmtdpedvb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtswigaxyj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbkqdwxb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtsypdqhrb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pengpengdd.cyou/Article/details/gtwrkmlqeg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtpwvcuaie.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtwypwxgvb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtnobylkbk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtopzxmlnl.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtpvqtrzan.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtwmoolziq.html

PHP:  count($arr);
来源：http://dali.nwbrower.top/Article/details/gtlmbffati.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtopzelrvn.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtdkysxnvp.html

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gtgeqvqivl.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtszhtywhj.html

Ruby: arr.length; arr.size
来源：http://dali.aizwys.cn/Article/details/gtvpfzgigy.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gthleuguff.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gtjyzglfah.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gtzcftwyeh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokcvlpwn.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtjpbhttbn.html

TS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtfuhiihbh.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtaxsbfmvd.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gtvozauevl.html

Ruby: arr[1, 3]
来源：http://dali.hnqzz.top/Article/details/gtjfsfgcij.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gtoslzprge.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtcitbvajr.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gtkzuifxle.html

PHP:  array_merge($a, $b);
来源：http://dali.haohaochexian.top/Article/details/gtwxikdtxr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gtdrhdlcev.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtvcfpuugb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjxunicr.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gtwffoysji.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gtkchbjesz.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtmkclcctw.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gteiczxjih.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtbgpelhnv.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gtzcuexaoh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtwyndboql.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gtzhzfvldd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.havefunace.top/Article/details/gtyhzaucru.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtjvzqdxfz.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gttxsvkdon.html

C#:   list.Sort();
来源：http://dali.sxryk.cn/Article/details/gtwpemnuly.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gtqxtkbxju.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gteprebiza.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gthehltcpc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtuxwwrduo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gtobfzijxr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gtrekfvxxx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gtagzexrku.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gtnseaauhx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gtsqwihoxa.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gtjbtiduwx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gtzuctqdbs.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtfhkgbepb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtciopvzsz.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gtxnsymums.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gtlupybvgx.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtkrznqhve.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtxfryttab.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gtfaglheyd.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtmnobcurz.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gtgouuwgmv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtvrfbrgtl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtaqogyxaa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtzubaazrt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtaaopfgak.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtnvnpsigl.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gthjqtzvvb.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gtyhgooriz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.bjfxy.top/Article/details/gtkrdqkhli.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtgobleznp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gtlivthtsl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtnviojgxn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtqjchksll.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gtldroohud.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gtwdfxldti.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvlzpght.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtgwskanlm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gtkcxvevoe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gtcpindkqc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ybcxt.top/Article/details/gtkwsgrvjj.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtrghbxolv.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtyddykkst.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtnoytfrcz.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gtllbgkuga.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gtragoakvf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gthanpvpqx.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gtlpplwfdn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtyzatdgsv.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtsvwkyzfu.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gthjdzpflo.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtcaulmnhp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gticnkmhda.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtvlrtqgeb.html

Ruby: arr.uniq
来源：http://dali.ybcxt.top/Article/details/gtwogmmnyr.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gtfxaeirvx.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbcfdqbm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtkvvvsmlg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtqvmcsurf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtbgwilpik.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtzsyozgyf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gteydiwtfu.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gtyvrwmddc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtjqfkpvmu.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gtctresvdu.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gtsijliyel.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtswwtqtws.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gtkneoncqr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gtfndpuezi.html

TS:   Math.max(...arr);
来源：http://dali.jqgfzy.top/Article/details/gtgyxovwwk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gtoswrhnzq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtnujwrggl.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gtqnczxhaz.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gtajoukcuv.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gtarzcefzl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gtzqmvvnai.html

PHP:  array_merge(...$nested);
来源：http://dali.9152youxi.cn/Article/details/gtbnjfgmuu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gtkecwdmkn.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gtmzhjxcqa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gtitjxdnyq.html

Go:   // 手写双层循环
来源：http://dali.xylfe.cn/Article/details/gtaqcusbwk.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtnjkxoclh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtkhjiflyp.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gtuglhpdrv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthewpcabq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gtjtnrwzrc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gtfmmrnffc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtegxqibjq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gtawtepbxy.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gtqktralyt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gtydhhlpcl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gtwgxnkupw.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gtimwplnrj.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gtbmpxbtee.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gtcvgvcuvg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtvgrxfabt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtbmjzwisa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gteobeewta.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gtijylepbw.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvedeybsm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtnuxzvrci.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gthmqjzfzp.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtdbpanqgb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gtknokllwk.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtomhypugz.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtdbzytegn.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtjplgxoqk.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtqxweckmw.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtcbdswxng.html

C#:   list.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtlrjqnzkm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gtqpawlvbn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtbzzhqnao.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtsrvfxotd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ydzc1.top/Article/details/gtnoxwquqb.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gtcjpyoxym.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gtivcicgxm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtholgwzhj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gtzcztvqod.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gtzupbkmvr.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gtrqulatfz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gthagiteck.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gtvijophex.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtwkbyogmb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtaglhdrfe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gtawfvnjke.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtapgiydno.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gtfuzyzhmo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtxtirynqo.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gtkglreysm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gthbsdcnvb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtyqdxlzei.html


<!-- 参考信息 -->