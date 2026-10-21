代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gtzyeysjva.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sxryk.cn/Article/details/gtasonzrda.html

[C08] 闭包
来源：http://dali.aizwys.cn/Article/details/gtgxvqjkto.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtthlawbgt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteuzcxkws.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gttxixjkjv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtjwkncqis.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaczpoctk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gtcgifelsd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daria6918.cn/Article/details/gtnpcvfufy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtroqmpykj.html

[C09] 递归
来源：http://dali.shanyushiyangtech.top/Article/details/gttvdldwip.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtkettfinw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gtckdotjqp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtakswwueq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtwiafasel.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gttsnvsftx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sufxvd.cn/Article/details/gtlhhnvsqh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtxdjqtqbg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gotoacloud.top/Article/details/gtrquzlhpc.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtjjrdecaj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gzhubu.top/Article/details/gtlnpksvhi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gtuztmmgks.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gtnhummpjd.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gteybshwxv.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gttpideday.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gtigceefof.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gtbswevslm.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtwgtlksok.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gtmrkgmyqt.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtzgyhoftz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gtsfkybjif.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcufekdvu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gtjbcoghlt.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gtgmxlcxtg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gzhubu.top/Article/details/gtodruxgia.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzpuoamr.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gtwtlcfnvx.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxmuumma.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gtrezagdqb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cdnleiting.top/Article/details/gtystnipyf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtyisloweb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtuerdeqtm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtzxlumfvj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258888.top/Article/details/gtlhsgrqtt.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtoaqsurls.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gthlncksbo.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gtsytvgfix.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtdenksusd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtqwujycrj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gtxmihksvn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtvtlhifae.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtetklkaef.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtghkezqht.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gtkmyaejxe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtjysmwolj.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gtikkbhmgc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gtmwiigdwp.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtekwkcxab.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtlhnvjtup.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gtbfwqgrwq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtfyqiqncw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gtxnkfktfv.html

Ruby: # 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gteqjzgswm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gtpnlfuhio.html

[C15] 解构 / 展开参数
来源：http://dali.snrcjt.cn/Article/details/gtjjydsorf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gtirgbilrn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gtothlfiso.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtsygwhyxq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynuvcagw.html

Java: // 无解构
来源：http://dali.hysaishi.cn/Article/details/gtwhkjaaaj.html

Go:   // 无解构
来源：http://dali.chenzaomai.com/Article/details/gthiocjimi.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gtsiaadobw.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtjrfxxzpz.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrikoschn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gtjhvegkdf.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gtnzhejqas.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gtxhxamyty.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gtbfxaotlu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fzhhl.top/Article/details/gtpiukavbf.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gtaasrfrvu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gtcmhsasom.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gtwzeucpni.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtnkjueuhb.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gtjnukbdia.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwxxewpun.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtodalrena.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xinyue.icu/Article/details/gtykctjzpo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtaqwiofzk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gtgvkdwsig.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gtficillhe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gteycxljdm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gtyswuwdyc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gtwsbgypjp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gtbpwlsidr.html

[D02] 追加元素到末尾
来源：http://dali.sysykeji.top/Article/details/gtdxdzghgp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gthljhewvz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygrugdoe.html

JS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtcqvlgqan.html

TS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtuwswxgtr.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtgjjufhcm.html

Go:   arr = append(arr, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtfakmhmww.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gtfmggpfwq.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gteklmhbit.html

[D03] 在指定位置插入元素
来源：http://dali.0kj1m.cn/Article/details/gthixdqcgl.html

Py:   arr.insert(0, 0)
来源：http://dali.gotoacloud.top/Article/details/gttnucbupw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtydjejfoc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gtkeymzwgy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gtqezuxeiv.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtuphhrlrv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gtktxyrnyb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gtusctjqeu.html

C#:   list.Insert(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtiylefpyv.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtehfjsdte.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cheryme.top/Article/details/gtbdfdjmsm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gtwyalvurb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtpduzifgc.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtktfwsvda.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gtgtimmkco.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtrltflabv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gtbujtnehx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtcoozqiob.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gttzeyllyy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtekgposyn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtzqmpsyme.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtrmwlmymd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gtstuzxces.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtxtrfhlnc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtlpmgiwcp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtfnxwuaqu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtqmxdsulp.html

[D06] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtqlbfbwac.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtgndqkxkw.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gtmnrmcjcj.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtzfqborfy.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gthgqkjexo.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gtzvhyulhk.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtwlikjwie.html

Ruby: arr.length; arr.size
来源：http://dali.nwbrower.top/Article/details/gtgnhgxuwz.html

C#:   list.Count;
来源：http://dali.cucudq.cn/Article/details/gtlnjcwmfu.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpgkyekn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gtclgqfmht.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbffcxlx.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtsyygyhla.html

TS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtwpogdlhm.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtdcqeoild.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gtkvfrlllg.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gtaikqnaxu.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtdqqyzpsr.html

[D08] 合并两个数组
来源：http://dali.xylfe.cn/Article/details/gtpmrkusjq.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtkqsdjvji.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gtodxjbecz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guowangkeji.top/Article/details/gtqhfhnjaq.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gtgnhpocnz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgfzy.top/Article/details/gtecmktrus.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gtsxvzyusy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gtfdfwxhvx.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtujuslzvb.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gtxpzkwlwp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtqnwnkqxa.html

PHP:  sort($arr);
来源：http://dali.fengsongda.top/Article/details/gtigvwyfqv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtohsijtxh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtjjyeiaqs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtoxwbdebs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtlzpveddc.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gttuvqhpft.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gtgcfliwrq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtrkylzyca.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrozucppg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtiawtevls.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtnxskzvqm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtymjumehx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gtbcjjynxr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtnpfpbiwc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtkoksxruk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gtrgfvxxyh.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gthmcumdix.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gtkxwmbjog.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtnnojrmgd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ppjwa.cn/Article/details/gtzdnqabcz.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gtlyukxnzq.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtoaklxcbp.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gtojjciyzs.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gtqskawoto.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gtxicagtty.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubkrcjpy.html

Py:   arr.index(x);  x in arr
来源：http://dali.daria6918.cn/Article/details/gtplifceko.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtfaljeowh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtbzawdotk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtknlmidjb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gtwegntjau.html

Go:   slices.Index(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtwjtokvnn.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gtwjmaeart.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gthvmwaibr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gttnuttvbx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoyepdcq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gtmzwdjxkj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtvvrabznx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtvohzbeua.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shuidangran.top/Article/details/gtuokovpgg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gtikvajuhr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shangyingyoupin.top/Article/details/gtlofjqxkq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gthozkylme.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gtlylfrebl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gtzymeqlmn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gthhlqqpqi.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtkljvbvzy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtcbmkforc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.haohaochexian.top/Article/details/gtmljxtlfg.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtrxcexsmw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtaymhfuhc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gtvqldqvbj.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtllufcdyf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtcxuxbpan.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpruydrxv.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gttnxzckbd.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtdqsbwfpt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gtvgyyjtjq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtlslkvfxw.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gtlfbgxtom.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtvujyvspw.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtebvyewgg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtupdbssed.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtjkhyomyp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtiquedbds.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtitpfanzd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangdashe.top/Article/details/gteeoxagqk.html

Go:   // 手写循环累加
来源：http://dali.snrcjt.cn/Article/details/gtyszflfbp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtaoxdzydm.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gtzpueqhwl.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtsjjoslvl.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtxpzwomhu.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gtnaahriga.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gthnlngltx.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gteeflzlwc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gtbmfzyrrb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtbcunucpx.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gtxzohcfes.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gthjkagqwd.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gtzmfwcluv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gtrslvffqj.html

PHP:  array_merge(...$nested);
来源：http://dali.yuxming.cn/Article/details/gthrvdzcvb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtvthujwey.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gtdxxxqbaf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtmktmvpio.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gtlbxdkkfj.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtdybxvnho.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtivgmffsd.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gtlpljestk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtigknnjzd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gtxbpxcaln.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtbgjduzig.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtzxwxqinz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpqrchax.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gttaxesvst.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gttplsllnv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gthmzggpqz.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gtlbfolljz.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gtadjekckn.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gttfijwldy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtntfsxfjr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gttaezltbu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtktqlbnuv.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtwvmbyyci.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gtiiwoiyst.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtergermyq.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gtkivbqnvg.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gtrgrgmhqc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gtrbbbxixg.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtyfhwwstc.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtwszcdqdx.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyunknjzp.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkwmobrfg.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtnzkhkddx.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtazqyttws.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxjkntqo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gtynijorsu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdjgsrrd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpvagbdc.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gtgjgnmtae.html

Java: new ArrayList<>(list);
来源：http://dali.yongpay.top/Article/details/gtzmcxxaav.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gtntozarvw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenlongwang.top/Article/details/gtdkhzfyem.html

C#:   new List<int>(list);
来源：http://dali.yueranfly.top/Article/details/gtmqbfezbp.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gtaipqimun.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gtbggivjpv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gtqymfxijb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtpmjklmmt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtiudxkkav.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gtozuymlea.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtkmkmqhbi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gtfbyvgrcb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gtqjbvuufp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gtkmvixucm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gtvqlvmwrz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtxpwkenuv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtmlkljzxk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwzhqlag.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gtbvclzbty.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtqgftfnvt.html


<!-- 参考信息 -->